# ✏KBO_Income_Prediction

--------------
 20200314~20200405\
 WITH [[조한별]](https://github.com/STAR3073)
 
----------------

###  Summary
새로운 시즌이 시작하기 전, 선수와 구단은 연봉협상을 하게 된다. 
당연히 선수는 가급적 많은 액수를 지급받길 원하고 구단은 가급적 적은 액수를 지급하길 원하다 보니 협상과정에서 서로 불편해지는 상황이 나오는 것은 이상하지 않다. 
이러한 상황속에서 최근까지도 선수들보다 구단이 유리한 쪽으로 협상이 이루어져왔다. 하지만 야구가 점점 발전해가면서 타율, 출루율과 같은 기존 클래식 스탯뿐만 아니라 
WRC+, WAR 등 여러가지 기록들이 조명받게 되면서 연봉산정 방식이 점점 바뀌고 있다. 
따라서 그러한 기록들을 반영하여 2021년 KBO 타자들의 적정 연봉은 얼마인가를 예상해보고자 한다.

-----------------

### Data
크롤링 된 데이터는 모두 KBO사이트에서 크롤링 해와 진행하였다.
KBO Data Site- (http://www.statiz.co.kr/main.php)
- 선수 기본 데이터 크롤링[[CODE]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/code/Statiz_All_Season_Crawling.ipynb)
[[Dataset]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/data/data_1982_2020.csv)

- 외국인 선수 이름 크롤링[[CODE]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/code/Foreigner_Crawling.ipynb)
[[Dataset]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/data/foreigner_1982_2020.csv)

- 수입 데이터 크롤링[[CODE]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/code/Income_Crawling.ipynb)
[[Dataset]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/data/income.csv)

- 전처리 및 모델링[[CODE]](https://github.com/I-SUBIN/KBO_Income_Prediction/blob/master/code/Income_Prediction.ipynb)



