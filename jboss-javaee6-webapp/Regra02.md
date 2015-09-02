2 - Salvar o endereco do usuario, seguindo as regras de CRUD (Create, Read, Update e Delete).
========================


Eu, como usuário, quero administrar meus dados de endereço para INCLUIR, CONSULTAR, ATUALIZAR, DELETAR meu endereço.

Os critérios de aceite dessa história são:
O endereço deve ser controlado por um ID único
Para o CEP deve-se garantir: Utilizar o serviço de BUSCA DE CEP para validar o CEP digitado
Em caso de erro, retornar a mensagem do serviço de BUSCA DE CEP

Os atributos RUA, NÚMERO, CEP, CIDADE e ESTADO são obrigatórios
Os atributos BAIRRO e COMPLEMENTO não são obrigatórios
Em caso de erro: Retornar uma mensagem de erro
Não efetuar a INCLUSÃO/ALTERAÇÃO

A busca deve ser feita pelo ID

 

O que se espera para as questões 1 e 2 - dicas e direcionamentos:

 
Os serviços devem receber e responder JSON;
Faça o uso de Mocks para as consultas de CEP, principalmente nos testes;
O uso de algum Banco de Dados será um diferencial, mas você pode salvar em memória;
Pense em como documentar os cenários desenvolvidos (Testes sempre são uma boa forma de documentar);
Ao finalizar o desenvolvimento você pode compartilhar o código pelo Github ou de outra maneira que preferir (como arquivo compactado). Se possivel, em caso de arquivo compacto, envie o mesmo para um virtual drive e compartilha o link na prova;
Fique a vontade para entrar em contato e tirar dúvidas;
A deleção deve ser feita pelo ID;
Juntamente com o Código, deve-se documentar a estratégia utilizada para a criação da aplicação, a arquitetura utilizada e os padrões. A documentação pode ser feita via GIT/Bitbucket ou adicionado no HackerRank. Isto faz parte da avaliação da prova;
Caso utilize o Git/Bitbucket, não esqueça de criar o .gitignore
