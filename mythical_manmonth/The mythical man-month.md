# The mythical man-month

__프로젝트 일정이 밀리는 고질적인 문제가 존재한다.__

이 문제의 원인은 계획을 예측하는 방법이 잘 못되었기 때문이다.

### Optimism

모든 프로그래머는 optimist이다.  따라서 모든 것이 잘될 것이라고 가정하고 계획을 세우는 것이 문제이다.

* 사람 생각의 incompleteness와 inconsistency는 implementation을 할때에야 분명히 드러난다.
* 프로그래밍의 도구는 매우 쉽게 다룰 수 있기 때문에 optimism을 가지고 구현을 시작할 것이고 도중에 문제가 생길 것이다.

### The'Man-Month

* 프로젝트 시간을 책정할때 시간을 표현하는 단위로 man-month개념을 사용하면 안된다. 이것이 적용가능할때는 작업이 한사람당 하나씩 쪼개질 수 있고 이들간의 communication이 없을때 뿐이다. 

* 프로그램 개발에 있어서 작업들이 sequential한 특성이 있기때문에 보통 완벽히 나누어질 수 없다. 그리고 이때는 사람을 추가한다고 시간에 영향을 주지 않는다. 

* 작업이 나누어지더라도 그 사이에 communication이 필요하면 오히려 악영향이 있을 수 있다.
* 작업이 어느정도까지 쪼개지고 나면 communication 비용이 이렇게 나눈 것에 대한 이익을 금방 넘어서 버린다.

### Systems Test

* 이 부분이 제일 sequential하고 optimism이 많이 작용하는 부분이다.
* Rule of thumb for scheduling a software task:
  l/3 planning
  l/6 coding
  l/4 component test and early system test
  l/4 system test, all components in hand.
* __기본적으로 test에 1/2을 할애해야한다__
* planning에 많은 시간을 할애한다.
* 상대적으로 예측하기 쉬운 시간인 coding은 1/6만 할애한다.
* 테스트는 거의 맨뒤에 하기때문에 테스트에 제대로 된 시간을 할애하지 못하면 마지막에 되어서야 딜레이를 인지할 수 있다. 

__Brooks's Law: Adding manpower to a late software project makes it later__

