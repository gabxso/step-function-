Criamos um Assistente de Delivery usando **AWS Step Functions** e **Amazon Bedrock** para automatizar o atendimento de pedidos de forma mais inteligente e prática.

### Passo a Passo

1. **Receber Pedido**: Quando o cliente faz o pedido, ele entra no sistema de fluxo do Step Functions, que começa o processo de entrega.
   
2. **Confirmar Pedido**: Com a ajuda do Amazon Bedrock, o assistente verifica os detalhes do pedido e confirma as informações automaticamente, como endereço e itens solicitados.

3. **Calcular Tempo de Entrega**: Em seguida, o sistema calcula a previsão de chegada com base na localização do cliente e na disponibilidade de entregadores.

4. **Enviar Notificação ao Cliente**: O assistente mantém o cliente atualizado, enviando mensagens automáticas sobre o status do pedido e a previsão de entrega.

5. **Solicitar Feedback**: Depois da entrega, o cliente é convidado a avaliar o serviço, ajudando a melhorar o atendimento.

### Resumo

Com essa estrutura, o Assistente de Delivery torna o processo de entrega mais eficiente e informativo. O uso do Amazon Bedrock permite uma interação mais personalizada, enquanto o Step Functions organiza todo o fluxo de trabalho, facilitando o acompanhamento e a atualização dos clientes.
