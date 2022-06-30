# singleton-em-TypeScript
Singleton é um (anti-)padrão de projeto de software (do inglês Design Pattern). Este padrão garante a existência de apenas uma instância de uma classe, mantendo um ponto global de acesso ao seu objeto.

Nota linguística: O termo vem do significado em inglês para um conjunto (entidade matemática) que contenha apenas um elemento.[1]

Alguns projetos necessitam que algumas classes tenham apenas uma instância. Por exemplo, em uma aplicação que precisa de uma infraestrutura de log de dados, pode-se implementar uma classe no padrão singleton. Desta forma existe apenas um objeto responsável pelo log em toda a aplicação que é acessível unicamente através da classe singleton.

Onde Usar
Quando você necessita de somente uma instância da classe, por exemplo, a conexão com banco de dados, vamos supor que você terá que chamar diversas vezes a conexão com o banco de dados em um código na mesma execução, se você instanciar toda vez a classe de banco, haverá grande perda de desempenho, assim usando o padrão singleton, é garantida que nesta execução será instânciada a classe somente uma vez. Lembrando que este pattern é considerado por muitos desenvolvedores um antipattern, então, cuidado onde for utilizá-lo.
https://drive.google.com/file/d/1vJWlEUCT0lqJiM8lphVMb_j74l2FDUf4/view?usp=sharing
