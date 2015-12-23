## Capability: Deployment 
Deployment is the process of releasing new features to the users, which should quick, simple and bullet-proof.

```
"Releasing software is too often an art;
it should be an engineering discipline."

"There should be be two tasks for a human being to perform to deploy
software into a development, test, or production environment:
to pick the version and environment and to push the 'deploy' button"

-- David Farley


Done means "released". This implies ownership of a project right up
until it’s in the hands of the user, and working properly.
There’s none of this "I’ve checked in my code so it’s done as far as I’m concerned"

-- James Betteley

```

### Level 1
 - Code, dependencies and configurations are manually copied between environments
 - There isn't any certainty about weather or not the deployment succeeded, typically users inform you that something has broken
 - Pushing to production goes directly from the developer's machine to production

### Level 2
 - There are environments specifically for testing deployments, and the product manually passes through each environment's tests before being deployed
 - 

### Level 3
 - Deployments are automated, and don't require any intervention from the devops team, for any component of the deployment ( configuration, data, dependencies, code, etc..)
 - Teams have absolute certainty that deployments have been successful, leading to more rapid delivery of features to users
 - Deployments are near-instantaneous, and happen without any disruption to the users
 - Individual features are atomically deployable and don't impact / aren't impacted by the in-progress development of other features
 - Individual features can be pulled from production near-instantaneously
 - Visualization or configuration management tools, such as docker chef or puppet, are used to ensure absolute consistency between all environments across all developers, eliminating any systemic issues due to environmental configuration






[Back](https://github.com/colugo/cautious-turtle)