## Micronaut 2.3.2 Documentation

- [User Guide](https://docs.micronaut.io/2.3.2/guide/index.html)
- [API Reference](https://docs.micronaut.io/2.3.2/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/2.3.2/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

## Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)

## Building a Native Image Without Using Docker
Installing GraalVM 21.0.0 with SDKman
```shell
$ sdk install java 21.0.0.r8-grl # or 21.0.0.r11-grl if you want to use JDK 11
$ sdk use java 21.0.0.r8-grl
```

Installing native-image tool
```shell
$ gu install native-image
```

Creating native image with Maven
```shell
$ ./mvnw package -Dpackaging=native-image
```