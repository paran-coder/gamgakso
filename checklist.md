<!-- 감각소 서비스화 작업의 완료/잔여 작업을 추적하는 체크리스트 -->
# 감각소 서비스화 체크리스트

## 인프라 구축
- [x] 도메인 구매 — `gamgakso.com` (가비아, 연 19,800원)
- [x] GitHub 저장소 생성 — `paran-coder/gamgakso`
- [x] Vercel 배포 — `gamgakso.vercel.app`
- [x] Cloudflare 계정 생성 및 도메인 추가
- [x] 가비아 네임서버 → Cloudflare로 변경 (`roxy.ns.cloudflare.com`, `wilson.ns.cloudflare.com`)
- [x] Cloudflare DNS 레코드 설정 (A: `@`→216.198.79.1, CNAME: `www`→vercel-dns-017)
- [x] SSL 인증서 발급 확인 (Cloudflare Universal SSL, Active)
- [x] 도메인 연결 — 외부(휴대폰 LTE)에서 `gamgakso.com` 정상 접속 확인
- [ ] 작업 PC의 통신사(하나로) DNS 캐시 갱신 — 본인 확인용. 미해결 시 DNS를 1.1.1.1로 변경

## 페이지 제작
- [x] 메인 도구 `index.html` — 헤더 내비게이션 추가
- [x] 소개 페이지 `about.html`
- [x] 사용법 페이지 `guide.html`
- [x] 세 페이지 타이포 일관성 정리 (폰트/크기/줄바꿈)
- [x] OG 대표 이미지 제작 — `og-image.png` (1200×630)
- [x] 세 페이지에 OG/Twitter 메타태그 추가

## 배포 반영
- [ ] 네 파일(`index.html`, `about.html`, `guide.html`, `og-image.png`) GitHub 업로드
- [ ] OG 미리보기 캐시 갱신 (카카오 OG 캐시 초기화 도구, 페이스북 디버거)

## 수익화
- [ ] 애드센스 신청 (도메인 연결 확인 후 진행)
- [ ] 애드센스 승인 대기 (보통 2~4주)
- [ ] 승인 후 광고 코드 삽입

## 향후 검토 (미확정)
- [ ] 트래픽 확보 전략 (타겟: PPT 작업자, 디자이너, 기획자)
- [ ] 추출 에셋의 저작권·라이선스 안내 문구 추가 여부
