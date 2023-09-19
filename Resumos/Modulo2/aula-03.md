# 📌 Indentação

Identação - - - >> Termo utilizado para escrever códigos de forma hierárquica.

````
public class Indentacao {

    public static void main(String[] args) {

        int mediaFinal = 10; // - - - - >> Variável do Tipo inteiro chamada mediaFinal, e lhe é atribuído o valor '6'.
        
        if (mediaFinal < 6) // - - - - >> Condição para o aluno ser aprovado.
            System.out.println("Reprovado!");

        else if (mediaFinal == 6)
            System.out.println("Prova Minerva!");

        else
            System.out.println("Aprovado!");
    }

}

````

# 📌 Organizando Arquivos
No decorrer do desenvolvimento de um sistema, vão surgindo novos arquivos (código fonte) na estrutura do projeto. Isso exige que seja realizado uma organização desses arquivos, através de pacotes (packages). 

A estrutura padrão de criação de packages é: organização.seunomeoudaempresa.nomedoprojeto.
Na prática, se você criasse um código para organizar seus estudos, ele ficaria: ```edu.damaris.estudos```, na qual edu corresponde a organização 'educação'.

## 📦 Criando Pacotes

1 - Para criar os pacotes em Java utilizando a IDE VsCode, você deve estar na pasta onde estão os arquivos principais de um projeto. Geralmente, o nome dessa pasta é _**scr**_.

2 - Em seguida, clique no ícone "**new folder**", para criar uma nova pasta e nomeie com a organização. Vamos usar o exemplo dado anteriormente. Então essa pasta terá o nome _**edu**_ e clique ENTER.

3 - Depois, clique de novo no mesmo ícone "**new folder**" e nomeie, agora, com o seu nome ou nome da empresa e clique ENTER.

4 - Por fim, clique novamente no ícone "**new folder**" e nomeie com o objetivo da pasta, no caso, _**estudos**._

#### A sequência de pastas ficaria ```src/edu/damaris/estudos```. Dentro deste package, é possível criar outras pastas para melhor organização, como ```/modulo1```, que ficaria dentro do package ```estudos```.
