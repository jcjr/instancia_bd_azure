# CONFIGURAR UMA INSTÂNCIA DE BANCO DE DADOS NA PLATAFORMA MICROSOFT AZURE

## OBJETIVO
O objetivo principal do repositório e descrever de forma clara e simples como configurar uma instância de banco de dados na 
plataforma Microsoft Azure. Será descrito os passos a serem seguido para a criação do banco de dados.

## BÁSICO
1o. Em "Detalhes do projeto" no campo "Grupo de recursos" você deve escolher a melhor opção para o que desejar a fazer. Está opção
pode gerar custos adicionais não previstos no projeto.

2o. Criar uma conta no site Microsoft Azure (https://azure.microsoft.com/pt-br/). Dê preferência a contas Microsoft(Hotmail.com e
Outlook.com), mas qualquer outra conta de e-mail pode ser utilizada. Você seguirá um passo a passo descrito no site que te levará
a criação da conta na plataforma Azure, informando que será necessário cadastrar uma meio de pagamento para que o cadastro tenha
sucesso.

3o. Após realizar o cadastro, o site abrirá na tela principal do Microsoft Azure, na qual pode-se selecionar os serviços a serem
utilizados, neste caso, você clica no ícone "Banco de dados SQL" e abrirá a página de configuração do servidor de banco de dados.

4o. Clique no botão "Criar" com um símbolo "+" para criar o banco de dados. Na página aberta, procure a área "Detalhes do banco de
dados" no campo "Nome do Banco de Dados". Neste ponto você definirá como será chamado seu banco de dados.

5o. O próximo preenchimento é o "Servidor". Caso seja seu primeiro servidor a ser criado ele aparecerá vazio, então deve-se clicar
no link "Criar novo" abaixo do campo. Aparecerá uma página para a criação do servidor. Deve-se definir o nome do servidor do banco
de dados, escolher a localização geográfica, definir o modo de autenticação e criação de um usuário para acesso ao servidor.

6o. Na opção que "Deseja usar o pool elástico SQL?" deixe como "Não", mas caso deseje a outra opção você definirá o nome. Lembrando
que os custos irão incidir nesta opção.

7o. Outro ponto importante é "Computação + armazenamento" na qual defini-se a configuração de processamento do servidor e tamanho do
espaço físico do disco. Um ponto bastante crucial e remete ao custo do projeto.

8o. Na opção "Redundância do armazenamento de backup" você define o local e como será feito o backup do banco de dados.

## REDE
9o. Esta área é reservada para a configuração de acesso ao servidor, neste ponto o mais importante é o "Método de conectividade" que
diz respeito a forma como você irá acessar os dados. A parte de "políticas de conexão" é um caso a parte, neste ponto você defini a 
como será acessado o servidor.

## SEGURANÇA
10o. Neste ponto você configura o nível de segurança do banco de dados. São necessárias pequenas configurações sem muita complicação.

## CONFIGURAÇÕES ADICIONAIS
11o. Opções relacionadas ao banco de dados descrevendo como ele deve ser inicializado, ordenação dos dados e horário na qual o servidor
pode ficar indisponível para manutenção.

Após realizado as configurações necessárias basta apenas clicar no botão "Revisar + Criar" para finalizar a criação do servidor e
banco de dados.

