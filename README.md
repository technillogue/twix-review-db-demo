## A demo for setting up Heroku-style review apps with Fly and GHA.

When you open a PR in this repo, it's automatically served at review-{branch name}.fly.dev. Pushing more commits redeploys. Closing or merging the PR destroys the app.

This demo uses Kotlin and grpc to run a simple grpc server with Exposed and Liquibase for databases

To run:

`./gradlew run`

To test:

`./gradlew test`

Format:

`./gradlew spotlessApply`
