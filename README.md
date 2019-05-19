# OpenReq
This project was created out of frustration with the lack of open source tooling for designing/planning software that more or less conforms to the standards described in DO-178B. For those that don't know, this is the Aviation industry's document that describes how safety-critical software should be developed. Currently this project is sitting more in the idea stage than anything else, but I would like to have this tool for my own project's planning and design phases.

## Current Scope:
At present, the idea is to couple a set of requirements with each feature or module that is built. The feature will be written in some source code and header file and tagged with unique requirement numbers. The requirements will be specified in another document and filled with various meta data and tracing. This effectively implements tracing and requirement generation for low-level requirements (LLR).

## Long Term Scope:
Ideally, this will transform into an application/manager that can organize the full set of documents that are produced from a project that adheres to DO-178B.
