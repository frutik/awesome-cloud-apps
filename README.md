# awesome-cloud-apps

## Cloud native

* [Service mesh: A critical component of the cloud native stack](https://www.cncf.io/blog/2017/04/26/service-mesh-critical-component-cloud-native-stack/)

### The Resilient Architecture Collection (by Adrian Hornsby)

* [Part 1: Embracing failure at scale](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-1-d3b60cd8d2b6)
* [Part 2: Avoiding Cascading Failures](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-2-9b51a7e2f10f)
* [Part 3: Preventing Service Failures with Health Check](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-3-16e8601c488e)

* [The Chaos Engineering Collection](https://adhorn.medium.com/the-chaos-engineering-collection-5e188d6a90e2)

## AWS

### RDS

* [Running out of IOPS in AWS RDS?](https://faun.pub/running-out-of-iops-in-aws-rds-lets-discuss-on-the-work-around-5430f2dd51df)
* [The gp2 burst balance credits for the RDS database instance are low](https://stackoverflow.com/questions/67618980/aws-rds-message-for-gp2)

### Serverless

* [Don’t use Lambda to move data! API Gateway can help](https://levelup.gitconnected.com/dont-use-lambda-to-move-data-api-gateway-can-help-fe899df239e6)
* [Serverless Pitfalls: Issues With Running a Startup on AWS Lambda](https://medium.com/@emaildelivery/serverless-pitfalls-issues-you-may-encounter-running-a-start-up-on-aws-lambda-f242b404f41c)
* [Best Practices for AWS Lambda Container Reuse](https://medium.com/capital-one-tech/best-practices-for-aws-lambda-container-reuse-6ec45c74b67e)
* [How to temporarily disable an AWS Lambda function using AWS CLI without removing the function](https://www.mikulskibartosz.name/temporarily-disable-aws-lambda-using-aws-cli/)

#### Performance, cold start

* [I’m afraid you’re thinking about AWS Lambda cold starts all wrong](https://theburningmonk.com/2018/01/im-afraid-youre-thinking-about-aws-lambda-cold-starts-all-wrong/)
* [Understanding Container Reuse in AWS Lambda](https://aws.amazon.com/blogs/compute/container-reuse-in-lambda/)
* [Predictable start-up times with Provisioned Concurrency](https://aws.amazon.com/blogs/compute/new-for-aws-lambda-predictable-start-up-times-with-provisioned-concurrency/)
* [Provisioned Concurrency: What it is and how to use it with the Serverless Framework](https://www.serverless.com/blog/aws-lambda-provisioned-concurrency)
* [Finding AWS Lambda Cold Start Durations](https://www.petermorlion.com/finding-aws-lambda-cold-start-durations/)

## Kubernetes

### General 

* [10 most common mistakes using kubernetes](https://blog.pipetail.io/posts/2020-05-04-most-common-mistakes-k8s/)
* [10 Anti-Patterns for Kubernetes Deployments](https://betterprogramming.pub/10-antipatterns-for-kubernetes-deployments-e97ce1199f2d)
* [DigitalOcean eBook: Kubernetes for Full-Stack Developers](https://www.digitalocean.com/community/books/digitalocean-ebook-kubernetes-for-full-stack-developers)
* [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
* [Kubernetes Workers Autoscaling based on RabbitMQ queue size](https://itnext.io/kubernetes-workers-autoscaling-based-on-rabbitmq-queue-size-cb0803193cdf)

### Deployment
* [Kubernetes Patterns - Declarative Deployments](https://www.magalix.com/blog/kubernetes-patterns-declarative-deployments)
* [Kubernetes rolling updates, rollbacks and multi-environments](https://itnext.io/kubernetes-rolling-updates-rollbacks-and-multi-environments-4ff9912df5)

### Ingress

* [Kubernetes NGINX Ingress WAF with ModSecurity](https://systemweakness.com/nginx-ingress-waf-with-modsecurity-from-zero-to-hero-fa284cb6f54a)

#### Ratelimiting

* [Rate-limiting for your Kubernetes applications with NGINX ingress](https://medium.com/titansoft-engineering/rate-limiting-for-your-kubernetes-applications-with-nginx-ingress-2e32721f7f57)
* [Rate Limiting with the HAProxy Kubernetes Ingress Controller](https://www.haproxy.com/blog/rate-limiting-with-the-haproxy-kubernetes-ingress-controller/)


### Services 

#### Headless Services

* [Building a headless service in Kubernetes](https://dev.to/eddiehale3/building-a-headless-service-in-kubernetes-3bk8)
* [DOCKER AND KUBERNETES HEADLESS SERVICE AND DISCOVERING PODS](https://www.bogotobogo.com/DevOps/Docker/Docker_Kubernetes_Headless_Service.php)

### Complex apps and environments

* [How to deploy application on Kubernetes with Helm](https://wkrzywiec.medium.com/how-to-deploy-application-on-kubernetes-with-helm-39f545ad33b8)
* [Kubernetes: Merge Multiple YAML Files Into One](https://levelup.gitconnected.com/kubernetes-merge-multiple-yaml-into-one-e8844479a73a)
* [Kubernetes: Change base YAML config for different environments prod/test using Kustomize](https://levelup.gitconnected.com/kubernetes-change-base-yaml-config-for-different-environments-prod-test-6224bfb6cdd6)

### Chaos engineering

* [Open Source solutions for chaos engineering in Kubernetes](https://blog.flant.com/chaos-engineering-in-kubernetes-open-source-tools/)

### Resources understanding

* [Deployments vs StatefulSets vs DaemonSets](https://medium.com/stakater/k8s-deployments-vs-statefulsets-vs-daemonsets-60582f0c62d4)
* [Essential Kubernetes Resources](https://medium.com/better-programming/essential-kubernetes-resources-2ccb250bcf44)
  Deployment, Pod Disruption Budget, Horizontal Pod Autoscaler, NetworkPolicy
* [Understanding resource limits in kubernetes: cpu time](https://medium.com/@betz.mark/understanding-resource-limits-in-kubernetes-cpu-time-9eff74d3161b)
* How we learned to improve Kubernetes CronJobs at Scale. [Part 1](https://eng.lyft.com/improving-kubernetes-cronjobs-at-scale-part-1-cf1479df98d4?gi=4912bee4ede), [Part 2](https://eng.lyft.com/how-we-learned-to-improve-kubernetes-cronjobs-at-scale-part-2-of-2-dad0c973ffca)

### Platforms, Frameworks and Tools

* [EKS vs GKE vs AKS - Evaluating Kubernetes in the Cloud](https://www.stackrox.com/post/2020/10/eks-vs-gke-vs-aks/)
* [Kubeflow 1.0 — Quick Overview](https://medium.com/@bv_subhash/kubeflow-1-0-quick-overview-d515834d3c67)



