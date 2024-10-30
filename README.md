# 로또
## 목표
1~45까지의 숫자 중 **중복되지 않게 6개의 당첨 숫자**를 입력받은 후,   
**로또 구입 금액**을 입력받은 뒤에 **중복되지 않는 숫자 6개와 보너스 숫자 1개**를   
입력받은 금액의 **로또 수량만큼** 무작위 추첨해 **당첨된 수량과 수익률**을 출력
## 기능

## 패키지 / 클래스

## 입출력 예시
### 입력
- 로또 구입 금액을 입력받음
```angular2html
14000
```
- 당첨 번호 6개를 중복되지 않게 쉼표로 구분해서 입력받음
```angular2html
1,2,3,4,5,6
```
- 보너스 번호를 입력받음
```angular2html
7
```
### 출력
- 발행한 로또 번호를 오름차순으로 정렬해 구입 수량만큼 출력
```angular2html
8개를 구매했습니다.
[8, 21, 23, 41, 42, 43] 
[3, 5, 11, 16, 32, 38] 
[7, 11, 16, 35, 36, 44] 
[1, 8, 11, 31, 41, 42] 
[13, 14, 16, 38, 42, 45] 
[7, 11, 30, 40, 42, 43] 
[2, 13, 22, 32, 38, 45] 
[1, 3, 5, 14, 22, 45]
```
- 당첨 내역을 출력
```angular2html
3개 일치 (5,000원) - 1개
4개 일치 (50,000원) - 0개
5개 일치 (1,500,000원) - 0개
5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
6개 일치 (2,000,000,000원) - 0개
```
- 수익률은 소수점 둘째 자리에서 반올림
```angular2html
총 수익률은 62.5%입니다.
```
- 예외 상황 시 에러 문구 출력("[ERROR]"로 시작해야 함)
```angular2html
[ERROR] 로또 번호는 1부터 45 사이의 숫자여야 합니다.
```
### 실행결과
```angular2html
구입금액을 입력해 주세요.
8000

8개를 구매했습니다.
[8, 21, 23, 41, 42, 43] 
[3, 5, 11, 16, 32, 38] 
[7, 11, 16, 35, 36, 44] 
[1, 8, 11, 31, 41, 42] 
[13, 14, 16, 38, 42, 45] 
[7, 11, 30, 40, 42, 43] 
[2, 13, 22, 32, 38, 45] 
[1, 3, 5, 14, 22, 45]

당첨 번호를 입력해 주세요.
1,2,3,4,5,6

보너스 번호를 입력해 주세요.
7

당첨 통계
---
3개 일치 (5,000원) - 1개
4개 일치 (50,000원) - 0개
5개 일치 (1,500,000원) - 0개
5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
6개 일치 (2,000,000,000원) - 0개
총 수익률은 62.5%입니다
```