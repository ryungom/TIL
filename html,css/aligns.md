# text-align, 텍스트 정렬을 알아보자
-  이미지 공백 생기는거는 폰트의 베이스라인때문 (yello world 예제). 해결하려면 vertical-align:top 넣으면 됌. 이미지가 탑 기준으로 정렬.
-   이미지 자체에는 여백이 없음. 이미지랑 텍스트가 같은 inline 요소이기 때문에
-   이미지와 텍스트와의 공백을 해결하기 위해 block화 시키면 협업에서 문제가 생길 수 있음. 이미지자체가 인라인인데 강제로 블록화시키면 안됌
-   자식요소를 정렬하는것임.
-   예제를 정리하는 습관을 들어보자
-   인라인이든 블록이던 수평정렬만 가능.
-   블록요소는 원래 100%이므로 수평정렬 적용안됌
-   margin 0 auto
    -   자기자신을 중앙정렬, 블럭요소가 부모의 전체 width를 가지고 있을경우 원하는 중앙 정렬을 얻을 수 없음
    -   자기자신이 inline-block일경우 사용x
    -   inline요소를 block으로 바꾼다음 width를 부모보다 좁게 사용하면 사용o 부모요소의 width랑 같으면 자식도 꽉차서 공간이 부족하여 정렬이 불가능함으로.
    -   transform:translate(-50%) left(50%) → 하드웨어 가속을 이용하기도 하므로 다양한 ui에 사용됌. css 최적화
-   사소한부분에 너무 신경쓰지 말고나머지 부분에 더욱 더 신경쓰기. html, css의 비율은 개념정도로만 알고있자. 중앙정렬도 마찬가지
-   text-decoration underline wavy 손글씨느낌의 밑줄

# vertical-align, 수직정렬을 알아보자.
- img태그의 바깥쪽 공백을 없애기 위하여 자주 사용(속성은 주로 top으로)
- 여백이 생기는 이유 - font때문에 그렇다.
- 값이 여러가지가 있다. 주로 baseline, top 위주로 사용됌
    - vertical-align: baseline;
    vertical-align: sub;
    vertical-align: super;
    vertical-align: text-top;
    vertical-align: text-bottom;
    vertical-align: middle;
    vertical-align: top;
    vertical-align: bottom;