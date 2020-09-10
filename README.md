# CI-CD dashboard

CI-CD dashboard web application that helps to observe CI-CD processes, integrates CI-CD tools to collect and store helpful data in one place.  

Modules:
* Builds - Jenkins builds dashboard, Jenkins builds stats/charts
* Deployments - deployments dashboard and history, based on data from Jenkins builds
* Kubernetes - online Kubernetes clusters data. Deployments, pods list and statuses, pod logs. 

Sourcecode is not ready to publish yet. Used in several commercial environments.


## Screens
**Builds** module - Jenkins builds dashboard.

![Image description](.fls/screen1.png)

![Image description](.fls/screen2.png)

**Builds** module - Jenkins builds stats/charts. Builds distribution by developer, pipelinegroup *(Jenkins multibranch pipeline)* and builds trend.

![Image description](.fls/screen3.png)

**Deployments** module - deployments dashboard. Application releases distribution across multiple environments and Kubernetes namespaces.

![Image description](.fls/screen4.png)

**Deployments** module - deployments history. Application releases history.

![Image description](.fls/screen5.png)

**Kubernetes** module - pods dashboard. Provide online data on pods state and logs from multiple Kubernetes clusters.

![Image description](.fls/screen6.png)

**Kubernetes** module - deployments dashboard. Provide online data on deployments from multiple Kubernetes clusters.

![Image description](.fls/screen7.png)
