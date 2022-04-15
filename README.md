```
Roberto Nogueira  
BSd EE, MSd CE
Solution Integrator Experienced - Certified by Ericsson
```
# Tutorial Kubernetes

![tutorial image](images/tutorial.png)

**About**

**Kubernetes Basics**

This tutorial provides a walkthrough of the basics of the **Kubernetes** cluster orchestration system. Each module contains some background information on major **Kubernetes** features and concepts, and includes an interactive online tutorial. These interactive tutorials let you manage a simple cluster and its containerized applications for yourself.

Using the interactive tutorials, you can learn to:

* Deploy a containerized application on a cluster.
* Scale the deployment.
* Update the containerized application with a new software version.
* Debug the containerized application.

The tutorials use [Katacoda](https://www.katacoda.com) to run a virtual terminal in your web browser that runs [Minikube](https://minikube.sigs.k8s.io), a small-scale local deployment of Kubernetes that can run anywhere. There's no need to install any software or configure anything; each interactive tutorial runs directly out of your web browser itself.

[Homepage](https://kubernetes.io/docs/tutorials/kubernetes-basics)

**Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]**

Full Kubernetes Tutorial | Kubernetes Course | Hands-on course with a lot of demos.

[Homepage](https://www.youtube.com/watch?v=X48VuDVv0do)
## Topics

Kubernetes Basics
* [ ] [1. Create a Kubernetes cluster](https://kubernetes.io/docs/tutorials/kubernetes-basics/create-cluster/cluster-intro/)
* [ ] [2. Deploy an app](https://kubernetes.io/docs/tutorials/kubernetes-basics/deploy-app/deploy-intro/)
* [ ] [3. Explore your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/explore/explore-intro/)
* [ ] [4. Expose your app publicly](https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/)
* [ ] [5. Scale up your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/scale/scale-intro/)
* [ ] [6. Update your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/)

Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]
 * [x] [ 0. Course Overview](https://www.youtube.com/watch?v=X48VuDVv0do&t=0s) 

 [1. What is Kubernetes](https://www.youtube.com/watch?v=X48VuDVv0do&t=138s) 
 * [x] What problems does Kubernetes solve? 
 * [x] What features do container orchestration tools offer? 
 
 [2. Main K8s Components](https://www.youtube.com/watch?v=X48VuDVv0do&t=320)
 * [x] Node & Pod 
 * [x] Service & Ingress 
 * [x] ConfigMap & Secret 
 * [x] Volumes 
 * [x] Deployment & StatefulSet 
 
 [3. K8s Architecture](https://www.youtube.com/watch?v=X48VuDVv0do&t=1349s)
 * [x] Worker Nodes 
 * [x] Master Nodes 
 * [x] Api Server 
 * [x] Scheduler 
 * [x] Controller Manager 
 * [x] etcd - the cluster brain 
 
 [4. Minikube and kubectl - Local Setup](https://www.youtube.com/watch?v=X48VuDVv0do&t=2087s) 
 * [ ] What is minikube? 
 * [ ] What is kubectl? 
 * [ ] install minikube and kubectl 
 * [ ] create and start a minikube cluster 

 🔗 Links:
  - Install Minikube (Mac, Linux and Windows): [https://bit.ly/38bLcJy](https://bit.ly/38bLcJy)
  - Install Kubectl: [https://bit.ly/32bSI2Z](https://bit.ly/32bSI2Z)
  - Gitlab: If you are using Mac, you can follow along the commands. I listed them all here: [https://bit.ly/3oZzuHY](https://bit.ly/3oZzuHY)
  
 [5. Main Kubectl Commands - K8s CLI](https://www.youtube.com/watch?v=X48VuDVv0do&t=2692s)
 * [ ] Get status of different components 
 * [ ] create a pod/deployment 
 * [ ] layers of abstraction 
 * [ ] change the pod/deployment 
 * [ ] debugging pods 
 * [ ] delete pod/deployment 
 * [ ] CRUD by applying configuration file 

 🔗 Links: 
 - Git repo link of all the commands: [https://bit.ly/3oZzuHY](https://bit.ly/3oZzuHY)
 
 [6. K8s YAML Configuration File](https://www.youtube.com/watch?v=X48VuDVv0do&t=3723s)
 * [ ] 3 parts of a Kubernetes config file (metadata, specification, status) 
 * [ ] format of configuration file 
 * [ ] blueprint for pods (template) 
 * [ ] connecting services to deployments and pods (label & selector & port) 
 * [ ] demo 

 🔗 Links: 
 - Git repo link: [https://bit.ly/2JBVyIk](https://bit.ly/2JBVyIk) 

 [7. Demo Project](https://www.youtube.com/watch?v=X48VuDVv0do&t=4576s)
 * [ ] Deploying MongoDB and Mongo Express 
 * [ ] MongoDB Pod ► Secret ► MongoDB Internal Service 
 * [ ] Deployment Service and Config Map 
 * [ ] Mongo Express External Service 

 🔗 Links: 
 - Git repo link: [https://bit.ly/3jY6lJp](https://bit.ly/3jY6lJp)
 
 [8. Organizing your components with K8s Namespaces](https://www.youtube.com/watch?v=X48VuDVv0do&t=6376s)
 * [ ] What is a Namespace? 
 * [ ] 4 Default Namespaces 
 * [ ] Create a Namespace 
 * [ ] Why to use Namespaces? 4 Use Cases 
 * [ ] Characteristics of Namespaces 
 * [ ] Create Components in Namespaces 
 * [ ] Change Active Namespace 

 🔗 Links: 
 - Install Kubectx: [https://github.com/ahmetb/kubectx#ins...](https://github.com/ahmetb/kubectx)
 
 [9. K8s Ingress explained](https://www.youtube.com/watch?v=X48VuDVv0do&t=7312s)
 * [ ] What is Ingress? External Service vs. Ingress 
 * [ ] Example YAML Config Files for External Service and Ingress 
 * [ ] Internal Service Configuration for Ingress 
 * [ ] How to configure Ingress in your cluster? 
 * [ ] What is Ingress Controller? 
 * [ ] Environment on which your cluster is running (Cloud provider or bare metal) 
 * [ ] Demo: Configure Ingress in Minikube 
 * [ ] Ingress Default Backend 
 * [ ] Routing Use Cases 
 * [ ] Configuring TLS Certificate 

 🔗 Links: 
 - Git Repo: [https://bit.ly/3mJHVFc](https://bit.ly/3mJHVFc)
 - Ingress Controllers: [https://bit.ly/32dfHe3](https://bit.ly/32dfHe3)
 - Ingress Controller Bare Metal: [https://bit.ly/3kYdmLB](https://bit.ly/3kYdmLB)
 
 [10. Helm - Package Manager](https://www.youtube.com/watch?v=X48VuDVv0do&t=8657s)
 * [ ] Package Manager and Helm Charts 
 * [ ] Templating Engine 
 * [ ] Use Cases for Helm 
 * [ ] Helm Chart Structure 
 * [ ] Values injection into template files 
 * [ ] Release Management / Tiller (Helm Version 2!) 

 🔗 Links: 
 - Helm hub: [https://hub.helm.sh/](https://hub.helm.sh/)
 - Helm charts GitHub Project: [https://github.com/helm/charts](https://github.com/helm/charts)
 - Install Helm: [https://helm.sh/docs/intro/install/](https://helm.sh/docs/intro/install/)
 
  [11. Persisting Data in K8s with Volumes](https://www.youtube.com/watch?v=X48VuDVv0do&t=9487s)
  * [ ] The need for persistent storage & storage requirements 
  * [ ] Persistent Volume (PV) 
  * [ ] Local vs Remote Volume Types 
  * [ ] Who creates the PV and when? 
  * [ ] Persistent Volume Claim (PVC) 
  * [ ] Levels of volume abstractions 
  * [ ] ConfigMap and Secret as volume types 
  * [ ] Storage Class (SC) 

  🔗 Links: 
  - Git Repo: [https://bit.ly/2Gv3eLi](https://bit.ly/2Gv3eLi)
  
  [12. Deploying Stateful Apps with StatefulSet](https://www.youtube.com/watch?v=X48VuDVv0do&t=10718s)
  * [ ] What is StatefulSet? Difference of stateless and stateful applications 
  * [ ] Deployment of stateful and stateless apps 
  * [ ] Deployment vs StatefulSet 
  * [ ] Pod Identity 
  * [ ] Scaling database applications: Master and Worker Pods 
  * [ ] Pod state, Pod Identifier 
  * [ ] 2 Pod endpoints 
  
  [13. K8s Services](https://www.youtube.com/watch?v=X48VuDVv0do&t=11623s)
  * [ ] What is a Service in K8s and when we need it? 
  * [ ] ClusterIP Services 
  * [ ] Service Communication 
  * [ ] Multi-Port Services 
  * [ ] Headless Services 
  * [ ] NodePort Services 
  * [ ] LoadBalancer Services
