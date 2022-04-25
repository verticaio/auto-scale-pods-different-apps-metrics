# AKS Ingress Controller Auto-Scaling using Custom HTTP Request Count Metrics with taking advantage of Prometheus Adapter Plugin

## Quick Intro 
Kubernetes default HPA is only scaling pods based CPU and Memory metrics and most of time scaling pods based on memory it is not working well. Sometimes it is not convenient because CPU and memory based scaling works late and this case we can lost our business requests.In Additional We want to scale our apps based on different metric value  and in this case default HPA memory nd cpu metric won't be relevant and also If we emphasize our problem to scaling Nginx Ingress controller using custom http request count in which ingress accept this traffic the specific period of time

Note: Please take a look this docx  [AKS_Ingress_Controller_Auto_Scaling.docx](AKS_Ingress_Controller_Auto_Scaling.docx) file for  more depth details info


Have Fun :)