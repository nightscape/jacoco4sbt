# jacoco4sbt - Code Coverage via JaCoCo from within SBT

This is an **[sbt](http://scala-sbt.org/)** plugin for code coverage analysis via **[JaCoCo](http://www.eclemma.org/jacoco/)**.

See the **[Wiki](https://github.com/sbt/jacoco4sbt/wiki)** for details.

## Change Log
* *2.1.5*
    * Added report summary to the build output
    * Added check for required coverage (fixing [#14](https://github.com/sbt/jacoco4sbt/issues/14))
    * Updated to JaCoCo version 0.7.0 (fixing [#18](https://github.com/sbt/jacoco4sbt/issues/18))

* *2.1.4*
    * Fixed a bad regression ([#8](https://github.com/sbt/jacoco4sbt/issues/8)) and added tests so that it doesn't happen again
    * Made code coverage work with forked tests ([#3](https://github.com/sbt/jacoco4sbt/issues/3) again,
      [#6](https://github.com/sbt/jacoco4sbt/issues/6) and
      [#9](https://github.com/sbt/jacoco4sbt/issues/9)) - this should make life
      a lot easier for [Play2](http://playframework.com) users

* *2.1.3*
    * Fixed [#3](https://github.com/sbt/jacoco4sbt/issues/3) (working directory in JaCoCo configuration)
    * Updated to latest JaCoCo version 0.6.4

* *2.1.2*
    * Added a Scala-specific report format (contributed by Jason)

* *2.1.1*

    * Updated for sbt 0.13.0 (final)

* *2.1.0*

    * Updated to work with sbt 0.13.x (contributed by Patrick)
    * Updated to latest JaCoCo version 0.6.3
    
* *2.0.0* (contributed by Joost)

    * Integration testing
    * (Optional) merging coverage of unit and integration tests
    * `clean` key for cleaning the JaCoCo output directory selectively
    
* *1.2.2* (contributed by Andreas)

    * Includes and excludes

## Contributors

Many thanks to
[Alexey Pismenskiy](https://github.com/apismensky),
[Andreas Flierl](https://bitbucket.org/asflierl),
[Jason Zaugg](https://github.com/retronym),
[Joost den Boer](https://bitbucket.org/diversit) and
[Patrick Mahoney](https://bitbucket.org/paddymahoney) for their awesome contributions!

## License

This program and the accompanying materials are made available under the terms of the **Eclipse Public License v1.0** which accompanies this distribution, and is available at http://www.eclipse.org/legal/epl-v10.html
