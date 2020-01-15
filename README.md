# Overview
_Awesomeness_ is a comprehensive list of open source (mostly non-commercial) technical resources related to IT systems architecture, design and implementation.

# Backend

## .Net
### Awesome

### Architectures
* [CoolStore](http://github.com/vietnam-devs/coolstore-microservices) - A containerized polyglot microservices consisting of services based on .NET Core, NodeJS and more running on service mesh (istio).
* [eShopOnContainers](http://github.com/dotnet-architecture/eShopOnContainers) (Microsoft) - Easy to get started sample reference microservice and container based application.
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Cross-platform web development with Visual Studio Code, C#, F#, JavaScript, ASP.NET Core, EF Core, React (ReactJS), Redux, Babel.
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML + C# .NET web apps.
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) - Vue startup application template that uses ASP.NET Core API layered architecture at the back-end and JWT based authentication.
* [CoolStore Web Application](https://github.com/vietnam-devs/coolstore-microservices) - A Kubernetes-based microservices application on service mesh.
* [Distributed Playground](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
* [DNC-DShop](https://github.com/devmentors/DNC-DShop) - An open source project (and a course available soon at devmentors.io), providing in-depth knowledge about building microservices using .NET Core framework and variety of tools.
* [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) - Akka.NET Reference Architecture - CQRS + Sharding + In-Memory Replication.
* [Magazine Website](https://github.com/thangchung/magazine-website) - A magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices and asynchronous programming.
* [Microservices in .NET Core](https://github.com/horsdal/microservices-in-dotnetcore) - The code sample from the microservices book [https://manning.com/books/microservices-in-net-core](https://manning.com/books/microservices-in-net-core)
* [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
* [Equinox](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 2.2 application with DDD, CQRS and Event Sourcing.
* [Cloudscribe](https://github.com/cloudscribe/cloudscribe) - ASP.NET Core multi-tenant web application foundation with management for sites, users, roles, claims and more.
* []() - 
* []() - 
* []() - 

### Distributed systems
* Actor based
  * [Orleans](http://dotnet.github.io/orleans) (Microsoft) - A straightforward approach to building distributed, high-scale applications in .NET.
  * [Akka.Net](http://getakka.net) - Build powerful concurrent & distributed applications more easily.
    * [Lighthouse](http://github.com/petabridge/lighthouse) - A simple service discovery platform for Akka.Cluster.
  * [Orleankka](http://orleanscontrib.github.io/Orleankka) - Functional extension for Microsoft Orleans framework.
  * [Proto.Actor](http://proto.actor) - Ultra fast distributed actors for Go, C# and Java/Kotlin.
  * [vlingo/platform](http://vlingo.io) - Leverage reactive multi-core with DDD.
* Event Driven
  * [Cirqus](http://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework
  * [Akkatecture](http://akkatecture.net) - cqrs and event sourcing for dotnet core 
  * [EventFlow](http://docs.geteventflow.net) - EventFlow is a basic CQRS+ES framework designed to be easy to use
  * [CQRS.Net](http://www.getcqrs.net) - The CQRS platform for Azure or on-premise.
  * [NEventStore](http://neventstore.org) - A persistence agnostic Event Store for .NET
  * [Brighter](http://www.goparamore.io) - Command Processor & Dispatcher implementation that can be used as a lightweight library in other projects. 
  * [Its.CQRS](http://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
  * [Aggregates.NET](http://github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServiceBus and GetEventStore
  * [NES](http://github.com/elliotritchie/NES) - Lightweight framework that helps you build domain models when you're doing event sourcing.
  * [Xer.Cqrs](http://github.com/XerProjects/Xer.Cqrs) - A simple CQRS library
  * [CQRSlite](http://github.com/gautema/CQRSlite) - A lightweight framework for helping writing CQRS and Eventsourcing applications in C#
  * [CQRS.nu](http://cqrs.nu) - Helping teams apply Domain Driven Design, often through Event Sourcing and CQRS.
  * [Butterfly.Server](https://github.com/firesharkstudios/butterfly-server) - The everything is real-time C# backend for single page applications.
* Queueing
  * [RawRabbit](http://github.com/pardahlman/RawRabbit) - A modern .NET framework for communication over RabbitMq
* Service Bus
  * [Mass Transit](http://masstransit-project.com) - Free, open source, lightweight message bus for creating distributed applications using the .NET framework.
  * [NServiceBus](http://particular.net/nservicebus) - The most developer-friendly service bus for .NET
  * [Zebus](http://github.com/Abc-Arbitrage/Zebus) - A lightweight Peer to Peer Service Bus
  * [Obvs](http://christopherread.github.io/Obvs) - An observable µServiceBus .NET library that wraps the complexities of your particular message transport in simple Rx based interfaces. Supported transports include: ActiveMQ, RabbitMQ, NetMQ, EventStore, and Kafka.
* Utilities
  * [Foundatio](http://github.com/FoundatioFx/Foundatio) - Pluggable foundation blocks for building distributed apps.
  * [Projac](http://github.com/BitTacklr/Projac) - A set of .NET projection libraries

### Services
* REST
  * Frameworks
    * [SaasKit](http://github.com/saaskit/saaskit) - A developer toolkit for building SaaS applications.
    * [refit](http://paulcbetts.github.io/refit) - The automatic type-safe REST library for .NET Core, Xamarin and .NET.
    * [RestSharp](http://restsharp.org) - Simple REST and HTTP API Client for .NET.
    * [RestEase](http://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library for .NET Standard 1.1 and .NET Framework 4.5 and higher, which is simple and customisable.
    * [RestLess](http://github.com/letsar/RestLess) - The automatic type-safe-reflectionless REST API client library for .Net Standard.
    * [Halcyon](http://github.com/visualeyes/halcyon) - A HAL implementation for ASP.NET.
    * [JSON API .Net Core](http://github.com/json-api-dotnet/JsonApiDotNetCore) - A [{ json:api }](http://jsonapi.org) web application framework.
    * [NetCoreStack Flying Proxy](http://github.com/NetCoreStack/Proxy) - The type-safe REST library for .NET Standard 2.0.
    * [OData Web API](http://github.com/OData/WebApi): A server library built upon ODataLib and WebApi.
    * [RService.IO](http://github.com/Stoom/RService.IO) - Light weight REST service framework for ASP.NET Core.
    * [OpenRasta](http://openrasta.org) - Open-source .NET framework for building everything web, from web sites to RESTful APIs.
    * [ProxyKit](http://github.com/damianh/ProxyKit) - A toolkit to create HTTP (reverse) proxies on ASP.NET Core
    * [JasperFx](http://jasperfx.github.io) - Next generation framework for server side .Net Core applications
  * Utilities
    * [Flurl](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP client for .NET
    * [aspnet-api-versioning](https://github.com/microsoft/aspnet-api-versioning) - Provides a set of libraries which add service API versioning to ASP.NET Web API, OData with ASP.NET Web API, and ASP.NET Core.
    * [HttpClientGoodies.NET](http://github.com/jeffijoe/httpclientgoodies.net) - Useful utilities for the .NET HttpClient.
    * [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) - ASP.NET Core rate limiting middleware
  * Swagger
    * [NSwag](http://github.com/RSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, Web API and TypeScript.
    * [autorest](http://github.com/Azure/autorest) - OpenAPI (a.k.a Swagger) Specification code generator.
    * [Swashbuckle.AspNetCore](http://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger tools for documenting API's built on ASP.NET Core.
      * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) - A bunch of useful filters for Swashbuckle.AspNetCore.
* Web Sockets
  * [Fleck](http://github.com/statianzo/Fleck) - C# Websocket Implementation
  * [SignalR](http://signalr.net) - Incredibly simple real-time web for .NET
  * [WampSharp](http://wampsharp.net) - A C# implementation of WAMP (The Web Application Messaging Protocol)
  * [SuperSocket](http://github.com/kerryjiang/SuperSocket) - SuperSocket is a light weight, cross platform and extensible socket server application framework.
  * [websocket-sharp](http://sta.github.io/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
  * [NetGain](http://github.com/StackExchange/NetGain) (StackExchange) - A high performance websocket server library powering Stack Overflow.
* GraphQL
  * [GraphiQL.NET](http://github.com/JosephWoodward/graphiql-dotnet) - GraphiQL middleware for ASP.NET Core
  * [GraphQL.NET](http://github.com/mkmarek/graphql-dotnetcore) - Library for creating GraphQL servers with .NET core.
  * [GraphQL for .NET](http://github.com/graphql-dotnet/graphql-dotnet) - This is an implementation of [Facebook's GraphQL](http://github.com/facebook/graphql) in .NET.
  * [parser](http://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET
  * [GraphQL Conventions Library for .NET](http://github.com/graphql-dotnet/conventions) - GraphQL Conventions Library for .NET
  * [GraphQl.AspNetCore](http://github.com/JuergenGutsch/graphql-aspnetcore) - ASP.NET Core MiddleWare to create a GraphQL end-point
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - A .NET Core library designed to integrate the Dapper and graphql-dotnet projects with ease-of-use in mind and performance as the primary concern.
  * [GraphQl.AspNetCore](https://github.com/JuergenGutsch/graphql-aspnetcore) - ASP.NET Core MiddleWare to create a GraphQL end-point.
  * [Hot Chocolate](https://hotchocolate.io) (ChiliCream) - A GraphQL Server for .NET core and .NET classic.
  * [Tanka GraphQL](https://pekkah.github.io/tanka-graphql) - GraphQL server and execution libraries
* API
  * [CondenserDotNet](http://github.com/Drawaes/CondenserDotNet) - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul lib
  * [Ocelot](http://threemammals.com/ocelot) - Open Source .NET Core API Gateway
* Middleware 
  * [Polly](http://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.
  * [steeltoe](http://steeltoe.i) (Pivotal) - Open source project that enables .NET developers to implement industry standard best practices when building resilient microservices for the cloud.
  * [Nancy](http://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono.
  * [peasy](http://github.com/peasy/Peasy.NET) - A middle tier micro-framework for .NET
  * [LightNode](http://neuecc.github.io/LightNode) - Micro RPC/REST Framework built on OWIN
  * [Nelibur](http://github.com/Nelibur/Nelibur) - Message based webservice framework on the pure WCF.
  * [Xer.Cqrs](http://github.com/XerProjects/Xer.Cqrs) - A simple CQRS library. 
  * [CLSA.NET](http://cslanet.com) - Software development framework that helps you build a reusable, maintainable object-oriented business layer for your app.
  * [CAP](http://github.com/dotnetcore/CAP) - CAP is a library based on .Net standard, which is a solution to deal with distributed transactions, also has the function of EventBus, it is lightweight, easy to use, and efficiently.
  * [RestBus](http://github.com/tenor/RestBus) - Easy, Service Oriented, Asynchronous Messaging and Queueing for .NET
  * [Rebus](http://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET
  * [Warewolf](http://github.com/Warewolf-ESB/Warewolf) - Effortless Microservice Design and Integration. This repository includes the code-base for the Warewolf Studio and Server.
  * [DotNetty](http://github.com/Azure/DotNetty) - Port of [Netty](http://github.com/netty/netty), asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.
  * [Halibut](http://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
  * [microdot](http://github.com/gigya/microdot) - An open source .NET microservices framework
  * [EmbedIO](http://unosquare.github.io/embedio) - A tiny, cross-platform, module based, MIT-licensed web server for .NET Framework and .NET Core
* Network
  * [edtFTPnet](http://enterprisedt.com/products/edtftpnet) - The popular free .NET FTP library
  * [FluentFTP](http://github.com/robinrodricks/FluentFTP) - An FTP and FTPS client for .NET & .NET Standard, optimized for speed.
  * [SSH.NET](http://github.com/sshnet/SSH.NET) - Secure Shell (SSH) library for .NET, optimized for parallelism.
  * [Ether.Network](http://github.com/Eastrall/Ether.Network) - Simple and fast C# networking library. Compatible with .NET Standard 1.3 and 2.0

### Data Access
* ORM
  * [Dapper](http://github.com/StackExchange/Dapper) (StackExchange) - Simple object mapper for .NET.
    * [FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
    * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
    * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper.
  * [NReco](http://www.nrecosite.com/dalc_net.aspx) - CRUD operations, dynamic queries, SQL generation in C#
  * [DbExtensions](http://maxtoroq.github.io/DbExtensions) - Data-access framework with a strong focus on query composition, granularity and code aesthetics. 
  * [Insight.Database](http://github.com/jonwagner/Insight.Database) - Fast, lightweight .NET micro-ORM
  * [LimeBean](http://nick-lucas.github.io/LimeBean) - Simple and concise API for accessing ADO.NET data sources. 
  * [Simple.Data](http://github.com/markrendle/Simple.Data) - A light-weight, dynamic data access component for C# 4.0
* Persistence
  * [marten](http://jasperfx.github.io/marten) - Polyglot Persistence for .NET Systems using the Rock Solid PostgreSQL Database
  * [ReactiveETL](http://github.com/madhon/ReactiveETL) - Rewrite of Rhino ETL using the reactive extensions for .Net
  * [SqlKata](http://sqlkata.com) - The powerful C# sql query builder
  * [SharpRepository](https://github.com/SharpRepository/SharpRepository) - C# Generic Repository for use with Entity Framework, RavenDB and more with built-in caching options.
* Caching
  * [Akavache](http://github.com/akavache/Akavache) - An asynchronous, persistent key-value store.
* Full text
  * [NEST](http://github.com/elastic/elasticsearch-net) - Elasticsearch.Net & NEST
  * [SimMetrics.NET](http://github.com/StefH/SimMetrics.Net) - Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman).
* Migrations
  * [Fluent Migrator](http://github.com/fluentmigrator/fluentmigrator) - Fluent migrations framework for .NET
  * [DbUp](http://dbup.github.io) - DbUp is a .NET library that helps you to deploy changes to SQL Server databases.
  * [Evolve](https://evolve-db.netlify.com) - Simple database migration tool that uses plain SQL scripts.

### Scheduling & Job Management
* Scheduling
  * [Hangfire](http://www.hangfire.io) - An easy way to perform background processing in .NET and .NET Core applications. No Windows Service or separate process required.
  * [Quartz.NET](http://www.quartz-scheduler.net) - Full-featured, open source job scheduling system that can be used from smallest apps to large scale enterprise systems.
  * [FluentScheduler](http://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
  * [Gofer.NET](https://github.com/brthor/Gofer.NET) - Easy C# API for Distributed Background Tasks/Jobs for .NET Core.
* State Machines & Workflow
  * [Stateless](http://github.com/dotnet-state-machine/stateless) - A simple library for creating state machines in C# code
  * [Automatonymous](http://github.com/MassTransit/Automatonymous) - A state machine library for .Net - 100% code - No doodleware
  * [workflow-core](http://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard
  * [Core WF](http://github.com/dmetzgar/corewf) - A port of the Windows Workflow Foundation (WF) runtime to the .NET Standard.
  * [Durable Task Framework](http://github.com/Azure/durabletask) (Microsoft) - Write long running persistent workflows in C# using the async/await capabilities.
  * [State Machine](http://www.appccelerate.com/statemachine.html) - Our applications are full of state machines. Enabled and disabled UI elements, abstractions of devices and business logic. Implementing these state machines with the state pattern is overly complicated. Therefore, we implemented a state machine component that allows implementing a state machine as a single class. This reduces complexity and needed effort dramatically. See for yourself.
  * [LiquidState](http://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET 
* Misc.
  * [NCronTab](http://github.com/atifaziz/NCrontab) - Crontab for .NET

### IoC
* [StructureMap](http://github.com/structuremap/structuremap) - A Dependency Injection/Inversion of Control tool for .NET.
* [Autofac](http://autofac.org) - Autofac is an addictive Inversion of Control container for .NET Core, ASP.NET Core, .NET 4.5.1+, Universal Windows apps, and more.
* [Ninject](http://www.ninject.org) - Open source dependency injector for .NET
* [Simple Injector](http://simpleinjector.org) - Easy-to-use Dependency Injection (DI) library for .NET 4+ that supports Silverlight, Windows Phone, Windows 8 including Universal apps and Mono. 
* [Scrutor](http://github.com/khellang/Scrutor) - Assembly scanning and decoration extensions for Microsoft.Extensions.DependencyInjection
* [AutoDI](https://github.com/Keboo/AutoDI) - Dependency injection made simple.
* [Castle.Windsor](https://github.com/castleproject/Windsor) - A best of breed, mature Inversion of Control container available for .NET.
* [DryIoc](https://github.com/dadhi/DryIoc) - A fast, small, full-featured IoC Container for .NET.
* [Grace](https://github.com/ipjohnson/Grace) - A feature rich dependency injection container library.
* [Inyector](https://github.com/davidrevoledo/Inyector) - Automatic dependency injection by configuration over scaned assemblies.
* [Lamar](https://github.com/JasperFx/lamar) - Fast inversion of control tool and sundry items of Roslyn chicanery.
* [LightInject](https://github.com/seesharper/LightInject) - An ultra lightweight IoC container.
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - An easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [Stashbox](https://github.com/z4kn4fein/stashbox) - A lightweight, portable dependency injection framework for .NET based solutions.
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning and decoration extensions for Microsoft.Extensions.DependencyInjection.

### Build & Deployment
* Build systems
  * [Cake](https://cakebuild.net) - A cross-platform build automation system with a C# DSL.
  * [NUKE](https://nuke.build) - A cross-platform build automation system with C# DSL.
  * [FlubuCore](https://github.com/dotnetcore/FlubuCore) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
  * [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - Stamp your assemblies, packages and more with a unique version generated from a single, simple version.json file and include git commit IDs for non-official builds.
* Windows
  * [WiX](http://wixtoolset.org) - The most powerful set of tools available to create your windows installation experience.
  * [Wax](http://github.com/tom-englert/Wax) - An interactive editor for WiX setup projects.
  * [Topshelf](http://topshelf-project.com) - Put Your Apps on the Topshelf.
  * [Squirrel](http://github.com/squirrel/squirrel.windows) - An installation and update framework for Windows desktop apps.
  * [dotnet-win32-service](http://github.com/dasMulli/dotnet-win32-service) - Helper classes to set up and run as windows services directly on .net core. A ServiceBase alternative.
* Tools
  * [Catlight](http://catlight.io) - Notifier for developers
* Infrastructure
  * [FluentDocker](https://github.com/mariotoffia/FluentDocker) - Commands, Services and Fluent API for docker, docker-compose & docker-machine, for win/mac/linux and native docker in C#
  * [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API

### Performance & Monitoring
* [BenchmarkDotNet](http://benchmarkdotnet.org) - Powerful .NET library for benchmarking.
* [AppMetrics](http://www.app-metrics.io) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application. 
* [Metrics.NET](http://github.com/Recognos/Metrics.NET) - The Metrics.NET library provides a way of instrumenting applications with custom metrics (timers, histograms, counters etc) that can be reported in various ways and can provide insights on what is happening inside a running application.
* [Warden](http://github.com/warden-stack/Warden) - Define "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.  
* [NBench](http://github.com/petabridge/NBench) - Cross-platform performance benchmarking and testing framework for .NET applications.
* [Prefix](http://stackify.com/prefix) - Understand what your code is doing and find bugs you didn’t even know existed. 
* [OpenTracing](https://opentracing.io) - Vendor-neutral APIs and instrumentation for distributed tracing.

### Algorithms & Data Structures
* Algorithms
  * [C# Algorithms](http://github.com/aalhour/C-Sharp-Algorithms) - A C# plug-and-play class-library project of standard Data Structures and Algorithms.
  * [Algorithmia](http://github.com/SolutionsDesign/Algorithmia) - Algorithm and data-structure library for .NET 4.5.2+/Netstandard 2.0+.
  * [CodeJam](http://github.com/rsdn/CodeJam) - Set of handy reusable .NET components that can simplify your daily work and save your time when you copy and paste your favorite helper methods and classes from one project to another.
* Data structures
  * [C5](http://github.com/sestoft/C5) - C5 generic collection library for C#/.NET.
  * [Optional](http://github.com/nlkl/Optional) - A robust option type for C#
  * [Enums.NET](http://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
  * [Shielded](http://github.com/jbakic/Shielded) - A strict and mostly lock-free Software Transactional Memory (STM) for .NET
  * [ByteSize](http://github.com/omar/ByteSize) - Utility class that makes byte size representation in code easier by removing ambiguity of the value being represented.
  * [Disruptor.net](http://github.com/disruptor-net/Disruptor-net) - Port of LMAX Disruptor to .NET
* Functional programming
  * [Functional Extensions for C#](http://github.com/vkhorikov/CSharpFunctionalExtensions) - This library helps write code in more functional way.
  * [LanguageExt](http://github.com/louthy/language-ext) - C# functional language extensions - a base class library for functional programming
* Reactive programming
  * [Rx.NET](http://github.com/Reactive-Extensions/Rx.NET) - The Reactive Extensions for .NET
  * [Reactive Streams .NET#](http://github.com/reactive-streams/reactive-streams-dotnet) - Reactive Streams for .NET
  * [Qactive](http://github.com/RxDave/Qactive) - A reactive queryable observable framework.
  * [sodium](http://sodium.nz) - A functional reactive programming library for multiple programming languages.
  * [Dynamic Data](http://github.com/RolandPheasant/DynamicData) - Reactive collections based on Rx.Net.
  * [Streams](http://nessos.github.io/Streams) - A lightweight F#/C# library for efficient functional-style pipelines on streams of data. 
  * [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional extensions for C#.
* Mapping 
  * [AutoMapper](http://github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET.
  * [TinyMapper](http://github.com/TinyMapper/TinyMapper) - A quick object-object mapper for .NET.
  * [ExpressMapper](http://github.com/fluentsprings/ExpressMapper) - Mapping .Net types.
  * [AgileMapper](http://github.com/agileobjects/AgileMapper) - A zero-configuration, highly-configurable object-object mapper with viewable execution plans.
  * [Stringly.Typed](http://github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types
* Patterns
  * [Mediator.Net](http://github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported
  * [MediatR](http://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET 
* Units
  * [UnitsNet](http://github.com/angularsen/UnitsNet) - Makes life working with units of measurement just a little bit better.
  * [Humanizer](http://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities * [NodaMoney](http://github.com/remyvd/NodaMoney) - NodaMoney provides a library that treats Money as a first class citizen and handles all the ugly bits like currencies and formatting.
  * [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - Allows cleaner DateTime expressions and operations.
  * [NodaTime](http://nodatime.org) - A better date and time API for .NET
  * [DateTimeExtensions](http://github.com/joaomatossilva/DateTimeExtensions) - This project is a merge of several common DateTime operations in the form of extensions to System.DateTime, including natural date difference text (precise and human rounded), holidays and working days calculations on several culture locales.
  * [Exceptionless.DateTimeExtensions](http://github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods
  * [UnitConversion](https://github.com/atulmish/UnitConversion) - Expansible Unit Conversion Library for .Net Core and .Net Framework.
  * [DeviceId](http://github.com/MatthewKing/DeviceId) - A simple library providing functionality to generate a 'device ID' that can be used to uniquely identify a computer.
* Extensions & LINQ
  * [ExtraLINQ](http://github.com/mariusschulz/ExtraLINQ) - ExtraLINQ provides a set of extension methods for various .NET sequence types.
  * [MoreLINQ](http://github.com/morelinq/MoreLINQ) - Extensions to LINQ to Objects.
  * [Mono.Linq.Expressions](http://github.com/jbevain/mono.linq.expressions) - Helper library to complement the System.Linq.Expressions namespace.
  * [Z.ExtensionMethods](http://github.com/zzzprojects/Z.ExtensionMethods) - Enhance the .NET Framework with over 1000 extension methods.
  * [Extend](http://github.com/DaveSenn/Extend) - Extension methods for .Net.
  * [dotNetExt](http://github.com/crpietschmann/dotnetext) - .NET Extension Method Library
  * [Relinq](http://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
  * [LinqOptimizer](http://nessos.github.io/LinqOptimizer) - An automatic query optimizer-compiler for Sequential and Parallel LINQ
  * [Type Convert](http://github.com/deniszykov/typeconvert) - C# utilities for convertion between types, type construction and inspection 

### Geolocation
* [OsmSharp](http://www.osmsharp.com) - C# library to work with OpenStreetMap (OSM) data.
* [NetTopologySuite](http://github.com/NetTopologySuite/NetTopologySuite) - A .NET GIS solution that is fast and reliable for the .NET platform.
* [SharpMap](http://github.com/SharpMap/SharpMap) - An easy-to-use mapping library for use in web and desktop applications.
* [GeoJSON.NET](http://github.com/GeoJSON-Net/GeoJSON.Net) - .Net library for GeoJSON types & corresponding Json.Net (de)serializers

### Data science
* Math
  * [Math.NET](http://www.mathdotnet.com) - Open-source initiative to build and maintain toolkits covering fundamental mathematics, targetting advanced but also every day needs of .Net developers.
  * [Microsoft Automatic Graph Layout](http://github.com/Microsoft/automatic-graph-layout) (Microsoft) - A set of tools for graph layout and viewing.
  * [ALGLIB](http://www.alglib.net) - Cross-platform numerical analysis and data processing library.
  * [autodiff](http://github.com/alexshtf/autodiff) - A .NET library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions.
  * [GeometRi](http://github.com/RiSearcher/GeometRi) - Simple and lightweight computational geometry library for .Net
  * [MathExtensions)](http://github.com/TommasoScalici/MathExtensions) - Library for .NET that aims to extend the basic but yet incomplete System.Math, with simple and useful extensions methods regarding various mathematical domains, like methods for combinatorics, sequence analysis, generation and manipulation, random extractions, etc.
* Frameworks
  * [Accord](http://accord-framework.net) - Machine learning, computer vision, statistics and general scientific computing for .NET.
  * [TensorFlowSharp](http://github.com/migueldeicaza/TensorFlowSharp) - TensorFlow API for .NET languages
  * [AForge.NET](http://www.aforgenet.com/framework) - open source C# framework designed for developers and researchers in the fields of Computer Vision and Artificial Intelligence.
  * [Infer.NET](http://infernet.azurewebsites.net) (Microsoft) - A framework for running Bayesian inference in graphical models.
  * [numl](http://numl.net) - a general purpose machine learning framework
  * [GeneticSharp](http://github.com/giacomelli/GeneticSharp) - Fast, extensible, multi-platform and multithreading C# Genetic Algorithm library that simplifies the development of applications using Genetic Algorithms (GAs).
  * [FsLab](http://fslab.org) - Data science tools: Professional, powerful & cross-platform
  * [Spreads](http://github.com/Spreads/Spreads) - Series and Panels for Real-time and Exploratory Analysis of Data Streams
  * [Deedle](http://bluemountaincapital.github.io/Deedle) - Exploratory data library for .NET
  * [SIML](http://simlbot.com) - Synthetic Intelligence Markup Language
  * [ML-Agents](http://github.com/Unity-Technologies/ml-agents) - Unity Machine Learning Agents
  * [ML.NET](https://github.com/dotnet/machinelearning) - Cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers.
  * [SiaNet](https://github.com/SciSharp/SiaNet) - A C# deep learning library, human friendly, CUDA/OpenCL supported, well structured, easy to extend.

### Testing
* Test frameworks
  * [nUnit](http://nunit.org) - unit-testing framework for all .Net languages.
  * [xUnit](http://xunit.github.io) - Free, open source, community-focused unit testing tool for the .NET Framework.
  * [MSTest](http://msdn.microsoft.com/en-us/library/hh694602.aspx) (Microsoft)
  * [Fixie](http://fixie.github.io) - Conventional Testing for .NET
* Assertions
  * [Shouldly](http://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be!
  * [FluentAssertions](http://fluentassertions.com) - Fluent API for asserting the results of unit tests that targets .NET Framework 4.5, 4.7, .NET Standard 1.3, 1.6 and 2.0.
  * [Power Assert .NET](http://github.com/PowerAssert/PowerAssert.Net) - Readable, Writable Test Assertions for .NET
* Data generation
  * [Bogus](http://github.com/bchavez/Bogus) - A simple and sane fake data generator for C#, F#, and VB.NET. Based on and ported from the famed faker.js. 
  * [Fibber](http://github.com/Schandlich/Fibber) - An indiscriminate data generator that will generate random data for all properties in a given class based on the property's type vs. its name.
  * [Rant](http://berkin.me/rant) - Free, all-purpose procedural text generation language developed for .NET.
  * [NBuilder](http://github.com/nbuilder/nbuilder) - Rapid generation of test objects in .NET
* Mocking
  * [Rhino Mocks](http://hibernatingrhinos.com/oss/rhino-mocks) - Dynamic mock object framework for .NET
  * [Moq](http://github.com/moq/moq4) - The most popular and friendly mocking framework for .NET
  * [NSubstitute](http://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking libraries.
  * [FakeItEasy](http://fakeiteasy.github.io) - A .Net dynamic fake framework for creating all types of fake objects, mocks, stubs etc.
  * [Stubbery](http://markvincze.github.io/Stubbery) - Simple library for creating and running Api stubs in .NET.
* BDD
  * [SpecFlow](http://specflow.org) - Cucumber for .NET. The open source solution trusted by .NET devs around the world.
  * [xbehave](http://xbehave.github.io) - xUnit.net extension for describing your tests using natural language.
  * [SpecsFor](http://github.com/MattHoneycutt/SpecsFor) - Light-weight Behavior-Driven Development framework that focuses on ease of use for *developers* by minimizing testing friction.
  * [NFluent](http://github.com/tpierrain/NFluent) - Smooth your .NET TDD experience with NFluent!
  * [Machine.Specifications](http://github.com/machine/machine.specifications) - Context/Specification framework geared towards removing language noise and simplifying tests.
  * [TestStack.BDDfy](http://github.com/TestStack/TestStack.BDDfy) - BDDfy is the simplest BDD framework EVER!
  * [Storyteller](http://storyteller.github.io) - Solutions for creating robust, human readable acceptance tests for your .Net or CoreCLR system and a means to create "living" technical documentation.
* Automation
  * [Selenium](http://www.seleniumhq.org) - Selenium automates browsers.
  * [Atata](http://atata-framework.github.io) - C#/.NET automated web testing full featured framework
  * [TestStack.White](http://github.com/TestStack/White) -  Automating rich client applications based on Win32, WinForms, WPF, Silverlight and SWT (Java) platforms.
  * [Managed Windows API](http://mwinapi.sourceforge.net) - A collection of .NET components that wrap PInvoke calls to access native API by managed code.
  * [Effort](http://entityframework-effort.net) - A powerful tool that enables a convenient way to create automated tests for Entity Framework based applications.
* Load testing
  * [Netling](http://github.com/hallatore/Netling) - Netling is a load tester client for easy web testing.
* Misc.
  * [Scientist.net](http://github.com/github/Scientist.net) -  A .NET library for carefully refactoring critical paths.
  * [AutoFixture](http://github.com/AutoFixture/AutoFixture) - AutoFixture is an open source library for .NET designed to minimize the 'Arrange' phase of your unit tests in order to maximize maintainability.
  * [Papercut](http://github.com/ChangemakerStudios/Papercut) - Papercut Simple Desktop SMTP Server
  * [.NET Fake JSON Server](http://github.com/ttu/dotnet-fake-json-server) - Fake JSON Server is a Fake REST API that can be used as a Back End for prototyping or as a template for a CRUD Back End.

### Caching
* [CacheManager](http://github.com/MichaCo/CacheManager) - CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.
* [Cashew](http://github.com/joakimskoog/Cashew) - A simple and elegant yet powerful HTTP client cache for .NET
* [LazyCache](http://github.com/alastairtree/LazyCache) - An easy to use thread safe generics based in memory caching service with a simple developer friendly API for C#.
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) - An open source caching library that contains basic usages and some advanced usages of caching which can help us to handle caching more easier!

### Framework specifics
- Languages & Compilers
  - [Irony](http://github.com/IronyProject/Irony) - .NET Language Implementation Kit.
  - [Flee](http://github.com/mparlak/Flee) - Fast Lightweight Expression Evaluator.
  - [Sprache](http://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.
  - [Pidgin](http://github.com/benjamin-hodgson/Pidgin) (StackExchange) - A lightweight, fast and flexible parsing library for C#.
* Serialization
  * [Hyperion](http://github.com/akkadotnet/Hyperion) -  Polymorphic serialization for .NET
  * [Jil](http://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil
  * [Wire](http://github.com/rogeralsing/Wire) - A high performance polymorphic serializer for the .NET framework.
  * [Migrant](http://github.com/antmicro/Migrant) - Fast and flexible serialization framework usable on undecorated classes.
  * [Utf8Json](http://github.com/neuecc/Utf8Json) - Fast JSON Serializer for C#
  * [protobuf](http://silentorbit.com/protobuf) - ProtoBuf is a Google Protocol Buffers implementation by generating custom C# code for your .proto specifications.
  * [protobuf-net](http://github.com/mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET
  * [Newtonsoft.Json](http://www.newtonsoft.com/json) - Popular high-performance JSON framework for .NET
  * [Schema.NET](http://github.com/RehanSaeed/Schema.NET) - Objects turned into strongly typed C# POCO classes for use in .NET.
  * [EDI.NET](http://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS formats.
  * [Ceras](http://github.com/rikimaru0345/Ceras) - Converts any object into a byte[] and back. 
* Reflection
  * [Fasterflect](http://github.com/buunguyen/fasterflect) - .NET Reflection Made Fast and Simple.
  * [Fast-member](http://code.google.com/archive/p/fast-member) - .NET reflection is slow... well, kinda slow.
  * [AdvanceDLSupport](http://github.com/Firwood-Software/AdvanceDLSupport) - Alternative approach to your usual P/Invoke!
  * [Bond](http://github.com/Microsoft/bond) (Microsoft) - Cross-platform framework for working with schematized data. 
* Code Generation
  * [Sigil](http://github.com/kevin-montrose/Sigil) - A fail-fast validating helper for .NET CIL generation
  * [Cecil](http://cecil.pe) - Cecil is a library to inspect, modify and generate .NET programs and libraries.
  * [Testura.Code](http://github.com/Testura/Testura.Code) - Wrapper around the Roslyn API and used for generation, saving and compiling C# code.
* AOP
  * [AspectCore](http://github.com/dotnetcore/AspectCore-Framework) - AspectCore is an AOP-based cross platform framework for .NET Standard.
  * [Fody](http://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies

### Report & PDF Generation
* File handling
  * [FileHelpers](http://www.filehelpers.net) - Import or export data from fixed length or delimited records in files, strings or streams.
  * [FlatFiles](http://github.com/jehugaleahsa/FlatFiles) - Reads and writes CSV, fixed-length and other flat file formats with a focus on schema definition, configuration and speed.
  * [FlatMapper](http://github.com/joaomatossilva/FlatMapper) - FlatMapper is a library to import and export data from and to plain text files.
  * [CsvHelper](http://joshclose.github.io/CsvHelper) - A library for reading and writing CSV files.
* Office integration
  * [NetOffice](https://github.com/NetOfficeFw/NetOffice) - .NET wrapper assemblies for accessing Microsoft Office applications.
  * [NPOI](http://github.com/tonyqus/npoi) - .NET library that can read/write Office formats without Microsoft Office installed.
  * [Open XML SDK](http://github.com/officedev/open-xml-sdk) (Microsoft) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents. 
  * [DocX](http://github.com/xceedsoftware/DocX) - Fast and easy to use .NET library that creates or modifies Microsoft Word files without installing Word.
  * [ExcelDataReader](http://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files
  * [EPPlus](http://github.com/JanKallman/EPPlus) - Create advanced Excel spreadsheets using .NET
  * [ClosedXML](http://github.com/ClosedXML/ClosedXML) - Makes it easier for developers to create Excel 2007+ (.xlsx, .xlsm, etc) files.
  * [FastReport](https://github.com/FastReports/FastReport) - Reporting tool for .NET Core/.NET Framework that helps your application generate document-like reports.
* PDF generation
  * [PDFSharp](http://www.pdfsharp.net) - Open Source .NET library that easily creates and processes PDF documents on the fly from any .NET language.
  * [iTextSharp](http://github.com/itext/itextsharp) - Easy PDF generation and manipulation for Java and .NET developers.
  * [PdfReport.Core](http://github.com/VahidN/PdfReport.Core) - Code first reporting engine, which is built on top of the [iTextSharp.LGPLv2.Core](http://github.com/VahidN/iTextSharp.LGPLv2.Core) and [EPPlus.Core](http://github.com/VahidN/EPPlus.Core) libraries.
* Markdown
  * [Markdig](http://github.com/lunet-io/markdig) - A fast, powerful, CommonMark compliant, extensible Markdown processor for .NET
  * [CommonMark.NET](http://github.com/Knagis/CommonMark.NET) - Implementation of CommonMark specification in C# for converting Markdown documents to HTML. 
  * [MarkdownSharp](http://github.com/StackExchange/MarkdownSharp) (StackExchange) - Open source C# implementation of Markdown processor, used by Stack Overflow.
* Reports
  * [DoddleReport](http://github.com/matthidinger/DoddleReport) - Generate custom reports (PDF, Excel, etc) from any IEnumerable datasource.

### Email
* [Postal](http://aboutcode.net/postal) - Create email using ASP.NET MVC views
* [MailKit](http://github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP. 
* [MailBody](http://doxakis.github.io/MailBody) - Create transactional email with a fluent interface (.net)
* [RazorMailer](http://github.com/jonleigh/RazorMailer) - A lightweight framework for sending emails from any .NET platform using Razor templates.

### Logging
* [Logary](http://logary.github.io) - High performance, multi-target logging, metric, tracing and health-check library for mono and .Net.
* [NLog](http://github.com/nlog/NLog) - Advanced and Structured Logging for Various .NET Platforms 
* [ELMAH](http://elmah.github.io) - Application-wide error logging facility that is completely pluggable. 
  * [ELMAH Core](https://github.com/ElmahCore/ElmahCore) - ELMAH for Net.Standard and Net.Core.
* [log4net](http://logging.apache.org/log4net) (Apache) - A tool to help the programmer output log statements to a variety of output targets. 
* [Serilog](http://serilog.net) - Flexible, structured events — log file convenience.
  * [Serilog ASP.NET Core](https://github.com/serilog/serilog-aspnetcore) - Serilog integration for ASP.NET Core 2+.
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) - An add-on to Serilog to log exception details and custom properties that are not output in Exception.ToString().
  * [Serilog Settings](https://github.com/serilog/serilog-settings-configuration) - A Serilog configuration provider that reads from Microsoft.Extensions.Configuration.
* [StackExchange.Exceptional](http://github.com/NickCraver/StackExchange.Exceptional) - Error handler used for the Stack Exchange network
* [Essential Diagnostics](http://github.com/sgryphon/essential-diagnostics) - Additional trace listeners, filters and utility classes for the .NET Framework System.Diagnostics trace logging. 
* [Logazmic](http://github.com/ihtfw/Logazmic) - Windows log viewer for log4j
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - High performance understanding for stack traces.

### CLI
* Parsers
  * [Command Line Parser](http://www.appccelerate.com/commandlineparser.html) - Every now and then, we write a little console application to quickly get a job done.
  * [CommandLineUtils](http://natemcmaster.github.io/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework. 
  * [clipr](http://github.com/nemec/clipr) - Command Line Interface ParseR for .Net
  * [commandline](http://github.com/commandlineparser/commandline) - C# command line parser for .NET with F# support
  * [EntryPoint](http://nick-lucas.github.io/EntryPoint) - Composable CLI Argument Parser for all modern .Net platforms 
  * [Fluent Command Line Parser](http://github.com/fclp/fluent-command-line-parser) - A simple, strongly typed .NET C# command line parser library using a fluent easy to use interface
  * [PowerArgs](http://github.com/adamabdelhamed/PowerArgs) - The ultimate .NET Standard command line argument parser
  * [readline](http://github.com/tonerdo/readline) - A Pure C# GNU-Readline like library for .NET/.NET Core
  * [Oakton](https://jasperfx.github.io/oakton) - Parsing and utilities for robust command line tools in .Net
* Formatters
  * [Colorful.Console](http://github.com/tomakita/Colorful.Console) - Style your C# console output!
  * [CsConsoleFormat](http://github.com/Athari/CsConsoleFormat) - .NET C# library for advanced formatting of console output
  * [ConsoleTableExt](http://github.com/minhhungit/ConsoleTableExt) - A fluent library to print out a nicely formatted table in a console application C#
* Invokers
  * [cmd](http://github.com/manojlds/cmd) - A C# Library to run external programs / commands in a simpler way.
  * [CliWrap](http://github.com/Tyrrrz/CliWrap) - Wrapper for command line interface executables.
  * [Sheller](https://github.com/twitchax/Sheller) - A .NET library that makes shelling out commands super easy and fluent.

### Content Management
* CMS
  * [Orchard](http://orchardproject.net) - A free, open source, community-focused Content Management System built on the ASP.NET MVC platform.
  * [Orchard Core](https://github.com/OrchardCMS/OrchardCore) - An open-source modular and multi-tenant application framework built with ASP.NET Core, and a content management system (CMS) built on top of that application framework.
  * [Umbraco](http://umbraco.com) - Umbraco is a fully-featured, open source Content Management System loved by thousands for its flexibility and great editing experience. 
  * [BetterCMS](http://www.bettercms.com) - Better CMS has an intuitive user interface designed to help you make updates to your website content and SEO settings quickly and efficiently. 
  * [Piranha CMS](http://piranhacms.org) - A lightweight & unobstrusive CMS for ASP.Net Core.
  * [Cofoundry](http://www.cofoundry.org) - Open Source .NET Core Application Framework & Content Management Platform
* Static Site Generators
  * [Pretzel](http://github.com/Code52/pretzel) - A site generation tool (and then some) for .NET platforms
  * [Sandra.Snow](http://github.com/Sandra/Sandra.Snow) - Jekyll inspired static site generation for .NET
  * [Wyam](http://wyam.io) - A highly modular and extremely configurable static content generator and toolkit.
* Templating
  * [RazorEngine](http://antaris.github.io/RazorEngine) - A templating engine built on Microsoft's Razor parsing engine, RazorEngine allows you to use Razor syntax to build dynamic templates.
  * [RazorLight](http://github.com/toddams/RazorLight) - Template engine based on Microsoft's Razor parsing engine for .NET Core
  * [Nustache](http://github.com/jdiamond/Nustache) - Logic-less templates for .NET
  * [mustache#](http://github.com/jehugaleahsa/mustache-sharp) - An extension of the mustache text template engine for .NET.
  * [DotLiquid](http://dotliquidmarkup.org) - DotLiquid is a templating system ported to the .NET framework from Ruby’s [Liquid Markup](http://www.liquidmarkup.org).
  * [Stubble](http://github.com/stubbleorg/stubble) - Trimmed down {{mustache}} templates in .NET

### Security & Compression
* Compression
  * [SharpZipLib](http://github.com/icsharpcode/SharpZipLib) - Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
  * [Snappy.Sharp](http://github.com/jeffesp/Snappy.Sharp) - An implementation of google's Snappy compression format in C#.
  * [SharpCompress](http://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.  
  * [LZ4](http://github.com/MiloszKrajewski/lz4net) - ultra fast compression algorithm - for all .NET platforms
* Hashing
  * [HashLib](http://archive.codeplex.com/?p=hashlib) - Hash files, streams, common types of data.
* Security
  * [IdentityServer](http://identityserver.io) - The Identity and Access Control solution that works for you
  * [OpenIddict](http://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core
  * [DotNetOpenAuth](http://dotnetopenauth.net) - Get started with OpenID, OAuth today!
  * [IdentityModel](http://github.com/IdentityModel/IdentityModel2) - A .NET standard helper library for claims-based identity, OAuth 2.0 and OpenID Connect. 
  * [Stuntman](http://rimdev.io/stuntman) - Sometimes you need a Stuntman before you send in real, unsuspecting users!
  * [jose-jwt](http://github.com/dvsekhvalnov/jose-jwt) - Ultimate Javascript Object Signing and Encryption (JOSE) and JSON Web Token (JWT) Implementation for .NET and .NET Core
  * [NWebsec](http://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET
  * [reCAPTCHA](http://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASPNET Core
  * [OwaspHeaders](http://github.com/GaProgMan/OwaspHeaders.Core) - A .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security
  * [Security](http://github.com/aspnet/Security) - Middleware for security and authorization of web apps.
  * [Cierge](http://pwdless.github.io/Cierge-Website) - Open source authentication server (OIDC) that handles user signup, login, profiles, management, and more.
* Cryptography
  * [BCrypt.NET](http://github.com/BcryptNet/bcrypt.net) - Bringing updates to the original bcrypt package
  * [Bouncy Castle](http://bouncycastle.org) - A lightweight cryptography API for Java and C#.
  * [libsodium-net](http://github.com/adamcaudill/libsodium-net) - A secure cryptographic library
  * [StreamCryptor](http://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf
  * [inferno](http://securitydriven.net/inferno) - .NET crypto done right. Professionally audited.
  * [nsec](https://nsec.rocks) - A modern and easy-to-use cryptographic library for .NET Core based on libsodium.

### Utilities
* Parsers
  * [HAP](http://html-agility-pack.net) - Html Agility Pack
  * [AngleSharp](http://anglesharp.github.io) - makes .NET ❤ HTML5
  * [YamlDotNet](http://github.com/aaubry/YamlDotNet) - .NET library for YAML
  * [Regextra](http://github.com/amageed/Regextra) - Simplifies some tasks typically solved via regex so that you no longer have (problems){2}.
* Detection
  * [MimeKit](http://github.com/jstedfast/MimeKit) - A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
  * [DeviceDetector.NET](http://github.com/totpero/DeviceDetector.NET) - The Universal Device Detection library will parse any User Agent and detect the browser, operating system, device used (desktop, tablet, mobile, tv, cars, console, etc.), brand and model. 
* Configuration
  * [Formo](http://chrismissal.com/Formo) - Formo allows you to use your configuration file as a dynamic object.
* Validation
  * [FluentValidation](http://github.com/JeremySkinner/FluentValidation) - A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
  * [valit](http://github.com/valit-stack/Valit) - Valit is dead simple validation for .NET Core.
  * [Guard](https://github.com/safakgur/guard) - A high-performance, extensible argument validation library.
  * [Valit](https://github.com/valit-stack/Valit) - Dead simple validation for .NET Core.
* Feature Management
  * [FeatureManagement.Net](https://github.com/microsoft/FeatureManagement-Dotnet) - Provides standardized APIs for enabling feature flags within applications. 
* Mics. 
  * [P](http://github.com/p-org/P) (Microsoft) - P is a language for asynchronous event-driven programming.
  * [ServiceStack.Text](http://servicestack.net/text) - .NET's missing high-performance utility belt
  * [SmartFormat.NET](http://github.com/scottrippey/SmartFormat.NET) - An extensible .NET replacement for String.Format

## Java
### Distributed systems
* [Akka](http://akka.io)

### Services
* [Finagle](http://twitter.github.io/finagle) (Twitter) - An extensible RPC system for the JVM, used to construct high-concurrency servers.

### Data Access
* [Calcite](http://calcite.apache.org) (Apache) - The foundation for your next high-performance database. 

## Python
### Awesome
* [Awesome Python](http://awesome-python.com) - Life is short, you need Python.

### Architectures
* [Saleor](http://getsaleor.com) - A GraphQL-first E-commerce platform for perfectionists

### Distributions and Installers
* [virtualenv](http://virtualenv.pypa.io/en/stable) - A tool to create isolated Python environments.
* [Anaconda](http://www.anaconda.com) -  The Most Popular Python Data Science Distribution
* [Miniconda](http://conda.io/miniconda.html) - A smaller alternative to Anaconda that is just conda and its dependencies

### Web Frameworks & Services
* [Django](http://www.djangoproject.com) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
* [sandman2](http://github.com/jeffknupp/sandman2) - Automatically generate a RESTful API service for your legacy database. No code required! 
* [Nameko](http://nameko.readthedocs.io/en/stable) - A microservices framework for Python that lets service developers concentrate on application logic and encourages testability
* [Vibora](http://vibora.io) - Fast, asynchronous and elegant Python web framework 

### Distributed Systems
* [Airflow](http://airflow.apache.org) (Apache) - A platform to programmatically author, schedule and monitor workflows
* [Celery](http://www.celeryproject.org) - An asynchronous task queue/job queue based on distributed message passing
* [Zappa](http://github.com/Miserlou/Zappa) - Serverless Python.

### Data Access
* [Peewee](http://github.com/coleifer/peewee) - A small, expressive orm (upports postgresql, mysql and sqlite)

### Data science
* Machine Learning
  * [TensorFlow](http://www.tensorflow.org) (Google) - An open source machine learning framework for everyone.
  * [NumPY](http://www.numpy.org) - fundamental package for scientific computing with Python.
  * [Pandas](http://pandas.pydata.org) - High-performance, easy-to-use data structures and data analysis tools for the [Python](http://www.python.org) programming language.
  * [scikit-learn](http://scikit-learn.org/stable) (INRIA) - Machine Learning in Python
  * [SpaCy](http://spacy.io) - Industrial-StrengthNatural Language Processing
  * [Flair](http://github.com/zalandoresearch/flair) - A very simple framework for state-of-the-art Natural Language Processing (NLP)
  * [Dask](http://dask.pydata.org/en/latest) - Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love.
  * [Numba](http://numba.pydata.org) - The power to speed up your applications with high performance functions written directly in Python.
  * [Pyro](http://pyro.ai) (Uber) - Deep Universal Probabilistic Programming
  * [Horovod](http://github.com/uber/horovod) (Uber) - Distributed training framework for TensorFlow
  * [chainer](http://chainer.org) - Bridge the gap between algorithms and implementations of deep learning.
  * [NLTK](http://www.nltk.org) - A leading platform for building Python programs to work with human language data
* Operational Research
  * [HorusLP](http://github.com/shanglun/horuslp) - Productivity tools for operations research based applications.

### Graphics & Drawring
* [Chartify](http://github.com/spotify/chartify) (Spotify) - Python library that makes it easy for data scientists to create charts.
* [Altair](http://altair-viz.github.io) - Declarative Visualization in Python

## Go
### Services
* [Martini](http://github.com/go-martini/martini) - Classy web framework for Go
* [Gorilla](http://www.gorillatoolkit.org/pkg/mux) - Gorilla web toolkit

## Node.js
### Awesome
* [Awesome GraphQL](http://github.com/chentsulin/awesome-graphql) - Awesome list of GraphQL & Relay
* [Automatic API](http://github.com/dbohdan/automatic-api) - A list of software that turns your database into a REST/GraphQL API 

### Distributed Systems
* Eventing
  * [noel](http://lifenautjoe.github.io/noel) - A universal, human-centric, replayable Javascript event emitter
  * [Bull](http://github.com/OptimalBits/bull) - Premium queue package for handling jobs and messages in NodeJS
  * [emitter](https://emitter.io) - Free open source real-time messaging service that connects all devices.
* Actors
  * [nact](http://nact.io) - Redux but for the server.

### Services
* REST
  * [ActionHero](http://www.actionherojs.com) - The reusable, scalable, and quick node.js API server for stateless and stateful applications
  * [egg](http://eggjs.org/en) - Born to build better enterprise frameworks and apps with Node.js & Koa
  * [NestJs](https://nestjs.com) - A framework for building efficient, scalable Node.js server-side applications.
* API Gateways
  * [Tyk](http://tyk.io) - Open source API Gateway that is fast, scalable and modern.
  * [Kong](http://getkong.org) - Secure, Manage & Extend your APIs and Microservices
* [GraphQL](http://graphql.org)
  * [Prisma](http://www.prismagraphql.com) (Graphcool) - Turn your database into a GraphQL API
  * [Apollo](http://github.com/apollographql/apollo-server) (Meteor) - GraphQL server for Express, Connect, Hapi, Koa and more
  * [PostGraphile](http://www.graphile.org) - Tools for building performant pluggable GraphQL APIs.
  * [Join-Monster](http://github.com/stems/join-monster) - A GraphQL to SQL query execution layer for query planning and batch data fetching.
  * [gestalt](http://github.com/charlieschwabacher/gestalt) - Use the GraphQL schema language and a small set of directives to define an API with a PostgreSQL backend declaratively, really quickly, and with a tiny amount of code.
  * [sql-to-graphql](http://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure 
  * [Altair](http://altair.sirmuel.design) - A beautiful feature-rich GraphQL Client for all platforms
  * [GraphQL Yoga](http://github.com/graphcool/graphql-yoga) (Graphcool) - Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience
* Serverless
  * [serverless-offline](http://github.com/dherault/serverless-offline) - Emulate AWS λ and API Gateway locally when developing your Serverless project 
  * [serverless-babel-starter](http://github.com/postlight/serverless-babel-starter) - Serverless with all the fixings: Webpack, Babel, Jest, ESLint, and Prettier.
  * [lambdapack](http://www.npmjs.com/package/lambdapack) - Package your AWS Lambda efficiently, ready to be deployed with [apex/up](http://github.com/apex/up)

### Data Access
* [EventStore](http://eventstore.org) - The open-source, functional database with Complex Event Processing in JavaScript.
* [TypeORM](http://typeorm.io) - ORM for TypeScript and JavaScript (ES7, ES6, ES5)
* [Sequelize](http://docs.sequelizejs.com) - A promise-based ORM for Node.js v4 and up.

### Templating
* [Pug](http://pugjs.org) – Robust, elegant, feature rich template engine for Node.js

### Algorithms & Data Structures
* Numerics
  * [crunch.js](http://crunch.js.org) - Arbitrary-Precision Integer Arithmetic Library
  * [Yaffle BigInteger](http://github.com/Yaffle/BigInteger) - Yet another implementaion of arbitrary-precision integers in pure JavaScript. 
  * [bigi](http://github.com/cryptocoinjs/bigi) - JavaScript Big Integer library based upon Tom Wu's work. 
  * [bn.js](http://github.com/indutny/bn.js) - BigNum in pure javascript
* Bitmaps
  * [Fast-BitSet](http://github.com/mattkrick/fast-bitset)-  A fast bitset with some nice methods
* Functional Programming
  * [Pampy.js](http://github.com/santinic/pampy.js) - Pattern Matching for JavaScript

### CRM
* [Tipe](http://tipe.io) - Create your content with powerful editing tools and access it from anywhere with a GraphQL or REST API. Stop letting your CMS decide how you build your apps. 

### Tools
* [i18next](http://www.i18next.com) - An **internationalization framework** written in and for JavaScript. 
* [ReLaXed](http://github.com/RelaxedJS/ReLaXed) - Create PDF documents using web technologies.
* [Prompts](http://github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts
* [Headless Chrome Crawler](http://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome
* [ClearGPDR](http://www.cleargdpr.com) - The Leading GDPR Compliance Solution: Open Source, Blockchain Based.

# Frontend
## Design
### Development
* [Haiku](http://www.haiku.ai) - Where designing is building
* [Figma](http://www.figma.com)
* [CSS Grid Builder](http://cssgrid.cc) - A collection of resources & tools to help you manage the Grid

### Style guides
* [Catalog](http://www.catalog.style) - Living style guides for digital products
* [Design Systems Repo](http://designsystemsrepo.com) - A frequently updated collection of Design Systems

## CSS
* Extensions
  * [CSS Blocks](http://css-blocks.com) (LinkedIn) - Blazing fast CSS for your design systems and app components
    * [OptiCSS](http://github.com/linkedin/opticss) (LinkedIn) - A CSS Optimizer
  * [SaSS](http://sass-lang.com)
  * [LeSS](http://lesscss.org)
* Frameworks
  * [mustard](http://mustard-ui.com) - Mustard UI is a starter CSS framework that actually looks good
* UX Frameworks
  * [Mailchimp](http://ux.mailchimp.com/patterns) - MailChimp Pattern Library is a byproduct of our move to a more responsive, nimble, & intuitive app.
* Email
  * [MJML](http://mjml.io) - The only framework that makes responsive email easy
  * [Foundation For Emails](http://foundation.zurb.com/emails.html) - Quickly create responsive HTML emails that work. Even on Outlook.

## Javascript

### Knowledge Base
* [Front End Toolkit](http://github.com/devbridge/Front-End-Toolkit)
* [Best of JS](http://bestof.js.org)
* [Awesome](http://github.com/sindresorhus/awesome) - Curated list of awesome lists

### Service/Data
* [ActiveResource.js](http://active-resource.js.org) - An API resource relational mapping library in JavaScript

### UX Frameworks
* Design Systems
  * [Awesome Design Systems](http://github.com/alexpate/awesome-design-systems) - A collection of awesome design systems
  * [Bootstrap](http://getbootstrap.com) - Build responsive, mobile-first projects on the web
    * [Material Design for Bootstrap](http://mdbootstrap.com)
    * [Shards](http://designrevision.com/downloads/shards) - A free and modern UI toolkit for web makers
    * [Fire](http://fire.uxtheme.net) - Easy Development with Fire UI Kit
  * [Carbon](http://carbondesignsystem.com) (IBM) - Design system for IBM Cloud products.
  * [Stencil](http://stenciljs.com) - The magical, reusable web component compiler
  * [Rizzo](http://rizzo.lonelyplanet.com/styleguide) (Lonely Planet) - 
  * [boundless](http://boundless.js.org) - UI toolkit that was conceived to abstract away difficult interface patterns
  * [Lightning Design System](http://www.lightningdesignsystem.com) (Salesforce) - Create the world’s best enterprise app experiences.
  * [Mapbox](http://www.mapbox.com/base) (Maxbox) - An internal guide & code repository for designing and coding at Mapbox.
  * [Atlassian Design](http://atlassian.design) (Atlassian) - Use Atlassian's end-to-end design language to create straightforward and beautiful experiences.
  * [Auth0 Styleguide](http://styleguide.auth0.com) (Auth0) - Conjunction of design patterns, components and resources used across our products.
  * [EVA](https://eva.design) - Customizable Design System easily adaptable to your Brand.
* Themes
  * [Hacker Themes](http://hackerthemes.com) - Bootstrap 4 themes & templates for ambitious developers
  * [Creative Time](http://www.creative-tim.com) - Premium Bootstrap themes, templates, UI Kits and more developed by Creative Tim.
  * [Tabler](http://tabler.github.io) - Premium and Open Source dashboard template with responsive and high quality UI. For Free!
  * [Papaya](http://www.eatapapaya.com) - Yummy landing page templates for any project.

### Libraries
* Charts and graphics
  * [protovis](http://mbostock.github.io/protovis) - A graphical approach to visualization
  * [d3js](http://d3js.org) - Data-Driven Documents
    * [d3-discovery](http://d3-discovery.net) - Finding D3 plugins with ease
    * [mermaid](http://mermaidjs.github.io) - Generation of diagram and flowchart from text in a similar manner as markdown
    * [nvd3](http://nvd3.org) - A reusable charting library
    * [d3-annotation](http://d3-annotation.susielu.com)
    * [plotly.js](http://plot.ly/javascript) - The open source JavaScript graphing library that powers Plotly
    * [epoch](http://epochjs.github.io/epoch) - A general purpose real-time charting library for building beautiful, smooth, and high performance visualizations
    * [metricsgraphicsjs](http://www.metricsgraphicsjs.org) - A library that is optimized for visualizing and laying out time-series data
    * [rickshaw](http://code.shutterstock.com/rickshaw) - JavaScript toolkit for creating interactive time series graphs
    * [plottablejs](http://plottablejs.org) (Palantir) - Flexible, interactive charts for the web
  * [Vega](http://vega.github.io/vega) - A Visualization Grammar
    * [Vega Lite](http://vega.github.io/vega-lite) - A Grammar of Interactive Graphics
  * [dygraphs](http://dygraphs.com) - Fast, flexible open source JavaScript charting library
  * [sigmajs](http://sigmajs.org) - Sigma is a JavaScript library dedicated to graph drawing
  * [cytoscape](http://js.cytoscape.org) - Graph theory / network library for analysis and visualisation
  * [cubismjs](http://square.github.io/cubism) (Square) - Time Series Visualization
  * [taucharts](http://www.taucharts.com) - Flexible javascript charting library for data exploration
  * [echarts](http://echarts.baidu.com) (Baidu) - A powerful, interactive charting and visualization library for browser
    * [ECharts-GL](http://github.com/ecomfe/echarts-gl) - Extension pack of [echarts](http://echarts.baidu.com), which providing 3D plots, globe visualization and WebGL acceleration. 
  * [chartjs](http://www.chartjs.org) - Simple yet flexible JavaScript charting for designers & developers
  * [chartist](http://gionkunz.github.io/chartist-js) - Simple responsive charts
  * [Pixi](http://www.pixijs.com) - The HTML5 Creation Engine
  * [Toast UI](http://ui.toast.com/tui-chart) - An easy way to draw various and essential charts on your web service. 
  * [flowchart.js](http://flowchart.js.org) - Draws simple SVG flow chart diagrams from textual representation of the diagram
  * [curtains.js](http://www.martin-laxenaire.fr/libs/curtainsjs/index.html)  - Easy WebGL tool to animate images
  * [G2](http://github.com/antvis/g2) (Alibaba) - The Grammar of Graphics in JavaScript
    * [BizCharts](http://github.com/alibaba/BizCharts) - Data visualization library based G2 and React
    * [G6](http://github.com/antvis/g6) - Relational data visualization framework. 
  * [deck.gl](http://uber.github.io/deck.gl) (Uber) - A WebGL-powered framework for visual exploratory data analysis of large datasets.
* Animations
  * [micron](http://webkul.github.io/micron) - a [μ] microInteraction library built withCSS Animations and controlled by JavaScript Power
  * [Just Animate](http://just-animate.github.io) - Making animation simple
* Maps
  * [pigeon-maps](http://mariusandra.github.io/pigeon-maps) - 
* Utilities
  * [Dinero.js](http://sarahdayan.github.io/dinero.js) - Dinero.js is a library for working with monetary values in JavaScript
  * [Proppy](http://proppyjs.com) - Functional props composition for components
* Tours
  * [Driver](http://kamranahmed.info/driver) - Light-weight, no-dependency, vanilla JavaScript engine to drive user's focus across the page

### Tooling
* [WebAssembly](http://webassembly.org) - A binary instruction format for a stack-based virtual machine.
* [bit](http://bitsrc.io) - Components are building blocks. You are the architect.
* [Lerna](http://lernajs.io) - A tool for managing JavaScript projects with multiple packages. 
* [codemods](http://github.com/facebook/codemod) - Tool/library to assist you with large-scale codebase refactors that can be partially automated but still require human oversight and occasional intervention.
* [Scroll Booster](http://ilyashubin.github.io/scrollbooster) - Enjoyable content drag-to-scroll library.
* [Webpack](http://webpack.js.org) - Bundle your assets
  * [Speed Measure](http://github.com/stephencookdev/speed-measure-webpack-plugin) - See how fast (or not) your plugins and loaders are, so you can optimise your builds
  * [NOW Loader](http://github.com/pranaygp/now-loader) - Deploys the required resource to now
  * [directory-named-webpack-plugin](http://www.npmjs.com/package/directory-named-webpack-plugin) - This plugin makes it possible to control what file within directory will be treated as entry file.
* [FuseBox](http://fuse-box.org) - A bundler that does it right
* [turbolinks](http://github.com/turbolinks/turbolinks) - Turbolinks makes navigating your web application faster

### [React](http://reactjs.org)
* Awesome
  * [Awesome React](http://github.com/enaqx/awesome-react)
  * [React Components & Libraries](http://github.com/brillout/awesome-react-components)
  * [Awesome Redux (brillout)](http://github.com/brillout/awesome-redux)
  * [Awesome Redux (xgrommx)](http://github.com/xgrommx/awesome-redux)
  * [Awesome MobX](http://github.com/mobxjs/awesome-mobx)
  * [MobX Ecosystem](http://github.com/xgrommx/mobx-ecosystem)
  * [Awesome React GraphQL](http://github.com/hasura/awesome-react-graphql) - A curated collection of resources, clients and tools that make working with GraphQL and React/React Native awesome. 
* Architectures
  * [React Storefront](http://github.com/moovweb/react-storefront) - Build and deploy e-commerce progressive web apps in record time.
* State Management
  * REST
    * [tectonic](http://tonyhb.github.io/tectonic) - A declarative REST data loader for react + redux
    * [React Agent](http://www.reactagent.com) - A JS library for your database management
    * [Redux Rest Resource](http://mgcrea.github.io/redux-rest-resource) - Dead simple and ready-to-use store module for handling HTTP REST resources.
  * [Redux](http://redux.js.org)
    * [Undux](http://github.com/bcherny/undux) - Dead simple state management for React
    * [next.js](http://github.com/zeit/next.js) - Framework for server-rendered or statically-exported React apps
    * [after.js](http://github.com/jaredpalmer/after.js) - Next.js-like framework for server-rendered React apps built with React Router 4
    * [jumpsuit](http://jumpsuit.js.org) - React framework for efficiently building powerful web applications
    * [rematch](http://rematch.gitbooks.io/rematch) -  Redux best practices without the boilerplate. No more action types, action creators, switch statements or thunks.
    * [dva](http://github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework. (Inspired by elm and choo) 
    * [microcosm](http://code.viget.com/microcosm) - Microcosm is [Flux](http://facebook.github.io/flux/docs/overview.html) with actions at center stage. Write optimistic updates, cancel requests, and track changes with ease. 
    * [Lore.js](http://www.lorejs.org) - Build apps worthy of legend. Convention-driven framework for React.
  * [MobX](http://mobx.js.org)
    * [cans](http://cans.js.org) - A framework for building React / MobX application
    * [mobx-state-tree](http://github.com/mobxjs/mobx-state-tree) - Model Driven State Management
    * [parket](http://github.com/ForsakenHarmony/parket) - A library to manage application state, heavily inspired by mobx-state-tree
    * [FormState](http://github.com/formstate/formstate) - Form state so simple that you will fall in love
    * [react-remux](http://github.com/vinej/react-remux) - A flux implementation with React and Mobx
  * Tools
    * [immutable.js](http://facebook.github.io/immutable-js) (Facebook) - Immutable collections for JavaScript
    * [Immer](http://github.com/mweststrate/immer) - Create the next immutable state by mutating the current one
    * [Unstated](http://github.com/jamiebuilds/unstated) - State so simple, it goes without saying.
    * [ModulaJS](http://github.com/freewheel/modulajs) - A modularization framework to manage application states using an immutable model tree.
    * [unistore](http://github.com/developit/unistore) - 650b state container with component actions for Preact & React
    * [reworm](http://github.com/pedronauck/reworm) - The simplest way to manage state
    * [uniforms](http://github.com/vazco/uniforms) - A set of React libraries for building forms
    * [Final Form](http://github.com/final-form/react-final-form) - High performance subscription-based form state management for React.
    * [react-portalgun](http://github.com/diegomura/react-portalgun) - Lightweight portal system for React. Mega seeds included
* Development Frameworks
  * [next.js](http://github.com/zeit/next.js) - A lightweight framework for static and server‑rendered applications.
  * [next-offline](http://github.com/hanford/next-offline) - Make your Next.js application work offline using service workers via Google's workbox.
  * [DVA](http://github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework.
  * [Create React App](http://github.com/facebook/create-react-app) - Create React apps with no build configuration.
  * [rekit](http://rekit.js.org) - A toolkit for building scalable web applications with React, Redux and React-router.
  * [fusion.js](http://fusionjs.com) - A plugin-based universal web framework
* Routing
   * [Junctions](http://junctions.js.org) - A batteries-included router for React.
* UX Frameworks
  * [Ring UI](https://jetbrains.github.io/ring-ui) - JetBrains Web UI components
  * [Gestalt](http://github.com/pinterest/gestalt) (Pinterest) - Set of React UI components that enforces Pinterest’s design language. 
  * [Grommet](http://grommet.io) (Hewlett Packard) - focus on the essential experience
     * [Grommet Addons](http://github.com/grommet/grommet-addons) - Higher order components and utilities based on core grommet components.
     * [Grommet Index](http://index.grommet.io/docs/grommet-index) - Additional components beyond the base Grommet components for use in data heavy environments [*deprecated* - use Grommet Addons instead].
  * [Material UI](http://material-ui-next.com) - React components that implement Google's Material Design.
  * [Ant Design](http://ant.design) - A design system with values of Nature and Determinacy for better user experience of enterprise applications
     * [Awesome Ant Design](http://github.com/websemantics/awesome-ant-design) - A curated list of Ant Design resources and related projects. 
     * [Ant.Motion](http://github.com/ant-design/ant-motion) - Animate specification and components of Ant Design  
     * [Scaffolds](http://scaffold.ant.design) - Practical scaffolds to kickoff 
     * [UI Kitten](https://akveo.github.io/react-native-ui-kitten) - React Native framework for creating stunning cross-platform mobile applications.
  * [React Desktop](http://reactdesktop.js.org) - JavaScript library built on top of [Facebook's React](http://facebook.github.io/react) library, which aims to bring a native desktop experience to the web, featuring many macOS Sierra and Windows 10 components.
  * [Semantic UI](http://react.semantic-ui.com) - Semantic UI React is the official React integration for [Semantic UI](http://semantic-ui.com) .
  * [Blueprint](http://blueprintjs.com) (Palantir) - A React-based UI toolkit for the web
  * [React Bootstrap](http://react-bootstrap.github.io) - The most popular front-end framework, rebuilt for React.
  * [Office UI Fabric](http://developer.microsoft.com/en-us/fabric#/components) (Microsoft) - Use our design language in your own experience
  * [react-md](http://react-md.mlaursen.com) - React material design
  * [modulz](http://www.modulz.co/showcase) - An open–source collection of styles, components, patterns, resources & more
  * [Clarity Design System](http://vmware.github.io/clarity) (VMWare) - UX guidelines, HTML/CSS framework, and Angular components working together to craft exceptional experiences
  * [React Lightning Design System](http://github.com/mashmatrix/react-lightning-design-system) - Salesforce Lightning Design System components built with React
  * [RSuite](http://rsuitejs.com/en) - A suite of React components
  * [Evergreen](http://evergreen.surge.sh) - React UI Framework for the Web
  * [Elemental](http://react-elemental-docs.static.kevinlin.info) - Modern, flat UI library for React
* Themes
   * [CoreUI](http://coreui.io) - Free Bootstrap Admin Template
* Security and Authentication
   * [React Check Auth](http://github.com/hasura/react-check-auth) - Add auth protection anywhere in your react/react-native app.
* Component/CSS frameworks
  * [Aphrodite](http://github.com/Khan/aphrodite) (Khan Academy) - Framework-agnostic CSS-in-JS with support for server-side rendering, browser prefixing, and minimum CSS generation
    * [Adonis](http://github.com/imgly/adonis) - The best of [Aphrodite](http://github.com/Khan/aphrodite) and [styled-components](http://github.com/styled-components/styled-components): Named DOM elements, stylable via object literals with support for inheritance, overriding and theming while staying lightweight (28 KB / 7.6 KB gzipped)
  * [glamor](http://github.com/threepointone/glamor) - Inline CSS for React et al.
  * [glamorous](http://github.com/paypal/glamorous) (PayPal) - Maintainable CSS with React
  * [emotion](http://emotion.sh) - The Next Generation of CSS-in-JS
  * [Radium](http://formidable.com/open-source/radium) (Formidable Labs) - Set of tools to manage inline styles on React elements.
  * [rebass](http://jxnblk.com/rebass) - Library of highly-composable, primitive UI components for React, built with styled-components to keep styles isolated and reduce the need to write custom CSS in your application.
  * [cxs](http://github.com/cxs-css/cxs) - fast af css-in-js in 0.7kb
  * [Styletron](http://github.com/rtsao/styletron) - Toolkit for component-oriented styling 
  * [styled-components](http://www.styled-components.com) - Visual primitives for the component age
    * [Styled Theming](http://github.com/styled-components/styled-theming) - Create themes for your app using styled-components
    * [styled-system](http://jxnblk.com/styled-system/#styled-system) - Design system utilities for [styled-components](http://github.com/styled-components/styled-components) and other css-in-js libraries
  * [reas](http://reas.js.org) - A minimalist and highly customizable component system
  * [React Foundation](http://react.foundation) - Foundation as React components
  * [React Grid](http://devexpress.github.io/devextreme-reactive/react/grid) (DevExtreme) - Your Data Grid, Your Way
* Charts & graphics
  * [Victory](http://formidable.com/open-source/victory) (Formidable Labs) - React.js components for modular charting and data visualization
  * [recharts](http://recharts.org) - A composable charting library built on React components
  * [react-vis](http://uber.github.io/react-vis) (Uber) - A composable charting library
  * [reactivemaps](http://github.com/appbaseio/reactivemaps) - A data aware UI components library for building realtime maps
  * [echarts-for-react](http://git.hust.cc/echarts-for-react) - A very simple echarts (v3.x & v4.x) wrapper for React.
  * [react-virtualized](http://www.reactvirtualized.com) - React components for efficiently rendering large lists and tabular data.
* Animations and video
  * [Pose](http://popmotion.io/pose) - Declarative motion system for HTML, SVG, React & React Native
  * [react-spring](http://github.com/drcmda/react-spring) - Helping react-motion and animated to become best friends
  * [popmotion](http://github.com/Popmotion/popmotion) - A functional, reactive animation library
  * [react-move](http://github.com/react-tools/react-move) - Beautiful, data-driven animations for React
  * [animated](http://github.com/animatedjs/animated) - Declarative Animations Library for React and React Native
  * [react-motion](http://github.com/chenglou/react-motion) - A spring that solves your animation problems
  * [Video.js](http://videojs.com) - The player framework
* Testing
  * [react-testing-library](http://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* Utilities
  * [react-with-gesture](http://github.com/drcmda/react-with-gesture) - Little helper for component-tied mouse/touch gestures
  * [React Graceful Image](http://github.com/linasmnew/react-graceful-image) - An image component for gracefully dealing with image errors by providing optional lazy loading, optional placeholder and configurable retries on failure 
  * [MDXC](http://mdxc.reactarmory.com) - Tool to convert Markdown into React Components.
  * [Spectacle](http://formidable.com/open-source/spectacle) (Formidable Labs) - A React.js based library for creating sleek presentations.
  * [Compositor](http://compositor.io) - Modern tools for designers & developers

### [Angular](http://angular.io)
* Awesome
  * [awesome-angular](http://github.com/gdi2290/awesome-angular) - A curated list of awesome Angular resources by [@TipeIO](http://github.com/TipeIO) 
  * [awesome-angular2](http://github.com/amcdnl/awesome-angular2) - A curated list of awesome Angular 2 resources by [@AngularClass](http://github.com/AngularClass) 
  * [awesome-angular-components](http://github.com/brillout/awesome-angular-components) - Catalog of Angular 2+ Components & Libraries 
* Development frameworks
  * [Nrwl Nx](http://nrwl.io/nx) - An open source toolkit for enterprise Angular applications
* UX Frameworks
  * [Angular Material](http://material.angular.io) - Material Design components for Angular
  * [NG-ZORRO](http://github.com/NG-ZORRO/ng-zorro-antd) - An enterprise-class UI components based on Ant Design and Angular.
  * [Nebular](https://akveo.github.io/nebular) - Customizable UI Kit, Auth & Security

### [Vue.js](http://vuejs.org)
* Examples
  * [Made With Vue](http://madewithvuejs.com) - A collection of projects made with vue.js
* Development Frameworks & Boilerplates
  * [nuxt](http://nuxtjs.org) - Universal Vue.js Applications
  * [Vue Enterprise Boilerplate](http://github.com/chrisvfritz/vue-enterprise-boilerplate) - An ever-evolving, very opinionated architecture and dev environment for new Vue SPA projects using Vue CLI 3.  
  * [Charcoal](http://github.com/setholito/charcoal) - A Vue.js & Bulma Starter Kit.
* UX Frameworks
  * [Material Design for Bootstrap](http://mdbootstrap.com/vue) - Vue Bootstrap with Material Design
  * [iView](http://www.iviewui.com) - A high quality UI Toolkit based on Vue.js.
  * [Vuetify](http://vuetifyjs.com) - Material Design Component Framework.
  * [Vue Design System](http://vueds.com) - An open source tool for building Design Systems with [Vue.js](http://vuejs.org)
  * [Fish UI](http://myliang.github.io/fish-ui) - A Vue.js 2.0 UI Toolkit for Web.
  * [Buefy](https://buefy.org) - Lightweight UI components for Vue.js based on Bulma.
  * [Ant Design of Vue](https://vue.ant.design) - An enterprise-class UI design language for web applications.
* CMS
  * [VuePress](http://vuepress.vuejs.org) - Vue-powered Static Site Generator 
* Tools
  * [Vue Tour](http://pulsardev.github.io/vue-tour) - a Lightweight, Simple and Customizable tour plugin for use with Vue.js
* Native
  * [vuido](http://github.com/mimecorg/vuido) - Native desktop applications using Vue.js

### [Ember.js](http://www.emberjs.com)
* Libraries
	* [ember-table](http://opensource.addepar.com/ember-table)

### Other frameworks
* [Polymer](http://www.polymer-project.org) - A library that brings web components into the mainstream, embracing JavaScript modules and npm.
  * [Hadron](http://hadron.app) - A unified platform for designers and developers who work together towards the same goal, moving ideas forward and learning from each other along the way.
* [Preact](http://preactjs.com) - Fast 3kB alternative to React with the same modern API. 
* [Inferno](http://infernojs.org) - Insanely fast, React-like library for building high-performance user interfaces on both the client and server.
* [svelte](http://svelte.technology) - The magical disappearing UI framework
* [Glimmer.js](http://glimmerjs.com) - Fast and light-weight UI components for the web
* [Knockout](http://knockoutjs.com) - Knockout makes it easier to create rich, responsive UIs with JavaScript  
* [Mithril](http://mithril.js.org) - Modern client-side Javascript framework for building Single Page Applications.
* [Aurelia](http://aurelia.io) - JavaScript client framework for web, mobile and desktop that leverages simple conventions to empower your creativity.
* [Meteor](http://www.meteor.com) - The fastest way to build javascript apps.
* [Ionic](http://ionicframework.com) - Build amazing apps in one codebase, for any platform, with the web.
* [Stencil](http://stenciljs.com) - The magical, reusable web component compiler
* [Marko](http://markojs.com) - It's like HTML and JS had a perfect baby that grew up to be awesome

### Utilities
* [selection](http://github.com/Simonwep/selection) - A simple and lightweight library to realize visual DOM Selections.  

## .Net
### UI frameworks
* WinForms
  * [Material Skin](http://github.com/IgnaceMaes/MaterialSkin) - Theming .NET WinForms, C# or VB.Net, to Google's Material Design Principles.
* WPF
  * [Caliburn.Micro](http://caliburnmicro.com) - A small, yet powerful framework, designed for building applications across all XAML platforms.
  * [MahApps.Metro](http://mahapps.com) - Let your desktop apps shine
  * [Material Design In XAML Toolkit](http://materialdesigninxaml.net) - Easily bring beautiful desktop applications to life, using a modern and popular design language. 
  * [Avalonia](http://avaloniaui.net) - A cross platform XAML Framework for .NET Framework, .NET Core and Mono
  * [Modern UI](http://github.com/firstfloorsoftware/mui) - Modern UI for WPF
  * [Catel](http://catelproject.com) - An application development platform with the focus on MVVM (WPF, Silverlight, Windows Phone, WinRT, Xamarin.Android and Xamarin.iOS) and MVC (ASP.NET MVC).
  * [MVVM Light Toolkit](http://github.com/lbugnion/mvvmlight) - The main purpose of the toolkit is to accelerate the creation and development of MVVM applications in Xamarin.Android, Xamarin.iOS, Xamarin.Forms, Windows 10 UWP, Windows Presentation Foundation (WPF), Silverlight, Windows Phone.
  * [Okra App Framework](http://okraframework.github.io) - The app centric MVVM framework for Windows and Windows Phone
  * [Prism](http://github.com/PrismLibrary/Prism) - A framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms.
  * [WAF](http://github.com/jbe2277/waf) - Win Application Framework (WAF) is a lightweight Framework that helps you to create well structured XAML Applications.
  * [Gemini](http://documentup.com/tgjones/gemini) - WPF framework designed specifically for building IDE-like applications.
  * [AdonisUI](https://github.com/benruehl/adonis-ui) - Lightweight UI toolkit for WPF applications offering classic but enhanced windows visuals.
* Web
  * [DotVVM](http://github.com/riganti/dotvvm) - Open source MVVM framework for Web Apps.
  * [Ooui](http://github.com/praeclarum/Ooui) - A small cross-platform UI library that brings the simplicity of native UI development to the web.
  * [Blazor](http://github.com/aspnet/Blazor) - Blazor is an experimental .NET web framework using C#/Razor and HTML that runs in the browser with WebAssembly 
* Mobile/UWP
  * [Xamarin](http://visualstudio.microsoft.com/xamarin) (Microsoft) - Deliver native Android, iOS, and Windows apps with a single shared .NET code base.
  * [Uno](http://platform.uno) - Build native apps for Mobile and Web using XAML and C#.
* Other
  * [Stylet](http://github.com/canton7/stylet) - Minimal MVVM framework inspired by Caliburn Micro, with good documentation, high test coverage, and its own IoC container
  * [ReactiveUI](http://github.com/reactiveui/reactiveui) - An advanced, composable, functional reactive model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming.
  * [Eto.Forms](http://github.com/picoe/Eto) - Cross platform GUI framework for desktop and mobile applications in .NET
  * [Neutronium](http://github.com/NeutroniumCore/Neutronium) - Build .NET desktop applications using HTML, CSS and javascript
  * [mvvmcross](http://www.mvvmcross.com) - App development without compromise.
  * [QtShartp](http://github.com/ddobrev/QtSharp) - Mono/.NET bindings for Qt
  * [xwt](http://github.com/mono/xwt) - A cross-platform UI toolkit for creating desktop applications with .NET and Mono
  * [WinApi](http://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop 

### Controls
* [Krypton](http://github.com/ComponentFactory/Krypton) - Krypton WinForms components for .NET
* [Callisto](http://github.com/timheuer/callisto) - A control toolkit for Windows 8 XAML applications.
* [MVVM Dialogs](http://github.com/FantasticFiasco/mvvm-dialogs) - Framework simplifying the concept of opening dialogs from a view model when using MVVM in WPF or UWP.

### Graphics
* Imaging
  * [dot.imaging](http://github.com/dajuric/dot-imaging) - Minimalistic .NET imaging portable platform
  * [metadata-extractor.NET](http://github.com/drewnoakes/metadata-extractor-dotnet) - Extracts Exif, IPTC, XMP, ICC and other metadata from image and movie files
  * [Image Resizer](http://github.com/imazen/resizer) - The Flexible Image Server
  * [Image Processor](http://imageprocessor.org) - A .NET Library For On-The-Fly Processing Of Images.
  * [Dynamic Image](http://dynamicimage.apphb.com) - A high-performance image manipulation library for ASP.NET
  * [Image Sharp](http://sixlabors.github.io/docs/articles/ImageSharp/GettingStarted.html) - A cross-platform library for the processing of image files 
  * [Magick.NET](http://github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick
  * [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform .Net wrapper to the OpenCV image processing library.
  * [OpenCvSharp](http://github.com/shimat/opencvsharp) - .NET Framework wrapper for OpenCV 
  * [Structure.Sketching](http://github.com/JaCraig/Structure.Sketching) - Image processing library for use in .Net applications that supports .Net Core.
  * [NetVips](http://kleisauke.github.io/net-vips) - Mono/.NET binding for the [libvips image processing library](http://jcupitt.github.io/libvips).
* Bar and QR codes
  * [QRCoder](http://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation
* Charts
  * [LiveCharts](http://lvcharts.net) - Simple, flexible, interactive & powerful data visualization for .Net
  * [OxyPlot](http://www.oxyplot.org) - OxyPlot is a cross-platform plotting library for .NET.
* Raster
  * [NGraphics](http://github.com/praeclarum/NGraphics) - Cross platform library for rendering vector graphics on .NET.
* 3D
  * [Helix Toolkit](http://www.helix-toolkit.org) - 3D for .NET
  * [opentk](http://github.com/opentk/opentk) - Fast, low-level C# wrapper for OpenGL and OpenAL.
  * [veldrid](http://mellinoe.github.io/veldrid-docs) - Low-level graphics library for .NET.

### Misc.
* [TomsToolbox](http://github.com/tom-englert/TomsToolbox) - A set of core functions and classes to ease every days .Net development tasks. 

## Java

## Other

* [Mint](http://www.mint-lang.com) - A refreshing programming language for the front-end web. 

# Databases
## Relational
### Engines
* [PostgreSQL](http://www.postgresql.org)
  * [postgrest](http://postgrest.com) - Standalone web server that turns your PostgreSQL database directly into a RESTful API.
  * [pREST](http://postgres.rest) - A way to serve a RESTful APIs for any database. 
  * [zombodb](http://github.com/zombodb/zombodb) - Making Postgres and Elasticsearch work together like it's 2018
  * [migra](http://migra.djrobstep.com) - A schema comparison tool for PostgreSQL.
  * [Citus Data](http://www.citusdata.com) - Worry-Free Postgres for SaaS
  * [skor](http://github.com/hasura/skor) - Listen to postgres events and forward them as JSON payloads to a webhook
  * [Odissey](http://github.com/yandex/odyssey) - Scalable PostgreSQL connection pooler
* [MySQL](http://www.mysql.com)
  * [Orchestrator](http://github.com/github/orchestrator) - A high availability and replication management tool
* [MariaDB](http://mariadb.org)
* [CockroachDB](http://github.com/cockroachdb/cockroach) - An open source, cloud-native SQL database.

### Distributed
* [Presto](http://prestodb.io) (Facebook) - Distributed SQL query engine for big data

### Editors
* [DBeaver](http://dbeaver.jkiss.org)
* [SQL Workbench/J](http://www.sql-workbench.eu)

## Document
### Engines
* [Elastic](http://www.elastic.co)
  * [Kibana](http://www.elastic.co/products/kibana) (Elastic)
  * [Grafana](http://grafana.com)
  * [Search Guard](http://search-guard.com) - Gives you full security control over your entire Elasticsearch environment. 
* [Solr](http://lucene.apache.org/solr)
  * [Banana](http://github.com/lucidworks/banana) (LucidWorks)
* [Mongo](http://www.mongodb.com)
* [RavenDB](http://ravendb.net) - The Original Fully Transactional Open Source NoSQL Document Database.

## Columnar
### Engines
* [Cassandra](http://cassandra.apache.org) (Apache) - Manage massive amounts of data, fast, without losing sleep
* [ScyllaDB](http://www.scylladb.com) - Scale-up performance of 1,000,000 IOPS per node, scale-out to hundreds of nodes and 99% latency of <1 msec
* [Druid](http://druid.io) (Apache) - A high performance analytics data store for event-driven data.
  * [Tranquility](http://github.com/druid-io/tranquility) - Helps you send real-time event streams to Druid and handles partitioning, replication, service discovery, and schema rollover, seamlessly and without downtime.

## Graph
### Engines
* [Neo4J](http://neo4j.com)
  * [Cypher](http://neo4j.com/developer/cypher-query-language)
  * [GRANDStack](http://grandstack.io) - Build full stack graph applications with ease.
* [ArangoDB](http://www.arangodb.com)
* [OrientDB](http://orientdb.com)
* [Titan](http://titan.thinkaurelius.com)
* [Dgraph](http://dgraph.io)

### Tools
* [Giraph](http://giraph.apache.org) (Apache) - An iterative graph processing system built for high scalability

## In-memory
### Engines
#### Open source
* [Ignite](http://ignite.apache.org)

#### Commercial
* [MemSQL](http://www.memsql.com)
* [Aerospike](http://www.aerospike.com)

## Columnar
### Engines
* [Cassandra](http://cassandra.apache.org) (Apache)

## Time-series
### Engines
* [Timescale](http://www.timescale.com) - Enabling a variety of powerful time-series queries with the SQL you already know. 

## Object stores
* [Ceph](http://ceph.com) - A unified, distributed storage system designed for excellent performance, reliability and scalability.
* [Minio](http://www.minio.io) - A high performance distributed object storage server, designed for large-scale private cloud infrastructure.

## Tools
* [Debezium](http://debezium.io) - Stream changes from your databases.

# Integration
## Knowledge Base
* [Awesome Microservices](http://github.com/mfornos/awesome-microservices) - A curated list of Microservice Architecture related principles and technologies

## Data Formats
* [Avro](http://avro.apache.org) (Apache)
* [Protobuf](http://developers.google.com/protocol-buffers) (Google)

## Protocols
* [HTTP/2](http://http2.github.io)
* [gRPC](http://grpc.io)
* [IPFS](http://ipfs.io)

## Frameworks & Platforms
### Libraries
* [Camel](http://camel.apache.org) (Apache)

### Platforms
* [Spring Cloud Data Flow](http://cloud.spring.io/spring-cloud-dataflow)
* [MuleSoft](http://www.mulesoft.com)
* [WSO2](http://wso2.com)
* [Fuse](http://developers.redhat.com/products/fuse/overview)

## Streaming
### Messaging
* [Kafka](http://kafka.apache.org) (Apache) - A distributed streaming platform
	* [KSQL](http://github.com/confluentinc/ksql) (Confluent) - The streaming SQL engine for Apache Kafka
	* [Kafka Connect](http://www.confluent.io/hub) (Confluent) - Discover and share connectors and more
  * [Hermes](http://hermes.allegro.tech) - Reliable and easy to use message broker built on top of Kafka
* [Pulsar](http://pulsar.apache.org) (Yahoo) - An open-source distributed pub-sub messaging system an open-source distributed pub-sub messaging system
* [NATS](http://nats.io) - A simple, high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.
* [ActiveMQ](http://activemq.apache.org) (Apache) - The most popular and powerful open source messaging and Integration Patterns server.
* [ZeroMQ](http://zeromq.org) - An intelligent transport layer for your distributed apps
* [RabbitMQ](http://www.rabbitmq.com) (Pivotal) - An intermediary for messaging
* [Chronicle Queue](http://github.com/OpenHFT/Chronicle-Queue) - Micro second messaging that stores everything to disk

### Processing
* [Heron](http://apache.github.io/incubator-heron) (Twitter) - A realtime, distributed, fault-tolerant stream processing engine
* [Storm](http://storm.apache.org) (Apache) - A free and open source distributed realtime computation system
  * [Trident](http://storm.apache.org/releases/current/Trident-tutorial.html) (Apache) - A high-level abstraction for doing realtime computing on top of Storm
* [Samza](http://samza.apache.org) - A distributed stream processing framework
* [Flink](http://flink.apache.org) (Apache) - Stateful Computations over Data Streams
* [Apex](http://apex.apache.org) (Apache)
* [Beam](http://beam.apache.org) (Apache)
* [Prajna](http://msrccs.github.io/Prajna)
* [Mobius](http://github.com/Microsoft/Mobius)
* [MBrace](http://mbrace.io)

## Batching
### ETL
* [Talend Open Studio](http://www.talend.com/products/data-integration)
* [Kettle - Pentaho Data Integration](http://www.pentaho.com/product/data-integration)

### Scheduling & Workflow
* [Airflow](http://airflow.incubator.apache.org) (Apache) - A platform to programmatically author, schedule and monitor workflows.

### Big Data
* [Hadoop](http://hadoop.apache.org) (Apache) - A framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.
* [Spark](http://spark.apache.org) (Apache) - A unified analytics engine for large-scale data processing.

### Tools
* [NiFi](http://nifi.apache.org) (Apache)

## End-to-End Solutions
* [WSO2](http://wso2.com) - 

### BPM

### Rules
* [Drools](http://www.drools.org) (JBoss) - 

# Mobile
## Cross platform
- [Flutter](http://flutter.io) - Build beautiful native apps in record time
- [Capacitator](http://capacitor.ionicframework.com) - The native bridge for cross-platform web apps

## Android
### Profiling
* [profilo](http://facebookincubator.github.io/profilo) - 

## iOS

# Analytics
## Awesome
* [Awesome Machine Learning](http://github.com/josephmisiti/awesome-machine-learning) - A curated list of awesome Machine Learning frameworks, libraries and software.
* [Machine Learning Tutorials](http://ujjwalkarn.github.io/Machine-Learning-Tutorials) - Machine learning and deep learning tutorials, articles and other resources

## Frameworks
* [Imply](http://imply.io) - A high-performance analytics solution to store, query, and visualize operational data.

## Self Service
* [Metabase](http://www.metabase.com) - 
* [DatabaseFlow](http://databaseflow.com) -

## NLP
* [fastText](http://github.com/facebookresearch/fastText) (Facebook) - Library for fast text representation and classification.
* [sonnet](http://github.com/deepmind/sonnet) (Google) - TensorFlow-based neural network library

## Visualization
* [facets](http://pair-code.github.io/facets) (Google) - Better data leads to better models.
* [AI-Blocks](http://mrnothing.github.io/AI-Blocks) - Spend time creating models, not implementing them.
* [Observable](http://beta.observablehq.com) - Discover insights faster and communicate more effectively with interactive notebooks for data analysis, visualization, and exploration.
* [Superset](http://superset.incubator.apache.org) (Apache) - A modern, enterprise-ready business intelligence web application

## Data Sets
* [Fashion MNIST](http://github.com/zalandoresearch/fashion-mnist) - A MNIST-like fashion product database.
* [parl.ai](http://parl.ai) - A unified platform for sharing, training and evaluating dialog models across many tasks.
  

## Notebooks
* [Zepellin](http://zeppelin.apache.org)
* [jupyter](http://jupyter.org)

# DevOps
## Web servers, Reverse Proxies and Load Balancers
* [nginx](http://www.nginx.com) - Deliver modern applications at scale
* [HAProxy](http://www.haproxy.org) - The Reliable, High Performance TCP/HTTP Load Balancer
* [Apache](http://httpd.apache.org) (Apache) - Open-source HTTP server for modern operating systems including UNIX and Windows.
* [træfik](http://traefik.io) - Modern HTTP reverse proxy and load balancer made to deploy microservices with ease
* [Caddy](http://caddyserver.com) - The HTTP/2 web server with automatic HTTPS.
* [Argo Tunnel](http://developers.cloudflare.com/argo-tunnel) - Exposes applications running on your local web server, on any network with an Internet connection, without adding DNS records or configuring a firewall or router.
* [Pushpin](http://pushpin.org) - Drop-in proxy server that pins client connections open, making realtime push easy. 

## App Servers
* [Tomcat](http://tomcat.apache.org) (Apache)

## Caching
* Varnish

## Logging
* [Loki](http://github.com/grafana/loki) - Like Prometheus, but for logs.

## Services
* [Ambassador](http://www.getambassador.io) - Open Source Kubernetes-Native API Gateway built on the Envoy Proxy.
* [Envoy](http://www.envoyproxy.io) - Open source edge and service proxy, designed for cloud-native applications
* [Gloo](http://gloo.solo.io) - The hybrid app gateway.
* [Istio](http://istio.io) - Connect, secure, control, and observe services.
  * [Kiali](http://www.kiali.io) - Service mesh observability

## Serverless
* Frameworks
  * [OpenWhisk](http://openwhisk.apache.org) (IBM) - Open source serverless cloud platform.
  * [architect](http://arc.codes) - Lambda functions simplified.
  * [serverless](http://serverless.com) - Your toolkit for deploying and operating serverless architectures. 
  * [Nuclio](http://nuclio.io) - Serverless Functions for Real-Time and Data-Driven Applications
* Deployment
  * [now](http://zeit.co/now) - Realtime Global Deployments.
  * [apex](http://apex.run) - Serverless architecture.

## Infrastructure
* [Docker](http://www.docker.com) - World’s leading software containerization platform. 
  * [Swarm](http://github.com/docker/swarm) (Docker) - A Docker native clustering system
  * [Moby](http://mobyproject.org) (Docker) - An open framework to assemble specialized container systems without reinventing the wheel. 
  * [Airbag](http://github.com/Soluto/airbag) - Tiny sidecar for your docker containers
* [Terraform](http://www.terraform.io) (HashiCorp) - Write, Plan, and Create Infrastructure as Code
* [Kubernetes](http://kubernetes.io) (Google) - Automating deployment, scaling, and management of containerized applications
  * [Helm](http://helm.sh) - The Kubernetes package manager
  * [Rancher](http://rancher.com) - Enterprise management for Kubernetes. Every distro. Every cluster. Every cloud. 
  * [skaffold](http://github.com/GoogleCloudPlatform/skaffold) - Easy and Repeatable Kubernetes Development
  * [Continuous Pipe](http://continuouspipe.io) - Continuous deployment solution for your containerized applications to Kubernetes clusters
  * [Typhoon](http://typhoon.psdn.io) - Typhoon is a minimal and free Kubernetes distribution
  * [kops](http://github.com/kubernetes/kops) - Production Grade K8s Installation, Upgrades, and Management
  * [Rook](http://rook.io) - File, Block, and Object Storage Services for your Cloud-Native Environments
  * [Compose on Kubernetes](http://github.com/docker/compose-on-kubernetes) (Docker) - Deploy applications described in Compose onto Kubernetes clusters
  * [Tilt](http://tilt.build) - Makes it possible to develop all your microservices locally in Kubernetes while collaborating with your team.
  * [Kubedb](http://kubedb.com) - Run production-grade databases easily on Kubernetes
  * [kops](http://github.com/kubernetes/kops) - Production grade K8s installation, upgrades, and management
* [Mesos](http://mesos.apache.org) (Apache) - Program against your datacenter like it’s a single pool of resources 
* Tools
  * [Grail](http://eng.uber.com/grail) (Uber) - Scaling Infrastructure Management
  * [Crossplane](http://crossplane.io) - The open source multicloud control plane.
  * [osquery](http://osquery.io) (Facebook) - Performant endpoint visibility.
  * [Spinnaker](http://www.spinnaker.io) (Netflix) - Fast, safe, repeatable deployments.

## Security
* [Infection Monkey](http://www.guardicore.com/infectionmonkey) -  Unleash the Infection Monkey in your network and discover security flaws in no time.

## Performance
* [Lighthouse](http://developers.google.com/web/tools/lighthouse) (Google) -  Automated tool for improving the quality of web pages. 
* [Vegeta](http://github.com/tsenart/vegeta) - A versatile HTTP load testing tool 

## Continuous Integration
* [Jenkins X](https://jenkins-x.io) - A CI/CD solution for modern cloud applications on Kubernetes

## Continuous Delivery
* [Buck](http://buckbuild.com) (Facebook) - A high-performance build tool

## Configuration
### Linux
- [Cockpit](http://cockpit-project.org) - Server manager that makes it easy to administer your GNU/Linux servers via a web browser.

### Windows

## Tools
### CLI
* [jaggr](http://github.com/rs/jaggr) - JSON Aggregation CLI
* [jplot](http://github.com/rs/jplot) - iTerm2 expvar/JSON monitoring tool

### Windows Consoles
* [Cmder](http://cmder.net)
* [ConEmu](http://conemu.github.io)
* [Babun](http://babun.github.io)
* [Clink](http://mridgers.github.io/clink)

### Remote Desktop clients
* [Remote Desktop Manager](http://remotedesktopmanager.com/home/download)

### Chat
* [Rocket.Chat](http://rocket.chat)

# Programming
## Languages
* [Crystal](http://crystal-lang.org)
* [Lua](http://www.lua.org)
* [Rust](http://www.rust-lang.org/en-US)
* [Python](http://www.python.org)
* [Dart](http://www.dartlang.org)
	* Awesome
		* [Dart](http://github.com/yissachar/awesome-dart)
* [Haskell](http://www.haskell.org)
* [Erlang](http://www.erlang.org)
	* [Elixir](http://elixir-lang.org)
	* [Phoenix](http://phoenixframework.org)
	* Awesome
		* [Erlang](http://github.com/drobakowski/awesome-erlang)
		* [Elixir](http://github.com/h4cc/awesome-elixir)

## Data Structures & Algorithms
* [Roaring Bitmaps](http://roaringbitmap.org) - A better compressed bitset

## People
* Javascript
	* [Dan Abramov](http://)
	* [Pete Hunt](http://)
	* [Sindre Sorhus](http://)
* .Net
	* [Jon Skeet's coding blog](http://codeblog.jonskeet.uk) (Jon Skeet)
	* [Code, code and more code](http://blog.marcgravell.com) (Marc Gravel)
	* [Fabulous Adventures in Coding](http://ericlippert.com) (Eric Lipert)

## Software Engineering
* Patterns
	* [Martin Fowler](http://martinfowler.com)
	* [Enterprise Integration Patterns](http://www.enterpriseintegrationpatterns.com)
* Processes
	* [CMMI](http://cmmiinstitute.com)
* Architecture
	* [TOGAF](http://www.opengroup.org/subjectareas/enterprise/togaf) (OpenGroup)
	* [Zachman](http://www.zachman.com)
* Reference Models
	* [SCOR - Supply Chain Reference Model](http://www.apics.org/apics-for-business/frameworks/scor) (APICS)
	* [CAUDIT - Higher Education Reference Architecture](http://www.caudit.edu.au/EA-Framework)

# Tools & Services

## Design
* [Sketch](http://www.sketchapp.com) - 
  * [Cabana](http://cabanadesignsystem.com) - Design System for Sketch
* [Figma](http://www.figma.com) - 
* [lunacy](http://icons8.com/lunacy) - 
* [Top 20 Design Systems](http://blog.prototypr.io/top-20-design-systems-7bf0963318ce)

## Content
* Resources
  * [Cool Backgrounds](http://coolbackgrounds.io) - A collection of tools to create compelling, colorful images for blogs, social media, and websites.
* Stock Photos
  * [Burst](http://burst.shopify.com) - Free stock photos for websites and commercial use
  * [Unsplash](http://unsplash.com) - Beautiful, free photos.
* Symbols
  * [HTML Symsols](http://www.toptal.com/designers/htmlarrows/symbols) - HTML Currency Symbols, Currency Entities and ASCII Currency Character Code Reference
  * [Orion](http://orioniconlibrary.com) - Free SVG vector icons

## Spreadsheets
* [Google Sheets](http://www.google.com/sheets)

## CMS
* [Publii](http://getpublii.com) - Make an extremely safe, fast and stylish static blog website in minutes.

## CRM
* 

## HR
* [teamdeck](http://teamdeck.io)

## Issue Management
* [JIRA](http://www.atlassian.com/jira)

## Invoicing
* [Elorus](http://www.elorus.com)

## Communications
* [Slack](http://slack.com) - Where Work Happens
* [Rocket.Chat](http://rocket.chat) - The leading free open source team chat Slack alternative. 
* [Intercom](http://) - Catch, convert and keep more customers
* [Indemandly](http://indemandly.com) - Simple, powerful, & versatile contact tool that you can stick on your website and social media. 

## Security
* [Gpg4win](http://www.gpg4win.org) - A secure solution
* [Keybase](http://keybase.io) - Security app for mobile phones and computers

## Misc.
* [For the Badge](http://forthebadge.com) - Badges for badges' sake.
