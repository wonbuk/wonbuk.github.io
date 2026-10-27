---
layout: post
title: "터미널에서 깃허브 사용"
date: 2026-10-27 21:45:00 +0900
published: true
---

---

1. 사용자 설정 (최초 1회만)
git config --global user.name "깃허브_아이디"
git config --global user.email "깃허브_이메일"
---

2. 레포지토리 복제하기
git clone 깃허브_HTTPS_주소
cd 레포지토리_폴더_이름
---

3. 파일 수정하기 (vi 편집기 사용 예시)
vi 파일이름.html
---

4. 변경 사항 확인 및 커밋하기
git status
git add .
git commit -m "터미널에서 웹페이지 수정 완료"
---

5. 깃허브에 반영하기 (푸시)
git push origin main
(비밀번호 입력 시 깃허브 비밀번호 대신 Personal Access Token 입력)
