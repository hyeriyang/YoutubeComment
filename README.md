####### 감성분석 & LDA Topic modeling

### 0. Data

- 감성분석 분류기를 만들기 위해  4명의 유버의 댓글을 전체 합쳐 데이터 생성
- 총 58654개의 댓글 데이터

### 1. Labeling

- 기존 배포되어 있는 감성어사전은 뉴스 제목에서만 나올법한 단어들..
- 유튜브 댓글 특성(신조어, 줄임말 등)에 맞춰 직접 감성어 사전 구축 !
- 감성어 사전 구축 : 긍정단어 883개, 부정단어 831개
- value=0을 기준으로 문장에 긍정 단어가 존재하면 +1, 부정 단어가 존재하면 -1 씩 계산됨
- value>0 : 긍정 / value=0 :중립 / value<0 : 부정


