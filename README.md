# Intro

The goal of this homework is to become familiar with the JUnit 5 Jupiter API. JUnit is the backbone for this course for writing tests and automating tests. As with the prior homework, some steps require research to complete. This lack of specificity is intentional, and students are encouraged to use the Internet to fill in the missing gaps. 

After the homework, a student should be able to:

* Add the JUnit 5 dependency to a Maven project
* Write standard JUnit 5 tests
* Write parameterized and dynamic JUnit 5 tests
* Run JUnit 5 tests from the command line via `mvn` and the [Surefire Plugin](https://maven.apache.org/surefire/maven-surefire-plugin/) for reporting.
* Create patches with `git` and the `format-patch` command.

# Part I (40 points)

Complete Part I of the [JUnit 5 Jupiter API Tutorial](https://developer.ibm.com/tutorials/j-introducing-junit5-part1-jupiter-api/). Feel free to explore the Eclipse automation if so desired, but keep in mind that `mvn` is the primary interface for running tests and gathering reports.

The [HelloJUnit5](https://github.com/makotogo/HelloJUnit5) repository for the solution does include the solution file for reference. Resist looking at that file too quickly and rather try to figure out the annotations and tests from the tutorial and documentation where possible for better preparation on future homework. 

Complete this part of the homework by committing your solution in the [HelloJUnit5](https://github.com/makotogo/HelloJUnit5) repository, creating a patch for your solution using `git` and the `format-patch` command, and then adding the patch to the top-level directory of this repository. The patch should include only changes needed to complete the tutorial. Be sure to follow commit and other code documentation guidelines.

# Part II Maven Support of JUnit (10 points)

The [HelloJUnit5](https://github.com/makotogo/HelloJUnit5) project includes the needed support to run tests via `mvn` in the CLI. Look to that `pom.xml` for an example to how to add in support for running tests. That support is provided by the [Maven Surefire Plugin](https://maven.apache.org/surefire/maven-surefire-plugin/examples/junit-platform.html).

Complete this part of the homework by copying into this repository the code used to complete the previous **HW0 Tooling** homework with its `pom.xml` file, adding to that file anything needed for the [Maven Surefire Plugin](https://maven.apache.org/surefire/maven-surefire-plugin/examples/junit-platform.html) to build and run JUnit tests, and then adding in a single test to verify `mvn` finds, builds, runs, and reports the test. As a reminder, the code should be a few hundred lines with a fully documented class from the previous homework. 

# Part III  JUnit Tests (25 points)

Complete this part by writing tests for the code added in the previous part. The tests should cover the features of JUnit from Part I of the [JUnit 5 Jupiter API Tutorial](https://developer.ibm.com/tutorials/j-introducing-junit5-part1-jupiter-api/). Including life-cycle code, assumptions, and nested tests. The tests should be useful and related to the JavaDoc specification.

Students are expected to use descriptive naming conventions for test methods. There are a few key elements to [unit test names](https://qualitycoding.org/unit-test-names/). Pick a [convention](https://dzone.com/articles/7-popular-unit-test-naming) that works for you and stick with it.

# Grading Rubric

| Problem | Point Value | Your Score |
| ------- | ----------- | ---------- |
| Patch for [HelloJUnit5](https://github.com/makotogo/HelloJUnit5)  | 15 | |
| Solution for [HelloJUnit5](https://github.com/makotogo/HelloJUnit5) | 25 | |
| `pom.xml` runs tests as expected | 10 | |
| Meaningful tests that cover JUnit 5 core functionality (with life-cycle, assumption, and nested features) | 25 | |
| Descriptive test names with consistent naming convention | 10 | |
| Well-formed commits (logically grouped with correctly styled messages) | 15 | | 
| No warnings or errors in build | 10 | |
| No warnings or errors in CheckStyle | 10 | |



