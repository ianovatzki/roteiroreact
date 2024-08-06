Roteiro aula (06/08/2024)


Na aula de hoje (06/08/2024), tivemos uma demonstração de como seria um site de viagens, aprendemos conceitos básicos de React e como utilizá-los neste site.

O site de viagens que criamos é uma aplicação em React com as seguintes páginas:. A Home apresenta uma mensagem de boas-vindas.. Destinos apresenta uma lista de destinos turísticos com nomes e descrições, podendo adicionar novos destinos através de um formulário.. Contato apresenta informações para contato.

 Além das páginas, temos os seguintes componentes reutilizáveis, Destino, para apresentar informações sobre um destino, FormDestino, para adicionar novos destinos. O Header tem o título “Aplicativo de Viagens” e o Footer tem “2024 Viagem App”. O App possui um estado que gerencia a lista de páginas e o atualmente ativo. No plano de visualização da aplicação, há um menu de navegação com botões para alternar a Home, Destinos e Contato. Isso tudo é claro, fazendo parte da forma inicial do projeto.


 Além disso, utilizamos regras de negócio essenciais para ter um mapeamento mais simples e lógico do projeto, como: 


Estamos no Brasil, então todos os pontos para calcular distância devem partir daqui.

Temos que ter pelo menos 10 destinos pré cadastrados com suas distâncias.

Calcular a distância até o destino escolhido.

Acima de 2000 km pega 2 voos.

Se o voo for inferior a 2 meses a partir de agora é 1500 reais (considerando ida e volta).

Se o voo for igual ou superior a 2 meses a partir de agora, paga 700 reais (considerando ida e volta).

Acima de 2000 km cada 1 km adicional custa 1 real a mais no total.

Cada semana de estadia custará 400 reais na estalagem padrão. Ou 700 reais na estalagem de luxo.

Cada participante adicional adiciona 25% nos custos de estalagem.

Enquanto escolhe o destino, o número de participantes, o tipo de estalagem e as datas de ida e volta, sempre aparece o subtotal imediato da compra a mostra com os critérios detalhados.

Após escolher a viagem, as datas, o número de participantes, será redirecionado para tela de pagamento e fechamento de pedido, discriminando os critérios detalhados e o total. E exibindo métodos de pagamento: pix ou cartão de crédito. 

Além disso, temos ainda a lógica do cálculo de distância e os custos da viagem, a lógica utilizada para calcular distâncias e custos da viagem é armazenada no site de viagens e critérios como estados. Eles armazenam informações sobre a data de chegada e retorno. Exibe o tipo de estalagem ou participantes. O subtotal é recalculado se os critérios forem alterados. As informações para serem armazenadas são as seguintes: Todas as datas são convertidas em objetos Date. A duração da estadia — em dias e semanas.

 O custo do voo: 3000 reais se a distância for superior a 2000 km, 1500 reais — caso contrário. O custo para cada quilômetro adicional será maior que 2000 km. O custo da estalagem: 400 reais por semana na estalagem padrão e 700 reais na estalagem de luxo. Um aumento de 25% no custo por participante. Soma de todos os custos acima. Todos os critérios discutidos acima podem ser selecionados a partir de uma interface que também irá exibir o subtotal em tempo real.

Dito isso, acredito que possam haver algumas melhorias neste app, como um mapa interativo por exemplo, ou até filtros na barra de pesquisa, além disso o design seria bem legal também.

