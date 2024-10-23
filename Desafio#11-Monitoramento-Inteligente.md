# Ferramentas de Monitoramento no Azure
Azure oferece varias ferramentas de monitoramenrto que ajudam a garantir os aplicativos e serviçoes estejam funcionando corretamente, abaixo ás principais.


## Azure Monitor ![Captura de tela 2024-10-23 011146](https://github.com/user-attachments/assets/039cf73e-93c9-46b0-b460-7aaf81154feb)



 Uma solução centralizada que fornece insights completos sobre o desempenho e a integridade dos recursos do Azure. 

- Coleta de Dados: Monitora métricas e logs de recursos do Azure, permitindo a coleta de dados em tempo real.
- Alertas: Configura alertas para notificar sobre condições específicas, como falhas ou desempenho abaixo do esperado.
- Análise: Utiliza o Azure Log Analytics para investigar dados e gerar insights

##  Configurando Azure Monitor
  1. - Acesse o [Portal do Azure](https://portal.azure.com/) 🌐
  2. - Selecione "Monitor" no menu lateral.
  3. - Criar uma Nova Regras de Alerta:
  4. - Vá para "Alertas" e clique em "Nova Regra de Alerta".
  5. - Escolha o recurso (como uma VM ou um App Service).
  6. - Defina a condição (por exemplo, "Uso de CPU > 80%").
  7. - Configure a ação (enviar um e-mail ou chamar um webhook).
  8. - Salve a regra.
    
  ## Resource Health ![Resource Health](https://github.com/user-attachments/assets/f760fd90-c2b1-46d9-8268-9f96b3dc139c)

  
  Ferramenta que fornece informações do estado dos seus recursos no Azure. Ela ajuda a monitor e diagnosticar problemas que podems afetar a disponibilizadade dos serviços e recursos.
  Ela indicica se os recursos estão saudaveis , em degradação ou offline, e mantém um historico dessas informações.
  E uma ferramenta esses para garantir a disponibilidade e o desempenhodos serviços na nuvem.

  
  1. Acessar o Azure Portal 🌐
   - Vá para o [Portal do Azure](https://portal.azure.com/).
2. - Selecionar o Recurso
- No painel do Azure, navegue até o recurso que deseja monitorar (por exemplo, uma máquina virtual, um banco de dados, etc.).
3. - Verificar o Resource Health
- No menu à esquerda, procure e clique em "Resource Health".
- Você verá o status atual do recurso (Saudável, Degraded ou Unavailable), junto com informações adicionais sobre a saúde.

4. Configurarando os  Alertas de Health


## Criar uma Regra de Alerta:
 ### Passo a Passo:
1. - Na seção Resource Health, clique em "Gerenciar Alertas" ou "Criar regra de alerta".
- Selecionar a Condição:

2. - Escolha o tipo de condição (por exemplo, "Resource Health status changes").
- Configure a condição para disparar um alerta quando o status mudar para "Degradado" ou "Indisponivel".
3. - Configurar Ação:

- Escolha uma ação a ser tomada quando o alerta for disparado, como enviar um e-mail, notificação por SMS, ou chamar um webhook.
4. - Definir Detalhes do Alerta:

5. - Dê um nome e uma descrição à regra de alerta e defina a severidade.
- Salvar:
- Clique em "Criar regra de alerta" para salvar a configuração.

Essas ferramentas juntas oferecem um visão abragente do estado dos seus serviços no Azure. 
Essas ferramentas e práticas ajudam a garantir que os recursos do Azure estejam sempre disponíveis e funcionando de forma otimizada, proporcionando uma base sólida para a operação de negócios.

Finalizamos o Bootcamp AZ900 - Essa certificação é uma excelente base para quem deseja entender os fundamentos do Azure.
