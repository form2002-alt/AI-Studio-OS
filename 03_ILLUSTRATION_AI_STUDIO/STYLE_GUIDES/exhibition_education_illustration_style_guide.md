# 전시·교육용 일러스트 화풍·표현기법 가이드

문서 목적: 단추파덜 일러스트 AI 스튜디오에서 전시·교육용 일러스트 프롬프트를 만들 때 사용할 기본 화풍·표현기법 기준을 정리한다.

적용 범위: 전시 패널, 설명 캡션, 오브젝트 라벨, 어린이 활동지, 사인그래픽, 포스터, 리플렛, 도록, 영상·미디어월, 체험물, 교육자료.

---

## 1. 기본 원칙

| 구분 | 기준 |
|---|---|
| 최우선 기준 | 예쁜 그림보다 전시·교육용으로 정확하고 실제 사용할 수 있는 그림을 우선한다. |
| 화풍 선택 기준 | 주제, 관람객, 출력 방식, 정보 전달 목적에 맞게 선택한다. |
| 피해야 할 방향 | 실사풍, 게임 콘셉트아트풍, 과도한 만화체, 장식 과다, 정보 왜곡. |
| 역사 주제 | 시대·지역·복식·도구 오류를 방지한다. |
| 과학 주제 | 구조·원리·과정 순서의 정확성을 우선한다. |
| 자연 주제 | 동식물 형태와 식별성을 우선한다. |
| 어린이 콘텐츠 | 친근하지만 지나치게 유아적이거나 상업 캐릭터풍으로 만들지 않는다. |
| 사인그래픽 | 작게 줄여도 즉시 읽혀야 한다. |
| 수채화 기본값 | 자잘한 붓터치를 최소화하고, 넓은 면과 농담 중심, 옅고 차분한 색을 사용한다. |

---

## 2. 대표 화풍 분류

| 대분류 | 대표 화풍 | 적합 용도 | 핵심 특징 |
|---|---|---|---|
| 수채 계열 | 현대적 수채화, 수채+펜화 | 역사·문화·자연 패널 | 부드럽고 품격 있음 |
| 펜화 계열 | 펜앤잉크, 파인라이너, 만년필화 | 역사, 유물, 도감, 구조 설명 | 선명하고 정보 전달력 좋음 |
| 연필 계열 | 흑연 연필, 색연필 | 인물, 자연, 어린이 자료 | 부드럽고 손그림 느낌 |
| 목탄·파스텔 계열 | 목탄화, 모노톤 파스텔 | 역사적 무게감, 전이공간 영상 | 강한 감정과 명암 |
| 과슈·마커 계열 | 과슈, 사인펜, 마커 | 어린이 콘텐츠, 포스터 | 친근하고 색면이 분명함 |
| 판화 계열 | 목판화, 리놀륨 판화, 에칭 | 역사 포스터, 상징 이미지 | 강한 그래픽성 |
| 디지털 계열 | 디지털 라인아트, 벡터, 플랫 일러스트 | 과학, 사인, 인포그래픽 | 수정·출력·가독성 우수 |
| 실루엣·픽토그램 | 검정 실루엣, 단색 아이콘 | 사인그래픽, 영상 소스 | 축소성과 즉시 인식성 우수 |

---

## 3. 수채화 계열 최종 기준

### 3-1. 수채화 기본 방향

| 항목 | 적용 기준 |
|---|---|
| 붓터치 | 자잘한 붓터치를 최소화한다. |
| 표현 방식 | 넓은 색면, 부드러운 농담, 큰 명암 덩어리 중심으로 표현한다. |
| 색감 | 진한 색보다 옅은 색, 저채도, 차분한 색조를 사용한다. |
| 분위기 | 올드한 수채화보다 현대적이고 절제된 전시용 수채화를 지향한다. |
| 세부묘사 | 작은 붓질로 묘사하지 않고 형태와 농담으로 정리한다. |
| 적합 용도 | 역사·문화·자연 패널, 도록, 리플렛, 교육자료. |
| 주의점 | 너무 흐리면 형태 인식이 약해질 수 있으므로 외곽은 명확히 유지한다. |

### 3-2. 수채화 기법 세분화

| 기법 | AI 프롬프트 표현 | 특징 | 추천 용도 |
|---|---|---|---|
| 현대적 수채화 | modern refined watercolor | 깔끔하고 절제된 수채 | 전시 패널 표준 |
| 투명 수채 | transparent watercolor wash | 맑고 가벼운 채색 | 자연·식물·문화 |
| 담채 수채 | light watercolor wash | 옅은 색 중심 | 배경, 보조 삽화 |
| 넓은 수채 번짐 | broad watercolor washes | 넓은 면의 부드러운 번짐 | 포스터, 배경 |
| 수채+펜화 | watercolor and ink illustration | 수채 색면 + 명확한 펜선 | 역사·자연·생활 |
| 디지털 수채 | digital watercolor brush | 수채 느낌을 디지털로 제어 | 영상·편집용 이미지 |

### 3-3. 수채화 기본 프롬프트

```text
Use a modern refined watercolor style with broad washes, large soft color areas, and gentle tonal gradation. Minimize tiny brush strokes and avoid overly detailed brushwork. Use pale, muted, light colors rather than dark or heavily saturated colors. Keep the subject clear, calm, and suitable for contemporary museum educational illustration.
```

### 3-4. 수채화 네거티브 프롬프트

```text
Avoid tiny repetitive brush strokes, overly detailed brushwork, old-fashioned watercolor rendering, dark saturated colors, heavy pigment, muddy colors, excessive texture, fussy details, and decorative brush marks.
```

---

## 4. 펜화 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 만년필화 | fountain pen drawing | 선 굵기 변화, 잉크감 | 역사 인물, 기록화풍 삽화 | 너무 고전적으로 보일 수 있음 |
| 펜앤잉크 | pen and ink drawing | 해칭, 명암선 | 역사, 건축, 유물 | 선이 많으면 어두워짐 |
| 파인라이너 | fine liner line art | 얇고 정확한 선 | 도감, 구조도, 활동지 | 출력 시 선 굵기 확보 |
| 사인펜화 | felt-tip pen illustration | 균일하고 또렷한 선 | 어린이 자료, 캐릭터 | 지나친 만화풍 주의 |
| 브러시펜 | brush pen linework | 굵기 변화와 동세 | 포스터, 인물 | 만화·캘리그래피 느낌 주의 |
| 스티플링 | stippling pen illustration | 점묘 명암 | 자연사, 과학 도감 | 과밀 주의 |
| 크로스해칭 | cross-hatching ink drawing | 교차선 명암 | 빈티지 역사 삽화 | 작게 보면 뭉칠 수 있음 |

기본 프롬프트:

```text
Use clean pen-and-ink linework with controlled hatching, clear outer contours, and minimal internal detail. The drawing should feel like a museum educational field sketch, not a comic illustration.
```

---

## 5. 연필·색연필 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 흑연 연필 | graphite pencil sketch | 부드러운 명암 | 인물, 역사 자료풍 | 미완성 느낌 주의 |
| 정밀 연필화 | detailed graphite pencil drawing | 세밀한 구조 표현 | 자연사, 과학 구조 | 실사처럼 과해질 수 있음 |
| 러프 스케치 | rough pencil sketch | 빠른 콘셉트 느낌 | 스토리보드, 초안 | 최종 납품용에는 약함 |
| 색연필 | colored pencil illustration | 따뜻하고 건조한 질감 | 어린이, 자연, 활동지 | 채도가 약할 수 있음 |
| 색연필+펜선 | colored pencil with ink outlines | 부드러운 색 + 명확한 선 | 어린이 패널 | 과도한 귀여움 주의 |

기본 프롬프트:

```text
Use a refined graphite pencil sketch style with soft shading, visible pencil texture, and clear silhouette. Avoid photorealistic skin detail and excessive wrinkles.
```

---

## 6. 목탄·파스텔 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 목탄화 | charcoal drawing | 강한 명암, 거친 질감 | 역사, 저항, 상실, 노동 | 디테일 손실 주의 |
| 압축 목탄 | compressed charcoal texture | 묵직한 검정 | 전이공간, 영상 배경 | 너무 어두울 수 있음 |
| 모노톤 파스텔 | monochrome pastel drawing | 부드러운 질감과 명암 | 역사 영상, 추상 장면 | 대비 관리 필요 |
| 소프트 파스텔 | soft pastel illustration | 부드러운 번짐 | 자연, 감성 배경 | 형태가 흐려질 수 있음 |
| 오일 파스텔 | oil pastel texture | 두껍고 거친 색층 | 어린이·포스터 | 고급 전시에는 캐주얼할 수 있음 |

기본 프롬프트:

```text
Use a monochrome charcoal and soft pastel texture with strong contrast, rough grain, and expressive edges. Keep the subject readable and suitable for a museum exhibition graphic.
```

---

## 7. 과슈·마커·사인펜 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 과슈 | matte gouache illustration | 매트하고 부드러운 색면 | 어린이 패널, 포스터 | 장식 과다 주의 |
| 플랫 과슈 | flat gouache style | 평면 색면 중심 | 카드뉴스, 어린이 그래픽 | 입체감 부족 가능 |
| 사인펜 | felt-tip marker drawing | 또렷하고 친근한 선 | 활동지, 미션카드 | 유아적 느낌 주의 |
| 알코올 마커 | alcohol marker illustration | 균일한 면, 선명한 색 | 캐릭터, 제품 스케치 | 상업 일러스트 느낌 |
| 브러시 마커 | brush marker illustration | 굵기 변화 있는 선 | 포스터, 동세 있는 인물 | 만화풍 주의 |

기본 프롬프트:

```text
Use a matte gouache illustration style with clean shapes, soft but opaque color blocks, and restrained details suitable for museum panels.
```

---

## 8. 판화·인쇄 질감 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 목판화 | woodcut print style | 굵은 선, 절삭감 | 역사 포스터, 민속 주제 | 거칠고 강한 인상 |
| 리놀륨 판화 | linocut illustration | 단순하고 평평한 절개선 | 아이콘, 포스터 | 세부 표현 제한 |
| 에칭 | etching style illustration | 섬세한 선과 해칭 | 고전 자료풍 | 서양 고전 삽화 느낌 |
| 실크스크린 | silkscreen print style | 제한 색상, 평면 인쇄 | 포스터, 그래픽 패턴 | 색수 제한 필요 |
| 리소그래프 | risograph print texture | 빈티지 인쇄 질감 | 카드뉴스, 포스터 | 전시 고급감 검토 필요 |

기본 프롬프트:

```text
Use a restrained woodcut print style with bold carved edges, limited colors, and strong silhouette readability. Avoid excessive decorative patterns.
```

---

## 9. 동양화·수묵 계열

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 수묵화 | ink wash painting | 먹 농담, 여백 | 한국 자연, 역사, 문화 | 일본·중국풍 혼입 주의 |
| 수묵담채 | ink wash with light color | 먹선 + 옅은 색 | 전통문화, 자연 | 색이 탁해질 수 있음 |
| 백묘화 | traditional ink line drawing | 채색 없이 선 중심 | 복식, 유물, 인물 설명 | 세부 고증 필요 |
| 현대 수묵 | contemporary ink wash illustration | 전통 먹질감 + 현대 구성 | 특별전 비주얼 | 지나친 추상화 주의 |

한국 역사·문화 주제에서 피할 표현:

| 피해야 할 표현 | 이유 |
|---|---|
| Japanese ink painting style | 일본풍 오인 위험 |
| ukiyo-e style | 일본 목판화풍으로 변질 |
| samurai-era ink illustration | 한국 역사 주제와 부적합 |
| oriental style | 너무 포괄적이고 고정관념적 표현 |

기본 프롬프트:

```text
Use contemporary Korean ink wash-inspired illustration with restrained brush texture, clear subject silhouette, and generous negative space. Avoid Japanese ukiyo-e, samurai, or kimono-like visual elements.
```

---

## 10. 디지털·컴퓨터 기반 기법

| 기법 | AI 프롬프트 표현 | 특징 | 적합 용도 | 주의점 |
|---|---|---|---|---|
| 디지털 라인아트 | clean digital ink line art | 균일하고 명확한 선 | 과학, 구조도, 활동지 | 차갑게 보일 수 있음 |
| 벡터 일러스트 | clean vector illustration | 선명한 면과 선 | 사인, 인포그래픽 | 감성 부족 가능 |
| 플랫 일러스트 | flat illustration | 단순한 색면 | 카드뉴스, 안내 그래픽 | 단순화 과다 주의 |
| 아이소메트릭 | isometric vector illustration | 3/4 입체 도식 | 공간·과정 설명 | 역사 인물에는 부적합 |
| 디지털 수채 | digital watercolor brush | 수채 질감의 디지털 제어 | 영상·패널 | 너무 인공적일 수 있음 |
| 디지털 페인팅 | digital painting | 회화적 브러시 | 포스터, 영상 콘셉트 | 게임 콘셉트아트로 흐를 수 있음 |
| 디지털 콜라주 | digital collage illustration | 여러 재료 조합 | 현대적 포스터 | 저작권 이미지 혼입 주의 |
| 벡터 실루엣 | solid black vector silhouette | 단색 외곽선 | 사인, 영상 소스 | 내부 정보 표현 불가 |

기본 프롬프트:

```text
Use clean digital ink line art with subtle paper texture, restrained shading, and clear museum educational readability. Avoid game concept art, glossy 3D rendering, and commercial mascot style.
```

---

## 11. 전시 공간별 추천 화풍

| 사용 공간 | 1순위 화풍 | 2순위 화풍 | 비추천 |
|---|---|---|---|
| 전시 패널 | 수채+펜화 | 디지털 라인아트 | 지나친 실사풍, 장식 과다 |
| 설명 캡션 | 파인라이너 | 미니 벡터 | 복잡한 수채, 목탄 |
| 오브젝트 라벨 | 파인라이너 | 단순 라인아트 | 진한 배경 이미지 |
| 어린이 활동지 | 굵은 라인아트 | 사인펜화 | 목탄, 복잡한 수묵 |
| 과학관 패널 | 벡터 구조도 | 디지털 라인아트 | 수채 번짐, 목탄 |
| 자연사 패널 | 자연사 도감풍 | 수채+파인라이너 | 캐릭터풍 단순화 |
| 역사관 패널 | 수채+펜화 | 펜앤잉크, 목탄 | 게임풍, 영화 포스터풍 |
| 사인그래픽 | 픽토그램 | 벡터 실루엣 | 수채, 디지털 페인팅 |
| 포스터 | 과슈, 판화 | 목탄, 제한색 그래픽 | 설명 도식 과다 |
| 영상·미디어월 | 레이어형 디지털 일러스트 | 목탄, 파스텔, 수채 번짐 | 세밀한 펜화 단독 |
| 도록·리플렛 | 수채 스폿 | 라인아트 | 무거운 목탄 과다 |

---

## 12. 전시 분야별 추천 화풍

### 역사·기념관

| 세부 주제 | 추천 화풍 | 이유 |
|---|---|---|
| 역사 인물 | 수채+펜화 | 복식과 분위기 균형 |
| 민중 생활 | 담채 수채+펜 | 생활 장면을 부드럽게 전달 |
| 독립운동 | 목탄, 모노톤 펜화 | 무게감과 기억성 |
| 노동·수탈 | 목탄 실루엣, 펜앤잉크 | 강도 높은 노동과 상징성 |
| 유물 설명 | 파인라이너, 수채+펜 | 형태와 구조 전달 |
| 지도·연표 | 벡터, 디지털 라인아트 | 정보 구조화에 적합 |
| 상징 포스터 | 판화, 과슈, 목탄 | 강한 대표성 |

### 과학관

| 세부 주제 | 추천 화풍 | 이유 |
|---|---|---|
| 원리 설명 | 벡터 도식 | 흐름·관계 표시가 쉬움 |
| 구조 설명 | 디지털 라인아트 | 라벨·단면 표현에 적합 |
| 실험 과정 | 플랫 과정도 | 단계가 명확함 |
| 생물 구조 | 자연사 도감풍 | 형태 정확성 우수 |
| 천문·우주 | 디지털 페인팅+인포그래픽 | 분위기와 정보 균형 |
| 기계·기술 | 아이소메트릭 벡터 | 구조와 공간 이해에 좋음 |
| 어린이 과학 | 과슈, 플랫 | 친근하고 명확함 |

### 자연사·생태관

| 세부 주제 | 추천 화풍 | 이유 |
|---|---|---|
| 동물 단일 대상 | 자연사 도감풍 | 식별성 우수 |
| 식물 단일 대상 | 보태니컬 수채+파인라이너 | 잎·줄기·꽃 구조 표현 |
| 생태계 장면 | 수채+펜화 | 자연성과 설명성 균형 |
| 먹이사슬 | 벡터 인포그래픽 | 관계 설명에 적합 |
| 서식지 지도 | 벡터 지도 | 공간 정보 전달 |
| 멸종위기종 | 자연사 도감풍, 수채+펜 | 정확성과 감성 균형 |
| 어린이 생태 | 과슈, 색연필 | 친근한 자연 학습 |

### 어린이 체험관

| 세부 주제 | 추천 화풍 | 이유 |
|---|---|---|
| 안내 캐릭터 | 과슈, 플랫 캐릭터 | 친근하고 안정적 |
| 미션 카드 | 굵은 라인아트, 사인펜 | 행동 이해가 빠름 |
| 체험 방법 안내 | 픽토그램+캐릭터 | 동작 전달에 좋음 |
| 안전 안내 | 친근한 픽토그램 | 위험 행동을 명확히 전달 |
| 활동지 | 흑백 라인아트 | 인쇄와 색칠 활동에 적합 |
| 스티커·보상 이미지 | 벡터, 과슈 | 재사용성 좋음 |
| 세계관 배경 | 과슈, 수채 | 따뜻한 분위기 조성 |

### 문화·민속·지역 전시

| 세부 주제 | 추천 화풍 | 이유 |
|---|---|---|
| 전통시장 | 수채+펜화 | 사람·공간·물건 표현 균형 |
| 민속놀이 | 수채+펜화, 플랫 | 동작 설명에 좋음 |
| 지역 풍경 | 현대적 수채 | 부드럽고 품격 있음 |
| 음식 문화 | 과슈, 수채+펜 | 색감과 형태 전달 |
| 전통 도구 | 파인라이너, 수채+펜 | 구조와 재질 설명 |
| 축제 | 과슈, 플랫 | 밝고 활기 있는 표현 |
| 생활문화 지도 | 벡터 지도, 아이콘 지도 | 정보 정리에 적합 |

---

## 13. 관람객별 화풍 선택

| 관람객 | 추천 화풍 | 피해야 할 방향 |
|---|---|---|
| 일반 관람객 | 수채+펜화, 디지털 라인아트, 벡터 | 지나친 추상화 |
| 어린이 | 과슈, 사인펜, 굵은 라인아트, 플랫 | 어두운 목탄, 과도한 세부묘사 |
| 청소년 | 디지털 라인아트, 인포그래픽, 벡터 | 유아적 캐릭터 |
| 가족 관람객 | 수채+펜화, 과슈, 자연사 도감풍 | 너무 학술적인 도식 |
| 전문가 | 파인라이너, 구조도, 자연사 도감풍 | 귀여운 단순화 |
| 외국인 관람객 | 픽토그램, 명확한 벡터, 장면형 삽화 | 텍스트 의존 이미지 |

---

## 14. 제작 조건별 추천 화풍

| 제작 조건 | 추천 화풍 | 이유 |
|---|---|---|
| 대형 출력 | 벡터, 디지털 라인아트, 과슈 | 확대 시 선명함 |
| 소형 캡션 | 파인라이너, 벡터 아이콘 | 축소 가독성 우수 |
| 흑백 인쇄 | 라인아트, 실루엣, 펜화 | 출력 안정적 |
| 색칠 활동지 | 굵은 라인아트 | 어린이 활동에 적합 |
| 영상 애니메이션 | 레이어형 벡터, 수채+펜 | 움직임 제작 용이 |
| 투명 PNG 필요 | 실루엣, 라인아트, 단일 대상 | 합성 쉬움 |
| 벡터화 필요 | 실루엣, 픽토그램, 플랫 | 사인 적용 쉬움 |
| 고증 검토 필요 | 펜화, 수채+펜화 | 세부 요소 통제 가능 |
| 분위기 전달 우선 | 목탄, 파스텔, 수묵, 디지털 페인팅 | 감정 표현 강함 |
| 정보 전달 우선 | 벡터, 라인아트, 도식 | 구조와 순서 명확 |

---

## 15. 화풍별 전시 적합성 매트릭스

| 화풍 | 정보 전달 | 감성 표현 | 고증 통제 | 어린이 적합 | 사인 활용 | 영상 활용 |
|---|---:|---:|---:|---:|---:|---:|
| 수채+펜화 | 높음 | 높음 | 높음 | 중상 | 중간 | 중상 |
| 현대적 수채화 | 중상 | 높음 | 중간 | 중상 | 낮음 | 중상 |
| 파인라이너 | 매우 높음 | 중간 | 높음 | 중상 | 중상 | 중간 |
| 벡터 | 매우 높음 | 중간 | 중상 | 높음 | 매우 높음 | 높음 |
| 실루엣 | 중간 | 높음 | 중상 | 중간 | 매우 높음 | 매우 높음 |
| 디지털 라인아트 | 매우 높음 | 중상 | 높음 | 높음 | 높음 | 높음 |
| 과슈 | 중상 | 높음 | 중간 | 매우 높음 | 중간 | 중상 |
| 색연필 | 중간 | 높음 | 중간 | 높음 | 낮음 | 낮음 |
| 목탄 | 낮음~중간 | 매우 높음 | 중간 | 낮음 | 중간 | 높음 |
| 수묵 | 중간 | 높음 | 중간 | 낮음~중간 | 낮음 | 중상 |
| 판화 | 중간 | 매우 높음 | 중간 | 낮음~중간 | 중상 | 중간 |
| 디지털 페인팅 | 중간 | 매우 높음 | 낮음~중간 | 중간 | 낮음 | 높음 |

---

## 16. AI 프롬프트 조립 공식

### 기본 공식

```text
Use [큰 화풍] with [구체 기법], [선 처리], and [질감].
Keep the forms [디테일 수준] for [사용 목적].
Avoid [금지 스타일].
```

### 정보 설명형

```text
Create a museum educational illustration of [주제].
Use [화풍] with [구체 기법].
Keep the forms accurate, readable, and not overly decorative.
Leave enough clear space for panel layout.
Avoid photorealism, fantasy elements, inaccurate details, and visual clutter.
```

### 역사 고증형

```text
Create a historically restrained museum illustration of [주제].
Use [화풍] with clear linework and controlled details.
Depict clothing, tools, posture, and setting cautiously according to [시대/지역].
Do not invent unsupported details.
Avoid modern objects, foreign costume elements, fantasy dramatization, and heroic exaggeration.
```

### 과학·구조 설명형

```text
Create a clean educational diagram of [주제].
Use digital line art and flat colors.
Show the structure, labels, arrows, and process order clearly.
Keep the layout simple and accurate for museum learning.
Avoid misleading diagrams, reversed process order, decorative clutter, and inaccurate proportions.
```

### 어린이 체험형

```text
Create a child-friendly educational illustration of [주제].
Use simple shapes, warm colors, bold outlines, and clear actions.
The image should be friendly but not overly childish or commercial mascot-like.
Avoid unsafe actions, exaggerated facial features, and excessive decoration.
```

### 사인그래픽형

```text
Create a minimal exhibition signage icon of [주제].
Use a clean vector pictogram style with a strong silhouette and simple geometry.
The image must remain readable at small size.
Avoid internal details, gradients, shading, texture, facial details, and decorative elements.
```

### 영상 소스형

```text
Create a layered exhibition media illustration of [주제].
Use [화풍] with separated foreground, middle ground, and background elements.
Keep the composition suitable for animation and projection.
Avoid excessive detail, tiny elements, complex textures, and elements that are difficult to separate into layers.
```

---

## 17. 최종 추천 조합

| 목적 | 가장 안정적인 조합 | 대체 조합 | 비추천 |
|---|---|---|---|
| 역사 인물 전신 | 수채+펜화 | 연필+펜, 펜앤잉크 | 3D, 게임풍 디지털 페인팅 |
| 1920년대 노동자 | 목탄 실루엣 | 펜앤잉크, 모노톤 수채 | 현대 마커 캐릭터 |
| 과학 원리 | 벡터 도식 | 디지털 라인아트 | 수채 번짐, 목탄 |
| 식물 관찰 | 수채+파인라이너 | 보태니컬 색연필 | 플랫 캐릭터 |
| 동물 생태 | 자연사 도감풍 | 수채+펜화 | 실루엣 단독 |
| 어린이 활동지 | 굵은 라인아트 | 사인펜, 플랫 | 목탄, 복잡한 수묵 |
| 안내 사인 | 픽토그램 | 실루엣, 벡터 아이콘 | 수채, 디지털 페인팅 |
| 전시 포스터 | 과슈, 판화 | 목탄, 디지털 페인팅 | 설명 도식 과다 |
| 영상 배경 | 목탄, 파스텔 | 수채 번짐, 디지털 페인팅 | 세밀한 펜화 단독 |
| 리플렛 보조컷 | 수채 스폿 | 라인아트 | 무거운 목탄 |

---

## 18. 공통 네거티브 프롬프트

```text
Avoid photorealism, anime style, manga style, game concept art, glossy 3D rendering, commercial mascot style, excessive decoration, cluttered background, random props, inaccurate anatomy, incorrect proportions, distorted hands, distorted feet, unreadable pose, overly dramatic lighting, fantasy elements, stock image look, low-quality composition, text artifacts, watermark, logo, signature.
```

### 분야별 추가 네거티브

| 분야 | 추가 네거티브 |
|---|---|
| 역사 | anachronistic objects, modern clothing, modern tools, foreign costume elements, Japanese kimono, geta, zori, waraji, samurai elements |
| 과학 | incorrect scientific structure, misleading diagram, reversed process order, inaccurate labels |
| 자연 | generic animal shape, fantasy anatomy, incorrect plant structure, inaccurate species features |
| 어린이 | overly childish proportions, commercial mascot style, unsafe actions, oversized anime eyes |
| 실루엣 | internal details, gradients, shadows, texture, facial details, merged limbs, unclear silhouette |
| 수채화 | tiny repetitive brush strokes, overly detailed brushwork, old-fashioned watercolor rendering, dark saturated colors, heavy pigment, muddy colors |

---

## 19. 최종 검수표

| 검수 항목 | 통과 기준 |
|---|---|
| 목적 적합성 | 전시 패널, 활동지, 사인, 영상 등 실제 용도와 화풍이 맞음 |
| 정보 가독성 | 주제·형태·행동·구조가 빠르게 읽힘 |
| 출력 안정성 | 확대·축소·흑백 인쇄·투명 배경 적용 가능성이 있음 |
| 고증 안정성 | 역사·문화 주제에서 시대착오와 외국풍 혼입이 없음 |
| 과학 정확성 | 구조·과정·방향·라벨이 주제와 맞음 |
| 자연 식별성 | 동식물의 형태와 특징이 구분됨 |
| 어린이 적합성 | 친근하지만 유아적 과장이나 위험 행동이 없음 |
| 사인 적합성 | 작은 크기에서도 의미가 유지됨 |
| 영상 제작성 | 레이어 분리, 움직임 적용, 배경 합성이 가능함 |
| 스타일 일관성 | 같은 전시 안에서 선 굵기, 채도, 질감이 통일됨 |
| 수채화 품질 | 자잘한 붓터치 없이 넓은 면과 농담으로 현대적으로 표현됨 |
| 금지 요소 배제 | 실사풍, 게임풍, 애니풍, 상업 캐릭터풍, 장식 과다가 없음 |

---

## 20. 가장 실무적인 기본 세트

| 기본 세트 | 주 용도 | 설명 |
|---|---|---|
| 현대적 수채+펜화 | 역사·문화·자연 패널 | 가장 안정적인 전시 교육용 기본 화풍 |
| 디지털 라인아트 | 과학·구조·과정 설명 | 정확성, 라벨, 수정에 강함 |
| 벡터 일러스트 | 인포그래픽·사인·지도 | 출력·확장·통일성 우수 |
| 굵은 라인아트 | 어린이 활동지·워크북 | 인쇄와 색칠 활동에 적합 |
| 과슈 | 어린이 체험관·포스터 | 친근하고 따뜻한 색면 |
| 목탄·모노톤 파스텔 | 역사적 분위기·전이공간 영상 | 감정과 상징 전달에 적합 |
| 실루엣 | 사인그래픽·영상 소스 | 외곽선만으로 강한 인식성 |

---

## 21. 최종 기준 한 줄 요약

| 상황 | 선택 |
|---|---|
| 전시 패널 표준 | 현대적 수채+펜화 |
| 과학 설명 표준 | 디지털 라인아트 / 벡터 도식 |
| 어린이 활동 표준 | 굵은 라인아트 / 과슈 / 사인펜 |
| 역사적 무게감 | 목탄 / 모노톤 파스텔 / 펜앤잉크 |
| 사인그래픽 | 픽토그램 / 벡터 / 실루엣 |
| 영상·미디어월 | 레이어형 디지털 일러스트 / 목탄 / 파스텔 / 수채 번짐 |
| 수채화 기본 방향 | 자잘한 붓터치 없이 넓은 면, 부드러운 농담, 옅은 색감 |
