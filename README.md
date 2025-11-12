### Hi there 👋

###
Name: Kim Dong Min

Motto: “문제를 해결 할 때 분석을 통해 구조를 나누고 하나하나 기능을 구성해가며 동작을 확인 하다 보면 해결 할 수 있다.”

School: Gachon University

### Portfolio - 김동민

[https://dongmiki.notion.site/My-Career-43f36bc3cecb4fe9850886453249a0b1?pvs=4](https://www.notion.so/Portfolio-24c57e1d999580cb9daecb4500e96172?pvs=94)
###
# 🎯 최근 프로젝트

## 📍 LOG:OUT

7월말 ~ 11월 (3~4개월)

# 🏆 GAS를 활용한 AI 시스템 개발

AI 시스템은 **입력–상태–행동** 구조로 분리하여 관리와 확장을 용이하게 했습니다.

- **입력**: Perception/Collision → 외부 자극 수집
- **상태**: Behavior Tree → 자극에 따른 State 전환
- **행동**: GAS → 상태 기반 Ability/Action 실행

이를 위해 Perception 반응, BT(Composite/Service/Task), GAS를 모두 커스텀하여 유기적으로 연동했고, Host–Client 환경에서도 동작을 보장하도록 설계했습니다.

<img width="1173" height="658" alt="image" src="https://github.com/user-attachments/assets/d4baa729-0bdb-4104-8be0-7afa0cb67087" />



# 🏆 로딩 시스템 개발

<img width="1468" height="1100" alt="image" src="https://github.com/user-attachments/assets/e083b2e0-5c90-4cb8-bfbf-8a65923ffc4f" />


멀티 환경에서 서버와 클라이언트가 같이 이동을 하는 상황에서(non-seamless travel방식의 경우) 서버의 World가 초기화되어야지 클라이언트가 접속을 시작해서 서버와 클라이언트간의 접속이 일치 하지 않는 현상이 발생하였습니다.

이를 해결하기 위해 중간에 매우 가벼운 로딩맵을 만들고 프리 로딩을 통해 다음 월드에 대한 정보를 미리 받은 다음 다음 월드로 넘어가는 방식을 사용 함으로써 호스트와 클라이언트 접속 차이를 최대한으로 줄였습니다.

# 🏆 멀티 플레이 UI 시스템 개발

<img width="1634" height="956" alt="image" src="https://github.com/user-attachments/assets/d256f98a-10aa-4906-bc02-ae032d7e269e" />


UIManager에 대한 간단한 구조도입니다.

언리얼의 특성상 오너쉽을 가지고 있어야, 네트워크 통신이 가능하기에, 여러 상황마다 위젯을 보이게하거나 안보이게하는 작업이 불편했습니다.

이를 좀 더 간편하게 하기 위해 UIManager를 만들어서 위젯을 등록해 두고 각 네트워크 통신 타입별로 호스트와 클라이언트가 위젯을 띄울 수 있도록 설계했습니다.

# 🏆 로컬 다이얼 로그 시스템 개발

<img width="1314" height="776" alt="image" src="https://github.com/user-attachments/assets/df902d1d-73e5-47b1-8e7b-63f2e27e909b" />


다이얼 로그를 스테이지별 플로우에 맞게 출력하기 위해서 계층구조로 만들고 각각에 Level를 부여했습니다. 

Level1은 전체 스테이지에서 통용되는 다이얼 로그들 또는 이벤트들이 있고, 그 밑의 Level들도 각각의 레벨에서 통용되는 것들있습니다.

현재 플로우에서 맞는 데이터를 가져와서 사용할 수 있도록 만들었습니다.

또한 특정 다이얼 로그가 실행될때 특정 이벤트도 발생시킬 수 있도록 만들었습니다.

예를 들면 챕터(Level1) - 던전(Level2) - 쾌스트(Level3)라고 하면 현재 진행중인 다이얼 로그를 가져와서 데이터를 사용할 수 있습니다.

가져온 데이터는 Dialog에서 Key값으로 분류되는  데이터 베이스를 접근해서 데이터를 가져올 수 있습니다.

<img width="1010" height="750" alt="image" src="https://github.com/user-attachments/assets/a29f5c2e-5dd0-4c60-bef9-94c207e5aca3" />


이후 가져온 데이터를 Trigger, Widget, Sound 등 다양한 곳에서 인터페이스를 사용하여 사용할 수 있습니다.


<!--
**ihaha424/ihaha424** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
