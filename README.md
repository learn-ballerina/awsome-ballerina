# Awsome Ballerina
A list of awesome Ballerina resources. Once you have an overview of the language, here are resources you can use to learn more.

- [Awsome Ballerina](#awsome-ballerina)
  - [General](#general)
  - [Language Concepts](#language-concepts)
    - [General Language](#general-language)
      - [Error handling](#error-handling)
      - [JSON](#json)
      - [XML](#xml)
      - [Immutability](#immutability)
      - [Binding Patterns](#binding-patterns)
      - [Functions](#functions)
      - [Type conversions](#type-conversions)
      - [Language integrated queries](#language-integrated-queries)
      - [Listners](#listners)
      - [Other Data types](#other-data-types)
      - [Statements](#statements)
    - [Data structures and algorithms](#data-structures-and-algorithms)
    - [Compiler](#compiler)
    - [Concurrency](#concurrency)
    - [Java interoperability](#java-interoperability)
    - [Transactions](#transactions)
    - [Streams](#streams)
    - [Workflows](#workflows)
  - [Standard and Extended library](#standard-and-extended-library)
    - [HTTP](#http)
    - [HTTP2](#http2)
    - [GraphQL](#graphql)
    - [WebSocket](#websocket)
    - [Pub/Sub](#pubsub)
    - [SerDes](#serdes)
    - [Email](#email)
    - [File](#file)
    - [Websub and webhooks](#websub-and-webhooks)
    - [gRPC](#grpc)
    - [Database](#database)
    - [Kafka](#kafka)
    - [Time](#time)
    - [Cache](#cache)
    - [FTP](#ftp)
    - [SOAP](#soap)
    - [Encoding/Decoding](#encodingdecoding)
    - [CSV I/O](#csv-io)
  - [Security](#security)
    - [Ballerina security overview](#ballerina-security-overview)
    - [Microservices Security](#microservices-security)
    - [OAuth](#oauth)
    - [OAuth2](#oauth2)
    - [JWT](#jwt)
    - [OSCP](#oscp)
    - [TLS/SSL](#tlsssl)
    - [OpenID](#openid)
    - [Taint Checking (Deprecated)](#taint-checking-deprecated)
  - [Cloud](#cloud)
    - [Kubernetes/C2C](#kubernetesc2c)
    - [AWS Step Functions](#aws-step-functions)
    - [AWS Lambda](#aws-lambda)
    - [Azure functions](#azure-functions)
    - [Azure services](#azure-services)
    - [OpenShift](#openshift)
  - [Observability](#observability)
  - [Tooling](#tooling)
    - [OpenAPI](#openapi)
    - [AsyncAPI](#asyncapi)
    - [Ballerina CLI tool](#ballerina-cli-tool)
    - [SemVer validator](#semver-validator)
    - [Strand dump tool](#strand-dump-tool)
    - [Ballerina shell](#ballerina-shell)
    - [Homebrew](#homebrew)
  - [Editor](#editor)
    - [VS Code](#vs-code)
    - [Language Server](#language-server)
    - [IntelliJIDEA](#intellijidea)
    - [Composer (Deprecated)](#composer-deprecated)
  - [Testing](#testing)
  - [Logging](#logging)
  - [Configuration management](#configuration-management)
  - [Package management](#package-management)
  - [Building and installing Ballerina](#building-and-installing-ballerina)
  - [Ballerina Connectors](#ballerina-connectors)
  - [CI/CD](#cicd)
  - [Comparisons with other languages](#comparisons-with-other-languages)
  - [Usecases](#usecases)
  - [Integration and design Patterns](#integration-and-design-patterns)


## General

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Seven reasons to try out Ballerina](https://medium.com/ballerina-techblog/seven-reasons-to-try-out-ballerina-f3934c4c53f0)  | [shazni nazeer](https://medium.com/@mshazninazeer)  |2022-06-28|
|  InfoQ | [Ballerina: a Data-Oriented Programming Language](https://www.infoq.com/articles/ballerina-data-oriented-language/)  | [Yehonathan Sharvit](https://www.infoq.com/profile/Yehonathan-Sharvit/)  |2022-05-10|
|  Blog | [Ballerina: Integration Programming Language](https://medium.com/ballerina-techblog/ballerina-integration-programming-language-5d8e1b52e582)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-05-08  |
|  InfoQ | [Ballerina Swan Lake: 10 Compelling Language Characteristics for Cloud Native Programming](https://www.infoq.com/articles/ballerina-cloud-native-programming/)  | [Dakshitha Ratnayake](https://www.infoq.com/profile/Dakshitha-Ratnayake/)  |2021-09-15|
|  InfoQ | [Ballerina - An Open Source JVM Language and Platform for Cloud-Era Application Programmers](https://www.infoq.com/news/2020/01/wso2-releases-ballerina-1-1/)  | [Michael Redlich](https://www.infoq.com/profile/Michael-Redlich/)  |2020-01-29|
|  Blog | [Ballerina — Part 1: Concept](https://medium.com/ballerina-techblog/ballerina-part-1-concept-ec889b064de5)  | [James Clark](https://medium.com/@jclark_th)  |2019-09-12|
|  Blog | [Ballerina — Part 0: Context](https://medium.com/ballerina-techblog/ballerina-programming-language-1821e55baa85)  | [James Clark](https://medium.com/@jclark_th)  |2019-09-11|
|  Blog | [Ballerina: Why a New Programming Language](https://medium.com/ballerina-techblog/ballerina-why-a-new-programming-language-8cedbc782caa)  | [Shafreen Anfar](https://medium.com/@anfar.shafreen)  |2019-06-02|
|  Blog | [The top ten articles about Ballerina](https://lafernando.medium.com/the-top-ten-articles-about-ballerina-9c7be2acd261)  | [Anjana Fernando](https://medium.com/@lafernando)  |2018-09-05|
|  InfoQ | [Ballerina Microservices Programming Language: Introducing the Latest Release and "Ballerina Central"](https://www.infoq.com/articles/ballerina-microservices-language-part-1/)  | [Tyler Jewell](https://www.infoq.com/profile/Tyler-Jewell/)  |2018-05-29|
|  Blog | [BallerinaLang — Visual Programming and its Role in Service Integration](https://medium.com/@nadeeshaangunasinghe/ballerinalang-visual-programming-and-its-role-in-service-integration-91dda041fa15)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2017-08-27|
|  DZone | [Ballerina Dances Onto the Integration Stage](https://dzone.com/articles/ballerina-dances-onto-the-integration-stage)  | [Steve Gertiser](https://dzone.com/users/294952/javerdog@gmail.com.html)  |2017-07-27|
|  DZone | [Getting Started With Ballerina in 10 Minutes](https://dzone.com/articles/getting-started-with-ballerina-in-10-minutes)  | [Chanaka Fernando](https://dzone.com/users/2726658/chanakaudaya.html)  |2017-03-08|
|  DZone | [Making Integration Great Again](https://dzone.com/articles/how-to-make-integration-great-again)  | [Chanaka Fernando](https://dzone.com/users/2726658/chanakaudaya.html)  |2017-02-22|


## Language Concepts

### General Language

#### Error handling

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [[Ballerina] Error Handling — Part II](https://medium.com/ballerina-techblog/ballerina-error-handling-part-ii-159fbe74c146)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2019-12-24|
|  Blog | [[Ballerina] Error Handling — Part I](https://medium.com/ballerina-techblog/ballerina-error-handling-part-i-d581f65c0f8d)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2019-09-28  |

#### JSON

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [[Ballerina] Working with JSON — JSON to record conversion](https://medium.com/ballerina-techblog/ballerina-working-with-json-part-i-json-to-record-conversion-1e810b0a30f0)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2021-01-27|
|  Blog | [[Ballerina] Converting CSV to JSON](https://medium.com/ballerina-techblog/ballerina-converting-csv-to-json-22954918731)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2019-09-25  |
|  Blog | [Ballerina’s JSON type and lax static typing](https://medium.com/ballerina-techblog/ballerinas-json-type-and-lax-static-typing-3b952f6add01)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2019-09-13  |

#### XML

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [XML Processing Made Easy with Ballerina](https://dzone.com/articles/xml-processing-made-easy-with-ballerina)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-10-26|

#### Immutability 

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Immutability in Ballerina — Part I](https://medium.com/ballerina-techblog/immutability-in-ballerina-part-i-e6c607ced627)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2021-09-26|
|  Blog | [Immutable Values in Ballerina](https://medium.com/ballerina-techblog/immutable-values-in-ballerina-99f7f6232c72)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-12-13|

#### Binding Patterns

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Using Binding Patterns in Ballerina](https://dzone.com/articles/utilising-binding-patterns-in-ballerina)  | [Suleka Helmini](https://dzone.com/users/3667460/suleka96.html)  |2021-10-20|
|  DZone | [Binding Patterns in Ballerina](https://dzone.com/articles/binding-patterns-in-ballerina)  | [Suleka Helmini](https://dzone.com/users/3667460/suleka96.html)  |2021-10-19|

#### Functions

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Hello, World! Program in Ballerina](https://ayesh9303.medium.com/hello-world-program-in-ballerina-9678d2c284fa)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-05-09|
|  Blog | [Defaultable Parameters in Ballerina](https://medium.com/@lanka.vitharana/defaultable-parameters-in-ballerina-c181f537bc76)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2019-12-10  |
|  Blog | [Changing the “main” function](https://medium.com/ballerina-techblog/changing-the-main-function-4f60b319b6e4)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-10-04|


#### Type conversions

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [[Ballerina] Casting and Conversions — Part II — Stamping, Cloning and Converting](https://medium.com/ballerina-techblog/ballerina-casting-and-conversions-part-ii-stamping-cloning-and-converting-785e2ac167aa)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-12-11|
|  Blog | [[Ballerina] Casting and Conversions — Part I](https://maryamzi.medium.com/ballerina-casting-and-conversions-part-i-678792616cac)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-12-11|

#### Language integrated queries

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Efficient Joins with Ballerina Query Expressions](https://stackoverflow.com/collectives/wso2/articles/72806142/efficient-joins-with-ballerina-query-expressions)  | [Lasini Liyanage](https://stackoverflow.com/users/6570185/lasinicl)  |2022-06-29|
|  SO | [Query Expressions in Ballerina](https://stackoverflow.com/collectives/wso2/articles/72666852/query-expressions-in-ballerina)  | [Lasini Liyanage](https://stackoverflow.com/users/6570185/lasinicl)  |2022-06-22|
|  DZone | [Language Integrated Queries In Ballerina](https://dzone.com/articles/language-integrated-queries-in-ballerina)  | [Mohanadarshan Vivekanandalingam](https://dzone.com/users/4448705/mohanadarshan.html)  |2020-10-16|

#### Listners

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [[Attaching multiple services to the same listener in Ballerina](https://stackoverflow.com/collectives/wso2/articles/73277198/attaching-multiple-services-to-the-same-listener-in-ballerina)  | [Maryam Ziyad](https://stackoverflow.com/users/8887779/maryamzi)  |2022-08-09|

#### Other Data types

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina: Behavioral Types](https://blog.devgenius.io/ballerina-behavioral-types-bac73fe48a87)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-06-26|
|  Blog | [Ballerina: Data Types](https://ayesh9303.medium.com/ballerina-data-types-c3d5b4166cd8)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-05-09|
|  DZone | [Working With Data in Microservices](https://dzone.com/articles/working-with-data-in-microservices)  | [Lakmal Warusawithana](https://dzone.com/users/1141403/lakwarus.html)  |2020-04-14|
|  Blog | [Introduction to Ballerina Tables](https://medium.com/ballerina-techblog/introduction-to-ballerina-tables-205286a53752)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2018-09-23|
|  Blog | [Ballerina Object type and all you need to know](https://medium.com/ballerina-techblog/ballerina-object-type-and-all-you-need-to-know-930c42a7bf95)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2018-07-12  |
|  Blog | [Coding in meaningful way(Identifier literal support in ballerina ).](https://medium.com/@lanka.vitharana/identifier-literals-in-ballerina-makes-it-possible-to-have-spaces-in-identifiers-83336ecb693e)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2017-05-14  |
|  Blog | [Any type support in ballerina](https://medium.com/ballerina-techblog/any-type-support-in-ballerina-d9651ac53695)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2017-05-04  |

#### Statements

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Control Structures in Ballerina](https://ayesh9303.medium.com/control-structures-in-ballerina-d13c288fe301)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-01-04|

### Data structures and algorithms

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Collections: Tables](https://medium.com/ballerina-techblog/ballerina-collections-tables-f4a0711085f7)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2022-03-10|
|  Blog | [Ballerina Collections: Arrays & Maps](https://ayesh9303.medium.com/ballerina-collections-arrays-maps-9df17186b5a1)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2022-02-22|
|  Blog | [Basic Algorithms using Ballerina](https://medium.com/ballerina-techblog/basic-algorithms-using-ballerina-908fe8d320a5)  | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2022-02-20|
|  Blog | [Parallel Merge Sort with Ballerina](https://medium.com/ballerina-techblog/parallel-merge-sort-with-ballerina-fe6f419a308c)  | [Kishanthan Thangarajah](https://medium.com/@kishanthan)  |2018-11-11|

### Compiler

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Compilation Process](https://medium.com/ballerina-techblog/ballerina-compilation-process-aba37aa05374)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2019-12-17  |

### Concurrency

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Concurrency-Safe Execution Using Ballerina Isolation](https://dzone.com/articles/concurrency-safe-execution-ballerina-isolation)  | [Hinduja Balasubramaniyam](https://dzone.com/users/4633935/hinduja-b.html)  |2021-11-07|
|  Blog | [Ballerina Concurrency Model and Non-Blocking I/O](https://medium.com/ballerina-techblog/ballerina-concurrency-model-and-non-blocking-i-o-14c6bed595f4)  | [Anjana Fernando](https://medium.com/@lafernando)  |2021-02-22|
|  Blog | [Unveiling Ballerina Non-Blocking Architecture](https://medium.com/ballerina-techblog/unveiling-ballerina-non-blocking-architecture-3ab9866b39ed)  | [Vinod Kavinda](https://medium.com/@vinok88)  |2019-09-30  |
|  Blog | [Concurrency in Ballerina (Workers, Send, Receive, Flush, Wait …)](https://medium.com/ballerina-techblog/concurrancy-in-ballerina-workers-send-receive-flush-wait-569585f3ec50)  | [Vinod Kavinda](https://medium.com/@vinok88)  |2018-12-28  |
|  Blog | [Concurrency control in Ballerina (Field based locking)](https://medium.com/ballerina-techblog/concurrency-control-in-ballerina-field-based-locking-979bcdeb0bd5)  | [Vinod Kavinda](https://medium.com/@vinok88)  |2018 Dev 16  |
|  Blog | [Ballerina: Concurrency Done Right!](https://lafernando.medium.com/ballerina-concurrency-done-right-fa0afa350cb0)  | [Anjana Fernando](https://medium.com/@lafernando)  |2018-04-29|
|  Blog | [Concurrency Management in Ballerina (Lock statement)](https://medium.com/ballerina-techblog/concurrency-management-in-ballerina-lock-statement-efc47194d68a)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2018-04-28  |
|  Blog | [A Glimpse Inside Workers In Ballerina](https://medium.com/ballerina-techblog/a-glimpse-of-workers-in-ballerina-b30e32b41fa)  | [Natasha Wijesekare](https://medium.com/@nwijesekare)  |2018-12-25|
|  Blog | [Ballerina Channels](https://medium.com/ballerina-techblog/ballerina-channels-af4908538411)  | [Vinod Kavinda](https://medium.com/@vinok88)  |2018-10-09  |

### Java interoperability

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Interop and all you need to know](https://medium.com/@lanka.vitharana/ballerina-interop-and-all-you-need-to-know-81eef0931120)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2019-12-10  |

### Transactions

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Practical Transaction Handling in Microservice Architecture](https://dzone.com/articles/practical-transaction-handling-in-microservice-arc)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-12-01|

### Streams

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Lets write a window in Ballerina](https://medium.com/ballerina-techblog/lets-write-a-window-in-ballerina-2bfa40cfb7fc)  | [Gimantha Bandara](https://medium.com/@gimanthabandara)  |2019-03-11|
|  Blog | [Writing Ballerina Streaming Extensions](https://medium.com/ballerina-techblog/writing-ballerina-streaming-extensions-304c9f815861)  | [Grainier Perera](https://medium.com/@grainier)  |2019-03-11|

### Workflows
|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Simple Long Running Workflows with Ballerina](https://lafernando.medium.com/simple-long-running-workflows-with-ballerina-e3617631b81c)  | [Anjana Fernando](https://medium.com/@lafernando)  |2018-10-08|

## Standard and Extended library 

### HTTP

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Single Liner Payload Read…](https://medium.com/ballerina-techblog/single-liner-payload-read-85a16e3265fc)  | [Chamil Elladeniya](https://medium.com/@chamilelle)  |2021-06-06|
|  Blog | [HTTP Deep-Dive with Ballerina: Services](https://medium.com/ballerina-techblog/http-deep-dive-with-ballerina-services-7a6e69af2fbb)  | [Anjana Fernando](https://medium.com/@lafernando)  |2021-01-28|
|  DZone | [HTTP Deep-Dive With Ballerina: Client Communication](https://dzone.com/articles/http-deep-dive-with-ballerina-client-communication)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-12-17|
|  Blog | [Request dispatching patterns of Ballerina HTTP service](https://medium.com/ballerina-techblog/request-dispatching-patterns-of-ballerina-http-service-16357509d7a9)  | [Chamil Elladeniya](https://medium.com/@chamilelle)  |2019-09-19|
|  Blog | [Implementing a Simple Web Server using Ballerina](https://medium.com/ballerina-techblog/implementing-a-simple-web-server-using-ballerina-8d180e041536)  | [Hemika Kodikara](https://medium.com/@hemika.kodikara)  |2019-04-24|
|  Blog | [Eat My Dust! : Making of Ballerina’s Lightning Fast HTTP Transport](https://medium.com/@anfar.shafreen/eat-my-dust-making-of-ballerinas-lightning-fast-http-transport-ce6b1955ff91)  | [Shafreen Anfar](https://medium.com/@anfar.shafreen)  |2019-02-23|
|  Blog | [Intercepting HTTP requests in Ballerina](https://medium.com/ballerina-techblog/intercepting-http-requests-in-ballerina-aaa37beee1c)  | [Vinod Kavinda](https://medium.com/@vinok88)  |2018-11-13  |
|  Blog | [HTTP Caching in Ballerina - Part I](https://medium.com/@pubuduf/http-caching-in-ballerina-part-i-d2446ceb7db2)  | [Pubudu Fernando](https://medium.com/@pubuduf)  |2018-11-13  |

### HTTP2

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [How to play with HTTP/2 in Ballerina](https://medium.com/ballerina-techblog/how-to-work-with-http-2-in-ballerina-6bdbafb100c1)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2018-08-01  |

### GraphQL

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [GraphQL Subscriptions with Ballerina: A Step-By-Step Guide](https://medium.com/ballerina-techblog/graphql-subscriptions-with-ballerina-a-step-by-step-guide-5a75e3a12813)  | [Nuvindu Dias](https://medium.com/@nuvidu-18)  |2022-09-30|
|  Blog | [REST is History, Let’s Do GraphQL (with Ballerina)](https://medium.com/ballerina-techblog/rest-is-history-lets-do-graphql-with-ballerina-dce7510b61e8)  | [Thisaru Guruge](https://medium.com/@thisaru)  |2021-06-29|
|  Blog | [Introduction to GraphQL with Ballerina](https://medium.com/ballerina-techblog/graphql-made-easy-with-ballerina-5ca04d9536d0)  | [Anjana Fernando](https://medium.com/@lafernando)  |2021-02-09|


### WebSocket

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina WebSocket Service — The Anatomy](https://medium.com/ballerina-techblog/understanding-ballerina-websocket-service-4babb128f9a5)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2022-05-24 |
|  Blog | [Real-Time Stock Data Updates with WebSockets using Ballerina](https://medium.com/ballerina-techblog/real-time-stock-data-updates-with-websockets-using-ballerina-7ecb2d4dcfa9) | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2021-11-26 |
|  Blog | [Go Real-Time with Ballerina WebSockets](https://medium.com/ballerina-techblog/go-real-time-with-ballerina-websockets-58c40ac11d6)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2021-07-28 |
|  Video | [How to use WebSocket with Ballerina](https://youtu.be/UT51LC-bKgs)  | [Anjana Fernando](https://www.youtube.com/@lafernando)  |2020-11-05 |


### Pub/Sub

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [An Introduction to Pub/Sub in Ballerina](https://medium.com/ballerina-techblog/an-introduction-to-pub-sub-in-ballerina-e259b38307fb)  | [Nuvindu Dias](https://medium.com/@nuvidu-18)  |2022-09-30|


### SerDes

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Serialization and Deserialization with Ballerina SerDes module](https://medium.com/ballerina-techblog/serialization-and-deserialization-with-ballerina-serdes-module-b05e1e44d9f2) | [Mohomed Sabthar](https://medium.com/@sabthar)  |2022-08-16|

### Email

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Sending Emails with Ballerina](https://medium.com/ballerina-techblog/sending-emails-with-ballerina-191f8edeade8)  | [Shammi Kolonne](https://shammi0107.medium.com/)  |2022-08-16|

### File

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [How to download a large file using Ballerina](https://medium.com/@anupama.pathirage/how-to-download-a-large-file-using-ballerina-ec735309cb)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2022-06-22|
|  Blog | [How to download a file from URL using Ballerina](https://medium.com/@anupama.pathirage/how-to-download-a-file-from-url-using-ballerina-adca85735d55)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2022-06-20|

### Websub and webhooks

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Event-Driven APIs With Webhook and WebSub](https://medium.com/ballerina-techblog/event-driven-apis-with-webhook-and-websub-83b0834f08f3)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2021-11-08|
|  Blog | [[Ballerina] Registering a GitHub Webhook](https://medium.com/ballerina-techblog/ballerina-registering-a-github-webhook-1bd7a75cb32d)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-08-12 |
|  Blog | [[Ballerina] Event Notification via Webhooks](https://medium.com/ballerina-techblog/ballerina-event-notification-via-webhooks-bc7cc63f4b6e)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-07-21|

### gRPC

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Introduction to gRPC on Ballerina](https://medium.com/ballerina-techblog/introduction-to-grpc-on-ballerina-7819d98c4e2b)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2021-08-28|
|  DZone | [gRPC Basics: Why, When, and How?](https://dzone.com/articles/grpc-basics-why-when-and-how)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-07-24|
|  Blog | [Ballerina + gRPC](https://medium.com/ballerina-techblog/ballerina-grpc-9ee601c0968d)  | [Buddhi Kothalawala](https://medium.com/@buddhikothalawala)  |2020-04-07|

### Database

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Avoiding SQL Injection in Ballerina](hhttps://stackoverflow.com/collectives/wso2/articles/74602985/avoiding-sql-injection-in-ballerina)  | [Niveathika](https://stackoverflow.com/users/4027644/niveathika)  |2022-12-08| 
|  SO | [Interacting with a RDBMS using Ballerina](https://stackoverflow.com/collectives/wso2/articles/73795707/interacting-with-a-rdbms-using-ballerina)  | [Extremum](https://stackoverflow.com/users/2782646/extremum)  |2022-09-21|
|  SO | [Create a Data API with Ballerina and H2](https://stackoverflow.com/collectives/wso2/articles/72986543/create-a-data-api-with-ballerina-and-h2)  | [Dakshitha Ratnayake](https://stackoverflow.com/users/14645116/dakshitha-ratnayake)  |2022-07-17|
|  Blog | [Interacting with a RDBMS using Ballerina](https://mshazninazeer.medium.com/interacting-with-a-rdbms-using-ballerina-63edd89f79f6)  | [shazni nazeer](https://medium.com/@mshazninazeer)  |2022-09-21|
|  Blog | [SQL Injection — Introduction with Ballerina](https://medium.com/mycodeideas/sql-injection-introduction-with-ballerina-30b75abad8fe)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2020-08-03| 
|  Blog | [Interact with an Oracle database with Ballerina](https://medium.com/ballerina-techblog/interact-with-an-oracle-database-with-ballerina-ed84052713e8)  | [Manuri Perera](https://medium.com/@Manuri)  |2019-03-30|
|  Blog | [Containerized Ballerina service with a MongoDB data backend](https://medium.com/ballerina-techblog/containerized-ballerina-service-with-a-mongodb-data-backend-c5c0a867720e)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-11-25|
|  Blog | [How to connect to MongoDB Atlas with Ballerina](https://medium.com/ballerina-techblog/lets-connect-to-mongodb-atlas-with-ballerina-8fd46f168fb6)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-11-02|
|  Blog | [[Ballerina] Database connection pool exhausted?](https://medium.com/ballerina-techblog/ballerina-database-connection-pool-exhausted-738e5cfba4be)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-10-27|
|  Blog | [Data Access for Microservices](https://medium.com/ballerina-techblog/data-services-with-ballerina-70ba17bd5c80)  | [Anjana Fernando](https://medium.com/@lafernando)  |2018-08-21|
|  Blog | [XA transaction example with Ballerina — Oracle and MySQL as resource managers](https://medium.com/ballerina-techblog/xa-transaction-example-with-ballerina-df9221bcf664)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-13|
|  Blog | [Using a Ballerina table as a proxy to an actual database table](https://medium.com/@Manuri/using-a-ballerina-table-as-a-proxy-to-an-actual-database-table-48024792a434)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-12|
|  Blog | [Interact with a Postgresql database with Ballerina!](https://medium.com/ballerina-techblog/interact-with-a-postgresql-database-with-ballerina-301fd5bc2c01)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-12|
|  Blog | [Oracle RefCursor Example with Ballerina](https://medium.com/ballerina-techblog/oracle-refcursor-example-with-ballerina-1448cc3aef11)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-11|
|  Blog | [Oracle PL/SQL example with Ballerina](https://medium.com/ballerina-techblog/oracle-pl-sql-example-with-ballerina-b978eb8a768)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-09|
|  Blog | [“select” iterable operation on Ballerina tables](https://medium.com/ballerina-techblog/example-of-select-iterable-operation-on-ballerina-tables-91f46d408597)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-08-13|
|  Blog | [Redis Caching example with Ballerina !](https://medium.com/ballerina-techblog/redis-caching-example-with-ballerina-16f875f31faf)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2018-07-21|
|  Blog | [Connect to your data with Ballerina](https://medium.com/ballerina-techblog/connect-to-your-data-with-ballerina-902b2bad872d)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-07-08|
|  Blog | [Insert batch of data to DB using Ballerina](https://medium.com/ballerina-techblog/insert-batch-of-data-using-ballerina-4c1a7d72c35e)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2018-06-09|
|  Blog | [Talking to a database with Ballerina](https://medium.com/@Manuri/talking-to-a-database-with-ballerina-f551e0a3fe77)  | [Manuri Perera](https://medium.com/@Manuri)  |2018-04-30|
|  Blog | [Ballerina JDBC Client — Performing DB Operations](https://medium.com/ballerina-techblog/ballerina-sql-connector-performing-db-operations-8e555e3688be)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2017-12-02|
|  Blog | [Ballerina JDBC Client— Connecting to DB](https://medium.com/ballerina-techblog/ballerina-sql-connector-connecting-to-db-ee31a81c8df6)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2017-11-26|
|  Blog | [Data Integration with Ballerina](https://medium.com/ballerina-techblog/data-integration-with-ballerina-c5bcf6de49b3)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2017-11-25|

### Kafka

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Kafka Serialization with Avro](https://medium.com/ballerina-techblog/ballerina-kafka-serialization-with-avro-83126a7df9a1)  | [Thisaru Guruge](https://medium.com/@thisaru)  |2020-05-05|
|  Blog | [Building a Simple Review Filtering System Using Ballerina Kafka](https://medium.com/ballerina-techblog/building-a-simple-review-filtering-system-using-ballerina-kafka-42cee518ecef) | [Thisaru Guruge](https://medium.com/@thisaru)  |2019-02-12|
|  Blog | [Getting Started with Ballerina Kafka](https://medium.com/ballerina-techblog/get-along-with-ballerina-kafka-754c28de685c)  | [Thisaru Guruge](https://medium.com/@thisaru)  |2019-02-05|

### Time

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [A guide for Date/Time conversion in Ballerina Language](https://stackoverflow.com/collectives/wso2/articles/73277351/a-guide-for-date-time-conversion-in-ballerina-language)  | [sahanhe](https://stackoverflow.com/users/6795551/sahanhe)  |2022-08-08|

### Cache

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Redesigning of Ballerina Cache](https://medium.com/ballerina-techblog/redesigning-of-ballerina-cache-a2cf59b0fee1)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2020-06-27|

### FTP

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina FTP client](https://bhashineen.medium.com/ballerina-ftp-client-1226a48f0b71)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2021-07-14 |

### SOAP

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina SOAP Connector](https://bhashineen.medium.com/ballerina-soap-connector-3974b6efaf2b)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2019-04-17 |

### Encoding/Decoding

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Different Types of Encoding/Decoding with Ballerina](https://stackoverflow.com/collectives/wso2/articles/73147933/different-types-of-encoding-decoding-with-ballerina)  | [Chanaka Lakmal](https://stackoverflow.com/users/4314651/ldclakmal)  |2022-07-28 |

### CSV I/O

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Upload CSV files to Ballerina Service](https://stackoverflow.com/collectives/wso2/articles/73574768/upload-csv-files-to-ballerina-service)  | [Anupama Pathirage](https://stackoverflow.com/users/1308004/anupama-pathirage)  |2022-09-01 |

## Security

### Ballerina security overview

|Type   | Title  |Author  |
|---|---|---|
|  Website | [Ballerina security](https://ldclakmal.me/ballerina-security/)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |

### Microservices Security

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [HTTP Security in Ballerina](https://medium.com/@ldclakmal/http-security-in-ballerina-b0b5927866f9)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2021-08-10  |
|  Blog | [Microservices Security with Ballerina](https://medium.com/ballerina-techblog/microservices-security-with-ballerina-e9d430f05373)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2021-08-02|
|  Blog | [Securely invoking a Client Endpoint in Ballerina](https://medium.com/ballerina-techblog/microservices-security-with-ballerina-e9d430f05373)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2018-05-21|

### OAuth

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Authenticate A Shopify App Using OAuth — The Ballerina Way](https://medium.com/ballerina-techblog/authenticate-a-shopify-app-using-oauth-the-ballerina-way-f827ab99f576)  | [Thisaru Guruge](https://medium.com/@thisaru)  |2020-06-02|

### OAuth2

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Securing Microservices with OAuth2](https://medium.com/ballerina-techblog/securing-microservices-with-oauth2-475a72bd5ddd)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2022-02-28|

### JWT

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Securing Microservices with JWT](https://medium.com/ballerina-techblog/securing-microservices-with-jwt-a16b738b110f) | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2021-10-21|

### OSCP

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [CRL, OCSP and OCSP stapling validation with Ballerina](https://bhashineen.medium.com/crl-ocsp-and-ocsp-stapling-validation-with-ballerina-31f8b58fd5cf)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2018-09-15 |
|  Blog | [[Ballerina] Enable OCSP stapling in Ballerina](https://bhashineen.medium.com/ballerina-enable-ocsp-stapling-in-ballerina-3cb404b8c415)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2018-08-13 |

### TLS/SSL

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Configuring Transport Layer Security (TLS/SSL) in Ballerina Client](https://bhashineen.medium.com/configuring-transport-layer-security-tls-ssl-in-ballerina-client-65cdf4baca2f)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2019-10-02 |
|  Blog | [Configure Ciphers and SSL protocols in Ballerina](https://bhashineen.medium.com/configure-ciphers-and-ssl-protocols-in-ballerina-51053004fff)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2017-10-30 |
|  Blog | [SSL Mutual Authentication with Ballerina](https://bhashineen.medium.com/ssl-mutual-authentication-with-ballerina-653aa50f15f)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2017-10-28 |

### OpenID

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Secure a Ballerina REST API with OpenID Connect using Asgardeo-Part 2](https://stackoverflow.com/collectives/wso2/articles/73748619/secure-a-ballerina-rest-api-with-openid-connect-using-asgardeo-part-2)  | [Dakshitha Ratnayake](https://stackoverflow.com/users/14645116/dakshitha-ratnayake)  |2022-09-16|
|  SO | [Secure a Ballerina REST API with OpenID Connect using Asgardeo-Part 1](https://stackoverflow.com/collectives/wso2/articles/73300996/secure-a-ballerina-rest-api-with-openid-connect-using-asgardeo-part-1)  | [Dakshitha Ratnayake](https://stackoverflow.com/users/14645116/dakshitha-ratnayake)  |2022-08-10|
|  DZone | [Building a Secure REST API with OpenID Connect](https://dzone.com/articles/building-a-secure-rest-api-with-openid-connect)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-07-14|

### Taint Checking (Deprecated)
|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina taint checking guide](https://medium.com/ballerina-techblog/ballerina-taint-checking-guide-553ec9b8f153) | [Dhananjaya Wicramasingha](https://medium.com/@Dhananjaya)  |2019-09-25|

## Cloud

### Kubernetes/C2C

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Deploying Ballerina Code on the Cloud](https://dzone.com/articles/deploying-ballerina-code-to-cloud)  | [Anuruddha Liyanarachchi](https://dzone.com/users/4637886/anuruddhal.html)  |2021-11-18|
|  DZone | [Microservices in Practice: Deployment Shouldn't Be an Afterthought](https://dzone.com/articles/microservices-in-practice-deployment)  | [Lakmal Warusawithana](https://dzone.com/users/1141403/lakwarus.html)  |2020-07-06|
|  DZone | [How Ballerina Makes Deploying to Kubernetes Easier for Developers](https://dzone.com/articles/how-ballerina-makes-deploying-to-kubernetes-easier)  | [Lakmal Warusawithana](https://dzone.com/users/1141403/lakwarus.html)  |2020-02-13|
|  DZone | [Generate Kubernetes YAML Right From Your App Code](https://dzone.com/articles/yaml-less-kubernetes)  | [Dmitry Sotnikov](https://dzone.com/users/295907/DSotnikov.html)  |2018-07-11|
|  DZone | [Microservices, Docker, Kubernetes, Serverless, Service Mesh, and Beyond](https://dzone.com/articles/microservices-docker-kubernetes-serverless-service)  | [Chanaka Fernando](https://dzone.com/users/2726658/chanakaudaya.html)  |2018-05-11|

### AWS Step Functions

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Practical Serverless: Long-Running Workflows with Human Interactions using Step Functions and Ballerina](https://medium.com/ballerina-techblog/practical-serverless-long-running-workflows-with-human-interactions-using-step-functions-and-dd6fbcb42f29)  | [Anjana Fernando](https://medium.com/@lafernando)  |2020-09-27|

### AWS Lambda

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Practical Serverless: Integrating Amazon S3 and Rekognition with Ballerina](https://medium.com/ballerina-techblog/practical-serverless-integrating-amazon-s3-and-rekognition-with-ballerina-f338cdf6015c)  | [Anjana Fernando](https://medium.com/@lafernando)  |2020-08-31|
|  Blog | [Test your Ballerina Function written for AWS Lambda](https://medium.com/ballerina-techblog/test-your-ballerina-function-written-for-aws-lambda-4dceff6c461a)  | [Hemika Kodikara](https://medium.com/@hemika.kodikara)  |2020-02-20|
|  DZone | [Running a Ballerina Service as a Serverless Function in AWS Lambda](https://dzone.com/articles/ballerina-services-in-serverless-world)  | [Isuru Perera](https://dzone.com/users/887623/chrishantha.html)  |2018-01-19|
|  DZone | [Implementing Serverless Functions With Ballerina on AWS Lambda](https://dzone.com/articles/implementing-serverless-functions-with-ballerina-o)  | [Imesh Gunaratne](https://dzone.com/users/238910/imesh.html)  |2017-06-27|



### Azure functions

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Building Azure Functions Project With Ballerina](https://stackoverflow.com/collectives/wso2/articles/74323311/building-azure-functions-project-with-ballerina)  | [Anjana Supun](https://stackoverflow.com/users/7980815/anjana-supun)  |2022-11-04|
|  Blog | [Practical Serverless: A Scalable OCR Solution in 10 Minutes](https://medium.com/ballerina-techblog/practical-serverless-a-scalable-ocr-solution-in-10-minutes-af9f88c6b008)  | [Anjana Fernando](https://medium.com/@lafernando)  |2020-08-03|
|  Blog | [Introduction to Azure Functions in Ballerina](https://medium.com/ballerina-techblog/introduction-to-azure-functions-in-ballerina-ffc774eae034) | [Anjana Fernando](https://medium.com/@lafernando)  |2020-07-23|
|  Video | [Ballerina Azure Functions Walk-through](https://youtu.be/mCJ_o-Sdd9U)  | [Anjana Fernando](https://www.youtube.com/@lafernando)  |2020-07-23 |

### Azure services
|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Production Grade Ballerina Microservices on Azure AKS - Part 2: Continuous Integration With Azure DevOps](https://dzone.com/articles/production-grade-ballerina-microservices-on-azure)  | [Dunith Dhanushka](https://dzone.com/users/540877/dunithd.html)  |2020-09-01|
|  DZone | [Production-Grade Microservices on Azure AKS With Ballerina — Part 1: The Basics](https://dzone.com/articles/production-grade-microservices-on-azure-aks-with-b)  | [Dunith Dhanushka](https://dzone.com/users/540877/dunithd.html)  |2020-05-28|
|  Blog | [Ballerina/Azure Cloud Case Study: Scalable Asynchronous Request Processing](https://medium.com/ballerina-techblog/ballerina-azure-cloud-case-study-scalable-asynchronous-request-processing-43d1180e2512)  | [Anjana Fernando](https://medium.com/@lafernando)  |2019-03-06|

### OpenShift

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Services on OpenShift](https://medium.com/ballerina-techblog/ballerina-services-on-openshift-21f6a7836213)  | [Hemika Kodikara](https://medium.com/@hemika.kodikara)  |2019-03-21|

## Observability

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Automated Microservices Observability in the Cloud](https://dzone.com/articles/automated-microservices-observability-in-the-cloud)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2021-10-12|
|  DZone | [Rethinking Programming: Automated Observability](https://dzone.com/articles/rethinking-programming-automated-observability)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-05-01|

## Tooling

### OpenAPI

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO  | [Generating proper OpenAPI Documentation for Ballerina Resource APIs](https://stackoverflow.com/collectives/wso2/articles/72670105/generating-proper-openapi-documentation-for-ballerina-resource-apis)  | [Sumudu Nissanka](https://stackoverflow.com/users/10716900/lnash)  |2022-06-18|
|  Blog | [Introduction to OpenAPI with Ballerina](https://medium.com/ballerina-techblog/introduction-to-openapi-with-ballerina-5b3212bd71a8)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2021-09-04|
|  Blog | [Make your Own Ballerina Client Connector using the Ballerina OpenAPI Tool](https://medium.com/ballerina-techblog/make-your-own-ballerina-client-connector-using-ballerina-openapi-tool-3b375d89882)  | [Sumudu Nissanka](https://medium.com/@lnash94)  |2021-07-23|
|  Blog | [How Ballerina OpenAPI Tool addresses your Code-First and Design-First API Approaches](https://medium.com/ballerina-techblog/how-ballerina-addresses-your-code-first-and-design-first-api-approaches-3b9b0086fda9)  | [Sumudu Nissanka](https://medium.com/@lnash94)  |2021-04-04|
|  Blog | [Super Cool Feature for your Ballerina service from Ballerina OpenAPI tool](https://medium.com/ballerina-techblog/super-cool-feature-for-your-ballerina-service-from-ballerina-openapi-tool-ac2cce9cedfb)  | [Sumudu Nissanka](https://medium.com/@lnash94)  |2021-07-23|
|  Blog | [Generating a Mock Service for Ballerina](https://medium.com/ballerina-techblog/openapi-to-ballerina-service-9a3d2f9299eb)  | [Imesh Chandrasiri](https://medium.com/@dimal.chandrasiri)  |2019-10-01|

### AsyncAPI

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Learn how to use the AsyncAPI contract with cloud-native programming language Ballerina to benefit your API development](https://medium.com/@lnash94/learn-how-to-use-the-asyncapi-contract-with-cloud-native-programming-language-ballerina-to-benefit-5d004f8e5f5e)  | [Sumudu Nissanka](https://medium.com/@lnash94) |2022-07-28|

### Ballerina CLI tool

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Developing Ballerina Project With Ballerina CLI Tool](https://dzone.com/articles/developing-ballerina-project-with-ballerina-cli-to)  | [Dhanushka Madushan](https://dzone.com/users/3511875/dhanushkamadushan.html)  |2020-03-11|
|  Blog | [Ballerina tool for distribution management](https://medium.com/ballerina-techblog/ballerina-tool-for-distribution-management-4dbd638d003a)   | [Tharik Kanaka](https://medium.com/@tharik.kanaka)  |2019-12-25|

### SemVer validator 

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Introduction to Ballerina Semantic Versioning Validator](https://medium.com/ballerina-techblog/an-introduction-to-ballerina-semantic-versioning-validator-956d4884b121)   | [Nipuna Ranasinghe](https://medium.com/@nipunaranasinghe)  |2022-09-19|

### Strand dump tool

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Troubleshoot Ballerina runtime using the strand dump](https://medium.com/ballerina-techblog/troubleshoot-ballerina-runtime-using-the-strand-dump-12e7322f8071)  | [Nadeeshan Dissanayake](https://medium.com/@dmndkdissanayake)  |2022-10-10|

### Ballerina shell

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Shell REPL — Implementation Overview](https://medium.com/ballerina-techblog/ballerina-shell-repl-implementation-overview-ee7e909da20c)  | [Sunera Avinash](https://medium.com/@kdsuneraavinash)  |2021-03-01|
|  Blog | [Ballerina Shell — A REPL for Ballerina](https://medium.com/ballerina-techblog/ballerina-shell-a-repl-for-ballerina-d5053c94363f) | [Sunera Avinash](https://medium.com/@kdsuneraavinash)  |2021-02-28|

### Homebrew

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [How we built Ballerina Homebrew Formula](https://medium.com/ballerina-techblog/how-to-create-your-own-homebrew-package-or-formula-8dfbf8e001d3)  | [Rasika Perera](https://medium.com/@rasika90)  |2019-01-06|

## Editor

### VS Code

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina statement editor](https://medium.com/ballerina-techblog/ballerina-statement-editor-a03ae23478d0)  | [Madusha Gunasekara](https://medium.com/@madushagunasekara)  |2022-09-20|
|  Blog | [Ballerina Development With VSCode](https://medium.com/ballerina-techblog/ballerina-development-with-vscode-4a2ee4c82602)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2018-11-04|
|  Blog | [Ballerina VSCode Plugin — Graphical Editor for Ballerina](https://medium.com/ballerina-techblog/ballerina-vscode-plugin-graphical-editor-for-ballerina-b6af226178d6)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2018-11-03|
|  Blog | [Ballerina VSCode Plugin — Language Intelligence](https://medium.com/ballerina-techblog/ballerina-vscode-plugin-language-intelligence-39b278912b57)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2018-11-03|
|  Blog | [Setting Up VSCode for Ballerina Development in 60 Seconds](https://medium.com/ballerina-techblog/setting-up-vscode-for-ballerina-development-in-60-seconds-4ee5615cf82b)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2018-09-07|


### Language Server 

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [A Practical Guide for Language Server Protocol](https://medium.com/ballerina-techblog/practical-guide-for-the-language-server-protocol-3091a122b750)  | [Malintha Ranasinghe](https://medium.com/@malintha1996)  |2022-06-28|
|  Blog | [Implementing a Language Server… How Hard Can It Be? — Part 3](https://medium.com/ballerina-techblog/implementing-a-language-server-how-hard-can-it-be-part-3-7269962498ac)  | [Nipuna Marcus](https://medium.com/@nipunamarcus)  |2020-01-14|
|  Blog | [Implementing a Language Server…How Hard Can It Be?? — Part 2](https://medium.com/ballerina-techblog/implementing-a-language-server-how-hard-can-it-be-part-2-fa65a741aa23)  | [Nipuna Marcus](https://medium.com/@nipunamarcus)  |2019-09-30|
|  Blog | [Implementing a Language Server…How Hard Can It Be?? — Part 1 (Introduction)](https://medium.com/ballerina-techblog/implementing-a-language-server-how-hard-can-it-be-part-1-introduction-c915d2437076)  | [Nipuna Marcus](https://medium.com/@nipunamarcus)  |2018-03-07|
|  Blog | [Ballerina Language Server — Demystifying Goto Definition](https://medium.com/ballerina-techblog/ballerina-language-server-demystifying-goto-definition-a528e9089e81)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2019-12-31|
|  Blog | [Extending Ballerina Language Server — Auto-Completion](https://medium.com/ballerina-techblog/extending-ballerina-language-server-auto-completion-f46a0238d317)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2019-11-17|
|  Blog | [Language Server for Ballerina— Auto Completion Engine in Depth](https://medium.com/ballerina-techblog/language-server-for-ballerina-auto-completion-engine-in-depth-ee20e543ac26)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2018-05-07|

### IntelliJIDEA

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Hello World: The IntelliJ Style!](https://nipunaranasinghe.medium.com/ballerina-hello-world-the-intellij-style-23b7c5da29d7)   | [Nipuna Ranasinghe](https://medium.com/@nipunaranasinghe)  |2021-04-12|
|  Blog | [Setting up Ballerina in IntelliJ IDEA](https://medium.com/ballerina-techblog/setting-up-ballerina-in-intellij-idea-e49e7e150a54)  | [Shan Mahanama](https://medium.com/@shan1024)  |2017-11-14|

### Composer (Deprecated)

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Ballerina Composer — Tutorial (Part II — Function Definitions)](https://medium.com/@nadeeshaangunasinghe/ballerina-composer-tutorial-part-ii-function-definitions-2ce142b4359a)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2017-02-28|
|  Blog | [Ballerina Composer — Tutorial (Part II — Function Definitions)](https://medium.com/@nadeeshaangunasinghe/ballerina-composer-tutorial-part-ii-function-definitions-2ce142b4359a4)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2017-02-28|
|  Blog | [Ballerina Composer — Flexible, powerful and Smartest ever graphical tool for composing your Ballerina Programs](https://medium.com/@nadeeshaangunasinghe/ballerina-composer-flexible-powerful-and-smartest-ever-graphical-tool-for-composing-your-89fc76e672d4)  | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2017-02-22|


## Testing

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Unit test Ballerina integration with Mock backends](https://medium.com/ballerina-techblog/unit-test-ballerina-integration-with-mock-backends-ffff790edb9f)  | [Aquib Zulfikar](https://medium.com/@aquib_49146)  |2021-08-17|
|  Blog | [Get started with service testing using Ballerina test framework](https://medium.com/ballerina-techblog/get-started-with-service-testing-using-ballerina-test-framework-18e3b907a33)  | [Fathima Dilhasha](https://medium.com/@dilhasha.nazeer)  |2021-08-17|

## Logging

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [Integrating Humio With Ballerina for Microservices Logging](https://dzone.com/articles/integrating-humio-with-ballerina)  | [PJ Hagerty](https://dzone.com/users/2997412/pjhagerty.html)  |2020-02-25|

## Configuration management

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Configuration Management in Ballerina](https://medium.com/ballerina-techblog/configuration-management-in-ballerina-b952cae80c49)  | [Pubudu Fernando](https://medium.com/@pubuduf)  |2019-01-01|
|  Blog | [Making Use of the Ballerina Config API](https://medium.com/@pubuduf/ballerina-config-api-f6a9c455267b)  | [Pubudu Fernando](https://medium.com/@pubuduf)  |2017-11-11|

## Package management

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  DZone | [How to Use Ballerina Local Repository](https://dzone.com/articles/how-to-use-ballerina-local-repository)  | [Pramodya Mendis](https://dzone.com/users/4656527/pramodya.html)  |2021-12-10|
|  Blog | [Internals of Module Management in Ballerina](https://medium.com/ballerina-techblog/internals-of-module-management-in-ballerina-8dfaac3b52f1)  | [Natasha Wijesekare](https://medium.com/@nwijesekare)  |2018-12-23|
|  Blog | [Cheat Sheet for Ballerina Commands associated with Module Management](https://medium.com/ballerina-techblog/cheat-sheet-for-ballerina-commands-associated-with-module-management-f56555705aff)  | [Natasha Wijesekare](https://medium.com/@nwijesekare)  |2018-10-21|

## Building and installing Ballerina

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [Building Ballerina from Sources](https://blog.devgenius.io/building-ballerina-from-sources-948d7db4ee5) | [Ayesh Almeida](https://medium.com/@ayesh9303)  |2021-05-11|
|  Blog | [Installing Ballerina: The hard way](https://medium.com/@shan1024/installing-ballerina-the-hard-way-aff571882ebc)  | [Shan Mahanama](https://medium.com/@shan1024)  |2019-09-18|

## Ballerina Connectors

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [How to Write a Connector in Ballerina](https://medium.com/ballerina-techblog/how-to-write-a-client-endpoint-in-ballerina-3c24c185ffaf)  | [Chanaka Lakmal](https://medium.com/@ldclakmal)  |2018-05-14  |
|  Blog | [Ballerina Native Client Connectors and all you need to know :)](https://medium.com/@lanka.vitharana/ballerina-native-client-connectors-and-all-you-need-to-know-e76957ca05dd)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2017-11-12  |
|  Blog | [Ballerina Connectors/Endpoints and What? How? Why?](https://medium.com/ballerina-techblog/ballerina-connectors-endpoints-and-what-how-why-a04d414657f0)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2017-11-08  |
|  Blog | [Plug custom native functions to Ballerina](https://medium.com/ballerina-techblog/plug-custom-native-functions-to-ballerina-5bbc2e15b6ac)  | [Rajith Vitharana](https://medium.com/@lanka.vitharana)  |2017-07-02  |

## CI/CD

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Blog | [CI/CD Cloud Workflows with GitHub Actions and Ballerina](https://medium.com/ballerina-techblog/ci-cd-cloud-workflows-with-github-actions-and-ballerina-5dbda9bcea76)  | [Anjana Fernando](https://medium.com/@lafernando)  |2019-05-09|
|  DZone | [Effective Microservices CI/CD With GitHub Actions and Ballerina](https://dzone.com/articles/effective-microservices-cicd-with-github-actions-a)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-02-25|

## Comparisons with other languages

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Techtarget | [A 7-point language comparison of Ballerina vs. Golang](https://www.techtarget.com/searchapparchitecture/tip/A-language-comparison-of-Ballerina-vs-Golang) | [Kerry Doyle](https://www.techtarget.com/contributor/Kerry-Doyle)  |2022-06-30|
|  Blog | [How to Create a REST API — Spring Boot and Ballerina](https://medium.com/ballerina-techblog/how-to-create-a-rest-api-spring-boot-and-ballerina-cc85477e22c8) | [Nadeeshaan Gunasinghe](https://medium.com/@nadeeshaangunasinghe)  |2022-02-18|
|  Blog | [gRPC Compression Support in Go, Java, and Ballerina](https://buddhikothalawala.medium.com/grpc-compression-support-in-go-java-and-ballerina-76fefd0f4713)  | [Buddhi Kothalawala](https://medium.com/@buddhikothalawala)  |2021-10-22|
|  Blog | [Echo Websocket service example — GO vs NodeJs vs Ballerina](https://bhashineen.medium.com/echo-websocket-service-example-go-vs-nodejs-vs-ballerina-10dc2807b5af)  | [Bhashinee Nirmali](https://medium.com/@bhashineen)  |2020-10-31 |
|  DZone | [File-Based Integration: Spring Integration vs Ballerina](https://dzone.com/articles/file-based-integration-spring-integration-vs-balle)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2019-12-23|
|  Blog | [Spring Boot vs Ballerina: Back-end For Front-end (BFF) Service](https://medium.com/ballerina-techblog/spring-boot-vs-ballerina-back-end-for-front-end-bff-service-e108eda70f95)  | [Shafreen Anfar](https://medium.com/@anfar.shafreen)  |2019-12-21|
|  Blog | [Converting a Spring Boot Service To Ballerina](https://lafernando.medium.com/converting-a-spring-boot-service-to-ballerina-ab19082c8b11)  | [Anjana Fernando](https://medium.com/@lafernando)  |2019-11-27|
|  Blog | [Spring Boot vs Ballerina: Hello-World Service](https://medium.com/ballerina-techblog/level-zero-spring-boot-vs-ballerina-805d01739ea3)  | [Shafreen Anfar](https://medium.com/@anfar.shafreen)  |2019-11-22|
|  Blog | [Managing data using Ballerina vs Go](https://medium.com/ballerina-techblog/managing-data-using-ballerina-vs-go-fcbc9d20f691)  | [Anupama Pathirage](https://medium.com/@anupama.pathirage)  |2018-12-19|
|  Blog | [Dockerize services written in Go, SpringBoot & Ballerina — A comparison](https://medium.com/@kishanthan/dockerize-services-written-in-go-vs-springboot-vs-ballerina-a-comparison-5629fcc5658)  | [Kishanthan Thangarajah](https://medium.com/@kishanthan)  |2018-12-14|
|  DZone | [How Ballerina  Is Different From Other Programming Languages](https://dzone.com/articles/ballerinawhy-it-is-different-from-other-programmin)  | [Chanaka Fernando](https://dzone.com/users/2726658/chanakaudaya.html)  |2017-03-02|

## Usecases

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  SO | [Document Your GitHub Repo Changes to Google Sheets Using Ballerina](https://stackoverflow.com/collectives/wso2/articles/74021013/document-your-github-repo-changes-to-google-sheets-using-ballerina)  | [Tharushi J](https://stackoverflow.com/users/7866464/tharushi-jayasekara)  |2022-10-10|
|  SO | [Server for moving object monitoring system in Ballerina - Part 3](https://stackoverflow.com/collectives/wso2/articles/74173754/server-for-moving-object-monitoring-system-in-ballerina-part-3)  | [Kavindu Zoysa](https://stackoverflow.com/users/10721779/kavindu-gimhan-zoysa)  |2022-10-23|
|  SO | [Server for moving object monitoring system in Ballerina - Part 2](https://stackoverflow.com/collectives/wso2/articles/73808623/server-for-moving-object-monitoring-system-in-ballerina-part-2)  | [Kavindu Zoysa](https://stackoverflow.com/users/10721779/kavindu-gimhan-zoysa)  |2022-09-22|
|  SO | [Server for moving object monitoring system in Ballerina - Part 1](https://stackoverflow.com/collectives/wso2/articles/73564233/server-for-moving-object-monitoring-system-in-ballerina-part-1)  | [Kavindu Zoysa](https://stackoverflow.com/users/10721779/kavindu-gimhan-zoysa)  |2022-09-01|
|  Blog | [Get Daily Exchange Rates via SMS Using Ballerina](https://medium.com/better-programming/get-daily-exchange-rates-via-sms-using-ballerina-6cfb577633c9)  | [Malintha Ranasinghe](https://medium.com/@malintha1996)  |2022-08-25|
|  Blog | [Overview of manipulating data in Ballerina with different APIs (PayPal API and randomuser.me)](https://medium.com/ballerina-techblog/overview-of-manipulating-data-in-ballerina-with-different-apis-paypal-api-and-randomuser-me-720828919fab) | [Dulaj Dilshan](https://medium.com/@dulajdilshan)  |2022-08-16|
|  Blog | [Extract data from a mail and upload it to a Google Spreadsheet using Ballerina Integrator](https://medium.com/@aquib_49146/extract-data-from-a-mail-and-upload-it-to-a-google-spreadsheet-using-ballerina-integrator-82e6e23ea2fb)  | [Aquib Zulfikar](https://medium.com/@aquib_49146)  |2020-01-02|
|  Blog | [[Ballerina] Event Notification via Webhooks](https://medium.com/ballerina-techblog/ballerina-event-notification-via-webhooks-bc7cc63f4b6e)  | [Maryam Ziyad](https://medium.com/@maryamzi)  |2018-05-01|
|  DZone | [Three Programming Languages That Will Drive Enterprise Development](https://dzone.com/articles/three-programming-languages-that-will-drive-the-en)  | [Chanaka Fernando](https://dzone.com/users/2726658/chanakaudaya.html)  |2019-09-19|
|  Blog | [Tweet my Stars, Ballerina!](https://medium.com/@maryamzi/tweet-my-stars-ballerina-3a9652226116)  | [Shan Mahanama](https://medium.com/@shan1024)  |2017-10-23|

## Integration and design Patterns

|Type   | Title  |Author  | Publisehd Date  |
|---|---|---|---|
|  Article | [The future of SaaS middleware](https://www.telemediaonline.co.uk/the-future-of-saas-middleware/)  | EILEEN O'CONNOR  |2022-12-07|
|  DZone | [Practical Microservices Development Patterns: Sync vs. Async](https://dzone.com/articles/practical-microservices-development-patterns-sync)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-07-06|
|  DZone | [Reactive Microservices Done Right!](https://dzone.com/articles/reactive-microservices-done-right)  | [Anjana Fernando](https://dzone.com/users/715279/lafernando.html)  |2020-06-24|
|  Blog | [Clone and Aggregate Integration Pattern with Ballerina](https://medium.com/ballerina-techblog/clone-and-aggregate-integration-pattern-with-ballerina-bdcd537b683)  | [Shafreen Anfar](https://medium.com/@anfar.shafreen)  |2018-12-23|
|  DZone | [Rethinking Service Integrations With Microservices Architecture](https://dzone.com/articles/rethinking-service-integrations-with-microservices-1)  | [Imesh Gunaratne](https://dzone.com/users/238910/imesh.html)  |2017-03-03|


