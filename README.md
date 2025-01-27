# BasicToHighStudy(python)
<div>
  <h2>2024.12.26</h2>
  
  <h3>is, == 차이점</h3>
  <p>== - 값을 비교</p>
  <p>is - 값과 참조를 비교함</p>

  <h3>swapcase 문자열 대소문자 변환 함수</h3>
  <p>str = str.swapcase() -> X</p>
  <p>print(str.swapcase()) -> O</p>
</div>

<div>
  <h2>2024.12.27</h2>
  
  <h3>print 출력 방법</h3>
  <ul>
    <li>print("{} + {} = {}".format(a,b,a+b))</li>
    <li>print(f"{a} + {b} = {a + b}")</li>
  </ul>
  
  <h3>특수문자열 쉽게  출력하기</h3>
  <p>print(r'!@#$%^&*(\'"<>?:;')</p>

  <div>
    <h2>2024.12.30</h2>
    <h3>프로그래머스 - 수열과 구간 쿼리3</h3>
  </div>
  ```python
    def solution(arr, queries):
      answer = []
      for k in range(len(queries)):
        i = queries[k][0]
        j = queries[k][1]
        arr[i], arr[j] = arr[j], arr[i]
    ```
  
  <div></div>
  
  <div></div>
  
  <div></div>
  
  <div></div>
</div>
