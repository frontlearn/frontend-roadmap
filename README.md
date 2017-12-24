# Frontend Roadmap

Roadmap for learning frontend.

## Table of Contents

1. [Introducion](#introducion)
2. [Bash, Command Line](#bash-command-line)
3. [HTTP](#http)
4. [Git](#git)
5. HTML
6. SVG
7. CSS
8. Preprocessors
9. Bootstrap
10. [JavaScript](#javascript)
11. [Data Structures](#data-structures)
12. [Algorithms](#algorithms)
13. Functional programming
14. Object-oriented programming
15. Design Patterns
16. Lodash
17. Browser
18. [DOM](#dom)
19. jQuery
20. React
21. Redux
22. Node.js
23. Package Managers
24. Web Server
25. Express
26. Scaffolding
27. Task Runners
28. Bundlers
29. Testing
30. Databases
31. Clouds
32. Continuous Integration
33. Virtualization

## Introducion

- [ ] How to learn?

## Bash, Command Line

- [ ] Basic Shell Features
  - [ ] Shell Syntax
  - [ ] Shell Commands
    - [ ] Simple Commands
    - [ ] Pipelines
    - [ ] Lists of Commands
    - [ ] Compound Commands
    - [ ] Coprocesses
  - [ ] Shell Functions
  - [ ] Shell Parameters
  - [ ] Shell Expansions
  - [ ] Redirections
  - [ ] Executing Commands
    - [ ] Environment
    - [ ] Exit Status
    - [ ] Signals
- [ ] Shell Builtin Commands
  - [ ] File system
  - [ ] Input and Output
  - [ ] System Info
  - [ ] Network
  - [ ] Process Monitoring
- [ ] Shell Variables
- [ ] Bash Features
  - [ ] Invoking Bash
  - [ ] Interactive Shells
  - [ ] Bash Conditional Expressions
  - [ ] Shell Arithmetic
  - [ ] Aliases
  - [ ] Arrays
  - [ ] The Directory Stack
  - [ ] Controlling the Prompt
- [ ] Job Control
- [ ] Command Line Editing
- [ ] Bash History
- [ ] Documentation

Links:

- [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html) (official)
- [The Bash Guide](http://guide.bash.academy)
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [Awesome OSX Command Line](https://github.com/herrbischoff/awesome-osx-command-line)
- [Awesome Shell](https://github.com/alebcay/awesome-shell)
- [Bash Guide](https://github.com/Idnan/bash-guide)
- [Bash Handbook](https://github.com/denysdovhan/bash-handbook)
- [Data Science at the Command Line](http://datascienceatthecommandline.com)
- [Filenames and Pathnames in Shell: How to do it Correctly](https://www.dwheeler.com/essays/filenames-in-shell.html)
- [Unofficial Bash Strict Mode](http://redsymbol.net/articles/unofficial-bash-strict-mode)
- [An A-Z Index of the Bash command line for Linux](https://ss64.com/bash)
- [bash-completion](https://github.com/scop/bash-completion) (tool)
- [ShellCheck](https://github.com/koalaman/shellcheck) (tool)

## HTTP

- [ ] Message Syntax and Routing
  - [ ] Architecture
  - [ ] Message Format
  - [ ] Transfer Codings
  - [ ] Message Routing
  - [ ] Connection Management
  - [ ] Security Considerations
- [ ] Semantics and Content
  - [ ] Representations
  - [ ] Request Methods
  - [ ] Request Header Fields
  - [ ] Response Status Codes
  - [ ] Response Header Fields
  - [ ] Security Considerations
- [ ] Conditional Requests
  - [ ] Validators
  - [ ] Precondition Header Fields
  - [ ] Status Code Definitions
  - [ ] Evaluation
  - [ ] Precedence
  - [ ] Security Considerations
- [ ] Range Requests
  - [ ] Range Units
  - [ ] Range Requests
  - [ ] Responses to a Range Request
  - [ ] Security Considerations
- [ ] Caching
  - [ ] Overview of Cache Operation
  - [ ] Storing Responses in Caches
  - [ ] Constructing Responses from Caches
  - [ ] Header Field Definitions
  - [ ] History Lists
  - [ ] Security Considerations
- [ ] Authentication
  - [ ] Access Authentication Framework
  - [ ] Status Code Definitions
  - [ ] Header Field Definitions
  - [ ] Security Considerations

Links:

- [Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing](https://tools.ietf.org/html/rfc7230) (official)
- [Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content](https://tools.ietf.org/html/rfc7231) (official)
- [Hypertext Transfer Protocol (HTTP/1.1): Conditional Requests](https://tools.ietf.org/html/rfc7232) (official)
- [Hypertext Transfer Protocol (HTTP/1.1): Range Requests](https://tools.ietf.org/html/rfc7233) (official)
- [Hypertext Transfer Protocol (HTTP/1.1): Caching](https://tools.ietf.org/html/rfc7234) (official)
- [Hypertext Transfer Protocol (HTTP/1.1): Authentication](https://tools.ietf.org/html/rfc7235) (official)
- [HyperText Transfer Protocol Design Issues](https://www.w3.org/Protocols/DesignIssues.html)
- [HTTP | MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [curl](https://github.com/curl/curl) (tool)

## Git

- [ ] Setup and Config
  - [ ] git
  - [ ] config
  - [ ] help
- [ ] Getting and Creating Projects
  - [ ] init
  - [ ] clone
- [ ] Basic Snapshotting
  - [ ] add
  - [ ] status
  - [ ] diff
  - [ ] commit
  - [ ] reset
  - [ ] rm
  - [ ] mv
- [ ] Branching and Merging
  - [ ] branch
  - [ ] checkout
  - [ ] merge
  - [ ] mergetool
  - [ ] log
  - [ ] stash
  - [ ] tag
- [ ] Sharing and Updating Projects
  - [ ] fetch
  - [ ] pull
  - [ ] push
  - [ ] remote
  - [ ] submodule
- [ ] Inspection and Comparison
  - [ ] show
  - [ ] log
  - [ ] diff
  - [ ] shortlog
  - [ ] describe
  - [ ] Patching
  - [ ] apply
  - [ ] cherry-pick
  - [ ] diff
  - [ ] rebase
  - [ ] revert
- [ ] Debugging
  - [ ] bisect
  - [ ] blame
  - [ ] grep
- [ ] Guides
  - [ ] gitattributes
  - [ ] Everyday Git
  - [ ] Glossary
  - [ ] gitignore
  - [ ] gitmodules
  - [ ] Revisions
  - [ ] Tutorial
  - [ ] Workflows
- [ ] Email
  - [ ] am
  - [ ] apply
  - [ ] format-patch
  - [ ] send-email
  - [ ] request-pull
- [ ] External Systems
  - [ ] svn
  - [ ] fast-import
- [ ] Administration
  - [ ] clean
  - [ ] gc
  - [ ] fsck
  - [ ] reflog
  - [ ] filter-branch
  - [ ] instaweb
  - [ ] archive
  - [ ] bundle
- [ ] Server Admin
  - [ ] daemon
  - [ ] update-server-info
- [ ] Plumbing Commands
  - [ ] cat-file
  - [ ] check-ignore
  - [ ] checkout-index
  - [ ] commit-tree
  - [ ] count-objects
  - [ ] diff-index
  - [ ] for-each-ref
  - [ ] hash-object
  - [ ] ls-files
  - [ ] merge-base
  - [ ] read-tree
  - [ ] rev-list
  - [ ] rev-parse
  - [ ] show-ref
  - [ ] symbolic-ref
  - [ ] update-index
  - [ ] update-ref
  - [ ] verify-pack
  - [ ] write-tree

Links:

- [Git Reference Manual](https://git-scm.com) (official)
- [Pro Git](https://git-scm.com/book/en/v2) (book)
- [Git User’s Manual](http://schacon.github.io/git/user-manual.html)
- [GitHowTo](https://githowto.com) (course)
- [Learn Git Branching](https://learngitbranching.js.org) (course)
- [GitHub](https://github.com) (service)
- [gitk](http://gitk.sourceforge.net) (tool)
- [gitx](https://github.com/pieter/gitx) (tool)

## HTML

## SVG

## CSS

## Preprocessors

## Bootstrap

## JavaScript

- [ ] Overview
  - [ ] Web Scripting
  - [ ] ECMAScript Overview
  - [ ] Terms and Definitions
  - [ ] Organization of This Specification
- [ ] Data Types and Values
  - [ ] Language Types
  - [ ] Specification Types
- [ ] Abstract Operations
  - [ ] Type Conversion
  - [ ] Testing and Comparison Operations
  - [ ] Operations on Objects
  - [ ] Operations on Iterator Objects
- [ ] Executable Code and Execution Contexts
  - [ ] Lexical Environments
  - [ ] Realms
  - [ ] Execution Contexts
  - [ ] Jobs and Job Queues
  - [ ] InitializeHostDefinedRealm
  - [ ] RunJobs
  - [ ] Agents
  - [ ] Agent Clusters
  - [ ] Forward Progress
- [ ] Ordinary and Exotic Objects Behaviours
  - [ ] Ordinary Object Internal Methods and Internal Slots
  - [ ] Function Objects
  - [ ] Built-in Function Objects
  - [ ] Built-in Exotic Object Internal Methods and Slots
  - [ ] Proxy Object Internal Methods and Internal Slots
- [ ] Source Code
  - [ ] Source Text
  - [ ] Types of Source Code
    - [ ] Strict Mode Code
    - [ ] Non-ECMAScript Functions
- [ ] Lexical Grammar
  - [ ] Unicode Format-Control Characters
  - [ ] White Space
  - [ ] Line Terminators
  - [ ] Comments
  - [ ] Tokens
  - [ ] Names and Keywords
  - [ ] Punctuators
  - [ ] Literals
  - [ ] Automatic Semicolon Insertion
- [ ] Expressions
  - [ ] Identifiers
  - [ ] Primary Expression
  - [ ] Left-Hand-Side Expressions
  - [ ] Update Expressions
  - [ ] Unary Operators
  - [ ] Exponentiation Operator
  - [ ] Multiplicative Operators
  - [ ] Additive Operators
  - [ ] Bitwise Shift Operators
  - [ ] Relational Operators
  - [ ] Equality Operators
  - [ ] Binary Bitwise Operators
  - [ ] Binary Logical Operators
  - [ ] Conditional Operator ( ? : )
  - [ ] Assignment Operators
  - [ ] Comma Operator ( , )
- [ ] Statements and Declarations
  - [ ] Statement Semantics
  - [ ] Block
  - [ ] Declarations and the Variable Statement
  - [ ] Empty Statement
  - [ ] Expression Statement
  - [ ] The if Statement
  - [ ] Iteration Statements
  - [ ] The continue Statement
  - [ ] The break Statement
  - [ ] The return Statement
  - [ ] The with Statement
  - [ ] The switch Statement
  - [ ] Labelled Statements
  - [ ] The throw Statement
  - [ ] The try Statement
  - [ ] The debugger Statement
- [ ] Functions and Classes
  - [ ] Function Definitions
  - [ ] Arrow Function Definitions
  - [ ] Method Definitions
  - [ ] Generator Function Definitions
  - [ ] Class Definitions
  - [ ] Async Function Definitions
  - [ ] Async Arrow Function Definitions
  - [ ] Tail Position Calls
- [ ] Scripts and Modules
  - [ ] Scripts
  - [ ] Modules
- [ ] Error Handling and Language Extensions
  - [ ] HostReportErrors ( errorList )
  - [ ] Forbidden Extensions
- [ ] Standard Built-in Objects
- [ ] The Global Object
  - [ ] Value Properties of the Global Object
  - [ ] Function Properties of the Global Object
  - [ ] Constructor Properties of the Global Object
  - [ ] Other Properties of the Global Object
- [ ] Fundamental Objects
  - [ ] Object Objects
  - [ ] Function Objects
  - [ ] Boolean Objects
  - [ ] Symbol Objects
  - [ ] Error Objects
- [ ] Numbers and Dates
  - [ ] Number Objects
  - [ ] The Math Object
  - [ ] Date Objects
- [ ] Text Processing
  - [ ] String Objects
  - [ ] RegExp (Regular Expression) Objects
- [ ] Indexed Collections
  - [ ] Array Objects
  - [ ] TypedArray Objects
- [ ] Keyed Collection
  - [ ] Map Objects
  - [ ] Set Objects
  - [ ] WeakMap Objects
  - [ ] WeakSet Objects
- [ ] Structured Data
  - [ ] ArrayBuffer Objects
  - [ ] SharedArrayBuffer Objects
  - [ ] DataView Objects
  - [ ] The Atomics Object
  - [ ] The JSON Object
- [ ] Control Abstraction Objects
  - [ ] Iteration
  - [ ] GeneratorFunction Objects
  - [ ] Generator Objects
  - [ ] Promise Objects
  - [ ] AsyncFunction Objects
- [ ] Reflection
  - [ ] The Reflect Object
  - [ ] Proxy Objects
  - [ ] Module Namespace Objects
- [ ] Memory Model
  - [ ] Memory Model Fundamentals
  - [ ] Agent Events Records
  - [ ] Chosen Value Records
  - [ ] Candidate Executions
  - [ ] Abstract Operations for the Memory Model
  - [ ] Relations of Candidate Executions
  - [ ] Properties of Valid Executions
  - [ ] Races
  - [ ] Data Races
  - [ ] Data Race Freedom
  - [ ] Shared Memory Guidelines

Links:

- [ECMA-262 8th Edition, June 2017. ECMAScript® 2017 Language Specification](http://www.ecma-international.org/ecma-262/8.0/index.html) (official)
- [ECMA-262 7th Edition, June 2016. ECMAScript® 2016 Language Specification](http://www.ecma-international.org/ecma-262/7.0/index.html) (official)
- [ECMA-262 6th Edition, June 2015. ECMAScript® 2015 Language Specification](http://www.ecma-international.org/ecma-262/6.0/index.html) (official)
- [ECMA-262 5.1 Edition, June 2011. ECMAScript® Language Specification](http://www.ecma-international.org/ecma-262/5.1/index.html) (official)
- [JavaScript | Code School](https://www.javascript.com)
- [JavaScript | MDN](https://developer.mozilla.org/ru/docs/Web/JavaScript)
- [JS Bin](https://jsbin.com) (service)
- [JSFiddle](https://jsfiddle.net) (service)
- [Babel](http://babeljs.io) (tool)

## Data Structures

- [ ] Data types
	- [ ] Primitive types
    - [ ] Boolean
    - [ ] Character
    - [ ] Floating-point (single-precision real number values)
    - [ ] Double (a wider floating-point size)
    - [ ] Integer (integral, fixed-precision values)
    - [ ] String
    - [ ] Reference (pointer, handle)
    - [ ] Enumerated type
	- [ ] Composite types or Non-primitive type
    - [ ] Array
    - [ ] Record (tuple, structure)
    - [ ] Union
    - [ ] Tagged union (variant, variant record, discriminated union, disjoint union)
	- [ ] Abstract data types
    - [ ] Container
    - [ ] List
    - [ ] Associative array
    - [ ] Multimap
    - [ ] Set
    - [ ] Multiset (Bag)
    - [ ] Stack
    - [ ] Queue
    - [ ] Double-ended queue
    - [ ] Priority queue
    - [ ] Tree
    - [ ] Graph
- [ ] Linear data structures
	- [ ] Arrays
	- [ ] Types of Lists
- [ ] Trees
	- [ ] Binary trees
	- [ ] B-trees
	- [ ] Heaps
	- [ ] Trees
	- [ ] Multiway trees
	- [ ] Space-partitioning trees
	- [ ] Application-specific trees
- [ ] Hashes
- [ ] Graphs
- [ ] Other
  - [ ] Lightmap
  - [ ] Winged edge
  - [ ] Doubly connected edge list
  - [ ] Quad-edge
  - [ ] Routing table
  - [ ] Symbol table

Links:

- [List of data structures | Wikipedia](https://en.wikipedia.org/wiki/List_of_data_structures)
- [Data Structures | Interviews](https://github.com/kdn251/interviews#data-structures)
- [Itsy Bitsy Data Structures](https://github.com/thejameskyle/itsy-bitsy-data-structures)
- [algorithms.js](https://github.com/felipernb/algorithms.js)

## Algorithms

- [ ] Automated planning
- [ ] Combinatorial algorithms
	- [ ] General combinatorial algorithms
	- [ ] Graph algorithms
		- [ ] Graph drawing
		- [ ] Network theory
		- [ ] Routing for graphs
		- [ ] Graph search
		- [ ] Subgraphs
	- [ ] Sequence algorithms
		- [ ] Approximate sequence matching
		- [ ] Selection algorithms
		- [ ] Sequence search
		- [ ] Sequence merging
		- [ ] Sequence permutations
		- [ ] Sequence alignment
		- [ ] Sequence sorting
		- [ ] Subsequences
		- [ ] Substrings
- [ ] Computational mathematics
	- [ ] Abstract algebra
	- [ ] Computer algebra
	- [ ] Geometry
	- [ ] Number theoretic algorithms
	- [ ] Numerical algorithms
		- [ ] Differential equation solving
		- [ ] Elementary and special functions
		- [ ] Geometric
		- [ ] Interpolation and extrapolation
		- [ ] Linear algebra
		- [ ] Monte Carlo
		- [ ] Numerical integration
		- [ ] Root finding
	- [ ] Optimization algorithms
- [ ] Computational science
	- [ ] Astronomy
	- [ ] Bioinformatics
	- [ ] Geoscience
	- [ ] Linguistics
	- [ ] Medicine
	- [ ] Physics
	- [ ] Statistics
- [ ] Computer science
	- [ ] Computer architecture
	- [ ] Computer graphics
	- [ ] Cryptography
	- [ ] Digital logic
	- [ ] Machine learning and statistical classification
	- [ ] Programming language theory
		- [ ] Parsing
	- [ ] Quantum algorithms
	- [ ] Theory of computation and automata
- [ ] Information theory and signal processing
	- [ ] Coding theory
		- [ ] Error detection and correction
		- [ ] Lossless compression algorithms
		- [ ] Lossy compression algorithms
	- [ ] Digital signal processing
		- [ ] Image processing
- [ ] Software engineering
- [ ] Database algorithms
- [ ] Distributed systems algorithms
	- [ ] Memory allocation and deallocation algorithms
- [ ] Networking
- [ ] Operating systems algorithms
	- [ ] Process synchronization
	- [ ] Scheduling
	- [ ] I/O scheduling
		- [ ] Disk scheduling

Links:

- [List of algorithms | Wikipedia](https://en.wikipedia.org/wiki/List_of_algorithms)
- [Algorithms | Khan Academy](https://www.khanacademy.org/computing/computer-science/algorithms) (course)
- [Algorithms | Interviews](https://github.com/kdn251/interviews#algorithms)
- [Algorithms | Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook/tree/master/algorithms)
- [Pretty algorithms](https://github.com/jiayihu/pretty-algorithms)
- [Itsy Bitsy Data Structures](https://github.com/thejameskyle/itsy-bitsy-data-structures)
- [algorithms.js](https://github.com/felipernb/algorithms.js)

## Functional programming

## Object-oriented programming

## Design Patterns

## Lodash

## Browser

## DOM

- [ ] Terminology
  - [ ] Trees
  - [ ] Strings
  - [ ] Ordered sets
  - [ ] Namespaces
- [ ] Events
  - [ ] Introduction to DOM Events
  - [ ] Interface Event
  - [ ] Interface CustomEvent
  - [ ] Constructing events
  - [ ] Defining event interfaces
  - [ ] Interface EventTarget
  - [ ] Dispatching events
  - [ ] Firing events
- [ ] Nodes
  - [ ] Introduction to The DOM
  - [ ] Node tree
    - [ ] Mutation algorithms
    - [ ] Interface NonElementParentNode
    - [ ] Interface ParentNode
    - [ ] Interface NonDocumentTypeChildNode
    - [ ] Interface ChildNode
    - [ ] Interface NodeList
    - [ ] Interface HTMLCollection
  - [ ] Mutation observers
    - [ ] Interface MutationObserver
    - [ ] Queuing a mutation record
    - [ ] Interface MutationRecord
    - [ ] Garbage collection
  - [ ] Interface Node
  - [ ] Interface Document
  - [ ] Interface DOMImplementation
  - [ ] Interface DocumentFragment
  - [ ] Interface DocumentType
  - [ ] Interface Element
  - [ ] Interface Attr
  - [ ] Interface CharacterData
  - [ ] Interface Text
  - [ ] Interface ProcessingInstruction
  - [ ] Interface Comment
- [ ] Ranges
  - [ ] Introduction to DOM Ranges
  - [ ] Interface Range
- [ ] Traversal
  - [ ] Interface NodeIterator
  - [ ] Interface TreeWalker
  - [ ] Interface NodeFilter
- [ ] Sets
  - [ ] Interface DOMTokenList
  - [ ] Interface DOMSettableTokenList
- [ ] Exceptions and Errors
  - [ ] Exceptions
  - [ ] Interface DOMError
  - [ ] Error names
- [ ] Server-Sent Events
  - [ ] The EventSource interface
  - [ ] Processing model
  - [ ] Parsing an event stream
  - [ ] Interpreting an event stream
  - [ ] Connectionless push and other features
  - [ ] Garbage collection
- [ ] Element Traversal
  - [ ] ElementTraversal interface
    - [ ] firstElementChild
    - [ ] lastElementChild
    - [ ] previousElementSibling
    - [ ] nextElementSibling
    - [ ] childElementCount
- [ ] Load and Save
  - [ ] Overview
  - [ ] Basic Types
    - [ ] The LSInputStream Type
    - [ ] The LSOutputStream Type
    - [ ] The LSReader Type
    - [ ] The LSWriter Type
  - [ ] Fundamental Interfaces
    - [ ] LSException
    - [ ] LSExceptionCode
    - [ ] DOMImplementationLS
    - [ ] LSParser
    - [ ] LSInput
    - [ ] LSResourceResolver
    - [ ] LSParserFilter
    - [ ] LSProgressEvent
    - [ ] LSLoadEvent
    - [ ] LSSerializer
    - [ ] LSOutput
    - [ ] LSSerializerFilter
- [ ] Validation
  - [ ] Overview
  - [ ] Exceptions
    - [ ] ExceptionVAL
    - [ ] ExceptionVALCode
  - [ ] Document Editing Interfaces
    - [ ] DocumentEditVAL
    - [ ] NodeEditVAL
    - [ ] ElementEditVAL
    - [ ] CharacterDataEditVAL
- [ ] HTML
  - [ ] Introduction
  - [ ] HTML Application of Core DOM
    - [ ] Naming Conventions
  - [ ] XHTML and the HTML DOM
  - [ ] Miscellaneous Object Definitions
    - [ ] HTMLCollection
    - [ ] HTMLOptionsCollection
  - [ ] HTMLDocument
  - [ ] HTML Elements
  - [ ] Property Attributes
  - [ ] Naming Exceptions
  - [ ] Exposing Element Type Names (tagName, (nodeName))
  - [ ] The HTMLElement interface
  - [ ] Object definitions
    - [ ] HTMLHtmlElement
    - [ ] HTMLHeadElement
    - [ ] HTMLLinkElement
    - [ ] HTMLTitleElement
    - [ ] HTMLMetaElement
    - [ ] HTMLBaseElement
    - [ ] HTMLIsIndexElement
    - [ ] HTMLStyleElement
    - [ ] HTMLBodyElement
    - [ ] HTMLFormElement
    - [ ] HTMLSelectElement
    - [ ] HTMLOptGroupElement
    - [ ] HTMLOptionElement
    - [ ] HTMLInputElement
    - [ ] HTMLTextAreaElement
    - [ ] HTMLButtonElement
    - [ ] HTMLLabelElement
    - [ ] HTMLFieldSetElement
    - [ ] HTMLLegendElement
    - [ ] HTMLUListElement
    - [ ] HTMLOListElement
    - [ ] HTMLDListElement
    - [ ] HTMLDirectoryElement
    - [ ] HTMLMenuElement
    - [ ] HTMLLIElement
    - [ ] HTMLDivElement
    - [ ] HTMLParagraphElement
    - [ ] HTMLHeadingElement
    - [ ] HTMLQuoteElement
    - [ ] HTMLPreElement
    - [ ] HTMLBRElement
    - [ ] HTMLBaseFontElement
    - [ ] HTMLFontElement
    - [ ] HTMLHRElement
    - [ ] HTMLModElement
    - [ ] HTMLAnchorElement
    - [ ] HTMLImageElement
    - [ ] HTMLObjectElement
    - [ ] HTMLParamElement
    - [ ] HTMLAppletElement
    - [ ] HTMLMapElement
    - [ ] HTMLAreaElement
    - [ ] HTMLScriptElement
    - [ ] HTMLTableElement
    - [ ] HTMLTableCaptionElement
    - [ ] HTMLTableColElement
    - [ ] HTMLTableSectionElement
    - [ ] HTMLTableRowElement
    - [ ] HTMLTableCellElement
    - [ ] HTMLFrameSetElement
    - [ ] HTMLFrameElement
    - [ ] HTMLIFrameElement
- [ ] CSS
  - [ ] Introduction
  - [ ] Style Sheet Interfaces
    - [ ] StyleSheet
    - [ ] StyleSheetList
    - [ ] MediaList
  - [ ] Document Extensions
    - [ ] LinkStyle
    - [ ] DocumentStyle
  - [ ] Association between a style sheet and a document

Links:

- [W3C DOM4. W3C Recommendation 19 November 2015](https://www.w3.org/TR/2015/REC-dom-20151119) (official)
- [Server-Sent Events. W3C Recommendation 03 February 2015](https://www.w3.org/TR/2015/REC-eventsource-20150203) (official)
- [Element Traversal Specification. W3C Recommendation 22 December 2008](https://www.w3.org/TR/2008/REC-ElementTraversal-20081222) (official)
- [Document Object Model (DOM) Level 3 Load and Save Specification. Version 1.0. W3C Recommendation 07 April 2004](https://www.w3.org/TR/2004/REC-DOM-Level-3-LS-20040407) (official)
- [Document Object Model (DOM) Level 3 Core Specification. Version 1.0. W3C Recommendation 07 April 2004](https://www.w3.org/TR/2004/REC-DOM-Level-3-Core-20040407) (official)
- [Document Object Model (DOM) Level 3 Validation Specification. Version 1.0. W3C Recommendation 27 January 2004](https://www.w3.org/TR/2004/REC-DOM-Level-3-Val-20040127) (official)
- [Document Object Model (DOM) Level 2 HTML Specification. Version 1.0. W3C Recommendation 09 January 2003](https://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) (official)
- [Document Object Model (DOM) Level 2 Core Specification. Version 1.0. W3C Recommendation 13 November 2000](https://www.w3.org/TR/2000/REC-DOM-Level-2-Core-20001113) (official)
- [Document Object Model (DOM) Level 2 Events Specification. Version 1.0. W3C Recommendation 13 November 2000](https://www.w3.org/TR/2000/REC-DOM-Level-2-Events-20001113) (official)
- [Document Object Model (DOM) Level 2 Style Specification. Version 1.0. W3C Recommendation 13 November 2000](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113) (official)
- [Document Object Model (DOM) Level 2 Traversal and Range Specification. Version 1.0. W3C Recommendation 13 November 2000](https://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) (official)
- [Document Object Model (DOM) Level 2 Views Specification. Version 1.0. W3C Recommendation 13 November 2000](https://www.w3.org/TR/2000/REC-DOM-Level-2-Views-20001113) (official)
- [Document Object Model (DOM) | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

## jQuery

## React

## Redux

## Node.js

## Package Managers

## Web Server

## Express

## Scaffolding

## Task Runners

## Bundlers

## Testing

## Databases

## Clouds

## Continuous Integration

## Virtualization
