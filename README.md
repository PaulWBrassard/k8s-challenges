# K8s Challenges
This is a collection of challenges regarding Kubernetes

# Prerequisites
 * Access to a Kubernetes cluster; [katacoda](https://www.katacoda.com/courses/kubernetes/playground) could be used without any prior setup.

# Challenges

## nginx-1
  <b>Challenge description:</b>
  This is a new deployment of nginx, ensure the pod starts running.

  <i>Have the testee run `curl -o nginx.yaml https://raw.githubusercontent.com/PaulWBrassard/k8s-challenges/master/challenges/nginx-1.yaml` to download the manifest, then instruct them to deploy it.</i>

## nginx-2
  <b>Challenge description:</b>
  Another Devops Engineer has modified our previous nginx deployment, they say the changes were necessary to land on the correct nodes. Let this version of the manifest take the place of the previous one. Ensure the pod starts running.

  <i>Have the testee run `curl -o nginx.yaml https://raw.githubusercontent.com/PaulWBrassard/k8s-challenges/master/challenges/nginx-2.yaml` to download the manifest, then instruct them to deploy it.</i>

## nginx-3
  <b>Challenge description:</b>
  For reporting reasons, pods are now required to be labeled with the application version number. The manifest has been updated by an application developer and given to you. Let it take the place of the previous deployment of nginx. Ensure the pod starts running.

  <i>Have the testee run `curl -o nginx.yaml https://raw.githubusercontent.com/PaulWBrassard/k8s-challenges/master/challenges/nginx-3.yaml` to download the manifest, then instruct them to deploy it.</i>
