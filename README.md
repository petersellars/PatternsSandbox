# Patterns Exploration

[Software Design Patterns on Wikipedia](http://en.wikipedia.org/wiki/Software_design_pattern)

[Distributed Design Patterns on Wikipedia](http://en.wikipedia.org/wiki/Distributed_design_patterns)

[xUnit Patterns](http://xunitpatterns.com/index.html)

## Development

### Creational
* Abstract Factory
* Builder
* Factory Method
* Lazy Initialization
* Multition
* Object Pool
* Prototype
* Resource acquisition is initialization
* Singleton

### Structural
* Adapter (Wrapper/Translator)
* Bridge
* Composite
* Decorator
* Facade
* Flyweight
* Front Controller
* Module
* Proxy
* Twin

### Behavioural
* Blackboard
* Chain of Responsibility
* Command
* Interpreter
* Iterator
* Mediator
* Memento
* Null Object
* Observer (Publish-Subscribe)
* Servant
* Specification
* State
* Strategy
* Template Method
* Visitor

### Concurrency
* Active Object
* Balking
* Binding Properties
* Double-Checked Locking
* Event-Based Asynchronous
* Guarded Suspension
* Join
* Lock
* Messaging Design Pattern (MDP)
* Monitor Object
* Reactor
* Read-Write Lock
* Scheduler
* Thread Pool
* Thread-Specific Storage

### Architectural
* Front Controller
* Interceptor
* MVC
* n-tier
* Specification
* Publish-Subscribe
* Naked Objects
* Service Locator
* Active Record
* Identity Map
* Data Access Object
* Data Transfer Object

## Distributed

### Distributed Communication

### Security & Reliability

### Event Driven

## Testing

### Basic
* Test Execution
    * Test Automation Framework
    * Test Runner
    * Test Discovery
    * Test Enumeration
    * Test Selection
    * Testcase Object
    * Test Suite Object
* Test Definition
    * Test Method
    * Assertion Method
    * Testcase Class
    * Four Phase Test
    * Assertion Message

### Automation Strategy
* Test Automation Strategy
    * Recorded Test
    * Scripted Test
    * Data-Driven Test
    * Test Automation Framework
* SUT Interaction Strategy
    * Layer Test
    * Back Door Manipulation
* Test Fixture Strategy
    * Minimal Fixture
    * Standard Fixture
    * Fresh Fixture
        * Persistent
        * Transient
    * Shared Fixture
        * Immutable Fixture

### Fixture Setup
* Fresh Fixture Setup
    * Inline Setup
    * Delegated Setup
    * Implicit Setup
    * Creation Method
    * Test Helper
        * Object Mother
* Shared Fixture Construction
    * Prebuilt Fixture
    * Lazy Setup
    * SuiteFixture Setup
    * Setup Decorator
    * Chained Tests
* Shared Fixture Access
    * Test Utility Method
    * Finder Method
* Result Verification
    * Delta Assertion

### Fixture TearDown
* Applicability
    * Persistent Fresh Fixture
    * Shared Fixture
* Code Organization
    * Inline TearDown
    * Implicit TearDown
* Teardown Strategy
    * Table Truncation TearDown
    * Transaction Rollback TearDown
    * Garbage-Collected TearDown
    * Automated TearDown

### Result Verification
* Verification Strategy
    * State Verification
    * Behaviour Verification
    * Back Door Verification
    * Assertion Method
* Assertion Method Styles
    * Guard Assertion
    * Custom Assertion
        * Verification Method
    * Delta Assertion

### Test Organization
* Named Test Suite
* Testcase Class Structure
    * Testcase Class per Class
    * Testcase Class per Fixture
    * Testcase Class per Feature
* Test Code Reuse
    * Test Utility Method
        * Finder Method
        * Creation Method
        * Custom Assertion
            * Verification Method
        * Parameterized Test
* Utility Method Location
    * Testcase Class
    * Testcase Superclass
    * Test Helper
        * Object Mother

### Test Double
* Test-Specific Subclass
    * Subclassed Test Double
* Test Double
* Test Double Usage
    * Dummy Object
    * Fake Object
    * Test Stub
    * Test Spy
    * Mock Object
* Test Double Construction
    * Configuration Test Double
    * Hard-coded Test Double

### Value
* Literal Value
* Generated Value
* Derived Value
* Dummy Object

### Datbase
* Fake Database
* Database Sandbox
* Delta Assertion
* Table Truncation TearDown
    * Lazy TearDown
* Transaction Rollback TearDown
* Stored Procedure Test

### Design-for-Testability
* Dependency Injection
    * Setter Injection
    * Parameter Injection
    * Constructor Injection
* Dependency Lookup
    * Object Factory
    * Service Locator
* Humble Object
    * Humble Container Adapter
    * Humble Transaction Controller
    * Humble Executable
    * Humble Dialog
* Test Hook
* Test-Specific Subclass
    * Subsituted Singleton
