# Project-Docker

Lab: testando um Service ClusterIP com um Pod Debian
Neste laboratório, criei um Pod com dois containers (Apache e Tomcat), um Service do tipo ClusterIP e um Pod Debian para testar a comunicação interna do cluster. Instalei o curl no Debian e usei esse Pod como cliente para acessar o Service.

Objetivo
Entender como selector, port e targetPort funcionam na prática:


debian-pod → frontend-service:80 → web-pod:8080 → Tomcat
Ambiente
Cluster Kubernetes local com kind.

kubectl configurado para o cluster.

Pod web-pod com Apache e Tomcat.

Service frontend-service do tipo ClusterIP.

Pod debian-pod usado para testar a comunicação.
