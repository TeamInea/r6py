# R6S 디스코드 봇
[R6SStats](https://r6stats.com/)에서 전적 데이터를 가져와 디스코드에 보여주는 봇입니다.

## Self Hosting
#### 파이썬 버전

이 봇은 파이썬 3.6.8을 기준으로 제작되었습니다

~~~
Python 3.6.8 (tags/v3.6.8:3c6b436a57, Dec 23 2018, 23:31:17) [MSC v.1916 32 bit (Intel)] on win32
~~~

#### 모듈

`requirements.txt`을 통하여 필요한 모듈을 설지하실 수 있습니다.

```
pip install -r requirements.txt
```

#### 봇 토큰
`bot.py` 파일을 텍스트 편집기로 여시면 20번째 줄에 아래와 같이 있습니다.

```python
TOKEN = 'Bot Token'
```

`Bot Toekn` 부분을 봇 토큰 값으로 바꾸시면 됩니다.

## 명령어

~~~
!r6h : 봇 정보&도움말 보기
!r6s : 자신의 디코 서버닉네임의 전체 전적보기
!r6s <닉네임> : 전체 전적보기
!r6v : 레인보우 식스 시즈 서버 상태 확인
~~~

명령어는 버전 업데이트를 통하여 추가 될 수 있습니다.



## 라이센스

GNU General Public License V3.0 을 따릅니다.
