
### 팩토리 메서드 패턴이란?
> 객체를 생성할 때 필요한 부분을 인터페이스화 해서 만들고, 어떤 클래스의 인스턴스를 만들지는 서브 클래스에서 결정하게 하는 패턴
> 추상 팩토리 클래스를 확장/상속받아 객체를 인스턴스화 하는 부분을 구현한다
> ex) PizzaStore -> NYPizzaStore / ChicagoPizzaStore (피자 생성 팩토리)


### 추상 팩토리 패턴이란?
> 구상 클래스에 의존하지 않고 서로 연관되거나 의존적인 객체로 이루어진 제품군을 생산하는 인터페이스를 제공하는 패턴
> 클라이언트는 추상 팩토리를 바탕으로 만들어지고, 실제 팩토리는 실행시에 결정된다
> ex) Pizza 객체를 생성할때 PizzaIngredientFactory를 활용하여 코드를 구현하고, 실제 Pizza 객체를 생성할때 NYPizzaIngredientFactory / ChicagoPizzaIngredientFactory 중 하나를 주입하여 객체를  생성


### 팩토리 패턴의 장점
- 객체를 인스턴스화 하는 부분을 분리하면서 구상 클래스의 코드를 간소화 할수 있다
- 객체를 인스턴스화 하는 부분은 팩토리 클래스에서 일괄적으로 수정이 가능하므로 확장/변경에 용이하다
- 해당 객체를 필요로 하는 여러개의 구현 클래스에서 팩토리클래스를 활용할 수 있다
- 팩토리를 정적 메소드로 선언하여, 클래스를 사용함과 동시에 바로 객체를 인스턴스화 할수도 있다 (정적 팩토리 (Static Factory))
 
![[Screen Shot 2023-04-23 at 3.14.08 PM.png]]