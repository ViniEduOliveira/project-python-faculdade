<h1>Gerenciador de Tarefas Pessoal </h1>

<h2>
  Este projeto é uma aplicação de linha de comando em Python para o gerenciamento de tarefas pessoais.

  O sistema permite cadastrar, atualizar, concluir e excluir tarefas, salvando todos os dados de forma persistente em arquivos JSON.
</h2>

<h1>Funcionalidades</h1>

<h2>
  Gestão de Tarefas: Cadastro de novas tarefas com título, descrição, prioridade e origem.

  Ciclo de Vida: Capacidade de iniciar uma tarefa (Ver Urgência), atualizar sua prioridade, marcá-la como concluída ou excluí-la (exclusão lógica).

  Persistência de Dados: O sistema salva todas as tarefas ativas em tarefas.json e move as tarefas concluídas (há mais de 7 dias) ou excluídas para um arquivo de histórico, tarefas_arquivadas.json.
</h2>

<h1>Relatórios Detalhados:</h1>

<h2>
  Tabela Principal: Lista todas as tarefas ativas, ordenadas por prioridade.

  Cálculo de Tempo: Calcula e exibe o tempo total de execução para tarefas já concluídas.

  Tabela de Histórico: Mostra as tarefas arquivadas (sem incluir as excluídas).

  Garantia de ID Único: O sistema verifica ambos os arquivos (tarefas.json e tarefas_arquivadas.json) para garantir que o código de uma nova tarefa seja sempre único.
</h2>
