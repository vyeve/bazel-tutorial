# Commands:
build particular target

```bash
bazel build src:HelloWorld
```

run target

```bash
bazel run src:HelloWorld
```

test

```bash
bazel test src:LibraryExampleTest
```

build all:
```bash
bazel build src:all
```
or 

```bash
bazel build src/...
```
or 

```bash
bazel build ...
```

cleanup
```bash
bazel clean
```