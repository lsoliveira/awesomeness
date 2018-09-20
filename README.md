# Overview
_Awesomeness_ is a comprehensive list of technical resources related to IT systems architecture, design and implementation.

# Backend

## .Net
### Distributed systems
* Actor based
  * [Orleans](https://dotnet.github.io/orleans) (Microsoft) - A straightforward approach to building distributed, high-scale applications in .NET.
  * [Akka.Net](https://getakka.net) - Build powerful concurrent & distributed applications more easily
    * [Lighthouse](https://github.com/petabridge/lighthouse) - A simple service discovery platform for Akka.Cluster
  * [Orleankka](http://orleanscontrib.github.io/Orleankka) - Functional extension for Microsoft Orleans framework 
  * [Proto.Actor](http://proto.actor) - Ultra fast distributed actors for Go, C# and Java/Kotlin
* Event Driven
  * [Cirqus](https://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework
  * [Akkatecture](https://akkatecture.net/) - cqrs and event sourcing for dotnet core 
  * [NEventStore](http://neventstore.org) - A persistence agnostic Event Store for .NET
  * [EventFlow](http://docs.geteventflow.net) - EventFlow is a basic CQRS+ES framework designed to be easy to use
  * [Brighter](https://www.goparamore.io) - Command Processor & Dispatcher implementation that can be used as a lightweight library in other projects. 
  * [Its.CQRS](https://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
  * [Aggregates.NET](https://github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServiceBus and GetEventStore
  * [NES](https://github.com/elliotritchie/NES) - Lightweight framework that helps you build domain models when you're doing event sourcing.
  * [Xer.Cqrs](https://github.com/XerProjects/Xer.Cqrs) - A simple CQRS library
  * [CQRSlite](https://github.com/gautema/CQRSlite) - A lightweight framework for helping writing CQRS and Eventsourcing applications in C#
* Queueing
  * [RawRabbit](https://github.com/pardahlman/RawRabbit) - A modern .NET framework for communication over RabbitMq
* Service Bus
  * [Mass Transit](http://masstransit-project.com) - Free, open source, lightweight message bus for creating distributed applications using the .NET framework.
  * [NServiceBus](https://particular.net/nservicebus) - The most developer-friendly service bus for .NET
  * [Zebus](https://github.com/Abc-Arbitrage/Zebus) - A lightweight Peer to Peer Service Bus
  * [Obvs](http://christopherread.github.io/Obvs) - An observable µServiceBus .NET library that wraps the complexities of your particular message transport in simple Rx based interfaces. Supported transports include: ActiveMQ, RabbitMQ, NetMQ, EventStore, and Kafka.
* Utilities
  * [Foundatio](https://github.com/FoundatioFx/Foundatio) - Pluggable foundation blocks for building distributed apps.
  * [Projac](https://github.com/BitTacklr/Projac) - A set of .NET projection libraries
### Services
* REST
  * [SaasKit](https://github.com/saaskit/saaskit) - A developer toolkit for building SaaS applications.
  * [refit](https://paulcbetts.github.io/refit) - The automatic type-safe REST library for .NET Core, Xamarin and .NET.
  * [RestSharp](http://restsharp.org) - Simple REST and HTTP API Client for .NET.
  * [RestEase](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library for .NET Standard 1.1 and .NET Framework 4.5 and higher, which is simple and customisable.
  * [RestLess](https://github.com/letsar/RestLess) - The automatic type-safe-reflectionless REST API client library for .Net Standard.
  * [HttpClientGoodies.NET](https://github.com/jeffijoe/httpclientgoodies.net) - Useful utilities for the .NET HttpClient.
  * [autorest](https://github.com/Azure/autorest) - OpenAPI (f.k.a Swagger) Specification code generator.
  * [Halcyon](https://github.com/visualeyes/halcyon) - A HAL implementation for ASP.NET.
  * [JSON API .Net Core](https://github.com/json-api-dotnet/JsonApiDotNetCore) - A [{ json:api }](http://jsonapi.org/) web application framework.
  * [NetCoreStack Flying Proxy](https://github.com/NetCoreStack/Proxy) - The type-safe REST library for .NET Standard 2.0.
  * [NSwag](https://github.com/RSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, Web API and TypeScript.
  * [OData Web API](https://github.com/OData/WebApi): A server library built upon ODataLib and WebApi.
  * [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger tools for documenting API's built on ASP.NET Core.
  * [RService.IO](https://github.com/Stoom/RService.IO) - Light weight REST service framework for ASP.NET Core.
  * [OpenRasta](http://openrasta.org) - Open-source .NET framework for building everything web, from web sites to RESTful APIs.
* Web Sockets
  * [Fleck](https://github.com/statianzo/Fleck) - C# Websocket Implementation
  * [SignalR](http://signalr.net) - Incredibly simple real-time web for .NET
  * [WampSharp](http://wampsharp.net) - A C# implementation of WAMP (The Web Application Messaging Protocol)
  * [SuperSocket](https://github.com/kerryjiang/SuperSocket) - SuperSocket is a light weight, cross platform and extensible socket server application framework.
  * [websocket-sharp](http://sta.github.io/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
  * [NetGain](https://github.com/StackExchange/NetGain) (StackExchange) - A high performance websocket server library powering Stack Overflow.
* GraphQL
  * [GraphiQL.NET](https://github.com/JosephWoodward/graphiql-dotnet) - GraphiQL middleware for ASP.NET Core
  * [GraphQL.NET](https://github.com/mkmarek/graphql-dotnetcore) - Library for creating GraphQL servers with .NET core.
  * [GraphQL for .NET](https://github.com/graphql-dotnet/graphql-dotnet) - This is an implementation of [Facebook's GraphQL](https://github.com/facebook/graphql) in .NET.
  * [parser](https://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET
  * [GraphQL Conventions Library for .NET](https://github.com/graphql-dotnet/conventions) - GraphQL Conventions Library for .NET
  * [GraphQl.AspNetCore](https://github.com/JuergenGutsch/graphql-aspnetcore) - ASP.NET Core MiddleWare to create a GraphQL end-point
* API
  * [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul lib
  * [Ocelot](http://threemammals.com/ocelot) - Open Source .NET Core API Gateway
* Middleware 
  * [Polly](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.
  * [steeltoe](https://steeltoe.i/) (Pivotal) - Open source project that enables .NET developers to implement industry standard best practices when building resilient microservices for the cloud.
  * [Nancy](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono.
  * [peasy](https://github.com/peasy/Peasy.NET) - A middle tier micro-framework for .NET
  * [LightNode](http://neuecc.github.io/LightNode) - Micro RPC/REST Framework built on OWIN
  * [Nelibur](https://github.com/Nelibur/Nelibur) - Message based webservice framework on the pure WCF.
  * [Xer.Cqrs](https://github.com/XerProjects/Xer.Cqrs) - A simple CQRS library. 
  * [CLSA.NET](http://cslanet.com) - Software development framework that helps you build a reusable, maintainable object-oriented business layer for your app.
  * [CAP](https://github.com/dotnetcore/CAP) - CAP is a library based on .Net standard, which is a solution to deal with distributed transactions, also has the function of EventBus, it is lightweight, easy to use, and efficiently.
  * [RestBus](https://github.com/tenor/RestBus) - Easy, Service Oriented, Asynchronous Messaging and Queueing for .NET
  * [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET
  * [Warewolf](https://github.com/Warewolf-ESB/Warewolf) - Effortless Microservice Design and Integration. This repository includes the code-base for the Warewolf Studio and Server.
  * [DotNetty](https://github.com/Azure/DotNetty) - Port of [Netty](https://github.com/netty/netty), asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.
  * [Halibut](https://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
  * [microdot](https://github.com/gigya/microdot) - An open source .NET microservices framework
  * [EmbedIO](https://unosquare.github.io/embedio) - A tiny, cross-platform, module based, MIT-licensed web server for .NET Framework and .NET Core
* Network
  * [edtFTPnet](https://enterprisedt.com/products/edtftpnet) - The popular free .NET FTP library
  * [FluentFTP](https://github.com/robinrodricks/FluentFTP) - An FTP and FTPS client for .NET & .NET Standard, optimized for speed.
  * [SSH.NET](https://github.com/sshnet/SSH.NET) - Secure Shell (SSH) library for .NET, optimized for parallelism.
  * [Ether.Network](https://github.com/Eastrall/Ether.Network) - Simple and fast C# networking library. Compatible with .NET Standard 1.3 and 2.0
### Data Access
* ORM
  * [Dapper](https://github.com/StackExchange/Dapper) (StackExchange)
  * [NReco](https://www.nrecosite.com/dalc_net.aspx) - CRUD operations, dynamic queries, SQL generation in C#
  * [DbExtensions](http://maxtoroq.github.io/DbExtensions) - Data-access framework with a strong focus on query composition, granularity and code aesthetics. 
  * [Insight.Database](https://github.com/jonwagner/Insight.Database) - Fast, lightweight .NET micro-ORM
  * [LimeBean](https://nick-lucas.github.io/LimeBean) - Simple and concise API for accessing ADO.NET data sources. 
  * [Simple.Data](https://github.com/markrendle/Simple.Data) - A light-weight, dynamic data access component for C# 4.0
* Persistence
  * [marten](http://jasperfx.github.io/marten) - Polyglot Persistence for .NET Systems using the Rock Solid PostgreSQL Database
  * [ReactiveETL](https://github.com/madhon/ReactiveETL) - Rewrite of Rhino ETL using the reactive extensions for .Net
  * [SqlKata](https://sqlkata.com) - The powerful C# sql query builder
* Caching
  * [Akavache](https://github.com/akavache/Akavache) - An asynchronous, persistent key-value store.
* Full text
  * [NEST](https://github.com/elastic/elasticsearch-net) - Elasticsearch.Net & NEST
  * [SimMetrics.NET](https://github.com/StefH/SimMetrics.Net) - Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman).
* Migrations
  * [Fluent Migrator](https://github.com/fluentmigrator/fluentmigrator) - Fluent migrations framework for .NET
  * [DbUp](http://dbup.github.io) - DbUp is a .NET library that helps you to deploy changes to SQL Server databases.
### Scheduling & Job Management
* Scheduling
  * [Hangfire](https://www.hangfire.io) - An easy way to perform background processing in .NET and .NET Core applications. No Windows Service or separate process required.
  * [Quartz.NET](https://www.quartz-scheduler.net) - Full-featured, open source job scheduling system that can be used from smallest apps to large scale enterprise systems.
  * [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* State Machines & Workflow
  * [Stateless](https://github.com/dotnet-state-machine/stateless) - A simple library for creating state machines in C# code
  * [Automatonymous](https://github.com/MassTransit/Automatonymous) - A state machine library for .Net - 100% code - No doodleware
  * [workflow-core](https://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard
  * [Core WF](https://github.com/dmetzgar/corewf) - A port of the Windows Workflow Foundation (WF) runtime to the .NET Standard.
  * [Durable Task Framework](https://github.com/Azure/durabletask) (Microsoft) - Write long running persistent workflows in C# using the async/await capabilities.
  * [State Machine](http://www.appccelerate.com/statemachine.html) - Our applications are full of state machines. Enabled and disabled UI elements, abstractions of devices and business logic. Implementing these state machines with the state pattern is overly complicated. Therefore, we implemented a state machine component that allows implementing a state machine as a single class. This reduces complexity and needed effort dramatically. See for yourself.
  * [LiquidState](https://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET 
* Misc.
  * [NCronTab](https://github.com/atifaziz/NCrontab) - Crontab for .NET
### IoC
* [StructureMap](https://github.com/structuremap/structuremap) - A Dependency Injection/Inversion of Control tool for .NET.
* [Autofac](https://autofac.org) - Autofac is an addictive Inversion of Control container for .NET Core, ASP.NET Core, .NET 4.5.1+, Universal Windows apps, and more.
* [Ninject](http://www.ninject.org) - Open source dependency injector for .NET
* [Simple Injector](https://simpleinjector.org) - Easy-to-use Dependency Injection (DI) library for .NET 4+ that supports Silverlight, Windows Phone, Windows 8 including Universal apps and Mono. 
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning and decoration extensions for Microsoft.Extensions.DependencyInjection    
### Deployment
* [WiX](http://wixtoolset.org) - The most powerful set of tools available to create your windows installation experience.
* [Wax](https://github.com/tom-englert/Wax) - An interactive editor for WiX setup projects.
* [Topshelf](http://topshelf-project.com) - Put Your Apps on the Topshelf.
* [Squirrel](https://github.com/squirrel/squirrel.windows) - An installation and update framework for Windows desktop apps.
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - Helper classes to set up and run as windows services directly on .net core. A ServiceBase alternative.
* [Catlight](https://catlight.io) - Notifier for developers
### Performance & Monitoring
* [BenchmarkDotNet](http://benchmarkdotnet.org) - Powerful .NET library for benchmarking.
* [AppMetrics](https://www.app-metrics.io) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application. 
* [Metrics.NET](https://github.com/Recognos/Metrics.NET) - The Metrics.NET library provides a way of instrumenting applications with custom metrics (timers, histograms, counters etc) that can be reported in various ways and can provide insights on what is happening inside a running application.
* [Warden](https://github.com/warden-stack/Warden) - Define "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.  
* [NBench](https://github.com/petabridge/NBench) - Cross-platform performance benchmarking and testing framework for .NET applications.
* [Prefix](https://stackify.com/prefix) - Understand what your code is doing and find bugs you didn’t even know existed. 
### Algorithms & Data Structures
* Algorithms
  * [C# Algorithms](https://github.com/aalhour/C-Sharp-Algorithms) - A C# plug-and-play class-library project of standard Data Structures and Algorithms.
  * [Algorithmia](https://github.com/SolutionsDesign/Algorithmia) - Algorithm and data-structure library for .NET 4.5.2+/Netstandard 2.0+.
  * [CodeJam](https://github.com/rsdn/CodeJam) - Set of handy reusable .NET components that can simplify your daily work and save your time when you copy and paste your favorite helper methods and classes from one project to another.
* Data structures
  * [C5](https://github.com/sestoft/C5) - C5 generic collection library for C#/.NET.
  * [Optional](https://github.com/nlkl/Optional) - A robust option type for C#
  * [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
  * [Shielded](https://github.com/jbakic/Shielded) - A strict and mostly lock-free Software Transactional Memory (STM) for .NET
  * [ByteSize](https://github.com/omar/ByteSize) - Utility class that makes byte size representation in code easier by removing ambiguity of the value being represented.
  * [Disruptor.net](https://github.com/disruptor-net/Disruptor-net) - Port of LMAX Disruptor to .NET
* Functional programming
  * [Functional Extensions for C#](https://github.com/vkhorikov/CSharpFunctionalExtensions) - This library helps write code in more functional way.
  * [LanguageExt](https://github.com/louthy/language-ext) - C# functional language extensions - a base class library for functional programming
* Reactive programming
  * [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The Reactive Extensions for .NET
  * [Reactive Streams .NET#](https://github.com/reactive-streams/reactive-streams-dotnet) - Reactive Streams for .NET
  * [Qactive](https://github.com/RxDave/Qactive) - A reactive queryable observable framework.
  * [sodium](http://sodium.nz/) - A functional reactive programming library for multiple programming languages.
  * [Dynamic Data](https://github.com/RolandPheasant/DynamicData) - Reactive collections based on Rx.Net.
  * [Streams](http://nessos.github.io/Streams) - A lightweight F#/C# library for efficient functional-style pipelines on streams of data. 
* Mapping 
  * [AutoMapper](https://github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET.
  * [TinyMapper](https://github.com/TinyMapper/TinyMapper) - A quick object-object mapper for .NET.
  * [ExpressMapper](https://github.com/fluentsprings/ExpressMapper) - Mapping .Net types.
  * [AgileMapper](https://github.com/agileobjects/AgileMapper) - A zero-configuration, highly-configurable object-object mapper with viewable execution plans.
  * [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types
* Patterns
  * [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported
  * [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET 
* Units
  * [UnitsNet](https://github.com/angularsen/UnitsNet) - Makes life working with units of measurement just a little bit better.
  * [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities * [NodaMoney](https://github.com/remyvd/NodaMoney) - NodaMoney provides a library that treats Money as a first class citizen and handles all the ugly bits like currencies and formatting.
  * [NodaTime](https://nodatime.org) - A better date and time API for .NET
  * [DateTimeExtensions](https://github.com/joaomatossilva/DateTimeExtensions) - This project is a merge of several common DateTime operations in the form of extensions to System.DateTime, including natural date difference text (precise and human rounded), holidays and working days calculations on several culture locales.
  * [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods
  * [UnitConversion](https://github.com/gkampolis/UnitConversion) - Expansible Unit Conversion Library for .Net Core and .Net Framework
  * [DeviceId](https://github.com/MatthewKing/DeviceId) - A simple library providing functionality to generate a 'device ID' that can be used to uniquely identify a computer.
* Extensions & LINQ
  * [ExtraLINQ](https://github.com/mariusschulz/ExtraLINQ) - ExtraLINQ provides a set of extension methods for various .NET sequence types.
  * [MoreLINQ](https://github.com/morelinq/MoreLINQ) - Extensions to LINQ to Objects.
  * [Mono.Linq.Expressions](https://github.com/jbevain/mono.linq.expressions) - Helper library to complement the System.Linq.Expressions namespace.
  * [Z.ExtensionMethods](https://github.com/zzzprojects/Z.ExtensionMethods) - Enhance the .NET Framework with over 1000 extension methods.
  * [Extend](https://github.com/DaveSenn/Extend) - Extension methods for .Net.
  * [dotNetExt](https://github.com/crpietschmann/dotnetext) - .NET Extension Method Library
  * [Relinq](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
  * [LinqOptimizer](http://nessos.github.io/LinqOptimizer) - An automatic query optimizer-compiler for Sequential and Parallel LINQ
  * [Type Convert](https://github.com/deniszykov/typeconvert) - C# utilities for convertion between types, type construction and inspection 
### Geolocation
* [OsmSharp](http://www.osmsharp.com) - C# library to work with OpenStreetMap (OSM) data.
* [NetTopologySuite](https://github.com/NetTopologySuite/NetTopologySuite) - A .NET GIS solution that is fast and reliable for the .NET platform.
* [SharpMap](https://github.com/SharpMap/SharpMap) - An easy-to-use mapping library for use in web and desktop applications.
* [GeoJSON.NET](https://github.com/GeoJSON-Net/GeoJSON.Net) - .Net library for GeoJSON types & corresponding Json.Net (de)serializers
### Math & AI
* Math
  * [Math.NET](https://www.mathdotnet.com) - Open-source initiative to build and maintain toolkits covering fundamental mathematics, targetting advanced but also every day needs of .Net developers.
  * [Microsoft Automatic Graph Layout](https://github.com/Microsoft/automatic-graph-layout) (Microsoft) - A set of tools for graph layout and viewing.
  * [ALGLIB](http://www.alglib.net) - Cross-platform numerical analysis and data processing library.
  * [autodiff](https://github.com/alexshtf/autodiff) - A .NET library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions.
  * [GeometRi](https://github.com/RiSearcher/GeometRi) - Simple and lightweight computational geometry library for .Net
  * [MathExtensions)](https://github.com/TommasoScalici/MathExtensions) - Library for .NET that aims to extend the basic but yet incomplete System.Math, with simple and useful extensions methods regarding various mathematical domains, like methods for combinatorics, sequence analysis, generation and manipulation, random extractions, etc.
* Frameworks
  * [AccordFramework.NET](http://accord-framework.net) - Machine learning made in a minute 
  * [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - TensorFlow API for .NET languages
  * [AForge.NET](http://www.aforgenet.com/framework) - open source C# framework designed for developers and researchers in the fields of Computer Vision and Artificial Intelligence.
  * [Infer.NET](http://infernet.azurewebsites.net) (Microsoft) - A framework for running Bayesian inference in graphical models.
  * [numl](http://numl.net) - a general purpose machine learning framework
  * [GeneticSharp](https://github.com/giacomelli/GeneticSharp) - Fast, extensible, multi-platform and multithreading C# Genetic Algorithm library that simplifies the development of applications using Genetic Algorithms (GAs).   
* Data
  * [FsLab](https://fslab.org) - Data science tools: Professional, powerful & cross-platform
  * [Spreads](https://github.com/Spreads/Spreads) - Series and Panels for Real-time and Exploratory Analysis of Data Streams
  * [Deedle](http://bluemountaincapital.github.io/Deedle) - Exploratory data library for .NET
  * [SIML](https://simlbot.com) - Synthetic Intelligence Markup Language
### Testing
* Test frameworks
  * [nUnit](http://nunit.org) - unit-testing framework for all .Net languages.
  * [xUnit](https://xunit.github.io) - Free, open source, community-focused unit testing tool for the .NET Framework.
  * [MSTest](https://msdn.microsoft.com/en-us/library/hh694602.aspx) (Microsoft)
  * [Fixie](http://fixie.github.io) - Conventional Testing for .NET
* Assertions
  * [Shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be!
  * [FluentAssertions](https://fluentassertions.com) - Fluent API for asserting the results of unit tests that targets .NET Framework 4.5, 4.7, .NET Standard 1.3, 1.6 and 2.0.
  * [Power Assert .NET](https://github.com/PowerAssert/PowerAssert.Net) - Readable, Writable Test Assertions for .NET
* Data generation
  * [Bogus](https://github.com/bchavez/Bogus) - A simple and sane fake data generator for C#, F#, and VB.NET. Based on and ported from the famed faker.js. 
  * [Fibber](https://github.com/Schandlich/Fibber) - An indiscriminate data generator that will generate random data for all properties in a given class based on the property's type vs. its name.
  * [Rant](http://berkin.me/rant) - Free, all-purpose procedural text generation language developed for .NET.
  * [NBuilder](https://github.com/nbuilder/nbuilder) - Rapid generation of test objects in .NET
* Mocking
  * [Rhino Mocks](https://hibernatingrhinos.com/oss/rhino-mocks) - Dynamic mock object framework for .NET
  * [Moq](https://github.com/moq/moq4) - The most popular and friendly mocking framework for .NET
  * [NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking libraries.
  * [FakeItEasy](https://fakeiteasy.github.io) - A .Net dynamic fake framework for creating all types of fake objects, mocks, stubs etc.
  * [Stubbery](https://markvincze.github.io/Stubbery) - Simple library for creating and running Api stubs in .NET.
* BDD
  * [SpecFlow](http://specflow.org) - Cucumber for .NET. The open source solution trusted by .NET devs around the world.
  * [xbehave](http://xbehave.github.io) - xUnit.net extension for describing your tests using natural language.
  * [SpecsFor](https://github.com/MattHoneycutt/SpecsFor) - Light-weight Behavior-Driven Development framework that focuses on ease of use for *developers* by minimizing testing friction.
  * [NFluent](https://github.com/tpierrain/NFluent) - Smooth your .NET TDD experience with NFluent!
  * [Machine.Specifications](https://github.com/machine/machine.specifications) - Context/Specification framework geared towards removing language noise and simplifying tests.
  * [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - BDDfy is the simplest BDD framework EVER!
  * [Storyteller](http://storyteller.github.io) - Solutions for creating robust, human readable acceptance tests for your .Net or CoreCLR system and a means to create "living" technical documentation.
* Automation
  * [Selenium](https://www.seleniumhq.org) - Selenium automates browsers.
  * [Atata](https://atata-framework.github.io) - C#/.NET automated web testing full featured framework
  * [TestStack.White](https://github.com/TestStack/White) -  Automating rich client applications based on Win32, WinForms, WPF, Silverlight and SWT (Java) platforms.
  * [Managed Windows API](http://mwinapi.sourceforge.net/) - A collection of .NET components that wrap PInvoke calls to access native API by managed code.
  * [Effort](http://entityframework-effort.net/) - **E**ntity **F**ramework **F**ake **O**bjectContext **R**ealization **T**ool. It is a powerful tool that enables a convenient way to create automated tests for Entity Framework based applications.
* Load testing
  * [Netling](https://github.com/hallatore/Netling) - Netling is a load tester client for easy web testing.
* Misc.
  * [Scientist.net](https://github.com/github/Scientist.net) -  A .NET library for carefully refactoring critical paths.
  * [AutoFixture](https://github.com/AutoFixture/AutoFixture) - AutoFixture is an open source library for .NET designed to minimize the 'Arrange' phase of your unit tests in order to maximize maintainability.
  * [Papercut](https://github.com/ChangemakerStudios/Papercut) - Papercut Simple Desktop SMTP Server
  * [.NET Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) - Fake JSON Server is a Fake REST API that can be used as a Back End for prototyping or as a template for a CRUD Back End.
### Caching
*  [CacheManager](https://github.com/MichaCo/CacheManager) - CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.
*  [Cashew](https://github.com/joakimskoog/Cashew) - A simple and elegant yet powerful HTTP client cache for .NET
*  [LazyCache](https://github.com/alastairtree/LazyCache) - An easy to use thread safe generics based in memory caching service with a simple developer friendly API for C#.
### Framework specifics
- Languages & Compilers
  - [Irony](https://github.com/IronyProject/Irony) - .NET Language Implementation Kit.
  - [Flee](https://github.com/mparlak/Flee) - Fast Lightweight Expression Evaluator.
  - [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.
  - [Pidgin](https://github.com/benjamin-hodgson/Pidgin) (StackExchange) - A lightweight, fast and flexible parsing library for C#.
* Serialization
  * [Hyperion](https://github.com/akkadotnet/Hyperion) -  Polymorphic serialization for .NET
  * [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil
  * [Wire](https://github.com/rogeralsing/Wire) - A high performance polymorphic serializer for the .NET framework.
  * [Migrant](https://github.com/antmicro/Migrant) - Fast and flexible serialization framework usable on undecorated classes.
  * [Utf8Json](https://github.com/neuecc/Utf8Json) - Fast JSON Serializer for C#
  * [protobuf](https://silentorbit.com/protobuf) - ProtoBuf is a Google Protocol Buffers implementation by generating custom C# code for your .proto specifications.
  * [protobuf-net](https://github.com/mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET
  * [Newtonsoft.Json](https://www.newtonsoft.com/json) - Popular high-performance JSON framework for .NET
  * [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Objects turned into strongly typed C# POCO classes for use in .NET.
  * [EDI.NET](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS formats.
* Reflection
  * [Fasterflect](https://github.com/buunguyen/fasterflect) - .NET Reflection Made Fast and Simple.
  * [Fast-member](https://code.google.com/archive/p/fast-member) - .NET reflection is slow... well, kinda slow.
  * [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport) - Alternative approach to your usual P/Invoke!
  * [Bond](https://github.com/Microsoft/bond) (Microsoft) - Cross-platform framework for working with schematized data. 
* Code Generation
  * [Sigil](https://github.com/kevin-montrose/Sigil) - A fail-fast validating helper for .NET CIL generation
  * [Cecil](http://cecil.pe) - Cecil is a library to inspect, modify and generate .NET programs and libraries.
  * [Testura.Code](https://github.com/Testura/Testura.Code) - Wrapper around the Roslyn API and used for generation, saving and compiling C# code.
* AOP
  * [AspectCore](https://github.com/dotnetcore/AspectCore-Framework) - AspectCore is an AOP-based cross platform framework for .NET Standard.
  * [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies
### Report & PDF Generation
* File handling
  * [FileHelpers](https://www.filehelpers.net) - Import or export data from fixed length or delimited records in files, strings or streams.
  * [FlatFiles](https://github.com/jehugaleahsa/FlatFiles) - Reads and writes CSV, fixed-length and other flat file formats with a focus on schema definition, configuration and speed.
  * [FlatMapper](https://github.com/joaomatossilva/FlatMapper) - FlatMapper is a library to import and export data from and to plain text files.
  * [CsvHelper](http://joshclose.github.io/CsvHelper) - A library for reading and writing CSV files.
* Office integration
  * [NPOI](https://github.com/tonyqus/npoi) - .NET library that can read/write Office formats without Microsoft Office installed.
  * [Open XML SDK](https://github.com/officedev/open-xml-sdk) (Microsoft) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents. 
  * [DocX](https://github.com/xceedsoftware/DocX) - Fast and easy to use .NET library that creates or modifies Microsoft Word files without installing Word.
  * [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files
  * [EPPlus](https://github.com/JanKallman/EPPlus) - Create advanced Excel spreadsheets using .NET
  * [ClosedXML](https://github.com/ClosedXML/ClosedXML) - Makes it easier for developers to create Excel 2007+ (.xlsx, .xlsm, etc) files.
* PDF generation
  * [PDFSharp](http://www.pdfsharp.net) - Open Source .NET library that easily creates and processes PDF documents on the fly from any .NET language.
  * [iTextSharp](https://github.com/itext/itextsharp) - Easy PDF generation and manipulation for Java and .NET developers.
  * [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - Code first reporting engine, which is built on top of the [iTextSharp.LGPLv2.Core](https://github.com/VahidN/iTextSharp.LGPLv2.Core) and [EPPlus.Core](https://github.com/VahidN/EPPlus.Core) libraries.
* Markdown
  * [Markdig](https://github.com/lunet-io/markdig) - A fast, powerful, CommonMark compliant, extensible Markdown processor for .NET
  * [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - Implementation of CommonMark specification in C# for converting Markdown documents to HTML. 
  * [MarkdownSharp](https://github.com/StackExchange/MarkdownSharp) (StackExchange) - Open source C# implementation of Markdown processor, used by Stack Overflow.
* Reports
  * [DoddleReport](https://github.com/matthidinger/DoddleReport) - Generate custom reports (PDF, Excel, etc) from any IEnumerable datasource.
### Email
* [Postal](http://aboutcode.net/postal) - Create email using ASP.NET MVC views
* [MailKit](https://github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP. 
* [MailBody](https://doxakis.github.io/MailBody) - Create transactional email with a fluent interface (.net)
* [RazorMailer](https://github.com/jonleigh/RazorMailer) - A lightweight framework for sending emails from any .NET platform using Razor templates.
### Logging
* [Logary](https://logary.github.io) - High performance, multi-target logging, metric, tracing and health-check library for mono and .Net.
* [NLog](https://github.com/nlog/NLog) - Advanced and Structured Logging for Various .NET Platforms 
* [Elmah](https://elmah.github.io) - Application-wide error logging facility that is completely pluggable. 
* [log4net](https://logging.apache.org/log4net) (Apache) - A tool to help the programmer output log statements to a variety of output targets. 
* [Serilog](https://serilog.net) - Flexible, structured events — log file convenience.
* [StackExchange.Exceptional](https://github.com/NickCraver/StackExchange.Exceptional) - Error handler used for the Stack Exchange network
* [Essential Diagnostics](https://github.com/sgryphon/essential-diagnostics) - Additional trace listeners, filters and utility classes for the .NET Framework System.Diagnostics trace logging. 
* [Logazmic](Windows log viewer for log4j) - Minimalistic log viewer for nlog.
### CLI
* Parsers
  * [Command Line Parser](http://www.appccelerate.com/commandlineparser.html) - Every now and then, we write a little console application to quickly get a job done.
  * [CommandLineUtils](https://natemcmaster.github.io/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework. 
  * [clipr](https://github.com/nemec/clipr) - Command Line Interface ParseR for .Net
  * [commandline](https://github.com/commandlineparser/commandline) - C# command line parser for .NET with F# support
  * [EntryPoint](https://nick-lucas.github.io/EntryPoint) - Composable CLI Argument Parser for all modern .Net platforms 
  * [Fluent Command Line Parser](https://github.com/fclp/fluent-command-line-parser) - A simple, strongly typed .NET C# command line parser library using a fluent easy to use interface
  * [PowerArgs](https://github.com/adamabdelhamed/PowerArgs) - The ultimate .NET Standard command line argument parser
  * [readline](https://github.com/tonerdo/readline) - A Pure C# GNU-Readline like library for .NET/.NET Core
* Formatters
  * [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output!
  * [CsConsoleFormat](https://github.com/Athari/CsConsoleFormat) - .NET C# library for advanced formatting of console output
  * [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - A fluent library to print out a nicely formatted table in a console application C#
* Invokers
  * [cmd](https://github.com/manojlds/cmd) - A C# Library to run external programs / commands in a simpler way. 
  * [CliWrap](https://github.com/Tyrrrz/CliWrap) - Wrapper for command line interface executables.
### Content Management
* CMS
  * [Orchard](http://orchardproject.net) - A free, open source, community-focused Content Management System built on the ASP.NET MVC platform.
  * [Umbraco](https://umbraco.com) - Umbraco is a fully-featured, open source Content Management System loved by thousands for its flexibility and great editing experience. 
  * [BetterCMS](http://www.bettercms.com) - Better CMS has an intuitive user interface designed to help you make updates to your website content and SEO settings quickly and efficiently. 
  * [Piranha CMS](http://piranhacms.org) - A lightweight & unobstrusive CMS for ASP.Net Core.
  * [Cofoundry](https://www.cofoundry.org) - Open Source .NET Core Application Framework & Content Management Platform
* Static Site Generators
  * [Pretzel](https://github.com/Code52/pretzel) - A site generation tool (and then some) for .NET platforms
  * [Sandra.Snow](https://github.com/Sandra/Sandra.Snow) - Jekyll inspired static site generation for .NET
  * [Wyam](https://wyam.io/) - A highly modular and extremely configurable static content generator and toolkit.
* Templating
  * [RazorEngine](http://antaris.github.io/RazorEngine) - A templating engine built on Microsoft's Razor parsing engine, RazorEngine allows you to use Razor syntax to build dynamic templates.
  * [RazorLight](https://github.com/toddams/RazorLight) - Template engine based on Microsoft's Razor parsing engine for .NET Core
  * [Nustache](https://github.com/jdiamond/Nustache) - Logic-less templates for .NET
  * [mustache#](https://github.com/jehugaleahsa/mustache-sharp) - An extension of the mustache text template engine for .NET.
  * [DotLiquid](http://dotliquidmarkup.org) - DotLiquid is a templating system ported to the .NET framework from Ruby’s [Liquid Markup](http://www.liquidmarkup.org/).
  * [Stubble](https://github.com/stubbleorg/stubble) - Trimmed down {{mustache}} templates in .NET
### Security & Compression
* Compression
  * [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
  * [Snappy.Sharp](https://github.com/jeffesp/Snappy.Sharp) - An implementation of google's Snappy compression format in C#.
  * [SharpCompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.  
  * [LZ4](https://github.com/MiloszKrajewski/lz4net) - ultra fast compression algorithm - for all .NET platforms
* Hashing
  * [HashLib](https://archive.codeplex.com/?p=hashlib) - Hash files, streams, common types of data.
* Security
  * [IdentityServer](https://identityserver.io) - The Identity and Access Control solution that works for you
  * [OpenIddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core
  * [DotNetOpenAuth](http://dotnetopenauth.net) - Get started with OpenID, OAuth today!
  * [IdentityModel](https://github.com/IdentityModel/IdentityModel2) - A .NET standard helper library for claims-based identity, OAuth 2.0 and OpenID Connect. 
  * [Stuntman](http://rimdev.io/stuntman) - Sometimes you need a Stuntman before you send in real, unsuspecting users!
  * [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Ultimate Javascript Object Signing and Encryption (JOSE) and JSON Web Token (JWT) Implementation for .NET and .NET Core
  * [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET
  * [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASPNET Core
  * [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) - A .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security
  * [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps.
  * [Cierge](https://pwdless.github.io/Cierge-Website) - Open source authentication server (OIDC) that handles user signup, login, profiles, management, and more.
* Cryptography
  * [BCrypt.NET](https://github.com/BcryptNet/bcrypt.net) - Bringing updates to the original bcrypt package
  * [Bouncy Castle](https://bouncycastle.org) - A lightweight cryptography API for Java and C#.
  * [libsodium-net](https://github.com/adamcaudill/libsodium-net) - A secure cryptographic library
  * [StreamCryptor](https://github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf
  * [inferno](http://securitydriven.net/inferno) - .NET crypto done right. Professionally audited.
### Utilities
* Parsers
  * [HAP](http://html-agility-pack.net) - Html Agility Pack
  * [AngleSharp](https://anglesharp.github.io) - makes .NET ❤ HTML5
  * [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET library for YAML
  * [Regextra](https://github.com/amageed/Regextra) - Simplifies some tasks typically solved via regex so that you no longer have (problems){2}.
* Detection
  * [MimeKit](https://github.com/jstedfast/MimeKit) - A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
  * [DeviceDetector.NET](https://github.com/totpero/DeviceDetector.NET) - The Universal Device Detection library will parse any User Agent and detect the browser, operating system, device used (desktop, tablet, mobile, tv, cars, console, etc.), brand and model. 
* Configuration
  * [Formo](http://chrismissal.com/Formo) - Formo allows you to use your configuration file as a dynamic object.
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
  * [valit](https://github.com/valit-stack/Valit) - Valit is dead simple validation for .NET Core.
* Mics. 
  * [P](https://github.com/p-org/P) (Microsoft) - P is a language for asynchronous event-driven programming.
  * [ServiceStack.Text](https://servicestack.net/text) - .NET's missing high-performance utility belt
  * [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - An extensible .NET replacement for String.Format
### Architectural Examples
* [CoolStore](https://github.com/vietnam-devs/coolstore-microservices) - A containerized polyglot microservices consisting of services based on .NET Core, NodeJS and more running on service mesh (istio).

## Java
### Distributed systems
* [Akka](https://akka.io)
### Services
### Data Access
* [Calcite](https://calcite.apache.org) (Apache) - The foundation for your next high-performance database. 

## Python

### Distributions and installers

* [virtualenv](https://virtualenv.pypa.io/en/stable/) - A tool to create isolated Python environments.
* [Anaconda](https://www.anaconda.com) -  The Most Popular Python Data Science Distribution 

### Services

* [sandman2](https://github.com/jeffknupp/sandman2) - Automatically generate a RESTful API service for your legacy database. No code required! 
* [Nameko](https://nameko.readthedocs.io/en/stable) - A microservices framework for Python that lets service developers concentrate on application logic and encourages testability
* [Vibora](https://vibora.io) - Fast, asynchronous and elegant Python web framework 

### Distributed Systems

* [Airflow](https://airflow.apache.org) (Apache) - A platform to programmatically author, schedule and monitor workflows
* [Celery](http://www.celeryproject.org) - An asynchronous task queue/job queue based on distributed message passing

### Data Access

* [Peewee](https://github.com/coleifer/peewee) - A small, expressive orm (upports postgresql, mysql and sqlite)

## Go

### Services

* [Martini](https://github.com/go-martini/martini) - Classy web framework for Go
* [Gorilla](http://www.gorillatoolkit.org/pkg/mux) - Gorilla web toolkit

## Node.js

### Awesome
* [Awesome GraphQL](https://github.com/chentsulin/awesome-graphql) - Awesome list of GraphQL & Relay
* [Automatic API](https://github.com/dbohdan/automatic-api) - A list of software that turns your database into a REST/GraphQL API 
### Distributed Systems

* [noel](https://lifenautjoe.github.io/noel) - A universal, human-centric, replayable Javascript event emitter
* [Bull](https://github.com/OptimalBits/bull) - Premium Queue package for handling jobs and messages in NodeJS

### Services

* REST
  * [ActionHero](https://www.actionherojs.com) - The reusable, scalable, and quick node.js API server for stateless and stateful applications
  * [egg](https://eggjs.org/en) - Born to build better enterprise frameworks and apps with Node.js & Koa
* API Gateways
  * [Tyk](https://tyk.io) - Open source API Gateway that is fast, scalable and modern.
  * [Kong](https://getkong.org) - Secure, Manage & Extend your APIs and Microservices
* [GraphQL](graphql.org)
  * [Prisma](https://www.prismagraphql.com) (Graphcool) - Turn your database into a GraphQL API
  * [Apollo](https://github.com/apollographql/apollo-server) (Meteor) - GraphQL server for Express, Connect, Hapi, Koa and more
  * [PostGraphile](https://www.graphile.org) - Tools for building performant pluggable GraphQL APIs.
  * [Join-Monster](https://github.com/stems/join-monster) - A GraphQL to SQL query execution layer for query planning and batch data fetching.
  * [gestalt](https://github.com/charlieschwabacher/gestalt) - Use the GraphQL schema language and a small set of directives to define an API with a PostgreSQL backend declaratively, really quickly, and with a tiny amount of code.
  * [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure 
  * [Altair](https://altair.sirmuel.design) - A beautiful feature-rich GraphQL Client for all platforms
  * [GraphQL Yoga](https://github.com/graphcool/graphql-yoga) (Graphcool) - Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience
* Serverless
  * [serverless](https://serverless.com) - Your toolkit for deploying and operating serverless architectures. 
  * [serverless-offline](https://github.com/dherault/serverless-offline) - Emulate AWS λ and API Gateway locally when developing your Serverless project 
  * [serverless-babel-starter](https://github.com/postlight/serverless-babel-starter) - Serverless with all the fixings: Webpack, Babel, Jest, ESLint, and Prettier.
  * [lambdapack](https://www.npmjs.com/package/lambdapack) - Package your AWS Lambda efficiently, ready to be deployed with [apex/up](https://github.com/apex/up)
### Data Access
* [EventStore](https://eventstore.org) - The open-source, functional database with Complex Event Processing in JavaScript.

### Templating

* [Pug](https://pugjs.org) – Robust, elegant, feature rich template engine for Node.js

### Algorithms & Data Structures

* Numerics
  * [crunch.js](http://crunch.js.org) - Arbitrary-Precision Integer Arithmetic Library
  * [Yaffle BigInteger](https://github.com/Yaffle/BigInteger) - Yet another implementaion of arbitrary-precision integers in pure JavaScript. 
  * [bigi](https://github.com/cryptocoinjs/bigi) - JavaScript Big Integer library based upon Tom Wu's work. 
  * [bn.js](https://github.com/indutny/bn.js) - BigNum in pure javascript
* Bitmaps
  * [Fast-BitSet](https://github.com/mattkrick/fast-bitset)-  A fast bitset with some nice methods

### CRM

* [Tipe](https://tipe.io) - Create your content with powerful editing tools and access it from anywhere with a GraphQL or REST API. Stop letting your CMS decide how you build your apps. 

### Tools

* [i18next](https://www.i18next.com) - An **internationalization-framework** written in and for JavaScript. 
* [ReLaXed](https://github.com/RelaxedJS/ReLaXed) - Create PDF documents using web technologies.
* [Prompts](https://github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts
* [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome
* [ClearGPDR](https://www.cleargdpr.com) - The Leading GDPR Compliance Solution: Open Source, Blockchain Based.

# Frontend

## Design
### Development
* [Haiku](https://www.haiku.ai) - Where designing is building
* [Figma](https://www.figma.com)
* [CSS Grid Builder](https://cssgrid.cc) - A collection of resources & tools to help you manage the Grid
### Style guides
* [Catalog](https://www.catalog.style) - Living style guides for digital products
* [Design Systems Repo](https://designsystemsrepo.com) - A frequently updated collection of Design Systems

## CSS
* Extensions
  * [CSS Blocks](http://css-blocks.com) (LinkedIn) - Blazing fast CSS for your design systems and app components
    * [OptiCSS](https://github.com/linkedin/opticss) (LinkedIn) - A CSS Optimizer
  * [SaSS](https://sass-lang.com)
  * [LeSS](http://lesscss.org)
* Frameworks
  * [mustard](https://mustard-ui.com) - Mustard UI is a starter CSS framework that actually looks good
* UX Frameworks
  * [Mailchimp](http://ux.mailchimp.com/patterns) - MailChimp Pattern Library is a byproduct of our move to a more responsive, nimble, & intuitive app.
* Email
  * [MJML](https://mjml.io) - The only framework that makes responsive email easy
  * [Foundation For Emails](https://foundation.zurb.com/emails.html) - Quickly create responsive HTML emails that work. Even on Outlook.

## Javascript

### Knowledge Base
* [Front End Toolkit](https://github.com/devbridge/Front-End-Toolkit)
* [Best of JS](https://bestof.js.org)
* [Awesome](https://github.com/sindresorhus/awesome) - Curated list of awesome lists

### UX Frameworks

* Design Systems
  * [Awesome Design Systems](https://github.com/alexpate/awesome-design-systems) - A collection of awesome design systems
  * [Bootstrap](https://getbootstrap.com) - Build responsive, mobile-first projects on the web
    * [Material Design for Bootstrap](https://mdbootstrap.com)
    * [Shards](https://designrevision.com/downloads/shards) - A free and modern UI toolkit for web makers
    * [Fire](http://fire.uxtheme.net) - Easy Development with Fire UI Kit
  * [Carbon](http://carbondesignsystem.com) (IBM) - Design system for IBM Cloud products.
  * [Stencil](https://stenciljs.com) - The magical, reusable web component compiler
  * [Rizzo](http://rizzo.lonelyplanet.com/styleguide) (Lonely Planet) - 
  * [boundless](https://boundless.js.org) - UI toolkit that was conceived to abstract away difficult interface patterns
  * [Lightning Design System](https://www.lightningdesignsystem.com) (Salesforce) - Create the world’s best enterprise app experiences.
  * [Mapbox](https://www.mapbox.com/base) (Maxbox) - An internal guide & code repository for designing and coding at Mapbox.
  * [Atlassian Design](https://atlassian.design) (Atlassian) - Use Atlassian's end-to-end design language to create straightforward and beautiful experiences.
  * [Auth0 Styleguide](https://styleguide.auth0.com) (Auth0) - Conjunction of design patterns, components and resources used across our products.
* Themes
  * [Hacker Themes](https://hackerthemes.com) - Bootstrap 4 themes & templates for ambitious developers
  * [Creative Time](https://www.creative-tim.com) - Premium Bootstrap themes, templates, UI Kits and more developed by Creative Tim.
  * [Tabler](https://tabler.github.io) - Premium and Open Source dashboard template with responsive and high quality UI. For Free!
  * [Papaya](https://www.eatapapaya.com/) - Yummy landing page templates for any project.

### Libraries
* Charts and graphics
  * [protovis](http://mbostock.github.io/protovis) - A graphical approach to visualization
  * [d3js](https://d3js.org) - Data-Driven Documents
    * [d3-discovery](https://d3-discovery.net) - Finding D3 plugins with ease
    * [mermaid](https://mermaidjs.github.io) - Generation of diagram and flowchart from text in a similar manner as markdown
    * [nvd3](http://nvd3.org) - A reusable charting library
    * [d3-annotation](http://d3-annotation.susielu.com)
    * [plotly.js](https://plot.ly/javascript) - The open source JavaScript graphing library that powers Plotly
    * [epoch](http://epochjs.github.io/epoch) - A general purpose real-time charting library for building beautiful, smooth, and high performance visualizations
    * [metricsgraphicsjs](https://www.metricsgraphicsjs.org) - A library that is optimized for visualizing and laying out time-series data
    * [rickshaw](http://code.shutterstock.com/rickshaw) - JavaScript toolkit for creating interactive time series graphs
    * [plottablejs](http://plottablejs.org) (Palantir) - Flexible, interactive charts for the web
  * [Vega](https://vega.github.io/vega) - A Visualization Grammar
    * [Vega Lite](https://vega.github.io/vega-lite) - A Grammar of Interactive Graphics
  * [dygraphs](http://dygraphs.com) - Fast, flexible open source JavaScript charting library
  * [sigmajs](http://sigmajs.org) - Sigma is a JavaScript library dedicated to graph drawing
  * [cytoscape](http://js.cytoscape.org) - Graph theory / network library for analysis and visualisation
  * [cubismjs](https://square.github.io/cubism) (Square) - Time Series Visualization
  * [taucharts](https://www.taucharts.com) - Flexible javascript charting library for data exploration
  * [echarts](http://echarts.baidu.com) (Baidu) - A powerful, interactive charting and visualization library for browser
    * [ECharts-GL](https://github.com/ecomfe/echarts-gl) - Extension pack of [echarts](http://echarts.baidu.com/), which providing 3D plots, globe visualization and WebGL acceleration. 
  * [chartjs](http://www.chartjs.org) - Simple yet flexible JavaScript charting for designers & developers
  * [chartist](https://gionkunz.github.io/chartist-js) - Simple responsive charts
  * [Pixi](http://www.pixijs.com/) - The HTML5 Creation Engine
  * [Toast UI](http://ui.toast.com/tui-chart) - An easy way to draw various and essential charts on your web service. 
  * [flowchart.js](https://flowchart.js.org) - Draws simple SVG flow chart diagrams from textual representation of the diagram
  * [curtains.js](https://www.martin-laxenaire.fr/libs/curtainsjs/index.html)  - Easy WebGL tool to animate images
  * [G2](https://github.com/antvis/g2) (Alibaba) - The Grammar of Graphics in JavaScript
    * [BizCharts](https://github.com/alibaba/BizCharts) - Data visualization library based G2 and React
    * [G6](https://github.com/antvis/g6) - Relational data visualization framework. 
  * [deck.gl](http://uber.github.io/deck.gl) (Uber) - A WebGL-powered framework for visual exploratory data analysis of large datasets.
* Animations
  * [micron](https://webkul.github.io/micron) - a [μ] microInteraction library built withCSS Animations and controlled by JavaScript Power
  * [Just Animate](https://just-animate.github.io) - Making animation simple
* Maps
  * [pigeon-maps](https://mariusandra.github.io/pigeon-maps) - 
* Utilities
  * [Dinero.js](https://sarahdayan.github.io/dinero.js) - Dinero.js is a library for working with monetary values in JavaScript
  * [Proppy](https://proppyjs.com) - Functional props composition for components
* Tours
  * [Driver](http://kamranahmed.info/driver) - Light-weight, no-dependency, vanilla JavaScript engine to drive user's focus across the page

### Tooling
* [bit](https://bitsrc.io) - Components are building blocks. You are the architect.
* [Lerna](https://lernajs.io) - A tool for managing JavaScript projects with multiple packages. 
* [codemods](https://github.com/facebook/codemod) - Tool/library to assist you with large-scale codebase refactors that can be partially automated but still require human oversight and occasional intervention.
* [Scroll Booster](https://ilyashubin.github.io/scrollbooster) - Enjoyable content drag-to-scroll library.
* [Webpack](https://webpack.js.org) - Bundle your assets
  * [Speed Measure](https://github.com/stephencookdev/speed-measure-webpack-plugin) - See how fast (or not) your plugins and loaders are, so you can optimise your builds
  * [NOW Loader](https://github.com/pranaygp/now-loader) - Deploys the required resource to now
  * [directory-named-webpack-plugin](https://www.npmjs.com/package/directory-named-webpack-plugin) - This plugin makes it possible to control what file within directory will be treated as entry file.
* [turbolinks](https://github.com/turbolinks/turbolinks) - Turbolinks makes navigating your web application faster

### [React](https://reactjs.org)
* Awesome
  * [Awesome React](https://github.com/enaqx/awesome-react)
  * [React Components & Libraries](https://github.com/brillout/awesome-react-components)
  * [Awesome Redux (brillout)](https://github.com/brillout/awesome-redux)
  * [Awesome Redux (xgrommx)](https://github.com/xgrommx/awesome-redux)
  * [Awesome MobX](https://github.com/mobxjs/awesome-mobx)
  * [MobX Ecosystem](https://github.com/xgrommx/mobx-ecosystem)
  * [Awesome React GraphQL](https://github.com/hasura/awesome-react-graphql) - A curated collection of resources, clients and tools that make working with GraphQL and React/React Native awesome. 
* State Management
  * REST
    * [tectonic](https://tonyhb.github.io/tectonic) - A declarative REST data loader for react + redux
    * [React Agent](http://www.reactagent.com) - A JS library for your database management
    * [Redux Rest Resource](http://mgcrea.github.io/redux-rest-resource) - Dead simple and ready-to-use store module for handling HTTP REST resources.
  * [Redux](https://redux.js.org)
    * [Undux](https://github.com/bcherny/undux) - Dead simple state management for React
    * [next.js](https://github.com/zeit/next.js) - Framework for server-rendered or statically-exported React apps
    * [after.js](https://github.com/jaredpalmer/after.js) - Next.js-like framework for server-rendered React apps built with React Router 4
    * [jumpsuit](https://jumpsuit.js.org) - React framework for efficiently building powerful web applications
    * [rematch](https://rematch.gitbooks.io/rematch) -  Redux best practices without the boilerplate. No more action types, action creators, switch statements or thunks.
    * [dva](https://github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework. (Inspired by elm and choo) 
    * [microcosm](http://code.viget.com/microcosm) - Microcosm is [Flux](https://facebook.github.io/flux/docs/overview.html) with actions at center stage. Write optimistic updates, cancel requests, and track changes with ease. 
  * [MobX](https://mobx.js.org)
    * [cans](http://cans.js.org) - A framework for building React / MobX application
    * [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree) - Model Driven State Management
    * [parket](https://github.com/ForsakenHarmony/parket) - A library to manage application state, heavily inspired by mobx-state-tree
    * [FormState](https://github.com/formstate/formstate) - Form state so simple that you will fall in love
    * [react-remux](https://github.com/vinej/react-remux) - A flux implementation with React and Mobx
  * Tools
    * [immutable.js](https://facebook.github.io/immutable-js) (Facebook) - Immutable collections for JavaScript
    * [Immer](https://github.com/mweststrate/immer) - Create the next immutable state by mutating the current one
    * [Unstated](https://github.com/jamiebuilds/unstated) - State so simple, it goes without saying.
    * [ModulaJS](https://github.com/freewheel/modulajs) - A modularization framework to manage application states using an immutable model tree.
    * [unistore](https://github.com/developit/unistore) - 650b state container with component actions for Preact & React
    * [uniforms](https://github.com/vazco/uniforms) - A set of React libraries for building forms
    * [Final Form](https://github.com/final-form/react-final-form) - High performance subscription-based form state management for React.
    * [react-portalgun](https://github.com/diegomura/react-portalgun) - Lightweight portal system for React. Mega seeds included
* Development Frameworks
  * [next.js](https://github.com/zeit/next.js) - A lightweight framework for static and server‑rendered applications.
  * [next-offline](https://github.com/hanford/next-offline) - Make your Next.js application work offline using service workers via Google's workbox.
  * [DVA](https://github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework.
  * [Create React App](https://github.com/facebook/create-react-app) - Create React apps with no build configuration.
  * [rekit](http://rekit.js.org) - A toolkit for building scalable web applications with React, Redux and React-router.
  * [fusion.js](https://fusionjs.com) - A plugin-based universal web framework
* Routing
   * [Junctions](https://junctions.js.org) - A batteries-included router for React.
* UX Frameworks
  * [Gestalt](https://github.com/pinterest/gestalt) (Pinterest) - Set of React UI components that enforces Pinterest’s design language. 
  * [Grommet](http://grommet.io) (Hewlett Packard) - focus on the essential experience
     * [Grommet Addons](https://github.com/grommet/grommet-addons) - Higher order components and utilities based on core grommet components.
     * [Grommet Index](http://index.grommet.io/docs/grommet-index) - Additional components beyond the base Grommet components for use in data heavy environments [*deprecated* - use Grommet Addons instead].
  * [Material UI](https://material-ui-next.com) - React components that implement Google's Material Design.
  * [Ant Design](https://ant.design) - A design system with values of Nature and Determinacy for better user experience of enterprise applications
     * [Awesome Ant Design](https://github.com/websemantics/awesome-ant-design) - A curated list of Ant Design resources and related projects. 
     * [Ant.Motion](https://github.com/ant-design/ant-motion) - Animate specification and components of Ant Design  
     * [Scaffolds](http://scaffold.ant.design) - Practical scaffolds to kickoff 
  * [React Desktop](http://reactdesktop.js.org) - JavaScript library built on top of [Facebook's React](https://facebook.github.io/react/) library, which aims to bring a native desktop experience to the web, featuring many macOS Sierra and Windows 10 components.
  * [Semantic UI](https://react.semantic-ui.com) - Semantic UI React is the official React integration for [Semantic UI](https://semantic-ui.com/) .
  * [Blueprint](http://blueprintjs.com) (Palantir) - A React-based UI toolkit for the web
  * [React Bootstrap](https://react-bootstrap.github.io) - The most popular front-end framework, rebuilt for React.
  * [Office UI Fabric](https://developer.microsoft.com/en-us/fabric#/components) (Microsoft) - Use our design language in your own experience
  * [react-md](https://react-md.mlaursen.com) - React material design
  * [modulz](https://www.modulz.co/showcase) - An open–source collection of styles, components, patterns, resources & more
  * [Clarity Design System](https://vmware.github.io/clarity) (VMWare) - UX guidelines, HTML/CSS framework, and Angular components working together to craft exceptional experiences
  * [React Lightning Design System](https://github.com/mashmatrix/react-lightning-design-system) - Salesforce Lightning Design System components built with React
  * [RSuite](https://rsuitejs.com/en) - A suite of React components
  * [Evergreen](https://evergreen.surge.sh) - React UI Framework for the Web
* Themes
   * [CoreUI](https://coreui.io) - Free Bootstrap Admin Template
* Security and Authentication
   * [React Check Auth](https://github.com/hasura/react-check-auth) - Add auth protection anywhere in your react/react-native app.
* Component/CSS frameworks
  * [Aphrodite](https://github.com/Khan/aphrodite) (Khan Academy) - Framework-agnostic CSS-in-JS with support for server-side rendering, browser prefixing, and minimum CSS generation
    * [Adonis](https://github.com/imgly/adonis) - The best of [Aphrodite](https://github.com/Khan/aphrodite) and [styled-components](https://github.com/styled-components/styled-components): Named DOM elements, stylable via object literals with support for inheritance, overriding and theming while staying lightweight (28 KB / 7.6 KB gzipped)
  * [glamor](https://github.com/threepointone/glamor) - Inline CSS for React et al.
  * [glamorous](https://github.com/paypal/glamorous) (PayPal) - Maintainable CSS with React
  * [emotion](https://emotion.sh) - The Next Generation of CSS-in-JS
  * [Radium](http://formidable.com/open-source/radium) (Formidable Labs) - Set of tools to manage inline styles on React elements.
  * [rebass](http://jxnblk.com/rebass) - Library of highly-composable, primitive UI components for React, built with styled-components to keep styles isolated and reduce the need to write custom CSS in your application.
  * [cxs](https://github.com/cxs-css/cxs) - fast af css-in-js in 0.7kb
  * [Styletron](https://github.com/rtsao/styletron) - Toolkit for component-oriented styling 
  * [styled-components](https://www.styled-components.com) - Visual primitives for the component age
    * [Styled Theming](https://github.com/styled-components/styled-theming) - Create themes for your app using styled-components
    * [styled-system](http://jxnblk.com/styled-system/#styled-system) - Design system utilities for [styled-components](https://github.com/styled-components/styled-components) and other css-in-js libraries
  * [reas](https://reas.js.org) - A minimalist and highly customizable component system
  * [React Foundation](https://react.foundation) - Foundation as React components
  * [React Grid](https://devexpress.github.io/devextreme-reactive/react/grid/) (DevExtreme) - Your Data Grid, Your Way
* Charts & graphics
  * [Victory](http://formidable.com/open-source/victory) (Formidable Labs) - React.js components for modular charting and data visualization
  * [recharts](http://recharts.org) - A composable charting library built on React components
  * [react-vis](http://uber.github.io/react-vis) (Uber) - A composable charting library
  * [reactivemaps](https://github.com/appbaseio/reactivemaps) - A data aware UI components library for building realtime maps
  * [echarts-for-react](http://git.hust.cc/echarts-for-react) - A very simple echarts (v3.x & v4.x) wrapper for React.
  * [react-virtualized](http://www.reactvirtualized.com) - React components for efficiently rendering large lists and tabular data.
* Animations and video
  * [Pose](https://popmotion.io/pose) - Declarative motion system for HTML, SVG, React & React Native
  * [react-spring](https://github.com/drcmda/react-spring) - Helping react-motion and animated to become best friends
  * [popmotion](https://github.com/Popmotion/popmotion) - A functional, reactive animation library
  * [react-move](https://github.com/react-tools/react-move) - Beautiful, data-driven animations for React
  * [animated](https://github.com/animatedjs/animated) - Declarative Animations Library for React and React Native
  * [react-motion](https://github.com/chenglou/react-motion) - A spring that solves your animation problems
  * [Video.js](http://videojs.com) - The player framework
* Testing
  * [react-testing-library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* Utilities
  * [react-with-gesture](https://github.com/drcmda/react-with-gesture) - Little helper for component-tied mouse/touch gestures
  * [React Graceful Image](https://github.com/linasmnew/react-graceful-image) - An image component for gracefully dealing with image errors by providing optional lazy loading, optional placeholder and configurable retries on failure 
  * [MDXC](http://mdxc.reactarmory.com) - Tool to convert Markdown into React Components.
  * [Spectacle](http://formidable.com/open-source/spectacle) (Formidable Labs) - A React.js based library for creating sleek presentations.
  * [Compositor](https://compositor.io) - Modern tools for designers & developers

### [Angular](https://angular.io)
* Awesome
  * [awesome-angular](https://github.com/gdi2290/awesome-angular) - A curated list of awesome Angular resources by [@TipeIO](https://github.com/TipeIO) 
  * [awesome-angular2](https://github.com/amcdnl/awesome-angular2) - A curated list of awesome Angular 2 resources by [@AngularClass](https://github.com/AngularClass) 
  * [awesome-angular-components](https://github.com/brillout/awesome-angular-components) - Catalog of Angular 2+ Components & Libraries 
* Development frameworks
  * [Nrwl Nx](https://nrwl.io/nx) - An open source toolkit for enterprise Angular applications
* UX Frameworks
  * [Angular Material](https://material.angular.io) - Material Design components for Angular
  * [NG-ZORRO](https://github.com/NG-ZORRO/ng-zorro-antd) - An enterprise-class UI components based on Ant Design and Angular. 

### [Vue.js](https://vuejs.org)
* Examples
  * [Made With Vue](https://madewithvuejs.com) - A collection of projects made with vue.js
* Development Frameworks & Boilerplates
  * [nuxt](https://nuxtjs.org) - Universal Vue.js Applications
  * [Vue Enterprise Boilerplate](https://github.com/chrisvfritz/vue-enterprise-boilerplate) - An ever-evolving, very opinionated architecture and dev environment for new Vue SPA projects using Vue CLI 3.  
  * [Charcoal](https://github.com/setholito/charcoal) - A Vue.js & Bulma Starter Kit.
* UX Frameworks
  * [Material Design for Bootstrap](https://mdbootstrap.com/vue) - Vue Bootstrap with Material Design
  * [iView](https://www.iviewui.com) - A high quality UI Toolkit based on Vue.js.
  * [Vuetify](https://vuetifyjs.com) - Material Design Component Framework.
  * [Vue Design System](https://vueds.com) - An open source tool for building Design Systems with [Vue.js](https://vuejs.org)
  * [Fish UI](https://myliang.github.io/fish-ui) - A Vue.js 2.0 UI Toolkit for Web.
* CMS
  * [VuePress](https://vuepress.vuejs.org) - Vue-powered Static Site Generator 
* Tools
  * [Vue Tour](https://pulsardev.github.io/vue-tour) - a Lightweight, Simple and Customizable tour plugin for use with Vue.js
* Native
  * [vuido](https://github.com/mimecorg/vuido) - Native desktop applications using Vue.js

### [Ember.js](https://www.emberjs.com)
* Libraries
	* [ember-table](http://opensource.addepar.com/ember-table)

### Other frameworks
* [Preact](https://preactjs.com) - Fast 3kB alternative to React with the same modern API. 
* [Inferno](https://infernojs.org) - Insanely fast, React-like library for building high-performance user interfaces on both the client and server.
* [svelte](https://svelte.technology) - The magical disappearing UI framework
* [Glimmer.js](https://glimmerjs.com) - Fast and light-weight UI components for the web
* [Knockout](http://knockoutjs.com) - Knockout makes it easier to create rich, responsive UIs with JavaScript  
* [Mithril](https://mithril.js.org) - Modern client-side Javascript framework for building Single Page Applications.
* [Aurelia](http://aurelia.io) - JavaScript client framework for web, mobile and desktop that leverages simple conventions to empower your creativity.
* [Meteor](https://www.meteor.com) - The fastest way to build javascript apps.
* [Ionic](https://ionicframework.com) - Build amazing apps in one codebase, for any platform, with the web.
* [Stencil](https://stenciljs.com) - The magical, reusable web component compiler
* [Marko](https://markojs.com) - It's like HTML and JS had a perfect baby that grew up to be awesome

### Utilities

* [selection](https://github.com/Simonwep/selection) - A simple and lightweight library to realize visual DOM Selections.  

## .Net
### UI frameworks
* WinForms
  * [Material Skin](https://github.com/IgnaceMaes/MaterialSkin) - Theming .NET WinForms, C# or VB.Net, to Google's Material Design Principles.
* WPF
  * [Caliburn.Micro](https://caliburnmicro.com) - A small, yet powerful framework, designed for building applications across all XAML platforms.
  * [MahApps.Metro](http://mahapps.com) - Let your desktop apps shine
  * [Material Design In XAML Toolkit](http://materialdesigninxaml.net) - Easily bring beautiful desktop applications to life, using a modern and popular design language. 
  * [Avalonia](http://avaloniaui.net) - A cross platform XAML Framework for .NET Framework, .NET Core and Mono
  * [Modern UI](https://github.com/firstfloorsoftware/mui) - Modern UI for WPF
  * [Catel](http://catelproject.com) - An application development platform with the focus on MVVM (WPF, Silverlight, Windows Phone, WinRT, Xamarin.Android and Xamarin.iOS) and MVC (ASP.NET MVC).
  * [MVVM Light Toolkit](https://github.com/lbugnion/mvvmlight) - The main purpose of the toolkit is to accelerate the creation and development of MVVM applications in Xamarin.Android, Xamarin.iOS, Xamarin.Forms, Windows 10 UWP, Windows Presentation Foundation (WPF), Silverlight, Windows Phone.
  * [Okra App Framework](http://okraframework.github.io) - The app centric MVVM framework for Windows and Windows Phone
  * [Prism](https://github.com/PrismLibrary/Prism) - A framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms.
  * [WAF](https://github.com/jbe2277/waf) - Win Application Framework (WAF) is a lightweight Framework that helps you to create well structured XAML Applications.
  * [Gemini](http://documentup.com/tgjones/gemini) - WPF framework designed specifically for building IDE-like applications.
* Web
  * [DotVVM](https://github.com/riganti/dotvvm) - Open source MVVM framework for Web Apps.
  * [Ooui](https://github.com/praeclarum/Ooui) - A small cross-platform UI library that brings the simplicity of native UI development to the web.
  * [Blazor](https://github.com/aspnet/Blazor) - Blazor is an experimental .NET web framework using C#/Razor and HTML that runs in the browser with WebAssembly 
* Other
  * [Stylet](https://github.com/canton7/stylet) - Minimal MVVM framework inspired by Caliburn Micro, with good documentation, high test coverage, and its own IoC container
  * [ReactiveUI](https://github.com/reactiveui/reactiveui) - An advanced, composable, functional reactive model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming.
  * [Eto.Forms](https://github.com/picoe/Eto) - Cross platform GUI framework for desktop and mobile applications in .NET
  * [Neutronium](https://github.com/NeutroniumCore/Neutronium) - Build .NET desktop applications using HTML, CSS and javascript
  * [mvvmcross](https://www.mvvmcross.com) - App development without compromise.
  * [QtShartp](https://github.com/ddobrev/QtSharp) - Mono/.NET bindings for Qt
  * [xwt](https://github.com/mono/xwt) - A cross-platform UI toolkit for creating desktop applications with .NET and Mono
  * [WinApi](https://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop 
### Controls
* [Krypton](https://github.com/ComponentFactory/Krypton) - Krypton WinForms components for .NET
* [Callisto](https://github.com/timheuer/callisto) - A control toolkit for Windows 8 XAML applications.
* [MVVM Dialogs](https://github.com/FantasticFiasco/mvvm-dialogs) - Framework simplifying the concept of opening dialogs from a view model when using MVVM in WPF or UWP.
### Graphics
* Imaging
  * [dot.imaging](https://github.com/dajuric/dot-imaging) - Minimalistic .NET imaging portable platform
  * [metadata-extractor.NET](https://github.com/drewnoakes/metadata-extractor-dotnet) - Extracts Exif, IPTC, XMP, ICC and other metadata from image and movie files
  * [Image Resizer](https://github.com/imazen/resizer) - The Flexible Image Server
  * [Image Processor](http://imageprocessor.org) - A .NET Library For On-The-Fly Processing Of Images.
  * [Dynamic Image](http://dynamicimage.apphb.com) - A high-performance image manipulation library for ASP.NET
  * [Image Sharp](https://sixlabors.github.io/docs/articles/ImageSharp/GettingStarted.html) - A cross-platform library for the processing of image files 
  * [Magick.NET](https://github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick
  * [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform .Net wrapper to the OpenCV image processing library.
  * [OpenCvSharp](https://github.com/shimat/opencvsharp) - .NET Framework wrapper for OpenCV 
  * [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - Image processing library for use in .Net applications that supports .Net Core.
  * [NetVips](https://kleisauke.github.io/net-vips) - Mono/.NET binding for the [libvips image processing library](https://jcupitt.github.io/libvips).
* Bar and QR codes
  * [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation
* Charts
  * [LiveCharts](https://lvcharts.net) - Simple, flexible, interactive & powerful data visualization for .Net
  * [OxyPlot](http://www.oxyplot.org) - OxyPlot is a cross-platform plotting library for .NET.
* Raster
  * [NGraphics](https://github.com/praeclarum/NGraphics) - Cross platform library for rendering vector graphics on .NET.
* 3D
  * [Helix Toolkit](http://www.helix-toolkit.org) - 3D for .NET
  * [opentk](https://github.com/opentk/opentk) - Fast, low-level C# wrapper for OpenGL and OpenAL.
  * [veldrid](https://mellinoe.github.io/veldrid-docs) - Low-level graphics library for .NET.
### Misc.
* [TomsToolbox](https://github.com/tom-englert/TomsToolbox) - A set of core functions and classes to ease every days .Net development tasks. 

## Java

## Other

* [Mint](https://www.mint-lang.com) - A refreshing programming language for the front-end web. 

# Databases
## Relational
### Systems
* [PostgreSQL](https://www.postgresql.org)
  * [postgrest](https://postgrest.com) - Standalone web server that turns your PostgreSQL database directly into a RESTful API.
  * [pREST](https://postgres.rest) - A way to serve a RESTful APIs for any database. 
  * [zombodb](https://github.com/zombodb/zombodb) - Making Postgres and Elasticsearch work together like it's 2018
  * [migra](https://migra.djrobstep.com) - A schema comparison tool for PostgreSQL.
  * [Citus Data](https://www.citusdata.com) - Worry-Free Postgres for SaaS
  * [skor](https://github.com/hasura/skor) - Listen to postgres events and forward them as JSON payloads to a webhook
  * [Odissey](https://github.com/yandex/odyssey) - Scalable PostgreSQL connection pooler
* [CockroachDB](https://github.com/cockroachdb/cockroach)

### Editors
* [DBeaver](https://dbeaver.jkiss.org)
* [SQL Workbench/J](http://www.sql-workbench.eu)

## Document
* [Elastic](https://www.elastic.co)
  * [Kibana](https://www.elastic.co/products/kibana) (Elastic)
  * [Grafana](https://grafana.com)
* [Solr](http://lucene.apache.org/solr)
  * [Banana](https://github.com/lucidworks/banana) (LucidWorks)
* [Mongo](https://www.mongodb.com)
* [RavenDB](https://ravendb.net) - The Original Fully Transactional Open Source NoSQL Document Database.

## Columnar

* Cassandra
* [ScyllaDB](https://www.scylladb.com) - Scale-up performance of 1,000,000 IOPS per node, scale-out to hundreds of nodes and 99% latency of <1 msec

## Graph

### Databases
* [Neo4J](https://neo4j.com)
  * [Cypher](https://neo4j.com/developer/cypher-query-language)
* [ArangoDB](https://www.arangodb.com)
* [OrientDB](https://orientdb.com)
* [Titan](http://titan.thinkaurelius.com)
* [Dgraph](https://dgraph.io)

### Tools
* [Giraph](http://giraph.apache.org) (Apache) - An iterative graph processing system built for high scalability

## In-memory
### Open source databases
* [Ignite](https://ignite.apache.org)

### Non-open source databases
* [MemSQL](https://www.memsql.com)
* [Aerospike](https://www.aerospike.com)

## Columnar
* [Cassandra](http://cassandra.apache.org) (Apache)

## Time-series

* [Timescale](http://www.timescale.com) - Enabling a variety of powerful time-series queries with the SQL you already know. 

# Integration
## Knowledge Base
* [Awesome Microservices](https://github.com/mfornos/awesome-microservices) - A curated list of Microservice Architecture related principles and technologies

## Data Formats
* [Avro](http://avro.apache.org) (Apache)
* [Protobuf](https://developers.google.com/protocol-buffers) (Google)

## Protocols
* [HTTP/2](https://http2.github.io)
* [gRPC](https://grpc.io)
* [IPFS](https://ipfs.io)

## Frameworks & Platforms
### Libraries
* [Camel](http://camel.apache.org) (Apache)

### Platforms
* [Spring Cloud Data Flow](https://cloud.spring.io/spring-cloud-dataflow)
* [MuleSoft](https://www.mulesoft.com)
* [WSO2](https://wso2.com)
* [Fuse](https://developers.redhat.com/products/fuse/overview)

## Messaging
* [Kafka](https://kafka.apache.org) (Apache)
	* [KSQL](https://github.com/confluentinc/ksql) (Confluent)
	* [Kafka Connect](https://www.confluent.io/product/connectors) (Confluent)
* [ActiveMQ](activemq.apache.org) (Apache)
* [ZeroMQ](zeromq.org)
* [RabbitMQ](https://www.rabbitmq.com) (Pivotal)

## Batch Processing
### ETL
* [Talend Open Studio](https://www.talend.com/products/data-integration)
* [Kettle - Pentaho Data Integration](http://www.pentaho.com/product/data-integration)
### Big Data
* [Hadoop](http://hadoop.apache.org)
* [Spark](https://spark.apache.org)

## Stream Processing
### Frameworks
* Java
	* [Samza](samza.apache.org) (Apache)
	* [Apex](http://apex.apache.org) (Apache)
	* [Beam](https://beam.apache.org) (Apache)
	* [Flink](https://flink.apache.org) (Apache)
* .Net
	* [Prajna](http://msrccs.github.io/Prajna)
	* [Mobius](https://github.com/Microsoft/Mobius)
	* [MBrace](http://mbrace.io)

### Tools
* [NiFi](https://nifi.apache.org) (Apache)

## Batch Processing
* Scheduling & Workflow
	* [Airflow](http://airflow.incubator.apache.org)

## Ene-to-End Solutions
* [WSO2](https://wso2.com)

### BPM

### Rules
* [Drools](https://www.drools.org) (JBoss)

# Mobile
## Cross platform

- [Flutter](https://flutter.io) - Build beautiful native apps in record time
- [Capacitator](https://capacitor.ionicframework.com/) - The native bridge for cross-platform web apps

## Android

### Profiling

* [profilo](https://facebookincubator.github.io/profilo) - 

## iOS

# Analytics
* Self Service
	* [Metabase](https://www.metabase.com)
	* [DatabaseFlow](https://databaseflow.com)

# Machine Learning

## Awesome

* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) - A curated list of awesome Machine Learning frameworks, libraries and software.
* [Machine Learning Tutorials](http://ujjwalkarn.github.io/Machine-Learning-Tutorials) - Machine learning and deep learning tutorials, articles and other resources

## NLP

* [fastText](https://github.com/facebookresearch/fastText) (Facebook) - Library for fast text representation and classification.
* [sonnet](https://github.com/deepmind/sonnet) (Google) - TensorFlow-based neural network library

## Visualization

* [facets](https://pair-code.github.io/facets) (Google) - Better data leads to better models.
* [AI-Blocks](https://mrnothing.github.io/AI-Blocks) - Spend time creating models, not implementing them.
* [Observable](https://beta.observablehq.com) - Discover insights faster and communicate more effectively with interactive notebooks for data analysis, visualization, and exploration.

## Data Sets

* [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) - A MNIST-like fashion product database.
* [parl.ai](http://parl.ai) - A unified platform for sharing, training and evaluating dialog models across many tasks.

## Libraries

* C#
  * [ML-Agents](https://github.com/Unity-Technologies/ml-agents) - Unity Machine Learning Agents
* Python
  * [TensorFlow](https://www.tensorflow.org) (Google) - An open source machine learning framework for everyone.
  * [NumPY](http://www.numpy.org) - fundamental package for scientific computing with Python.
  * [Pandas](https://pandas.pydata.org) - High-performance, easy-to-use data structures and data analysis tools for the [Python](https://www.python.org/) programming language.
  * [scikit-learn](http://scikit-learn.org/stable) (INRIA) - Machine Learning in Python
  * [spaCy](https://spacy.io) - Industrial-StrengthNatural Language Processing
  * [Dask](https://dask.pydata.org/en/latest) - Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love.
  * [Numba](https://numba.pydata.org) - The power to speed up your applications with high performance functions written directly in Python.
  * [Pyro](http://pyro.ai) (Uber) - Deep Universal Probabilistic Programming
  * [Horovod](https://github.com/uber/horovod) (Uber) - Distributed training framework for TensorFlow
  * [chainer](https://chainer.org) - Bridge the gap between algorithms and implementations of deep learning.

## Notebooks
* [Zepellin](https://zeppelin.apache.org)
* [jupyter](http://jupyter.org)

# DevOps
## Web servers, Reverse Proxies and Load Balancers
* [nginx](https://www.nginx.com) - Deliver modern applications at scale
* [HAProxy](http://www.haproxy.org) - The Reliable, High Performance TCP/HTTP Load Balancer
* [Apache](https://httpd.apache.org) (Apache) - Open-source HTTP server for modern operating systems including UNIX and Windows.
* [træfik](https://traefik.io) - Modern HTTP reverse proxy and load balancer made to deploy microservices with ease
* [Caddy](https://caddyserver.com) - The HTTP/2 web server with automatic HTTPS.
* [Argo Tunnel](https://developers.cloudflare.com/argo-tunnel) - Exposes applications running on your local web server, on any network with an Internet connection, without adding DNS records or configuring a firewall or router.
* [Pushpin](https://pushpin.org) - Drop-in proxy server that pins client connections open, making realtime push easy. 
## App Servers
* [Tomcat](http://tomcat.apache.org) (Apache)
## Caching
* Varnish
## Serverless
* Frameworks
  * [OpenWhisk](https://openwhisk.apache.org) (IBM)
  * [architect](https://arc.codes) - Lambda functions simplified
* Deployment
  * [now](https://zeit.co/now) - Realtime Global Deployments
  * [apex](http://apex.run) - Serverless architecture
## Infrastructure
* [Docker](https://www.docker.com) - World’s leading software containerization platform. 
  * [Swarm](https://docs.docker.com/engine/swarm)
  * [Moby](https://mobyproject.org) (Docker) - An open framework to assemble specialized container systems without reinventing the wheel. 
* [Kubernetes](https://kubernetes.io) (Google) - Automating deployment, scaling, and management of containerized applications
  * [Rancher](https://rancher.com) - Enterprise management for Kubernetes. Every distro. Every cluster. Every cloud. 
  * [skaffold](https://github.com/GoogleCloudPlatform/skaffold) - Easy and Repeatable Kubernetes Development
  * [Continuous Pipe](https://continuouspipe.io) - Continuous deployment solution for your containerized applications to Kubernetes clusters
  * [Typhoon](https://typhoon.psdn.io/) - Typhoon is a minimal and free Kubernetes distribution
  * [kops](https://github.com/kubernetes/kops) - Production Grade K8s Installation, Upgrades, and Management
* Mesos (Apache)
* Tools
  * [Grail](https://eng.uber.com/grail) (Uber) - Scaling Infrastructure Management
  * [osquery](https://osquery.io) (Facebook) - Performant endpoint visibility
  * [Spinnaker](https://www.spinnaker.io) (Netflix) - Fast, safe, repeatable deployments
  * [Istio](https://istio.io) - Connect, secure, control, and observe services.
## Security
* [Infection Monkey](https://www.guardicore.com/infectionmonkey) -  Unleash the Infection Monkey in your network and discover security flaws in no time.

## Performance
* [Lighthouse](https://developers.google.com/web/tools/lighthouse) (Google) -  Automated tool for improving the quality of web pages. 

## Configuration

### Linux

- [Cockpit](http://cockpit-project.org) - Server manager that makes it easy to administer your GNU/Linux servers via a web browser.

### Windows

## Tools

### Windows Consoles

* [Cmder](cmder.net)
* [ConEmu](https://conemu.github.io)
* [Babun](babun.github.io)
* [Clink](https://mridgers.github.io/clink)

### Remote Desktop clients

* [Remote Desktop Manager](https://remotedesktopmanager.com/home/download)

### Chat

* [Rocket.Chat](https://rocket.chat)

# Programming
## Languages
* [Crystal](https://crystal-lang.org)
* [Lua](https://www.lua.org)
* [Rust](https://www.rust-lang.org/en-US)
* [Python](https://www.python.org)
* [Dart](https://www.dartlang.org)
	* Awesome
		* [Dart](https://github.com/yissachar/awesome-dart)
* [Haskell](https://www.haskell.org)
* [Erlang](https://www.erlang.org)
	* [Elixir](https://elixir-lang.org)
	* [Phoenix](phoenixframework.org)
	* Awesome
		* [Erlang](https://github.com/drobakowski/awesome-erlang)
		* [Elixir](https://github.com/h4cc/awesome-elixir)

## Data Structures & Algorithms

* [Roaring Bitmaps](https://roaringbitmap.org) - A better compressed bitset

## People

* Javascript
	* [Dan Abramov]()
	* [Pete Hunt]()
	* [Sindre Sorhus]()
* .Net
	* [Jon Skeet's coding blog](https://codeblog.jonskeet.uk) (Jon Skeet)
	* [Code, code and more code](https://blog.marcgravell.com) (Marc Gravel)
	* [Fabulous Adventures in Coding](https://ericlippert.com) (Eric Lipert)

## Software Engineering
* Patterns
	* [Martin Fowler](https://martinfowler.com)
	* [Enterprise Integration Patterns](http://www.enterpriseintegrationpatterns.com)
* Processes
	* [CMMI](http://cmmiinstitute.com)
* Architecture
	* [TOGAF](http://www.opengroup.org/subjectareas/enterprise/togaf) (OpenGroup)
	* [Zachman](https://www.zachman.com)
* Reference Models
	* [SCOR - Supply Chain Reference Model](https://www.apics.org/apics-for-business/frameworks/scor) (APICS)
	* [CAUDIT - Higher Education Reference Architecture](https://www.caudit.edu.au/EA-Framework)

# Tools & Services

## Design
* [Sketch](https://www.sketchapp.com) - 
  * [Cabana](https://cabanadesignsystem.com) - Design System for Sketch
* [Figma](https://www.figma.com) - 
* [lunacy](https://icons8.com/lunacy) - 

## Content

* Photos
  * [Burst](https://burst.shopify.com) - Free stock photos for websites and commercial use
  * [Unsplash](http://unsplash.com) - Beautiful, free photos.
* Symbols
  * [HTML Symsols](https://www.toptal.com/designers/htmlarrows/symbols) - HTML Currency Symbols, Currency Entities and ASCII Currency Character Code Reference

## Spreadsheet

* [Google Sheets](https://www.google.com/sheets)
* [Fieldbook](https://fieldbook.com)

## CMS

* [Publii](https://getpublii.com) - Make an extremely safe, fast and stylish static blog website in minutes.

## CRM
* 

## HR
* [teamdeck](https://teamdeck.io)

## Issue Management
* [JIRA](www.atlassian.com/jira)

## Invoicing
* [Elorus](https://www.elorus.com)

## Communications
* [Slack](https://slack.com) - Where Work Happens
* [Rocket.Chat](https://rocket.chat) - The leading free open source team chat Slack alternative. 
* [Intercom]() - Catch, convert and keep more customers
* [Indemandly](https://indemandly.com) - Simple, powerful, & versatile contact tool that you can stick on your website and social media. 

## Security
* [Gpg4win](https://www.gpg4win.org) - A secure solution
* [Keybase](https://keybase.io) - Security app for mobile phones and computers

## Misc.
* [For the Badge](https://forthebadge.com) - Badges for badges' sake.
