# 눈물 일지

GitHub Pages + Jekyll로 운영하는 개인 기록 홈페이지입니다.

## 새 글 작성 및 날짜 선택

1. 홈페이지 상단의 **새 글 쓰기**를 엽니다.
2. 날짜, 제목, 본문을 입력하고 **글 파일 만들기 (.md)**를 누릅니다.
3. 내려받은 `.md` 파일을 GitHub 저장소의 `_posts` 폴더에 업로드합니다.
4. Commit changes를 누르면 배포 후 글이 목록에 표시됩니다.

## 이미 게시한 글의 날짜·내용 수정

1. 홈페이지 글 목록 또는 개별 글에서 **날짜·글 수정** 링크를 누릅니다.
2. GitHub 편집 화면에서 `display_date` 값을 `YYYY-MM-DD` 형식으로 바꿉니다.
3. 제목, 소개, 본문도 필요하면 함께 수정하고 Commit changes를 누릅니다.

예시:

```yaml
---
title: "첫 번째 일지"
display_date: "2026-11-10"
description: "이곳에 나의 첫 문장을 남긴다."
---
```

**참고:** GitHub Pages는 정적 홈페이지라 웹사이트 화면에서 수정한 내용을 GitHub에 직접 저장할 수는 없습니다. 날짜·내용 수정 링크는 GitHub 파일 편집 화면으로 연결됩니다. 게시 후 표시 날짜와 정렬은 `display_date`를 기준으로 합니다. 글 주소(파일명)는 그대로 유지됩니다.

## 저장소 설정

저장소: `53014/atearofsullie.github.io`

Settings → Pages에서 `main` 브랜치와 `/(root)`를 사용합니다.

홈페이지: https://53014.github.io/atearofsullie.github.io/
