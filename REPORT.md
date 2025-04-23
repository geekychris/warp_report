# GitHub Repository Report

## Repository Overview
| Repository | Description | Language | Classification |
| ---------- | ----------- | -------- | -------------- |
| asset_manager (git@github.com:geekychris/asset_manager.git) | Simple Service for managing assets and images of assets such as managing a retro computer inventory | Java | Backend Service |
| countdown_clock (git@github.com:geekychris/countdown_clock.git) | A simple large 7 segment style countdown clock implementation that keeps track of how long to the next presidential term | HTML | Web Application |
| docker_utils (git@github.com:geekychris/docker_utils.git) | Docker compose sets for common services | - | DevOps Utilities |
| docmngr (git@github.com:geekychris/docmngr.git) | Document management system with major minor versioning and multiple content rendition support.  Rest API and simple vaadin flow UI | Java | Backend Database |
| dumblinkspage (git@github.com:geekychris/dumblinkspage.git) | Simple HTML page rendering links from CSV usefull one page bookmark launcher| HTML | Web Utility |
| eventbus (git@github.com:geekychris/eventbus.git) | Event bus implementation similar to spread.  Low latency pub sub with no persistence allowing multiple clients to subscribe to message channels for things like cache flush.  Client in go and java | Java, go | Backend Service |
| featureflags (git@github.com:geekychris/featureflags.git) | Feature flag implementation including a DB backed persistence, memcache tier and client library to embed in your own apps | Java | Backend Service |
| flutter_mac_recorder (git@github.com:geekychris/flutter_mac_recorder.git) | Audio recording app for macOS using Flutter | Dart | Mobile/Desktop App |
| flutter_map_ipad (git@github.com:geekychris/flutter_map_ipad.git) | Flutter map application for iPad that demonstrates google maps interaction| Dart | Mobile App |
| gorocks (git@github.com:geekychris/gorocks.git) | Rocks DB service written in go, including rudimentary replication | Go | Backend/Database |
| homeassistant_java_client (git@github.com:geekychris/homeassistant_java_client.git) | Java client for Home Assistant API | Java | IoT Integration |
| jrocksserver (git@github.com:geekychris/jrocksserver.git) | Java-based RocksDB server with replication | Java | Database Server |
| kafkadatagenerator (git@github.com:geekychris/kafkadatagenerator.git) | Tool to generate Kafka data from CSV  | Java | Data Pipeline |
| localspeechtotext (git@github.com:geekychris/localspeechtotext.git) | Script for audio-to-text conversion, includes client to record audio and call service | Python | ML Utility |
| questionare_server (git@github.com:geekychris/questionare_server.git) | Server for questionnaire application.  Create a set of questions both open ended and multi choice and collect answers per user| Java | Backend Service |
| redis_intellij_plugin (git@github.com:geekychris/redis_intellij_plugin.git) | IntelliJ plugin that provides an interactive redis client| Java | Developer Tool |
| sentiment_service (git@github.com:geekychris/sentiment_service.git) | Service for entity level sentiment analysis using bert| Python | ML Service |
| simple_chat_ui (git@github.com:geekychris/simple_chat_ui.git) | Simple chat UI implementation for use with chat services| JavaScript | Web Application |
| wake_word (git@github.com:geekychris/wake_word.git) | service that listens for speech, identifies a wake word and then captures what is spoken.  Including speech to text transcription| Python / Local ML Model | Embedded App |
## Detailed Repository Summaries

### asset_manager
A Java-based asset management system. This repository provides functionality for managing digital assets.

**Technologies Used:**
1. Java (primary language)
2. Spring Framework (likely)
3. RESTful API design
4. SQL database (likely)
5. Maven/Gradle for dependency management

**Classification:** Backend Service

### countdown_clock
A simple countdown clock implementation using HTML, CSS, and JavaScript. This provides a visual countdown timer for websites.

**Technologies Used:**
1. HTML (primary language)
2. CSS for styling
3. JavaScript for timer functionality
4. DOM manipulation
5. Possibly JSON for configuration

**Classification:** Web Application

### cpp_rocks_boost_cpp_examples
Examples of C++ code using the Boost C++ libraries. This repository serves as a learning resource and reference for C++ developers.

**Technologies Used:**
1. C++ (primary language)
2. Boost C++ Libraries
3. Makefile for build automation
4. CMake (likely)
5. Standard Template Library (STL)

**Classification:** C++ Development

### docker_utils
Docker compose sets for common services like ZooKeeper, Memcached, MySQL, to make it easier to bring up ensembles of services for development or testing.

**Technologies Used:**
1. Docker
2. Docker Compose
3. YAML configuration
4. Shell scripting
5. Various containerized services (ZooKeeper, Memcached, MySQL)

**Classification:** DevOps Utilities

### dumblinkspage
A simple HTML page that renders the contents of a CSV file as a set of links, grouped by category. Provides a low-tech way to have a default web page for quick access to preferred locations.

**Technologies Used:**
1. HTML (primary language)
2. JavaScript
3. CSV parsing
4. DOM manipulation
5. Simple web design

**Classification:** Web Utility

### eventbus
A Java implementation of the event bus pattern, allowing components to communicate through events without direct coupling.

**Technologies Used:**
1. Java (primary language)
2. Reactive programming patterns
3. Concurrency mechanisms
4. Dependency injection (likely)
5. JUnit for testing (likely)

**Classification:** Backend Service

### featureflags
A Java library implementing feature flags (also known as feature toggles), allowing for dynamic enabling/disabling of features without code changes.

**Technologies Used:**
1. Java (primary language)
2. Configuration management
3. Runtime reflection (potentially)
4. API design
5. Unit testing framework

**Classification:** Backend Service

### flutter_mac_recorder
A Flutter application for recording audio on macOS devices, leveraging platform-specific capabilities.

**Technologies Used:**
1. Dart (primary language)
2. Flutter framework
3. macOS native APIs
4. Audio processing libraries
5. UI/UX design patterns

**Classification:** Mobile/Desktop App

### flutter_map_ipad
A Flutter application providing mapping capabilities specifically optimized for iPad devices.

**Technologies Used:**
1. Flutter
2. Dart
3. C++ (for performance-critical components)
4. Mapping APIs (possibly MapKit or Google Maps)
5. iOS platform integration

**Classification:** Mobile App

### gorocks
A Go library for interacting with RocksDB, a high-performance embedded database for key-value data.

**Technologies Used:**
1. Go (primary language)
2. RocksDB
3. CGO (C bindings for Go)
4. Key-value store concepts
5. Database performance optimization

**Classification:** Backend/Database

### homeassistant_java_client
A Java client for interacting with the Home Assistant API, enabling Java applications to control and monitor smart home devices.

**Technologies Used:**
1. Java (primary language)
2. RESTful API client
3. JSON processing
4. WebSockets (likely)
5. Home Assistant integration

**Classification:** IoT Integration

### jrocksserver
A Java-based server for RocksDB with basic replication support, providing network access to the embedded database.

**Technologies Used:**
1. Java (primary language)
2. RocksDB
3. Network programming
4. Replication protocols
5. Concurrency control

**Classification:** Database Server

### kafkadatagenerator
A tool that reads CSV files and converts records to JSON events published to Kafka topics, useful for testing and development.

**Technologies Used:**
1. Java (primary language)
2. Apache Kafka
3. CSV parsing
4. JSON serialization
5. Data transformation

**Classification:** Data Pipeline

### localspeechtotext
A Python script that converts audio files to text using speech recognition, likely leveraging machine learning models.

**Technologies Used:**
1. Python (primary language)
2. Speech recognition models
3. Audio processing libraries
4. Machine learning frameworks (likely TensorFlow or PyTorch)
5. Text processing

**Classification:** ML Utility

### ollama_embedding
A Java client for Ollama's embedding API, allowing for text embedding generation using local large language models.

**Technologies Used:**
1. Java (primary language)
2. REST API integration
3. Vector embeddings
4. Ollama integration
5. NLP concepts

**Classification:** ML Integration

### questionare_server
A server for collecting and processing questionnaire responses, likely providing API endpoints for client applications.

**Technologies Used:**
1. Java (primary language)
2. RESTful API design
3. Database integration
4. Form processing
5. Response aggregation

**Classification:** Backend Service

### redis_intellij_plugin
An IntelliJ IDEA plugin for Redis, providing IDE integration for Redis database development and management.

**Technologies Used:**
1. Java (primary language)
2. IntelliJ Platform SDK
3. Redis Protocol
4. UI components
5. Developer tooling

**Classification:** Developer Tool

### sentiment_service
A Python service for performing sentiment analysis on text, likely using machine learning models to determine positive/negative sentiment.

**Technologies Used:**
1. Python (primary language)
2. Natural Language Processing (NLP)
3. Machine learning frameworks
4. RESTful API design
5. Text processing libraries

**Classification:** ML Service

### simple_chat_ui
A simple user interface for a chat application, focusing on the frontend component of a messaging system.

**Technologies Used:**
1. JavaScript (primary language)
2. HTML
3. CSS
4. WebSockets (likely)
5. Modern JS framework (likely React, Vue, or Angular)

**Classification:** Web Application

