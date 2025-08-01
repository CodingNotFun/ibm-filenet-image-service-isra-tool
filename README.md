# ibm-filenet-image-service-isra-tool
leverage ibm filenet image service isra adapter to interact with image service to perform documents creation, extraction ,query and migration to other modern ecm platforms

![system context diagram](1.jpg)

Why develop this utility?

The FileNet Image Services system is a legacy platform that does not provide a web service interface, making it incompatible with modern technologies and integration methods. To address this limitation, IBM developed a JCA (Java Connector Architecture) adapter known as ISRA, which enables communication with Image Services using RPC (Remote Procedure Call).

This utility leverages the ISRA adapter and is designed to run on a separate machine. By using the Java JCA framework, it facilitates interaction with the Image Services system without requiring direct integration into the legacy environment.

With this tool, users can:

- Extract documents from FileNet Image Services
- Create and upload new documents into the system
- Query documents

This approach modernizes access to the legacy system without altering its core architecture, enabling smoother integration into contemporary workflows.
