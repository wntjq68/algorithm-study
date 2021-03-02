# Baekjoon 1806 : 부분 합

## Solution Logic

1. 정렬된 배열을 이용하기 위해 누적합에 대한 정보를 담은 배열을 만든다. -> sum[]

2. i = 배열의 시작 -1, j = 배열의 마지막 인덱스

3. i != j && j <= 원소의 갯수 조건을 만족 하면 밑의 조건식을 반복한다.
    - sum[j] - sum[i](부분합) > s : j - i (원소의 갯수) 가 기존의 답보다 작으면 답으로 한다. 그리고 i 를 1 더해준다.
    - 위조건에 만족하지 않는다면, j를 1 더해준다.