
3 - Dada uma stream, encontre o primeiro caracter que no se repita no resto da stream. O termino da leitura da stream deve ser garantido atraves do metodo hasNext(), ou seja, retorna falso para o termino da leitura da stream. Voce tera acesso a leitura da stream atraves dos metodos de interface fornecidos ao termino do enunciado.
========================

Premissas:

 
Uma chamada para hasNext() ir retornar se a stream ainda contem caracteres para processar.
Uma chamada para getNext() ir retornar o proximo caracter a ser processado na stream.
Nao sera possivel reiniciar o fluxo da leitura da stream.

 

Exemplo:

Input:  aAbBABac

Output: b

No exemplo, ‘b’ é o primeiro caracter da stream que não se repete.

 

Segue o exemplo da interface em Java:

public interface Stream{

    public char getNext();

    public boolean hasNext();

}

 

public static char firstChar(Stream input) {

}

 

O que espera-se como resultado - Dicas e direcionamentos:
Tente criar sua implementacao pensando em performance;
Efetuar casos de teste para diversos cenarios e uma boa pratica;
Documentar o codigo e uma boa pratica;
Os codigos mais simples tendem a serem mais elegantes;
Em caso de nao localizacao do caracter, o sistema deve informar uma mensagem amigavel;
Ao finalizar o desenvolvimento você pode compartilhar o código pelo Github ou de outra maneira que preferir (como arquivo compactado). Se possivel, em caso de arquivo compacto, envie o mesmo para um virtual drive e compartilha o link na prova;
Juntamente com o Código, deve-se documentar a estratégia utilizada para a criação da aplicação, a arquitetura utilizada e os padrões. A documentação pode ser feita via GIT/Bitbucket ou adicionado no HackerRank. Isto faz parte da avaliação da prova;
Caso utilize o Git/Bitbucket, não esqueça de criar o .gitignore
