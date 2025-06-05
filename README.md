# marioGame

This repository contains a simple Mario-style game written in Java using the ACM graphics library.

## Building

The project depends on the ACM Java libraries. Download `acm.jar` from the [Stanford ACM website](https://cs108.github.io/accumulation/acm.jar) or another source and place it in a `lib` directory.
All Java sources reside in the `starter` folder. Compile them with:

```bash
javac -cp lib/acm.jar starter/*.java
```

## Running

Run the game with:

```bash
java -cp lib/acm.jar:. starter.Main
```

The `Main` class launches the `Mario` game window.
