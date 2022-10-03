6.1.

- class  이름에 띄어쓰기 있으면 안됨. 두 개의 클래스로 인식함.
  __ 이렇게 아래 줄 두 개(?)로 써줄 것.
- 그리고 column 등의 class 이름을 지을 때는 id__column 같이 써주기. 그게 어디 있는 건지 쉽게 알 수 있게끔

6.2.

- BEM=Block Element Modifier
  더 쉽게 읽히는 css?
- .btn__price {}
- BEM에서 -- 는 modifier. 
- id를 쓰는지 class를 쓰는지 헷갈리니까 그냥 다 class를 써버리자.

6.3.

- script는 항상 body 닫기 바로 전에 있어야 한다. 

6.5.

- google font에서 폰트 가져올 수 있는데, 한 폰트 안에서도 내가 안 쓸 거는 안 가져오는 것도 중요. 다 가져오면 불러올 때 시간이 많이 걸릴 수 있기 때문.

- 요소들 정 중앙 중심으로 균형있게 배치하는 법

- *.status-bar*{

    display: flex;

    */\* justify-content: space-between; \*/*

    justify-content: center;

  }

  

  *.status-bar__column*{

    width: 33%;

  }

  *.**status-bar__column**:**nth-child*(2) {

    display: flex;

    justify-content: center;

  }

  *.**status-bar__column**:**last-child*{

    display: flex;

    justify-content: flex-end;

    align-items: center;

  }

- ​      <i *class*="fas fa-battery-half fa-2x"></i> 
  fa-2x 해주면 font awesome에서 가져온 아이콘 크기 크게할 수 있다.