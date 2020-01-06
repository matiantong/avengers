模板方法模式：
1.定义：
复用算法的结构和步骤，父类包含执行步骤的聚合方法，而每个具体步骤的实现可以在子类完成

2.适用性：
1)一次性实现一个算法的不变部分，并且将可变的行为留给子类完成
2)各子类公共的行为应该被提取出来并集中到一个公共父类中以避免代码的重复

3.模式的组成：
父类角色:提供包含步骤的模板方法
子类角色:提供实现具体的步骤

4.UML图，时序图