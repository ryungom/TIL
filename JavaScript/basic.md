# JAVASCRIPT 입문
-   container class = 부트스트랩 그리드 시스템에 사용  
-   input 중에서 웹서비스 토큰에서 값이 안보일때는 type을 hidden으로 
-   deploy : 배포하기, 초보자가 사용하기 쉬운것 netlify 왠만한 트래픽 가능
-   addthis : sns 쉽게 공유할수있는 버튼 만들기 서비스
-   애드 네트워크 : 손쉽게 광고를 서비스에 붙일 수 있음. kakao adfit
-   네이버사이트 등록 : 네이버 서치어드바이저
-   sitemap addvisor 에서 사이트 등록후에 xml문서 생성
-   검색엔진 최적화 SEO: serch engine optimization
    -   seo가 최적화될 수록 검색엔진 상위에 뜨게 됌.
    -   내부요소 최적화(html 컨텐츠 메타태그 등)
    -   외부요소 최적화(백링크 개수 등. 다른사이트에서 링크건것들)
    -   title - document라고 검색하면 검색해서 들어올리가 없음
    -   meta name=”description” content=”사이트설명” 메타태그 필요
    -   네이버 웹 마스터 가이드의 내용 따라가면 SEO 최적화 테스트 가능
    -   js 마지막에 쓰는이유 : 코드는 위에서 아래로 읽기때문에 html 다 읽고와서 스크립트가 읽는게 좋아서
    -   세미콜론 : 하나의 명령어가 끝남.
    -   주석 : 컴퓨터가 못읽음.
        -   코드설명적거나 코드를 동작시키고싶지 않을때
    -   document,write() console.log 차이?
           -   변수 variable var
                -   es6 let, const
        -   자료형 구분 문자열string, ‘’ “”
        -   숫자형 정수int, 실수형float(소숫점 등),
        -   불린형 boolean true false
        -   typeof 데이터자료형 구분

    -   [로또번호 추첨기]
        -   math.random() 0이상 1미만 실수(float).
        -   *45 하면 0~45미만 실수뜸
        -   +1하면 1이상 46미만 실수
        -   parseInt 소숫점빼고 정수 int형으로.
        -   배열
            -   배열에 임의의숫자 6개 넣는거는 parseInt(Math.random()*45+1) 6개 쓰기
                -   난 그냥 *6 때려박음 머쓱
        -   반복문
            -   for, while
            -   for (시작; 끝; 증가) { 반복 코드 }
                -   특정 횟수만큼 동작
            -   반복문 var i 에서 i 를 쓰지 않아도 코드가 6번 반복되게 할 수 있음
            -   while 특정 조건까지 계속 반복할때까지 사용.
                -   while (조건) { 반복하려는 코드 }
        -   중복된 값 확인
            -   indexOf (값)이랑 == -1을 확인하면 중복값 확인 가능
                -   값이 있으면 위치값 나오고 없으면 -1
        -   .sort() 배열값 정렬, 그냥쓰면 앞자리 위주로 정렬.
            -   숫자크기는 .sor((a,b) ⇒ a-b) 익명함수. b-a 내림차순일단 알아만두기
        -   굳이 외우지말고 반복하다보면 코드가 익숙해질것임.
            
        
        [자기소개서 글자수]
        -   Dom - document Object Model. html코드 쉽게 접근
        -   id의 입력값 가져오기 : value;
        -   문자열의 길이 : .length 배열에서도 가능. string에서의 자료형도 문자열의 길이 파악가능
        -   이벤트가 발생: 키보드를 누룰때. 하면 ㅇㅇ해라 : 이벤트 핸들링
        -   이벤트 = 이벤트 헨들링 ←이렇게 작성
        -   substring : 글자수 제한에 이용되는 이벤트
            -   substring(0,5) 0이상 5미만. 200글자이상 잘라보자
        
        [미니스타크래프트]
        -   제이쿼리에서 document.getElementById(’content’).value; 이걸 줄여서
            -   $(’#content’).val(); 쌉가능
        -   제이쿼리 크로스브라우징 좋음. 모든브라우저 사용 가능
        -   익명함수. 함수이름없이 바로 실행 가능.
        -   제이쿼리 홈페이지 api 찾아보면 공식사용문서 찾아볼 수 있음.
            -   [  ] 대괄호 있으면 선택사항임
            -   코딩은 배울게 너무 많음. 구글링을 습관 길러보기.
        -   콜백
        -   animate, css는 {()} 들어가야 함. property에 ‘’ 넣어두기
