## 성창해 · Changhae Seong

제조·엔지니어링 도메인에 **CAD 자동화 · 시뮬레이션 시각화 · AI** 를 붙이는 일을 합니다.
Java/Spring 백엔드로 시작해 지금은 데스크톱 애플리케이션, 3D 웹, LLM 파이프라인까지 다룹니다.

📍 경상남도 창원 &nbsp;·&nbsp; 📧 haeya0124@gmail.com

<br/>

### 지금 다루는 것

**🔧 CAD 자동화**
CATIA V5 를 COM 자동화로 조종합니다. 파라미터 일괄 조회·수정·저장, 스케치·솔리드·서피스 생성 스크립팅,
그리고 **만든 형상을 실제로 측정해 검증하는 회귀 테스트**까지 붙여 둡니다. 도면 한 장을 손으로 고치는 대신 스크립트가 100장을 고치게 만드는 쪽입니다.

**🌊 시뮬레이션 · 버추얼 트윈**
OpenModelica · FMI 2.0(FMU) 로 계산한 결과를 브라우저에서 돌립니다.
React Three Fiber 로 배관·펌프 네트워크를 3D 로 세우고, 파라미터 스윕 결과를 겹쳐 비교하는 CLI 도 따로 만들어 씁니다.

**🤖 AI 실무 적용**
RAG 챗봇과 문서 판독 파이프라인을 만듭니다. 두 가지를 원칙으로 둡니다 —
**답변에는 항상 출처를 붙이고, 근거를 못 찾으면 못 찾았다고 먼저 밝힌다.**
**AI 는 제안만 하고 확정은 사람이 한다.** 스캔된 시방서를 읽어 사내 양식을 채우는 일에서, AI 출력이 검토 없이 DB 로 들어가면 틀린 값이 축적돼 이후 모든 산출물에 전파되기 때문입니다.

**🖥 데스크톱 애플리케이션**
Electron 렌더러 + Python(FastAPI) 러너를 프로세스로 갈라 붙이는 구조를 씁니다.
학습된 모델(Keras · PyTorch · scikit-learn · ONNX)을 **매니페스트(JSON)로 기술해** 새 모델을 붙일 때 앱을 고치지 않아도 되게 만드는 식으로, 확장 지점을 코드 밖에 둡니다.

<br/>

### 일하는 방식

- **문서를 코드와 같은 저장소에 둡니다.** 스펙 · 아키텍처 · 컨벤션 · 이슈 · 변경 이력을 `docs/` 트리로 관리하고, 문서와 코드가 어긋나면 CI 가 막습니다.
- **게이트를 먼저 세웁니다.** typecheck · lint · 테스트 케이스 수 하한 · 번들 예산 · 시크릿 스캔 · 취약점 검사 — 통과 못 하면 머지하지 않습니다.
- **조용히 깨지는 자리를 계약 테스트로 묶습니다.** 개발 서버에선 멀쩡한데 배포본에서만 터지는 결함이 제일 비쌉니다. 짝이 되어 움직여야 하는 파일들은 계약 테스트가 어긋남을 잡게 합니다.
- **이슈 → 워크트리 → 전후 증거 캡처 → PR** 순서로 작업합니다. 무엇을 고쳤는지는 말이 아니라 증거로 남깁니다.

<br/>

### 🛠 Tech Stack

<table>
  <tr>
    <td width="120"><b>Language</b></td>
    <td>
      <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=OpenJDK&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/>
      <img src="https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Front-End</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/>
      <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=Electron&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Back-End</b></td>
    <td>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white"/>
      <img src="https://img.shields.io/badge/MyBatis-C73B3B?style=flat-square&logo=databricks&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>AI / Sim</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
      <img src="https://img.shields.io/badge/Modelica%20%C2%B7%20FMI-1F425F?style=flat-square"/>
      <img src="https://img.shields.io/badge/CATIA%20V5-005386?style=flat-square&logo=dassaultsystemes&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Quality</b></td>
    <td>
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/>
      <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
      <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Infra</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
    </td>
  </tr>
</table>

<br/>

### 📌 저장소 안내

현재 진행 중인 프로젝트는 대부분 **비공개 저장소**에 있습니다.
공개된 저장소(`KORIT_SQF_STUDY_*`, `springboot`, `react`, `SPRING_SECURITY` 등)는 2024년 부트캠프 시절의 학습 기록입니다.

작업물이 궁금하시면 메일 주시면 정리해서 보내드리겠습니다. 🙂

<br/>

### 📊 GitHub

<img src="https://github-readme-stats.vercel.app/api?username=changs0124&show_icons=true&hide_border=true&include_all_commits=true&theme=default" height="150"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=changs0124&layout=compact&hide_border=true&langs_count=8&theme=default" height="150"/>
