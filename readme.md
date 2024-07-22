# Documentação:
  
  - *1º Passo:* criar gatilho com o Github  
  ![gatilho cloud build com github](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2011-28-37.png?raw=true)
  - *2º Passo:* enviei o push para o Github e tive o seguinte erro:  
  ![Erro de logging](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2011-43-44.png?raw=true)
  - *3º Passo:* para arrumar o erro anterior editei o cloud build:  
  ![Edição cloudbuid.yaml](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2011-43-55.png?raw=true)
  - *4º Passo:* segundo erro:  
  ![Erro no cloudbuild.yaml](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2011-49-34.png?raw=true)
  - *5º Passo:* editei o cloudbui.yaml novamente para versão final, e fiz a criação do bucket com o nome especificado no backend para salvar as versões do terraform
  ![Cloud build com sucesso](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2012-03-22.png?raw=true)  
  ![Cloud Storage](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2012-03-42.png?raw=true)  
  ![vpc criada](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2012-04-03.png?raw=true)
  ![VM criada](https://github.com/GuilhermeMarques1/pipeline-CICD-CloudBuild-Terraform/blob/main/images/Screenshot%20from%202024-07-22%2012-04-39.png?raw=true)
