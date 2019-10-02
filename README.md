# Create Gists

All builds were performed with a clean environment, i.e. after a `rm -rf build owasp-dependency-check/database`.

## Corretto 8
```

```bash
./gradlew dependencyCheckAnalyze --stacktrace | tee corretto-8-stacktrace.gist
./gradlew dependencyCheckAnalyze --debug | tee corretto-8-debug.gist
```

started with

```text
openjdk version "1.8.0_222"
OpenJDK Runtime Environment Corretto-8.222.10.1 (build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM Corretto-8.222.10.1 (build 25.222-b10, mixed mode)
```

finished with status code `0` (`gradlew`).

## Corretto 11

```bash
./gradlew dependencyCheckAnalyze --stacktrace | tee corretto-11-stacktrace.gist
./gradlew dependencyCheckAnalyze --debug | tee corretto-11-debug.gist
```

started with

```text
openjdk version "11.0.4" 2019-07-16 LTS
OpenJDK Runtime Environment Corretto-11.0.4.11.1 (build 11.0.4+11-LTS)
OpenJDK 64-Bit Server VM Corretto-11.0.4.11.1 (build 11.0.4+11-LTS, mixed mode)
```

finished with status code `1` (`gradlew`).

## Zulu 11

```bash
./gradlew dependencyCheckAnalyze --stacktrace | tee zulu-11-stacktrace.gist
./gradlew dependencyCheckAnalyze --debug | tee zulu-11-debug.gist
```

started with

```text
openjdk version "11.0.4" 2019-07-16 LTS
OpenJDK Runtime Environment Zulu11.33+15-CA (build 11.0.4+11-LTS)
OpenJDK 64-Bit Server VM Zulu11.33+15-CA (build 11.0.4+11-LTS, mixed mode)
```

finished with status code `1` (`gradlew`).
