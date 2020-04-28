# JUnit example

This is a repository to demo JUnit 5 testing.

The steps I followed to set it up from scratch:
- installed Java, Git, and Gradle - see https://gradle.org/install/
- created a new directory "junitexample" and changed the directory to this new directory
- created a new Java project using gradle by "gradle init --type java-application --test-framework junit-jupiter"
- built the project using gradle wrapper by "./gradlew build" - see https://guides.gradle.org/building-java-applications/
- executed the project using gradle wrapper by "./gradlew run"
- executed the tests of the project using gradle wrapper by "./gradlew test"
- checked the results of the test in the local folder ./build/reports/tests/test/index.html
- created a git repository in the "junitexample"
- pushed the local repository into GitHub
- used a GitHub Action to do the build and test of the project in GitHub, automatically after each commit to the repository - see https://help.github.com/en/actions/language-and-framework-guides/building-and-testing-java-with-gradle) 
- the results of the build and tests (including failed ones) can be checked in the "Actions" tab in GitHub after each commit
