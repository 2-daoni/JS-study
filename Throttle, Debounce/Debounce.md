## Debounce
<hr/>
: 연속으로 호출되는 함수들 중 마지막에 호출되는 함수만 실행되도록 하는 것
<br/>
-> 첫 함수 호출 후 연이어 호출되는 함수들 중 가장 마지막 함수를 호출하고 일정시간 후까지 호출이 안되면 그 함수를 실행시킨다.

* 사용
    * 검색 - ㄷ 디 딥 디바 디방 디바우 디바운 디바운ㅅ 디바운스 (디바운스를 검색하기 위해 api가 9번 호출된다)
    * 호출되는 이벤트 콜백 중 마지막에 호출한 것만 실행되어 트래픽 낭비를 막을 수 있다.

![debounce](https://t1.daumcdn.net/cfile/tistory/994614365C17654319?original)
