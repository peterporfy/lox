## Compile and run

### Lox
1. `javac com/craftinginterpreters/lox/*.java`
2. `java com.craftinginterpreters.lox.Lox`

### Run examples

`java com.craftinginterpreters.lox.Lox ../01.lox`

### Tools

#### Generate AST Classes

1. `javac com/craftinginterpreters/tool/GenerateAst.java`
2. `java com.craftinginterpreters.tool.GenerateAst com/craftinginterpreters/lox`

`javac com/craftinginterpreters/tool/GenerateAst.java && java com.craftinginterpreters.tool.GenerateAst com/craftinginterpreters/lox`
