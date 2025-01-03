[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.jooby/jooby/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.jooby/jooby)
[![Javadoc](https://javadoc.io/badge/io.jooby/jooby.svg)](https://javadoc.io/doc/io.jooby/jooby/latest)
[![Github](https://github.com/jooby-project/jooby/workflows/Full%20Build/badge.svg)](https://github.com/jooby-project/jooby/actions)
[![Discord](https://img.shields.io/discord/1225457509909922015?label=discord)](https://discord.gg/nmfJmmrq)
[![Become a Patreon](https://img.shields.io/badge/patreon-donate-orange.svg)](https://patreon.com/edgarespina)
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg?logo=paypal&style=flat-square)](https://paypal.me/edgarespina)

# &infin; do more, more easily

[Jooby](https://jooby.io) is a modern, performant and easy to use web framework for Java and Kotlin built on top of your
favorite web server.

Java:

```java
import static io.jooby.Jooby.runApp;

public class App {

  public static void main(final String[] args) {
    runApp(args, app -> {
      app.get("/", ctx -> "Welcome to Jooby!");
    });
  }
}

```

Kotlin:

```kotlin
import io.jooby.runApp

fun main(args: Array<String>) {
  runApp(args) {
    get ("/") {
      "Welcome to Jooby!"
    }
  }
}

```

documentation
=====

Documentation is available at [https://jooby.io](https://jooby.io)

help
=====

[Discord](https://discord.gg/nmfJmmrq)

donate & support
=====
- [Sponsor](https://github.com/sponsors/jknack)
- [Paypal](https://www.paypal.com/paypalme2/edgarespina)
- [Patreon](https://www.patreon.com/edgarespina)
- [support@jooby.io](mailto:support@jooby.io?Subject=Jooby%20Support)

| Logo | Sponsor |
|------|---------|
| <img src="https://github.com/user-attachments/assets/4a3f519e-0b2e-4bb4-b2eb-624b05720e31" alt="Premium Minds" width="32" height="32"> | [@premium-minds](https://github.com/premium-minds) |
| <img src="https://github.com/user-attachments/assets/51073649-6cba-4e7b-8eee-8c05f4b9648e" alt="David" width="32" height="32"> | [@tipsy](https://github.com/tipsy)|
| <img src="https://github.com/user-attachments/assets/ac8c311c-1873-4024-9670-0e7599b1026b" alt="Mercedes Benz" width="32" height="32"> | [@mercedes-benz](https://github.com/mercedes-benz)|

Previous version
=====

- v2: [Documentation](https://jooby.io/v2) and [source code](https://github.com/jooby-project/jooby/tree/2.x)
- v1: [Documentation](https://jooby.io/v1) and [source code](https://github.com/jooby-project/jooby/tree/1.x)

author
=====

 [Edgar Espina](https://twitter.com/edgarespina)

license
=====

[Apache License 2](http://www.apache.org/licenses/LICENSE-2.0.html)
