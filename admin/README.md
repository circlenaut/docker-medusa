# Setup

## Installation

Follow setup instructions from [here](https://docs.medusajs.com/admin/quickstart)

```bash
git clone https://github.com/medusajs/admin medusa-admin
cd medusa-admin
yarn install
```

Then run in the root directory:

```bash
sudo docker-compose -f docker-compose.dev.yml up --build --force-recreate
```

Go go localhost:7070 and login with
- admin@medusa-test.com : supersecret

