# 종합 전시 시스템 V5.1 Patch 1

AI 협업 + Adobe 제작 + Blender 3D + QA 검수 기반 범용 전시·문화콘텐츠 제작 운영체계입니다.

## 적용 범위

- 전시 기획·리서치·문안
- 전시디자인·사인그래픽
- 일러스트·이미지 생성·보정
- 영상·미디어 씬보드
- 3D 렌더링·Blender 공간 시각화
- 성우·음악·사운드
- 홍보·SNS 콘텐츠
- 제안서·문서화
- 제작·시공·납품 QA

## V5.1 Patch 1 핵심 보완

| 보완 항목 | 내용 |
|---|---|
| AI 적용 메커니즘 | 새 대화창·외부 AI는 V5.1을 자동으로 알지 못하므로 Master Brief, 프리셋, QA 기준을 함께 주입한다. |
| 생성 도구 레이어 | 기획·분석 AI와 이미지·영상·음성·음악 생성 도구를 분리한다. |
| Gemini / AI Studio 관계 | Google AI Studio는 Gemini 모델/API 실험 환경으로 정의한다. |
| 법적·계약 리스크 | AI 도구 약관, 상업 이용, 저작권, 공공기관 납품 고지, 계약서 조항을 확인한다. |
| 출처 체계 재설계 | 단순 등급표가 아니라 출처 유형, 발행 주체, 원자료 여부, 용도 적합성을 함께 판단한다. |
| 간이 절차 | 1인 운영을 위해 소형·중형·대형 프로젝트 절차를 구분한다. |
| 템플릿 원본 단일화 | 본문 중복 템플릿은 부록 원본 참조 방식으로 관리한다. |
| QA 판정 주체 | ChatGPT는 검토 보조자이며 최종 판정자는 사용자/PM/클라이언트/제작처다. |

## 기본 사용 원칙

1. 먼저 `QUICK_START_CARDS.md`의 빠른 작업 시작 카드를 사용한다.
2. 중형 이상 프로젝트는 `MASTER_BRIEF_TEMPLATE.md`로 Master Brief 초안을 만든다.
3. AI 작업에는 `SYSTEM_INSTRUCTIONS_COMPRESSED.md`의 핵심 지침을 함께 주입한다.
4. 법적·계약 리스크는 `QA_AND_LEGAL_RISK_GATE.md`로 별도 검수한다.
5. 개인 맞춤설정과 프로젝트 지침은 `CUSTOM_INSTRUCTIONS_KO.md`를 사용한다.

## 파일 구성

| 파일 | 용도 |
|---|---|
| `README.md` | V5.1 Patch 1 개요 |
| `V5_1_PATCH1_SYSTEM_MANUAL.md` | 운영 매뉴얼 요약본 |
| `SYSTEM_INSTRUCTIONS_COMPRESSED.md` | ChatGPT / Gemini / Claude / Project 지침용 압축본 |
| `QUICK_START_CARDS.md` | C안 빠른 사용 카드·요청 템플릿 |
| `MASTER_BRIEF_TEMPLATE.md` | Master Brief 템플릿 |
| `QA_AND_LEGAL_RISK_GATE.md` | QA·법적·계약 리스크 게이트 |
| `CUSTOM_INSTRUCTIONS_KO.md` | 개인 맞춤설정·프로젝트 지침용 문안 |
| `SYNC_MANIFEST.md` | 동기화 기록 |
