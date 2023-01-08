# 1강
## 스택 자료구조 
#### 먼저 들어 온 데이터가 나중에 나가는 형식(선입후출)의 자료구조입니다. 
#### 입구와 출구가 동일한 형태로 스택을 시각화할 수 있습니다. 
```
stack = []
stack.append()
stack.pop()
```
<br/>

## 큐 자료구조
#### 먼저 들어 온 데이터가 먼저 나가는 형식(선입선출)의 자료구조입니다.
#### 큐는 입구와 출구가 모두 뚫려 있는 터널과 같은 형태로 시각화 할 수 있습니다. 
```
from collections import deque #큐 구현을 위해 deque 라이브러리 사용
queue = deque()

queue.append()
queue.popleft()
```
<br/>

