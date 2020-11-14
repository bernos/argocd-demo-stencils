# argocd-demo-stencils

This repository contains "stencils" for commonly deployed application types. In our imaginary organisation, this repository would be maintained by a central team responsible for ensuring that we have a set of easy to use stencils that adhere to best practices.

In this example we are using Helm to parameterise configuration options that users will want to alter, such as image names and replica counts, but this could just as easily be implemented with other tools such as Kustomize, jsonnet or kpt.
