# Projeto-files-docker

## 📍 Hallo Guys!!!

Hoje trouxe um conteúdo massa para quem quer contruir um Lab para conhecer e testar as funcionalidades do Docker.
Para montar o Cluster usei o Hypervisor do tipo 2, o virtual Box.
Usei o Debian 11, netinstall de 64 Bits, como mostra a imagem abaixo:


![image](https://github.com/user-attachments/assets/19b62fe1-4ad6-485e-a06d-5d7f7e0cbe4f)


Criei 3 máquinas virtuais, seguindo o modelo do Bootcamp, todas com as mesmas configurações:  
Memória RAM: 2GB  
Vcpu: 2 Núcleos  
Disco: 10GB dinâmicos  
Rede: 1 Nic em Bridge e 1 Nic em modo interno.  
A interface em modo Bridge, vamos usa-la para instalar os serviços utilizados no Lab.  
A Interface em modo interno, vamos usa-la para que as 3 máquinas conversem entre si e compartilhem recursos do Docker.  


Os arquivos usados durante o Bootcamp estão disponíveis nesse repositório.  
Para saber mais sobre as configurações das VMS, podem enviar issues.
