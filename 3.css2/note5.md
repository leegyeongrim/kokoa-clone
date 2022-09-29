4.0.

- transition:어떤 상태에서 다른 상태로의 변화를 애니매이션으로 만드는 것.

- transition은 state가 없는 요소에 붙어야 한다?
  저기다 놓으면 변화 트리거 사라지면, 예를 들어 마우스 떼면 즉각 원래대로 돌아간다. 

  =a에 붙인다고 하면 a{transition:... } 이렇게 해야지, a:hover 있는 데에다가 하면 안 된다. 

- transition: 적용시킬요소 시간 등등
  transition: background-color 5s ease-in-out, color 3s ease-in-out;

- transition:all 이렇게도 가능. 이러면 배경, 글자색 등 모든 것에 적용.