gradle-multi-project-checkstyle
==

A sample to enable gradle checkstyle plugin on multiple project.

Run
--

```
$ ./gradlew clean checkstyleMain

> Task :sample-project1:checkstyleMain
[ant:checkstyle] [ERROR] /Users/moznion/.ghq/github.com/moznion/gradle-multi-project-checkstyle/sample-project1/src/main/java/net/moznion/sample/project1/Project1.java:5: Line is longer than 100 characters (found 101). [LineLength]
Checkstyle rule violations were found. See the report at: file:///Users/moznion/.ghq/github.com/moznion/gradle-multi-project-checkstyle/sample-project1/build/reports/checkstyle/main.html

> Task :sample-project2:checkstyleMain
[ant:checkstyle] [ERROR] /Users/moznion/.ghq/github.com/moznion/gradle-multi-project-checkstyle/sample-project2/src/main/java/net/moznion/sample/project2/Project2.java:0: File does not end with a newline. [NewlineAtEndOfFile]
Checkstyle rule violations were found. See the report at: file:///Users/moznion/.ghq/github.com/moznion/gradle-multi-project-checkstyle/sample-project2/build/reports/checkstyle/main.html


BUILD SUCCESSFUL in 1s
7 actionable tasks: 6 executed, 1 up-to-date
```

License
--

Public domain

