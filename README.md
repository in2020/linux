# Linux
## Tips
### bash source
```
source /etc/profile
```
source 명령어는 환경변수 재설정 명령어로 bash 내부 명령어다. 실행 파일이 따로 존재하지 않는다. bash가 실행상태에서 실행이 가능하다.
### profile.d
/etc/profile.d 경로의 디렉토리.  
디렉토리 안에 모든 쉘스크립트(*.sh)를 실행한다. 
### 포트포워드
```
iptables -t nat -A POSTROUTING -j MASQUERADE 
iptables -t nat -A PREROUTING -p tcp -i eth0 --dport [FROM PORT] -j DNAT —to [IP]:[TO PORT] 
```
```
ssh -i [key file] [user]@[host] -f -p 22 -N -L 3306:127.0.0.1:3306
```

## study 순서
1. 파일구조
1. boot sequence 
1. 기본 명령어 

## directories space
```
du -sh *
```
