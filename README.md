|  **Build Status**                |
|:---------------------------------|
|  [![][actions-img]][actions-url] |

```
~/.julia/dev/TestJiveIssue54 $ cd test
~/.julia/dev/TestJiveIssue54/test $ julia runtests.jl
1/1 kk.jl
a: Test Failed at /Users/username/.julia/dev/TestJiveIssue54/test/kk.jl:4
  Expression: 1 == 2
   Evaluated: 1 == 2
Stacktrace:
 [1] macro expansion
   @ /Applications/Julia-1.7.2.app/Contents/Resources/julia/share/julia/stdlib/v1.7/Test/src/Test.jl:445 [inlined]
 [2] macro expansion
   @ ~/.julia/dev/TestJiveIssue54/test/kk.jl:4 [inlined]
 [3] macro expansion
   @ /Applications/Julia-1.7.2.app/Contents/Resources/julia/share/julia/stdlib/v1.7/Test/src/Test.jl:1283 [inlined]
 [4] top-level scope
   @ ~/.julia/dev/TestJiveIssue54/test/kk.jl:4
b: Test Failed at /Users/username/.julia/dev/TestJiveIssue54/test/kk.jl:7
  Expression: 1 == 2
   Evaluated: 1 == 2
Stacktrace:
 [1] macro expansion
   @ /Applications/Julia-1.7.2.app/Contents/Resources/julia/share/julia/stdlib/v1.7/Test/src/Test.jl:445 [inlined]
 [2] macro expansion
   @ ~/.julia/dev/TestJiveIssue54/test/kk.jl:7 [inlined]
 [3] macro expansion
   @ /Applications/Julia-1.7.2.app/Contents/Resources/julia/share/julia/stdlib/v1.7/Test/src/Test.jl:1283 [inlined]
 [4] top-level scope
   @ ~/.julia/dev/TestJiveIssue54/test/kk.jl:7
    Fail: 2  (compile: 1.28, elapsed: 1.60 seconds)
❗️  Test run finished with 2 test failures.  (compile: 1.28, elapsed: 1.60 seconds)
ERROR: LoadError: Test run finished with errors.
in expression starting at /Users/username/.julia/dev/TestJiveIssue54/test/runtests.jl:2
```

[actions-img]: https://github.com/wookay/TestJiveIssue54.jl/workflows/CI/badge.svg
[actions-url]: https://github.com/wookay/TestJiveIssue54.jl/actions
