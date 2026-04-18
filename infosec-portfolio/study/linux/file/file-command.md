# 📂 파일 및 디렉토리 명령어

## 📌 개요
리눅스에서 파일과 디렉토리를 생성, 조회, 복사, 삭제하기 위한 기본 명령어들이다.

---

## ⚙️ 주요 명령어

### 📁 ls (목록 조회)
ls
ls -l
ls -a
-l : 상세 정보 출력
-a : 숨김 파일 포함

### 📁 pwd (현재 경로 확인)
pwd

### 📁 cd (디렉토리 이동)
cd /home
cd ..
cd ~

### 📁 mkdir (디렉토리 생성)
mkdir test
mkdir -p a/b/c

### 📁 cp (파일 복사)
cp file1 file2
cp -r dir1 dir2

### 📁 mv (이동 / 이름 변경)
mv file1 file2
mv file /home/

### 📁 rm (삭제)
rm file
rm -r dir
rm -rf *
⚠️ rm -rf는 매우 위험 (복구 불가)

>> 💡 한 줄 정리

파일과 디렉토리를 관리하는 기본 명령어는 리눅스 사용의 핵심이다.
