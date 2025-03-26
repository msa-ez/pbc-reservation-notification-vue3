## PBC Alarm 시스템 개요
PBC Alarm 시스템은 모든 알림 관련 작업을 효율적이고 안전하게 처리하도록 설계되었습니다. 이 시스템은 즉각 알람 발송 및 예약 알림 발송을 위한 견고한 프레임워크를 제공합니다. SSE(Server-Sent Events) 기반의 기술을 활용하여 실시간으로 알림을 전송하며, 사용자 친화적인 인터페이스를 통해 알림 설정을 쉽게 관리할 수 있도록 지원합니다. 특히, Vue3 기반 환경에서 원활하게 동작하도록 최적화되어 있어, 최신 웹 기술을 활용한 매끄럽고 반응성 높은 사용자 경험을 제공합니다. 이러한 기능을 통해 다양한 알림 옵션을 제공하고, 사용자 경험을 최적화하여 보다 매끄럽고 편리한 알림 과정을 제공합니다. PBC Alarm 시스템은 신뢰성과 확장성을 동시에 확보하며, 사용자에게 보다 다양한 선택지를 제공하여 알림 과정을 더욱 매끄럽고 편리하게 만듭니다.

## 사용 가능한 기능
### 1) 즉각 알람 발송 <br>
  SSE 기반의 기술을 통해 사용자가 즉각적인 알람을 받을 수 있도록 하며, 안전하고 빠른 알림 환경을 보장합니다.

### 2) 예약 알림 발송 <br>
  사용자가 정해진 날짜와 시간에 알림을 설정할 수 있는 기능을 제공하여, 예약된 알림을 정확하게 발송할 수 있도록 지원합니다.

## 사용 방법

### 1) 분석/설계
1. 적용한 PBC의 바운디드 컨텍스트 영역을 더블 클릭하여 PBC 패널을 활성화 합니다.

<img width="1275" alt="image" src="https://github.com/user-attachments/assets/69cebda6-8334-4945-b0b7-7b061ad6c064" /> <br>
<PBC Panel 생성 예시>

2. PBC 패널 옵션중 읽기 요소, 커맨드 요소, 이벤트 요소에서 각각 사용할 기능에 해당하는 이벤트스토밍 스티커를 선택합니다. 

<img width="435" alt="image" src="https://github.com/user-attachments/assets/22365ca1-139f-4582-a95f-bb425bb61383" /> <br>
<Panel 스티커 옵션 선택 예시>

### 2) 구현
1. 패널을 닫은 후, CODE를 클릭하여 코드 프리뷰를 통해 이벤트스토밍기반 생성된 코드를 확인합니다.
<img width="714" alt="image" src="https://github.com/user-attachments/assets/4d3f35e7-30cb-483d-a3b5-2fd099101ed4" /> <br>

2. 생성된 코드에서 선택한 PBC 폴더 > README.md를 클릭하여 소스코드 사용방법을 확인합니다.
<img width="716" alt="image" src="https://github.com/user-attachments/assets/324887ab-53b3-4bd9-b8ba-823a62bcf764" /> <br>
<PBC README.md 파일 예시>

3. IDE환경에서 소스코드를 Load한 후, README를 참고하여 다운로드 > 압축 해제를 진행하여 소스코드에 다운로드 받은 PBC가 생성되었는지 확인합니다.
<img width="741" alt="image" src="https://github.com/user-attachments/assets/037b4ac3-dc03-4b96-9d83-dd049629d24f" /> <br>
<PBC 소스코드 다운 예시>

4. port 충돌을 고려해 application.yml(payment/src/main/resources/application.yml)의 port를 적절하게 변경합니다.
<img width="290" alt="image" src="https://github.com/user-attachments/assets/8809f047-3cc4-4e66-932e-9f89f6f8df5b" /> <br>
<PBC Port 변경 예시>
