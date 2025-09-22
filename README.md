<div align="center" style="background-color:black; padding:20px;">
  <img src="https://giffiles.alphacoders.com/219/219162.gif" width="500">
</div>

<h1 align="center">👩‍💻 Yeeun Kim </h1>

<h3 align="center"><i>"햅삐얍삐"</i></h3>

<p align="center">

  <!-- Animated typing SVG -->

</p>

## 📈 Profile Views

![Profile Views](https://komarev.com/ghpvc/?username=yeun04226&style=for-the-badge)

---

### 🔥 Commit Streak
![GitHub Streak](https://streak-stats.vercel.app/?user=yeun04226&theme=light&hide_border=true)

---
## About Me

* NAME : YEEUN KIM

* INTENDED MAJOR : DATA SCIENCE / PREVIOUS MAJOR : BUSINESS ADMINISTRATION

* PERSONALITY : INDEPENDENT BUT WARM-HEARTED🌼

* I'M STUDYING IELTS

* I LOVE JUSTIN BIEBER THE MOST  

<p>
  <img src="https://img.youtube.com/vi/msGuqelopMA/0.jpg" width="120" align="middle">
  👉🏻 <a href="https://youtu.be/msGuqelopMA?si=RSFENETjNJ6d2Q05">click and listen here!</a>
</p>

---
## HOBBY
- 영화 보기
- 노래 찾기
- 누워 있기

import random  # 랜덤 숫자 뽑기

print("Guess the number!")  # 게임 시작 안내

secret_number = random.randint(1, 100)  # 1~100 사이 랜덤 숫자

# print(f"The secret number is {secret_number}")  # 디버깅용 (정답 미리 보기)

while True:  # 정답을 맞출 때까지 반복
    guess = input("Please input your guess: ")

    if not guess.isdigit():  # 숫자가 아니면 다시 입력
        print("Please enter a valid number!")
        continue

    guess = int(guess)
    print(f"You guessed: {guess}")

    if guess < secret_number:
        print("Too small!")
    elif guess > secret_number:
        print("Too big!")
    else:
        print("You win!")
        break
