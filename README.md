# Create Gists

## Corretto 8
```

```bash
gradle dependencyCheckAnalyze --stacktrace | tee corretto-8-stacktrace.gist
gradle dependencyCheckAnalyze --debug | tee corretto-8-debug.gist
```

tested with

```text
openjdk version "1.8.0_222"
OpenJDK Runtime Environment Corretto-8.222.10.1 (build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM Corretto-8.222.10.1 (build 25.222-b10, mixed mode)
```

## Corretto 11

```bash
gradle dependencyCheckAnalyze --stacktrace | tee corretto-11-stacktrace.gist
gradle dependencyCheckAnalyze --debug | tee corretto-11-debug.gist
```

tested with

```text
openjdk version "11.0.4" 2019-07-16 LTS
OpenJDK Runtime Environment Corretto-11.0.4.11.1 (build 11.0.4+11-LTS)
OpenJDK 64-Bit Server VM Corretto-11.0.4.11.1 (build 11.0.4+11-LTS, mixed mode)
```
