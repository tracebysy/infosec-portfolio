# 🔐 파일 권한 (Permission)

## 📌 개요
리눅스에서는 파일과 디렉토리에 대한 접근 권한을 설정하여 보안을 관리한다.

---

## 🧠 권한 구조

### -rwxr-xr-x
-> 의미
첫 글자	파일 타입 (-: 파일, d: 디렉토리)
- rwx	소유자 (User)
- r-x	그룹 (Group)
- r-x	기타 사용자 (Other)

-> 권한 숫자 표현 값	의미
- 4	read (r)
- 2	write (w)
- 1	execute (x)

예: chmod 755 file
7 = rwx
5 = r-x
5 = r-x

### ⚙️ 주요 명령어
- chmod (권한 변경)
chmod 755 file
chmod u+x file
- chown (소유자 변경)
chown user file
chown user:group file

💡 중요 포인트
실행 권한(x)이 있어야 프로그램 실행 가능
잘못된 권한 설정은 보안 취약점 발생

🧠 한 줄 정리
파일 권한은 리눅스 보안의 기본 요소이다.
