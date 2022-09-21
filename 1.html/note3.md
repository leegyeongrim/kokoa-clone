2-9  
- label은 id랑 같이 있어야 한다. for, id를 일치시키면 label 클릭 시 for와 같은 값을 들고 있는 input을 작동시킨다.

- for와 id에는 공백 입력하면 안 된다.

- ★id는 scripting이나 css를 식별하려는 목적을 가진 attribute.

- ★id는 body 안에 어떤 태그에도 넣을 수 있는 attribute.  
그렇게 할 수 있는 이유는 id가 unique identifier(고유식별자)이기 때문.  

- element 당 하나의 id만 가질 수 있다.  
그리고 그 id 값은 고유해야 한다.(body든 form이든 어딘가에 똑같은 id값이 있으면 안 된다.)  
  
  왜 그래야 하냐면 css가 html에 있는 요소들을 지정해서 지시를 내릴 때 id를 기준으로 내리기 때문.  


2-10
- semantic=문서를 보기만 해도 그 의미를 짐작할 수 있는 것.
- 빠르게 그게 무엇인지 인식할 수 있다. 그러므로 semantic을 많이 쓰도록 하자. 
- div, header, main, footer(꼬리말)