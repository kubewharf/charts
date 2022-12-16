# Katalyst Helm Charts

Katalyst Helm Charts is for user to deploy katalyst system on their kubernetes cluster by `helm install`.

## Getting Started

We support two options to deploy katalyst system:

### Option.1 Install Katalyst Components All in One

```console
helm install katalyst -n katalyst-system --create-namespace kubewharf/katalyst
```

### Option.2 Install Katalyst Components Standalone

**Install Katalyst-agent**

```console
helm install katalyst-agent -n katalyst-system --create-namespace kubewharf/katalyst-agent
```

**Install Katalyst-controller**

```console
helm install katalyst-controller -n katalyst-system --create-namespace kubewharf/katalyst-controller
```

**Install Katalyst-metric**

```console
helm install katalyst-metric -n katalyst-system --create-namespace kubewharf/katalyst-metric
```

**Install Katalyst-scheduler**

```console
helm install katalyst-scheduler -n katalyst-system --create-namespace kubewharf/katalyst-scheduler
```

**Install Katalyst-webhook**

```console
helm install katalyst-webhook -n katalyst-system --create-namespace kubewharf/katalyst-webhook
```
