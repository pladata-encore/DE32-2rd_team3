# 데이터 엔지니어링 32기 2nd project 3팀 

<img src = "https://github.com/user-attachments/assets/1520da55-7956-4614-8f35-aa43835e2db8"  width="80%" height="80%">


## 업무용 메신저 만들기 프로젝트
### SB CHAT (1 Stone 3 Birds Chat) 
<img src = "https://github.com/user-attachments/assets/e0ca323f-b5ff-418f-86c4-b7d94eab5236"  width="30%" height="30%">

# 프로젝트 진행 배경 

* 업무 내용에 대해 외부 메신저 프로그램 사용으로 인한 사내 기술 유출 우려 때문에 사내 업무 전용 메신저 개발
* 사내 문제 발생시 감사팀의 메신저 내용 감찰을 용이하기 하게 위해 업무용 메신저 개발 

# 프로젝트 요구사항 정의서

* 요구사항 정의서 : [REQUIRE.md](https://github.com/1-Stone-3-Birds/SB_Works/blob/main/Require.md)
  
<img src = "https://github.com/user-attachments/assets/cc0b7d55-c789-42c4-83bd-a2bd556ff623"  width="80%" height="80%">

# 프로젝트 진행 일정

## 1. 프로젝트 개발 일정 
<img src = "https://github.com/user-attachments/assets/5db91c6f-9646-4172-b26b-fa7089bf3ddc"  width="100%" height="100%">

* 일정 계획 : [SCHEDULE.md](https://github.com/1-Stone-3-Birds/SB_Works/blob/main/Schedule.md)  

## 2. 프로젝트 테스트 일정 
<img src = "https://github.com/user-attachments/assets/f2eb31a9-549e-4b6c-9cb8-e612bbfeeee5" width="100%" height="100%">

* 필수 업무는 실선, 부가 업무는 점선, 연계 업무는 이중선으로 표시

* 테스트 일정 : [TEST.md](https://github.com/1-Stone-3-Birds/SB_Works/blob/main/Test.md)

# 기술 스택 

- ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000000?style=flat&logo=apache-kafka&logoColor=white): 실시간 데이터 스트리밍 
- ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white): 대규모 데이터 처리 / 제플린 분석 언어
- ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017E9A?style=flat&logo=apache-airflow&logoColor=white): 데이터 파이프라인 
- ![Apache Zeppelin](https://img.shields.io/badge/Apache%20Zeppelin-006400?style=flat&logo=apache-zeppelin&logoColor=white): 데이터 시각화/ 분석

# 프로젝트 프로그램 아키텍처 구상도 
![data flow - Page 1 (2)](https://github.com/user-attachments/assets/2746e20b-049f-4b00-9ad4-74ed35b00a6a)



## 프로젝트 코드 
* 프로젝트 코드:  [team_repo](https://github.com/1-Stone-3-Birds/SB_Works) 	
	
# 프로젝트 결과물 
	- 추후 업데이트 

# 프로젝트 회고 

## 박수진
### 1. 배운 점
'apscheduler'를 사용하여 정해진 시간에 작업을 자동으로 수행하는 방법을 배움. 스케줄러 설정의 다양한 방법(apscheduler, crontab ..)과 그 방법들의 장단점을 직접 이해할 수 있었음
### 2. 느낀 점
팀원의 중요성을 깨달은 프로젝트. 
팀원 모두가 소통이 잘 돼고, 열정적인 모습을 보여줘서, 첫 팀플임에도 불구하고 모르는 것을 질문하는데 어려움이 없었고, 이 상태로 최종 프로젝트에 들어가도 좋겠다라는 생각을 함.. 잘하는 사람이 있으면 그 사람에게 업무가 치중될 수 있었지만, 우리 팀은 분업이 잘 되어서 많은 걸 배울 수 있었음
### 3. 아쉬운 점
streamlit이라는 UI를 쓰려하였지만, 다중 채팅에 한계가 있는 점을 고려하지 못했고, 그로 인해 작업들이 조금 미뤄지게 되면서 UI를 적용하지 못한 점이 아쉬움
또 브랜치를 나누기로 사전에 얘기를 했지만, 실제로는 많이 나누지 못해 한 브랜치에 치중되었던 게 아쉬움
### 4. 개선할 점
환경 설정이 특히.. kafka 다운이 내 컴퓨터에는 이상하게 적용이 잘 되지 않아서.. 깃과 pdm에 대해 더 공부할 필요를 느낌 


## 김태민
### 1. 배운 점
kafka에 대해서 자연스럽게 구석구석 탐구하게 되었던 것 같아서 많이 배울 수 있었습니다. 

### 2. 느낀 점
이전 프로젝트보다 의사소통 측면에서 개선된 것이 긍정적이었고, 좀 더 완벽한 결과물을 얻기 위해 다들 열정이 넘쳤던 것 같아서 좋았습니다.

### 3. 아쉬운 점
다만 열정만 넘쳤고 사전조사가 조금 덜 되어서 시간을 많이 소모한 것이 아쉽습니다. 1일차에 시간 소모를 줄이고 진도를 나갔다면 2일차에 시간을 여유롭게 사용할 수 있었을 것 같은데 1일차에 못한 부분을 2일차에 채우느라 힘들었던 것 같습니다.

### 4. 개선할 점
추후 프로젝트에서는 사전조사가 잘 되어야 할 것 같습니다.
또, 시간 배분을 잘 하기 위해 필요하다면 빠른 포기도 중요한 것 같습니다.

시간이 더 있었다면 
- UI를 깔끔하게 개선
- 한글을 입력했다가 지우면 생기는 encoding 오류 처리

## 이상훈
### 1. 배운 점
의사소통, 프로젝트 진행 및 코드 이해, 활용 

### 2. 느낀 점
의사소통이 중요하다는 것을 느꼈습니다. 소통에서 오는 많은 의견과 프로젝트 구성 및 방향에 대해 이해가 더 높아졌습니다. 굿. 서로 도와가면서 좋은 시너지를 느꼈습니다.

### 3. 아쉬운 점
많은 소통과 의견으로 열정이 넘쳐 프로젝트 진행 시 약간 지체된 점이 아쉽습니다.\
기본적인 요구사항 외 추가 요건을 해보려 시간이 지체되서 아쉽다. 결국 원점으로..\
채팅 프로그램 UI도 못해보고.....아쉽

### 4. 개선할 점
프로젝트 전, 기술 적용에 대한 조금 더 디테일한 사전조사가 시간을 아끼는 방법일지도..?\
기본적인 요구사항을 먼저 완료한 뒤 추가적인 선택사항을 진행하면 좋을 것 같다고 생각했습니다.

## 이상우
### 1. 배운 점
Kafka에 대해서 수업시간에 제가 이해한 내용보다 좀 더 깊게 알게 되었고 프로젝트를 진행하는 방식에 대해서 좀 더 발전시킬 수 있는 기회였습니다.

### 2. 느낀 점
업무의 분담의 중요성을 느꼈습니다. 원할한 프로젝트를 위해서 공통의 목표를 바라볼 수 있게 대화를 적극적으로 해야하는 것을 느꼈습니다.\
제대로 기술에 대한 공부를 하지 않고 무턱대고 프레임워크나 코드를 가져다 썼을때 오는 리스크를 알게되었습니다.

### 3. 아쉬운 점
제대로 알지 못한 기술을 활용하다가 프로그램의 목적과 달라 1일차 진행물을 폐기하게 되었는데, 그로인해 프로젝트 진행이 지연되어서 시간이 있었다면 더 좋은 프로그램을 만들 수 있었을 것 같다는 아쉬움이 있습니다.

### 4. 개선할 점
프로젝트에 필요한 기술에 대해서 당장에 필요한 부분을 코드로 구현하는 부분적인 것보다 코드의 목적이 프로젝트와 부합하는지 더 넓은 시야에서 바라볼 수 있는 학습 능력을 길러야겠습니다.\ 
생각을 조금더 조리있고 핵심을 위주로 짧게 정리함으로써 프로젝트와 관련된 대화시간의 길이를 효율적으로 조정할 수 있게 해야겠습니다.\
프로그램적으로는 상대방이 채팅을 치면 내가 채팅치던 부분이 사라지는 부분 , UI를 적용하지 못한 부분을 개선하고 싶습니다.

