# artifact-versions

The projects listed are 'children' of maven-parent. This project manages the dependencies to keep everyone in sync.
Parent project: [maven-parent](https://github.com/imamchishty/maven-parent) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.maven/maven-parent/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.maven/maven-parent)

- version of spring-boot used is 1.4.2.RELEASE.
- version of spring-cloud-dependencies is Brixton.RELEASE.


## Projects

| Project                                                                                           | Description                                                                                 | Badges |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [spring-boost](https://github.com/imamchishty/spring-boost)                                    | Microservices code generator.                                                               |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.tool/spring-boost/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.tool/spring-boost)                                         [![Build Status](https://travis-ci.org/imamchishty/spring-boost.svg?branch=master "spring-boost")](https://travis-ci.org/imamchishty/spring-boost)                                                                       |
| 2. [trace-request-api](https://github.com/imamchishty/trace-request-api)                          | Traces requests API                                                                         |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-api/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-api)                             [![Build Status](https://travis-ci.org/imamchishty/trace-request-api.svg?branch=master "trace-request-api")](https://travis-ci.org/imamchishty/trace-request-api)                                                   |
| 3. [trace-request-filter](https://github.com/imamchishty/trace-request-filter)                    | Servlet filter which sets up necessary keys to enable request tracing.                      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-filter/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-filter)                       [![Build Status](https://travis-ci.org/imamchishty/trace-request-filter.svg?branch=master "filter-request-filter")](https://travis-ci.org/imamchishty/trace-request-filter)                                   |
| 4. [trace-request-jpa](https://github.com/imamchishty/trace-request-jpa)                          | Trace requests stored via JPA                                                               |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-jpa/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-jpa)                             [![Build Status](https://travis-ci.org/imamchishty/trace-request-jpa.svg?branch=master "filter-request-jpa")](https://travis-ci.org/imamchishty/trace-request-jpa)                                                  |
| 5. [trace-request-viewer](https://github.com/imamchishty/trace-request-viewer)                    | View requests via network style diagrams                                                    |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-viewer/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-viewer)                       [![Build Status](https://travis-ci.org/imamchishty/trace-request-viewer.svg?branch=master "filter-request-viewer")](https://travis-ci.org/imamchishty/trace-request-viewer)                                      |
| 6. [trace-request-graylog](https://github.com/imamchishty/trace-request-graylog)                  | Interacts with Graylog to get view trace requests.                                          |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-graylog/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-graylog)                     [![Build Status](https://travis-ci.org/imamchishty/trace-request-graylog.svg?branch=master "filter-request-graylog")](https://travis-ci.org/imamchishty/trace-request-graylog)                                  |
| 7. [exception-controller-spring](https://github.com/imamchishty/exception-controller-spring)      | Handles exceptions that occur in spring applications.                                       |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-controller-spring/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-controller-spring) [![Build Status](https://travis-ci.org/imamchishty/exception-controller-spring.svg?branch=master "exception-controller-spring")](https://travis-ci.org/imamchishty/exception-controller-spring)           |
| 8. [exception-core](https://github.com/imamchishty/exception-core)                                | Re-usable, generic and rich exceptions/models.                                              |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-core/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-core)                           [![Build Status](https://travis-ci.org/imamchishty/exception-core.svg?branch=master "Travis CI")](https://travis-ci.org/imamchishty/exception-core)                                                                   |
| 9. [requestbody-cache-filter](https://github.com/imamchishty/requestbody-cache-filter)            | Wraps HTTP requests, allowing access to the request body via a ThreadLocal.                 |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-filter/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-filter)                           [![Build Status](https://travis-ci.org/imamchishty/requestbody-cache-filter.svg?branch=master "requestbody-cache-filter")](https://travis-ci.org/imamchishty/requestbody-cache-filter)                       |
|10. [requestbody-cache-interceptor](https://github.com/imamchishty/requestbody-cache-interceptor)  | Exception interceptor that sets the postBody property on the exception model.               |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-interceptor/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-interceptor)                 [![Build Status](https://travis-ci.org/imamchishty/requestbody-cache-interceptor.svg?branch=master "requestbody-cache-filter")](https://travis-ci.org/imamchishty/requestbody-cache-interceptor)        |
|11. [thread-context-handler](https://github.com/imamchishty/thread-context-handler)                | Sets the thread context for the duration of a thread call.                                  |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-handler/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-handler)                 [![Build Status](https://travis-ci.org/imamchishty/thread-context-handler.svg?branch=master "thread-context-aspect")](https://travis-ci.org/imamchishty/thread-context-handler)                               |
|12. [thread-context-aspect](https://github.com/imamchishty/thread-context-aspect)                  | Uses spring aspects to set thread context.                                                  |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-aspect/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-aspect)                   [![Build Status](https://travis-ci.org/imamchishty/thread-context-aspect.svg?branch=master "JMC threads list")](https://travis-ci.org/imamchishty/thread-context-aspect)                                       |
|13. [threadlocal-string-utility](https://github.com/imamchishty/threadlocal-string-utility)        | ThreadLocal utilities.                                                                      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/threadlocal-string-utility/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/threadlocal-string-utility)         [![Build Status](https://travis-ci.org/imamchishty/threadlocal-string-utility.svg?branch=master "threadlocal-string-utility")](https://travis-ci.org/imamchishty/threadlocal-string-utility)               |
|14. [spring-actuator](https://github.com/imamchishty/spring-actuator)                              | Custom actuator endpoints for seeing exceptions count, trace requests, exceptions etc.      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.spring/spring-actuator/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.spring/spring-actuator)                               [![Build Status](https://travis-ci.org/imamchishty/spring-actuator.svg?branch=master "Travis CI")](https://travis-ci.org/imamchishty/spring-actuator)                                                                |

## Dependency Tree
Internal (shedhack) dependencies between projects.

__thread-context-handler__
  - none

__exception-core__
  - none

__trace-request-api__
  - none

__thread-context-aspect__
  - thread-context-handler

__exception-controller-spring__
  - exception-core
  - trace-request-api

__spring-actuator__
  - exception-controller-spring
  - trace-request-api

__trace-request-filter__
  - trace-request-api
  - spring-actuator (test)
  - exception-controller-spring (test)

__requestbody-cache-filter__
  - none

__requestbody-cache-interceptor__
  - exception-controller-spring
  - cache-filter
  - exception-core

__spring-boost__
  - everything

