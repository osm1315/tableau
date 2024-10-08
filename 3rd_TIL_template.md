# Third Study Week

- 20강: [파이와 도넛차트](#20강-파이와-도넛차트)

- 21강: [워드와 버블차트](#21강-워드와-버블차트)

- 22강: [이중축과 결합축](#22강-이중축과-결합축)

- 23강: [분산형 차트](#23강-분산형-차트)

- 24강: [히스토그램](#24강-히스토그램)

- 25강: [박스플롯](#25강-박스플롯)

- 26강: [영역차트](#26강-영역차트)

- 27강: [간트차트](#27강-간트차트)

- 28강: [필터](#28강-필터)

- 29강: [그룹](#29강-그룹)


- 문제1 : [문제1](#문제1)

- 문제2 : [문제2](#문제2)

- 참고자료 : [참고자료](#참고-자료)



## Study Schedule

| 강의 범위     | 강의 이수 여부 | 링크                                                                                                        |
|--------------|---------|-----------------------------------------------------------------------------------------------------------|
| 1~9강        |  ✅      | [링크](https://youtu.be/3ovkUe-TP1w?si=CRjj99Qm300unSWt)       |
| 10~19강      | ✅      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=75)       |
| 20~29강      | ✅      | [링크](https://www.youtube.com/watch?v=Qcl4l6p-gHM)      |
| 30~39강      | 🍽️      | [링크](https://www.youtube.com/watch?v=e6J0Ljd6h44&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=55)       |
| 40~49강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=45)       |
| 50~59강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=35)       |
| 60~69강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=25)       |
| 70~79강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=15)       |
| 80~89강      | 🍽️      | [링크](https://www.youtube.com/watch?v=AXkaUrJs-Ko&list=PL87tgIIryGsa5vdz6MsaOEF8PK-YqK3fz&index=5)        |


<!-- 여기까진 그대로 둬 주세요-->
<!-- 이 안에 들어오는 텍스트는 주석입니다. -->

# Third Study Week

## 20강: 파이와 도넛차트
<!-- 파이와 도넛차트에 관해 배우게 된 점을 적어주세요 -->
- 전체에 대한 비율 표시
- 비율과 총합계를 동시에 보기 위해 이중축을 활용한 도넛차트 이용

> **🧞‍♀️ 도넛차트를 생성하는 법을 기록해주세요.**
```
1. 열 선반 더블클릭하여 0 입력 -> 임의의 축 생성
2. 선반에 만든 필드를 ctrl + 드래그 -> 두개의 원 생성
3. 두번째 원에 마크에 포함된 값 빼고 레이블에 합계 넣기
4. 사이즈 조정
5. 열 선반 두번째 필드에서 이중축 선택
+ 시트에서 마우스 우클릭 -> 서식 -> 상단의 격자무늬 -> 행, 열 구분선 없음으로 변경 -> 삼선 아이콘 -> 영 기준선 없음으로 변경 -> 시트에서 축 선택하고 마우스 우클릭 -> 머리글 표시 해제
```

## 21강: 워드와 버블차트
<!-- 워드와 버블차트에 관해 배우게 된 점을 적어주세요 -->
- 버블차트: 수치적 데이터를 원의 크기로 표현
- 워드클라우드: 문서 내에서 등장하는 키워드가 얼마나 자주 등장하는지를 텍스트 크기로 표현
- 카운트할 컬럼을 마우스 우클릭으로 크기 마크에 넣어 카운트 선택 -> 레이블 마크에도 넣기 -> 마크 자동을 텍스트로 변경

## 22강: 이중축과 결합축
<!-- 이중축과 결합축에 관해 배우게 된 점을 적어주세요 -->
- 이중축: 하나의 뷰어 안에서 축을 이중으로 사용하는 차트 -> 마크를 각각의 축에 개별적으로 적용 가능
- 결합축: 하나의 축을 공유하는 차트, 축을 공유하는 측정값을 필요에 따라 추가 가능, 가장 큰 범위의 축 공유
    - 표현하려는 다른 컬럼을 라인 그래프 왼쪽 축으로 초록색 박스가 생길때까지 끌어오면 생성 가능

## 23강: 분산형 차트
<!-- 분산형 차트에 관해 배우게 된 점을 적어주세요 -->
- 파라미터 간의 상관관계를 파악하는데 유용
- 왼쪽 상단 분석 -> 모델의 추세선을 시트로 드래그 -> 선형에 드랍
- 추세선은 전체 추세선, 범주별 추세선 사용 가능
    - 이중축 활용하면 같이 볼 수 있음
    - 열 선반 필드 복사 -> 추세선 우클릭 -> 모든 추세선 편집 -> 범주 선택 -> 열 선반 필드에서 이중축 선택 -> 머리글 해제

## 24강: 히스토그램
<!-- 히스토그램에 관해 배우게 된 점을 적어주세요 -->
- 연속형 측정값을 범위 혹은 구간차원으로 그룹화하여 수치데이터의 빈도를 분포형태를 표시(양적 데이터)
- 막대그래프: 불연속형 여러 범주의 데이터를 비교
- 차원 필드 없이 측정값만으로 그래프를 그릴때 주로 사용
- 구간차원: 일정한 크기의 포켓을 만들어 그 안에 값을 담아 표현시키기위한 도구
- 컬럼을 열 선반에 올리고 히스토그램으로 표현방식을 바꾸면 태블로 내부에서 3가지 작업이 자동 수행
    - 뷰가 연속형 세로 막대를 표시하도록 표현 
    - 열 선반에 배치하여 합계로 집계되었던 측정값이 연속형의 수익 구간 차원으로 변경 
    - 측정값이 행 선반으로 이동되고 집계가 합계에서 카운트로 변경
- 컬럼(구간차원) 우클릭 -> 편집 -> 값 변경: 구간차원의 값 크기 변경 가능
- 축 편집 -> 눈금에서 로그 활성화하면 최소최댓값의 극단적 표현 완화 가능

## 25강: 박스플롯
<!-- 박스플롯에 관해 배우게 된 점을 적어주세요 -->

## 26강: 영역차트
<!-- 영역차트에 관해 배우게 된 점을 적어주세요 -->
- 라인과 축 사이의 공간이 색상으로 채워진 라인차트
- 연속형 데이터의 누계를 표현

## 27강: 간트차트
<!-- 간트차트에 관해 배우게 된 점을 적어주세요 -->
- 시간 경과에 따른 기간을 시각화하는데 사용
- 값이 시간인 필드를 크기 마크에 넣기
- 기간은 합계가 아닌 평균으로 -> 자동을 간트차트로 

## 계산 필드 만들기
상단 툴바의 분석 -> 계산된 필드 만들기 -> 이름 지정 -> 두날짜간의 차이를 변환하는 함수: DATEDIFF(), 테이블에서 컬럼 끌고 오기 -> 생성

## 28강: 필터
<!-- 필터에 관해 배우게 된 점을 적어주세요 -->
- 데이터를 라이브가 아닌 추출로 연결해 필터링한 데이터 저장하고 분석 가능
- 라이브 연결에서도 필터 추가 가능
- 컨텍스트 필터: 필터 중 상위 필터, 여러가지 필터를 사용할 경우 다른 필터가 컨텍스트 필터에 종속되어 작동
    - 우선적으로 적용하고자 하는 필터를 우클릭 -> 컨텍스트에 추가
    - 종속필터를 필터 선반에 두기 전에 컨텍스트 필터를 먼저 설정해야 쿼리 속도 향상

## 29강: 그룹
<!-- 그룹에 관해 배우게 된 점을 적어주세요 -->
- 수동으로 필드에 있는 항목들을 묶을 수 있고 데이터 원본에 없는 사용자 지정 그룹 필드 생성 가능
- 뷰에서 그룹 만들기
    - 뷰에서 드래그하고 마우스 우클릭 -> 그룹 선택 -> 데이터 필드에 새 필드 추가됨 -> 자동으로 색상 구분 
- 항목별로 묶을 필드를 선택해서 만들기
    - 컬럼 마우스 우클릭 -> 만들기 -> 그룹 -> 그룹필드를 색상 마크에 드래그



## 문제 1.

```js
유정이는 superstore 데이터셋에서 '주문' 테이블을 보고 있습니다.
1) 국가/지역 - 시/도- 도시 의 계층을 생성했습니다. 계층 이름은 '위치'로 설정하겠습니다.
2) 날짜의 데이터 타입을 '날짜'로 바꾸었습니다.

코로나 시기의 도시별 매출 top10을 확인하고자
1) 배송 날짜가 코로나시기인 2021년, 2022년에 해당하는 데이터를 필터링했고
2) 위치 계층을 행으로 설정해 펼쳐두었습니다.
이때, 매출의 합계가 TOP 10인 도시들만을 보았습니다.
```

![image-2.png](https://github.com/yousrchive/tableau/blob/main/study/img/1st%20study/image-4.png?raw=true)

```
겉보기에는 전체 10개로, 잘 나온 결과처럼 보입니다. 그러나 유정이는 치명적인 실수를 저질렀습니다.
오늘 배운 '컨텍스트 필터'의 내용을 고려하여 올바른 풀이 및 결과를 구해주세요.
```

```
배송 날짜가 2021,2022년인 데이터가 우선적으로 고려되어야 하기 때문에 해당 필터를 컨텍스트 필터로 설정해야합니다
```
![문제1](./images/study3/스크린샷%202024-09-26%20오전%201.49.08.png)

<!-- DArt-B superstore가 아닌 개인 superstore 파일을 사용했다면 값이 다르게 표시될 수 있습니다.-->

## 문제 2.

```js
태영이는 관심이 있는 제품사들이 있습니다. '제품 이름' 필드에서 '삼성'으로 시작하는 제품들을 'Samsung group'으로, 'Apple'으로 시작하는 제품들을 'Apple group'으로, 'Canon'으로 시작하는 제품들을 'Canon group'으로, 'HP'로 시작하는 제품들을 'HP group', 'Logitech'으로 시작하는 제품들을 'Logitech group'으로 그룹화해서 보려고 합니다. 나머지는 기타로 설정해주세요. 이 그룹화를 명명하는 필드는 'Product Name Group'으로 설정해주세요.

(이때, 드래그보다는 멤버 찾기 > 시작 문자 설정하여 모두 찾아 한번에 그룹화해 확인해보세요.)
```
![문제2](./images/study3/스크린샷%202024-09-26%20오전%201.55.25.png)
![문제2](./images/study3/스크린샷%202024-09-26%20오전%202.02.17.png)

```js
해당 그룹별로 어떤 국가/지역이 주문을 많이 차지하는지를 보고자 합니다. 매출액보다는 주문량을 보고 싶으므로, 주문Id의 카운트로 계산하겠습니다.

기타를 제외하고 지정한 5개의 그룹 하위 목들만을 이용해 아래와 같이 지역별 누적 막대그래프를 그려봐주세요.
```
![문제2](./images/study3/스크린샷%202024-09-26%20오전%202.07.38.png)
