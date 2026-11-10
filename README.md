# Awesome Clojure [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for Clojure, ClojureScript, web routing, data transformation engines, database tooling, concurrency frameworks, and REPL-driven development.

Clojure is a functional, dynamic Lisp dialect targeting the Java Virtual Machine (JVM), JavaScript (ClojureScript), and native runtimes. Its immutable data structures, macro system, and emphasis on state management enable high-concurrency systems, interactive development, and data-driven architectures. This list is intended for software engineers, backend developers, Clojure developers, and system architects.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Web Development & Routing](#web-development--routing)
- [Database & Query Engines](#database--query-engines)
- [Data Validation & Transformation](#data-validation--transformation)
- [Concurrency & Asynchronous Processing](#concurrency--asynchronous-processing)
  - [Async & Event Streams](#async--event-streams)
  - [Component Lifecycles](#component-lifecycles)
- [Related Awesome Lists](#related-awesome-lists)

## Web Development & Routing

Libraries, micro-frameworks, and server abstractions for building HTTP APIs, web applications, and routing trees in Clojure.

- [Ring](https://github.com/ring-clojure/ring) — Standard Clojure HTTP server abstraction providing request/response maps and middleware specifications.
- [Compojure](https://github.com/weavejester/compojure) — Concise routing library for Ring designed to map HTTP requests to handling functions.
- [Reitit](https://github.com/metosin/reitit) — High-performance data-driven routing engine supporting Ring, coercion, OpenAPI, and client-side ClojureScript routing.
- [http-kit](https://github.com/http-kit/http-kit) — High-performance, event-driven HTTP client and server library with native WebSocket support.
- [Luminus](https://github.com/luminus-framework/luminus) — Robust micro-framework ecosystem for building scalable web applications using composable Clojure components.

## Database & Query Engines

Data-driven SQL generators, Datomic integrations, lightweight Datalog engines, and migration tooling.

- [HoneySQL](https://github.com/seancorfield/honeysql) — Data-driven library for building SQL queries by constructing Clojure data structures.
- [next.jdbc](https://github.com/seancorfield/next-jdbc) — Modern, high-performance Clojure wrapper interface over Java Database Connectivity (JDBC).
- [DataScript](https://github.com/tonsky/datascript) — Immutable, in-memory Datalog database engine running in both Clojure and ClojureScript environments.
- [Migratus](https://github.com/migratus/migratus) — General-purpose database migration framework managing schema updates through SQL or Clojure scripts.
- [Toucan](https://github.com/metabase/toucan) — Lightweight ORM-like library designed for managing database models and relationships cleanly.

## Data Validation & Transformation

Schema definition engines, pattern matching engines, and data structure manipulation toolkits.

- [malli](https://github.com/metosin/malli) — High-performance, data-driven schema specification, validation, and transformation library for Clojure(Script).
- [clojure.spec](https://clojure.org/guides/spec) — Core Clojure library for describing the structure of data, validating inputs, and generating property-based tests.
- [Specter](https://github.com/redplanetlabs/specter) — Declarative query and transformation API for navigating and updating deeply nested and recursive data structures.
- [Instaparse](https://github.com/Engelberg/instaparse) — Parser generator transforming context-free grammars directly into Clojure data trees without code generation steps.

## Concurrency & Asynchronous Processing

Channel-based concurrency models, state management primitives, and application lifecycle frameworks.

### Async & Event Streams

- [core.async](https://github.com/clojure/core.async) — Asynchronous programming library introducing CSP (Communicating Sequential Processes) channels to Clojure and ClojureScript.
- [Manifold](https://github.com/clj-commons/manifold) — Building blocks for asynchronous abstractions, unifying streams, deferreds, and futures.
- [Aleph](https://github.com/clj-commons/aleph) — Asynchronous information exchange framework built on Netty for non-blocking HTTP, TCP, and UDP communication.

### Component Lifecycles

- [Component](https://github.com/stuartsierra/component) — Framework for managing dependency injection and lifecycle states (start/stop) of Clojure software systems.
- [Integrant](https://github.com/weavejester/integrant) — Data-driven framework for managing application architecture, service initialization, and configuration maps.
- [Mount](https://github.com/tolitius/mount) — Lightweight alternative for managing system state along namespace boundaries for rapid REPL workflows.

## Related Awesome Lists

- [Awesome Functional Programming](https://github.com/brandonhimpfen/awesome-functional-programming) — Purely functional languages, lambda calculus, type systems, and immutable data.
- [Awesome Java](https://github.com/brandonhimpfen/awesome-java) — Frameworks, concurrency libraries, and high-performance JVM tools.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Client and server-side JS ecosystem tools, bundlers, and runtime engines.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community management frameworks for open projects.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
