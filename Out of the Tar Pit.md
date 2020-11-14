# Out of the Tar Pit

#### 1 Introduction

소프트웨어 개발에서 절망적인 상황이 오는 근원은 complexity이다

complexity의 원인은 크게 두 가지로 볼 수 있다.

1. code volume
2. flow of control

큰 프로젝트일수록 위의 두 가지에 대한 complecity는 걷잡을 수 없이 커진다. 이를 해결하기 위해 제시된 방법이 두 가지 있다.

1. OOP: state와 behavior를 묶어서 들고 다닌다
2. Functional programming: state와 side effect를 최대한 피하는 방법

이 두 가지 방법에서 장점들을 얻어 큰 스케일의 프로젝트에서 complexity를 줄일 수 있는 방법을 고안해볼 수 있을 것이다.

#### Complexity

소프트웨어 개발에서 생기는 거의 모든 문제는 시스템을 완벽히 이해하지 못해서 발생한다. 시스템을 완벽히 이해하는데 방해가 되는 주된 원인은 complexity이다. Dijkstra를 포함한 많은 튜링상 수상자들도 complexity에 대한 위험성을 경고했다. 하지만 simplicity를 이루는 것은 어렵다

#### Approaches to Understanding

