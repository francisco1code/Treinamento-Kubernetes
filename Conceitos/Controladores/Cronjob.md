# Cronjob

## Oque é ?

Um Cron Job cria Jobs em um cronograma baseado em tempo.

Um objeto CronJob é como um arquivo crontab (tabela cron). Executa um job periodicamente em um determinado horário, escrito no formato Cron. 

[Como rodar o cronjob]("https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/")

## Como funciona ?

Um trabalho cron cria um objeto de trabalho about uma vez por tempo de execução de seu planejamento, Dizemos "about" porque há certas circunstâncias em que duas tarefas podem ser criadas ou nenhum trabalho pode ser criado. 