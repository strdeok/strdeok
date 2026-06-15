<div align="center">

# 황덕 | Frontend Developer

사용자 경험과 성능 지표를 함께 보는 프론트엔드 개발자입니다.  
Next.js와 React 기반 서비스에서 데이터 로딩 구조, 렌더링 병목, 초기 진입 성능을 개선하는 데 집중하고 있습니다.

<br />

<a href="mailto:ejraks1548@gmail.com">
  <img src="https://img.shields.io/badge/Email-ejraks1548%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/strdeok">
  <img src="https://img.shields.io/badge/GitHub-strdeok-181717?style=flat-square&logo=github&logoColor=white" />
</a>

</div>

---

## About Me

- 사용자 피드백과 성능 지표를 기반으로 문제를 분석하고 개선합니다.
- Lighthouse, React Profiler, Network 탭, 서버 로그를 활용해 병목을 찾습니다.
- Next.js App Router 환경에서 Server Component와 Client Component의 역할 분리를 고민합니다.
- 단순 구현보다 “왜 느린지”, “어디서 나눠야 하는지”, “사용자가 먼저 봐야 하는 정보가 무엇인지”를 중요하게 생각합니다.

---

## Tech Stack

### Core

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=fff)

### Styling & State

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=fff)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=flat-square&logo=styledcomponents&logoColor=fff)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=fff)

### Backend & Tools

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=fff)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=000)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=fff)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=fff)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=fff)

---

## Featured Projects

### SSAJOON

온라인 코딩 테스트 연습 서비스  
문제 조회, 코드 제출, 채점 결과, 제출 기록, 동료 풀이 비교 기능을 제공하는 알고리즘 문제 풀이 플랫폼입니다.

**Tech Stack**  
Next.js, TypeScript, Supabase, Tailwind CSS, TanStack Query, CodeMirror 6

**What I Improved**

- 3,000개 이상 문제 목록에서 공용 데이터와 사용자별 데이터를 분리
- 제출 통계 사전 집계 구조를 적용해 API 응답 시간 개선
- 문제 본문은 Server Component에서 먼저 렌더링하고, 코드 에디터와 사용자별 데이터는 지연 로드
- Lighthouse, Turbopack Analyzer 기반으로 초기 로딩 리소스 최적화

**Result**

- API 응답 시간 `7~8s → 120ms`
- FCP `1.5s → 0.3s`
- LCP `2.1s → 0.3s`
- 요청 수 `84 → 27`
- 전송량 `836KB → 210KB`

<br />

<a href="https://ssajoon.vercel.app/">
  <img src="https://img.shields.io/badge/Live_Service-000000?style=flat-square&logo=vercel&logoColor=white" />
</a>
<a href="https://github.com/strdeok/ssajoon">
  <img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white" />
</a>

---

### Rebin

폐기물 수거함 위치 안내 서비스  
사용자 위치를 기반으로 가까운 수거함을 탐색하고, 품목별 수거함 정보를 확인할 수 있는 지도 기반 서비스입니다.

**Tech Stack**  
React, TypeScript, Firebase, Tailwind CSS, Google Maps API, MSW

**What I Improved**

- React Profiler로 지도 이동 시 리렌더링 병목 분석
- Zustand, useShallow, React.memo, useCallback을 활용해 상태 변경 범위 축소
- 현재 지도 영역에 필요한 마커만 렌더링하도록 개선
- Firebase 경량화, LazyMotion, Route-based Code Splitting으로 초기 로딩 최적화

**Result**

- Lighthouse 성능 점수 `66 → 94`
- 메인 번들 크기 `581KB → 475KB`
- 평균 렌더링 시간 `15.4ms → 1ms 수준`
- 주요 인터랙션 리렌더링 `90% 이상 감소`

<br />

<a href="https://rebin-e8883.firebaseapp.com/">
  <img src="https://img.shields.io/badge/Live_Service-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
</a>
<a href="https://github.com/strdeok/Rebin">
  <img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white" />
</a>

---

## My Focus

```txt
사용자 경험 개선
├─ 초기 진입 속도 개선
├─ 렌더링 병목 분석
├─ 서버 상태 관리
├─ 데이터 로딩 구조 개선
└─ 실제 사용자 피드백 기반 개선
