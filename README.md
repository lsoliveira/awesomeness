# Overview
_Awesomeness_ is a comprehensive list of technical resources related to IT systems architecture, design and implementation.

# Backend

## .Net
### Awesome

### Architectures
* [CoolStore](github.com/vietnam-devs/coolstore-microservices) - A containerized polyglot microservices consisting of services based on .NET Core, NodeJS and more running on service mesh (istio).
* [DShop](github.com/devmentors/DNC-DShop.Common) - Distributed .NET Core.
* [eShopOnContainers](github.com/dotnet-architecture/eShopOnContainers) (Microsoft) - Easy to get started sample reference microservice and container based application.

### Distributed systems
* Actor based
  * [Orleans](dotnet.github.io/orleans) (Microsoft) - A straightforward approach to building distributed, high-scale applications in .NET.
  * [Akka.Net](getakka.net) - Build powerful concurrent & distributed applications more easily
    * [Lighthouse](github.com/petabridge/lighthouse) - A simple service discovery platform for Akka.Cluster
  * [Orleankka](orleanscontrib.github.io/Orleankka) - Functional extension for Microsoft Orleans framework 
  * [Proto.Actor](proto.actor) - Ultra fast distributed actors for Go, C# and Java/Kotlin
* Event Driven
  * [Cirqus](github.com/d60/Cirqus) - d60 event sourcing + CQRS framework
  * [Akkatecture](akkatecture.net/) - cqrs and event sourcing for dotnet core 
  * [NEventStore](neventstore.org) - A persistence agnostic Event Store for .NET
  * [EventFlow](docs.geteventflow.net) - EventFlow is a basic CQRS+ES framework designed to be easy to use
  * [Brighter](www.goparamore.io) - Command Processor & Dispatcher implementation that can be used as a lightweight library in other projects. 
  * [Its.CQRS](github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
  * [Aggregates.NET](github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServiceBus and GetEventStore
  * [NES](github.com/elliotritchie/NES) - Lightweight framework that helps you build domain models when you're doing event sourcing.
  * [Xer.Cqrs](github.com/XerProjects/Xer.Cqrs) - A simple CQRS library
  * [CQRSlite](github.com/gautema/CQRSlite) - A lightweight framework for helping writing CQRS and Eventsourcing applications in C#
* Queueing
  * [RawRabbit](github.com/pardahlman/RawRabbit) - A modern .NET framework for communication over RabbitMq
* Service Bus
  * [Mass Transit](masstransit-project.com) - Free, open source, lightweight message bus for creating distributed applications using the .NET framework.
  * [NServiceBus](particular.net/nservicebus) - The most developer-friendly service bus for .NET
  * [Zebus](github.com/Abc-Arbitrage/Zebus) - A lightweight Peer to Peer Service Bus
  * [Obvs](christopherread.github.io/Obvs) - An observable µServiceBus .NET library that wraps the complexities of your particular message transport in simple Rx based interfaces. Supported transports include: ActiveMQ, RabbitMQ, NetMQ, EventStore, and Kafka.
* Utilities
  * [Foundatio](github.com/FoundatioFx/Foundatio) - Pluggable foundation blocks for building distributed apps.
  * [Projac](github.com/BitTacklr/Projac) - A set of .NET projection libraries

### Services
* REST
  * [SaasKit](github.com/saaskit/saaskit) - A developer toolkit for building SaaS applications.
  * [refit](paulcbetts.github.io/refit) - The automatic type-safe REST library for .NET Core, Xamarin and .NET.
  * [RestSharp](restsharp.org) - Simple REST and HTTP API Client for .NET.
  * [RestEase](github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library for .NET Standard 1.1 and .NET Framework 4.5 and higher, which is simple and customisable.
  * [RestLess](github.com/letsar/RestLess) - The automatic type-safe-reflectionless REST API client library for .Net Standard.
  * [HttpClientGoodies.NET](github.com/jeffijoe/httpclientgoodies.net) - Useful utilities for the .NET HttpClient.
  * [autorest](github.com/Azure/autorest) - OpenAPI (f.k.a Swagger) Specification code generator.
  * [Halcyon](github.com/visualeyes/halcyon) - A HAL implementation for ASP.NET.
  * [JSON API .Net Core](github.com/json-api-dotnet/JsonApiDotNetCore) - A [{ json:api }](jsonapi.org/) web application framework.
  * [NetCoreStack Flying Proxy](github.com/NetCoreStack/Proxy) - The type-safe REST library for .NET Standard 2.0.
  * [NSwag](github.com/RSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, Web API and TypeScript.
  * [OData Web API](github.com/OData/WebApi): A server library built upon ODataLib and WebApi.
  * [Swashbuckle.AspNetCore](github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger tools for documenting API's built on ASP.NET Core.
  * [RService.IO](github.com/Stoom/RService.IO) - Light weight REST service framework for ASP.NET Core.
  * [OpenRasta](openrasta.org) - Open-source .NET framework for building everything web, from web sites to RESTful APIs.
* Web Sockets
  * [Fleck](github.com/statianzo/Fleck) - C# Websocket Implementation
  * [SignalR](signalr.net) - Incredibly simple real-time web for .NET
  * [WampSharp](wampsharp.net) - A C# implementation of WAMP (The Web Application Messaging Protocol)
  * [SuperSocket](github.com/kerryjiang/SuperSocket) - SuperSocket is a light weight, cross platform and extensible socket server application framework.
  * [websocket-sharp](sta.github.io/websocket-sharp) - A C# implementation of the WebSocket protocol client and server
  * [NetGain](github.com/StackExchange/NetGain) (StackExchange) - A high performance websocket server library powering Stack Overflow.
* GraphQL
  * [GraphiQL.NET](github.com/JosephWoodward/graphiql-dotnet) - GraphiQL middleware for ASP.NET Core
  * [GraphQL.NET](github.com/mkmarek/graphql-dotnetcore) - Library for creating GraphQL servers with .NET core.
  * [GraphQL for .NET](github.com/graphql-dotnet/graphql-dotnet) - This is an implementation of [Facebook's GraphQL](github.com/facebook/graphql) in .NET.
  * [parser](github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET
  * [GraphQL Conventions Library for .NET](github.com/graphql-dotnet/conventions) - GraphQL Conventions Library for .NET
  * [GraphQl.AspNetCore](github.com/JuergenGutsch/graphql-aspnetcore) - ASP.NET Core MiddleWare to create a GraphQL end-point
* API
  * [CondenserDotNet](github.com/Drawaes/CondenserDotNet) - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul lib
  * [Ocelot](threemammals.com/ocelot) - Open Source .NET Core API Gateway
* Middleware 
  * [Polly](github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.
  * [steeltoe](steeltoe.i/) (Pivotal) - Open source project that enables .NET developers to implement industry standard best practices when building resilient microservices for the cloud.
  * [Nancy](github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono.
  * [peasy](github.com/peasy/Peasy.NET) - A middle tier micro-framework for .NET
  * [LightNode](neuecc.github.io/LightNode) - Micro RPC/REST Framework built on OWIN
  * [Nelibur](github.com/Nelibur/Nelibur) - Message based webservice framework on the pure WCF.
  * [Xer.Cqrs](github.com/XerProjects/Xer.Cqrs) - A simple CQRS library. 
  * [CLSA.NET](cslanet.com) - Software development framework that helps you build a reusable, maintainable object-oriented business layer for your app.
  * [CAP](github.com/dotnetcore/CAP) - CAP is a library based on .Net standard, which is a solution to deal with distributed transactions, also has the function of EventBus, it is lightweight, easy to use, and efficiently.
  * [RestBus](github.com/tenor/RestBus) - Easy, Service Oriented, Asynchronous Messaging and Queueing for .NET
  * [Rebus](github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET
  * [Warewolf](github.com/Warewolf-ESB/Warewolf) - Effortless Microservice Design and Integration. This repository includes the code-base for the Warewolf Studio and Server.
  * [DotNetty](github.com/Azure/DotNetty) - Port of [Netty](github.com/netty/netty), asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.
  * [Halibut](github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
  * [microdot](github.com/gigya/microdot) - An open source .NET microservices framework
  * [EmbedIO](unosquare.github.io/embedio) - A tiny, cross-platform, module based, MIT-licensed web server for .NET Framework and .NET Core
* Network
  * [edtFTPnet](enterprisedt.com/products/edtftpnet) - The popular free .NET FTP library
  * [FluentFTP](github.com/robinrodricks/FluentFTP) - An FTP and FTPS client for .NET & .NET Standard, optimized for speed.
  * [SSH.NET](github.com/sshnet/SSH.NET) - Secure Shell (SSH) library for .NET, optimized for parallelism.
  * [Ether.Network](github.com/Eastrall/Ether.Network) - Simple and fast C# networking library. Compatible with .NET Standard 1.3 and 2.0

### Data Access
* ORM
  * [Dapper](github.com/StackExchange/Dapper) (StackExchange)
  * [NReco](www.nrecosite.com/dalc_net.aspx) - CRUD operations, dynamic queries, SQL generation in C#
  * [DbExtensions](maxtoroq.github.io/DbExtensions) - Data-access framework with a strong focus on query composition, granularity and code aesthetics. 
  * [Insight.Database](github.com/jonwagner/Insight.Database) - Fast, lightweight .NET micro-ORM
  * [LimeBean](nick-lucas.github.io/LimeBean) - Simple and concise API for accessing ADO.NET data sources. 
  * [Simple.Data](github.com/markrendle/Simple.Data) - A light-weight, dynamic data access component for C# 4.0
* Persistence
  * [marten](jasperfx.github.io/marten) - Polyglot Persistence for .NET Systems using the Rock Solid PostgreSQL Database
  * [ReactiveETL](github.com/madhon/ReactiveETL) - Rewrite of Rhino ETL using the reactive extensions for .Net
  * [SqlKata](sqlkata.com) - The powerful C# sql query builder
* Caching
  * [Akavache](github.com/akavache/Akavache) - An asynchronous, persistent key-value store.
* Full text
  * [NEST](github.com/elastic/elasticsearch-net) - Elasticsearch.Net & NEST
  * [SimMetrics.NET](github.com/StefH/SimMetrics.Net) - Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman).
* Migrations
  * [Fluent Migrator](github.com/fluentmigrator/fluentmigrator) - Fluent migrations framework for .NET
  * [DbUp](dbup.github.io) - DbUp is a .NET library that helps you to deploy changes to SQL Server databases.

### Scheduling & Job Management
* Scheduling
  * [Hangfire](www.hangfire.io) - An easy way to perform background processing in .NET and .NET Core applications. No Windows Service or separate process required.
  * [Quartz.NET](www.quartz-scheduler.net) - Full-featured, open source job scheduling system that can be used from smallest apps to large scale enterprise systems.
  * [FluentScheduler](github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* State Machines & Workflow
  * [Stateless](github.com/dotnet-state-machine/stateless) - A simple library for creating state machines in C# code
  * [Automatonymous](github.com/MassTransit/Automatonymous) - A state machine library for .Net - 100% code - No doodleware
  * [workflow-core](github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard
  * [Core WF](github.com/dmetzgar/corewf) - A port of the Windows Workflow Foundation (WF) runtime to the .NET Standard.
  * [Durable Task Framework](github.com/Azure/durabletask) (Microsoft) - Write long running persistent workflows in C# using the async/await capabilities.
  * [State Machine](www.appccelerate.com/statemachine.html) - Our applications are full of state machines. Enabled and disabled UI elements, abstractions of devices and business logic. Implementing these state machines with the state pattern is overly complicated. Therefore, we implemented a state machine component that allows implementing a state machine as a single class. This reduces complexity and needed effort dramatically. See for yourself.
  * [LiquidState](github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET 
* Misc.
  * [NCronTab](github.com/atifaziz/NCrontab) - Crontab for .NET

### IoC
* [StructureMap](github.com/structuremap/structuremap) - A Dependency Injection/Inversion of Control tool for .NET.
* [Autofac](autofac.org) - Autofac is an addictive Inversion of Control container for .NET Core, ASP.NET Core, .NET 4.5.1+, Universal Windows apps, and more.
* [Ninject](www.ninject.org) - Open source dependency injector for .NET
* [Simple Injector](simpleinjector.org) - Easy-to-use Dependency Injection (DI) library for .NET 4+ that supports Silverlight, Windows Phone, Windows 8 including Universal apps and Mono. 
* [Scrutor](github.com/khellang/Scrutor) - Assembly scanning and decoration extensions for Microsoft.Extensions.DependencyInjection    

### Deployment
* [WiX](wixtoolset.org) - The most powerful set of tools available to create your windows installation experience.
* [Wax](github.com/tom-englert/Wax) - An interactive editor for WiX setup projects.
* [Topshelf](topshelf-project.com) - Put Your Apps on the Topshelf.
* [Squirrel](github.com/squirrel/squirrel.windows) - An installation and update framework for Windows desktop apps.
* [dotnet-win32-service](github.com/dasMulli/dotnet-win32-service) - Helper classes to set up and run as windows services directly on .net core. A ServiceBase alternative.
* [Catlight](catlight.io) - Notifier for developers

### Performance & Monitoring
* [BenchmarkDotNet](benchmarkdotnet.org) - Powerful .NET library for benchmarking.
* [AppMetrics](www.app-metrics.io) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application. 
* [Metrics.NET](github.com/Recognos/Metrics.NET) - The Metrics.NET library provides a way of instrumenting applications with custom metrics (timers, histograms, counters etc) that can be reported in various ways and can provide insights on what is happening inside a running application.
* [Warden](github.com/warden-stack/Warden) - Define "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.  
* [NBench](github.com/petabridge/NBench) - Cross-platform performance benchmarking and testing framework for .NET applications.
* [Prefix](stackify.com/prefix) - Understand what your code is doing and find bugs you didn’t even know existed. 

### Algorithms & Data Structures
* Algorithms
  * [C# Algorithms](github.com/aalhour/C-Sharp-Algorithms) - A C# plug-and-play class-library project of standard Data Structures and Algorithms.
  * [Algorithmia](github.com/SolutionsDesign/Algorithmia) - Algorithm and data-structure library for .NET 4.5.2+/Netstandard 2.0+.
  * [CodeJam](github.com/rsdn/CodeJam) - Set of handy reusable .NET components that can simplify your daily work and save your time when you copy and paste your favorite helper methods and classes from one project to another.
* Data structures
  * [C5](github.com/sestoft/C5) - C5 generic collection library for C#/.NET.
  * [Optional](github.com/nlkl/Optional) - A robust option type for C#
  * [Enums.NET](github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
  * [Shielded](github.com/jbakic/Shielded) - A strict and mostly lock-free Software Transactional Memory (STM) for .NET
  * [ByteSize](github.com/omar/ByteSize) - Utility class that makes byte size representation in code easier by removing ambiguity of the value being represented.
  * [Disruptor.net](github.com/disruptor-net/Disruptor-net) - Port of LMAX Disruptor to .NET
* Functional programming
  * [Functional Extensions for C#](github.com/vkhorikov/CSharpFunctionalExtensions) - This library helps write code in more functional way.
  * [LanguageExt](github.com/louthy/language-ext) - C# functional language extensions - a base class library for functional programming
* Reactive programming
  * [Rx.NET](github.com/Reactive-Extensions/Rx.NET) - The Reactive Extensions for .NET
  * [Reactive Streams .NET#](github.com/reactive-streams/reactive-streams-dotnet) - Reactive Streams for .NET
  * [Qactive](github.com/RxDave/Qactive) - A reactive queryable observable framework.
  * [sodium](sodium.nz/) - A functional reactive programming library for multiple programming languages.
  * [Dynamic Data](github.com/RolandPheasant/DynamicData) - Reactive collections based on Rx.Net.
  * [Streams](nessos.github.io/Streams) - A lightweight F#/C# library for efficient functional-style pipelines on streams of data. 
* Mapping 
  * [AutoMapper](github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET.
  * [TinyMapper](github.com/TinyMapper/TinyMapper) - A quick object-object mapper for .NET.
  * [ExpressMapper](github.com/fluentsprings/ExpressMapper) - Mapping .Net types.
  * [AgileMapper](github.com/agileobjects/AgileMapper) - A zero-configuration, highly-configurable object-object mapper with viewable execution plans.
  * [Stringly.Typed](github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types
* Patterns
  * [Mediator.Net](github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported
  * [MediatR](github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET 
* Units
  * [UnitsNet](github.com/angularsen/UnitsNet) - Makes life working with units of measurement just a little bit better.
  * [Humanizer](github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities * [NodaMoney](github.com/remyvd/NodaMoney) - NodaMoney provides a library that treats Money as a first class citizen and handles all the ugly bits like currencies and formatting.
  * [NodaTime](nodatime.org) - A better date and time API for .NET
  * [DateTimeExtensions](github.com/joaomatossilva/DateTimeExtensions) - This project is a merge of several common DateTime operations in the form of extensions to System.DateTime, including natural date difference text (precise and human rounded), holidays and working days calculations on several culture locales.
  * [Exceptionless.DateTimeExtensions](github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods
  * [UnitConversion](github.com/gkampolis/UnitConversion) - Expansible Unit Conversion Library for .Net Core and .Net Framework
  * [DeviceId](github.com/MatthewKing/DeviceId) - A simple library providing functionality to generate a 'device ID' that can be used to uniquely identify a computer.
* Extensions & LINQ
  * [ExtraLINQ](github.com/mariusschulz/ExtraLINQ) - ExtraLINQ provides a set of extension methods for various .NET sequence types.
  * [MoreLINQ](github.com/morelinq/MoreLINQ) - Extensions to LINQ to Objects.
  * [Mono.Linq.Expressions](github.com/jbevain/mono.linq.expressions) - Helper library to complement the System.Linq.Expressions namespace.
  * [Z.ExtensionMethods](github.com/zzzprojects/Z.ExtensionMethods) - Enhance the .NET Framework with over 1000 extension methods.
  * [Extend](github.com/DaveSenn/Extend) - Extension methods for .Net.
  * [dotNetExt](github.com/crpietschmann/dotnetext) - .NET Extension Method Library
  * [Relinq](github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
  * [LinqOptimizer](nessos.github.io/LinqOptimizer) - An automatic query optimizer-compiler for Sequential and Parallel LINQ
  * [Type Convert](github.com/deniszykov/typeconvert) - C# utilities for convertion between types, type construction and inspection 

### Geolocation
* [OsmSharp](www.osmsharp.com) - C# library to work with OpenStreetMap (OSM) data.
* [NetTopologySuite](github.com/NetTopologySuite/NetTopologySuite) - A .NET GIS solution that is fast and reliable for the .NET platform.
* [SharpMap](github.com/SharpMap/SharpMap) - An easy-to-use mapping library for use in web and desktop applications.
* [GeoJSON.NET](github.com/GeoJSON-Net/GeoJSON.Net) - .Net library for GeoJSON types & corresponding Json.Net (de)serializers

### Data science
* Math
  * [Math.NET](www.mathdotnet.com) - Open-source initiative to build and maintain toolkits covering fundamental mathematics, targetting advanced but also every day needs of .Net developers.
  * [Microsoft Automatic Graph Layout](github.com/Microsoft/automatic-graph-layout) (Microsoft) - A set of tools for graph layout and viewing.
  * [ALGLIB](www.alglib.net) - Cross-platform numerical analysis and data processing library.
  * [autodiff](github.com/alexshtf/autodiff) - A .NET library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions.
  * [GeometRi](github.com/RiSearcher/GeometRi) - Simple and lightweight computational geometry library for .Net
  * [MathExtensions)](github.com/TommasoScalici/MathExtensions) - Library for .NET that aims to extend the basic but yet incomplete System.Math, with simple and useful extensions methods regarding various mathematical domains, like methods for combinatorics, sequence analysis, generation and manipulation, random extractions, etc.
* Frameworks
  * [AccordFramework.NET](accord-framework.net) - Machine learning made in a minute 
  * [TensorFlowSharp](github.com/migueldeicaza/TensorFlowSharp) - TensorFlow API for .NET languages
  * [AForge.NET](www.aforgenet.com/framework) - open source C# framework designed for developers and researchers in the fields of Computer Vision and Artificial Intelligence.
  * [Infer.NET](infernet.azurewebsites.net) (Microsoft) - A framework for running Bayesian inference in graphical models.
  * [numl](numl.net) - a general purpose machine learning framework
  * [GeneticSharp](github.com/giacomelli/GeneticSharp) - Fast, extensible, multi-platform and multithreading C# Genetic Algorithm library that simplifies the development of applications using Genetic Algorithms (GAs).
  * [FsLab](fslab.org) - Data science tools: Professional, powerful & cross-platform
  * [Spreads](github.com/Spreads/Spreads) - Series and Panels for Real-time and Exploratory Analysis of Data Streams
  * [Deedle](bluemountaincapital.github.io/Deedle) - Exploratory data library for .NET
  * [SIML](simlbot.com) - Synthetic Intelligence Markup Language
  * [ML-Agents](github.com/Unity-Technologies/ml-agents) - Unity Machine Learning Agents

### Testing
* Test frameworks
  * [nUnit](nunit.org) - unit-testing framework for all .Net languages.
  * [xUnit](xunit.github.io) - Free, open source, community-focused unit testing tool for the .NET Framework.
  * [MSTest](msdn.microsoft.com/en-us/library/hh694602.aspx) (Microsoft)
  * [Fixie](fixie.github.io) - Conventional Testing for .NET
* Assertions
  * [Shouldly](github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be!
  * [FluentAssertions](fluentassertions.com) - Fluent API for asserting the results of unit tests that targets .NET Framework 4.5, 4.7, .NET Standard 1.3, 1.6 and 2.0.
  * [Power Assert .NET](github.com/PowerAssert/PowerAssert.Net) - Readable, Writable Test Assertions for .NET
* Data generation
  * [Bogus](github.com/bchavez/Bogus) - A simple and sane fake data generator for C#, F#, and VB.NET. Based on and ported from the famed faker.js. 
  * [Fibber](github.com/Schandlich/Fibber) - An indiscriminate data generator that will generate random data for all properties in a given class based on the property's type vs. its name.
  * [Rant](berkin.me/rant) - Free, all-purpose procedural text generation language developed for .NET.
  * [NBuilder](github.com/nbuilder/nbuilder) - Rapid generation of test objects in .NET
* Mocking
  * [Rhino Mocks](hibernatingrhinos.com/oss/rhino-mocks) - Dynamic mock object framework for .NET
  * [Moq](github.com/moq/moq4) - The most popular and friendly mocking framework for .NET
  * [NSubstitute](github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking libraries.
  * [FakeItEasy](fakeiteasy.github.io) - A .Net dynamic fake framework for creating all types of fake objects, mocks, stubs etc.
  * [Stubbery](markvincze.github.io/Stubbery) - Simple library for creating and running Api stubs in .NET.
* BDD
  * [SpecFlow](specflow.org) - Cucumber for .NET. The open source solution trusted by .NET devs around the world.
  * [xbehave](xbehave.github.io) - xUnit.net extension for describing your tests using natural language.
  * [SpecsFor](github.com/MattHoneycutt/SpecsFor) - Light-weight Behavior-Driven Development framework that focuses on ease of use for *developers* by minimizing testing friction.
  * [NFluent](github.com/tpierrain/NFluent) - Smooth your .NET TDD experience with NFluent!
  * [Machine.Specifications](github.com/machine/machine.specifications) - Context/Specification framework geared towards removing language noise and simplifying tests.
  * [TestStack.BDDfy](github.com/TestStack/TestStack.BDDfy) - BDDfy is the simplest BDD framework EVER!
  * [Storyteller](storyteller.github.io) - Solutions for creating robust, human readable acceptance tests for your .Net or CoreCLR system and a means to create "living" technical documentation.
* Automation
  * [Selenium](www.seleniumhq.org) - Selenium automates browsers.
  * [Atata](atata-framework.github.io) - C#/.NET automated web testing full featured framework
  * [TestStack.White](github.com/TestStack/White) -  Automating rich client applications based on Win32, WinForms, WPF, Silverlight and SWT (Java) platforms.
  * [Managed Windows API](mwinapi.sourceforge.net/) - A collection of .NET components that wrap PInvoke calls to access native API by managed code.
  * [Effort](entityframework-effort.net/) - **E**ntity **F**ramework **F**ake **O**bjectContext **R**ealization **T**ool. It is a powerful tool that enables a convenient way to create automated tests for Entity Framework based applications.
* Load testing
  * [Netling](github.com/hallatore/Netling) - Netling is a load tester client for easy web testing.
* Misc.
  * [Scientist.net](github.com/github/Scientist.net) -  A .NET library for carefully refactoring critical paths.
  * [AutoFixture](github.com/AutoFixture/AutoFixture) - AutoFixture is an open source library for .NET designed to minimize the 'Arrange' phase of your unit tests in order to maximize maintainability.
  * [Papercut](github.com/ChangemakerStudios/Papercut) - Papercut Simple Desktop SMTP Server
  * [.NET Fake JSON Server](github.com/ttu/dotnet-fake-json-server) - Fake JSON Server is a Fake REST API that can be used as a Back End for prototyping or as a template for a CRUD Back End.

### Caching
*  [CacheManager](github.com/MichaCo/CacheManager) - CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.
*  [Cashew](github.com/joakimskoog/Cashew) - A simple and elegant yet powerful HTTP client cache for .NET
*  [LazyCache](github.com/alastairtree/LazyCache) - An easy to use thread safe generics based in memory caching service with a simple developer friendly API for C#.

### Framework specifics
- Languages & Compilers
  - [Irony](github.com/IronyProject/Irony) - .NET Language Implementation Kit.
  - [Flee](github.com/mparlak/Flee) - Fast Lightweight Expression Evaluator.
  - [Sprache](github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.
  - [Pidgin](github.com/benjamin-hodgson/Pidgin) (StackExchange) - A lightweight, fast and flexible parsing library for C#.
* Serialization
  * [Hyperion](github.com/akkadotnet/Hyperion) -  Polymorphic serialization for .NET
  * [Jil](github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil
  * [Wire](github.com/rogeralsing/Wire) - A high performance polymorphic serializer for the .NET framework.
  * [Migrant](github.com/antmicro/Migrant) - Fast and flexible serialization framework usable on undecorated classes.
  * [Utf8Json](github.com/neuecc/Utf8Json) - Fast JSON Serializer for C#
  * [protobuf](silentorbit.com/protobuf) - ProtoBuf is a Google Protocol Buffers implementation by generating custom C# code for your .proto specifications.
  * [protobuf-net](github.com/mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET
  * [Newtonsoft.Json](www.newtonsoft.com/json) - Popular high-performance JSON framework for .NET
  * [Schema.NET](github.com/RehanSaeed/Schema.NET) - Objects turned into strongly typed C# POCO classes for use in .NET.
  * [EDI.NET](github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS formats.
* Reflection
  * [Fasterflect](github.com/buunguyen/fasterflect) - .NET Reflection Made Fast and Simple.
  * [Fast-member](code.google.com/archive/p/fast-member) - .NET reflection is slow... well, kinda slow.
  * [AdvanceDLSupport](github.com/Firwood-Software/AdvanceDLSupport) - Alternative approach to your usual P/Invoke!
  * [Bond](github.com/Microsoft/bond) (Microsoft) - Cross-platform framework for working with schematized data. 
* Code Generation
  * [Sigil](github.com/kevin-montrose/Sigil) - A fail-fast validating helper for .NET CIL generation
  * [Cecil](cecil.pe) - Cecil is a library to inspect, modify and generate .NET programs and libraries.
  * [Testura.Code](github.com/Testura/Testura.Code) - Wrapper around the Roslyn API and used for generation, saving and compiling C# code.
* AOP
  * [AspectCore](github.com/dotnetcore/AspectCore-Framework) - AspectCore is an AOP-based cross platform framework for .NET Standard.
  * [Fody](github.com/Fody/Fody) - Extensible tool for weaving .net assemblies

### Report & PDF Generation
* File handling
  * [FileHelpers](www.filehelpers.net) - Import or export data from fixed length or delimited records in files, strings or streams.
  * [FlatFiles](github.com/jehugaleahsa/FlatFiles) - Reads and writes CSV, fixed-length and other flat file formats with a focus on schema definition, configuration and speed.
  * [FlatMapper](github.com/joaomatossilva/FlatMapper) - FlatMapper is a library to import and export data from and to plain text files.
  * [CsvHelper](joshclose.github.io/CsvHelper) - A library for reading and writing CSV files.
* Office integration
  * [NPOI](github.com/tonyqus/npoi) - .NET library that can read/write Office formats without Microsoft Office installed.
  * [Open XML SDK](github.com/officedev/open-xml-sdk) (Microsoft) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents. 
  * [DocX](github.com/xceedsoftware/DocX) - Fast and easy to use .NET library that creates or modifies Microsoft Word files without installing Word.
  * [ExcelDataReader](github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files
  * [EPPlus](github.com/JanKallman/EPPlus) - Create advanced Excel spreadsheets using .NET
  * [ClosedXML](github.com/ClosedXML/ClosedXML) - Makes it easier for developers to create Excel 2007+ (.xlsx, .xlsm, etc) files.
* PDF generation
  * [PDFSharp](www.pdfsharp.net) - Open Source .NET library that easily creates and processes PDF documents on the fly from any .NET language.
  * [iTextSharp](github.com/itext/itextsharp) - Easy PDF generation and manipulation for Java and .NET developers.
  * [PdfReport.Core](github.com/VahidN/PdfReport.Core) - Code first reporting engine, which is built on top of the [iTextSharp.LGPLv2.Core](github.com/VahidN/iTextSharp.LGPLv2.Core) and [EPPlus.Core](github.com/VahidN/EPPlus.Core) libraries.
* Markdown
  * [Markdig](github.com/lunet-io/markdig) - A fast, powerful, CommonMark compliant, extensible Markdown processor for .NET
  * [CommonMark.NET](github.com/Knagis/CommonMark.NET) - Implementation of CommonMark specification in C# for converting Markdown documents to HTML. 
  * [MarkdownSharp](github.com/StackExchange/MarkdownSharp) (StackExchange) - Open source C# implementation of Markdown processor, used by Stack Overflow.
* Reports
  * [DoddleReport](github.com/matthidinger/DoddleReport) - Generate custom reports (PDF, Excel, etc) from any IEnumerable datasource.

### Email
* [Postal](aboutcode.net/postal) - Create email using ASP.NET MVC views
* [MailKit](github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP. 
* [MailBody](doxakis.github.io/MailBody) - Create transactional email with a fluent interface (.net)
* [RazorMailer](github.com/jonleigh/RazorMailer) - A lightweight framework for sending emails from any .NET platform using Razor templates.

### Logging
* [Logary](logary.github.io) - High performance, multi-target logging, metric, tracing and health-check library for mono and .Net.
* [NLog](github.com/nlog/NLog) - Advanced and Structured Logging for Various .NET Platforms 
* [Elmah](elmah.github.io) - Application-wide error logging facility that is completely pluggable. 
* [log4net](logging.apache.org/log4net) (Apache) - A tool to help the programmer output log statements to a variety of output targets. 
* [Serilog](serilog.net) - Flexible, structured events — log file convenience.
* [StackExchange.Exceptional](github.com/NickCraver/StackExchange.Exceptional) - Error handler used for the Stack Exchange network
* [Essential Diagnostics](github.com/sgryphon/essential-diagnostics) - Additional trace listeners, filters and utility classes for the .NET Framework System.Diagnostics trace logging. 
* [Logazmic](github.com/ihtfw/Logazmic) - Windows log viewer for log4j

### CLI
* Parsers
  * [Command Line Parser](www.appccelerate.com/commandlineparser.html) - Every now and then, we write a little console application to quickly get a job done.
  * [CommandLineUtils](natemcmaster.github.io/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework. 
  * [clipr](github.com/nemec/clipr) - Command Line Interface ParseR for .Net
  * [commandline](github.com/commandlineparser/commandline) - C# command line parser for .NET with F# support
  * [EntryPoint](nick-lucas.github.io/EntryPoint) - Composable CLI Argument Parser for all modern .Net platforms 
  * [Fluent Command Line Parser](github.com/fclp/fluent-command-line-parser) - A simple, strongly typed .NET C# command line parser library using a fluent easy to use interface
  * [PowerArgs](github.com/adamabdelhamed/PowerArgs) - The ultimate .NET Standard command line argument parser
  * [readline](github.com/tonerdo/readline) - A Pure C# GNU-Readline like library for .NET/.NET Core
* Formatters
  * [Colorful.Console](github.com/tomakita/Colorful.Console) - Style your C# console output!
  * [CsConsoleFormat](github.com/Athari/CsConsoleFormat) - .NET C# library for advanced formatting of console output
  * [ConsoleTableExt](github.com/minhhungit/ConsoleTableExt) - A fluent library to print out a nicely formatted table in a console application C#
* Invokers
  * [cmd](github.com/manojlds/cmd) - A C# Library to run external programs / commands in a simpler way. 
  * [CliWrap](github.com/Tyrrrz/CliWrap) - Wrapper for command line interface executables.

### Content Management
* CMS
  * [Orchard](orchardproject.net) - A free, open source, community-focused Content Management System built on the ASP.NET MVC platform.
  * [Umbraco](umbraco.com) - Umbraco is a fully-featured, open source Content Management System loved by thousands for its flexibility and great editing experience. 
  * [BetterCMS](www.bettercms.com) - Better CMS has an intuitive user interface designed to help you make updates to your website content and SEO settings quickly and efficiently. 
  * [Piranha CMS](piranhacms.org) - A lightweight & unobstrusive CMS for ASP.Net Core.
  * [Cofoundry](www.cofoundry.org) - Open Source .NET Core Application Framework & Content Management Platform
* Static Site Generators
  * [Pretzel](github.com/Code52/pretzel) - A site generation tool (and then some) for .NET platforms
  * [Sandra.Snow](github.com/Sandra/Sandra.Snow) - Jekyll inspired static site generation for .NET
  * [Wyam](wyam.io/) - A highly modular and extremely configurable static content generator and toolkit.
* Templating
  * [RazorEngine](antaris.github.io/RazorEngine) - A templating engine built on Microsoft's Razor parsing engine, RazorEngine allows you to use Razor syntax to build dynamic templates.
  * [RazorLight](github.com/toddams/RazorLight) - Template engine based on Microsoft's Razor parsing engine for .NET Core
  * [Nustache](github.com/jdiamond/Nustache) - Logic-less templates for .NET
  * [mustache#](github.com/jehugaleahsa/mustache-sharp) - An extension of the mustache text template engine for .NET.
  * [DotLiquid](dotliquidmarkup.org) - DotLiquid is a templating system ported to the .NET framework from Ruby’s [Liquid Markup](www.liquidmarkup.org/).
  * [Stubble](github.com/stubbleorg/stubble) - Trimmed down {{mustache}} templates in .NET

### Security & Compression
* Compression
  * [SharpZipLib](github.com/icsharpcode/SharpZipLib) - Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
  * [Snappy.Sharp](github.com/jeffesp/Snappy.Sharp) - An implementation of google's Snappy compression format in C#.
  * [SharpCompress](github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.  
  * [LZ4](github.com/MiloszKrajewski/lz4net) - ultra fast compression algorithm - for all .NET platforms
* Hashing
  * [HashLib](archive.codeplex.com/?p=hashlib) - Hash files, streams, common types of data.
* Security
  * [IdentityServer](identityserver.io) - The Identity and Access Control solution that works for you
  * [OpenIddict](github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core
  * [DotNetOpenAuth](dotnetopenauth.net) - Get started with OpenID, OAuth today!
  * [IdentityModel](github.com/IdentityModel/IdentityModel2) - A .NET standard helper library for claims-based identity, OAuth 2.0 and OpenID Connect. 
  * [Stuntman](rimdev.io/stuntman) - Sometimes you need a Stuntman before you send in real, unsuspecting users!
  * [jose-jwt](github.com/dvsekhvalnov/jose-jwt) - Ultimate Javascript Object Signing and Encryption (JOSE) and JSON Web Token (JWT) Implementation for .NET and .NET Core
  * [NWebsec](github.com/NWebsec/NWebsec) - Security libraries for ASP.NET
  * [reCAPTCHA](github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASPNET Core
  * [OwaspHeaders](github.com/GaProgMan/OwaspHeaders.Core) - A .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security
  * [Security](github.com/aspnet/Security) - Middleware for security and authorization of web apps.
  * [Cierge](pwdless.github.io/Cierge-Website) - Open source authentication server (OIDC) that handles user signup, login, profiles, management, and more.
* Cryptography
  * [BCrypt.NET](github.com/BcryptNet/bcrypt.net) - Bringing updates to the original bcrypt package
  * [Bouncy Castle](bouncycastle.org) - A lightweight cryptography API for Java and C#.
  * [libsodium-net](github.com/adamcaudill/libsodium-net) - A secure cryptographic library
  * [StreamCryptor](github.com/bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf
  * [inferno](securitydriven.net/inferno) - .NET crypto done right. Professionally audited.

### Utilities
* Parsers
  * [HAP](html-agility-pack.net) - Html Agility Pack
  * [AngleSharp](anglesharp.github.io) - makes .NET ❤ HTML5
  * [YamlDotNet](github.com/aaubry/YamlDotNet) - .NET library for YAML
  * [Regextra](github.com/amageed/Regextra) - Simplifies some tasks typically solved via regex so that you no longer have (problems){2}.
* Detection
  * [MimeKit](github.com/jstedfast/MimeKit) - A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
  * [DeviceDetector.NET](github.com/totpero/DeviceDetector.NET) - The Universal Device Detection library will parse any User Agent and detect the browser, operating system, device used (desktop, tablet, mobile, tv, cars, console, etc.), brand and model. 
* Configuration
  * [Formo](chrismissal.com/Formo) - Formo allows you to use your configuration file as a dynamic object.
* Validation
  * [FluentValidation](github.com/JeremySkinner/FluentValidation) - A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
  * [valit](github.com/valit-stack/Valit) - Valit is dead simple validation for .NET Core.
* Mics. 
  * [P](github.com/p-org/P) (Microsoft) - P is a language for asynchronous event-driven programming.
  * [ServiceStack.Text](servicestack.net/text) - .NET's missing high-performance utility belt
  * [SmartFormat.NET](github.com/scottrippey/SmartFormat.NET) - An extensible .NET replacement for String.Format

## Java
### Distributed systems
* [Akka](akka.io)

### Services
* [Finagle](twitter.github.io/finagle) (Twitter) - An extensible RPC system for the JVM, used to construct high-concurrency servers.

### Data Access
* [Calcite](calcite.apache.org) (Apache) - The foundation for your next high-performance database. 

## Python
### Awesome
* [Awesome Python](awesome-python.com) - Life is short, you need Python.

### Architectures
* [Saleor](https://getsaleor.com) - A GraphQL-first E-commerce platform for perfectionists

### Distributions and Installers
* [virtualenv](virtualenv.pypa.io/en/stable/) - A tool to create isolated Python environments.
* [Anaconda](www.anaconda.com) -  The Most Popular Python Data Science Distribution
* [Miniconda](conda.io/miniconda.html) - A smaller alternative to Anaconda that is just conda and its dependencies

### Web Frameworks & Services
* [Django](www.djangoproject.com) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
* [sandman2](github.com/jeffknupp/sandman2) - Automatically generate a RESTful API service for your legacy database. No code required! 
* [Nameko](nameko.readthedocs.io/en/stable) - A microservices framework for Python that lets service developers concentrate on application logic and encourages testability
* [Vibora](vibora.io) - Fast, asynchronous and elegant Python web framework 

### Distributed Systems
* [Airflow](airflow.apache.org) (Apache) - A platform to programmatically author, schedule and monitor workflows
* [Celery](www.celeryproject.org) - An asynchronous task queue/job queue based on distributed message passing

### Data Access
* [Peewee](github.com/coleifer/peewee) - A small, expressive orm (upports postgresql, mysql and sqlite)

### Data science
* [TensorFlow](www.tensorflow.org) (Google) - An open source machine learning framework for everyone.
* [NumPY](www.numpy.org) - fundamental package for scientific computing with Python.
* [Pandas](pandas.pydata.org) - High-performance, easy-to-use data structures and data analysis tools for the [Python](www.python.org/) programming language.
* [scikit-learn](scikit-learn.org/stable) (INRIA) - Machine Learning in Python
* [SpaCy](spacy.io) - Industrial-StrengthNatural Language Processing
* [Flair](https://github.com/zalandoresearch/flair) - A very simple framework for state-of-the-art Natural Language Processing (NLP)
* [Dask](dask.pydata.org/en/latest) - Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love.
* [Numba](numba.pydata.org) - The power to speed up your applications with high performance functions written directly in Python.
* [Pyro](pyro.ai) (Uber) - Deep Universal Probabilistic Programming
* [Horovod](github.com/uber/horovod) (Uber) - Distributed training framework for TensorFlow
* [chainer](chainer.org) - Bridge the gap between algorithms and implementations of deep learning.
* [NLTK](www.nltk.org) - A leading platform for building Python programs to work with human language data

### Graphics & Drawring
* [Chartify](github.com/spotify/chartify) (Spotify) - Python library that makes it easy for data scientists to create charts.
* [Altair](altair-viz.github.io) - Declarative Visualization in Python

## Go
### Services
* [Martini](github.com/go-martini/martini) - Classy web framework for Go
* [Gorilla](www.gorillatoolkit.org/pkg/mux) - Gorilla web toolkit

## Node.js
### Awesome
* [Awesome GraphQL](github.com/chentsulin/awesome-graphql) - Awesome list of GraphQL & Relay
* [Automatic API](github.com/dbohdan/automatic-api) - A list of software that turns your database into a REST/GraphQL API 

### Distributed Systems
* [noel](lifenautjoe.github.io/noel) - A universal, human-centric, replayable Javascript event emitter
* [Bull](github.com/OptimalBits/bull) - Premium Queue package for handling jobs and messages in NodeJS

### Services
* REST
  * [ActionHero](www.actionherojs.com) - The reusable, scalable, and quick node.js API server for stateless and stateful applications
  * [egg](eggjs.org/en) - Born to build better enterprise frameworks and apps with Node.js & Koa
  * [ActiveResource.js](https://active-resource.js.org) - An API resource relational mapping library in JavaScript
* API Gateways
  * [Tyk](tyk.io) - Open source API Gateway that is fast, scalable and modern.
  * [Kong](getkong.org) - Secure, Manage & Extend your APIs and Microservices
* [GraphQL](graphql.org)
  * [Prisma](www.prismagraphql.com) (Graphcool) - Turn your database into a GraphQL API
  * [Apollo](github.com/apollographql/apollo-server) (Meteor) - GraphQL server for Express, Connect, Hapi, Koa and more
  * [PostGraphile](www.graphile.org) - Tools for building performant pluggable GraphQL APIs.
  * [Join-Monster](github.com/stems/join-monster) - A GraphQL to SQL query execution layer for query planning and batch data fetching.
  * [gestalt](github.com/charlieschwabacher/gestalt) - Use the GraphQL schema language and a small set of directives to define an API with a PostgreSQL backend declaratively, really quickly, and with a tiny amount of code.
  * [sql-to-graphql](github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure 
  * [Altair](altair.sirmuel.design) - A beautiful feature-rich GraphQL Client for all platforms
  * [GraphQL Yoga](github.com/graphcool/graphql-yoga) (Graphcool) - Fully-featured GraphQL Server with focus on easy setup, performance & great developer experience
* Serverless
  * [serverless](serverless.com) - Your toolkit for deploying and operating serverless architectures. 
  * [serverless-offline](github.com/dherault/serverless-offline) - Emulate AWS λ and API Gateway locally when developing your Serverless project 
  * [serverless-babel-starter](github.com/postlight/serverless-babel-starter) - Serverless with all the fixings: Webpack, Babel, Jest, ESLint, and Prettier.
  * [lambdapack](www.npmjs.com/package/lambdapack) - Package your AWS Lambda efficiently, ready to be deployed with [apex/up](github.com/apex/up)

### Data Access
* [EventStore](eventstore.org) - The open-source, functional database with Complex Event Processing in JavaScript.

### Templating
* [Pug](pugjs.org) – Robust, elegant, feature rich template engine for Node.js

### Algorithms & Data Structures
* Numerics
  * [crunch.js](crunch.js.org) - Arbitrary-Precision Integer Arithmetic Library
  * [Yaffle BigInteger](github.com/Yaffle/BigInteger) - Yet another implementaion of arbitrary-precision integers in pure JavaScript. 
  * [bigi](github.com/cryptocoinjs/bigi) - JavaScript Big Integer library based upon Tom Wu's work. 
  * [bn.js](github.com/indutny/bn.js) - BigNum in pure javascript
* Bitmaps
  * [Fast-BitSet](github.com/mattkrick/fast-bitset)-  A fast bitset with some nice methods

### CRM

* [Tipe](tipe.io) - Create your content with powerful editing tools and access it from anywhere with a GraphQL or REST API. Stop letting your CMS decide how you build your apps. 

### Tools

* [i18next](www.i18next.com) - An **internationalization-framework** written in and for JavaScript. 
* [ReLaXed](github.com/RelaxedJS/ReLaXed) - Create PDF documents using web technologies.
* [Prompts](github.com/terkelg/prompts) - Lightweight, beautiful and user-friendly interactive prompts
* [Headless Chrome Crawler](github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome
* [ClearGPDR](www.cleargdpr.com) - The Leading GDPR Compliance Solution: Open Source, Blockchain Based.

# Frontend

## Design
### Development
* [Haiku](www.haiku.ai) - Where designing is building
* [Figma](www.figma.com)
* [CSS Grid Builder](cssgrid.cc) - A collection of resources & tools to help you manage the Grid

### Style guides
* [Catalog](www.catalog.style) - Living style guides for digital products
* [Design Systems Repo](designsystemsrepo.com) - A frequently updated collection of Design Systems

## CSS
* Extensions
  * [CSS Blocks](css-blocks.com) (LinkedIn) - Blazing fast CSS for your design systems and app components
    * [OptiCSS](github.com/linkedin/opticss) (LinkedIn) - A CSS Optimizer
  * [SaSS](sass-lang.com)
  * [LeSS](lesscss.org)
* Frameworks
  * [mustard](mustard-ui.com) - Mustard UI is a starter CSS framework that actually looks good
* UX Frameworks
  * [Mailchimp](ux.mailchimp.com/patterns) - MailChimp Pattern Library is a byproduct of our move to a more responsive, nimble, & intuitive app.
* Email
  * [MJML](mjml.io) - The only framework that makes responsive email easy
  * [Foundation For Emails](foundation.zurb.com/emails.html) - Quickly create responsive HTML emails that work. Even on Outlook.

## Javascript

### Knowledge Base
* [Front End Toolkit](github.com/devbridge/Front-End-Toolkit)
* [Best of JS](bestof.js.org)
* [Awesome](github.com/sindresorhus/awesome) - Curated list of awesome lists

### UX Frameworks
* Design Systems
  * [Awesome Design Systems](github.com/alexpate/awesome-design-systems) - A collection of awesome design systems
  * [Bootstrap](getbootstrap.com) - Build responsive, mobile-first projects on the web
    * [Material Design for Bootstrap](mdbootstrap.com)
    * [Shards](designrevision.com/downloads/shards) - A free and modern UI toolkit for web makers
    * [Fire](fire.uxtheme.net) - Easy Development with Fire UI Kit
  * [Carbon](carbondesignsystem.com) (IBM) - Design system for IBM Cloud products.
  * [Stencil](stenciljs.com) - The magical, reusable web component compiler
  * [Rizzo](rizzo.lonelyplanet.com/styleguide) (Lonely Planet) - 
  * [boundless](boundless.js.org) - UI toolkit that was conceived to abstract away difficult interface patterns
  * [Lightning Design System](www.lightningdesignsystem.com) (Salesforce) - Create the world’s best enterprise app experiences.
  * [Mapbox](www.mapbox.com/base) (Maxbox) - An internal guide & code repository for designing and coding at Mapbox.
  * [Atlassian Design](atlassian.design) (Atlassian) - Use Atlassian's end-to-end design language to create straightforward and beautiful experiences.
  * [Auth0 Styleguide](styleguide.auth0.com) (Auth0) - Conjunction of design patterns, components and resources used across our products.
* Themes
  * [Hacker Themes](hackerthemes.com) - Bootstrap 4 themes & templates for ambitious developers
  * [Creative Time](www.creative-tim.com) - Premium Bootstrap themes, templates, UI Kits and more developed by Creative Tim.
  * [Tabler](tabler.github.io) - Premium and Open Source dashboard template with responsive and high quality UI. For Free!
  * [Papaya](www.eatapapaya.com/) - Yummy landing page templates for any project.

### Libraries
* Charts and graphics
  * [protovis](mbostock.github.io/protovis) - A graphical approach to visualization
  * [d3js](d3js.org) - Data-Driven Documents
    * [d3-discovery](d3-discovery.net) - Finding D3 plugins with ease
    * [mermaid](mermaidjs.github.io) - Generation of diagram and flowchart from text in a similar manner as markdown
    * [nvd3](nvd3.org) - A reusable charting library
    * [d3-annotation](d3-annotation.susielu.com)
    * [plotly.js](plot.ly/javascript) - The open source JavaScript graphing library that powers Plotly
    * [epoch](epochjs.github.io/epoch) - A general purpose real-time charting library for building beautiful, smooth, and high performance visualizations
    * [metricsgraphicsjs](www.metricsgraphicsjs.org) - A library that is optimized for visualizing and laying out time-series data
    * [rickshaw](code.shutterstock.com/rickshaw) - JavaScript toolkit for creating interactive time series graphs
    * [plottablejs](plottablejs.org) (Palantir) - Flexible, interactive charts for the web
  * [Vega](vega.github.io/vega) - A Visualization Grammar
    * [Vega Lite](vega.github.io/vega-lite) - A Grammar of Interactive Graphics
  * [dygraphs](dygraphs.com) - Fast, flexible open source JavaScript charting library
  * [sigmajs](sigmajs.org) - Sigma is a JavaScript library dedicated to graph drawing
  * [cytoscape](js.cytoscape.org) - Graph theory / network library for analysis and visualisation
  * [cubismjs](square.github.io/cubism) (Square) - Time Series Visualization
  * [taucharts](www.taucharts.com) - Flexible javascript charting library for data exploration
  * [echarts](echarts.baidu.com) (Baidu) - A powerful, interactive charting and visualization library for browser
    * [ECharts-GL](github.com/ecomfe/echarts-gl) - Extension pack of [echarts](echarts.baidu.com/), which providing 3D plots, globe visualization and WebGL acceleration. 
  * [chartjs](www.chartjs.org) - Simple yet flexible JavaScript charting for designers & developers
  * [chartist](gionkunz.github.io/chartist-js) - Simple responsive charts
  * [Pixi](www.pixijs.com/) - The HTML5 Creation Engine
  * [Toast UI](ui.toast.com/tui-chart) - An easy way to draw various and essential charts on your web service. 
  * [flowchart.js](flowchart.js.org) - Draws simple SVG flow chart diagrams from textual representation of the diagram
  * [curtains.js](www.martin-laxenaire.fr/libs/curtainsjs/index.html)  - Easy WebGL tool to animate images
  * [G2](github.com/antvis/g2) (Alibaba) - The Grammar of Graphics in JavaScript
    * [BizCharts](github.com/alibaba/BizCharts) - Data visualization library based G2 and React
    * [G6](github.com/antvis/g6) - Relational data visualization framework. 
  * [deck.gl](uber.github.io/deck.gl) (Uber) - A WebGL-powered framework for visual exploratory data analysis of large datasets.
* Animations
  * [micron](webkul.github.io/micron) - a [μ] microInteraction library built withCSS Animations and controlled by JavaScript Power
  * [Just Animate](just-animate.github.io) - Making animation simple
* Maps
  * [pigeon-maps](mariusandra.github.io/pigeon-maps) - 
* Utilities
  * [Dinero.js](sarahdayan.github.io/dinero.js) - Dinero.js is a library for working with monetary values in JavaScript
  * [Proppy](proppyjs.com) - Functional props composition for components
* Tours
  * [Driver](kamranahmed.info/driver) - Light-weight, no-dependency, vanilla JavaScript engine to drive user's focus across the page

### Tooling
* [WebAssembly](webassembly.org) - A binary instruction format for a stack-based virtual machine.
* [bit](bitsrc.io) - Components are building blocks. You are the architect.
* [Lerna](lernajs.io) - A tool for managing JavaScript projects with multiple packages. 
* [codemods](github.com/facebook/codemod) - Tool/library to assist you with large-scale codebase refactors that can be partially automated but still require human oversight and occasional intervention.
* [Scroll Booster](ilyashubin.github.io/scrollbooster) - Enjoyable content drag-to-scroll library.
* [Webpack](webpack.js.org) - Bundle your assets
  * [Speed Measure](github.com/stephencookdev/speed-measure-webpack-plugin) - See how fast (or not) your plugins and loaders are, so you can optimise your builds
  * [NOW Loader](github.com/pranaygp/now-loader) - Deploys the required resource to now
  * [directory-named-webpack-plugin](www.npmjs.com/package/directory-named-webpack-plugin) - This plugin makes it possible to control what file within directory will be treated as entry file.
* [FuseBox](fuse-box.org) - A bundler that does it right
* [turbolinks](github.com/turbolinks/turbolinks) - Turbolinks makes navigating your web application faster

### [React](reactjs.org)
* Awesome
  * [Awesome React](github.com/enaqx/awesome-react)
  * [React Components & Libraries](github.com/brillout/awesome-react-components)
  * [Awesome Redux (brillout)](github.com/brillout/awesome-redux)
  * [Awesome Redux (xgrommx)](github.com/xgrommx/awesome-redux)
  * [Awesome MobX](github.com/mobxjs/awesome-mobx)
  * [MobX Ecosystem](github.com/xgrommx/mobx-ecosystem)
  * [Awesome React GraphQL](github.com/hasura/awesome-react-graphql) - A curated collection of resources, clients and tools that make working with GraphQL and React/React Native awesome. 
* Architectures
  * [React Storefront](https://github.com/moovweb/react-storefront) - Build and deploy e-commerce progressive web apps in record time.
* State Management
  * REST
    * [tectonic](tonyhb.github.io/tectonic) - A declarative REST data loader for react + redux
    * [React Agent](www.reactagent.com) - A JS library for your database management
    * [Redux Rest Resource](mgcrea.github.io/redux-rest-resource) - Dead simple and ready-to-use store module for handling HTTP REST resources.
  * [Redux](redux.js.org)
    * [Undux](github.com/bcherny/undux) - Dead simple state management for React
    * [next.js](github.com/zeit/next.js) - Framework for server-rendered or statically-exported React apps
    * [after.js](github.com/jaredpalmer/after.js) - Next.js-like framework for server-rendered React apps built with React Router 4
    * [jumpsuit](jumpsuit.js.org) - React framework for efficiently building powerful web applications
    * [rematch](rematch.gitbooks.io/rematch) -  Redux best practices without the boilerplate. No more action types, action creators, switch statements or thunks.
    * [dva](github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework. (Inspired by elm and choo) 
    * [microcosm](code.viget.com/microcosm) - Microcosm is [Flux](facebook.github.io/flux/docs/overview.html) with actions at center stage. Write optimistic updates, cancel requests, and track changes with ease. 
    * [Lore.js](www.lorejs.org) - Build apps worthy of legend. Convention-driven framework for React.
  * [MobX](mobx.js.org)
    * [cans](cans.js.org) - A framework for building React / MobX application
    * [mobx-state-tree](github.com/mobxjs/mobx-state-tree) - Model Driven State Management
    * [parket](github.com/ForsakenHarmony/parket) - A library to manage application state, heavily inspired by mobx-state-tree
    * [FormState](github.com/formstate/formstate) - Form state so simple that you will fall in love
    * [react-remux](github.com/vinej/react-remux) - A flux implementation with React and Mobx
  * Tools
    * [immutable.js](facebook.github.io/immutable-js) (Facebook) - Immutable collections for JavaScript
    * [Immer](github.com/mweststrate/immer) - Create the next immutable state by mutating the current one
    * [Unstated](github.com/jamiebuilds/unstated) - State so simple, it goes without saying.
    * [ModulaJS](github.com/freewheel/modulajs) - A modularization framework to manage application states using an immutable model tree.
    * [unistore](github.com/developit/unistore) - 650b state container with component actions for Preact & React
    * [reworm](github.com/pedronauck/reworm) - The simplest way to manage state
    * [uniforms](github.com/vazco/uniforms) - A set of React libraries for building forms
    * [Final Form](github.com/final-form/react-final-form) - High performance subscription-based form state management for React.
    * [react-portalgun](github.com/diegomura/react-portalgun) - Lightweight portal system for React. Mega seeds included
* Development Frameworks
  * [next.js](github.com/zeit/next.js) - A lightweight framework for static and server‑rendered applications.
  * [next-offline](github.com/hanford/next-offline) - Make your Next.js application work offline using service workers via Google's workbox.
  * [DVA](github.com/dvajs/dva) - React and redux based, lightweight and elm-style framework.
  * [Create React App](github.com/facebook/create-react-app) - Create React apps with no build configuration.
  * [rekit](rekit.js.org) - A toolkit for building scalable web applications with React, Redux and React-router.
  * [fusion.js](fusionjs.com) - A plugin-based universal web framework
* Routing
   * [Junctions](junctions.js.org) - A batteries-included router for React.
* UX Frameworks
  * [Gestalt](github.com/pinterest/gestalt) (Pinterest) - Set of React UI components that enforces Pinterest’s design language. 
  * [Grommet](grommet.io) (Hewlett Packard) - focus on the essential experience
     * [Grommet Addons](github.com/grommet/grommet-addons) - Higher order components and utilities based on core grommet components.
     * [Grommet Index](index.grommet.io/docs/grommet-index) - Additional components beyond the base Grommet components for use in data heavy environments [*deprecated* - use Grommet Addons instead].
  * [Material UI](material-ui-next.com) - React components that implement Google's Material Design.
  * [Ant Design](ant.design) - A design system with values of Nature and Determinacy for better user experience of enterprise applications
     * [Awesome Ant Design](github.com/websemantics/awesome-ant-design) - A curated list of Ant Design resources and related projects. 
     * [Ant.Motion](github.com/ant-design/ant-motion) - Animate specification and components of Ant Design  
     * [Scaffolds](scaffold.ant.design) - Practical scaffolds to kickoff 
  * [React Desktop](reactdesktop.js.org) - JavaScript library built on top of [Facebook's React](facebook.github.io/react/) library, which aims to bring a native desktop experience to the web, featuring many macOS Sierra and Windows 10 components.
  * [Semantic UI](react.semantic-ui.com) - Semantic UI React is the official React integration for [Semantic UI](semantic-ui.com/) .
  * [Blueprint](blueprintjs.com) (Palantir) - A React-based UI toolkit for the web
  * [React Bootstrap](react-bootstrap.github.io) - The most popular front-end framework, rebuilt for React.
  * [Office UI Fabric](developer.microsoft.com/en-us/fabric#/components) (Microsoft) - Use our design language in your own experience
  * [react-md](react-md.mlaursen.com) - React material design
  * [modulz](www.modulz.co/showcase) - An open–source collection of styles, components, patterns, resources & more
  * [Clarity Design System](vmware.github.io/clarity) (VMWare) - UX guidelines, HTML/CSS framework, and Angular components working together to craft exceptional experiences
  * [React Lightning Design System](github.com/mashmatrix/react-lightning-design-system) - Salesforce Lightning Design System components built with React
  * [RSuite](rsuitejs.com/en) - A suite of React components
  * [Evergreen](evergreen.surge.sh) - React UI Framework for the Web
* Themes
   * [CoreUI](coreui.io) - Free Bootstrap Admin Template
* Security and Authentication
   * [React Check Auth](github.com/hasura/react-check-auth) - Add auth protection anywhere in your react/react-native app.
* Component/CSS frameworks
  * [Aphrodite](github.com/Khan/aphrodite) (Khan Academy) - Framework-agnostic CSS-in-JS with support for server-side rendering, browser prefixing, and minimum CSS generation
    * [Adonis](github.com/imgly/adonis) - The best of [Aphrodite](github.com/Khan/aphrodite) and [styled-components](github.com/styled-components/styled-components): Named DOM elements, stylable via object literals with support for inheritance, overriding and theming while staying lightweight (28 KB / 7.6 KB gzipped)
  * [glamor](github.com/threepointone/glamor) - Inline CSS for React et al.
  * [glamorous](github.com/paypal/glamorous) (PayPal) - Maintainable CSS with React
  * [emotion](emotion.sh) - The Next Generation of CSS-in-JS
  * [Radium](formidable.com/open-source/radium) (Formidable Labs) - Set of tools to manage inline styles on React elements.
  * [rebass](jxnblk.com/rebass) - Library of highly-composable, primitive UI components for React, built with styled-components to keep styles isolated and reduce the need to write custom CSS in your application.
  * [cxs](github.com/cxs-css/cxs) - fast af css-in-js in 0.7kb
  * [Styletron](github.com/rtsao/styletron) - Toolkit for component-oriented styling 
  * [styled-components](www.styled-components.com) - Visual primitives for the component age
    * [Styled Theming](github.com/styled-components/styled-theming) - Create themes for your app using styled-components
    * [styled-system](jxnblk.com/styled-system/#styled-system) - Design system utilities for [styled-components](github.com/styled-components/styled-components) and other css-in-js libraries
  * [reas](reas.js.org) - A minimalist and highly customizable component system
  * [React Foundation](react.foundation) - Foundation as React components
  * [React Grid](devexpress.github.io/devextreme-reactive/react/grid/) (DevExtreme) - Your Data Grid, Your Way
* Charts & graphics
  * [Victory](formidable.com/open-source/victory) (Formidable Labs) - React.js components for modular charting and data visualization
  * [recharts](recharts.org) - A composable charting library built on React components
  * [react-vis](uber.github.io/react-vis) (Uber) - A composable charting library
  * [reactivemaps](github.com/appbaseio/reactivemaps) - A data aware UI components library for building realtime maps
  * [echarts-for-react](git.hust.cc/echarts-for-react) - A very simple echarts (v3.x & v4.x) wrapper for React.
  * [react-virtualized](www.reactvirtualized.com) - React components for efficiently rendering large lists and tabular data.
* Animations and video
  * [Pose](popmotion.io/pose) - Declarative motion system for HTML, SVG, React & React Native
  * [react-spring](github.com/drcmda/react-spring) - Helping react-motion and animated to become best friends
  * [popmotion](github.com/Popmotion/popmotion) - A functional, reactive animation library
  * [react-move](github.com/react-tools/react-move) - Beautiful, data-driven animations for React
  * [animated](github.com/animatedjs/animated) - Declarative Animations Library for React and React Native
  * [react-motion](github.com/chenglou/react-motion) - A spring that solves your animation problems
  * [Video.js](videojs.com) - The player framework
* Testing
  * [react-testing-library](github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* Utilities
  * [react-with-gesture](github.com/drcmda/react-with-gesture) - Little helper for component-tied mouse/touch gestures
  * [React Graceful Image](github.com/linasmnew/react-graceful-image) - An image component for gracefully dealing with image errors by providing optional lazy loading, optional placeholder and configurable retries on failure 
  * [MDXC](mdxc.reactarmory.com) - Tool to convert Markdown into React Components.
  * [Spectacle](formidable.com/open-source/spectacle) (Formidable Labs) - A React.js based library for creating sleek presentations.
  * [Compositor](compositor.io) - Modern tools for designers & developers

### [Angular](angular.io)
* Awesome
  * [awesome-angular](github.com/gdi2290/awesome-angular) - A curated list of awesome Angular resources by [@TipeIO](github.com/TipeIO) 
  * [awesome-angular2](github.com/amcdnl/awesome-angular2) - A curated list of awesome Angular 2 resources by [@AngularClass](github.com/AngularClass) 
  * [awesome-angular-components](github.com/brillout/awesome-angular-components) - Catalog of Angular 2+ Components & Libraries 
* Development frameworks
  * [Nrwl Nx](nrwl.io/nx) - An open source toolkit for enterprise Angular applications
* UX Frameworks
  * [Angular Material](material.angular.io) - Material Design components for Angular
  * [NG-ZORRO](github.com/NG-ZORRO/ng-zorro-antd) - An enterprise-class UI components based on Ant Design and Angular. 

### [Vue.js](vuejs.org)
* Examples
  * [Made With Vue](madewithvuejs.com) - A collection of projects made with vue.js
* Development Frameworks & Boilerplates
  * [nuxt](nuxtjs.org) - Universal Vue.js Applications
  * [Vue Enterprise Boilerplate](github.com/chrisvfritz/vue-enterprise-boilerplate) - An ever-evolving, very opinionated architecture and dev environment for new Vue SPA projects using Vue CLI 3.  
  * [Charcoal](github.com/setholito/charcoal) - A Vue.js & Bulma Starter Kit.
* UX Frameworks
  * [Material Design for Bootstrap](mdbootstrap.com/vue) - Vue Bootstrap with Material Design
  * [iView](www.iviewui.com) - A high quality UI Toolkit based on Vue.js.
  * [Vuetify](vuetifyjs.com) - Material Design Component Framework.
  * [Vue Design System](vueds.com) - An open source tool for building Design Systems with [Vue.js](vuejs.org)
  * [Fish UI](myliang.github.io/fish-ui) - A Vue.js 2.0 UI Toolkit for Web.
* CMS
  * [VuePress](vuepress.vuejs.org) - Vue-powered Static Site Generator 
* Tools
  * [Vue Tour](pulsardev.github.io/vue-tour) - a Lightweight, Simple and Customizable tour plugin for use with Vue.js
* Native
  * [vuido](github.com/mimecorg/vuido) - Native desktop applications using Vue.js

### [Ember.js](www.emberjs.com)
* Libraries
	* [ember-table](opensource.addepar.com/ember-table)

### Other frameworks
* [Polymer](www.polymer-project.org) - A library that brings web components into the mainstream, embracing JavaScript modules and npm.
  * [Hadron](hadron.app) - A unified platform for designers and developers who work together towards the same goal, moving ideas forward and learning from each other along the way.
* [Preact](preactjs.com) - Fast 3kB alternative to React with the same modern API. 
* [Inferno](infernojs.org) - Insanely fast, React-like library for building high-performance user interfaces on both the client and server.
* [svelte](svelte.technology) - The magical disappearing UI framework
* [Glimmer.js](glimmerjs.com) - Fast and light-weight UI components for the web
* [Knockout](knockoutjs.com) - Knockout makes it easier to create rich, responsive UIs with JavaScript  
* [Mithril](mithril.js.org) - Modern client-side Javascript framework for building Single Page Applications.
* [Aurelia](aurelia.io) - JavaScript client framework for web, mobile and desktop that leverages simple conventions to empower your creativity.
* [Meteor](www.meteor.com) - The fastest way to build javascript apps.
* [Ionic](ionicframework.com) - Build amazing apps in one codebase, for any platform, with the web.
* [Stencil](stenciljs.com) - The magical, reusable web component compiler
* [Marko](markojs.com) - It's like HTML and JS had a perfect baby that grew up to be awesome

### Utilities
* [selection](github.com/Simonwep/selection) - A simple and lightweight library to realize visual DOM Selections.  

## .Net
### UI frameworks
* WinForms
  * [Material Skin](github.com/IgnaceMaes/MaterialSkin) - Theming .NET WinForms, C# or VB.Net, to Google's Material Design Principles.
* WPF
  * [Caliburn.Micro](caliburnmicro.com) - A small, yet powerful framework, designed for building applications across all XAML platforms.
  * [MahApps.Metro](mahapps.com) - Let your desktop apps shine
  * [Material Design In XAML Toolkit](materialdesigninxaml.net) - Easily bring beautiful desktop applications to life, using a modern and popular design language. 
  * [Avalonia](avaloniaui.net) - A cross platform XAML Framework for .NET Framework, .NET Core and Mono
  * [Modern UI](github.com/firstfloorsoftware/mui) - Modern UI for WPF
  * [Catel](catelproject.com) - An application development platform with the focus on MVVM (WPF, Silverlight, Windows Phone, WinRT, Xamarin.Android and Xamarin.iOS) and MVC (ASP.NET MVC).
  * [MVVM Light Toolkit](github.com/lbugnion/mvvmlight) - The main purpose of the toolkit is to accelerate the creation and development of MVVM applications in Xamarin.Android, Xamarin.iOS, Xamarin.Forms, Windows 10 UWP, Windows Presentation Foundation (WPF), Silverlight, Windows Phone.
  * [Okra App Framework](okraframework.github.io) - The app centric MVVM framework for Windows and Windows Phone
  * [Prism](github.com/PrismLibrary/Prism) - A framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms.
  * [WAF](github.com/jbe2277/waf) - Win Application Framework (WAF) is a lightweight Framework that helps you to create well structured XAML Applications.
  * [Gemini](documentup.com/tgjones/gemini) - WPF framework designed specifically for building IDE-like applications.
* Web
  * [DotVVM](github.com/riganti/dotvvm) - Open source MVVM framework for Web Apps.
  * [Ooui](github.com/praeclarum/Ooui) - A small cross-platform UI library that brings the simplicity of native UI development to the web.
  * [Blazor](github.com/aspnet/Blazor) - Blazor is an experimental .NET web framework using C#/Razor and HTML that runs in the browser with WebAssembly 
* Mobile/UWP
  * [Xamarin](visualstudio.microsoft.com/xamarin) (Microsoft) - Deliver native Android, iOS, and Windows apps with a single shared .NET code base.
  * [Uno](platform.uno) - Build native apps for Mobile and Web using XAML and C#.
* Other
  * [Stylet](github.com/canton7/stylet) - Minimal MVVM framework inspired by Caliburn Micro, with good documentation, high test coverage, and its own IoC container
  * [ReactiveUI](github.com/reactiveui/reactiveui) - An advanced, composable, functional reactive model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming.
  * [Eto.Forms](github.com/picoe/Eto) - Cross platform GUI framework for desktop and mobile applications in .NET
  * [Neutronium](github.com/NeutroniumCore/Neutronium) - Build .NET desktop applications using HTML, CSS and javascript
  * [mvvmcross](www.mvvmcross.com) - App development without compromise.
  * [QtShartp](github.com/ddobrev/QtSharp) - Mono/.NET bindings for Qt
  * [xwt](github.com/mono/xwt) - A cross-platform UI toolkit for creating desktop applications with .NET and Mono
  * [WinApi](github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop 

### Controls
* [Krypton](github.com/ComponentFactory/Krypton) - Krypton WinForms components for .NET
* [Callisto](github.com/timheuer/callisto) - A control toolkit for Windows 8 XAML applications.
* [MVVM Dialogs](github.com/FantasticFiasco/mvvm-dialogs) - Framework simplifying the concept of opening dialogs from a view model when using MVVM in WPF or UWP.

### Graphics
* Imaging
  * [dot.imaging](github.com/dajuric/dot-imaging) - Minimalistic .NET imaging portable platform
  * [metadata-extractor.NET](github.com/drewnoakes/metadata-extractor-dotnet) - Extracts Exif, IPTC, XMP, ICC and other metadata from image and movie files
  * [Image Resizer](github.com/imazen/resizer) - The Flexible Image Server
  * [Image Processor](imageprocessor.org) - A .NET Library For On-The-Fly Processing Of Images.
  * [Dynamic Image](dynamicimage.apphb.com) - A high-performance image manipulation library for ASP.NET
  * [Image Sharp](sixlabors.github.io/docs/articles/ImageSharp/GettingStarted.html) - A cross-platform library for the processing of image files 
  * [Magick.NET](github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick
  * [Emgu CV](www.emgu.com/wiki/index.php/Main_Page) - Cross platform .Net wrapper to the OpenCV image processing library.
  * [OpenCvSharp](github.com/shimat/opencvsharp) - .NET Framework wrapper for OpenCV 
  * [Structure.Sketching](github.com/JaCraig/Structure.Sketching) - Image processing library for use in .Net applications that supports .Net Core.
  * [NetVips](kleisauke.github.io/net-vips) - Mono/.NET binding for the [libvips image processing library](jcupitt.github.io/libvips).
* Bar and QR codes
  * [QRCoder](github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation
* Charts
  * [LiveCharts](lvcharts.net) - Simple, flexible, interactive & powerful data visualization for .Net
  * [OxyPlot](www.oxyplot.org) - OxyPlot is a cross-platform plotting library for .NET.
* Raster
  * [NGraphics](github.com/praeclarum/NGraphics) - Cross platform library for rendering vector graphics on .NET.
* 3D
  * [Helix Toolkit](www.helix-toolkit.org) - 3D for .NET
  * [opentk](github.com/opentk/opentk) - Fast, low-level C# wrapper for OpenGL and OpenAL.
  * [veldrid](mellinoe.github.io/veldrid-docs) - Low-level graphics library for .NET.

### Misc.
* [TomsToolbox](github.com/tom-englert/TomsToolbox) - A set of core functions and classes to ease every days .Net development tasks. 

## Java

## Other

* [Mint](www.mint-lang.com) - A refreshing programming language for the front-end web. 

# Databases
## Relational
### Engines
* [PostgreSQL](www.postgresql.org)
  * [postgrest](postgrest.com) - Standalone web server that turns your PostgreSQL database directly into a RESTful API.
  * [pREST](postgres.rest) - A way to serve a RESTful APIs for any database. 
  * [zombodb](github.com/zombodb/zombodb) - Making Postgres and Elasticsearch work together like it's 2018
  * [migra](migra.djrobstep.com) - A schema comparison tool for PostgreSQL.
  * [Citus Data](www.citusdata.com) - Worry-Free Postgres for SaaS
  * [skor](github.com/hasura/skor) - Listen to postgres events and forward them as JSON payloads to a webhook
  * [Odissey](github.com/yandex/odyssey) - Scalable PostgreSQL connection pooler
* [MySQL](www.mysql.com)
  * [Orchestrator](github.com/github/orchestrator) - A high availability and replication management tool
* [MariaDB](mariadb.org)
* [CockroachDB](github.com/cockroachdb/cockroach) - An open source, cloud-native SQL database.

### Distributed
* [Presto](prestodb.io) (Facebook) - Distributed SQL query engine for big data

### Editors
* [DBeaver](dbeaver.jkiss.org)
* [SQL Workbench/J](www.sql-workbench.eu)

## Document
### Engines
* [Elastic](www.elastic.co)
  * [Kibana](www.elastic.co/products/kibana) (Elastic)
  * [Grafana](grafana.com)
* [Solr](lucene.apache.org/solr)
  * [Banana](github.com/lucidworks/banana) (LucidWorks)
* [Mongo](www.mongodb.com)
* [RavenDB](ravendb.net) - The Original Fully Transactional Open Source NoSQL Document Database.

## Columnar
### Engines
* [Cassandra](cassandra.apache.org) (Apache) - Manage massive amounts of data, fast, without losing sleep
* [ScyllaDB](www.scylladb.com) - Scale-up performance of 1,000,000 IOPS per node, scale-out to hundreds of nodes and 99% latency of <1 msec
* [Druid](druid.io) (Apache) - A high performance analytics data store for event-driven data.
  * [Tranquility](github.com/druid-io/tranquility) - Helps you send real-time event streams to Druid and handles partitioning, replication, service discovery, and schema rollover, seamlessly and without downtime.

## Graph
### Engines
* [Neo4J](neo4j.com)
  * [Cypher](neo4j.com/developer/cypher-query-language)
  * [GRANDStack](grandstack.io) - Build full stack graph applications with ease.
* [ArangoDB](www.arangodb.com)
* [OrientDB](orientdb.com)
* [Titan](titan.thinkaurelius.com)
* [Dgraph](dgraph.io)

### Tools
* [Giraph](giraph.apache.org) (Apache) - An iterative graph processing system built for high scalability

## In-memory
### Engines
#### Open source
* [Ignite](ignite.apache.org)

#### Commercial
* [MemSQL](www.memsql.com)
* [Aerospike](www.aerospike.com)

## Columnar
### Engines
* [Cassandra](cassandra.apache.org) (Apache)

## Time-series
### Engines
* [Timescale](www.timescale.com) - Enabling a variety of powerful time-series queries with the SQL you already know. 

## Object stores
* [Ceph](ceph.com) - A unified, distributed storage system designed for excellent performance, reliability and scalability.
* [Minio](www.minio.io) - A high performance distributed object storage server, designed for large-scale private cloud infrastructure.

# Integration
## Knowledge Base
* [Awesome Microservices](github.com/mfornos/awesome-microservices) - A curated list of Microservice Architecture related principles and technologies

## Data Formats
* [Avro](avro.apache.org) (Apache)
* [Protobuf](developers.google.com/protocol-buffers) (Google)

## Protocols
* [HTTP/2](http2.github.io)
* [gRPC](grpc.io)
* [IPFS](ipfs.io)

## Frameworks & Platforms
### Libraries
* [Camel](camel.apache.org) (Apache)

### Platforms
* [Spring Cloud Data Flow](cloud.spring.io/spring-cloud-dataflow)
* [MuleSoft](www.mulesoft.com)
* [WSO2](wso2.com)
* [Fuse](developers.redhat.com/products/fuse/overview)

## Streaming
### Messaging
* [Kafka](kafka.apache.org) (Apache) - A distributed streaming platform
	* [KSQL](github.com/confluentinc/ksql) (Confluent) - The streaming SQL engine for Apache Kafka
	* [Kafka Connect](www.confluent.io/hub) (Confluent) - Discover and share connectors and more
  * [Hermes](hermes.allegro.tech) - Reliable and easy to use message broker built on top of Kafka
* [Pulsar](pulsar.apache.org) (Yahoo) - An open-source distributed pub-sub messaging system an open-source distributed pub-sub messaging system
* [NATS](nats.io) - A simple, high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.
* [ActiveMQ](activemq.apache.org/) (Apache) - The most popular and powerful open source messaging and Integration Patterns server.
* [ZeroMQ](zeromq.org/) - An intelligent transport layer for your distributed apps
* [RabbitMQ](www.rabbitmq.com) (Pivotal) - An intermediary for messaging
* [Chronicle Queue](github.com/OpenHFT/Chronicle-Queue) - Micro second messaging that stores everything to disk

### Processing
* [Heron](apache.github.io/incubator-heron) (Twitter) - A realtime, distributed, fault-tolerant stream processing engine
* [Storm](storm.apache.org) (Apache) - A free and open source distributed realtime computation system
  * [Trident](storm.apache.org/releases/current/Trident-tutorial.html) (Apache) - A high-level abstraction for doing realtime computing on top of Storm
* [Samza](samza.apache.org) - A distributed stream processing framework
* [Flink](flink.apache.org) (Apache) - Stateful Computations over Data Streams
* [Apex](apex.apache.org) (Apache)
* [Beam](beam.apache.org) (Apache)
* [Prajna](msrccs.github.io/Prajna)
* [Mobius](github.com/Microsoft/Mobius)
* [MBrace](mbrace.io)

## Batching
### ETL
* [Talend Open Studio](www.talend.com/products/data-integration)
* [Kettle - Pentaho Data Integration](www.pentaho.com/product/data-integration)

### Scheduling & Workflow
* [Airflow](airflow.incubator.apache.org) (Apache) - A platform to programmatically author, schedule and monitor workflows.

### Big Data
* [Hadoop](hadoop.apache.org) (Apache) - A framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.
* [Spark](spark.apache.org) (Apache) - A unified analytics engine for large-scale data processing.

### Tools
* [NiFi](nifi.apache.org) (Apache)

## End-to-End Solutions
* [WSO2](wso2.com) - 

### BPM

### Rules
* [Drools](www.drools.org) (JBoss) - 

# Mobile
## Cross platform

- [Flutter](flutter.io) - Build beautiful native apps in record time
- [Capacitator](capacitor.ionicframework.com/) - The native bridge for cross-platform web apps

## Android
### Profiling
* [profilo](facebookincubator.github.io/profilo) - 

## iOS

# Analytics
## Awesome
* [Awesome Machine Learning](github.com/josephmisiti/awesome-machine-learning) - A curated list of awesome Machine Learning frameworks, libraries and software.
* [Machine Learning Tutorials](ujjwalkarn.github.io/Machine-Learning-Tutorials) - Machine learning and deep learning tutorials, articles and other resources

## Frameworks
* [Imply](imply.io) - A high-performance analytics solution to store, query, and visualize operational data.

## Self Service
* [Metabase](www.metabase.com) - 
* [DatabaseFlow](databaseflow.com) -

## NLP
* [fastText](github.com/facebookresearch/fastText) (Facebook) - Library for fast text representation and classification.
* [sonnet](github.com/deepmind/sonnet) (Google) - TensorFlow-based neural network library

## Visualization
* [facets](pair-code.github.io/facets) (Google) - Better data leads to better models.
* [AI-Blocks](mrnothing.github.io/AI-Blocks) - Spend time creating models, not implementing them.
* [Observable](beta.observablehq.com) - Discover insights faster and communicate more effectively with interactive notebooks for data analysis, visualization, and exploration.
* [Superset](superset.incubator.apache.org) (Apache) - A modern, enterprise-ready business intelligence web application

## Data Sets
* [Fashion MNIST](github.com/zalandoresearch/fashion-mnist) - A MNIST-like fashion product database.
* [parl.ai](parl.ai) - A unified platform for sharing, training and evaluating dialog models across many tasks.
  

## Notebooks
* [Zepellin](zeppelin.apache.org)
* [jupyter](jupyter.org)

# DevOps
## Web servers, Reverse Proxies and Load Balancers
* [nginx](www.nginx.com) - Deliver modern applications at scale
* [HAProxy](www.haproxy.org) - The Reliable, High Performance TCP/HTTP Load Balancer
* [Apache](httpd.apache.org) (Apache) - Open-source HTTP server for modern operating systems including UNIX and Windows.
* [træfik](traefik.io) - Modern HTTP reverse proxy and load balancer made to deploy microservices with ease
* [Caddy](caddyserver.com) - The HTTP/2 web server with automatic HTTPS.
* [Argo Tunnel](developers.cloudflare.com/argo-tunnel) - Exposes applications running on your local web server, on any network with an Internet connection, without adding DNS records or configuring a firewall or router.
* [Pushpin](pushpin.org) - Drop-in proxy server that pins client connections open, making realtime push easy. 

## App Servers
* [Tomcat](tomcat.apache.org) (Apache)

## Caching
* Varnish

## Serverless
* Frameworks
  * [OpenWhisk](openwhisk.apache.org) (IBM)
  * [architect](arc.codes) - Lambda functions simplified
* Deployment
  * [now](zeit.co/now) - Realtime Global Deployments
  * [apex](apex.run) - Serverless architecture

## Infrastructure
* [Docker](www.docker.com) - World’s leading software containerization platform. 
  * [Swarm](docs.docker.com/engine/swarm)
  * [Moby](mobyproject.org) (Docker) - An open framework to assemble specialized container systems without reinventing the wheel. 
  * [Airbag](https://github.com/Soluto/airbag) - Tiny sidecar for your docker containers
* [Terraform](https://www.terraform.io/) (HashiCorp) - Write, Plan, and Create Infrastructure as Code
* [Kubernetes](kubernetes.io) (Google) - Automating deployment, scaling, and management of containerized applications
  * [Rancher](rancher.com) - Enterprise management for Kubernetes. Every distro. Every cluster. Every cloud. 
  * [skaffold](github.com/GoogleCloudPlatform/skaffold) - Easy and Repeatable Kubernetes Development
  * [Continuous Pipe](continuouspipe.io) - Continuous deployment solution for your containerized applications to Kubernetes clusters
  * [Typhoon](typhoon.psdn.io/) - Typhoon is a minimal and free Kubernetes distribution
  * [kops](github.com/kubernetes/kops) - Production Grade K8s Installation, Upgrades, and Management
  * [Rook](https://rook.io) - File, Block, and Object Storage Services for your Cloud-Native Environments
  * [Compose on Kubernetes](https://github.com/docker/compose-on-kubernetes) (Docker) - Deploy applications described in Compose onto Kubernetes clusters
* Mesos (Apache)
* Tools
  * [Grail](eng.uber.com/grail) (Uber) - Scaling Infrastructure Management
  * [osquery](osquery.io) (Facebook) - Performant endpoint visibility
  * [Spinnaker](www.spinnaker.io) (Netflix) - Fast, safe, repeatable deployments
  * [Istio](istio.io) - Connect, secure, control, and observe services.

## Security
* [Infection Monkey](www.guardicore.com/infectionmonkey) -  Unleash the Infection Monkey in your network and discover security flaws in no time.

## Performance
* [Lighthouse](developers.google.com/web/tools/lighthouse) (Google) -  Automated tool for improving the quality of web pages. 

## Configuration

### Linux
- [Cockpit](cockpit-project.org) - Server manager that makes it easy to administer your GNU/Linux servers via a web browser.

### Windows

## Tools

### Windows Consoles
* [Cmder](cmder.net)
* [ConEmu](conemu.github.io)
* [Babun](babun.github.io)
* [Clink](mridgers.github.io/clink)

### Remote Desktop clients
* [Remote Desktop Manager](remotedesktopmanager.com/home/download)

### Chat
* [Rocket.Chat](rocket.chat)

# Programming
## Languages
* [Crystal](crystal-lang.org)
* [Lua](www.lua.org)
* [Rust](www.rust-lang.org/en-US)
* [Python](www.python.org)
* [Dart](www.dartlang.org)
	* Awesome
		* [Dart](github.com/yissachar/awesome-dart)
* [Haskell](www.haskell.org)
* [Erlang](www.erlang.org)
	* [Elixir](elixir-lang.org)
	* [Phoenix](phoenixframework.org)
	* Awesome
		* [Erlang](github.com/drobakowski/awesome-erlang)
		* [Elixir](github.com/h4cc/awesome-elixir)

## Data Structures & Algorithms
* [Roaring Bitmaps](roaringbitmap.org) - A better compressed bitset

## People
* Javascript
	* [Dan Abramov]()
	* [Pete Hunt]()
	* [Sindre Sorhus]()
* .Net
	* [Jon Skeet's coding blog](codeblog.jonskeet.uk) (Jon Skeet)
	* [Code, code and more code](blog.marcgravell.com) (Marc Gravel)
	* [Fabulous Adventures in Coding](ericlippert.com) (Eric Lipert)

## Software Engineering
* Patterns
	* [Martin Fowler](martinfowler.com)
	* [Enterprise Integration Patterns](www.enterpriseintegrationpatterns.com)
* Processes
	* [CMMI](cmmiinstitute.com)
* Architecture
	* [TOGAF](www.opengroup.org/subjectareas/enterprise/togaf) (OpenGroup)
	* [Zachman](www.zachman.com)
* Reference Models
	* [SCOR - Supply Chain Reference Model](www.apics.org/apics-for-business/frameworks/scor) (APICS)
	* [CAUDIT - Higher Education Reference Architecture](www.caudit.edu.au/EA-Framework)

# Tools & Services

## Design
* [Sketch](www.sketchapp.com) - 
  * [Cabana](cabanadesignsystem.com) - Design System for Sketch
* [Figma](www.figma.com) - 
* [lunacy](icons8.com/lunacy) - 
* [Top 20 Design Systems](blog.prototypr.io/top-20-design-systems-7bf0963318ce)

## Content
* Photos
  * [Burst](burst.shopify.com) - Free stock photos for websites and commercial use
  * [Unsplash](unsplash.com) - Beautiful, free photos.
* Symbols
  * [HTML Symsols](www.toptal.com/designers/htmlarrows/symbols) - HTML Currency Symbols, Currency Entities and ASCII Currency Character Code Reference

## Spreadsheet
* [Google Sheets](www.google.com/sheets)
* [Fieldbook](fieldbook.com)

## CMS
* [Publii](getpublii.com) - Make an extremely safe, fast and stylish static blog website in minutes.

## CRM
* 

## HR
* [teamdeck](teamdeck.io)

## Issue Management
* [JIRA](www.atlassian.com/jira)

## Invoicing
* [Elorus](www.elorus.com)

## Communications
* [Slack](slack.com) - Where Work Happens
* [Rocket.Chat](rocket.chat) - The leading free open source team chat Slack alternative. 
* [Intercom]() - Catch, convert and keep more customers
* [Indemandly](indemandly.com) - Simple, powerful, & versatile contact tool that you can stick on your website and social media. 

## Security
* [Gpg4win](www.gpg4win.org) - A secure solution
* [Keybase](keybase.io) - Security app for mobile phones and computers

## Misc.
* [For the Badge](forthebadge.com) - Badges for badges' sake.
