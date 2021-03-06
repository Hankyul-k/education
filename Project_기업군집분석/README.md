<!-- 프로젝트명, 프로젝트 소개, 설치 방법, 사용 예제, 개발 환경 설정 방법, 기여 방법, 변경 로그, 라이센스 및 작성자 정보를 포함해야 한다. -->


# 📃 기업 군집 분석 프로젝트 

기업의 정형·비정형 데이터를 분석해 기업을 군집하고자 함.
<br/><br/>

## 프로젝트 소개
- KOSPI 20개 기업을 선정
- 주가 데이터와 뉴스 데이터(TF-IDF 적용)로 기업을 군집 후 결과 비교
- 주가 데이터(시계열 데이터)로 군집 시, 유사한 주가 흐름을 가진 기업을 확인할 수 있음.
- 군집을 비교해 뉴스와 주가 간 관계를 확인하고자 함.
<br/><br/>

## 프로젝트 수행 기간
2021.07.05 - 2021.08.06
<br/><br/>

## 개발 과정
프로젝트 기획 및 방법론 선정 → 데이터 수집 → 데이터 전처리 → 군집 → 결과 분석 → 데이터 시각화 → 결과 도출<br/>
<b>※</b> 데이터 전처리 ~ 데이터 시각화 반복하여 단계적으로 결과 개선
<br/><br/>

## 데이터 수집
- 수치형 데이터
    - 기업 재무제표
        - Dart
    - 증권데이터 :
        - kiwoomAPI
        - Finance DataReader
- 비정형 데이터
    - 뉴스데이터 : 
      - Crawling (Bigkinds/네이버금융 뉴스)
      - Bigkinds 제공 데이터
<br/><br/>

<!-- # 분석 과정 -->


## 개발 환경
- Pycharm C.E. 2021.2.3
- Jupyter LAB
- Python 3.8 64bit
- Python 3.7 32bit

<!-- ## 참고 자료 -->
