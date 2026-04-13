# Requisitos do Sistema - Aplicativo de Delivery

## Requisitos Funcionais

1. **Cadastro de usuários**  
   O sistema deve permitir que usuários criem uma conta informando nome, email, telefone e senha.

2. **Login de usuários**  
   O sistema deve permitir que usuários realizem login utilizando email e senha.

3. **Visualização de restaurantes**  
   O aplicativo deve exibir uma lista de restaurantes ou estabelecimentos disponíveis.

4. **Visualização de cardápio**  
   O usuário deve conseguir visualizar os produtos disponíveis em cada restaurante.

5. **Finalização de pedidos**  
   O sistema deve permitir que o usuário finalize um pedido informando endereço de entrega e forma de pagamento.

6. **Acompanhamento de pedidos**  
   O usuário deve poder acompanhar o status do pedido (ex: preparando, saiu para entrega).

7. **Histórico de pedidos**  
   O sistema deve permitir que o usuário visualize pedidos realizados anteriormente.

8. **Cadastro de restaurantes e produtos**  
   Restaurantes devem poder cadastrar seus produtos, preços e descrições.
---

## Requisitos Não Funcionais

1. **Usabilidade**  
   O aplicativo deve possuir interface simples, intuitiva e fácil de usar.

2. **Desempenho**  
   O sistema deve carregar telas e informações de forma rápida.

3. **Segurança**  
   Os dados dos usuários devem ser protegidos e armazenados de forma segura.

4. **Disponibilidade**  
   O sistema deve estar disponível para uso a qualquer momento.

5. **Compatibilidade**  
   O aplicativo deve funcionar em diferentes dispositivos e sistemas operacionais.

6. **Escalabilidade**  
   O sistema deve suportar aumento de usuários sem perda significativa de desempenho.

7. **Confiabilidade**  
   Os pedidos devem ser processados corretamente, evitando perda de dados.

8. **Manutenibilidade**  
   O sistema deve permitir atualizações e correções de forma simples.







## Testes do Sistema

### Teste de Cadastro de Usuário

**Objetivo:**  
Verificar se o sistema realiza corretamente o cadastro de um novo usuário.

**Passos do teste:**  
1. Acessar a tela de cadastro.  
2. Preencher os campos obrigatórios: nome, email, telefone e senha.  
3. Clicar no botão de cadastro.  

**Resultado esperado:**  
O sistema deve cadastrar o usuário com sucesso e exibir uma mensagem de confirmação ou redirecionar para a tela inicial/login.

**Critério de sucesso:**  
O usuário deve ser registrado no sistema sem erros, desde que os dados informados sejam válidos.

---

### Teste do Movimento de Entrega

**Objetivo:**  
Verificar se o sistema atualiza corretamente o andamento da entrega do pedido.

**Passos do teste:**  
1. Realizar um pedido no aplicativo.  
2. Confirmar o pedido no sistema.  
3. Alterar o status do pedido para “Em preparo”.  
4. Alterar o status para “Saiu para entrega”.  
5. Finalizar com o status “Entregue”.  

**Resultado esperado:**  
O usuário deve conseguir acompanhar a mudança de status do pedido em tempo real ou de forma atualizada na tela de acompanhamento.

**Critério de sucesso:**  
O sistema deve exibir corretamente cada etapa da entrega até a conclusão do pedido.