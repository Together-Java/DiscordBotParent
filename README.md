# DiscordBotParent
The maven parent for the Together Java discord bots.

## Usage

In your own pom, add the jitpack repository
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>
```

And then add this repository as the parent:
```xml
<parent>
  <groupId>com.github.Together-Java</groupId>
  <artifactId>DiscordBotParent</artifactId>
  <version>-SNAPSHOT</version> <!-- You can also use another version -->
</parent>
```

You can find all versions on [jitpack](https://jitpack.io/#Together-Java/DiscordBotParent).


## Code style
This project uses the [google java styleguide](https://google.github.io/styleguide/javaguide.html).
You can find a formatter profile for your IDE [here](https://github.com/google/styleguide).
