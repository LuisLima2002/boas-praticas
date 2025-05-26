# Boas Práticas de Desenvolvimento
Lista de Boas Práticas LabSub.

##Branches do projeto
1. stable: essa branch contém o último código do projeto que foi testado e aprovado
2. development: essa branch contém o último código do projeto que foi desenvolvido e ainda está sendo validado
3. feature/(nome-da-feature): branches com o préfixo "feature/" contém códigos que estão sendo desenvolvidos para adicionar ou melhorar uma feature do projeto
4. bugfix/(nome-do-bug): branches com o préfixo "bugfix/" contém códigos que estão sendo desenvolvidos para corrigir erros identificados nas branches stable ou development

##Fluxo de desenvolvimento
1. Crie um novo branch no seu repositório local, o nome da branch deve ter o préfixo indicando a natureza da mudança, assim como um nome curto que deixe claro o objetivo da mudança.
2. Implemente suas mudanças
3. Faça um push do seu branch para o repositório remoto
4. Submeta um Pull Request com uma breve descrição/justificava das mudanças
5. Aguarde a revisão do mesmo por outros desenvolvedores da sua equipe
6. Caso alguma mudança seja solicitada, implemente-a.
7. Caso o Pull Request seja aprovado, faça o merge na branch development.

A etapa 6 é feita na página de discussão do pull request. Nela é possível fazer comentários sobre trechos de código ou sobre o pull request em geral, tal como um fórum.

Orientações:
- Revisor:
  - Caso conheça algum tutorial ou link útil para resolver algum problema apontado, compartilhe-o na área de discussão do pull request.
- Desenvolvedor que submeteu o pull request:
  - Responda os questionamentos dos revisores.
  - Caso algum revisor tenha solicitado algo e você não consiga entender a solicitação, não hesite em questioná-lo.


##Controle de versão
- Mensagens de commit devem ser curtas e objetivas ou fazer referência a uma atividade definida no Trello. Exemplos:
  - "Fix bug at user controller"
  - "Add sign in feature"
  - "(Nome da atividade no Trello)"
- Commits devem possuir poucas mudanças, em geral. Ou seja: commite constantamente.
- Pulls Request devem ser revisados o quanto antes, para evitar que quem os tenha feito fique "bloqueado" enquanto aguarda feedback

![Fluxograma de boas práticas](https://github.com/LuisLima2002/boas-praticas/blob/main/fluxograma.jpg?raw=true)
