# math-lib.jar

Build the library first with `mvn clean package` from the `math-lib` directory, then copy `math-lib/target/math-lib-1.0.jar` to this directory as `calculator-app/lib/math-lib.jar`.

Run the application from `calculator-app` with:

```text
mvn package
java -cp "target/classes;lib/math-lib.jar" com.codegym.Main
```
