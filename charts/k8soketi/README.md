k8soketi Server Chart
===================

Containerize & Orchestrate your k8soketi application with this simple Helm chart.

## 🤝 Supporting

**If you are using one or more Renoki Co. open-source packages in your production apps, in presentation demos, hobby projects, school projects or so, sponsor our work with [Github Sponsors](https://github.com/sponsors/rennokki). 📦**

## 🛑 Requirements

- Kubernetes v1.19+

## 🚀 Installation

Install Helm chart repository:

```bash
$ helm repo add k8soketi https://helm.soketi.app
$ helm repo update
```

Install the k8soketi chart:

```bash
$ helm upgrade k8soketi \
    --install \
    --version=1.0.0 \
    soketi/k8soketi
```

Check `values.yaml` for additional available customizations.

## 🐛 Testing

Coming soon.

## 🤝 Contributing

Please see [CONTRIBUTING](../../CONTRIBUTING.md) for details.

## 🔒  Security

If you discover any security related issues, please email alex@renoki.org instead of using the issue tracker.

## 🎉 Credits

- [Alex Renoki](https://github.com/rennokki)
- [All Contributors](../../../../contributors)
