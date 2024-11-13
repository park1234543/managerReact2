
## STACK 선정 이유 🙆‍♂️

- 전역 상태관리

  
  - 큰 프로젝트 에서 많이 사용 하는 Redux-toolkit을 경험해보고 싶어 도입하였고 redux-toolkit 사용 시 사람들이 불편함을 느끼는 비동기 처리를 react query를 도입하여 해결했습니다.

- CSS - in - JS
  - button의 색상이나 width값만 props로 변경하여 컴포넌트의 재사용성을 높이고 싶어 결정했습니다.

## Design Patterns⭐️

- Container/Presentational 패턴 참고
  - 컴포넌트를 깔끔하게 관리.
  - container 컴포넌트 대신 pages폴더에 container를 대신할 page컴포넌트를 만들어 각종 데이터 fetch와 전역으로 관리할 필요없는 상태들을 작성하고 props로 컴포넌트 전달.

