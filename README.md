# Project-Kubernetes

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

<img width="1049" height="712" alt="image" src="https://github.com/user-attachments/assets/30efe5f3-be7f-4e30-b65a-d698a4d64b92" />


<img width="1049" height="712" alt="image" src="https://github.com/user-attachments/assets/0c87ba36-af14-415e-9496-cf1af0be9867" />


<img width="1049" height="712" alt="image" src="https://github.com/user-attachments/assets/6d7fc6d0-5012-41cb-8634-7a7eeefcdaeb" />


<img width="1568" height="810" alt="image" src="https://github.com/user-attachments/assets/622cb6fd-bd26-4c46-8030-680afca6e370" />


<img width="1235" height="861" alt="image" src="https://github.com/user-attachments/assets/2e1053c5-41cf-4260-b5a0-d233c6d28c02" />

