# git-flow-prac
git flow를 간략하게 익히기 위한 프로젝트입니다 (참고: [velog](https://velog.io/@nias0327/Git-Flow%EC%9D%98-%EA%B0%9C%EB%85%90%EA%B3%BC-%EC%A0%81%EC%9A%A9))

## 브랜치 전략
- feature: 단위별 기능 개발 브랜치
  - 네이밍
    - feature/기능요약 형식 추천
      ex) feature/login
    - 이슈추적을 사용한다면 feature/{issue-number}-{feature-name} 형식 추천
      ex) feature/1-init-project, feature/2-build-gradle-script-write
- develop: 다음 출시 버전 개발 브랜치
- release: 이번 출시 버전 준비 브랜치
- hotfix: 출시 버전에서 발생한 버그 수정 브랜치
- master: 최종 제품 출시용
  - X.0: 프로젝트 추가
  - 1.X: 기능 추가

## 실습
- main, develop, feature 브랜치로 나누어 진행
