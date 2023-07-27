# producing-chart

1st challenge

## 공지사항

- 아래 내용을 읽고 기한 내에 자유롭게 구현하여 제출합니다.
- 시험처럼 시간을 정하고 구현하셔도, 또는 조금씩 나누어 여유롭게 구현하셔도 됩니다.
- 질문이 있으신 경우 모두가 볼 수 있도록 Issues에 올려주세요.
- PR을 보내실 때는 구현된 화면을 간단히 캡쳐하여 보내주시면 더욱 좋습니다!

## 구현 사항

### 점수 입력

- Alex 외 5명의 게임 점수를 입력할 수 있습니다.
- 단, 점수는 최대 9999까지 입력 가능합니다.
- 'Make Chart'를 누르면 Chart 화면으로 이동합니다.
- 이 때, 하나의 점수라도 누적되면 'Make Chart' 버튼을 누를 수 없습니다.
- 'Reset Data'를 누르면 입력된 데이터를 초기화 시킵니다.

### 차트 화면

- Toggle Button을 이용하여 Pi Chart 또는 Bar Chart로 변경할 수 있습니다.
- 'back' 버튼을 누르면 점수 입력 화면으로 돌아갑니다.
  - 이 때, 기존 점수가 남아있어야 합니다.
- Pi Chart 내 부채꼴 영역은 작은 정사각형의 color로 채워져야 합니다.(아래 프로토 타입 참고)
- Chart 내 점수 순서는 점수 입력 화면에서의 순서를 유지합니다.
- Chart에 애니메이션을 적용합니다.
  - Chart 화면 최초 집입 시 또는 토글 버튼 클릭 시 애니메이션을 보여줍니다.

### 디자인

- 요소 배치 등은 지키되 size 속성 또는 color 속성 등은 자유롭게 변경 가능합니다.
- placeholder, hover 효과 등 UI/UX 요소는 필수가 아니며 자유롭게 작성합니다.

## 기술 스택

- React
- Styled Components
- 그 외 스택은 자유롭게 결정

## 프로토타입

👇 점수 입력 화면

<img width="800" alt="스크린샷 2023-07-27 20 34 22" src="https://github.com/FEChallenge/producing-chart/assets/84956036/43b61c86-ce90-4849-9e4d-611e2dfcc428">

👇 Pi Chart 화면

<img width="800" alt="스크린샷 2023-07-27 20 34 35" src="https://github.com/FEChallenge/producing-chart/assets/84956036/191b5eb3-952d-470d-a4ca-128b597599c4">

👇 Bar Chart 화면

<img width="800" alt="스크린샷 2023-07-27 23 00 14" src="https://github.com/FEChallenge/producing-chart/assets/84956036/6c83f248-1d76-44df-be10-49d26b6e4250">
