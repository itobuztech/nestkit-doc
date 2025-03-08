---
title: Data Seed
---
# DB Seed

The DB seed feature provides a way to populate your database with essential test data. This ensures your application runs smoothly from the first startup with minimal required data.

## Overview

Database seeding is a crucial part of application development and testing. Our seed functionality:

- Creates initial admin users
- Populates lookup tables with common values
- Sets up required configuration data
- Provides sample data for development and testing

## Running Seeds

Seeds can be executed using the following command:

```bash
npm run db:seed
```

Or with yarn:

```bash
yarn db:seed
```

## Seed Customization

The seed data is defined in the `src/seeds` directory. You can modify existing seeds or add new ones based on your application requirements.

### Creating Custom Seeds

1. Create a new file in the seeds directory

## Benefits

- Consistent testing environment across development machines
- Quick application setup for new developers
- Reliable data for automated tests
- Smooth application running with minimum required data
