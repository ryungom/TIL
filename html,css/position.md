
# ✨오늘의 포스팅
- [position의 fixed, stickey 가 어떻게 구분될까?](https://ryungom.tistory.com/85)
## position 의 이해
- 기본적으로 relative라는 근본이 되는 요소를 기준으로 좌측 상단을 0,0 좌표 기준으로 하위 요소들을 맞추는 방법.
- 이중 fixed와 stickey 속성은 고정속성인데, 조금 역할이 다름.
	- 두 속성의 같은점들은 화면에서 해당 position 값들을 고정하는 것.
	- fixed : 위치 변동없이 아예 완전히 고정하는 요소. 
	- sticky : 스크롤에 적용되면서 스크롤이 해당 높이를 지나가게 되면 화면 위쪽에 달라붙게 만듦
- position 속성의 쓰이는 요소 이해
	-    부모와 자식이 position relative, absolute 관계면 z-index 가 안먹음.
		- 노멀Flow의 HTML 흐름을 이해해야 한다. 노멀Flow -> float -> positon 이렇게 나뉘기 때문에 계층이 다르면 서로 레이아웃이 맞지 않음...
		- 해당 이유로 인해 레이아웃 잡을때는 똑 떨어진 요소가 아닌이상 레이아웃으로 position을 잘 잡지 않는다
	-   z-index는 10단위로 주는것이 좋다. 100단위는 잘 보기 어렵. 중간에 내용을 수정할 일도 있기 때문에

## position의 정렬
- position은 **view port** 기준으로 정렬되는 것이다. html 기준이 아님
	- position이 static이 아닐 경우 부모요소의 컨테이너 블록이 아닌 view port 기준으로 정렬되는 것 
- 가상요소(inline)에 position을 주게 되면 block이 됌. 그렇기에 display:block을 넣어 주지 않아도 컨텐츠 요소만큼의 크기를 가지게 되는 블록레벨 요소가 된다. normal-flow를 벗어나게 된다는 뜻.
	- 비슷한 요소로 inline에 float을 주어도 block이 됌.
- left:0, right:0을 주는것은 block 요소마냥 가용 공간을 늘리겠다는 뜻.
- position으로 중앙 정렬하는 방법은 translate속성과 함께 이용한다.
	- transform:translate(-50%,-50%); top:50%; left:50%;