# HTTP LOAD BALANCER

Example of a load balancer that randomizes two routes between 4 servers, built following the TDD principles.

## Usage

Build the server image:

```bash
docker build -t server .
```

Spin up the servers based on the compose:

```bash
docker-compose up -d
```

Every test should pass succesfully:

```python
pytest
```