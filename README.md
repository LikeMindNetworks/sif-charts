# sif-charts
helm charts for sif clusters

## Drone

### resources
- `values.yaml` On Kubernetes
  - change `drone.admin` to the same username as a github user (assuming github integration)
  - resource on alternative dbs:
    - http://readme.drone.io/admin/database-engines/
- Drone Cli
  - http://docs.drone.io/database-settings/
  - connect to remote set the following env vars:
    - DRONE_SERVER
    - DRONE_TOKEN: this is from the drone ui
- How To publish docker images to private repository
  - http://plugins.drone.io/drone-plugins/drone-docker/
  - Secrets: http://docs.drone.io/manage-secrets/
  - Use plugins/ecr image to push to ECR
  - http://plugins.drone.io/ for other plugin images


- Github integration
  - required to register an oauth app with github
  - http://docs.drone.io/install-for-github/
