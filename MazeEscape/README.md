# Maze-Escape
미로를 탈출하는 최단경로 구하기(BFS)

- N x M 크기의 직사각형 형태의 미로에 갖혀있음.
- (1,1)의 위치부터 시작하여 (N,M)의 위치에 도달해야함.
- 출발지부터 도착지까지 최단거리로 이동해야함

- 사용하는 문법
- 방향을 정해서 리스트에 저장하는 방법을 사용
- dx = [-1,1,0,0] dy = [0,0,1,-1]
- queue 사용(bfs를 구현하기 위하여)


- BFS를 사용하는 이유?
- 미로 탈출과 관련해서 최단거리를 구하는 것은 BFS를 이용하면 효율적으로 구할 수 있다.

- 이를 통해 DFS를 사용하는 경우와 BFS를 사용하는 경우를 나누어볼 수 있다.

- BFS는 최단거리를 구할 때 사용
- DFS는 연결되어있는 덩어리를 구할 때 사용