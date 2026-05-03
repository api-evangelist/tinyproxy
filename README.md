# Tinyproxy

Tinyproxy is a lightweight, open-source HTTP/HTTPS proxy daemon designed for POSIX operating systems. It is ideal for use cases in embedded deployments, small networks, and environments where a full-featured HTTP proxy is required with minimal system resource usage. Configuration is file-based with an internal statistics monitoring page.

## APIs

### Tinyproxy

Tinyproxy is a lightweight HTTP/HTTPS proxy daemon for POSIX operating systems with minimal system resource requirements. Provides forward proxying, HTTPS CONNECT tunneling, domain filtering, access control, upstream proxy chaining, transparent proxying, and an internal statistics monitoring page.

- **Documentation:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **GitHub:** [https://github.com/tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy)

## Features

- HTTP and HTTPS proxy support
- CONNECT tunneling for HTTPS
- Domain and URL filtering
- Access control lists
- Upstream proxy chaining
- Transparent proxy mode
- Internal statistics monitoring page
- Privacy header filtering
- Logging with configurable verbosity
- Small memory footprint (~2MB with glibc)

## Use Cases

- Embedded systems proxy
- Small network HTTP proxy
- Content filtering gateway
- Development and testing proxy
- Container sidecar proxy
- IoT device internet access control

## Artifacts

| Type | File |
|---|---|
| JSON Schema | [tinyproxy-config-schema.json](json-schema/tinyproxy-config-schema.json) |
| JSON Structure | [tinyproxy-config-structure.json](json-structure/tinyproxy-config-structure.json) |
| JSON-LD Context | [tinyproxy-context.jsonld](json-ld/tinyproxy-context.jsonld) |
| Vocabulary | [tinyproxy-vocabulary.yml](vocabulary/tinyproxy-vocabulary.yml) |

## Examples

- [Configuration Example](examples/tinyproxy-config-example.json)

## Solutions

- Network access control
- Internet traffic filtering
- Embedded proxy deployments
- Development proxy environments

## Links

- **Website:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **Documentation:** [https://tinyproxy.github.io/](https://tinyproxy.github.io/)
- **GitHub Organization:** [https://github.com/tinyproxy](https://github.com/tinyproxy)
