# Debian

I [applied](https://nm.debian.org/person/mans0954/) to become a Debian Developer with uploading rights in 2016, successfully completing the process that year. Since then I have contributed/updated [over 60 packages](https://qa.debian.org/developer.php?email=mans0954@debian.org) for libraries and applications written in a variety of languages. Here are some examples:

- Rust
  - [elan](https://tracker.debian.org/pkg/elan) tool for managing installations of the Lean theorem prover
  - [rust-fslock](https://tracker.debian.org/pkg/rust-fslock) use files as locks
  - [rust-pipeline](https://tracker.debian.org/pkg/rust-pipeline) macro collection to pipe \|> your functions calls
- Python
  - [pympress](https://tracker.debian.org/pkg/pympress) simple and powerful dual-screen PDF reader
  - [mathlibtools](https://tracker.debian.org/pkg/mathlibtools) supporting tool for Lean mathlib
  - [sphinx-celery](https://tracker.debian.org/pkg/sphinx-celery) Sphinx Celery theme
  - [vine](https://tracker.debian.org/pkg/vine) a Python implementation of the promise pattern for asynchronous programming
  - [willow](https://tracker.debian.org/pkg/willow) Python image library combining Pillow, Wand and OpenCV (Python 3)
- Java
  - [commons-email](https://tracker.debian.org/pkg/commons-email) Apache Commons Java API for sending email
  - [csvjdbc](https://tracker.debian.org/pkg/csvjdbc) read-only JDBC driver that uses CSV or DBF files as database tables
  - [dropwizard-metrics](https://tracker.debian.org/pkg/dropwizard-metrics) capture JVM- and application-level metrics for Java applications
  - [mongo-java-driver](https://tracker.debian.org/pkg/mongo-java-driver) MongoDB Java Driver
  - [rabbitmq-java-client](https://tracker.debian.org/pkg/rabbitmq-java-client) RabbitMQ Java client
- Perl
  - [libamazon-s3-perl](https://tracker.debian.org/pkg/libamazon-s3-perl) portable client interface to Amazon Simple Storage System (S3)
  - [libapache-session-memcached-perl](https://tracker.debian.org/pkg/libapache-session-memcached-perl) Perl module for storing persistent data using memcached
  - [libmail-chimp3-perl](https://tracker.debian.org/pkg/libmail-chimp3-perl) interface to mailchimp.com's RESTful Web API v3
  - [libchi-driver-redis-perl](https://tracker.debian.org/pkg/libchi-driver-redis-perl) CHI driver that uses Redis to store the data
- R
  - [r-bioc-rbgl](https://tracker.debian.org/pkg/r-bioc-rbgl)

Some fixes/improvements to the Debian packages used for building packages:

- [855243](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=855243) Report and fix a bug where `lintian` was erroneously tagging python documentation packages as legacy python2
- [848337](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=848337) Report and fix `dh-make-perl` handling of version ambiguity
- [853045](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=853045) Fix broken link for `repack.sh` in `examples/repack.stub`
- [813307](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=813307) Add support for `smoke-cleanup` script
- [883239](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=883239) Report and fix interaction of `quilt` and `mh_patchpom` when applied to the same build
- [826410](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=826410) Add non-interactive mode to `mh_make`
- [878103](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=878103) Report and fix wrong package name for maven `-doc` packages
- [807686](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=807686) Fix an existing issue where files in the `debian` folder were inappropriately modified during builds
- [826430](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=826430) Report and fix `mh_make` is always verbose, even when `-v|--verbose` is not specified
- [820163](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=820163) Report and fix an exception when `mh_resolve_dependencies` is run with `--non-interactive`