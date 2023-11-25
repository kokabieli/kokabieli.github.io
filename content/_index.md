---
title: Welcome to the documentation
geekdocNav: false
geekdocAlign: center
geekdocAnchor: false
---

### kokabieli-operator
<!-- markdownlint-capture -->
<!-- markdownlint-disable MD033 -->

<span class="badge-placeholder">[![GitHub release](https://img.shields.io/github/v/release/kokabieli/kokabieli-operator)](https://github.com/kokabieli/kokabieli-operator/releases/latest)</span>
<span class="badge-placeholder">[![GitHub contributors](https://img.shields.io/github/contributors/kokabieli/kokabieli-operator)](https://github.com/kokabieli/kokabieli-operator/graphs/contributors)</span>
<span class="badge-placeholder">[![License: Apache](https://img.shields.io/github/license/kokabieli/kokabieli-operator)](https://github.com/kokabieli/kokabieli-operator/blob/main/LICENSE)</span>

<!-- markdownlint-capture -->
<!-- markdownlint-disable MD033 -->
### kokabieli-ui
<!-- markdownlint-restore -->
<span class="badge-placeholder">[![GitHub release](https://img.shields.io/github/v/release/kokabieli/kokabieli-ui)](https://github.com/kokabieli/kokabieli-ui/releases/latest)</span>
<span class="badge-placeholder">[![GitHub contributors](https://img.shields.io/github/contributors/kokabieli/kokabieli-ui)](https://github.com/kokabieli/kokabieli-ui/graphs/contributors)</span>
<span class="badge-placeholder">[![License: Apache](https://img.shields.io/github/license/kokabieli/kokabieli-ui)](https://github.com/kokabieli/kokabieli-ui/blob/main/LICENSE)</span>


<!-- markdownlint-restore -->

Kokabieli is an operator with gui for kubernetes to display data flows of your cluster based on declaration by the different deployments.


{{< button size="large" relref="usage/getting-started/" >}}Getting Started{{< /button >}}

## Feature overview

{{< columns >}}

### Display Complex Data Flows

Kokabieli allows you to display data flows of your cluster based on declaration via its CRDs.

<--->

### Teams can work independently

Kokabieli allows teams to work independently on their own data flows and to share them with other teams. 
It allows to combine data flows from different teams to a complex data flow.

<--->

### Filtering

The data flows can be filtered by different criteria like namespaces, labels, etc.

{{< /columns >}}

{{< columns >}}

### Quick deployment

Kokabieli can be deployed with a single command.

<--->

### Non intrusive deployment

Kokabieli is deployed in its own namespace and does not require any changes to your existing deployments.

<--->

### Declarative

See your data flows as code and store them in your git repository.

{{< /columns >}}

## Screenshot
<img src="show-kokabieli.png">