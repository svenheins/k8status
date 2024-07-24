# k8status

flask api with some metrics

## prerequisites

- envsubst: apt install gettext

## launch

Run the following scripts:

1. 01_podman_build_push.sh to build and push the image
2. 02_deploy_with_env.sh to kubectl apply -f the deployment.yaml with additional env variables
3. 03_ingress_with_env.sh to publish the service under the DEPLOY_URL
