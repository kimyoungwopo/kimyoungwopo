<p align="center">
  <img src="./assets/profile-banner.svg" width="100%" alt="Kim Youngwoo — Frontend Developer & Product Builder. Build the interface. Connect the product." />
</p>

<p align="center">
  <strong>프론트엔드를 중심으로 제품의 구조, 흐름, 운영까지 설계합니다.</strong><br />
  <sub>사용자 흐름부터 API 연결, 모바일 QA까지.</sub>
</p>

<p align="center">
  <a href="mailto:kbc01054575075@gmail.com"><img src="https://img.shields.io/badge/Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="이메일로 연락하기" /></a>
  <a href="https://github.com/kimyoungwopo/frameflow"><img src="https://img.shields.io/badge/Frameflow-0F172A?style=flat-square&logo=github&logoColor=5EEAD4" alt="Frameflow 저장소" /></a>
  <a href="https://kimyoungwopo.github.io/cafe24-smart-design"><img src="https://img.shields.io/badge/Cafe24_Live_Docs-0F172A?style=flat-square&logo=readthedocs&logoColor=93C5FD" alt="Cafe24 공개 레퍼런스" /></a>
</p>

---

## 01 / Featured Build

### Frameflow

**이미지 워크플로를 연결하고, 결과를 검증하는 로컬 스튜디오.**

<a href="https://github.com/kimyoungwopo/frameflow">
  <img src="https://raw.githubusercontent.com/kimyoungwopo/frameflow/main/docs/assets/studio-overview.png" width="100%" alt="Frameflow 실제 스튜디오 화면: 이미지 생성과 편집 노드를 연결하는 워크플로" />
</a>

이미지 생성·편집을 노드 그래프로 구성하고, Local Bridge와 provider adapter로 연결합니다. 모션 아틀라스 검증 → 정확한 프레임 분리 → GIF/APNG 출력까지 명확한 계약으로 다룹니다.

`Next.js` · `TypeScript` · `Local-first` · `Apache-2.0`

[**Explore repository →**](https://github.com/kimyoungwopo/frameflow) · [한국어 가이드](https://github.com/kimyoungwopo/frameflow/blob/main/README.ko.md)

---

## 02 / Open-source Toolkit

### Cafe24 Smart Design
**카페24 스킨 작업을 위한 검색 가능한 레퍼런스.**

모듈·변수·수정자, JSON registry, 공식 문서 맵과 AI 편집 guardrail을 정리합니다. 공개 뷰어에서 탐색하고 데이터 검증으로 정합성을 확인합니다.

[Repository](https://github.com/kimyoungwopo/cafe24-smart-design) · [**Live docs →**](https://kimyoungwopo.github.io/cafe24-smart-design) · `HTML` · `MIT`

### Frontend Token Trim Skillpack
**구현에 필요한 맥락은 남기고, 불필요한 컨텍스트는 줄이는 도구.**

Ponytail · Graphify · Headroom 기반으로 Hermes Agent의 프론트엔드 구현과 QA 흐름을 정리합니다.

[**Repository →**](https://github.com/kimyoungwopo/frontend-token-trim-skillpack) · `Hermes Agent` · `Skillpack` · `MIT`

### Korean E-commerce Visual Copywriting Skill
**한국 커머스 이미지와 상세페이지 카피를 위한 Agent Skill.**

대표이미지, 상세페이지 스토리보드, 이미지 내 문구와 생성형 이미지 프롬프트를 구조화합니다.

[**Repository →**](https://github.com/kimyoungwopo/korean-ecommerce-visual-copywriting-skill) · `Python` · `Visual copywriting` · `MIT`

---

## 03 / Product Work

### WOD / PRDAY
**운동 기록부터 예약·코칭까지 이어지는 모바일 운영 흐름.**

회원·관리자 역할별 화면, WOD 기록, 예약, 코칭 신청·승인 UX를 운영 데이터와 연결합니다.

`Mobile-first SaaS` · `Role-based UI` · `Operations`

---

## 04 / Engineering Craft

**Flow before features.**
사용자가 어디서 들어와 어떤 행동을 완료하는지 먼저 설계합니다.

**States before screens.**
로딩·빈 화면·오류·권한까지 API 응답과 함께 연결합니다.

**Verify before shipping.**
모바일 가독성, 터치 타깃, 접근성, SEO/OG와 회귀 QA를 확인합니다.

<p>
  <img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Supabase-111827?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase" />
  <img src="https://img.shields.io/badge/Node.js-111827?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
</p>

<details>
<summary><strong>구현 영역과 제품 흐름 더 보기</strong></summary>

- **App Shell & IA** — 모바일 진입 동선, 대시보드, 상세·설정, 하단 시트와 sticky CTA
- **Auth & Role** — 게스트·회원·관리자 분기, 보호 라우트, 로그인 전후 상태
- **Data-driven UI** — API route BFF, 목록·필터·상세·폼, 에러·빈 상태
- **Ship Quality** — SEO/OG, 접근성, 배포, visual regression과 운영 체크리스트

```mermaid
flowchart TD
  A[User flow] --> B[API and data contract]
  B --> C[UI states and role flow]
  C --> D[Mobile and visual QA]
  D --> E[Ship and iterate]
  classDef step fill:#111E35,stroke:#60A5FA,color:#F8FAFC;
  class A,B,C,D,E step;
```

</details>

---

## 05 / Activity

<p align="center">
  <img width="100%" src="https://github-readme-streak-stats.herokuapp.com?user=kimyoungwopo&theme=dark&background=0D1117&hide_border=true&stroke=60A5FA&ring=5EEAD4&fire=60A5FA&currStreakLabel=93C5FD" alt="GitHub 기여 활동과 연속 기여 기록" />
</p>

<p align="center"><sub>Build with intent. Verify with evidence.</sub></p>
