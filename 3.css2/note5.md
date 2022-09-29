4.0.

- transition:어떤 상태에서 다른 상태로의 변화를 애니매이션으로 만드는 것.

- transition은 state가 없는 요소에 붙어야 한다?
  저기다 놓으면 변화 트리거 사라지면, 예를 들어 마우스 떼면 즉각 원래대로 돌아간다. 

  =a에 붙인다고 하면 a{transition:... } 이렇게 해야지, a:hover 있는 데에다가 하면 안 된다. 

- transition: 적용시킬요소 시간 등등
  transition: background-color 5s ease-in-out, color 3s ease-in-out;

- transition:all 이렇게도 가능. 이러면 배경, 글자색 등 모든 것에 적용.

4.1.

- https://matthewlein.com
- duration:1000이 1초.
- linear:시작-끝까지 속도 일정. 
- ease in :점점 빨라짐. 
- ease out:점점 느려짐.
- cubic-bezier : all 1000ms cubic-bezier (0.250, 0.250, 0.750, 0.750); /* linear */
  나만의 커브를 만들 수 있게 한다. 
- 살짝 주의- cubic-bezier(0.250 <-이거 스페이스 하면 안됨. 붙여써야 함. 

4.2.

- border:이미지보다 작을 경우 바깥 부분 이미지는 안 보임.
- border-radius: 50% = 원이 됨. 
- transform:rotateY Y축 회전. 90deg로 하면 말 그대로 90도를 돌려 이미지의 측면이 정면으로 오는 거기 때문에 안 보임. 
- scale:축 방향으로 크기를 늘림. 1보다 작게 하면 줄어들게도 할 수 있음. 
- translate:위치 옮기기. 
- ★★transform의 명령은 다른 형제(sibling)을 변화시키지는 않는다. 
  무슨 말이냐면,  예를 들어 img 바로 다음에 span이 있으면 img를 transform 시켜도 span에는 영향을 안 준다. 다른 요소들의 위치는 그대로다. 
  transformation은 box element를 변형시키지 않는다. = margin, padding이 적용되지 않는다. 
  우리가 변형시키는 건 픽셀이지, margin, padding을 위해 translate를 사용하지 않는다. 
  다른 형제 요소는 img가 그냥 그 자리에 있다고 생각한다. 
- skew는 비스듬히 기울이기. 각도 입력해야 함. 
- cf 이런 효과들, 애니매이션은 그래픽 카드에 의해 돌아가는 것.
- 더 많은 효과들은 transform mdn 참고.