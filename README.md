# instagram_posting_analysis
인스타그램 포스팅을 대상으로 데이터 시각화 및 분석을 진행.
다음과 같은 순서로 현재까지 작업이 진행되었음

- a) 인스타그램 포스팅 크롤링 (repository에는 코드 및 데이터가 없음. 참조바람)
- b) 소상공인 상권 데이터의 상점명, 위도, 경도 데이터를 활용하여, 을지로3가, 가로수길, 이태원 내 상점별 포스팅 갯수 계산 (상점별로 텍스트 내 특정 상점명이 포함되는 포스팅들의 갯수를 계산)
- c) pydeck을 활용하여 데이터 시각화 진행  

# requirements
`requirements.yaml` 참조

# installation
프로젝트 폴더에서 `conda env create --name insta_posting_analysis --file=requirements.yaml` 실행

# Directory
- input: 데이터 분석에 사용한 데이터. 소상공인 상권 데이터에서 가져온 store 폴더와 인스타그램 포스팅이 담긴 posts 폴더가 있음
- output: 데이터 시각화 결과물 (현재는 pydeck으로 생성한 html 파일 존재)
- notebook: 데이터 분석을 위해 작성된 jupyter notebooks
