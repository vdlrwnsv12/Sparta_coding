<h1>달리기 반</h1>
<h2>1.팩토리얼 계산</h2>
**사용자로부터 입력받은 숫자의 팩토리얼을 계산하는 프로그램을 작성하세요.**
  
    - 팩토리얼은 n!로 표현되며, n! = n × (n-1) × (n-2) × ... × 1입니다.
    - 예를 들어, 5! = 5 × 4 × 3 × 2 × 1 = 120입니다.
    - `for`, `while`, `do-while`문 중 하나를 활용하여 해결해주세요.
    - Console.ReadLind() 을 활용해서 출력 값을 출력해주세요.
    

- 예상출력

```
Enter a number: 5
Factorial of 5 is 120
```
<img width="653" alt="스크린샷 2025-01-08 오후 2 37 47" src="https://github.com/user-attachments/assets/6ecfda3e-3e95-4bab-ad90-756fb1d6faab" /> <br>
<s> 오타 수정 귀찮아서 안함 </s>

-------------------
<h2>2.숫자 맞히기</h2>
- [ ]  개발환경 구축 완료<br>
- [ ]  배열에 대한 이해<br>
- [ ]  제어문 중 반복문(`for`, `while`, `do-while`)과 조건문(`if`, `else if` , )에 대한 이해<br>
- [ ]  배열 (`Random` 클래스 사용)<br>

<aside>
🍀 **본격적으로 시작해 볼까요?**

</aside>

- **숫자 맞추기 게임을 작성하세요.**<br>
```
컴퓨터가 1부터 100 사이의 숫자를 선택하면 사용자가 그 숫자를 맞추는 게임을 구현하세요. 
사용자가 숫자를 입력하면 컴퓨터는 숫자가 더 크거나 작은지 힌트를 줍니다.
맞출 때까지 반복합니다.
```
- 예상출력

```
Enter your guess (1-100): 50
Too low! Try again.
Enter your guess (1-100): 75
Too high! Try again.
Enter your guess (1-100): 60
Congratulations! You guessed the number.
```
<img width="750" alt="스크린샷 2025-01-08 오후 3 20 02" src="https://github.com/user-attachments/assets/dfdabea4-44eb-4edb-9e5f-4efd70642426" />

<h2>구구단</h2>
- 이중 반복문을 사용하여 2단부터 9단까지의 구구단을 출력하는 프로그램을 작성하세요. 각 단은 1부터 9까지 곱하여 결과를 출력해야 합니다.
    - **구구단 세로로 출력해 주세요**
        - 출력 예시
        
        ```csharp
        2 x 1 = 2    3 x 1 = 3    4 x 1 = 4    ...   9 x 1 = 9
        2 x 2 = 4    3 x 2 = 6    4 x 2 = 8    ...   9 x 2 = 18
        ...
        2 x 9 = 18   3 x 9 = 27   4 x 9 = 36   ...   9 x 9 = 81
        ```
  <img width="1003" alt="스크린샷 2025-01-08 오후 3 37 09" src="https://github.com/user-attachments/assets/0232ff78-26ed-45e9-9386-698039e23da7" />
  
    - **구구단 가로로 출력해 주세요**

        - 출력 예시
        
        ```csharp
        2 x 1 = 2    2 x 2 = 4    2 x 3 = 6    ...   2 x 9 = 18

        3 x 1 = 3    3 x 2 = 6    3 x 3 = 9    ...   3 x 9 = 27
        ...
        9 x 1 = 9    9 x 2 = 18   9 x 3 = 27   ...   9 x 9 = 81
        
        ```
   <img width="523" alt="스크린샷 2025-01-08 오후 3 39 19" src="https://github.com/user-attachments/assets/52a31d0a-cd3c-4965-87a5-be2a3ed4b432" />
