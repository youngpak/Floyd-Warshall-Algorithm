# Floyd-Warshall-Algorithm

- 플루이드 워셜(Floyd-Warshall Algorithm) 알고리즘

- 플루이드 워셜 알고리즘은 모든 지점에서 모든 지점으로의 최단 경로를 모두 구하는 경우에 활용할 수 있는 알고리즘이다.
노드의 개수가 N개일 때 N번의 단계를 수행하며, 단계마다 모든 노드에 대하여 다른 모든 노드로 가는 최단 거리 정보를 담기 위한 2차원 리스트를 생성하는 O(N²)의 연산을 한다. 따라서 N번의 단계마다 O(N²)의 연산을 필요로 하는 이 알고리즘의 총시간 복잡도는 O(N³)이다.
