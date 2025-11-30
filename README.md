## 1. 리눅스(Linux) 필수 명령어 🐧

서버 관리나 개발을 할 때 가장 자주 쓰이는 프로세스 관련 명령어 4가지입니다.

| 명령어 | 기능 | 언제 사용하나요? |
| :---: | :---: | :--- |
| **top** | 실시간 점유율 보기 | 컴퓨터가 갑자기 느려져서 원인을 찾을 때 |
| **ps** | 실행 중인 목록 스냅샷 | 특정 프로그램이 켜져 있는지 확인할 때 |
| **jobs** | 백그라운드 작업 확인 | 뒤에서 몰래 돌고 있는 작업을 찾을 때 |
| **kill** | 강제 종료 | 프로그램이 먹통이라 강제로 꺼야 할 때 |

### (link) 참고하면 좋은 사이트
더 자세한 내용이나 옵션이 궁금하다면 아래 사이트를 추천합니다.
1. [**Inpa Dev**](https://inpa.tistory.com/category/OS/Linux?page=3) - 그림으로 쉽게 원리를 설명해주는 블로그
2. [**ExplainShell**](https://explainshell.com) - 복잡한 명령어를 해석해주는 사이트

---

## 2. 마크다운(Markdown) - 불렛(Bullet) 기능(function)

### 불렛이란?
순서가 없는 목록(리스트)을 만들 때 사용하는 기호입니다.

### 사용 가능한 기호
아래 3가지 중 아무거나 써도 결과는 똑같습니다!
- `*` (별표)
- `+` (더하기)
- `-` (빼기)

### 💡 차이점이 있나요?
**전혀 없습니다!** 결과물은 모두 똑같은 점(•)으로 나옵니다.
3가지나 있는 이유는 예전부터 사람들이 쓰던 습관이 다양해서 모두 지원하는 것뿐입니다. (보통 `-`를 가장 많이 씁니다.)

### 목록 안에 목록 넣기 (들여쓰기)
큰 항목 아래에 하위 설명을 넣으려면 **스페이스바 2번** (또는 탭 1번)을 누르고 작성하세요.

#### [예시]
* **과일**
  * 사과🍎, 배🍐, 수박🍉
* **프로그래밍 언어**
  * 파이썬, 자바, C언어

---

## ⚠️ 텍스트 강조 시 주의사항 ⚠️

굵은 글씨(`**`)나 기울임꼴(`*`)을 쓸 때는 **"샌드위치"**처럼 양쪽을 꼭 닫아줘야 합니다.

- ❌ 잘못된 예: `**닫는 걸 깜빡하면 안 돼요`
- ✅ 올바른 예: `**꼭 양쪽을 닫아주세요**`

---

## 3. 이미지(image) -> **README** 파일에 업로드 🌉

#### 사과(apple)
![사과(apple)](https://pixabay.com/photos/apples-red-pair-fruits-red-apples-1506119/)

출처: *[사과(apple)](https://pixabay.com/photos/apples-red-pair-fruits-red-apples-1506119/ "출처 : Pixaba")*

#### 에펠탑
![에펠탑](https://pixabay.com/photos/eiffel-tower-paris-the-city-france-2000717/)

출처: *[에펠탑](https://pixabay.com/photos/eiffel-tower-paris-the-city-france-2000717/ "출처 : Pixabay")*

## ⚠️ 이미지 삽입시 주의사항 ⚠️

**위와 같이 사진이 있는 사이트를 그냥 복사해서 올 경우 접근 금지, 즉 외부 링크 차단을 함!!**

#### How (방법은?)
- 이미지를 **README**가 있는 파일에 저장하고 그걸 불러와야 함!!⭐️

## 제대로 된 이미지(image) 업로드
#### 사과(apple)
![사과(apple)](apples-1506119_1280.jpg)

출처: *[사과(apple)](https://pixabay.com/photos/apples-red-pair-fruits-red-apples-1506119/ "출처 : Pixaba")*

#### 에펠탑
![에펠탑](eiffel-tower-2000717_1280.jpg)

출처: *[에펠탑](https://pixabay.com/photos/eiffel-tower-paris-the-city-france-2000717/ "출처 : Pixabay")*

---

## **[문제(question)]**

<details>
<summary>Q1. 이미지 삽입 시 주의 사항은 무엇인가요?</summary>
<br>

**A. README 파일이 있는 곳(같은 폴더)에 사진을 저장 후 불러와야 합니다.**
(외부 링크를 그냥 쓰면 403 에러로 사진이 안 보일 수 있습니다.)

</details>

<details>
<summary>Q2. 불렛(목록)을 만드는 기호 3가지는?</summary>
<br>

**A. `*` (별표), `-` (빼기), `+` (더하기)**
이 중 아무거나 사용해도 됩니다.

</details>

<details>
<summary>Q3. 불렛 기호 3가지의 결과 모양은 서로 다르다? (O/X)</summary>
<br>

**A. 정답은 [ X ] 입니다.**
작성할 때 기호만 다를 뿐, 결과물은 모두 **똑같은 점(•)**으로 나옵니다.

</details>

<details>
<summary>Q4. 텍스트 강조(굵게, 기울임) 시 주의 사항은?</summary>
<br>

**A. 양쪽을 꼭 닫아줘야 합니다.**
샌드위치처럼 글자 앞뒤를 기호로 감싸야 제대로 작동합니다. (예: `**강조**`)

</details>