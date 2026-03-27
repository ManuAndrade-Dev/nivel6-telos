# nivel6-telos

1. Atributos e Métodos:
Atributos (características): health, velocity e direction.
Métodos (ações): move() e jump().

2. Conceito de Classe:
A alternativa correta é a B. Uma classe funciona como um modelo ou "molde" que define quais características (atributos) e ações (comportamentos) os objetos daquele tipo terão.

3. Valor de e2.health:
O valor será 100.
Por que? Porque e1 e e2 são objetos independentes. Alterar a vida do primeiro objeto para 50 não muda a vida do segundo, que permanece com o valor inicial definido na classe.

4. Valor de e._health:
O valor será 50.
Por que? O código mostra que o valor 50 foi atribuído diretamente ao atributo _health daquela instância específica.

5. Por que boss chama display()?
Isso acontece por causa da Herança. Como a classe BossEnemy estende (extends) a classe Enemy, ela "herda" automaticamente todas as funções da classe pai, incluindo o método display().

6. O que será exibido em e.move()?
Será exibido "Pulando".
Por que? A variável e está usando uma instância de JumpingEnemy. Como essa classe filha redefiniu o método move(), o comportamento que vale é o dela (sobrescrita de método).

7. Verdadeiro ou Falso:
(V) Métodos podem alterar atributos.
(F) Métodos não podem receber parâmetros (Eles podem sim receber parâmetros).
(V) Métodos representam comportamentos.

8. e1 e e2 são o mesmo objeto?
Não.
Por que? Cada vez que você usa o comando .new(), o computador cria um objeto novo e exclusivo na memória. Mesmo que sejam da mesma classe, eles são entidades diferentes
