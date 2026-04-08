# Protos Repository

This repository contains all service-related Protocol Buffer (`.proto`) files.

## Structure

```
protos/
├── user/
│   └── v1/
│       └── user_service.proto
└── README.md
```

## Proto File Conventions

- Each service has its own folder (e.g., `user/`)
- Versioned subfolders (e.g., `v1/`) for API versioning
- `go_package` notation: `github.com/YourGitHubUserName/protos/<service>/<version>;<service_version>`

## Usage

These proto files are automatically compiled into Go code using the generator repository.
The generated files are published to: `github.com/YourGitHubUserName/proto-generated-go`
