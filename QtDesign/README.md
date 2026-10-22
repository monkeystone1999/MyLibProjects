# Qt Qml 에서 가져다 쓸 디자인 & Color paletes

최대한 많이 구현하는 것을 목표 삭제보다는 확장

## Design

- 버튼, Layout 등을 내가 원하는 방식으로 재탄생

## Color paletes

- Material UI
- Fluent UI
- HIG (Apple) Base

## 자동화

- 최초에 primary color 를 주입 시 secondary, third color 를 뽑아주는 HCT/HSL 수학 공식 채용
- Well known 한 Color Set 들의 경우에는 하드코딩이 되어있는 방식을 채택하나 root에서 Color set 을 선택한 후에는 동일한 Interface 로 사용이 가능하게끔 채택
