### garbage collector?

메모리 할당을 추적하고 할당된 메모리 영역이 필요하지 않은 영역일 경우 판단해서 회수 하는 것

자바스크립트에서 변수는 직접적으로 참조값을 담고 있지 않고, 해당 값을 메모리 상에 저장한다. 참조값을 생성하고 나서 더 이상 참조할 것이 없거나 비어졌을 때 garbage collector가 동작해서 메모리가 반환된다. → 메모리를 다시 재 사용할 수 있는 상태가 된다.
