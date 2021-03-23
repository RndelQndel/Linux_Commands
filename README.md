# Linux_Commands
List Linux Commands

# useradd
useradd [ user_account ]  
useradd [ options ] [ user_account ]  
useradd options  
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-u | 사용자 계졍 UID | user account UID
-g | 사용자 계정 GID | user account GID
-G | 사용자 계정의 2차 그룹 GID | user account second GID
-d | 사용자의 홈 디렉터리 지정 | set user's Home directory
-e | 사용자 계정 만료일 지정 | set user account expire date
-f | 사용자 계정 유효일자 지정 | set user password expired date
-s | 로그인 시 사용할 기본 셀(SHELL) 지정 | set user's login shell
-M | 사용자 홈 디렉터리를 생성하지 않음 | No create home
-c | 주석 | comment

# usermod
usermod [ options ] [ user_account ]  
usermod options
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-u | 사용자 계정 UID 생성 | create user account UID
