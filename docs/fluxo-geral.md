Fluxo Geral do Projeto

Objetivo  
Demonstrar uma automação de atendimento integrada com um CRM simples.

Etapas do fluxo  
1. O cliente envia uma mensagem para o bot  
2. O Telegram entrega a mensagem ao n8n  
3. O n8n extrai nome, usuário e texto da mensagem  
4. A automação identifica a intenção da mensagem  
5. O sistema registra o contato no CRM  
6. O cliente recebe uma resposta automática  

Classificações possíveis  
- vendas  
- suporte  
- financeiro  
- humano  
- geral  

CRM  
O CRM é representado por uma planilha do Google Sheets com os campos:  
- id  
- nome  
- telefone_ou_user  
- canal  
- mensagem  
- intencao  
- status  
- data_entrada  
- ultimo_contato  
- observacoes  

Resultado da demo  
Ao final do fluxo, o atendimento fica registrado, classificado e respondido automaticamente.
