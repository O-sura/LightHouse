# Lighthouse
> Stop writing Gateway API manifests. Define how your application should be exposed, and let the controller handle the rest.

Lighthouse is a Kubernetes operator that provides a simple, declarative API for exposing applications to the outside world. Instead of manually creating Services, HTTPRoutes, TLS certificates, and other networking resources, developers define a single custom resource describing the desired public endpoint. The controller reconciles the required Kubernetes resources using Gateway API, making application exposure consistent, repeatable, and platform-agnostic.
