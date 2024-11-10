# webhook

Inspired by [rancher webhook](https://github.com/rancher/webhook) and [cloudweav webhook](https://github.com/cloudweav/cloudweav/tree/master/pkg/webhook), it's a framework for developing a Kubernetes webhook easily.
Developers need to only implement interface and register it to the webhook server. It supports validator, mutator and CRD conversion webhook.

Go to [cloudweav/webhook-sample](https://github.com/cloudweav/webhook-sample) to look a simple example.
