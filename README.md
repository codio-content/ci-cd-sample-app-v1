# ci-cd-sample-app-v1

# Release build

```parcel build src/index.html```

# Development build

```parcel src/index.html```

# Quality check

```eslint src/*.js```

# Run unit tests

```jest```

# Deployment

```parcel build src/index.html && git subtree push --prefix dist origin gh-pages```
