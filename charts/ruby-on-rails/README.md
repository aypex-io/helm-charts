# Ruby on Rails Helm Chart

A helm chart for running a ruby-on-rails applications.

## Kubernetes Resources

This chart runs creates a number of Kubernetes resources:

**Deployment**

This runs your application and controls the rollout strategy on deployment.

**Horizontal Pod Autoscaler**

Controls horizontal scaling of your application based on resource requirements.

**Service & Ingress**

Exposes application over network and configures load balancer traffic ingress.

**secret**

All environment variables are mounted as a secret

**Service Account**

A Kubernetes service account for your application.

**Job**

A job that can be run alone for migrations or other rake tasks.

**Cron Job**

A job that can be run alone for migrations or other rake tasks.
