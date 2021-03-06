CI Sentry
=========

[![Build Status](https://snap-ci.com/sghill/ci-sentry/branch/master/build_image)](https://snap-ci.com/sghill/ci-sentry/branch/master)

CI Sentry guards build data.

CI is sometimes configured to keep a small number of builds for space reasons.
With a long history of data, it becomes easier to see if builds are
improving with changes to practice and process.

Interesting Things
------------------

* dropwizard-configuration for validated, overridable, yaml-based configuration
* argparse4j for command line argument parsing
* Injected, tested, non-static SLF4J loggers
* Parallel processing with Fork/Join framework
* Square's Dagger for compile-time validated dependency injection
* Square's Retrofit/OkHttp for binding to the Jenkins API
* Ektorp for saving to CouchDb

License
-------
```
Copyright 2015 Steve Hill

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
