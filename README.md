Used versions in the demo:
► helm version: v3.2.1
► prometheus-operator: v0.38.1

In general there are 3 ways to do the setup:
1. Create all the configuration files yourself 👩🏻‍💻
This way is pretty inefficient and it's a lot of effort.
2. Using a Kubernetes Operator 😎
In this option you would go and find an operator for Prometheus and deploy it in the cluster using the configuration files of the operator. It is more efficient.
3. Using Helm chart to deploy the Prometheus Operator 🚀
This is the most efficient way