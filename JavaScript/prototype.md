 # Prototype
  - 모든 인스턴스가 하나의 메서드를 공유하도록 만들어 자원을 더 효율적으로 사용하도록 도와주는 것.
  - 메서드를 저장하는 공간이라고 생각하자.
  - this는 인스턴스를 가르킴.
  - 예시
  ```javascript
      this.sayYourName = function(){
        console.log(`삐리비리. 제 이름은 ${this.name}입니다. 주인님.`);
      }
  ```
  - 이렇게 만들면 100개의 객체를 만들때마다 100개의 함수를 새로 만들어냄. 그래서 이러한 자원의 낭비를 막기위해 만들어낸것이 다음과 같은 프로토타입.
  ```javascript
      function NewFactory2(name){
        this.name = name;
      }

      NewFactory2.prototype.sayYourName = function(){
        console.log(`삐리비리. 제 이름은 ${this.name}입니다. 주인님.`);
      }
  ```

  