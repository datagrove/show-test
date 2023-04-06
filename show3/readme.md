
# usage

show3 [dir]

if directory is not provided, then current directory is used.

directory must have a show3.json like this 

```
{
    "testRoot": "../RunTest/TestResults",
    "appRoot": "../results/dist"
}
```

appRoot is the build from "results" Typescript package
testRoot is the TestResults file that contains all the runs.

the paths are resolved relative to directory holding show3.json

