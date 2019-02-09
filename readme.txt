<문제 2>

1) Purpose of this code.

Tree들의 구조는 이미 선언되어 있고 이 tree들의 successor를 찾는 코드이다. 

2) Input and Output 

우선 tree들의 구조체를 선언했다. linked tree의 구조체를 선언하여 구조체 안에 data, leftchild, rightchild, parent의 포인터 주소
들을 선언해서 각각의 node들을 연결하였다. output은 순서대로 succesor가 나오도록 하였다. a가 가장 왼쪽에 있는 노드라면
a를 먼저 출력하고 a의 successor c, c의 successor b가 나올 수 있도록 하였다.

3) variables I used
가장 중요한 변수는 tree의 각 노드들인 구조체 변수이다. parent 포인터 변수를 더 추가하여 쉽게 successor나 predecessor에 접근할
수 있도록 하였다. 또한 이 구조체 노드들을 각각의 함수에 집어넣어 원하는 결과를 출력할 수 있도록 하였다.

<문제 3>

1) Purpose of this code.

tree 들의 predecessor를 찾는 구조이다.

2) Input and Output 

input은 문제 2의 것과 같고 output으로는 순서대로 predecessor가 나오도록 하였다. e가 가장 왼쪽에 있는 노드라면 e를 먼저
출력하고 e의 predecessor f, f의 predecessor d가 나올 수 있도록 하였다.

3) variables I used
가장 중요한 변수는 tree의 각 노드들인 구조체 변수이다. parent 포인터 변수를 더 추가하여 쉽게 successor나 predecessor에 접근할
수 있도록 하였다. 또한 이 구조체 노드들을 각각의 함수에 집어넣어 원하는 결과를 출력할 수 있도록 하였다.