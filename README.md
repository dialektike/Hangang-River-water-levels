# Hangang River water levels (한강 수위 자료)

## 개요

자료 분석을 하고자 자료 범위가 큰 자료를 찾아봤지만, 적당한 것이 없었습니다. [R](https://www.r-project.org/)을 공부하면서 보니, 거기에는 나일강에 대한 수위 자료가 공개되어 있었습니다. 여기서 힌트를 갖고 한강 수위 자료를 찾아보게 되었습니다. 한강의 공식적인 수위는 한강 대교의 수위표를 기준으로 정합니다. 평균수위는 한강대교 양수표기준으로 수위 1,025m, 한강 고수부지 침수가 시작되는 지정수위는 4.5m, 경계수위는 8.5m, 위험수위는 10.5m입니다( [홍수시 한강수위를 알고 싶습니다. | 서울시 정보소통광장](http://opengov.seoul.go.kr/civilappeal/2896791) 참고). 이처럼 한강 수위는 기준은 한강대교 수위를 기준으로 합니다. 따라서 저 또한 한강 수위를 조사해서 자료로 만들기로 결정했습니다. 

## 목적

여기 자료들은 자료 분석 교육을 목적으로 아래 참고 자료 항목을 통해서 수집된 것들입니다. 상업적으로 사용하기 위해서 만들어진 자료가 결코 아닙니다.

## 주의할 점

실제 파일을 받아서 처리한 것이 아니기 때문에 자료의 신뢰도를 논문에 쓸 만큼은 보증할 수 없습니다. 물론 최대한 실수를 하지 않고 처리하려고 했기 때문에 원 자료가 문제가 없다면, 여기에 있는 자료 또한 거의 문제가 없을 것입니다.
## 자료 출처 링크

자료 출처 링크는 다음과 같다.

http://www.wamis.go.kr/WKW/WL_HRDATA.ASPX?code=1018683&name=%BC%AD%BF%EF%BD%C3(%C7%D1%B0%AD%B4%EB%B1%B3)&gvcd=01&Search=1&Sort=1&Basin=1&Oper=N&ObsKd=-1&OrgMng=-1

## 참고 링크

1. 서울시(한강대교) 관측소 제원 현황입니다.
http://www.wamis.go.kr/wkw/WL_OBSINFO.ASPX?code=1018683&name=%BC%AD%BF%EF%BD%C3(%C7%D1%B0%AD%B4%EB%B1%B3)&gvcd=01&Search=1&Sort=1&Basin=1&Oper=N&ObsKd=-1&OrgMng=-1
2. 실시간 한강 하천 수위
	* [하천수위 - 서울안전누리](http://safecity.seoul.go.kr:8070/scmyn_cf/flood/riverGauge.do)
