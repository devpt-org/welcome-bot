# devPT Discord Welcome Bot

Este repositório serve de momento de armazenamento das frases utilizadas para dar as boas-vindas aos mais recentes membros.

A frase de introdução a novos utilizadores é construída com base no output da junção de uma seleção aleatória de uma frase do ficheiro `intro.txt` e de uma outra frase do ficheiro `welcoming.txt`.

A tag `<@${context.params.event.user.id}>` é substituída em runtime pelo nome de utilizador que entrou no servidor, mencionando-o.

## Regras de contribuição

Se quiseres contribuir, corrigir algo, ou até recomendar melhorias, cria um pull request.

### Como posso começar?

1. Faz fork do projeto (<https://github.com/devpt-org/welcome-bot/fork>)
2. Cria uma branch para as tuas frases (`git checkout -b add/funny-phrases`)
3. Faz commit das tuas alterações (`git commit -am 'Add some funny phrases'`)
4. Faz push da tua branch para master (`git push origin add/funny-phrases`)
5. Cria um novo Pull Request