# Linux
## Tips
### source
```
source /etc/profile
```
source 명령어는 환경변수 재설정 명령어로 bash 내부 명령어다. 실행 파일이 따로 존재하지 않는다. bash가 실행상태에서 실행이 가능하다.
```
/etc/profile.d : 디렉토리 안에 모든 쉘스크립트를 실행한다. 
```
### 포트포워드
```
iptables -t nat -A POSTROUTING -j MASQUERADE 
iptables -t nat -A PREROUTING -p tcp -i eth0 --dport [FROM PORT] -j DNAT —to [IP]:[TO PORT] 
```


## study 순서
1. 파일구조
1. boot sequence 
1. 기본 명령어 
