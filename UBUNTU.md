# ubuntu
- 참고 서적 : 이것이 우분투 리눅스다.
- 사용자 관리와 파일 속성
  - /etc/passwd, /etc/shadow, /etc/group 
  - inode : 리눅스/유닉스의 파일 시스템에서 사용하는 자료구조
  - Symbolic link는 inode를 새로 만들고 Hard link는 같은 inode를 사용한다. 
    Hard link는 원본 파일을 삭제 해도 문제 없음.
- RAID(Redundant Array of Independent Disk)
  - RAID Linear, RAID0(fast), RAID1(mirror), RAID5(parity 1), RAID6(parity 2)
  - RAID 구성 확인 mdadm --detail --scan
