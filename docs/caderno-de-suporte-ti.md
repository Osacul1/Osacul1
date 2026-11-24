# Caderno de Suporte TI

## Caso 01 — Uma tarefa foi apagada por engano

**Ambiente:** demonstração pública da [Lista de Tarefas](https://osacul1.github.io/lista-de-tarefas/), em um navegador de desktop. Exercício com dados de exemplo.

**Relato simulado:** “Apaguei uma tarefa por engano e preciso recuperar.”

**Triagem:** confirmar se a página ainda está aberta na mesma aba e se a exclusão foi a última ação desse tipo. Perguntar se existe um backup, sem pedir que a pessoa recarregue a página.

**Reprodução observada:** foi criada a tarefa “Revisar aula de redes”. Após a exclusão, o app mostrou “Tarefa excluída” e exibiu o botão “Desfazer exclusão”. Ao clicar nele, a tarefa reapareceu na lista e o app mostrou “Exclusão desfeita”.

**Limite da solução:** o README informa que o botão guarda somente a última exclusão da sessão. Se a página já foi recarregada ou fechada, verificar a existência de backup e conferir a prévia antes de importar. A recuperação após recarregar ficou fora deste teste.

**Resposta ao usuário:** “Se a página ainda está aberta, clique em Desfazer exclusão e confira se a tarefa voltou. Se já fechou a página, me diga se você tem um backup para conferirmos as opções.”

[Documentação do app](https://github.com/Osacul1/lista-de-tarefas)
