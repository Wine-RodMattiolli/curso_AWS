# Ultimate AWS Certified Solutions Architect Associate 2022

> Sejam bem vindos ao meu acompanhamento de estudos do curso de AWS.

> Logo na apresentação de todos os serviços, o instrutor do curso nos apresenta toda a rede de databases que a Amazon possui, espalhados pelo mundo, para melhor atendimento ao cliente e menor latência na transferência de dados.

> Em seguida, foi apresentado o primeiro serviço do qual iremos aprender: **IAM - Identity and Access Management**.

### IAM - Identity and Access Management

> É um serviço global, ou seja, não precisamos selecionar uma região de trabalho.

> Esse serviço é utilizado para criar usuários dentro da sua organização e, se necessário, agrupa-los.

> Dentro desses grupos, são colocados os usuários que desempenham tarefas de forma coletiva e não se pode colocar um grupo dentro de outro por vontade própria

> Dentro das motivações sobre construir um grupo ou não, está a necessidade de se criar documentos chamados políticas, aonde se gerencia os acessos e a permitibiliade dos envolvidos.

#### Melhores práticas com IAM
1. Não use a conta root a menos que você queira montar algum setup.
2. Cadastre usuários em grupos e dê permissões aos grupos.
3. Crie senhas robustas e use sempre autentificação de multi-fatores.
4. Use Roles para dar permissões para a AWS.
5. Caso for usar CLI, crie senhas de acesso.
   