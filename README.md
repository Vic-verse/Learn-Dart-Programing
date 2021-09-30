# Learn-Dart-Programing

Dart is a programming language designed for client development, such as for the web and mobile apps. It is developed by Google and can also be used to build server and desktop applications.

Dart is an object-oriented, class-based, garbage-collected language with C-style syntax. Dart can compile to either native code or JavaScript. It supports interfaces, mixins, abstract classes, reified generics, and type inference.

Uses :
Web
To run in mainstream web browsers, Dart relies on a source-to-source compiler to JavaScript. According to the project site, Dart was "designed to be easy to write development tools for, well-suited to modern app development, and capable of high-performance implementations. When running Dart code in a web browser the code is precompiled into JavaScript using the dart2js compiler. Compiled as JavaScript, Dart code is compatible with all major browsers with no need for browsers to adopt Dart. Through optimizing the compiled JavaScript output to avoid expensive checks and operations, code written in Dart can, in some cases, run faster than equivalent code hand-written using JavaScript idioms.
Stand-alone
The Dart software development kit (SDK) ships with a stand-alone Dart VM, allowing Dart code to run in a command-line interface environment. As the language tools included in the Dart SDK are written mostly in Dart, the stand-alone Dart VM is a critical part of the SDK. These tools include the dart2js compiler and a package manager called pub. Dart ships with a complete standard library allowing users to write fully working system apps, such as custom web servers.

Ahead-of-time compiled :
Dart code can be AOT-compiled into machine code (native instruction sets). Apps built with Flutter, a mobile app SDK built with Dart, are deployed to app stores as AOT-compiled Dart code.

Native :
Dart 2.6 with dart2native compiler to compile to self-contained, native executables code. Before Dart 2.6, this feature only exposed this capability on iOS and Android mobile devices via Flutter.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#DartPad : 
The Dart team created DartPad at the start of 2015, to provide an easier way to start using Dart. It is a fully online editor from which users can experiment with Dart application programming interfaces (APIs), and run Dart code. It provides syntax highlighting, code analysis, code completion, documentation, and HTML and CSS editing.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Follow these steps to start using the Dart SDK to develop command-line and server apps. First you’ll play with the Dart language in your browser, no download required. Then you’ll install the Dart SDK, write a small program, and run that program using the Dart VM. Finally, you’ll use an AOT (ahead of time) compiler to compile your finished program to native machine code, which you’ll execute using the Dart runtime.

1. Play with Dart code in DartPad
With DartPad you can experiment with the Dart language and APIs, no download necessary.

For example, here’s an embedded DartPad that lets you play with the code for a small Hello World program. Click Run to run the app; output appears in the console view. Try editing the source code — perhaps you’d like to change the greeting to use another language.


2. Install Dart
Once you’re ready to move beyond DartPad and develop real apps, you need an SDK. You can either download the Dart SDK directly (as described below) or download the Flutter SDK, which (as of Flutter 1.21) includes the full Dart SDK.

For Window :  C:\> choco install dart-sdk
 
