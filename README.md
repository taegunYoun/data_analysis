# Iris 데이터셋 시각화 과제

## 과제 개요

Iris 데이터셋을 활용하여 다양한 차원 축소 기법(PCA, LDA, t-SNE)을 적용하고, 각각을 2차원 또는 3차원으로 시각화한다.

## 사용 라이브러리

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (datasets, PCA, LDA, TSNE)

## 시각화 내용

### 0. 데이터 불러오기

- scikit-learn의 `load_iris()` 함수로 Iris 데이터셋을 불러오고, Pandas DataFrame으로 구성하여 `iris`, `X`, `y` 변수로 저장.

### 1. 2차원 산점도 (Scatter Plot)

- x축: sepal length
- y축: sepal width
- 각 클래스(품종)를 색상으로 구분하여 시각화
- 제목: Iris data scatter plot

### 2. PCA 2차원 시각화

- PCA를 통해 2개의 주성분으로 차원 축소
- x축: principal component 1
- y축: principal component 2
- 클래스별 색상 구분
- 제목: PCA 2D visualization of iris dataset

### 3. PCA 3차원 시각화

- PCA를 통해 3개의 주성분으로 차원 축소
- x축: principal component 1
- y축: principal component 2
- z축: principal component 3
- 클래스별 색상 및 범례 설정
- 제목: PCA 3D visualization of iris dataset

### 4. LDA 2차원 시각화

- LDA를 통해 클래스 간 분리도를 최대화하는 방향으로 2차원 변환
- x축: LDA component 1
- y축: LDA component 2
- 클래스별 색상 구분
- 제목: LDA 2D visualization of iris dataset

### 5. t-SNE 2차원 시각화

- t-SNE를 이용해 비선형 방식으로 2차원 임베딩
- x축: t-SNE feature 1
- y축: t-SNE feature 2
- perplexity 30, max_iter 1000 사용
- 클래스별 색상 구분
- 제목: t-SNE 2D visualization of iris dataset

### 6. t-SNE 3차원 시각화

- t-SNE를 이용해 3차원 임베딩
- x축: t-SNE feature 1
- y축: t-SNE feature 2
- z축: t-SNE feature 3
- perplexity 30, max_iter 1000 사용
- 클래스별 색상 및 범례 설정
- 제목: t-SNE 3D visualization of iris dataset
