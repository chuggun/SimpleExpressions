## SimpleExpressions
#### Parsing and building Expression trees
* Optimizes Expressions
* Single responsibility

### SameMethodsCalls
* Eg.: (int x, int y) => F(x) > F(y) ? F(x) : (F(x) < F(2 * y) ? F(2 * y) : F(y))
* Substitutes repeating calls of expensive methods with condition expression wich places variable instead of method call and assign it during run-time only if neccessary
* Implements Visitor behavior while processing expression nodes