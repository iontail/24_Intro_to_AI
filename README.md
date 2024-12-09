# 2024-2 SKKU Introduction to A.I
> 성균관대학교 인공지능개론 5팀 코드서버

### 김민석 · 김승겸 · 이찬희 · 정상헌 · 한서연
#### Minseok Kim · Seunggeom Kim ·  Chanhee Lee ·  Sanghun Jung ·  Seoyeon Han

-----



### 온라인 도박 중독 재발 방지를 위한 디지털 치료제 연구
: Digital Therapeutics(DTx) Research for Preventing Relapse in Online Gambling Addiction


## Abstract
인터넷 도박은 높은 접근성과 익명성, 게임의 다양성, 즉각적인 보상 등으로 인해 누구나 빠르게 중독될 수 있는 위험성을 지니고 있다. 이를 해결하기 위해 본 연구는 인터넷 도박 중독의 재발 방지를 위한 디지털치료제 개발을 진행하고자 한다. 먼저, 여러 선행연구를 분석하여 경고 문구가 중독에 미치는 영향, 일반 사이트와 도박 사이트를 분류하는 과정 등을 전체적으로 파악하고자 한다. 이후 분석 알고리즘을 제작하여 프로그램으로 직접 구현하고자 한다. 분석 알고리즘은 다음과 같다. 
1. 치료대상자가 방문하는 사이트의 텍스트로부터 지속적으로 중독 재발 가능성 혹은 중독 위험 수치 계산 
2. 일정 수치 초과 시 경고 문구와 이미지를 포함한 UI 제공 
본 연구는 최근 사회문제로 대두되고 있는 인터넷 도박 중독에 대한 즉각적인 탐지에 이은 치료까지 연계된다는 점에서 큰 의의를 지닐 것으로 예상된다.


## 데이터셋
+ 키워드 기반 데이터셋 (등장 횟수 기준 상위 키워드)
  
  | 레이블 | 내용 |
  |:---:|:---:|
  |0|일반사이트|
  |1|도박사이트|
  |2|도박 제외 불법사이트|
+ KAIST사이버보안연구센터 데이터 제공
+ Son, J. et al. "Ensuring Reliability of BERT-Based Harmful Website Classification Model using XAI". 2024 한국컴퓨터종합학술대회 논문집.
