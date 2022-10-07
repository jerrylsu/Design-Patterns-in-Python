Design-Patterns-in-Python
===============

Python设计模式集合

Current Patterns
----------------

__创建型模式__:

| Pattern | Description |
|:-------:| ----------- |
|  |  |

__结构型模式__:

| 模式名称 | 描述 |
|:-------:| ----------- |
| [外观模式](patterns/structural/facade.py) | 使用一个类作为其他一些类的统一的API接口 |
| [组合模式](patterns/structural/composite.py) | 让客户端统一对待单个对象和组合 |
| [装饰器模式](patterns/structural/decorator.py) | 动态的给一个对象添加一些额外的职责 |
| [桥接模式](patterns/structural/bridge.py) | 将抽象部分与其实现部分分离，使它们都可以独立的变化 |
| [适配器模式](patterns/structural/adapter.py) | 将一个接口转换为客户希望的另一个接口，使得原本不兼容的类可以一起工作 |
| [代理模式](structural/proxy.ipynb) | 为其他对象提供一种代理，以控制这个对象的访问 |


__行为型模式__:

| 模式名称 | 描述 |
|:-------:| ----------- |
| [策略模式](behavioral/strategy.ipynb) | 定义一系列算法，每个独立封装，并使它们可相互替换。策略让算法独立于使用它的客户端而变化 |
| [状态模式](behavioral/state.ipynb) | 允许一个对象在其内部状态改变时改变它的行为，对象看起来像是修改了它的类 |
| [观察者模式](behavioral/observer.ipynb) | 定义对象间的一种一对多的依赖关系，当一个对象的状态发生改变时，所以依赖于它的对象都得到通知并被自动更新 |
| 中介者模式](behavioral/mediator.ipynb) | 用一个中介对象来封装一系列的对象交互。中介者使各个对象不需要显示地相互引用，从而使其解耦，而且可以独立地改变它们之间的交互 |

https://refactoring.guru/design-patterns

https://github.com/faif/python-patterns
