# 简单工厂模式
> 简单工厂模式(Simple Factory Pattern)：定义一个工厂类，它可以根据参数的不同返回不同类的实例，被创建的实例通常具有共同的父类。

由于在简单工厂模式中用于创建实例的方法是静态(static)方法，因此简单工厂模式又被称为静态工厂方法(Static Factory Method)模式，它属于**类创建型**模式。

简单工厂模式的要点在于：当用户需要什么时，只需要传入一个正确的参数就可以获取所需要的对象，而无须知道其创建细节。