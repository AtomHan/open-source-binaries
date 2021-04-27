# Open Source binaries used at Atomico
A collection of Open Source binaries used at Atomico, compiled and built.

## Conjure

Conjure includes `conjure`, `conjure-python`, `conjure-typescript`, and `conjure-postman`. `conjure` is a build tool which generates API boilerplate using plugins, of which we use Python, Typescript, and Postman.

### Build

```shell
$ cd conjure && ./gradlew build ; cd ../
$ cd conjure-python && ./gradlew build ; cd ../
$ cd conjure-postman && ./gradlew build ; cd ../
$ cd conjure-typescript && yarn && yarn build ; cd ../
```
