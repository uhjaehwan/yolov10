# yolov10
##마크다운 문법
### 구리고등학교

###1학년 김민재 ![image](https://github.com/user-attachments/assets/3d0f348b-4fa5-4157-9119-a2cbae89442a)

#####구구단 만들기


```bash
for i in range(2, 10):  # 2단부터 9단까지 반복
    print(f"📌 {i}단")
    for j in range(1, 10):  # 1부터 9까지 곱하기
        print(f"{i} × {j} = {i * j}")
    print()  # 줄 바꿈
```
```bash
dan = int(input("출력할 구구단을 입력하세요: "))

# 구구단 출력
print(f"\n📌 {dan}단")
for i in range(1, 10):
    print(f"{dan} × {i} = {dan * i}")
```
