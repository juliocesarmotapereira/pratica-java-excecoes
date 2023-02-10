## Prática de Java Exceções: aprenda a criar, lançar e controlar exceções

Material de estudos práticos do Programa ONE da Oracle

### Anotações

* Funcionamento pilha de execução.
* Depuração (debug).

* Toda exceção em Java possui um nome que a identifica.
* Exceções não tratadas caem na pilha de execução procurando por alguém que saiba lidar com ela.
* Analisar o rastro de exceções, ou stacktrace.
* Tratar exceções com os blocos try-catch.
* Manipular uma exceção lançada dentro do bloco catch.
* Multi-Catch utilizando o pipe (|).

* HEAP (Memória de objetos)
* Exceções: como lançar e como atribuir uma mensagem. 

* Throwable > Exception > RuntimeException > ArithmeticException > NullPointerException > MinhaException
* Throwable > Error > VirtualMachineError > StackOverflowError
* Checked são criadas através do pertencimento a uma hierarquia que não passe por RuntimeException.
* Unchecked são criadas como descendentes de RuntimeException.

* Palavras chaves relacionadas com exceções: throw, finally, catch, throws, try.
* Bloco finally: útil para o fechamento de recursos (como conexão).