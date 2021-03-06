# Spring Batch Examples

Collection of Spring Batch Examples.

## Why ?

Spring Batch Examples exist, because i needed a central place to store the source code of my own examples collection. Instead of the usual private Subversion repository i wanted to give Github a try.

To further simplify it, all work is under Apache 2.0 license (see [license wiki page][1] for more details), fork it, use it, bend it and if you find a bug or improvement, do not hesitate to push a patch.

## What ?

The Examples are described in the [wiki][2]

## General Informations

All Spring Batch Examples:

* are individual maven projects, the pom.xml in the root directory is only for a convenient _build all_ feature
* are tested with:
  * Spring Batch 2.1.8.RELEASE
  * Spring Framework 3.0.6.RELEASE
* are provided "as is", no guarantees :-)
* work with [in-memory database][database], but not with in-memory jobrepository, since the [MapJobRepository is threadsafe][3] i could use it, but why break a standard configuration ?
* for the general Maven, Spring and Database setup see the [project setup][project-setup] wiki page.

## License

Apache 2.0 see [license wiki page][1] for more details

[1]: https://github.com/langmi/spring-batch-examples/wiki/License---Apache-2.0
[2]: https://github.com/langmi/spring-batch-examples/wiki
[3]: https://jira.springsource.org/browse/BATCH-1541
[project-setup]: https://github.com/langmi/spring-batch-examples/wiki/project-setup
[database]:http://hsqldb.org/doc/2.0/guide/running-chapt.html#running_inprocess-sect