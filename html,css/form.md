# ✨오늘의 포스팅
- [HTML Living Standard | Form](https://ryungom.tistory.com/79)

---

# Form 태그 알아보기
-   iframe
    -   외부 페이지들을 가져오기에 안성맞춤인 페이지. 단점도 존재하는데 백도어로 해킹할 수 잇는 위험성도 있음
-   audio, video
    -   주의사항 : 트래픽 주의.실서비스 할때 주의해야함
    -   동영상 2~3개정도 서비스하게 되면 그날 트래픽 전부 사용하게 됨. 10명만 봐도 끝장남
-   track, 코덱, 포멧(교안 확인하기)
-   form
    
    -   버튼태그의 기본type : submit
    -   form method 보내는 방법 action 어디로 보내겠다
    -   input에 name값을 지정하고 로그인하면, url창에 쿼리스트링으로 아이디 비번 입력값이 뜸
        -   form의 method를 post로 보내면 안보여지고 감춰짐. 서버로 전송됌.
        -   get은 url로 요청을 보낸다
        -   post는 url로 전달이 아닌 body에 전달됨
    -   hidden
        -   과소평가ㄴㄴ.
        - 인터렉션한 페이지를 만들 때 수치값 저장해서 안보이게끔 하는 용도로도 쓰임

    -   radio
        -   label이랑 같이 사용. p태그 쓰면 글자 눌러도 클릭이 안되는데 라벨이랑 같이 묶이면 글자 눌러도 선택 가능함.
    -   [샘플이미지](https://via.placeholder.com/640x400) 이미지계의 로렘입섬