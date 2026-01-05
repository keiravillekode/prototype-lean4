# Tests

To run the tests, first make sure you have [Lake](https://github.com/leanprover/lake) installed (it comes with Lean 4).

From the exercise directory, run:

```bash
lake update
lake build
./.lake/build/bin/<ExerciseName>Test
```

For example, for the hello-world exercise:

```bash
lake update
lake build
./.lake/build/bin/HelloWorldTest
```
