# codeproject-ai

- Currently deployed as a docker compose daemon. Not a stack.
- This could/should be redeployed as a stack when CUDA GPUs can reliably be used in that configuration.

## Deployment
### Docker Compose

```bash
docker compose up -d
```

### Docker Stack (Work In Progress)

```bash
docker stack deploy -c stack.yaml codeproject-ai
```

