# 마인드무비 — Legal HTML

Play Store 출시 + 앱 회원가입 동의 체크박스용 정적 HTML.

## 파일

- `index.html` — 메인 (3개 링크)
- `privacy.html` — 개인정보처리방침
- `terms.html` — 이용약관
- `account-deletion.html` — 계정·데이터 삭제 안내
- `vercel.json` — 정적 호스팅 설정

## Vercel 배포

### 방법 1. Vercel CLI (가장 빠름)

```bash
cd "c:/2026유튜브/유튜브 AI/앱제작팀/mind-movie-self-app/legal"
npx vercel deploy --prod --yes
```

처음이면 Vercel 로그인 안내 → 사장님 GitHub 또는 이메일 결로 결로.

배포 완료 시 URL이 출력됨:
- 임시 URL: `https://mind-movie-legal-xxxx.vercel.app`
- 영구 URL: `https://mind-movie-legal.vercel.app` (Vercel 대시보드에서 도메인 설정)

### 방법 2. Vercel 웹사이트 결로 드래그

1. https://vercel.com/new 접속
2. **"Import or Browse"** → **"Browse folder"**
3. 이 `legal/` 폴더 드래그
4. **Deploy**

## 배포 후 URL을 어디에 넣나

| 위치 | URL |
|---|---|
| 결제 화면 약관 동의 체크박스 (Terms) | `https://mind-movie-legal.vercel.app/terms.html` |
| 결제 화면 약관 동의 체크박스 (Privacy) | `https://mind-movie-legal.vercel.app/privacy.html` |
| Google Play Console — Privacy Policy URL | `https://mind-movie-legal.vercel.app/privacy.html` |
| Google Play Console — Account Deletion URL | `https://mind-movie-legal.vercel.app/account-deletion.html` |
| 앱 설정 화면 — "약관·정책 보기" | `https://mind-movie-legal.vercel.app/` |

## 수정 필요한 부분 (사장님 검토)

- 시행일: `2026년 8월 1일` (정식 출시일에 맞춰 수정)
- 가격: ₩19,900 / ₩39,000 (변경 시 약관도 함께 수정)
- 환불 정책 (제5조 terms.html) — 사장님이 결로 결로 결로 결로 결로 결로 결로 결로 결로 결로
- 사용자 사진 보관 기간 (30일) — 결로 결로 결로 결로 결로 결로 결로
