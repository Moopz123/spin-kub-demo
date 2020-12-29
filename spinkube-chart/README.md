<<<<<<< HEAD
# Installing helm chart - "helloworld-chart"
<br />

**Clone helloworld-chart from github:**

`git clone https://github.com/srihas/helloworld-chart.git`

<br />

**Change directory to the cloned directory**

`cd helloworld-chart`

<br />

**Install helm chart from local directory using:**

`helm install helloworld .`

**Check status of helm chart:**

`helm list`

**Check kubectl entities:**

`kubectl get all`

**In case of errors in deployment of pod, like ImgPullBack etc:**

`kubectl describe pod <pod-container-id>`

**Once the pod is Running, launch url in browser:**

`http://localhost`



**Finally to uninstall the helm chart and all kubernetes entities automatically:**

`helm uninstall helloworld`

=======
# Installing helm chart - "helloworld-chart"
<br />

**Clone helloworld-chart from github:**

`git clone https://github.com/srihas/helloworld-chart.git`

<br />

**Change directory to the cloned directory**

`cd helloworld-chart`

<br />

**Install helm chart from local directory using:**

`helm install helloworld .`

**Check status of helm chart:**

`helm list`

**Check kubectl entities:**

`kubectl get all`

**In case of errors in deployment of pod, like ImgPullBack etc:**

`kubectl describe pod <pod-container-id>`

**Once the pod is Running, launch url in browser:**

`http://localhost`



**Finally to uninstall the helm chart and all kubernetes entities automatically:**

`helm uninstall helloworld`

>>>>>>> a8ed571f2f6f15e10e926b3ba82cf94a280e5c73
