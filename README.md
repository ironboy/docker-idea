# docker-idea
docker-idea

```json
[
  "// strings are names of branches",
  "// a container is created per branch",
  "// (provided it contains a Dockerfile)",
  "",
  "// arrays after strings can contain",
  "// routes to proxy to the container",
  "// and/or a port to publish to the host",
  "",
  "// example:",
  "",
  "dev-proxy",
  [
    3000
  ],
  "dev-frontend",
  [
    "/"
  ],
  "dev-backend",
  [
    "/api",
    "/json",
    4000
  ],
  "sql",
  [
    3306
  ]
]
```