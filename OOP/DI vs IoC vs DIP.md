# DI vs IoC vs DIP

### 🎊 시작하기 전에..

DI, IoC, DIP가 비슷비슷한건줄 알고, 어떤 부분이 다른지 몰랐다면 잘 찾아온것이라고 생각한다.

이 글에서는 각 각의 정의, 내용보다는 차이점을 중점적으로 다룰 것이다.

### 😵 DI, IoC

스프링을 공부하는 사람이라면 DI과 IoC가 거의 동등한 것이라고 생각할 수도 있다. 왜냐하면 스프링 3대 요소를 이야기할 때 **IoC/DI**라고 많이 이야기 하기 때문이다. 하지만 DI는 IoC를 **구현하는 방법** 중 하나이다. 하지만 역으로 IoC를 사용하지 않는 DI또한 가능하다. 이를 Pure DI라고 부른다.

### 👩🏻‍🤝‍👩🏻 DI, DIP

DI과 DIP는 이름이 쌍둥이 처럼 비슷한데, 꽤나 차이점이 있다.

DIP는 "**상위모듈**이 **하위모듈**을 **의존하면 안되며**(의존을 뒤집기 위해 **interface**를 활용해 **추상화**를 한다.), 추상화는 **구체적인 사항**에 **의존**해서는 안된다" 로 정의 되어있다.

하지만 DI는 간단하다. 추상화를 해치지 않고 **의존성을 인수로 넘겨**주는 방법이다.

따라서 DI는 DIP의 사용이 **필수적이지 않다**. 또한 DI는 DIP를 구현하는 방법 중 하나라고 볼 수 있으며 의존성을 외부에서 주입을 받더라도 구체 클래스에 의존하고 있다면 DI는 사용하고 있지만, DIP는 지켜지지 않는다고 볼 수 있다.

### 💡 결론

DI, IoC, DIP는 헷갈리는 개념이 맞다. 하지만 그냥 대략적인 겉모습만 보는 것 보다는 각 각의 개념을 이해하는 것이 중요하다고 생각한다.

또한 초보 개발자인 내가 쓴 글이므로 틀린 내용이 있을 수도 있다. 하나의 Refrence만 보고 판단하지 말자! 글에 오류가 있으면 언제든 Issue는 환영입니다✨

