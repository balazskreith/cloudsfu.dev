# Kubernetes Native Solution for WebRTC SFU

This repository contains the source code for [STUNner](https://l7mp.io/stunner), a Kubernetes-native solution for WebRTC Selective Forwarding Units (SFU).

## Overview

STUNner provides a Kubernetes-native approach to deploying WebRTC media servers, offering:
- Single load balancer for all media traffic
- Simplified network management
- Enhanced security through controlled exposure
- Easy scaling with Kubernetes
- Native cloud integration

## Key Features

- **Simplified Deployment**: Single IP and port for all media traffic
- **Enhanced Security**: Reduced attack surface and controlled public exposure
- **High Performance**: Optimized media routing with minimal latency
- **Enterprise Ready**: Designed for production deployments

## Quick Links

- [Documentation](https://l7mp.io/stunner/doc)
- [Installation Guide](https://l7mp.io/stunner/doc/installation.html)
- [GitHub Repository](https://github.com/l7mp/stunner)
- [Example Configurations](https://github.com/l7mp/stunner/tree/main/examples)

## Development

This is a static website built with GitHub Pages and Jekyll.

### Local Development

To preview the site locally:

1. Install Ruby and Jekyll
```bash
gem install bundler jekyll
```

2. Clone the repository
```bash
git clone https://github.com/l7mp/stunner.git
cd stunner
```

3. Install dependencies
```bash
bundle install
```

4. Start the local server
```bash
bundle exec jekyll serve
```

5. Visit `http://localhost:4000` in your browser

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

Please ensure your PR description clearly describes the changes you're proposing.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Community

Join our community:
- [GitHub Discussions](https://github.com/l7mp/stunner/discussions)
- [GitHub Issues](https://github.com/l7mp/stunner/issues)
- [Slack Channel](https://l7mp.slack.com)