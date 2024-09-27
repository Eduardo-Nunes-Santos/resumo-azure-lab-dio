# Configurando Recursos | VM

## Criando a maquina Virtual

### 1° Passo 
Acesse o Portal Azure 
--  Entre no [Portal do Azure](https://portal.azure.com).

### 2° Passo 
Configurar a Maquina Virtual
--  No painel lateral, procure por “Máquinas Virtuais” e clique em "➕ Criar". Escolha o Grupo de Recurso e dê um nome a sua VM e defina a região.

![image](https://github.com/user-attachments/assets/ff18a7bf-dbb4-4429-b6a8-0729004f3cb5)

Ao clicar em Opções de Disponiblidade, note que o menu dropdown mostrará tem 3 opções. 

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


