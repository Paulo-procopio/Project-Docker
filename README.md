# Project-Kubernetes

Lab: testando um Service ClusterIP com um Pod Debian
Neste laboratório, criei um Pod com dois containers (Apache e Tomcat), um Service do tipo ClusterIP e um Pod Debian para testar a comunicação interna do cluster. Instalei o curl no Debian e usei esse Pod como cliente para acessar o Service.

Objetivo

Entender como selector, port e targetPort funcionam na prática:


Ambiente:

. Cluster Kubernetes local com kind.

. kubectl configurado para o cluster.

. Pod web-pod com Apache e Tomcat.

. Service frontend-service do tipo ClusterIP.

. Pod debian-pod usado para testar a comunicação.

<img width="870" height="719" alt="01" src="https://github.com/user-attachments/assets/f3a1c9b1-cb0b-4c33-b60d-0737feae1044" />

<img width="621" height="384" alt="02" src="https://github.com/user-attachments/assets/05a53296-430a-4ce9-b6b5-105fe82d31cb" />

<img width="951" height="409" alt="03" src="https://github.com/user-attachments/assets/4b04a741-35c2-4ce7-b02a-f17b452176cc" />

<img width="710" height="120" alt="04" src="https://github.com/user-attachments/assets/11c2a600-0b68-4ff7-b0ee-7445010a8eb3" />

<img width="1071" height="975" alt="05" src="https://github.com/user-attachments/assets/20c7eecb-3abd-4de1-b939-a91ddc7841e8" />

<img width="1563" height="906" alt="06" src="https://github.com/user-attachments/assets/68731721-e264-4ed4-a7c4-5a516e69fb7d" />
