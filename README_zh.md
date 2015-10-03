pyhton-设计模式
===============

收集用Pyhton写的设计模式和风格.

当有一个新的成品时, 更新这个文件并执行`append_output.sh` 
(举个栗子: ./append_output.sh borg.py), 以保证底部的输入结果是最新的.

已有的模式:

| 模式 | 说明 |
| -------| ----------- |
| [三层架构](3-tier.py) | 数据<->业务逻辑<->描述 分离 (严格的关系) |
| [mvc](mvc.py) | 模型<->视图<->控制器 (非严格的关系) |
| [borg](borg.py) | 在实例中共享状态的一种单例模式(id不一样, state一样) |
| [抽象工厂模式](abstract_factory.lua) | 用一个通用的方法, 根据特定的工厂类来创建一个类的实例 |
| [工厂模式](factory_method.lua) | 根据专门的函数或者方法, 创建一个类的实例 |
| [原型](prototype.py) | 用一个工厂类, 通过复制原型, 得到一个新的实例(如果实例存在的话) |
| [adapter](adapter.py) | adapt one interface to another using a whitelist |
| [bridge](bridge.py) | a client-provider middleman to soften interface changes |
| [builder](builder.py) | call many little discrete methods rather than having a huge number of constructor parameters |
| [catalog](catalog.py) | general methods will call different specialized methods based on construction parameter |
| [chain](chain.py) | apply a chain of successive handlers to try and process the data |
| [command](command.py) | bundle a command and arguments to call later |
| [composite](composite.py) | encapsulate and provide access to a number of different objects |
| [decorator](decorator.py) | wrap functionality with other functionality in order to affect outputs |
| [facade](facade.py) | use one class as an API to a number of others |
| [flyweight](flyweight.py) | transparently reuse existing instances of objects with similar/identical state |
| [graph_search](graph_search.py) | (graphing algorithms, not design patterns) |
| [mediator](mediator.py) | an object that knows how to connect other objects and act as a proxy |
| [memento](memento.py) | generate an opaque token that can be used to go back to a previous state |
| [observer](observer.py) | provide a callback for notification of events/changes to data |
| [pool](pool.py) | preinstantiate and maintain a group of instances of the same type |
| [proxy](proxy.py) | an object funnels operations to something else |
| [publish_subscribe](publish_subscribe.py) | a source syndicates events/data to 0+ registered listeners |
| [state](state.py) | logic is org'd into a discrete number of potential states and the next state that can be transitioned to |
| [strategy](strategy.py) | selectable operations over the same data |
| [template](template.py) | an object imposes a structure but takes pluggable components |
| [visitor](visitor.py) | invoke a callback for all items of a collection |
| [chaining_method](chaining_method.py) | continue callback next object method |
