Spring

Spring Framework

```
자바엔터프라이즈 개발을 빠르고 편리하게 만들어주는 프레임워크
java Application 개발에 필요한 하부구조를 포괄적으로 제공하기에 Application 개발에 집중하여 생산성이 증가
```



Container

```
instance의 life Cycle을 관리하는 역할 
Ex) Bean Container
```



IoC(제어의 역전)

```
객체의 생성부터 소멸까지 Life Cycle을 개발자가 담당하지 않고 다른 대상에게 위임하는 방식 
Ex) 
	특정 객체를 Bean Container에 등록하도록 설정 -> 
	개발자는 객채의 생성 없이 Bean Container에서 주입받아 사용
```



DI(의존성 주입)

```
Spring Framework에서 지원하는 IoC의 형태
Ex) 
	특정 객체를 Bean Container에 등록하도록 설정 -> 
	개발자는 객채의 생성 없이 Bean Container에서 주입받아 사용
의존성: 현재의 객체가 다른 객채와 상호작용하고있다면 객채의존

```

디컴파일