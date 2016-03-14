# CentOS 에서 Chrome 설치 하기

# 0. 이 글은
*  CentOS 에서 Chrome 을 사용을 하시는 분들을 위한 글 입니다.
*  이 가이드를 통해 Chrome 을 설치하실 수 있습니다.
*  가이드를 통해 리눅스에서 패캐지 설치 방법을 익힐 수 있습니다.
*  관리자 권한이 필요합니다.
*  64비트에 최적화 되어 있습니다.

# 1. 콘솔 창에서 Chrome 에 필요한 패캐지 설치
```
sudo yum install lsb libXss.so.1*
```
# 2. Chrome RPM 파일 다운로드
```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm
```
# 3. RPM 파일 설치
```
sudo rpm -ivh google-*.rpm
```
# 4. 설치 완료
*  크롬을 실행하여 정상적으로 실행 되는지 Test 실행을 해보시기 바랍니다.
*  Windows 에서 사용하던 Chrome 과 똑같은 환경에서 인터넷 서핑을 하실 수 있습니다.
*  UI가 조금씩 다를 수 있지만 기능은 모두 있습니다.
*  리눅스에서 뱅킹을 하고자 한다면 윈도우 사용을 권해 드립니다.
