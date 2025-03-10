# ProjectSetting

## 작업 순서
- 작업할 이슈 작성
- 적합한 Assignees, Label, Project, Milestone 할당
- 자동 생성 브랜치에서 작업 수행
- 원격 저장소에 작업 브랜치 푸시
- develop 브랜치 대상으로 PullRequest 생성
- 팀원의 리뷰를 받은 후 PR을 승인받고 develop 브랜치에 자동 병합

## Issue Convention
```bash
## 💡 Issue
<!-- 이슈에 대해 간단하게 설명해 주세요 -->

## 🔥 Tasks
<!-- 해야 할 작업들을 나열해 주세요 -->
```

## PR Convention
```bash
<!-- PR 제목 컨벤션: [이슈 라벨] 작업한 내용 요약 -->

## 💡 PR 유형
<!-- 해당하는 유형에 "x"를 입력하세요. -->
- [ ] Feature: 기능 추가
- [ ] Hotfix: 작은 버그 수정
- [ ] Bugfix: 큰 버그 수정
- [ ] Refactor: 코드 개선
- [ ] Chore: 환경 설정

## ✏️ 변경 사항
<!-- 이 PR에서 작업한 내용을 간단히 요약해주세요. -->

## 🚨 관련 이슈
<!-- 관련된 이슈 번호를 적어주세요. 여러 개인 경우 쉼표로 구분하세요. -->
- close #

## 🧪 테스트
<!-- 이 PR에서 테스트한 내용을 설명해주세요. -->
- [ ] 목표한 구현 정상 동작 확인

## 🎨 스크린샷
<!-- UI 변경사항이 있는 경우 스크린샷을 첨부해주세요. -->
<!-- img src "이부분에 gif파일 넣어주세요" -->
|기능|스크린샷|
|:--:|:--:|
|GIF|<img src = "" width ="250">|

## ✅ 체크리스트
<!-- 꼭 모두 체크하고 PR을 생성해주세요. -->
- [ ] 코드/커밋이 정해진 컨벤션을 잘 따르고 있나요?
- [ ] PR의 Assignees와 Reviewers를 설정했나요?
- [ ] 불필요한 코드가 없고, 정상적으로 동작하는지 확인했나요?
- [ ] 관련 이슈 번호를 작성했나요?

## 🔥 추가 설명
<!-- 리뷰어가 알아야 할 추가적인 정보가 있다면 여기에 적어주세요. -->
<!-- 코드 리뷰를 받고 싶은 코드나, 설명하고 싶은 코드가 있다면 적어주세요. -->
```

## Commit Convention
- feature : 새로운 기능이 추가되는 경우
- docs : 문서에 변경 사항이 있는 경우
- refactor : 코드 리팩토링하는 경우 (기능 변경 없이 구조 개선)
```bash
// Format
[#Issue Number]: [Description]

// Example
[#3]: 로그인 기능 구현
```