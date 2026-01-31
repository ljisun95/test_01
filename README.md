# 🐍 Snake Game (HTML / CSS / JavaScript)

A simple web-based Snake Game built using pure HTML, CSS, and JavaScript.  
Everything is contained in a **single HTML file**, making it easy to run and share.

---

## 🎮 Features

- Control the snake using the arrow keys (↑ ↓ ← →).
- When the snake moves beyond the screen boundary, it **warps to the opposite side** instead of triggering a game over.
- Eating food increases your score and lengthens the snake.
- Start or restart the game using the **Spacebar** or the on-screen button.
- Built entirely with **HTML5 Canvas** and vanilla JavaScript—no external libraries required.

---

## 📂 Project Structure

This project consists of a single file:

```
index.html
```

All CSS and JavaScript code is embedded directly inside the HTML file.

---

## 🚀 How to Run

1. Clone this repository or download it as a ZIP file:

```
git clone https://github.com/your-username/your-repository.git
```

2. Open `index.html` in any modern web browser.

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |
| Space | Start / Restart Game |

---

## 📸 Screenshot

(You can add your own screenshot here!)

```
![snake-game](./screenshot.png)
```

---

## 🧩 Key Code Snippet

### Screen Wrapping Logic

The snake reappears on the opposite side when crossing the boundary:

```js
head.x = (head.x + tileCount) % tileCount;
head.y = (head.y + tileCount) % tileCount;
```

---

## 🛠️ Tech Stack

- **HTML5 Canvas**
- **CSS3**
- **JavaScript (Vanilla)**

---

## 📜 License

Add your preferred license here (e.g., MIT License).

---

## 🙌 Contributing

Contributions, suggestions, and pull requests are welcome!






-----------------------------------------------------------------------------------------------------------------------------------

# 🐍 Snake Game (HTML / CSS / JavaScript)

간단한 웹 기반 스네이크 게임입니다.  
하나의 HTML 파일 안에 **HTML + CSS + JavaScript**가 모두 포함되어 있어 바로 실행할 수 있습니다.

---

## 🎮 게임 특징

- 방향키(↑ ↓ ← →)로 뱀을 조작합니다.
- 벽에 닿으면 게임 오버가 아니라 **반대편 화면으로 이동(워프)** 합니다.
- 음식(빨간 블록)을 먹으면 점수가 올라가고 뱀이 길어집니다.
- 스페이스바 또는 버튼으로 게임을 시작하거나 다시 시작할 수 있습니다.
- 별도의 라이브러리 없이 **순수 HTML5 Canvas**로 구현되었습니다.

---

## 📂 파일 구성

이 프로젝트는 단 하나의 파일로 구성됩니다.

```
index.html
```

HTML 내부에 CSS와 JavaScript가 모두 포함되어 있어 브라우저에서 바로 실행할 수 있습니다.

---

## 🚀 실행 방법

1. 이 저장소를 클론하거나 ZIP으로 다운로드합니다.

```
git clone https://github.com/사용자명/저장소명.git
```

2. `index.html` 파일을 더블 클릭하여 브라우저에서 실행합니다.

---

## 🕹️ 조작 방법

| 키 | 기능 |
|----|------|
| ↑ | 위로 이동 |
| ↓ | 아래로 이동 |
| ← | 왼쪽으로 이동 |
| → | 오른쪽으로 이동 |
| Space | 게임 시작 / 다시 시작 |

---

## 📸 게임 화면 예시

(원하시면 스크린샷을 여기에 추가하세요!)

```
![snake-game](./screenshot.png)
```

---

## 🧩 주요 기능 코드 설명

### 화면 워프 처리

뱀이 화면 밖으로 나가면 반대편에서 등장합니다.

```js
head.x = (head.x + tileCount) % tileCount;
head.y = (head.y + tileCount) % tileCount;
```

---

## 🛠️ 기술 스택

- **HTML5 Canvas**
- **CSS3**
- **Vanilla JavaScript**

---

## 📜 라이선스

원하시는 라이선스를 선택해 추가하세요.  
예: MIT License

---

## 🙌 기여

버그 제보, 기능 제안, PR 모두 환영합니다!

---

필요하시면 **프로젝트 배너**, **GIF 데모**, **배포용 GitHub Pages 설정**도 만들어 드릴게요.
