# scope, this

# scope(스코프)
스코프는 범위이다.

## 스코프의 종류 


## this
- 함수는 dynamic
    - 일반 함수, 콜백 함수, 내부 함수는 모두 함수이다.
    - 호출 주체가 없다. (=this는 전역객체를 참조한다)
- 메서드는 객체 
    - 객체의 메서드의 this는 객체에 묶인다. (Lexical)
- 자바스크립트에서 this는 기본적으로 실행 컨텍스트가 생성될 때 함께 결정된다.
    - this는 함수를 호출할 때 결정된다.


## 참고자료
- [도서] 코어 자바스크립트 - 정재남 지음
- [[im-d-team/Dev-Docs] : scope_this.md](https://github.com/im-d-team/Dev-Docs/blob/master/Javascript/scope_this.md)