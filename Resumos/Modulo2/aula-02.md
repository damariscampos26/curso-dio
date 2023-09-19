# 📌 Estrutura de Métodos
#### O nome da classe deve ser o mesmo nome do arquivo e sempre começar com letra maiúscula, palavras compostas também. 
No corpo da classe principal, são declarados os métodos.

````
public class EstruturaDeMetodos {

    // Método principal. Aqui, são declaradas variáveis e etc
    
    public static void main (String [] args) {

        int number1 = 5;
        int number2 = 9;
        
        int somar = somar (number1, number2);  // Aqui tem uma variável com nome 'somar' do tipo int, e o valor dela é a chamada do método, o segundo método principal. Como identificamos que ela está chamando um método? Porque há dois parâmetros: 'number1' e 'number2'.

        System.out.println(somar);

        // **** Segundo Exemplo ****

        String primeiroNome = "Dâmaris";
        String segundoNome = "Campos";

        String meuNome = meuNome(primeiroNome, segundoNome);

        System.out.println(meuNome);

    }

        // ***Estrutura de Métodos***

        // TipoRetorno - NomeObjetivoNoInfinitivo - Parâmetro(s).
        // Os métodos são declarados no corpo da classe, e não do método main.
        // Cada parâmetro de método, é separado por vírgula.

    public static int somar (int number1, int number2) {
        return number1+number2;
    }

    public static String meuNome (String primeiroNome, String segundoNome){
        return "Qual seu nome? " + primeiroNome.concat(" ")+segundoNome; //concat - - - >> concatenar/adicionar espaço entre um elemento e outro.
    }
}
````
