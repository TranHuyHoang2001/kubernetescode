# kubernetescode
# kubernetesmanifest

https://github.com/TranHuyHoang2001/kubernetesmanifest

# WorkFlow:

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/e14571c7-b7b2-4798-9bf0-6d61f3d30f42)

- Setup Jenskin server on GCP (Google Cloud Platform) VM instances.
- Unlock Jenskin.
- Config Credentials.
- Add Docker plugin.

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/a953880d-7a84-42fc-904f-e1d12a5d3b01)

- Add 2 pipeline, link with 2 repo github and build now.

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/5ac5b624-e0fd-4a3f-bbc2-580b0b11b192)

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/47d2f531-9745-44d8-921c-cc708564f649)

- Docker image (in dockerhub).

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/c7f26fd8-69d7-4348-8b3f-05a52a0f57f9)

- Setup Kubernetes (i choose Minikube on local).
- And forward port.

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/b41a644c-0dce-430e-9162-5f70c8450b55)

- In localhost:8080, login ArgoCD use admin and password generated.

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/b755843e-861b-48fd-8fc9-522e61683af7)

- Create new app.

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/4a99ba49-9eaf-4ffc-b2b6-9ddf096796b1)

- Check pods is running, get svc

![image](https://github.com/TranHuyHoang2001/kubernetescode/assets/93071557/8a237007-8bdc-4f7c-8bd7-3a7c09dc7f92)

- And now you try to change code, Jenskin will trigger from Github, build Docker image, update image in deployment.yaml. ArgoCD will 
deploy deployments.yaml to Kubernetes.
