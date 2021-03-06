# Java9 Workshop
## Intro
### JEP223	New Version-String Scheme
### JEP237	Linux/AArch64 Port


## general - without a component
### JEP200	The Modular JDK
### JEP201	Modular Source Code
### JEP220	Modular Run-Time Images
### JEP260	Encapsulate Most Internal APIs
### JEP261	Module System


## core 
### JEP259 - Stack-Walking API -- [web](http://openjdk.java.net/jeps/259)

## core-jdk.nashorn    
### JEP236 - 	Parser API for Nashorn

## core-lang	  
### JEP102	- Process API Updates -- [web](http://openjdk.java.net/jeps/102)
#### ProcessBuilder
##### public static final Redirect DISCARD
#### Process
##### public boolean supportsNormalTermination()
##### public long getPid()
##### public CompletableFuture<Process> onExit()
##### public ProcessHandle toHandle()
##### public ProcessHandle.Info info()
##### public Stream<ProcessHandle> children()
##### public Stream<ProcessHandle> descendants()
### ProcessHandle

### Process
#### public boolean supportsNormalTermination()
#### public long getPid()
#### public CompletableFuture<Process> onExit()
#### public ProcessHandle toHandle()
#### public ProcessHandle.Info info()
#### public Stream<ProcessHandle> children()
#### public Stream<ProcessHandle> descendants()



### JEP193	- Variable Handles
### JEP227	- Unicode 7.0
### JEP254	- Compact Strings - Newsletter von Heinz
### JEP267	- Unicode 8.0
### JEP277	- Enhanced Deprecation - evtl nicht im JDK9
### JEP285	- Spin-Wait Hints

## core-lang.invoke	
### JEP274	- Enhanced Method Handles
### JEP276	- Dynamic Linking of Language-Defined Object Models

## core-net    
### JEP110	- HTTP/2 Client


## core-util:collections   
### JEP269	- Convenience Factory Methods for Collections

## core-util:i18n  
### JEP226	- UTF-8 Property Files
### JEP252 - Use CLDR Locale Data by Default


## core-util.concurrent    
### JEP266 - 	More Concurrency Updates

## core-util.logging   
### JEP264	 - Platform Logging API and Service - LoggerFinder


## client-2d
### JEP251 - Multi-Resolution Images
### JEP258 - HarfBuzz Font-Layout Engine - info only
### JEP265 - Marlin Graphics Renderer - info only

## client-awt
### JEP263 - HiDPI Graphics on Windows and Linux - info only
### JEP272 - Platform-Specific Desktop Features

## client-beans
### JEP256 - BeanInfo Annotations

## client-javax.imageio	
### JEP262 - TIFF Image I/O

## javafx-controls	
### JEP253	Prepare JavaFX UI Controls & CSS APIs for Modularization - info only

## javafx-media	
### JEP257	Update JavaFX/Media to Newer Version of GStreamer - info only



## security-javax.crypto	
### JEP246	Leverage CPU Instructions for GHASH and RSA

## security-javax.net.ssl	
### JEP219	Datagram Transport Layer Security (DTLS)
### JEP244	TLS Application-Layer Protocol Negotiation Extension
### JEP249	OCSP Stapling for TLS

## security-security	
### JEP229	Create PKCS12 Keystores by Default
### JEP232	Improve Secure Application Performance
### JEP273	DRBG-Based SecureRandom Implementations
### JEP287	SHA-3 Hash Algorithms
### JEP288	Disable SHA-1 Certificates





## hotspot-gc	
### JEP214	Remove GC Combinations Deprecated in JDK 8
### JEP248	Make G1 the Default Garbage Collector
### JEP271	Unified GC Logging

## hotspot-compiler	
### JEP165	Compiler Control - ?? to abstract for most developersJEP165
### JEP197	Segmented Code Cache
### JEP233	Generate Run-Time Compiler Tests Automatically - not part of the book
### JEP243	Java-Level JVM Compiler Interface

## hotspot-runtime	
### JEP143	Improve Contended Locking
### JEP245	Validate JVM Command-Line Flag Arguments
### JEP250	Store Interned Strings in CDS Archives
### JEP270	Reserved Stack Areas for Critical Sections

## hotspot-svc	
### JEP158	Unified JVM Logging - see JEP271
### JEP228	Add More Diagnostic Commands



## tools-jar	
## core-svc-tools  
### JEP240	 - Remove the JVM TI hprof Agent
### JEP241	 - Remove the jhat Tool




## tools-javadoc(tool)	
### JEP221	Simplified Doclet API
### JEP224	HTML5 Javadoc
### JEP225	Javadoc Search

## tools-javac	
### JEP199	Smart Java Compilation, Phase Two
### JEP211	Elide Deprecation Warnings on Import Statements
### JEP213	Milling Project Coin
### JEP215	Tiered Attribution for javac
### JEP216	Process Import Statements Correctly
### JEP217	Annotations Pipeline 2.0
### JEP235	Test Class-File Attributes Generated by javac
### JEP247	Compile for Older Platform Versions
### JEP280	Indify String Concatenation

### JEP238	Multi-Release JAR Files

## tools-jlink	
### JEP282	jlink: The Java Linker

## deploy-packager	
### JEP275	Modular Java Application Packaging

## tools-jshell	
### JEP222	jshell: The Java Shell (Read-Eval-Print Loop)

## tools-launcher	
### JEP231	Remove Launch-Time JRE Version Selection


## Coding Practices
### Streams (from Java8 to Java9)
### Functional Coding Aspects with Java9

## TDD
### jUnit4 and jUnit5
### From jUnit to Mutation-Testing 
### testing JavaFX with TestFX

## Microbenchmarking 
### JMH
### Collecting Metrics with ProxyBuilder
### gatling
