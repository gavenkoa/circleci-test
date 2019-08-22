
# Testing CircleCI

https://circleci.com/integrations/

https://circleci.com/docs/2.0/deployment-integrations/

# Publishing Gradle

* [Publishing Gradle](https://docs.gradle.org/current/userguide/publishing_overview.html)

```
gradle publish
> Task :generatePomFileForLibPublication
> Task :compileJava UP-TO-DATE
> Task :processResources NO-SOURCE
> Task :classes UP-TO-DATE
> Task :jar UP-TO-DATE
> Task :publishLibPublicationToMvnRepository
> Task :publish
```

There is special task: `publishToMavenLocal`.