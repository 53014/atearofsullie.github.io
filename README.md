# 눈물 일지

개인 기록용 Jekyll 홈페이지입니다.

## GitHub에 올리는 방법

1. ZIP 파일을 압축 해제합니다.
2. 압축 해제한 폴더 안의 **모든 파일과 폴더**를 GitHub 저장소 `53014/sulliesrecord.github.io`의 최상위에 업로드합니다.
3. 폴더 구조가 다음과 같은지 확인합니다.
   - `assets/css/style.css`
   - `_layouts/default.html`
   - `_layouts/post.html`
   - `_posts/2026-11-10-첫-번째-일지.md`
   - `_config.yml`
   - `index.html`
4. GitHub 저장소의 Settings → Pages에서 `main` 브랜치와 `/(root)`가 선택되어 있는지 확인합니다.
5. Actions 탭에서 Pages 배포가 완료된 뒤 아래 주소를 엽니다.

https://53014.github.io/sulliesrecord.github.io/

## 새 글 쓰기

`_posts` 폴더에 `YYYY-MM-DD-글제목.md` 형식으로 새 파일을 만들고 아래처럼 작성합니다.

---
title: "글 제목"
description: "목록에 표시할 짧은 소개"
---

여기에 본문을 씁니다.

파일을 저장하고 GitHub에 업로드하면 홈페이지 목록에 글이 추가됩니다.
