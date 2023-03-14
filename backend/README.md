# Setup

## Installation

Follow setup instructions from [here](https://docs.medusajs.com/quickstart/quick-start)

```bash
medusa new medusa --seed
```

Then run in the root directory:

```bash
sudo docker-compose -f docker-compose.dev.yml up --build --force-recreate
```