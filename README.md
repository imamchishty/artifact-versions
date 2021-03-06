# Project Versions

The projects listed are 'children' of maven-parent. This project manages the dependencies to keep everyone in sync.
Parent project: [maven-parent](https://github.com/imamchishty/maven-parent) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.maven/maven-parent/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.maven/maven-parent)

- version of spring-boot used is 1.5.4.RELEASE.
- version of spring-cloud-dependencies is Dalston.SR1.

## Projects

| Project                                                                                           | Description                                                                                 | Badges |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [exception-core](https://github.com/imamchishty/exception-core)                                | Re-usable, generic and rich exceptions/models.                                              |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-core/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-core)                           [![Build Status](https://travis-ci.org/imamchishty/exception-core.svg?branch=master "Travis CI")](https://travis-ci.org/imamchishty/exception-core)                                                                   |
| 2. [trace-request-api](https://github.com/imamchishty/trace-request-api)                          | Traces requests API                                                                         |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-api/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-api)                             [![Build Status](https://travis-ci.org/imamchishty/trace-request-api.svg?branch=master "trace-request-api")](https://travis-ci.org/imamchishty/trace-request-api)                                                   |
| 3. [thread-context-handler](https://github.com/imamchishty/thread-context-handler)                | Sets the thread context for the duration of a thread call.                                  |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-handler/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-handler)                 [![Build Status](https://travis-ci.org/imamchishty/thread-context-handler.svg?branch=master "thread-context-aspect")](https://travis-ci.org/imamchishty/thread-context-handler)                               |
| 4. [thread-context-aspect](https://github.com/imamchishty/thread-context-aspect)                  | Uses spring aspects to set thread context.                                                  |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-aspect/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/thread-context-aspect)                   [![Build Status](https://travis-ci.org/imamchishty/thread-context-aspect.svg?branch=master "JMC threads list")](https://travis-ci.org/imamchishty/thread-context-aspect)                                       |
| 5. [exception-controller-spring](https://github.com/imamchishty/exception-controller-spring)      | Handles exceptions that occur in spring applications.                                       |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-controller-spring/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.exception/exception-controller-spring) [![Build Status](https://travis-ci.org/imamchishty/exception-controller-spring.svg?branch=master "exception-controller-spring")](https://travis-ci.org/imamchishty/exception-controller-spring)           |
| 6. [spring-actuator](https://github.com/imamchishty/spring-actuator)                              | Custom actuator endpoints for seeing exceptions count, trace requests, exceptions etc.      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.spring/spring-actuator/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.spring/spring-actuator)                               [![Build Status](https://travis-ci.org/imamchishty/spring-actuator.svg?branch=master "Travis CI")](https://travis-ci.org/imamchishty/spring-actuator)                                                                |
| 7. [trace-request-filter](https://github.com/imamchishty/trace-request-filter)                    | Servlet filter which sets up necessary keys to enable request tracing.                      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-filter/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.trace/trace-request-filter)                       [![Build Status](https://travis-ci.org/imamchishty/trace-request-filter.svg?branch=master "filter-request-filter")](https://travis-ci.org/imamchishty/trace-request-filter)                                   |
| 8. [requestbody-cache-filter](https://github.com/imamchishty/requestbody-cache-filter)            | Wraps HTTP requests, allowing access to the request body via a ThreadLocal.                 |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-filter/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-filter)                           [![Build Status](https://travis-ci.org/imamchishty/requestbody-cache-filter.svg?branch=master "requestbody-cache-filter")](https://travis-ci.org/imamchishty/requestbody-cache-filter)                       |
| 9. [requestbody-cache-interceptor](https://github.com/imamchishty/requestbody-cache-interceptor)  | Exception interceptor that sets the postBody property on the exception model.               |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-interceptor/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.requestbody/cache-interceptor)                 [![Build Status](https://travis-ci.org/imamchishty/requestbody-cache-interceptor.svg?branch=master "requestbody-cache-filter")](https://travis-ci.org/imamchishty/requestbody-cache-interceptor)        |
| 10. [spring-boost](https://github.com/imamchishty/spring-boost)                                    | Microservices code generator.                                                               |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.tool/spring-boost/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.tool/spring-boost)                                         [![Build Status](https://travis-ci.org/imamchishty/spring-boost.svg?branch=master "spring-boost")](https://travis-ci.org/imamchishty/spring-boost)                                                                       |
|11. [threadlocal-string-utility](https://github.com/imamchishty/threadlocal-string-utility)        | ThreadLocal utilities.                                                                      |[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/threadlocal-string-utility/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/com.shedhack.thread/threadlocal-string-utility)         [![Build Status](https://travis-ci.org/imamchishty/threadlocal-string-utility.svg?branch=master "threadlocal-string-utility")](https://travis-ci.org/imamchishty/threadlocal-string-utility)               |


## Dependency Tree

![alt tag](https://github.com/imamchishty/artifact-versions/blob/master/shedhack-dependency-tree.jpg)

Internal (shedhack) dependencies between projects (release order in brackets).

__1. exception-core__
  - none

__2. trace-request-api__
  - none
    
__3. thread-context-handler__
  - none

__4. thread-context-aspect__
  - thread-context-handler

__5. exception-controller-spring__
  - exception-core
  - trace-request-api

__6. spring-actuator__
  - exception-controller-spring
  - trace-request-api

__7. trace-request-filter__
  - trace-request-api
  - spring-actuator (test)
  - exception-controller-spring (test)

__8. requestbody-cache-filter__
  - none

__9. requestbody-cache-interceptor__
  - exception-controller-spring
  - cache-filter
  - exception-core

__10.spring-boost__
  - everything

