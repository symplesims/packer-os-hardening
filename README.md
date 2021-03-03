# packer-os-hardening
packer ansible os-hardening


## 기본 관리
```
timezone 설정
Time Server 설정
기본 편집기 설정
bash prompt
기본 패키지 설치
```


## 계정 관리
```
패스워드 최소 길이 설정
패스워드 최소 사용기간 설정
패스워드 최대 사용 기간 설정
패스워드 복잡성 설정 체크
패스워드 중복 사용 금지 설정
계정 잠금 임계값 설정 체크
su 사용 제한 체크
불필요한 계정/그룹 체크
UID/GID 0 체크
sudo 사용자 체크
Bash Session Timeout 설정 체크
사용자 shell 점검
```


## 파일 및 디렉토리 관리
```
/etc/passwd* 파일의 소유자/퍼미션 체크
/etc/group* 파일의 소유자/퍼미션 체크
/etc/shadow* 파일의 소유자/퍼미션 체크
/etc/gshadow* 파일의 소유자/퍼미션 체크
UMASK 설정 체크
관리자 명령어 권한 체크
SUID, SGID, Sticky bit 설정 파일 리스팅
```

## 서비스 관리
```
processlist, df, LISTEN 포트 리스팅
Anonymous FTP 비활성화 체크
Apache ServerTokens, ServerSignature, Indexes 체크
apache, tomcat 의 구동 계정 체크
ssh 포트 번호 체크
root 사용자 ssh 원격 접속 체크
로그온 시 경고 메시지 체크
기본 커널 튜닝
```

## 로그 관리
```
Bash HISTSIZE, HISTFILESIZE, HISTTIMEFORMAT 체크
bash log 별도 파일 보관 유무 체크
last, lastb, dmesg 접근 권한 체크
logrotate 설정 유무 체크
```

## 추가 패키지 설치
```
AWS System Manager
AWS CLI
lsof
htop
```

* Ansible 의 이해가 필요 하면 [ansible-guide](./docs/ansible-guide.md) 를 참고 하세요.

