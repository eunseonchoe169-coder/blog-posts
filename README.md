# Blog Posts

블로그 글의 아이디어, 초안, 발행본과 이미지를 한곳에서 관리하는 저장소입니다.

## 폴더 구성

```text
blog-posts/
├─ drafts/                 # 작성 중인 글
├─ posts/                  # 발행을 마친 글
├─ images/                 # 글에 사용하는 이미지
└─ templates/
   └─ post-template.md     # 새 글을 시작할 때 복사하는 양식
```

## 사용하는 방법

1. `templates/post-template.md`를 복사합니다.
2. 파일 이름을 `YYYY-MM-DD-주제.md` 형식으로 정해 `drafts/`에 저장합니다.
3. 글을 작성하고 이미지가 필요하면 `images/글-이름/` 아래에 넣습니다.
4. 발행이 끝난 글은 `posts/`로 옮기고 `status`를 `published`로 변경합니다.
5. 수정 내용을 GitHub에 반영하면 변경 이력이 자동으로 남습니다.

## 파일 이름 예시

- `drafts/2026-10-22-ai-automation-study.md`
- `posts/2026-10-22-ai-automation-study.md`
- `images/ai-automation-study/cover.png`

## 공개 저장소 주의사항

이 저장소는 공개 상태이므로 누구나 내용을 볼 수 있습니다. 비밀번호, 인증번호, 개인정보, 고객 정보, 공개 전 기밀자료는 저장하지 마세요.

## 첫 번째 할 일

`drafts/2026-10-22-ai-automation-first-step.md`에 들어 있는 예시 글을 본인의 경험에 맞게 수정해 보세요.

