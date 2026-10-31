# RodaBee organization profile

Organization-level presentation and the current repository map for RodaBee.
Default branch: `main`. This repository is public and is not a product runtime.

The organization landing page is [profile/README.md](profile/README.md).
Brand assets live in [assets/](assets/). Do not place credentials, customer data,
private environment configuration or internal lab endpoints in the public profile.

## Current engineering layout

- [`web`](https://github.com/rodabee/web): unified SvelteKit storefront/backoffice.
- [`api`](https://github.com/rodabee/api): Go GraphQL backend and PostgreSQL.
- [`infra`](https://github.com/rodabee/infra): alternative GCP/AWS infrastructure.
- [`db-migration`](https://github.com/rodabee/db-migration),
  [`cutover`](https://github.com/rodabee/cutover) and
  [`migration-plan`](https://github.com/rodabee/migration-plan): migration tools,
  operational handbook and architecture/history.

The previous `buyers-web`, `backoffice`, `rodabee-backend` and `faas` repositories
are archived references. Archive status describes source ownership, not whether
an old deployed cloud service has been shut down.
