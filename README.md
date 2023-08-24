# gui-for-operator-sdk

The Operator SDK provides the tools to build, test, and package Operators. Initially, the SDK facilitates the marriage of an application’s business logic (for example, how to scale, upgrade, or backup) with the Kubernetes API to execute those operations. Over time, the SDK can allow engineers to make applications smarter and have the user experience of cloud services. Leading practices and code patterns that are shared across Operators are included in the SDK to help prevent reinventing the wheel.

The Operator SDK is a framework that uses the controller-runtime library to make writing operators easier by providing:

1. High level APIs and abstractions to write the operational logic more intuitively
2. Tools for scaffolding and code generation to bootstrap a new project fast
3. Extensions to cover common Operator use cases

Build your own operator: https://sdk.operatorframework.io/build/


The goal of this project is to create a Dynamic GUI based on an Ansible CRD

Further info: https://cloud.redhat.com/blog/openshift-4-2-declarative-dynamic-ui-for-your-operator

# Autocreate APIs by Using Your Connected Apps Credentials

Link: https://docs.mulesoft.com/service-mesh/1.2/create-an-api-configure-service-mesh-CRD

# K8s Ingress 

Link: https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-ingress-guide-nginx-example.html

From the this command's output, 

kubectl api-resources --verbs=list --namespaced -o name | xargs -n 1 kubectl get --ignore-not-found --show-kind -n <namespace>

we can see that ingresses, endpoints, service accounts, persistent volume claims, and config maps are amongst the returned resources. This is unlike the restrictive list from kubectl get all.


# links
https://docs.mulesoft.com/service-mesh/1.2/create-an-api-configure-service-mesh-CRD#create-api-autocreate

https://www.hostinger.com/tutorials/tmux-beginners-guide-and-cheat-sheet/#:~:text=tmux%20is%20a%20terminal%20multiplexer,output%20at%20the%20same%20time.

https://docs.mulesoft.com/service-mesh/1.2/download-and-install-service-mesh

https://mastering-shiny.org/action-dynamic.html

https://swagger.io/docs/specification/about/

https://cloud.redhat.com/blog/openshift-4-2-declarative-dynamic-ui-for-your-operator
