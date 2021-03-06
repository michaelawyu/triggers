---
title: "Triggers"
linkTitle: "Triggers"
weight: 3
description: >
  Event Triggers
---

Triggers enables users to map fields from an event payload into resource
templates. Put another way, this allows events to both model and instantiate
themselves as Kubernetes resources. In the case of `tektoncd/pipeline`, this
makes it easy to encapsulate configuration into `PipelineRun`s and
`PipelineResource`s.

![TriggerFlow](https://github.com/tektoncd/triggers/blob/master/images/TriggerFlow.png?raw=true)

## Learn More

See the following links for more on each of the resources involved:

- [`TriggerTemplate`](/docs/triggers/triggertemplates)
- [`TriggerBinding`](/docs/triggers/triggerbindings)
- [`EventListener`](/docs/triggers/eventlisteners)
- [`ClusterTriggerBinding`](/docs/triggers/clustertriggerbindings)

## Getting Started Tasks

- [Create an Ingress on the EventListener Service](https://github.com/tektoncd/triggers/blob/master/docs/create-ingress.yaml)
- [Create a GitHub webhook](https://github.com/tektoncd/triggers/blob/master/docs/create-webhook.yaml)
