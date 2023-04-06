# restaurant-simulator
A simple multithreaded Java project for expressing thread concepts

*Cozinheiro

 - Prepara os Condimentos
 - Limpa a Cozinha

 - Recebe Pedidos (do Garçom ou Delivery)
 - Prepara os Pedidos
   -- Pode aguardar todos os pedidos de uma mesa está pronto para liberar
 - Notifica que Pedido Está Pronto
 
 Exceções:
 
 - Pode servir a mesa em algumas situações, logo, em casos extremos, acumula a função de garçom
 - Em alguns casos pode ir na mesa conversar com o cliente
 
*Garçom

 - Atende o cliente na Mesa
 - Anota o Pedido
 - Envia o Pedido para Cozinha
 - Retira o Pedido na Cozinha
 - Serve a Mesa
 - Recebe o Pagamento
 - Limpa a Mesa
 - Notifica que a Mesa está Liberada
 
 Exceções:

 - Pode ser recepcionista em caso de exceções
 - Pedido pode estar errado
 - Pedido pode demorar mais do que o esperado
 - Cliente com saldo insuficiente para pagamento
 - Cliente pode desistir do Pedido

*Cliente

 - Ocupa uma Mesa
 - Faz o Pedido
 - Come
 - Faz o Pagamento
 - Vai embora
 
 Exceções:
 
 - Pode esperar tempo demais por uma mesa
 - Pode esperar tempo demais pelo Pedido
 - Item que ele pediu pode vir errado ou pode estar em falta
 - Pode reclamar da comida
 - Pode ir ao banheiro
 - Pode estar sem dinheiro
 - Pode reclamar do Preço
 - Pode pedir para falar com o Cozinheiro
 - Pode pedir para falar com o Gerente
 
*Gerente

- Abre o Restaurante
- Acompanha os setores do restaurante
- Resolve Conflitos entre cliente x garçom x cozinha x recepção
- Concede Cortesias
- Fecha o Restaurante

Exceções:

- Em alguns casos pode acumular as funções de Garçom e/ou Recepcionista
- Pode ter que abrir mesas extras
- Pode chamar funcionários de última hora

*Recepcionista

- Faz reserva de Mesas
- Recebe Pedidos do Delivery
- Gerencia Disponibilidade das Mesas
- Cadastra Cliente

Exceções:

- Em alguns casos extremos pode acumular a função de Garçom
- Tem autonomia para gerenciar pequenos conflitos
