## Baekjoon 6603 : 로또

### 논리순서

1. DFS를 이용하여 탐색
2. 사전 순서를 위해 맨 처음 받은 배열을 정렬해준다.
3. 숫자를 하나씩 집어 넣으면서 깊이를 늘려주고 방문한 노드에 대해 방문을 표시해준다.
4. 로또 갯수 만큼 깊이가 내려가면 그떄 배열에 집어 넣어진 수들을 출력해준다.
5. 다시 부모 노드로 돌아가면서 방문 표시한 기록을 없애주면서 위과정을 반복한다.