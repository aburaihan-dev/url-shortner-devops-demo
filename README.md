# url-shortner-devops-demo

``
Demo 'url-shortner' application Built with NodeJS for DevOps Training.
``

## Training Topics
- [] Jenkins pipeline Build and ...
   1. [] Deploy using docker container image directly to the server.
   2. [] Push to docker/gitlab registry.
   3. [] Deploy using 'docker-compose.yaml' file.
   4. [] Test automation and email report.

- [] Monitoring Setup
    1. [] Metrics export to prometheus and visualize with grafana.
    2. [] Alertmanager for health notification.
    2. [] Service to Service communication logging and visualization.
    3. [] ELK-stack log monitoring

- [] Kubernetes Setup ...
    1. [] k8s deployment
    2. [] Services
    3. [] Ingress
    4. [] Autoscaling with keda and prometheus.
    5. [] CI\CD with ArgoCD.


## Application Stack
- Backend:  NestJS
- Frontend: NextJS
- Database: PostgreSQL
- Cache:    Redis


### Design

### Draft diagram of **url-shortner** [^1].
![Basic Diagram](https://res.cloudinary.com/practicaldev/image/fetch/s--7KrJoFJK--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/karanpratapsingh/portfolio/master/public/static/courses/system-design/chapter-V/url-shortener/url-shortener-basic-design.png "Basic Diagram")

### High-Availability diagram draft of **url-shortner** [^1]
![High-Availability Diagram](https://res.cloudinary.com/practicaldev/image/fetch/s--NG7ZUoaM--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://raw.githubusercontent.com/karanpratapsingh/portfolio/master/public/static/courses/system-design/chapter-V/url-shortener/url-shortener-advanced-design.png "High-Availability Diagram")

## Reference
- [^1] [System Design: URL Shortener](https://dev.to/karanpratapsingh/system-design-url-shortener-10i5)