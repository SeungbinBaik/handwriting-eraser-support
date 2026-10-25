# 필기 지우개 (Handwriting Eraser) — support & privacy

App Store·Google Play 가 요구하는 지원 URL 과 개인정보 처리방침 URL 용 정적 페이지 (iPhone·안드로이드 공용).

- 고객 지원: https://eraser.edureserve.com/ (10-25부터 사용자 도메인 — 옛 github.io 주소는 GitHub 가 301 로 넘긴다)
- 개인정보 처리방침: https://eraser.edureserve.com/privacy.html
- 친구에게 알려 주기·자랑하기 링크: https://eraser.edureserve.com/i/?c=<어디서> — 기기에 맞는 스토어로만 보낸다 (iOS App Store,
  안드로이드 Play 에 `utm_source=invite&utm_campaign=<어디서>`, PC 는 두 스토어 단추). 링크에 사람·기기 정보 없음.
- 도메인: Cloudflare DNS(edureserve.com) `CNAME eraser → seungbinbaik.github.io`, **프록시 끔**(켜면 GitHub 인증서 갱신이 막힌다).
  저장소 루트의 `CNAME` 파일을 빼고 올리면 사용자 도메인이 풀려 공유한 링크가 모두 깨진다.

앱은 이 페이지를 실행 중에 불러오지 않는다 (서버 없음). 원본은 앱 저장소의 `docs/public/`.
