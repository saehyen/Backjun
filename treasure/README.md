# treasure
두 리스트의 원소를 곱한값을 더한값중 최소값 구하기
- 1번째 방법(나의 답)은 A리스트를 오름차순으로 정렬하고 B리스트를 내림차순으로 정렬하여 곱한값을 sum으로 더하는 방식이었다.
- 이 방법은 간단하지만 72ms만큼의 시간이 걸리는 방법이다.

- 2번째 방법은 A리스트의 최대값과 B리스트의 최소값을 곱하여 더한뒤 원소에서 제거하는 방식이다.
- 이 방법은 sort가 필요없지만, 최대값과 최소값을 찾아 더하고 매번 삭제를 해야한다는 단점이 있다.