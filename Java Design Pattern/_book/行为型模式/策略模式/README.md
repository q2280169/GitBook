# 策略模式
策略模式中，定义一些独立的类来封装不同的算法，每一个类封装一种具体的算法，在这里每一个封装算法的类都可以称之为一种策略(Strategy)，为了保证这些策略在使用时具有一致性，一般会提供一个抽象的策略类来做规则的定义，而每种算法则对应于一个具体策略类。

>策略模式(Strategy Pattern)：定义一系列算法类，将每一个算法封装起来，并让它们可以相互替换，策略模式让算法独立于使用它的客户而变化。

策略模式也称为政策(Policy)模式，它是一种**对象行为型**模式。



