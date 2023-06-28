ERD


<img src="https://github.com/leegyeongsik/blog-v3/assets/67450537/f2a04217-6d8c-4cf5-bcc2-ca719196f72f"  width="700" height="370">

API명세서


<img src="https://github.com/leegyeongsik/blog-v3/assets/67450537/c2c05360-f119-4e9d-91b2-61c92024350f"  width="700" height="370">
<img src="https://github.com/leegyeongsik/blog-v3/assets/67450537/5a2adfc5-75a6-4cef-8923-8ec8668f2a08"  width="700" height="370">
<img src="https://github.com/leegyeongsik/blog-v3/assets/67450537/707a6117-af53-45fb-bfd1-c0a17052dad8"  width="700" height="370">




Q1) 댓글이 달려있는 게시글을 삭제하려고 할 때 무슨 문제가 발생할까요? 
JPA가 아닌 Database 테이블 관점에서 해결방법이 무엇일까요?
댓글entity에 외래키가 걸려있다면 게시글을 삭제할수없게 된다 

Q2) Q1과 같은 문제가 발생했을 때 JPA에서는 어떻게 해결할 수 있을까요?
게시판이 삭제된다면 댓글 entity에 담겨있는 게시판도 삭제한다

Q3) IoC / DI 에 대해 간략하게 설명해 주세요!

제어의 역전 IoC - 제어의 흐름을 전통적인 방식과 다르게 뒤바뀌는 것
의존성 주입 DI - 사용할 객체를 외부에서 주입받는 것
