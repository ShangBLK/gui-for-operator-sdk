# gui-for-operator-sdk

The Operator SDK provides the tools to build, test, and package Operators. Initially, the SDK facilitates the marriage of an application’s business logic (for example, how to scale, upgrade, or backup) with the Kubernetes API to execute those operations. Over time, the SDK can allow engineers to make applications smarter and have the user experience of cloud services. Leading practices and code patterns that are shared across Operators are included in the SDK to help prevent reinventing the wheel.

The Operator SDK is a framework that uses the controller-runtime library to make writing operators easier by providing:

1. High level APIs and abstractions to write the operational logic more intuitively
2. Tools for scaffolding and code generation to bootstrap a new project fast
3. Extensions to cover common Operator use cases

Build your own operator: https://sdk.operatorframework.io/build/


The goal of this project is to create a Dynamic GUI based on an Ansible CRD

Further info: https://cloud.redhat.com/blog/openshift-4-2-declarative-dynamic-ui-for-your-operator
