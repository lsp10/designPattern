#开闭原则
一个软件实体 （类 模块 函数）应该对扩展开房，对修改关闭

用抽象构建框架  用实现扩展细节

提高软件的系统的可复用行和可维护性


面向抽象编程


接口作为契约  必须是稳定

#依赖倒置原则

高层接口不应该依赖底层模块  二者应该依赖其抽象

不应该依赖于底层细节  应该依赖其抽象

针对接口编程  不依赖于实现细节编程


减少类间的耦合性 提高系统的稳定性 提高代码的可读性和可维护性 降低修改程序所造成的风险


#@单一职责原则

不要存在多于一个导致类变更的原因



一个类实现两个需求或者功能  任何一个需求和功能的变动都会造成这个类的修改 


一个类/接口/方法只负责一项职责

职责划分  一个职责就是一组接口 一组接口实现一个完整的职责  职责 职责和需求（功能）对应关系 不确定

优点：降低类的复杂度，提高类的可读性 提高系统的可维护性，降低变更引起的风险