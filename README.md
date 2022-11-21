# Projeto Praia Bonita

Site que apresenta algumas praias conhecidas do litoral brasileiro.
Esse projeto faz parte da iniciativa de praticar o desenvolvimento
colaborativo, tendo assim a experiência de como são vários
desenvolvedores trabalhando num mesmo código.


## Estrutura do projeto

- Páginas, como `index.html`, devem estar na raiz do projeto para facilitar o roteamento pelos links;
- Pasta `styles/` será colocado os arquivos `.css` para incluir os estilos das páginas;
- Arquivo `.prettierrc.json` contém as regras de formatação do código;
- Pasta `.vscode/` contém configurações de formatação seguindo as regras do arquivo `.prettierrc.json`. Fica a sugestão de usar o [vscode](https://code.visualstudio.com/). 

### Fluxo de trabalho

 1. Realize um ``fork`` do projeto para copiar o repositório para o seu
    Github. Lembrando que a branch `main` do seu `fork` será o local onde fará o `pull request` para o projeto.
 2. Verifique antes de começar o trabalho se existem atualizações da branch `main` desse repositório. Pela interface do próprio Github é mais fácil verificar se o seu `fork` precisa ser atualizado. 
 3. Após finalizar uma tarefa, realize um `pull request` para esse repositório que iniciara o processo de ***code review***.

### *Code review* 

Cada `pull request` passará por uma revisão do código, podendo ser aprovado ou não. Se for aprovado, ele entrará no código de produção e será feito o ***deploy*** **automático** para o servidor. Caso não seja, o desenvolvedor deverá verificar na **aba Pull requests** desse repositório as pendências a serem resolvidas. **Atenção**, as alterações realizadas na branch `main` do seu `fork` entrarão no `pull request` durante o processo de aprovação.

## Divisão de tarefas 

### *Issues*

Cada tarefa será representada por uma ***issue***. Ao finalizar uma, escreva no título do seu `pull request` um `close #NUMERO_DA_ISSUE` que o Github fechará automaticamente a ***issue*** , se for aceito pelo ***code review***. Exemplo: 

    feat: form for contact page (close #3)
Após aprovado, a ***issue*** #3 será fechada automaticamente.

### *Projects*

As ***issues*** ficarão organizadas em um ***project***, onde será delegado as tarefas para cada desenvolvedor, no estilo do *trello*.
