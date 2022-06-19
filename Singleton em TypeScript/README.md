Exemplo de padrão único de TypeScript
====================================

Este é  um exemplo simples de como você pode fazer um gerenciador de pontuação para um jogo com TypeScript usando o padrão Singleton .


====================================

Prós e Contras

Mais nem tudo são flores, o singleton tem alguns pontos negativos, são eles:

O Singleton pode ser quebrado - Embora se deseje apenas ter uma única instância da classe, e seja feito um código para isto, através da reflexão é possível se criar outra instância da classe.
É dificil de reverter - No caso por exemplo, de um gerenciador de cache, caso o mesmo estiver espalhado por toda a aplicação, e você se arrepender e quiser mudar, será difícil de reverter as implementações já feitas.
É necessário você saber os prós e contras de utilizar um pattern, ou tecnologia. É necessário ter bom senso para que a ferramenta não atrapalhar, mais seja algo para facilitar o trabalho e dar qualidade. O Singleton pode ser útil, mais em determinadas situações pode ser desnecessário, cabe a você analisar e aplicar ele for útil.
