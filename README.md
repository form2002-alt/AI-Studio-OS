# AI Studio OS

전시디자인, 일러스트, AI 영상, 실사 렌더링, 문화 콘텐츠, 코딩 파트너, 기술 디렉팅 시스템을 통합 관리하기 위한 저장소입니다.

## 저장소 목적

이 저장소는 대용량 결과물 저장소가 아니라, 다음과 같은 텍스트 중심 자산을 버전 관리하기 위한 공간입니다.

| 구분 | 관리 대상 |
|---|---|
| 시스템 인스트럭션 | ChatGPT, Google AI Studio, Gemini, Claude용 작동 규칙 |
| 템플릿 | 작업 요청서, QA 체크리스트, 제안서, 영상, 렌더링, 코딩 템플릿 |
| 프롬프트 | 이미지, 영상, 렌더링, 코딩, 리서치 프롬프트 |
| 페르소나 | 전시, 일러스트, 영상, 렌더링, 기술감독, QA 페르소나 |
| 코드 | 웹, QR, 키오스크, 자동화 스크립트 |

## 운영 원칙

1. Google Drive는 원본 자료, 이미지, 영상, 납품 파일 보관소로 사용합니다.
2. GitHub는 시스템 문서, 프롬프트, 템플릿, 코드의 버전 관리용으로 사용합니다.
3. ChatGPT 프로젝트는 현재 작업을 실행하는 공간으로 사용합니다.
4. 모든 작업은 템플릿 우선 방식으로 진행합니다.
5. 확인되지 않은 사실은 `확인 필요`로 표시합니다.
6. 일러스트·이미지·영상 콘셉트 작업은 `07_ILLUSTRATION_STUDIO/STYLE_SYSTEM_REFERENCE.md`의 표준 화풍 시스템을 우선 참조합니다.
7. 전시회사 AI 운영체제 v3.0의 일러스트 관련 작업은 `06_EXHIBITION_AI_OS/EXHIBITION_AI_OS_V3_ILLUSTRATION_STYLE_PATCH.md`를 연결 기준으로 사용합니다.
8. 전시 시스템 v4.0 관련 작업은 `06_EXHIBITION_AI_OS/v4_0/`을 기준 문서 세트로 사용합니다.
9. 종합 전시 시스템 V5.1 Patch 1 관련 작업은 `06_EXHIBITION_AI_OS/v5_1_patch1/`을 기준 문서 세트로 사용합니다.

## 기본 구조

```text
AI-Studio-OS
├── 00_ADMIN
├── 01_COMMON_SYSTEM
├── 02_PLATFORM_SYSTEMS
├── 03_TEMPLATE_LIBRARY
├── 04_PROMPT_LIBRARY
├── 05_PERSONA_LIBRARY
├── 06_EXHIBITION_AI_OS
├── 07_ILLUSTRATION_AI_STUDIO
├── 07_ILLUSTRATION_STUDIO
├── 08_AI_VIDEO_STUDIO
├── 09_CULTURE_CONNECT
├── 10_TRUE_RENDER_STUDIO
├── 11_CODING_PARTNER
├── 12_TECHNICAL_DIRECTOR
└── 99_ARCHIVE
```

## 최근 반영 문서

| 구분 | 경로 | 내용 |
|---|---|---|
| 종합 전시 시스템 V5.1 Patch 1 | `06_EXHIBITION_AI_OS/v5_1_patch1/README.md` | AI 적용 메커니즘, 생성 도구 레이어, 법적·계약 리스크, 간이 절차가 반영된 V5.1 기준 문서 세트 |
| V5.1 빠른 사용 카드 | `06_EXHIBITION_AI_OS/v5_1_patch1/QUICK_START_CARDS.md` | 호출·빠른 작업 시작·이미지·영상·렌더링·리서치·QA 요청 카드 |
| V5.1 시스템 지침 압축본 | `06_EXHIBITION_AI_OS/v5_1_patch1/SYSTEM_INSTRUCTIONS_COMPRESSED.md` | ChatGPT 프로젝트 지침 / Custom GPT / Gemini Gems / Claude Projects용 압축 지침 |
| V5.1 QA·법적 리스크 | `06_EXHIBITION_AI_OS/v5_1_patch1/QA_AND_LEGAL_RISK_GATE.md` | AI 도구 약관, 상업 이용, 저작권, 공공기관 납품 고지, QA 판정 주체 기준 |
| 전시 시스템 v4.0 | `06_EXHIBITION_AI_OS/v4_0/README.md` | 범용 전시 AI 운영 시스템 v4.0 개요, 압축 지침, 프롬프트, Style Archive, QA 문서 세트 |
| 전시 시스템 v4.0 압축 지침 | `06_EXHIBITION_AI_OS/v4_0/SYSTEM_INSTRUCTIONS_COMPRESSED.md` | ChatGPT 프로젝트 지침 / Custom GPT Instructions 저장용 압축본 |
| 전시 시스템 v4.0 프롬프트 세트 | `06_EXHIBITION_AI_OS/v4_0/PROMPT_TEMPLATES.md` | 전시 기획·검증·문안·이미지·인포그래픽·영상·렌더링·제작·QA 작업 프롬프트 |
| 전시회사 AI OS 일러스트 패치 | `06_EXHIBITION_AI_OS/EXHIBITION_AI_OS_V3_ILLUSTRATION_STYLE_PATCH.md` | Illustration Engine, QA Engine, Render & Video Engine에 화풍 시스템 연결 |
| 전시 일러스트 요청 템플릿 | `03_TEMPLATE_LIBRARY/EXHIBITION_ILLUSTRATION_REQUEST_TEMPLATE_V3.md` | 전시회사 AI 운영체제 v3.0용 일러스트 요청 템플릿 |
| 통합 화풍 시스템 | `07_ILLUSTRATION_STUDIO/STYLE_SYSTEM_REFERENCE.md` | 전시·교육·홍보용 일러스트 표준 화풍 20종 |
| 수채화 기본값 | `07_ILLUSTRATION_STUDIO/WATERCOLOR_STYLE_REFERENCE.md` | 현대적 담백 수채화 + 얇은 라인아트 기준 |

## 파일명 규칙

```text
YYYYMMDD_프로젝트명_작업유형_v001_작성자.md
```

예시:

```text
20260706_AIStudioOS_공통시스템_v001_Danchoo.md
```
