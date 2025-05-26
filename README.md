# System Administration Configurations

## 설명
- 리눅스마스터 1급/정보보안기사 학습, 그리고 인프라 관리 과정에서 습득한 이론을 바탕으로, 실제 시스템에 적용 가능한 설정 파일을 작성했습니다.
- 각 설정은 보안성/실용성을 고려하여 작성되었습니다.

## 디렉터리 구조
- dns: DNS 서버 설정
    - named.conf
- dotfiles: 개발 환경 설정
    - .vimrc, .bashrc
- file-sharing: FTP, Samba 서버 설정
    - vsftpd.conf, smb.conf
- nginx: Nginx 웹서버 설정
    - nginx.conf
- security: TCP Wrapper, SSH 보안 설정
    - hosts.allow, hosts.deny, sshd_config

## 중점사항
- 포트 변경, 접근 제어, 인증 강화 등 기본 보안 설정
- 화이트리스트 방식 접근 제어
- DDOS 공격 방지
