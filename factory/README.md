# simple factory

1. 在程序中，需要创建的对象很多，导致对象的new操作多且杂时，需要使用简单工厂模式

2. 分离对象的创建和操作两部分,方便后期的程序扩展和维护

tips:
	简单工厂模式，在实际项目中使用的较少。


# factory method
工厂方法模式的意义是定义一个创建产品对象的工厂接口，将实际创建工作推迟到子类当中。核心工厂类不再负责产品的创建，这样核心类成为一个抽象工厂角色，仅负责具体工厂子类必须实现的接口，这样进一步抽象化的好处是使得工厂方法模式可以使系统在不修改具体工厂角色的情况下引进新的产品。

1. 在设计的初期，就考虑到产品在后期会进行扩展的情况下，可以使用工厂方法模式
2. 产品结构较复杂的情况下，可以使用工厂方法模式



# abstruct factory
abstruct factory 是工厂方法模式的扩展和延伸，但是抽象工厂模式，更有一般性和代表性；
它具有工厂方法具有的优点，也增加了解决实际问题的能力,解决工厂越建越多的问题。

1. 工厂方法模式适用于产品种类结构单一的场合，为一类产品提供创建的接口
2. 抽象工厂方法适用于产品种类结构多的场合，主要用于创建一组（有多个种类）相关的产品，为它们提供创建的接口，当具有多个抽象角色时，抽象工厂便可以派上用场。