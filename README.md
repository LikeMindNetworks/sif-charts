# sif-charts
helm charts for sif clusters

## Drone

### resources
- `values.yaml` On Kubernetes
  - change `drone.admin` to the same username as a github user (assuming github integration)
  - resource on alternative dbs:
    - http://readme.drone.io/admin/database-engines/
- Drone Cli
  - http://docs.drone.io/cli-installation/
  - connect to remote set the following env vars:
    - DRONE_SERVER
    - DRONE_TOKEN: this is from the drone ui
- How To publish docker images to private repository
  - http://readme.drone.io/questions/how-to-build-publish-docker-images/
  - http://readme.drone.io/0.5/download-private-docker-images-secrets/
  - don't forget to sign to .drone.yml file
