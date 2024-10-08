# Configuração de Recursos e dimensionamento de VMs 

## Configuração e dimensionamento de VMs

### 1° Passo 
Acesse o Portal Azure 
- Entre no [Portal do Azure](https://portal.azure.com).

### 2° Passo 
Configurar a Maquina Virtual
--  No painel lateral, procure por “Máquinas Virtuais” e clique em "➕ Criar". Escolha o Grupo de Recurso e dê um nome a sua VM e defina a região.

![image](https://github.com/user-attachments/assets/ff18a7bf-dbb4-4429-b6a8-0729004f3cb5)

Ao clicar em Opções de Disponiblidade, note que o menu dropdown mostrará 3 opções. 

### 3° Passo 
Disco :  Configurando o disco e Armazenamento criptografado. Verifique se o check excluir VM esta selecionado para não haver surpresa de custos ocultos depois.

![image](https://github.com/user-attachments/assets/6a28e047-6925-4d6e-92f6-8d982fe1c156)

### 4° Passo
Redes : Escolha uma opção das redes ou crie um nova clicando no botão 'Criar novo'. Os endereços publicos e as Nics permanecem idependente da sua rede virtual. Voccê selecionando a opção 'Excluir o IP público e a NIC quando a VM for excluída', assim que  a VM for excluida o IP publico e a NIc, será excluida automaticamente.

![image](https://github.com/user-attachments/assets/fe7524b4-eba7-4dc5-899d-8405f5d06c32)

### 5° Passo 
Gerenciamento : Onde são tratadas questões de segurança, acesso , desligamento automatico, backup e atualizaçãoes
![image](https://github.com/user-attachments/assets/414652b1-b5ab-4239-9f90-47ac5a2c70d5)
![image](https://github.com/user-attachments/assets/b8c80710-1b9b-4c0d-9452-1b5cb0121e14)

### 6° Passo 
Monitoramento: Habilitamos os alertas para sermmos notificado do eventos importantes que acontecem com nosso recurso. Na opção Diagnostico para solucionar problemas de falha de inicialização de imagens personalizadas ou de plataforma. Em Integridade, ao habilitar o conjunto de monitoriamento de integridade para dimensionamento. Este monitoriamento e necessario para infraestrutura geranciada da plataforma e atualizações do S.O.

![image](https://github.com/user-attachments/assets/4f1e0152-769f-49fd-a64f-8a13df79ee79)

### 7° Passo
Avançado : Adiconamos configuração de agentes, scripts ou aplicativos adicionais por meio de extensões da máquina virtual ou cloud-init.
![image](https://github.com/user-attachments/assets/d5ca8b3c-9e01-4d7a-82d5-0cf707d0c4fa)
![image](https://github.com/user-attachments/assets/fe3085d9-23c7-45ac-972c-2a72e898ef25)

### 8° Passo
Marcas: São os pares de nome/valor que permitem classificar recursos e exibir faturamento consolidado aplicando a mesma marca a vários recursos e grupos de recursos.

![image](https://github.com/user-attachments/assets/1bd858a8-4d0c-4ffb-a7f3-b70412f38f20)

### 9° Passo
Revisar + Criar : A hora de verificar toda configuração que foi realizada e o custo, caso esteja de acordo com as configurações e custos é só clicar no botão em criar.

![image](https://github.com/user-attachments/assets/5ca73dad-2123-4035-87fc-8cb8250f93f6)


