# Regras de Gatilho

<p><strong>Regra: all_sucess</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se todas as tarefas anteriores foram concluídas com sucesso</p>

<p><strong>Regra: all_failed</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se todas as tarefas anteriores falharam </p>

<p><strong>Regra: all_done</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se todas as tarefas anteriores foram concluidas 
independente do status</p>

<p><strong>Regra: one_sucess</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se pelo menos uma das tarefas anteriores foi concluída com sucesso</p>

<p><strong>Regra: one_failed</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se pelo menos uma das tarefas anteriores falhou.</p>

<p><strong>Regra: none_failed</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se nenhuma das tarefas anteriores falhou.</p>

<p><strong>Regra: none_skipped</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é executada se nenhuma das tarefas anteriores foi pulada.</p>

<p><strong>Regra: dummy</strong> <strong> Quando é Executada (em relação a tarefa anterior) </strong> a tarefa é sempre executada, independente do status das tarefas anteriores.</p>
