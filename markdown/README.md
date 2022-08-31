1. 제목 작성
제목을 작성하고 싶을 경우에는 앞에 #을 붙여 만든다.
syntax : # 제목 or ## 부제목 (#을 붙일 때마다 글씨 크기가 줄어든다)
# Title
## subtitle

2. 번호 없는 리스트 작성
앞에 * or - or + 넣어서 작성
* list1
- list2

3. 이텔릭체 작성
텍스트 앞과 뒤에 * 혹은 _ 작성
syntax : *텍스트*

4. 굵은 글씨 작성
텍스트 앞과 뒤에 ** 혹은 __ 작성
syntax : **텍스트**

5. 인용
syntax : > 텍스트
> 텍스트
인용문 안에 인용문을 만들고 싶으면 > 기호 하나 더 추가

6. 수평선 넣기
기호(*, -, _ 3개 이상 나열)
syntax : ---
---

7. 링크달기

syntax : [텍스트](링크주소) or [텍스트][참조명] \n [참조명]:링크주소

[블로그 참조] (https://lsh424.tistory.com/37)
[블로그 참조] (https://lsh424.tistory.com/37)
[블로그 참조]:https://lsh424.tistory.com/37

8. 코드 블록 추가하기
위 아래 줄에 가센트 기호 파이썬 참조문이랑 같음 (""" """)
```
from collections import deque
dq = deque()
```
