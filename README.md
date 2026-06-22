# CI/CD Pipelines 🚀

Reusable CI/CD templates for multiple platforms.

## Supported

- **GitHub Actions**: Build, test, deploy
- **GitLab CI**: Multi-stage pipelines
- **Jenkins**: Declarative pipelines

## Quick Start

```yaml
# .github/workflows/deploy.yml
uses: org/ci-cd-pipelines/.github/workflows/deploy.yml@main
with:
  environment: production
  registry: ghcr.io
```

## License

MIT