### position?

css에서는 position option을 줄 수 있다.

각 요소의 position을 어떻게 지정하는지에 따라 뷰와 구성이 달라지게 된다.

### option

1. static
   - 요소들이 문서의 일반적인 흐름에 따라 배치된다.
   - 기본적인 요소 옵션, position 옵션을 아무것도 지정하지 않으면 기본적으로 static 옵션이 들어간다.
   - static의 경우 top, right, bottom, left,z-index 속성들이 아무런 효과를 주지 못한다.
2. relative
   - 요소들이 문서의 일반적인 흐름에 따라 배치가 된다.
   - 요소의 static 위치에서 상대적인 위치에 배치가 된다.
   - top:100px 옵션을 주게 되면, 원래 static이었을때의 위치를 기준으로 100px을 주게 된다.
   - 다른 요소들의 위치에 영향을 주지 않는 특성이 있기 때문에 글자가 겹칠 수 있다.
3. absolute
   - 문서의 일반적인 흐름을 따르지 않는다.
   - 가장 가까운 위치에 있는 요소에 대해 상대적 위치로 배치된다.
   - 조상 요소가 없으면 body를 기준으로 상대적 위치를 배치한다.
4. fixed
   - 문서의 일반적인 흐름을 따르지 않는다.
   - 스크린의 뷰포트를 기준으로 한 위치에 배치된다.
   - 고정된 자리를 가지게 된다.
   - 뷰포트: 웹페이지가 사용자에게 보여지는 영역
5. sticky
   - 문서의 일반적인 흐름에 따라 배치된다.
   - 다른 요소들에 영향을 주지 않는 특성을 가진다.
   - 문서의 흐름을 따르면서 containing box를 기준으로 상대적인 위치에 배치된다. → fixed를 쓰면 요소들이 겹쳐보일 수 있지만, sticky를 쓰면 그런 상황을 예방할 수 있다.
