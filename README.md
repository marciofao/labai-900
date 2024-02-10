# labai-900
Modelo de IA para venda de Bicicletas

Etapas de realização:
- acessar https://portal.azure.com/
- Criar um recurso
- Seleciona Azure machine learning -> criar
- cria um novo grupo de recursos
- Adiciona nome
- Selecionado região west 2
- examinar+criar -> criar
- aguardar finalização
- Ir para o recurso
- iniciar studio (https://ml.azure.com)
- seleciona ML automatizado -> novo trabalho
- adiciona nome, nome trabalho, descricao, avançar
- criar, adicionar nome, descricao,
- selecionar de arquivos da web
- adiciona url https://aka.ms/bike-rentals
- cabeçalhos: somente primeiro
- avançar, avançar, criar
- tarefa: regressão, seleciona na lista, avançar
- coluna:rentals
- configurações adicionais: desmarcar todas, modelos: random forest, lightgbm -> salvar, avançar
- maximos: 3, limite 0,085 tempos limite: 15, habilita encerramento antecipado, validação: divisão treinamento: 10
- dedicado 16 gb, enviar
  
