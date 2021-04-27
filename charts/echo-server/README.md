Echo Server Chart
=================

Containerize & Orchestrate your Echo Server application with this simple Helm chart.

## 🤝 Supporting

Renoki Co. and Soketi on GitHub aims on bringing a lot of open source projects and helpful projects to the world. Developing and maintaining projects everyday is a harsh work and tho, we love it.

If you are using your application in your day-to-day job, on presentation demos, hobby projects or even school projects, spread some kind words about our work or sponsor our work. Kind words will touch our chakras and vibe, while the sponsorships will keep the open source projects alive.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R42U8CL)

## 🚀 Installation

Install Helm chart repository:

```bash
$ helm repo add soketi https://helm.soketi.app
$ helm repo update
```

Install the Echo Server chart:

```bash
$ helm upgrade soketi \
    --install \
    --version=0.5.0 \
    soketi/echo-server
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
