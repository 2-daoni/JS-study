## lodash를 이용한 Throttle, Debounce
<hr/>
![debounce](https://file.notion.so/f/s/9ee22101-f75c-4a9d-982a-90e8c0d36c5d/Untitled.png?id=55fe5df6-587e-4546-a57a-a5dcace0b13f&table=block&spaceId=eaa5b4d0-f521-47bb-b1c7-7cbad4f5c700&expirationTimestamp=1680227786453&signature=h5bQhEi-fvILHkVkiYfvp22C3Q15Rumz-yrw-q3Xgb8&downloadName=Untitled.png)

### [Throttle]
: _.<span style='color:red'>throttle</span>(func, [wait=0], [options={}])
<br/>
1. [options.leading=true]
<br/>
: true면 첫 발생 이벤트는 일단 실행한다
<br/>
2. [options.trailing=true]
<br/>
: true면 마지막 이벤트 발생 후 wait 만큼 지난 후 함수 실행함

### [Debounce]
:_.<span style='color:red'>debounce</span>(func, [wait=0], [options={}])
<br/>
1. [options.leading=true]
<br/>
: true면 첫 발생 이벤트는 일단 실행한다
<br/>
2. [options.trailing=true]
<br/>
: true면 마지막 이벤트 발생 후 wait 만큼 지난 후 함수 실행함
3. [options.maxWait]
<br/>
: 함수 호출이 딜레이 될 수 있는 maximum 시간
<br/>
-> maxWait 설정시 wait 만큼 debounce 딜레이가 적용되고, maxWait만큼 이벤트 최대 호출 주기가 적용되기 때문에 debounce + throttle 합친 것 처럼 동작한다.


