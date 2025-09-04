# Open Closed Principle

## Principle Description

The principle declares a `Null Constraint` rule for the Object Orientired Programming paradigm. It prohibits the modification of parent elements (base classes, classes with direct dependencies - such as a private `enum` property in C# - or entire assemblies) on `addition`.

## Example Description

The provided example illustrates a violation of this rule in `Mistake` and demonstrates the severity of the problem in `Escalation`, which arises from a direct dependency on an `enum` within the `Monitor` class of the `MonitorAssembly`. A concrete solution is presented, which involves separating assemblies, introducing Dependency Injection, and employing the Strategy pattern in `Refactoring`. This approach resolves the issue without sacrificing any other advantages.

The final result is in `Soliton`.

## Explore

`Initial`: [Diff](https://github.com/VladisS-Vostok2000/BestPractices/compare/master...OpenClosedPrinciple_Initial) | [Source](https://github.com/VladisS-Vostok2000/BestPractices/tree/OpenClosedPrinciple_Initial/BestPractices/OOP/SOLID/Open%20Closed%20Principle/1\)%20Initial)

`Mistake`: [Source](https://github.com/VladisS-Vostok2000/BestPractices/tree/OpenClosedPrinciple_Mistake/BestPractices/OOP/SOLID/Open%20Closed%20Principle) | [Diff](https://github.com/VladisS-Vostok2000/BestPractices/compare/master...OpenClosedPrinciple_Initial)

`Escalation`: [OpenClosedPrinciple_Mistake -> master](https://github.com/VladisS-Vostok2000/BestPractices/compare/master...OpenClosedPrinciple_Escalation)

`Refactoring`: [OpenClosedPrinciple_Mistake -> master](https://github.com/VladisS-Vostok2000/BestPractices/compare/master...OpenClosedPrinciple_Refactoring)

`Solution`: [OpenClosedPrinciple_Mistake -> master](https://github.com/VladisS-Vostok2000/BestPractices/compare/master...OpenClosedPrinciple_Solution)
