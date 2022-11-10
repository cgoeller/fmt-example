# fmt-example

Format check with maven -> No changes

```bash
mvn fmt:check
```

Format check with CLI -> Would change one file

```bash
java -jar lib/google-java-format-1.15.0-all-deps.jar -n src/main/java/org/example/Test.java
```

Format check with CLI  --skip-reflowing-long-strings -> No changes

```bash
java -jar lib/google-java-format-1.15.0-all-deps.jar -n --skip-reflowing-long-strings src/main/java/org/example/Test.java
```
