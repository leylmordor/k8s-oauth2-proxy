## Introduction

This repository contains YAML manifests for deploying and configuring the Oauth2 Proxy.

## Getting Started

To get started with the K8s Oauth2 Proxy, follow the steps below:

1. Clone this repository:

   ```shell
   git clone https://github.com/leylmordor/k8s-oauth2-proxy.git
   ```

2. Navigate to the cloned repository:

   ```shell
   cd k8s-oauth2-proxy
   ```

3. Customize the configuration:
   Open the `config.yaml` file and update the OAuth2 provider settings according to your requirements.

4. Deploy the K8s Oauth2 Proxy:

   ```shell
   kubectl apply -f oauth2-proxy.yaml
   ```

5. Verify the deployment:
   ```shell
   kubectl get pods
   ```

## Documentation

1. Read my blog post on implementing an NGINX controller with Google Kubernetes Engine [here](https://medium.com/@muleyl/implement-nginx-controller-with-google-kubernetes-engine-1d10d28ca5e).
2. For detailed information on using and configuring the OAuth2 Proxy, please refer to the [official documentation](https://oauth2-proxy.github.io/oauth2-proxy/).
