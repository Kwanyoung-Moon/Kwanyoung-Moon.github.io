# KOSPI 일별 주가 다운로드 받기

### 1. KRX 증권거래소 크롤링 시도
+ 기업명 선택하는 부분 코딩이 어려워서 포기
  + html 문법을 좀더 공부해야 함
  + 기업명 리스트에서 드래그 - guru99에서 grid 드래그에 관한 내용이 있었음

+ csv 파일을 저장할때 '다른 이름으로 저장'이 가능한가?
  + 이전 학기에 selenium으로 네이버 맞춤법 검사기를 돌렸던 팀이 있었으니 가능할 듯 한데... 이 부분은 일단 남겨둠


### 2. pandas_datareader 패키지
+ 참고자료
  + ['파이썬으로 배우는 알고리즘 트레이딩'](https://wikidocs.net/4369)
  + [Pandas를 이용한  Naver 금융에서 주식데이터 가져오기](https://excelsior-cjh.tistory.com/109)
    + KRX에서 종목코드 다운로드 받는 방법
    + 네이버 금융 크롤링은 수행하지 않았음

+ 추후에 확인할 부분
  + pandas_datareader에서 Yahoo Finance 대신 Google Finance가 대세인 이유
  + Google API가 필요한지 여부 
  + Google Finance 이용 시 종목코드 입력 format
   
+ my experience
  + 일단 예제에서 Yahoo를 사용하는 경우가 많아 Yahoo로 다운로드 받았는데 몇몇 기업들은 2015~2019 데이터를 요청하였으나 2개월치만 다운로드 받아지는 등의 오류가 있음
  + 당장은 자료를 온전하게 구하는 것보다 fda 실습이 목적이니 패스
