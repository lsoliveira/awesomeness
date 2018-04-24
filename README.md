# Overview
_Awesomeness_ is a comprehensive list of technical resources related to IT systems architecture, design and implementation.

# Backend

## .Net
### Distributed systems

* Actor based
  * [Orleans](https://dotnet.github.io/orleans) (Microsoft) - A straightforward approach to building distributed, high-scale applications in .NET.
  * [Akka.Net](https://getakka.net) - Build powerful concurrent & distributed applications more easily.
  * [Orleankka](http://orleanscontrib.github.io/Orleankka) - Functional extension for Microsoft Orleans framework. 
  * [Proto.Actor](http://proto.actor) - Ultra fast distributed actors for Go, C# and Java/Kotlin
* Event Driven
  * [Cirqus](https://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework
  * [NEventStore](http://neventstore.org) - A persistence agnostic Event Store for .NET
  * [EventFlow](http://docs.geteventflow.net) - EventFlow is a basic CQRS+ES framework designed to be easy to use
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
  * [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types.
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
  * [LinqOptimizer](http://nessos.github.io/LinqOptimizer) - An automatic query optimizer-compiler for Sequential and Parallel LINQ. 
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
### Languages & Compilers
* [Irony](https://github.com/IronyProject/Irony) - .NET Language Implementation Kit.
* [Flee](https://github.com/mparlak/Flee) - Fast Lightweight Expression Evaluator.
* [Sparche](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) (StackExchange) - A lightweight, fast and flexible parsing library for C#.
### Framework specifics (seria
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

## Java
### Distributed systems
* [Akka](https://akka.io)
### Services
### Data Access
* [Calcite](https://calcite.apache.org) (Apache)

## Python
### Services
* [sandman2](https://github.com/jeffknupp/sandman2)

## Javascript

### Awesome
* [Awesome GraphQL](https://github.com/chentsulin/awesome-graphql)
* [Automatic API](https://github.com/dbohdan/automatic-api)
### REST
* [ActionHero](https://www.actionherojs.com)
* [Tyk](https://tyk.io)
* [Kong](https://getkong.org)
### [GraphQL](graphql.org)
* [Prisma](https://www.prismagraphql.com)
* [Apollo](https://github.com/apollographql/apollo-server)
* [Graphile](https://www.graphile.org)
* [Join-Monster](https://github.com/stems/join-monster)
* [gestalt](https://github.com/charlieschwabacher/gestalt)
* [sql-to-graphql](https://github.com/rexxars/sql-to-graphql)
* [Altair](https://altair.sirmuel.design) - A beautiful feature-rich GraphQL Client for all platforms
### Serverless
* [serverless](https://serverless.com)
* [serverless-offline](https://github.com/dherault/serverless-offline)
* [serverless-babel-starter](https://github.com/postlight/serverless-babel-starter)
### Data-access
* [EventStore](https://eventstore.org) - The open-source, functional database with Complex Event Processing in JavaScript.

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
* Frameworks
	* [CSS-Blocks](http://css-blocks.com)
	* [SaSS](https://sass-lang.com)
	* [LeSS](http://lesscss.org)
* Email
	* [MJML](https://mjml.io) - The only framework that makes responsive email easy
	* [Foundation For Emails](https://foundation.zurb.com/emails.html) - Quickly create responsive HTML emails that work. Even on Outlook.

## Javascript

### Knowledge Base
* [Front End Toolkit](https://github.com/devbridge/Front-End-Toolkit)
* [Best of JS](https://bestof.js.org)
* [Awesome](https://github.com/sindresorhus/awesome) - Curated list of awesome lists

### UX Frameworks
* [Bootstrap](https://getbootstrap.com) - Build responsive, mobile-first projects on the web
	* [Material Design for Bootstrap](https://mdbootstrap.com)
	* [Shards](https://designrevision.com/downloads/shards) - A free and modern UI toolkit for web makers
* [Carbon](http://carbondesignsystem.com) (IBM)
* [Stencil](https://stenciljs.com)
* [boundless](https://boundless.js.org) - UI toolkit that was conceived to abstract away difficult interface patterns

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
	* [dygraphs](http://dygraphs.com) - Fast, flexible open source JavaScript charting library
	* [sigmajs](http://sigmajs.org) - Sigma is a JavaScript library dedicated to graph drawing
	* [cytoscape](http://js.cytoscape.org) - Graph theory / network library for analysis and visualisation
	* [cubismjs](https://square.github.io/cubism) (Square) - Time Series Visualization
	* [taucharts](https://www.taucharts.com) - Flexible javascript charting library for data exploration
	* [echarts](http://echarts.baidu.com) (Baidu) - A powerful, interactive charting and visualization library for browser
	* [chartjs](http://www.chartjs.org) - Simple yet flexible JavaScript charting for designers & developers
	* [chartist](https://gionkunz.github.io/chartist-js) - Simple responsive charts
* Maps
	* [pigeon-maps](https://mariusandra.github.io/pigeon-maps)
* Utilities
	* [Dinero.js](https://sarahdayan.github.io/dinero.js) - Dinero.js is a library for working with monetary values in JavaScript
* Tours
	* [Driver](http://kamranahmed.info/driver) - Light-weight, no-dependency, vanilla JavaScript engine to drive user's focus across the page

### Tooling
* [bit](https://bitsrc.io) - Components are building blocks. You are the architect.
* [Webpack](https://webpack.js.org) - Bundle your assets
	* [Speed Measure](https://github.com/stephencookdev/speed-measure-webpack-plugin) - See how fast (or not) your plugins and loaders are, so you can optimise your builds
	* [NOW Loader](https://github.com/pranaygp/now-loader) - Deploys the required resource to now
* [turbolinks](https://github.com/turbolinks/turbolinks) - Turbolinks makes navigating your web application faster

### [React](https://reactjs.org)
* Awesome
	* [Awesome React](https://github.com/enaqx/awesome-react)
	* [React Components & Libraries](https://github.com/brillout/awesome-react-components)
	* [Awesome Redux (brillout)](https://github.com/brillout/awesome-redux)
	* [Awesome Redux (xgrommx)](https://github.com/xgrommx/awesome-redux)
	* [Awesome MobX](https://github.com/mobxjs/awesome-mobx)
	* [MobX Ecosystem](https://github.com/xgrommx/mobx-ecosystem)
* State Management
	* REST
		* [tectonic](https://tonyhb.github.io/tectonic)
	* [Redux](https://redux.js.org)
		* [Redux Rest Resource](http://mgcrea.github.io/redux-rest-resource)
		* [Undux](https://github.com/bcherny/undux)
		* [next.js](https://github.com/zeit/next.js)
		* [after.js](https://github.com/jaredpalmer/after.js)
		* [jumpsuit](https://jumpsuit.js.org) - React framework for efficiently building powerful web applications
	* [MobX](https://mobx.js.org)
		* [cans](http://cans.js.org)
		* [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree)
		* [parket](https://github.com/ForsakenHarmony/parket)
		* [FormState](https://github.com/formstate/formstate)
		* [react-remux](https://github.com/vinej/react-remux) - A flux implementation with React and Mobx
	* Tools
		* [immutable.js](https://facebook.github.io/immutable-js) (Facebook)
		* [Immer](https://github.com/mweststrate/immer)
		* [unistore](https://github.com/developit/unistore)
		* [uniforms](https://github.com/vazco/uniforms) - A set of React libraries for building forms
* Development Frameworks
	* [next.js](https://github.com/zeit/next.js)
	* [next-offline](https://github.com/hanford/next-offline)
	* [DVA](https://github.com/dvajs/dva)
	* [Create React App](https://github.com/facebook/create-react-app)
	* [rekit](http://rekit.js.org)
* UX Frameworks
	* [Gestalt](https://pinterest.github.io/Card) (Pinterest)
	* [Grommet](http://grommet.io) (Hewlett Packard)
	* [Material UI](http://www.material-ui.com)
	* [Ant Design](https://ant.design)
	* [React Desktop](http://reactdesktop.js.org)
	* [Semantic UI](https://react.semantic-ui.com)
	* [Blueprint](http://blueprintjs.com)
	* [React Bootstrap](https://react-bootstrap.github.io)
	* [Office UI Fabric](https://developer.microsoft.com/en-us/fabric#/components) (Microsoft)
	* [react-md](https://react-md.mlaursen.com)
	* [modulz](https://www.modulz.co/showcase) - An open–source collection of styles, components, patterns, resources & more
	* [Clarity Design System](https://vmware.github.io/clarity) (VMWare) - UX guidelines, HTML/CSS framework, and Angular components working together to craft exceptional experiences
			[Design System React](https://react.lightningdesignsystem.com) (SalesForce) - Design System React is an implementation of the Lightning Design System
* Component/CSS frameworks
	* [Aphrodite](https://github.com/Khan/aphrodite) (Khan Academy)
	* [glamor](https://github.com/threepointone/glamor)
	* [glamorous](https://github.com/paypal/glamorous) (PayPal)
	* [emotion](https://emotion.sh)
	* [Radium](http://formidable.com/open-source/radium) (Formidable Labs)
	* [styled components](https://www.styled-components.com) - Visual primitives for the component age
	* [reas](https://reas.js.org) - A minimalist and highly customizable component system
* Charts & graphics
	* [Victory](http://formidable.com/open-source/victory) (Formidable Labs) - React.js components for modular charting and data visualization
	* [recharts](http://recharts.org) - A composable charting library built on React components
	* [react-vis](http://uber.github.io/react-vis) (Uber) -
	* [reactivemaps](https://github.com/appbaseio/reactivemaps) - A data aware UI components library for building realtime maps
* Animations
	* [Pose](https://popmotion.io/pose)
	* [react-spring](https://github.com/drcmda/react-spring) - Helping react-motion and animated to become best friends
	* [popmotion](https://github.com/Popmotion/popmotion) - A functional, reactive animation library
	* [react-move](https://github.com/react-tools/react-move) - Beautiful, data-driven animations for React
	* [animated](https://github.com/animatedjs/animated) - Declarative Animations Library for React and React Native
	* [react-motion](https://github.com/chenglou/react-motion) - A spring that solves your animation problems
* Testing
	* [react-testing-library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* Utilities
	* [react-with-gesture](https://github.com/drcmda/react-with-gesture) - Little helper for component-tied mouse/touch gestures

### [Angular](https://angular.io)
* Awesome
	* [awesome-angular](https://github.com/gdi2290/awesome-angular)
	* [awesome-angular2](https://github.com/amcdnl/awesome-angular2)
* Development frameworks
	* [Nrwl Nx](https://nrwl.io/nx) - An open source toolkit for enterprise Angular applications
* UX Frameworks
	* [Angular Material](https://material.angular.io)
	* [awesome-angular-components](https://github.com/brillout/awesome-angular-components)

### [Vue.js](https://vuejs.org)
* Development Frameworks
	* [NUXT](https://nuxtjs.org) - Universal Vue.js Applications
* UX Frameworks
	* [Material Design for Bootstrap](https://mdbootstrap.com/vue)
	* [iView](https://www.iviewui.com) - A high quality UI Toolkit based on Vue.js

### [Ember.js](https://www.emberjs.com)
* Libraries
	* [ember-table](http://opensource.addepar.com/ember-table)

### Other frameworks
* [Preact](https://preactjs.com)
* [Inferno](https://infernojs.org)
* [svelte](https://svelte.technology)
* [Glimmer.js](https://glimmerjs.com)
* [Knockout](http://knockoutjs.com)
* [Mithril](https://mithril.js.org)
* [Aurelia](http://aurelia.io)
* [Meteor](https://www.meteor.com)
* [Ionic](https://ionicframework.com)
	* [Stencil](https://stenciljs.com)

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
	* [DotVVM](https://github.com/riganti/dotvvm) - Open source MVVM framework for Web Apps
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

# Databases
## Relational
### Systems
* [PostgreSQL](https://www.postgresql.org)
	* [postgrest](https://postgrest.com)
	* [postgres](https://postgres.rest)
	* [zombodb](https://github.com/zombodb/zombodb) - Making Postgres and Elasticsearch work together like it's 2018
	* [migra](https://migra.djrobstep.com) - A schema comparison tool for PostgreSQL.
	* [Citus Data](https://www.citusdata.com) - Worry-Free Postgres for SaaS
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
## Android

# Development
* [Flutter](https://flutter.io)

# Profiling
* [profilo](https://facebookincubator.github.io/profilo)

## iOS

# Analytics
* Self Service
	* [Metabase](https://www.metabase.com)
	* [DatabaseFlow](https://databaseflow.com)

# Machine Learning

## Libraries
* Python
	* [NumPY](www.numpy.org)
	* [Pandas](https://pandas.pydata.org)
	* [scikit-learn](http://scikit-learn.org/stable)
	* [spaCy](https://spacy.io)
	* [Dask](https://dask.pydata.org/en/latest)
	* [Numba](https://numba.pydata.org)

## Notebooks
* [Zepellin](https://zeppelin.apache.org)
* [jupyter](http://jupyter.org)

# DevOps
## Web servers, Reverse Proxies and Load Balancers
* [nginx](https://www.nginx.com) - 
* [HAProxy](http://www.haproxy.org) - The Reliable, High Performance TCP/HTTP Load Balancer
* [Apache](https://httpd.apache.org) (Apache)
* [traefik](https://traefik.io) - Modern HTTP reverse proxy and load balancer made to deploy microservices with ease
## App Servers
* [Tomcat](http://tomcat.apache.org) (Apache)
## Caching
* Varnish
## Serverless
* Frameworks
	* [OpenWhisk](https://openwhisk.apache.org) (IBM)
## Deployment
* Docker
	* [Swarm](https://docs.docker.com/engine/swarm)
* [Kubernetes](https://kubernetes.io) (Google) - Automating deployment, scaling, and management of containerized applications
	* [skaffold](https://github.com/GoogleCloudPlatform/skaffold) - Easy and Repeatable Kubernetes Development
	* [Continuous Pipe](https://continuouspipe.io) - Continuous deployment solution for your containerized applications to Kubernetes clusters
* Mesos (Apache)
* Tools
	* [Grail](https://eng.uber.com/grail) (Uber)
	* [osquery](https://osquery.io) (Facebook)
	* [Spinnaker](https://www.spinnaker.io) (Netflix) - Fast, safe, repeatable deployments
## Tools
* Windows Consoles
	* [Cmder](cmder.net)
	* [ConEmu](https://conemu.github.io)
	* [Babun](babun.github.io)
	* [Clink](https://mridgers.github.io/clink)
* Remote Desktop clients
	* [Remote Desktop Manager](https://remotedesktopmanager.com/home/download)
* Chat
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

## Tools & Services

### Design
* [Sketch](https://www.sketchapp.com)
* [Figma](https://www.figma.com)
* [lunacy](https://icons8.com/lunacy)

### Spreadsheet
* [Google Sheets](https://www.google.com/sheets)
* [Fieldbook](https://fieldbook.com)

### CRM
*

### HR
* [teamdeck](https://teamdeck.io)

### Issue Management
* [JIRA](www.atlassian.com/jira)

## Invoicing
* [Elorus](https://www.elorus.com)

### Communications
* [Slack](https://slack.com)
* [Rocket.Chat](https://rocket.chat)

### Security
* [Gpg4win](https://www.gpg4win.org) - A secure solution
* [Keybase](https://keybase.io) - Security app for mobile phones and computers

### Misc.
* [For the Badge](https://forthebadge.com) - Badges for badges' sake.