# AeroPass | 10초 AI 브랜드 광고 제작 기록

> **최종 메시지:** 기다림은 짧게, 당신의 시간은 더 길게.

## 1. 프로젝트 개요

| 항목 | 내용 |
| --- | --- |
| 브랜드 | **AeroPass** (가상 공항 패스 서비스) |
| 서비스 | 스마트폰 탑승권 인식으로 빠른 통로 이용 경험을 제공하는 공항 패스 |
| 타깃 | 출장·여행으로 공항을 자주 이용하며 대기 시간을 아끼고 싶은 여행자 |
| USP | 붐비는 공항에서 빠르고 차분한 이동 경험으로 시간을 되돌려 준다. |
| 광고 목적 | AeroPass의 빠르고 편안한 공항 이동 경험을 인지시킨다. |
| 핵심 메시지 | **“기다림은 짧게, 당신의 시간은 더 길게.”** |
| 톤앤매너 | 딥 네이비 공항 공간, 절제된 청록(Teal) 빛, 프리미엄·미래적·차분한 시네마틱 무드 |
| 최종 형식 | 16:9, 1080p HD, 30fps, 약 10초 |
| 최종 영상 | `AreoPass_BrandADAug11_2.mp4` |

## 2. 기획 의도와 서사

광고는 **혼잡(문제) → 휴대폰 인식(전환) → 밝은 탑승 게이트(해결) → 브랜드명·슬로건(기억)** 흐름으로 구성했다.

인물은 검은 롱코트와 검은 기내용 캐리어를 든 뒷모습으로 고정했다. 얼굴을 노출하지 않아 생성 이미지 간 인물 얼굴의 불일치를 줄이고, 시선이 ‘공항의 대기 시간’과 ‘AeroPass의 인식 경험’에 머물도록 설계했다.

## 3. 공통 비주얼 가이드

| 요소 | 고정 조건 |
| --- | --- |
| 주인공 | 성인 여행자, 검은 테일러드 롱코트, 검은 하드셸 캐리어, 얼굴 미노출·뒷모습 |
| 스캐너 | 세로로 슬림한 실버·그라파이트 기둥, 상단 사각 인식 패널, 얇은 청록 LED |
| 색감 | 딥 네이비 그림자 + 청록 포인트 + 마지막 장면의 밝고 차가운 자연광 |
| 화면 비율 | 제작 및 편집 기준 16:9 |
| 텍스트 | AI 이미지 안에는 텍스트를 만들지 않고, 마지막 엔드 카드에서 Final Cut Pro 제목 기능으로 삽입 |

### 에셋 규격·파일 정리 규칙

- 편집 마스터는 **16:9 / 1080p HD / 30fps**로 통일했다. 원본 이미지나 영상의 비율이 다를 경우 Final Cut Pro에서 화면을 채우되, 인물·스캐너·비행기가 잘리지 않도록 프레이밍을 조정했다.
- 색감은 모든 씬에서 `deep navy + teal`을 공통 키워드로 유지하고, 마지막 탑승 게이트만 밝은 자연광으로 전환해 문제 해결의 감정을 강조했다.
- 파일명은 `AeroPass_[역할]_Sc[씬번호]` 형식으로 정리했다. 예: `AeroPassSC1_good...`, `AeroScan_Sc01`, `AeroScan_Sc3`, `AeroPass_Sound1`.
- 이미지, 영상, 음성, 음악을 Final Cut Pro 라이브러리 `AeroPass_BrandAd`에 모아 재사용 가능한 원본으로 유지했다.

## 3-1. 제작 파이프라인

```text
브랜드·메시지 정의
  → 공통 인물·색감·스캐너 규격 고정
  → Text-to-Image로 씬별 기준 이미지 생성·선별
  → 참조 이미지를 넣어 Image-to-Video로 필요한 움직임만 생성
  → AI 음성·BGM·인식음 생성
  → Final Cut Pro에서 컷·타이포·음량·페이드 통합
  → 약 10초 MP4로 출력 및 재생 검수
```

생성 전에 스토리보드와 기준 이미지를 먼저 확정하고, 생성 후에는 ‘인물의 뒷모습·캐리어·스캐너·색감’이 맞는 결과만 선택했다. 이 순서로 재생성 횟수를 줄였다.

## 4. 스토리보드

### 씬 1 — 대기 (0:00–0:04.3 / 약 4.3초)

| 필드 | 내용 |
| --- | --- |
| 목표 메시지 | 혼잡한 공항에서 여행자의 시간이 멈춰 있는 문제를 보여 준다. |
| 화면 구성 | 붐비는 국제공항 보안 대기열. 검은 롱코트와 캐리어의 주인공이 뒷모습으로 서 있고, 주변 승객과 가방이 화면을 채운다. |
| 화면 카피/내레이션 | 없음. 공항의 혼잡한 분위기와 음악의 긴장감으로 시작한다. |
| 사용 도구와 목적 | **학습 네이토 gpt-image-2**로 혼잡 공항 기준 이미지를 생성하고, **ElevenLabs Image & Video / Veo**로 선택 이미지를 짧은 영상으로 변환했다. |
| 입력 프롬프트 (원문) | `A premium cinematic airport technology commercial, widescreen 16:9. Inside a modern international airport security area, a crowded queue of travelers moving past with slight motion blur, rolling suitcase wheels and legs in the foreground. One adult traveler is paused in the center, seen only from behind, wearing a black tailored long coat and holding a black carry-on suitcase. No visible face. Deep navy ambient lighting with restrained teal accent lights, realistic premium advertising photography, 35mm cinematic lens, high contrast, subtle film grain. No readable text, no logos, no watermark.` |
| 출력 결과 요약 | 혼잡한 줄과 뒷모습의 주인공이 확실히 보이는 인트로 비주얼을 확보했다. |
| 결과 파일 | `AeroPassSC1_good he_2026-08-11T00_15_43` |

### 씬 2 — 인식 (0:04.3–0:06.3 / 약 2.0초)

| 필드 | 내용 |
| --- | --- |
| 목표 메시지 | AeroPass는 복잡한 절차 대신 한 번의 인식으로 다음 단계로 연결된다는 점을 전달한다. |
| 화면 구성 | 휴대폰을 슬림한 공항 스캐너의 상단 패널에 가까이 대는 클로즈업. 청록 LED가 점등된다. 배경의 공항 혼잡은 흐리게 처리한다. |
| 화면 카피/내레이션 | 짧고 깨끗한 인식음. |
| 사용 도구와 목적 | **학습 네이토 gpt-image-2**로 손·휴대폰·스캐너 클로즈업을 생성했다. **ElevenLabs Image & Video / Veo**와 **Adobe Firefly Generate Video**는 해당 정지 이미지에 움직임을 주기 위한 이미지-투-비디오 후보 도구로 사용했다. |
| 입력 프롬프트 (원문) | `Extreme close-up of the upper scanning surface of the exact same tall, slim, freestanding airport scanner pedestal from the previous scene. The scanner is a narrow vertical graphite-black and silver column with a small rectangular scanner panel at the top and one thin teal LED light running vertically along its edge. It is not a large box, not a wall-mounted device, and not a different scanner design. Only the top section of this slim scanner pedestal is visible. A natural hand in a black coat sleeve holds a glossy black smartphone a few centimeters from the scanner. A thin teal scanning light glows between them. No face, no full body, no wide airport view, no text, no logos, no watermark.` |
| 출력 결과 요약 | 스캐너·휴대폰·손의 거리와 청록 LED가 명확한 인식 클로즈업을 만들었다. |
| 결과 파일 | `AeroScan_Sc01` |

### 씬 3 — 통과와 출발 (0:06.3–0:08.3 / 약 2.0초)

| 필드 | 내용 |
| --- | --- |
| 목표 메시지 | 혼잡했던 대기 경험이 밝고 여유로운 출발의 순간으로 바뀐다는 가치를 보여 준다. |
| 화면 구성 | 보안·체크인 이후의 밝은 탑승 게이트. 주인공이 캐리어를 끌고 걸으며, 대형 창밖에는 제트브리지에 연결된 여객기가 보인다. |
| 화면 카피/내레이션 | `기다림은 짧게.` |
| 사용 도구와 목적 | **Adobe Firefly / Gemini**로 탑승 게이트의 키 비주얼을 생성했고, **ElevenLabs Image & Video / Veo**로 짧은 이동감을 보강했다. |
| 입력 프롬프트 (원문) | `Bright premium airport boarding gate in daytime, widescreen 16:9. A traveler in a black long coat pulls a black carry-on suitcase toward a boarding gate, seen from behind. Large windows clearly show a passenger airplane and jet bridge outside. Soft warm daylight fills the terminal. The mood is calm, optimistic, and full of anticipation. The area is a boarding gate lounge after security. No scanner, no security gate, no check-in counter, no teal scanning lights. A few distant passengers wait near the boarding entrance. Realistic cinematic photography, bright clean floor, elegant travel commercial. No readable text, no logos, no watermark.` |
| 출력 결과 요약 | 보안 구역과 구분되는 밝은 탑승 게이트와 실제 항공기가 보이는 마무리 장면을 확보했다. |
| 결과 파일 | `AeroScan_Sc3` |

### 씬 4 — 엔드 카드 (0:08.3–0:10.0 / 약 1.7초)

| 필드 | 내용 |
| --- | --- |
| 목표 메시지 | 브랜드와 약속을 명확하게 남긴다. |
| 화면 구성 | 씬 3의 밝은 탑승 게이트 장면을 유지한다. `AeroPass`는 상단 중앙, 슬로건은 우측의 어두운 게이트 영역에 배치한다. 마지막 짧은 구간에 화면과 글자를 함께 페이드 아웃한다. |
| 화면 카피/내레이션 | 화면: `AeroPass` / `기다림은 짧게, 당신의 시간은 더 길게.`<br>음성: `기다림은 짧게. 당신의 시간은 더 길게. 에어로패스.` |
| 사용 도구와 목적 | **Final Cut Pro**로 제목, 슬로건, 페이드 아웃, 오디오 레벨을 통합했다. 편집 도구는 AI 결과물을 교체하지 않고 컷 편집·자막·간단한 오디오 조정에만 사용했다. |
| 입력 프롬프트 | 해당 없음 — 생성된 씬 3의 결과물을 Final Cut Pro에서 엔드 카드로 확장했다. |
| 출력 결과 요약 | 밝은 출발 장면 위에 브랜드명·슬로건을 겹쳐, 마지막 3초 안에 브랜드를 기억하도록 완성했다. |
| 결과 파일 | 최종 편집 `AreoPass_BrandADAug11_2.mp4` |

## 5. 오디오 설계

| 구간 | 사용 요소 | 생성 도구 | 목적 |
| --- | --- | --- | --- |
| 0:00–0:04.3 | 긴장감 있는 전자 리듬과 공항 분위기 | ElevenLabs Music / 사운드 효과 | 혼잡과 대기의 압박감을 만든다. |
| 0:04.3–0:06.3 | 짧은 디지털 인식음 | ElevenLabs Sound Effects | 휴대폰 인식의 전환점을 명확히 한다. |
| 0:06.3–0:10.0 | 밝아지는 신스·시네마틱 음악 | ElevenLabs Music | 탑승 게이트로 이동하는 해방감과 기대감을 만든다. |
| 0:06.1–0:09.9 | 한국어 내레이션 | ElevenLabs Text to Speech | 슬로건을 음성으로 한 번 더 각인한다. |

### 내레이션 입력문

```text
기다림은 짧게.

당신의 시간은 더 길게.

에어로패스.
```

### BGM 입력 프롬프트

```text
Cinematic high-end travel technology commercial, 10 seconds. Start with urgent rhythmic ticking, deep electronic bass pulse, and fast muted percussion to evoke a crowded airport rush. At 4 seconds, a sharp clean digital scan chime. Immediately open into a powerful uplifting synth swell with bright cinematic chords and a confident premium finish. Dynamic, emotional, modern, polished. No vocals, no lyrics.
```

## 6. 프롬프트 수정 전/후 기록

### 문제: 공항이 충분히 혼잡하지 않고, 주인공과 스캐너의 위치 관계가 불명확했다.

| 구분 | 내용 |
| --- | --- |
| 수정 전 프롬프트 | `Deep navy ambient lighting with restrained teal accent lights, realistic premium advertising photography, 35mm cinematic lens, shallow depth of field, high contrast, subtle film grain. Clean negative space in the upper right area for later advertising copy. No readable text, no logos, no watermark, no distorted hands, no visible faces.` |
| 수정 전 결과/문제 | 인물과 게이트는 나왔지만 빈 공간이 많고, ‘줄을 서서 스캐너까지 다가가는’ 서사가 약했다. |
| 수정 후 핵심 변경 | `Three parallel security lanes are packed shoulder-to-shoulder`, `No empty queue lanes and no empty floor space`, `the scanner is directly ahead`, `The traveler has not scanned yet`를 추가했다. |
| 수정 후 프롬프트 | `A premium cinematic airport security commercial, widescreen 16:9. Inside the same crowded standard airport security queue, the same traveler in a black tailored long coat has reached the front of the line. A single smart scanner pedestal is directly ahead, about one meter away. The traveler is walking one final step toward the scanner but is not holding the phone to it yet. Behind the traveler, the ordinary security queue remains tightly packed with many waiting travelers and suitcases. There is no open fast lane. The scanner is ahead of the traveler; it is not behind the traveler and not beside the traveler. Deep navy airport ambience, restrained teal accent light, realistic premium travel technology commercial, cinematic rear three-quarter camera angle, 35mm lens, high contrast, subtle film grain. No readable text, no logos, no watermark, no visible face.` |
| 결과 변화 | 혼잡한 줄, 주인공, 스캐너의 전후 관계가 명확해져 다음 스캔 클로즈업으로 컷 연결하기 쉬워졌다. |

## 7. 일관성 유지와 도구 선택

### 레퍼런스 사용

- 공통 인물 조건을 모든 프롬프트에 반복했다: **검은 롱코트, 검은 캐리어, 뒷모습, 얼굴 미노출**.
- 스캐너 클로즈업을 마스터 레퍼런스로 정하고, Firefly와 ElevenLabs의 이미지 참조 기능에 인물·스캐너 이미지를 첨부했다.
- 스캐너의 **슬림한 세로 실루엣, 상단 사각 패널, 청록 LED**를 반복 조건으로 지정했다.
- 생성 결과 사이의 미세한 형태 차이는 휴대폰 인식음과 청록 LED 점등 순간에 와이드 샷에서 클로즈업으로 컷 전환해 완화했다.

### 도구별 역할과 선택 이유

| 도구 | 역할 | 선택 이유 / 한계 |
| --- | --- | --- |
| 학습 네이토 `gpt-image-2` | 초안 이미지, 혼잡도·구도 탐색 | 긴 프롬프트와 빠른 시도에 적합했지만 전용 캐릭터 레퍼런스 제어가 약해 단독으로 일관성을 유지하기 어려웠다. |
| Adobe Firefly (Gemini/Generate Video) | 참조 이미지를 활용한 키 비주얼·이미지-투-비디오 | 레퍼런스 이미지를 첨부할 수 있어 의상·색감·스캐너의 조건을 고정하는 데 유리했다. 단, 파트너 모델/비디오 생성은 프리미엄 크레딧 제약이 있었다. |
| ElevenLabs Image & Video / Veo | 짧은 영상 생성·변환 | 선택한 이미지에서 ‘걷기 → 휴대폰 접근 → LED 인식’ 같은 짧은 움직임을 만들기 위해 사용했다. |
| ElevenLabs TTS / Music / Sound Effects | 내레이션, BGM, 인식음 | 10초 광고의 음성·음악·효과음을 같은 AI 생태계에서 빠르게 만들고 톤을 조절할 수 있었다. |
| Final Cut Pro | 통합 편집 | AI 생성 시각·청각 결과물을 컷, 제목, 페이드, 음량으로 통합하는 용도로만 사용했다. |

### Text-to-Image와 Image-to-Video 선택 기준

| 구분 | 프로젝트에서의 역할 | 선택 이유 |
| --- | --- | --- |
| Text-to-Image | 혼잡도, 인물 위치, 스캐너 형태, 탑승 게이트 구도를 먼저 확정 | 한 장면의 구도와 디자인을 반복 수정하기에 빠르고 상대적으로 저렴했다. |
| Image-to-Video | ‘한 걸음 이동’, ‘휴대폰 접근’, ‘청록 LED 점등’처럼 짧은 움직임만 생성 | 기준 이미지를 참조로 쓰면 인물·공항 구조가 새로 바뀌는 위험을 낮출 수 있었다. |
| Text-to-Video를 주력으로 쓰지 않은 이유 | 장면마다 인물·스캐너·공항 구조가 달라질 가능성이 컸다. | 10초 광고에서 일관성과 제어 가능성을 품질보다 우선해, 이미지 기준 방식으로 전환했다. |

### 도구 선택의 우선순위

우선순위는 **제어 가능성과 일관성 → 결과 품질 → 비용·크레딧 → 생성 속도**였다. 짧은 광고에서는 화려한 한 번의 결과보다 같은 인물·스캐너·색감이 이어지는 것이 브랜드 신뢰에 더 중요하다고 판단했다.

## 8. 크레딧·대기열 제약 대응

영상 생성에는 크레딧이 많이 들고 Firefly의 파트너 모델은 프리미엄 크레딧 부족 메시지가 발생했다. 그래서 다음 전략으로 범위를 조정했다.

1. 텍스트-투-비디오를 반복 생성하지 않고 먼저 정지 이미지에서 인물·공항·스캐너 구도를 확정했다.
2. 5개 장면을 모두 새 영상으로 만들지 않고, 핵심 움직임이 필요한 장면만 이미지-투-비디오로 생성했다.
3. 마지막 엔드 카드는 생성 이미지를 다시 만들지 않고 Final Cut Pro에서 정지/유지, 타이포그래피, 페이드로 구성했다.
4. 크레딧 부족 시에도 정지 이미지에 컷 편집과 짧은 패닝·줌을 적용해 메시지와 10초 리듬을 유지했다.

대체 도구는 비디오 생성에 Kling 또는 Pika, 음악/효과음에 Suno 또는 다른 TTS·사운드 도구를 준비할 수 있다.

## 9. 최종 체크리스트

- [x] 가상 브랜드·타깃·USP·핵심 메시지 정의
- [x] 문제 → 전환 → 해결 → 브랜드 인지 구조
- [x] 이미지 생성 AI, 비디오 생성/변환 AI, 오디오 생성 AI 사용
- [x] 마지막 구간에 브랜드명과 슬로건 배치
- [x] Final Cut Pro는 통합 편집 용도로만 사용
- [x] 프롬프트 수정 전/후와 수정 이유 기록
- [x] 크레딧 부족 시 제작 범위 조정 전략 기록
- [x] 최종 영상 약 10초
- [x] 직접 촬영본·유료 스톡을 사용하지 않고, 시각·청각 원본을 생성형 AI 결과물로 구성

## 9-1. 심층 인터뷰 예상 답변

### Q1. 서로 다른 도구의 결과를 통합하며 생긴 불일치는 어떻게 보정했나?

해상도와 비율은 Final Cut Pro의 16:9 / 1080p HD / 30fps 프로젝트에 맞췄다. 색감은 모든 프롬프트에 딥 네이비와 청록 포인트를 반복하고, 마지막 장면만 밝은 자연광으로 의도적으로 전환했다. 인물의 얼굴을 보여 주지 않고 검은 롱코트·검은 캐리어·뒷모습을 공통 규칙으로 두었으며, 스캐너의 모양 차이는 휴대폰 인식음과 LED 점등 순간에 클로즈업으로 컷 전환해 덜 보이게 했다.

### Q2. 같은 스토리보드를 다른 도구로 만들면 무엇이 달라지는가?

학습 네이토 `gpt-image-2`는 장면 구도와 혼잡도를 빠르게 탐색하기 좋았지만 반복 인물·제품 디자인을 고정하는 기능은 약했다. Firefly와 ElevenLabs Image & Video는 참조 이미지를 첨부해 기존 결과를 이어 갈 수 있어 일관성 제어에 유리했다. 반면 파트너 영상 모델은 크레딧 제약이 커서 비용과 생성 가능 여부가 가장 큰 차이였다.

### Q3. 영상 생성 크레딧이 더 부족했다면 어떻게 바꾸겠는가?

씬 1의 혼잡 이미지와 씬 3의 탑승 게이트 이미지를 정지 화면으로 사용하고, Final Cut Pro에서 느린 패닝·줌과 컷·효과음만 적용한다. 꼭 필요한 장면인 ‘휴대폰 인식’만 짧은 이미지-투-비디오로 남긴다. 즉, 영상 생성 씬 수를 3개에서 1개로 줄이되 문제→전환→해결의 메시지는 유지한다.

### Q4. 60초 버전을 15초로 줄여야 한다면 어떤 씬을 유지하겠는가?

대기열의 문제 제시, 휴대폰 인식의 전환, 밝은 탑승 게이트와 엔드 카드의 해결 장면만 유지한다. 공항을 걷는 중간 연결 장면이나 여러 각도의 스캐너 샷은 삭제한다. 15초 안에서도 ‘혼잡 5초 → 인식 4초 → 출발·브랜드 6초’로 메시지를 압축할 수 있다.

## 10. 제출 파일

| 구분 | 파일명 | 비고 |
| --- | --- | --- |
| 최종 광고 영상 | `AreoPass_BrandADAug11_2.mp4` | Final Cut Pro로 편집한 약 10초 MP4 |
| 스토리보드·제작 기록 | `AeroPass_Storyboard.md` | 본 문서 |
| BGM | `Seamless_Journey_2026-08-10T072007.mp3` | ElevenLabs Music 생성 결과 |
