# 516test
Test GithubActions

A simple Java project that runs with Gradle.

Test classes included in the project, each containing at least one test. JUnit5 is used for testing and integrated via the Gradle configuration.

A clean project structure pushed to GitHub, containing only the necessary files.

GitHub Actions setup with two jobs:

1. A build job that compiles the project.

2. A test job that runs test classes.

A dynamic test job configuration where:

1. All test classes are run on the main branch.

2. Only one test class is executed on all other branches.

A separate branch(test-branch) is used to validate this behavior.
