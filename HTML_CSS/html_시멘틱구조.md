## 시멘틱구조

아무 생각 없이 그냥 태그 꽂아넣던 시절이 있었다. 물론 지금도 그렇다. 마크업을 배우기 위해 html의 기초부터 다시 배우고 있지만 다시라는 말이 무색하게 모르는 것이 너무 많다. 사람은 한 눈에 보고 구조를 알 수 있지만 컴퓨터는 다르다. 그렇기 때문에 시멘틱 태그를 사용해 컴퓨터를 이해시키는 것이 목적이다. 컴퓨터가 이해하기 쉽게 작성한 코드는 물론 사람들이 보기에도 더 간편해진다.

```jsx

// 시멘틱한 html의 예
<header>
   <nav />
</header>

<main>
	<section>
	  <header />
		<article />
		<footer />
	 </section>
</main>
<footer></footer>
```

위의 태그들은 html을 아는 사람이라면 어떻게 구성되어 있는지 쉽게 파악 할 수 있을만한 코드이다. 전체적으로는 세가지 파트로 구분되어 있고, 그 안에서도 이해하는 것에 크게 무리가 없을 정도로 직관적이다.

시멘틱 태그는 모두 div 태그와 같은 기능을 수행하는 태그들이다. 하지만 태그의 이름이 곧 영역을 나타낸다는 점이 div태그와의 차이점이라고 할 수 있다.
