## Apache Pekko HTTP quickstart in Scala

You can use [Giter8][g8] to create your own project from the quickstart.

Prerequisites:
- JDK 8
- sbt 1.4.x or higher

Open a console and run the following command to apply this template:
 ```
sbt new apache/incubabor-pekko-http-quickstart-scala.g8
 ```

You can also install [Giter8](http://www.foundweekends.org/giter8/setup.html) and install using:
 ```
g8 apache/incubabor-pekko-http-quickstart-scala.g8
 ```

This template will prompt for the following parameters. Press `Enter` if the default values suit you:
- `name`: Becomes the name of the project.
- `scala_version`: Specifies the Scala version for this project.
- `pekko_http_version`: Specifies which version of Pekko HTTP should be used for this project.
- `pekko_version`: Specifies which version of Pekko should be used for this project.
- `organization`: Specifies the organization for this project.

The template comes with the following sources:

* `QuickstartApp.scala` -- contains the main method which bootstraps the application 
* `UserRoutes.scala` -- Pekko HTTP `routes` defining exposed endpoints
* `UserRegistry.scala` -- the actor which handles the registration requests
* `JsonFormats.scala` -- converts the JSON data from requests into Scala types and from Scala types into JSON responses

Once inside the project folder use the following command to run the code:
```
sbt run
```

Template license
----------------
Written in 2017 by Lightbend, Inc.

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
