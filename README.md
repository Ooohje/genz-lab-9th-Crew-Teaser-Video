# Gen Z Lab 9th Crew Teaser Video

젠지랩(Gen Z Lab) 9기 크루 모집·젠지랩 소개 영상을 만든 과정과 규칙을 정리한 문서입니다.
영상은 공식 행사에서 상영하며, 이미지·영상·목소리·효과음은 Higgsfield의 AI 모델로 만들고 편집은 Python + ffmpeg 스크립트로 합칩니다.

- **화면**: 1920×1080(16:9) 안에 21:9 그림, 위아래 검은 여백, 자막은 아래 여백 안
- **길이**: 약 71초
- **주인공**: 글리밍(Gleaming) 한 명, 모든 대사를 글리밍이 말함
- **모집 기간과 '9기 크루 모집' 문구는 넣지 않음**(소개 영상으로도 다시 쓰기 위해)

---

## 1. 캐릭터 지침: 글리밍

기준 이미지는 캐릭터 프로필 시트 한 장입니다. 모든 이미지와 영상의 글리밍은 이 프로필과 **완전히 같아야** 합니다.

| 항목 | 규칙 |
|---|---|
| 몸 | 콩 모양의 반투명 젤리 몸, 분홍·보라·청록·파랑 은하수 무늬와 작은 별빛, 배 쪽에 작은 방울 하나 |
| 머리 | 끝이 둥글게 빛나는 짧은 더듬이 두 개 |
| 얼굴 | 흰 하이라이트가 있는 크고 둥근 검은 눈 두 개, 분홍 볼, 밝게 웃는 입 |
| 팔·다리 | 짧고 둥근 팔 끝(**손가락 없음**), 짧은 다리 |
| 크기 | 화면 높이의 약 45%, 전신, 바닥에 섬 |
| 수 | 화면에 **항상 한 명**. 순간이동 금지(컷 사이에 위치가 이어져야 함) |
| 색 | 프로필 기준 채도 약 0.61, 밝기 약 0.76. AI 결과가 더 진하고 밝게 나오면 글리밍 부분만 보정 |

**표정 규칙**
- 표정은 **입과 볼로만** 바꿉니다. 눈은 프로필과 같은 크기·모양·하이라이트·간격으로 고정합니다.
- 눈을 크게 뜨기, 감기, 윙크, 곁눈질은 쓰지 않습니다(캐릭터가 달라 보이거나 얄미워 보임).
- 쓰는 표정 예: 활짝 웃음, "오!" 하고 놀란 입, 눈 뜬 채 크게 웃음, 입 다문 차분한 미소.

**열쇠 규칙**
- 소품은 황금 열쇠 하나: 둥근 고리 머리, 곧은 막대, 한쪽에 네모난 이빨 두 개.
- 열쇠 길이는 글리밍 키(더듬이 포함)의 **약 5분의 4**. 모양·크기가 컷마다 바뀌면 안 됩니다.
- 글리밍은 열쇠를 **항상 들고 있습니다**. 열쇠를 꽂을 때는 **이빨 쪽이 열쇠구멍으로** 들어가고 고리를 잡습니다.
- 금색은 열쇠에만 씁니다. 반짝임·렌즈 플레어는 넣지 않습니다.

**그림 톤**
- 광택 있는 3D 애니메이션, 삼성 광고처럼 깨끗한 흰 스튜디오 배경(인트로만 어두운 금빛 포스터 배경).
- 사람은 모두 귀여운 3D 캐릭터로 그리고, 실제 사진 속 인물을 닮게 그리지 않습니다.
- 글자는 짧은 영어로 넣고, 철자는 생성 뒤에 반드시 확인합니다.

**대사 톤**: 공식 행사용이라 권유형·정중한 표현. 명령형·도발적 표현은 쓰지 않습니다.

---

## 2. 영상 구성

| 장면 | 내용 | 대사(글리밍) | 한국어 자막 |
|---|---|---|---|
| 인트로 | 어두운 포스터 열쇠구멍으로 멀리서 줌인 → 빛 → 흰 스튜디오에서 열쇠를 든 글리밍 | Something new awaits. Unlock it with the ninth key. | 새로운 가능성, 9번째 열쇠로 열어보세요. |
| Workshop | 문(BOUNDARIES) 앞 대사 → 열쇠 돌리기 → 문이 열리며 빛 속으로 → 워크샵 | One: Connect! Shall we open the boundaries together? / Meet 120 crew at workshops and share ideas freely. | 첫 번째, 함께 연결되기. 경계를 함께 열어볼까요? / 워크샵에서 120여 명의 크루와 만나고, 아이디어를 자유롭게 나눠보세요. |
| TrenderZ | 문(HESITATION) → 같은 흐름 → 트렌드 매거진 모임 | Two: Discover trends! No need to hesitate. / Freely shared trends come together in our magazine. | 두 번째, 트렌드 발굴하기. 망설이지 않아도 괜찮아요. / 자유롭게 나눈 트렌드가 모여 매거진이 돼요. |
| Campus Connect | 문(DISTANCE) → 같은 흐름 → 대학생 아이디어톤 발표 | Three: Sync with the world! Shall we close the distance? / Listen to Next Gen voices, too. | 세 번째, 세상과 통하기. 그 거리를 좁혀볼까요? / Next 세대의 목소리도 함께 들어보세요. |
| Meeting with Executives | 문(LIMITS) → 같은 흐름 → 경영진 앞 제안 | Four: Share your thoughts! Let's go beyond the limits. / Propose ideas directly to executives. | 네 번째, 생각을 전하기. 한계 너머로 함께 가봐요. / 경영진에게 직접 제안해보세요. |
| 7대 프로그램 | R5 건물 앞에 프로그램 카드 7장 | Bring imagined ideas to life at Gen Z Lab. | 상상 속 아이디어를, 젠지랩에서 펼쳐보세요. |
| 자격 조건 | AGE? DEPT? LOCATION? 블록을 열쇠로 톡 → 무너짐 → 환호 | Whatever your age, department, or location, passion is enough. / Let's go together with Gen Z Lab! | 나이, 부서, 사업장 상관없이, 열정이면 충분합니다. / 젠지랩과 함께 가요! |
| 아웃트로 | 열쇠구멍 속 글리밍 | The ninth master key is waiting for you. | 아홉 번째 마스터키가 여러분을 기다립니다 |
| 로고 | 검은 화면에 Gen Z Lab. 로고 | Gen Z Lab! | (자막 없음) |

문 장면 네 곳은 모두 같은 흐름입니다.
1. **문 앞 대사**: 고정 카메라, 글리밍이 열쇠를 세워 들고 카메라를 보며 말함(입 모양을 대사에 맞춤).
2. **열쇠 돌리기 클로즈업**: 옆모습, 문마다 표정만 다름(입·볼만).
3. **1인칭 빛 속으로**: 돌문 가운데 선에서 빛이 새고 문이 양쪽으로 열리며 빛 속으로.
4. **활동 장면**: 설명 대사는 입을 다문 보이스오버.

장면 사이는 바로 컷(화면 크기가 달라서 자연스러움), 빛 → 활동만 0.25초 디졸브입니다.

---

## 3. 제작 과정

### 3-1. 기준 이미지
- 캐릭터 프로필 시트(글리밍 + 열쇠)를 기준으로 삼고, 글자를 지운 사본을 모든 이미지 생성의 첫 번째 참고 이미지로 넣습니다.

### 3-2. 컷 이미지 (시작 프레임)
- 모델: **GPT Image 2.6**, 21:9, 2k(2688×1152), quality medium.
- 참고 이미지: 프로필 사본(항상 1번) + 필요한 장면 참고(앞에서 만든 문 이미지 등).
- 프롬프트는 약 200토큰으로 짧게, 바뀌는 것만, 금지문 대신 긍정문으로 씁니다.
- 고칠 때는 새로 그리지 않고 **앞 결과를 참고로 넣고 "The same picture as image 1, with one change: …"** 로 결함만 고칩니다. 구도·글리밍이 유지됩니다.
- 생성 뒤 검증:
  - 글리밍 색: 글리밍 몸만 골라(GrabCut) 채도·밝기·색 분포를 프로필과 비교하고 글리밍 부분만 보정합니다.
  - 얼굴: 눈 크기·간격·높이, 입, 몸 색을 프로필·기존 컷과 **확대해 나란히** 비교합니다(색 수치만으로는 얼굴 차이를 못 잡음).
  - 글자 철자, 열쇠 길이(글리밍 키의 약 0.8), 손가락 유무.
- AI 편집으로 안 고쳐지는 작은 부분(이빨 하나, 글자 하나)은 로컬 편집(Python, PIL·OpenCV)으로 고칩니다.

### 3-3. 영상
- 모델: **Seedance 2.0 Mini**, 720p, 21:9, 소리 없음(`generate_audio: false`), 4~7초.
- 입력: **시작 이미지 한 장만**(필요하면 끝 이미지). 프로필을 함께 넣으면 첫 프레임부터 그림을 다시 그려 버립니다.
- 프롬프트 형식(맨 앞 잠금 문장 3줄 + 카메라 + 동작):
  ```
  Gleaming is exactly the cartoon character in the start frame: glossy galaxy-jelly body, two orb-tipped antennae, big black eyes, pink cheeks, smooth fingerless stub arms; the same face, proportions and colors in every frame.
  The golden key is exactly the key in the start frame: round ring head, straight shaft, two square teeth on one side; it stays in the same arm, with the same shape and size in every frame.
  Family-friendly glossy 3D cartoon animation, bright clean white studio light; one Gleaming, one key.
  Camera: Wide shot, eye level, locked-off static camera, the whole frame stays exactly as composed, deep focus.
  Action: The first frame is exactly the start frame. …
  ```
- 문 앞 대사 컷은 대사 mp3를 함께 넣어(`audio_references`) 입 모양을 맞춥니다.
- 생성 뒤 검증: 첫 프레임과 시작 이미지의 차이, 프레임 사이 튐, 열쇠 길이·모양, 글리밍 색·얼굴, 글자, 그리고 **컷 사이에 글리밍이 어디서 어디로 갔는지**(이야기 흐름).
- AI 영상은 2.6~3초쯤부터 열쇠가 빠지거나 모양이 변하는 일이 많아서, 그 전에 잘라 씁니다.

### 3-4. 목소리
- 모델: **Seed Audio**, 목소리 Bram, `pitch_rate 3`(귀여운 남자 애니메이션 톤), mp3, 한 줄씩 생성.
- 편집에서 모든 대사를 **1.1배속**으로 맞추고, 대사가 끝나면 바로 다음 컷으로 넘어가게 컷 길이를 대사 길이에 맞춥니다.
- 녹음 앞뒤의 짧은 숨소리(0.2초 미만, 0.8초 넘게 떨어진 소리)는 길이 계산에서 뺍니다. 안 빼면 말이 끝났는데 입만 움직이는 구간이 생깁니다.

### 3-5. 효과음
- 모델: Mirelo(텍스트 → 효과음). 열쇠 돌리는 딸깍·철컥, 돌문 열림, 장벽 무너짐.
- 웃음소리는 얄미워 보일 수 있어 쓰지 않고 짧은 대사로 대신했습니다.

### 3-6. 편집 (`작업스크립트/build_full.py`)
- ffmpeg로 컷을 잘라 이어 붙이고, 21:9 그림을 1920×1080에 넣어 위아래 검은 여백을 만듭니다.
- 자막: ASS, **Pretendard SemiBold** 44px 흰색, 아래 검은 여백 안 가운데(넷플릭스 자막 느낌, 두꺼운 테두리 없음).
- 배경음악: numpy로 직접 합성한 118BPM 업비트 전자음. 대사가 없을 때는 크게, 대사·효과음이 나올 때는 자동으로 작아집니다(덕킹).
- 로고: 원본 PNG를 검은 화면에 그대로 얹고 "Gen Z Lab!" 목소리만.
- 실행: `python -X utf8 작업스크립트/build_full.py`(필요 패키지: numpy, soundfile, imageio-ffmpeg, opencv-python-headless)

---

## 4. 해 보고 알게 된 것

- **열쇠는 AI 영상에서 움직이지 않게 합니다.** 가만히 들고 있으면 모양이 유지되지만, 뽑거나 휘두르면 모양·크기가 바뀝니다.
- **1인칭으로 두 팔이 열쇠를 쥔 구도**는 영상 생성 필터에 계속 막혔습니다. 옆모습 클로즈업 + 열쇠 없는 1인칭 문 열기로 나눴습니다.
- 인물을 도는 카메라(아크)는 인물이 대신 돌아 버립니다. 화면을 기울이는 더치 앵글은 글자가 기울어 보여 쓰지 않습니다.
- 서로 다른 각도의 열쇠가 겹치는 디졸브는 깨져 보입니다. 화면 크기가 다른 컷끼리는 바로 끊는 편이 자연스럽습니다.
- 컷을 고치기 전에 **이야기 흐름**(글리밍이 걸어가 → 열고 → 들어가 → 안에서 활동)부터 맞는지 봅니다.
- 영상 모델은 표지판 글자를 바꾸기도 합니다(예: DEPT? → DEPT!). 이럴 때는 시작 이미지의 글자를 영상 위에 덮어 고칩니다(크레딧 0).
- 크레딧은 생성 전에 비용을 먼저 확인하고, 한 컷으로 시험한 뒤 나머지를 진행합니다.
