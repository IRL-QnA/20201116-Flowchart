## 문제

[순서도 랩터로 어떻게 작성할 지 #1](/../../issues/1)

<details>
<summary>:open_book: 문제 보기</summary>

  ### 문제

  아래 (출력)과 같이 문자열이 출력될 수 있도록 하는 <b>"자연어, 순서도, 파이썬, C언어"</b>까지 기술하여 보자.

  ### 입출력 형식

  (입력) 원가가 1000원인 과자를 1300원에 25개를 팔았다.
  ※ 총 판매액과 판매이익을 아래와 같이 출력한다.

  (출력)
  ```text
  Total Sales Price : 32500
  Sales Profit : 7500
  ```

</details>

---

## 순서도

```
(Start)
 v
[price <- 1000]
 v
[sell <- 1300]
 v
[n <- 25]
 v
[total_sales_price <- sell*n]
 v
[sales_profit <- total_sales_price - price*n]
 v
/PUT "Total Sales Price : "+total_sales_pricec/
 v
/PUT "Sales Profit : "+sales_profit/ ->
 v
(End)
```

참조: [#](https://fishpoint.tistory.com/1647)
