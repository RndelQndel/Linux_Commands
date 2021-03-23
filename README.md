# Linux_Commands
List Linux Commands

# useradd
__useradd [ user_account ]__  
__useradd [ options ] [ user_account ]__  
  
user를 추가한다  
add user  
  
useradd options  
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-u | 사용자 계졍 UID | user account UID
-g | 사용자 계정 GID | user account GID
-G | 사용자 계정의 2차 그룹 GID | user account second GID
-d | 사용자의 홈 디렉터리 지정 | set user's Home directory
-e | 사용자 계정 만료일 지정 | set user account expire date
-f | 사용자 계정 비밀번호 유효일자 지정 | set user password expired date
-s | 로그인 시 사용할 기본 셀(SHELL) 지정 | set user's login shell
-M | 사용자 홈 디렉터리를 생성하지 않음 | No create home
-c | 주석 | comment

# usermod
__usermod [ options ] [ user_account ]__  
  
user 속성을 변경한다    
Change user setting  
  
usermod options
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-u | 사용자 계정 UID 생성 | create user account UID
-g | 사용자 계정의 1차 그룹 GID 지정 | set user account's first GID
-G | 사용자 계정의 2차 그룹 GID 지정 | set user account's second GID
-c | 주석 | comment
-d | 사용자 홈 디렉터리를 지정 | set user's Home directory
-e | 사용자 계정 만료일 지정 | set user account expire date
-f | 사용자 계정 비밀번호 유효일자 지정 | set user password expired date
-s | 로그인할 때 사용할 기본 셀(SHELL) 지정 | set user's login shell

# userdel
__userdel [ user_account ]__  
  
user를 삭제한다  
delete user  
  


# groupadd
__groupadd [ group_name ]__  
__groupadd [ options ] [ group_name ]__  
  
group을 추가한다  
add group  
  
groupadd options
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-g | 그룹의 GID를 지정 | set group GID
-r | 0에서 499까지 GID를 자동 지정 | auto set GID ( 0 ~ 499 )

# groupmod
__groupmod [ option ] [ group_name ]__  
  
group 속성을 변경한다.  
Change group setting  
  
groupmod options
Option | Description(Kor) | Description(Eng)
---- | ---- | ----
-g | 그룹의 GID를 지정 | set group GID
-r | 0에서 499까지 GID를 자동 지정 | auto set GID ( 0 ~ 499 )

# groupdel
__groupdel [ group_name ]__  
  
group을 삭제한다.  
delete group.  

# Test
