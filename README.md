# G2 Mini-project: Vocabulary Learning App (ver. 1.0; asof 10/22, 2026)

## 👥 Group Information

| Item | Details |
|---|---|
| Group | G2 |
| Members | 이유찬 (Leader), 강유진, 김유진, 최준위 |
| README editor | 최준위 |
| Date & Time | 10/22, 13:00 – 14:55 |
| Location | 1층 미래교육센터 / Room 116 |

---

## 💙 1. What We Learned from the Two Articles

### 1-1. Webb (2007): Vocabulary Learning

- Main point: 단어를 많이 접할수록 어휘 지식이 늘어남. 단어를 안다는 건 뜻뿐 아니라 철자, 품사, 문장 속 쓰임, 함께 자주 쓰이는 표현까지 아는 것이고, 뜻을 스스로 떠올리거나 문장에서 쓰는 능력은 가장 늦게 발달함(10회 노출 후에도 뜻 회상률 약 29%).
- What teachers can learn: 같은 단어를 다양한 문맥에서 반복해서 만나게 해야 하고, 객관식 정답률만으로 습득을 판단하면 안 됨. 뜻 고르기와 직접 떠올리기, 문장 쓰기 활동을 함께 써야 함.

### 1-2. Nakata et al. (2021)

- Main point: 이전에 배운 단어까지 출제한 누적 평가 집단은 주간 점수는 낮았지만 3주 뒤 진행한 최종 평가에서 훨씬 높았음. 당장의 높은 점수가 장기 기억을 보장하지 않으며, 적절한 어려움이 기억을 강화함.
- What teachers can learn: 시험은 평가 도구이면서 학습을 촉진하는 도구가 될 수 있음. 새 단어와 이전 단어를 섞어 출제하되, 목적을 미리 설명해서 낮은 점수로 동기가 떨어지지 않게 배려해야 함.

### 1-3. Our Takeaway for the App

- 각 단어를 여러 활동과 문맥에서 반복해서 만나게 함.
- 다시 보여 주기만 하지 않고 직접 떠올리는 인출 활동을 넣음.
- 새 단어 학습 중에도 이전에 배운 단어와 틀린 단어를 섞어서 다시 출제함.

---

## 💙 2. Our Selected Words from the Basic Vocabulary List

### 2-1. About the List

- 2022 개정 교육과정 [별표 3]에 실린 기본 어휘 3,000개를 알파벳순으로 정리한 목록임.
- 학교급을 별표로 표시함. `*` 표시 800개는 초등학교, `**` 표시 1,200개는 중학교와 고등학교 공통과목, 표시 없는 단어는 고등학교 선택과목에서 사용하도록 권장함.
- 괄호 안에 word family를 함께 제시함. (e.g., health (healthy), apply (applicant))
- 미국식과 영국식처럼 철자가 다른 variation은 슬래시로 함께 제시함. (e.g., neighbor / neighbour)

### 2-2. Selected Words (10–20)

`relax`, `prepare`, `exercise`, `communicate`, `borrow`, `health`, `neighbor`, `recipe`, `schedule`, `hunger`, `recommend`, `manage`, `believe`, `catch`, `add`, `adopt`, `apply`, `decide`, `suggest`, `improve`

### 2-3. Why We Chose These Words

- 난이도: 중학교 2학년 학습자 수준에 맞춰 중·고등학교 공통 권장(`**`) 단어를 중심으로 고르고, 초등 권장(`*`) 단어 일부를 복습용으로 섞음.
- 산출 활동: 모두 일상 상황에서 자주 쓰이는 단어라 학습자가 자기 생활에 빗대어 문장을 직접 만들어 보기 좋음.
- 주제 중심 학습: 단어들을 '일상생활'이라는 하나의 주제로 묶어서 서로 연결된 맥락 속에서 반복해 학습할 수 있음.

---

## 💙 3. App Design Draft

### 3-1. Design Concept

- 반투명한 유리 질감의 메뉴와 버튼을 사용해 깔끔하고 세련된 화면을 만듦.
- 메뉴는 화면 하단 바에 배치해 엄지로 쉽게 누를 수 있게 하고, 메뉴를 누르거나 화면을 좌우로 밀어서 학습 활동을 바꿀 수 있게 함.
- 단어와 예문은 선명한 바탕에 크게 보여 줘서 휴대폰에서도 읽기 쉽게 함.

### 3-2. Learners

- Korean 2nd-year middle school students (K8)

### 3-3. Goal

- 단어의 형태만 외우는 데서 그치지 않고 단어 자체를 이해해서, 일상생활에서 직접 말하고 쓸 수 있게 하는 것이 목표임.
- 이를 위해 뜻뿐 아니라 철자, 품사, 문장 속 쓰임, 함께 자주 쓰이는 표현, 의미가 연관된 단어까지 함께 익히도록 함.

### 3-4. Learning Activities

- 플래시카드: 20개 단어를 5개씩 4세트로 나누어, 각 단어의 철자, 뜻, 발음, 예문을 학습하고 단어군과 변이형을 함께 익힘. 모르는 단어는 '모르겠어요'로 표시해 복습 탭에 모음.
- 빈칸 채우기 퀴즈: 문장과 해석을 보고 빈칸에 알맞은 단어를 떠올려 직접 입력하며, 문맥에 맞게 형태를 바꿔 쓰는 법을 익힘. 정답과 오답을 바로 확인하고 오답에는 간단한 해설을 받음.
- 복습 탭: 퀴즈에서 틀리거나 '모르겠어요'로 표시한 단어가 자동으로 모이고, 이 단어들만 다시 퀴즈로 풀 수 있음.

- Encounters (Webb 2007): 학습자는 플래시카드, 빈칸 채우기 퀴즈, 복습 탭에서 각 단어를 서로 다른 문장과 활동으로 여러 번 만나게 됨.
- Retrieval (Nakata et al. 2021): 빈칸 채우기 퀴즈에서 단어를 기억에서 직접 떠올리게 하고, 틀린 단어는 복습 탭에서 반복해서 다시 인출하게 함.

### 3-5. Use of the List Information

| Information | How our app uses it |
|---|---|
| Level (`*`, `**`) | 단어 목록의 수준 표시를 바탕으로 앱 안에서 난이도를 별 1~3개로 다시 나눠 표시함. 별 1개는 초등 권장(`*`) 단어, 별 2개는 중·고 공통(`**`) 단어, 별 3개는 표시 없는 고등 선택과목 단어로 가장 어려운 단계임. |
| Word family (e.g., *species* ~ *specify*) | 플래시카드에 단어군을 함께 보여 주고(e.g., health → healthy, decide → decision), 빈칸 채우기 퀴즈에서 문맥에 맞는 형태를 직접 입력하게 해 품사와 쓰임을 함께 익히게 함. |
| Variation (e.g., *rumor* / *rumour*) | 플래시카드에 미국식과 영국식 철자를 함께 보여 주고, 빈칸 채우기 퀴즈에서는 두 철자를 모두 정답으로 인정함. (e.g., neighbor / neighbour) |

### 3-6. Context Elements (LPGCTXF, Week 03)

| Element | Our decision |
|---|---|
| L (Learner) | 한국 중학교 2학년 학생(K8)을 대상으로 함. |
| P (Proficiency) | A2~B1 수준. 기본적인 문장은 읽고 이해할 수 있지만, 배운 단어를 직접 문장에 활용하는 데는 어려움이 있는 학습자임. |
| G (Goal) | 단어의 뜻과 철자를 정확히 알고, 일상 문장에서 실제로 사용할 수 있게 하는 것이 목표임. |
| C (Content) | '일상생활' 주제의 기본 어휘 20개(relax, prepare, borrow, schedule, recommend, decide 등)와 각 단어의 예문, 단어군, 변이형 정보를 학습함. |
| T (Time & Task) | 하루 10분씩 일주일 동안 학습함. 세트별 플래시카드와 빈칸 채우기 퀴즈를 하고, 복습 탭에서 틀린 단어를 다시 연습함. |
| X (Constraints) | 별도 설치나 회원가입 없이 웹 브라우저에서 바로 사용할 수 있게 함. 학습자마다 수준이 다르므로 짧고 쉬운 예문을 사용함. |
| F (Feedback) | 정답과 오답을 즉시 알려 주고, 오답에는 간단한 해설을 제공함. 틀린 단어는 복습 탭에 자동으로 모아 다시 학습하게 함. |

---

## 💙 4. App Features

1. Flashcards (word → meaning, spelling): This feature helps learners learn the spelling and meaning of each word, along with its word family and spelling variations, because seeing these forms together builds a fuller understanding of the word than memorizing its meaning alone.
2. Fill-in-the-blank quiz: This feature helps learners understand how each word is used and changes form in real sentences because they must recall the word and choose the right form for the context, not just recognize it.
3. Review tab (wrong-word collection): This feature helps learners focus on the words they have not yet mastered because every answer gets instant feedback with a short explanation, and all missed words are gathered in one place for repeated review, so learners can see what they don't know and practice it again.

---

## 💙 5. Sample Word Data

| Word | Word-family | Variation | Level | Meaning (Korean) | Example sentence |
|---|---|---|---|---|---|
| relax | NA | NA | Middle/High (**) | 휴식을 취하다, 긴장을 풀다 | I relax by listening to music after school. |
| prepare | NA | NA | Middle/High (**) | 준비하다 | My mom is preparing dinner in the kitchen. |
| exercise | NA | NA | Elementary (*) | 운동하다, 운동 | I exercise in the park every morning. |
| communicate | communication | NA | Middle/High (**) | 의사소통하다 | We communicate with our friends by text message. |
| borrow | NA | NA | Elementary (*) | 빌리다 | Can I borrow your pen? |
| health | healthy | NA | Middle/High (**) | 건강 | Sleep is important for your health. |
| neighbor | NA | neighbour | Middle/High (**) | 이웃 | My neighbor has a cute dog. |
| recipe | NA | NA | Middle/High (**) | 조리법 | This recipe is easy to follow. |
| schedule | NA | NA | Middle/High (**) | 일정 | I check my schedule every night. |
| hunger | hungry | NA | Middle/High (**) | 배고픔 | The baby cried from hunger. |
| recommend | NA | NA | Middle/High (**) | 추천하다 | Can you recommend a good book? |
| manage | NA | NA | Middle/High (**) | 관리하다, 해내다 | I manage my time well during exams. |
| believe | NA | NA | Elementary (*) | 믿다 | I believe you can do it. |
| catch | NA | NA | Elementary (*) | 잡다 | I ran to catch the bus. |
| add | NA | NA | Elementary (*) | 더하다, 추가하다 | Add some salt to the soup. |
| adopt | NA | NA | Middle/High (**) | 입양하다, 채택하다 | We adopted a puppy from the animal shelter. |
| apply | applicant | NA | Middle/High (**) | 지원하다, 적용하다 | I applied for the school's English camp. |
| decide | decision | NA | Elementary (*) | 결정하다 | I decided to join the soccer club. |
| suggest | NA | NA | Middle/High (**) | 제안하다 | My friend suggested watching a movie. |
| improve | NA | NA | Middle/High (**) | 향상시키다 | I want to improve my English. |

---

## 💙 6. Test and Improve

### 6-1. Checklist

- [x] All features work (every button was clicked).
- [x] All words, meanings, and sentences are correct.
- [x] The app gives clear feedback for right and wrong answers.
- [x] Learners **retrieve** words and meet each word **more than once**.
- [x] The app is easy to use on a phone.

### 6-2. Problems Found and How We Fixed Them

| Problem | Fix |
|---|---|
| 빈칸 퀴즈에서 정답 단어의 뜻이 힌트로 나와, 문장을 이해하지 않고도 답을 맞힐 수 있음 | 단어 뜻 대신 문장 전체의 한국어 해석을 보여 주도록 바꿈 (v2) |
| 하루 10분 타이머와 일주일 카운터가 학습에 꼭 필요하지 않고 화면만 복잡하게 만듦 | 타이머와 카운터를 삭제함 (v2) |
| 플래시카드의 조명 효과가 단어에 집중하는 데 방해가 됨 | 카드에서는 조명 효과를 빼고 메뉴와 버튼에만 남김 (v2) |
| 발음이 미국식으로 고정되어 있지 않음 | 미국 영어 음성으로 읽도록 지정함 (v2) |
| 퀴즈 해설에서 문장 전체를 들을 수 없음 | 해설 창에 정답이 들어간 문장 전체 듣기 버튼을 추가함 (v2) |
| '다시 볼래요'라는 표현이 학습자가 단어를 모른다는 상태를 분명히 나타내지 못함 | 버튼 문구를 '모르겠어요'로 바꿈 (v2) |
| 단어 가족과 변이형 정보가 카드 뒷면에만 있어 놓치기 쉬움 | 해당 정보가 있는 단어는 카드 앞면에도 표시함 (v2) |
| 밝은 그라데이션 색감이 산만함 | 회색, 검은색, 흰색 위주의 미니멀한 색감으로 바꿈 (v2) |
| 상단의 앱 제목과 소개 문구가 불필요하게 공간을 차지함 | 상단 제목과 소개 문구를 삭제함 (v2) |
| 카드 넘기기 버튼이 화면을 차지하고 모바일에서 조작이 번거로움 | 버튼을 없애고 카드를 좌우로 밀어서 넘기게 바꿈. 양옆 화살표와 점 표시로 넘길 수 있음을 알려 줌 (v2) |
| 빈칸 퀴즈 탭에 들어가자마자 문제가 바로 시작됨 | 시작 버튼을 누르면 20문제가 매번 다른 순서로 나오고, 다 풀면 결과 화면이 뜨도록 바꿈 (v2) |
| 20개 단어를 한 번에 학습해야 해서 부담이 큼 | 5개씩 4세트로 나누어 세트별로 학습하고, 세트마다 결과를 확인하도록 바꿈 (v2) |
| 일부 기기에서 발음이 이상하게 나옴. 기기에 기본 음성이 없으면 장난용 효과 음성이 자동으로 선택되는 문제였음 | 효과 음성을 자동 선택에서 제외하고 자연스러운 음성을 우선 고르게 함. 복습 탭에 음성 선택 메뉴를 추가함 (v3) |
| 기기에 따라 첫 재생 때 한국어 음성이 영어를 읽음 | 음성 목록을 다 불러온 뒤에 재생하도록 바꿈 (v3) |
| 기기마다 설치된 음성이 달라 발음 품질이 일정하지 않음 | 오픈소스 음성 합성 모델(Kokoro)로 단어 20개와 퀴즈 문장 20개의 미국식 음성을 만들어 html 안에 넣음. 기기 자체 음성은 재생 실패 시 예비용으로만 사용함 (v4) |

### 6-3. Saved Versions

- `index_v1.html`: 첫 버전. 플래시카드, 빈칸 채우기 퀴즈, 복습 탭, 하단 메뉴 바와 스와이프 메뉴 이동
- `index_v2.html`: 5개씩 4세트 학습, 카드 스와이프, 퀴즈 시작 화면과 20문제 무작위 출제, 다크 모드 색감, 문장 해석과 문장 듣기
- `index_v3.html`: 발음 음성 자동 선택 오류 수정, 음성 선택 메뉴 추가
- `index_v4.html`: 단어와 퀴즈 문장의 미국식 음성 40개를 앱 안에 내장
- `G2_project_draft.html`: final version

---

## 💙 7. Next Steps

- 단일 html 파일의 한계를 넘어 실제 앱 형태로 발전시키고 싶음.
  - 지금은 학습 기록이 기기 한 대의 브라우저에만 저장되므로, 계정과 서버를 연결해 다른 기기에서도 기록을 이어 가고 교사가 학생들의 학습 현황을 확인할 수 있게 하고 싶음.
  - 3,000단어 전체를 연결하면 음성 파일까지 한 파일에 담기 어려우므로, 단어 데이터와 음성을 따로 관리하는 구조로 바꾸고 싶음.
- 학습 효과를 높이는 기능을 더 넣고 싶음.
  - 틀린 단어를 하루, 사흘, 일주일 간격으로 다시 출제하는 간격 반복 복습
  - 배운 단어로 자기 생활에 관한 문장을 직접 써 보는 산출 활동
  - 단어를 소리 내어 읽고 녹음해 원어민 발음과 비교하는 말하기 연습