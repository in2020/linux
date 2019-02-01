# ubuntu
- 참고 서적 : 이것이 우분투 리눅스다.
- 사용자 관리와 파일 속성
  - /etc/passwd, /etc/shadow, /etc/group 
  - /etc/group : sudo, daemon등 group에 사용자 추가하여 사용자 권한 관리
    _ 그룹의 사용처가 2개로 이해된다 파일에 지정하는 그룹과 특정 권한을 위한 그룹
    - 생각해 보니 사용자에 그룹을 지정하는데 그룹에서도 사용자를 지정하네.. 
  - inode : 리눅스/유닉스의 파일 시스템에서 사용하는 자료구조
  - Symbolic link는 inode를 새로 만들고 Hard link는 같은 inode를 사용한다. 
    Hard link는 원본 파일을 삭제 해도 문제 없음.
- 파티션, 파일시스템, 볼륨, 마운트
- LVM(Logical Volume Manager)
- RAID(Redundant Array of Independent Disk)
  - RAID Linear, RAID0(fast), RAID1(mirror), RAID5(parity 1), RAID6(parity 2)
  - RAID 구성 확인 mdadm --detail --scan
