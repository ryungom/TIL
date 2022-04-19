# Flex와 Grid를 알아보자
-   Flex
	-  width값 위주 계산. 가로나 세로로 정렬되어있는 content 정렬에 효과적인 방법.    
	-   해당요소는 width값 무시하고 부모영역 차지, 자식요소에 사용됌   
	-   flex-order는 접근성 향상을 위해서 사용될 수 있다.
	    -   숫자그대로 옮기는게 아니라 가장 큰 숫자가 옮겨짐    
	-   modal은 positon으로 하나 똑 띄워둔거랑 같음   
	-   ** 중앙정렬의 기본공식 justify-content:center, align-items center  **
	- align-items는 한줄일때 중앙정렬.
	- justify-content랑 flex-direction reverse로 하면 flex 시작점의 끝이 시작이 됌
    
-   Grid
	- 가로,세로를 포함하여 좀 더 복잡한 이미지 레이아웃 정렬에 특화되어 있음
    -   달력만들때 테이블이 아닌 그리드가 훨음
    -   그리드에서 n / n 은 분수가 아니다. start와 end 표시
-   flex,grid는 pixel 간격 정확하게 맞추기가 어렵다. 이를위해 float 방식의 정렬도 잘 알아야 함.
