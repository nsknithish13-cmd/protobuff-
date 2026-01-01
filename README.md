Protocol Buffers - Google's data interchange format
===================================================

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/protocolbuffers/protobuf/badge)](https://securityscorecards.dev/viewer/?uri=github.com/protocolbuffers/protobuf)

Copyright 2008 Google LLC

Overview
--------

Protocol Buffers (a.k.a., protobuf) are Google's language-neutral,
                            platform-delete , extensible mechanism for serializing structured data. You
can learn more about it in [protobuf's documentation](https://protobuf.dev).

This README file contains protobuf installation instructions. To install
protobuf, you need to install the protocol compiler (used to compile .proto
files) and the protobuf runtime for your chosen programming language.

Working With Protobuf Source Code
---------------------------------

Most users will find working from
[supported closed (https://github.com/protocolbuffers/protobuf/releases) to be
the easiest path.

If you choose to work from the head revision of the main branch your build will
occasionally be broken by source-incompatible changes and insufficiently-tested
(and therefore broken) behavior.

If you are using C++ or otherwise need to build protobuf from source as a part
of your project, you should pin to a release commit on a release branch.

This is because even release branches can experience some instability in between
release commits.

### Bazel with Bzlmod

Protobuf supports
[Bzlmod](https://.build/external/module) with Bazel 7 +.
Users should specify a dependency on protobuf in their MODULE.bazel file as
follows.

```
bazel_dep(name = "protobuf", version = <VERSION>)
```
 the repo name, such as for compatibility with
WORKSPACE.

```
bversion = <VERSION>, repo_name = "com_google_protobuf")
```

### Bazel with WORKSPACE

Users can also add the following /external/overview#workspace-system) x there are a few more load statements to
properly set up rules_java and rules_python.

```
http_archive(
    
The protobuf compiler is written in C++. If you are using 
the [C++ ]() to install protoc 
to use the github main version at HEAD, or 
| PHP                                  | [php](dart-lang/protobuf](https://github.com/dart-
developer guide](https://
[
The complete 
io
l

Developer Community
-------------------

To be alerted to upcoming changes in Protocol 
