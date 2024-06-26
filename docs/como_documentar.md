# Passo a Passo Documentação do Projeto

Para adicionar informações, novos documentos, imagens ou alterações em geral na nossa documentação é necessário seguir os seguintes passos:

## 1. Criar uma "branch" específica para sua alteração .

  O nome da branch deve conter palavras chave da alteração como por exemplo:

Ex.1: 

- Desejo adicionar a ata da reunião geral da semana passada
- O nome da branch para isso será: "AtaRG-Data"
- Em "Data" insira os números diretamente como "1505" no caso da ata ser do dia 15/05

Ex.2:

- Irei adicionar diagramas para o projeto conceitual
- O nome da branch será: "Diagrama-Tipo-Area"
- Em "Tipo" insira o tipo do diagrama que será inserido
- Em "Area" insira a área da qual pertence o diagrama

  Da mesma forma siga o padrão para outros tipos de alterações

![CPE1](img/comodocumentar-1.png)

  Na área amarela é possível identificar qual branch você está (No caso do exemplo é a main). Para trocar de branch ou criar uma nova você pode apertar na seta para baixo, selecionar a branch desejada ou escrever o nome da branch nova para ser criada no espaço de busca.

## 2. Adicione suas alterações na pasta "docs".

  Para que o site funcione é necessário adicionar as alterações seja em texto ou arquivo dentro da pasta "docs" e seguindo o padrão de criação de arquivos já existente, pois somente assim o site é compilado e exibirá tudo.

## 3. Confirme as alterações por meio de um commit ou mais de um.

  - Cada alteração em um ou vários arquivos devem ser commitadas, para garantir que o arquivo seja "salvo" no repositório do GitHub.
  - Para realizar os commits você deve:

![CPE2](img/comodocumentar-1.png)

  - Na área vermelha é possível selecionar o arquivo que você irá editar
  - Na área azul você pode apertar no botão "code" para visualizar em código e no botão do lápis para editar
  - No código você faz suas alterações da forma que preferir

![CPE3](img/comodocumentar-2.png)


## 4. Realize um PR(Pull Request) da sua branch com a branch principal "main"
 
- Feito o(s) commit(s), deve ser feito o Pull Request para enviar para a branch "main" todas as alterações feitas.
- Segue abaixo o passo a passo para realizar o processo:

![CPE4](img/comodocumentar-3.png)
  
  - Na área em azul, você irá entrar na aba para criação e vizualização das "Pull Requests" existentes, entre nela para dar continuidade ao processo.
  - Na área em vermelho, poderá ocorrer duas opções, ambas realizando a mesma função, de dar continuidade e solicitar a criação de um Pull Request (a unica diferença entre os dois será que o botão "Compare & Pull Request, virá configurado já para o commit recem realizado").

![CPE5](img/comodocumentar-4.png)

  - Conforme a imagem, a área laranja informa que a aba atual se refere as comparações feitas, podendo verificar todos os arquivos alterados pelos commits executados previamente.
  - Em azul claro, será verificado a brach que as alterações serão importadas, no caso da imagem acima, vamos pegar as alterações da branch "Branch_Teste" para a branch "main", ou seja, as alterações da "Branch_Teste" serão jogadas para a branch "Main" para que o site possa carregar as alterações.
  - A área em verde é para o botão que irá confirmar as alterações. 

![CPE6](img/comodocumentar-5.png)

  - Em amarelo demonstra a área que será informado o Titulo que será dado ao Pull Request (Geralmente se refere ao que foi commitado no projeto anteriormente) e a descrição, como oque foi alterado e o por que.
  - Em branco temos os campos de "Reviewers" será selecionado a pessoa que irá verificar seu Pull Request (Geralmente será o gerente do projeto ou de software) e o Assignees que correspondem às pessoas que participaram do commit.
  - Por final a área verde, será para confirmar as informações até então preenchidas e criar de fato o Pull Resquest.

__________________________________________________________________________

- Finalmente, solicitamos que lembre de acionar revisor e solicitar revisão rapidamente.


