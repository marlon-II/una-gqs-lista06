📚 Média do Aluno — Java

Projeto desenvolvido em Java como exemplo introdutório para uma aula de Ciência da Computação.

O programa recebe o nome e duas notas de um aluno, calcula sua média e informa sua situação acadêmica.

🎯 Objetivo

Este projeto tem como objetivo demonstrar conceitos básicos de programação em Java, como:

Entrada de dados pelo teclado;

Declaração e utilização de variáveis;

Tipos de dados;

Operações matemáticas;

Estruturas condicionais;

Saída de informações no console.

🛠️ Tecnologias utilizadas

Java

Scanner para entrada de dados;

Git para controle de versão;

GitHub para hospedagem do projeto.

📂 Estrutura do projeto
media-aluno/
├── MediaAluno.java
└── README.md

💻 Código-fonte
import java.util.Scanner;

public class MediaAluno {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Digite o nome do aluno: ");
        String nome = scanner.nextLine();

        System.out.print("Digite a primeira nota: ");
        double nota1 = scanner.nextDouble();

        System.out.print("Digite a segunda nota: ");
        double nota2 = scanner.nextDouble();

        double media = (nota1 + nota2) / 2;

        System.out.println("\nAluno: " + nome);
        System.out.println("Média: " + media);

        if (media >= 7) {
            System.out.println("Situação: Aprovado!");
        } else if (media >= 5) {
            System.out.println("Situação: Recuperação.");
        } else {
            System.out.println("Situação: Reprovado.");
        }

        scanner.close();
    }
}

▶️ Como executar
1. Verifique se o Java está instalado

No terminal, execute:

java -version


Também é possível verificar o compilador Java:

javac -version

2. Clone o repositório
git clone URL_DO_SEU_REPOSITORIO


Entre na pasta do projeto:

cd media-aluno

3. Compile o programa
javac MediaAluno.java

4. Execute o programa
java MediaAluno

🧪 Exemplo de execução
Digite o nome do aluno: João
Digite a primeira nota: 8
Digite a segunda nota: 6

Aluno: João
Média: 7.0
Situação: Aprovado!

📊 Regras do programa
Média	Situação
>= 7	Aprovado
>= 5 e < 7	Recuperação
< 5	Reprovado
🧠 Conceitos utilizados
Variáveis

O programa utiliza variáveis para armazenar as informações fornecidas pelo usuário:

String nome;
double nota1;
double nota2;
double media;

Entrada de dados

A classe Scanner é utilizada para receber informações digitadas pelo usuário:

Scanner scanner = new Scanner(System.in);

Cálculo da média

A média das duas notas é calculada através da seguinte expressão:

double media = (nota1 + nota2) / 2;

Estrutura condicional

O programa utiliza if, else if e else para verificar a situação do aluno:

if (media >= 7) {
    System.out.println("Situação: Aprovado!");
} else if (media >= 5) {
    System.out.println("Situação: Recuperação.");
} else {
    System.out.println("Situação: Reprovado.");
}

🚀 Possíveis melhorias

O projeto pode ser expandido para praticar novos conceitos de programação.

Algumas possibilidades são:

 Adicionar uma terceira ou quarta nota;

 Validar notas entre 0 e 10;

 Calcular a média de vários alunos;

 Criar uma classe Aluno;

 Utilizar ArrayList;

 Criar um menu interativo;

 Salvar os resultados em um arquivo;

 Implementar testes automatizados;

 Criar uma interface gráfica.

📖 Finalidade educacional

Este projeto foi desenvolvido para fins educacionais, servindo como exemplo para estudantes que estão iniciando seus estudos em programação e na linguagem Java.

👨‍💻 Autor

Seu Nome

⭐ Se este projeto foi útil para seus estudos, considere deixar uma estrela no repositório!
