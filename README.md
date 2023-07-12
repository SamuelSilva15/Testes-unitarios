# Assertions

* A classe Assertions é uma coleção de métodos que afirmam se certas condições comuns em testes correspondem ao esperado.
* Os métodos estáticos da classe Assertions são parte importante dos casos de teste e avaliam se certas condições, decisivas para determinar o sucesso ou falha do teste, geram um resultado esperado. Geralmente esses métodos lançam uma exceção do tipo AssertionFailedError.

Alguns dos principais métodos: assertTrue, assertFalse, assertNull, assertNotNull, assertEquals, assertArrayEquals, assertNotEquals, etc.

# Lifecycle Methods
 * É utilizado para realizar tarefas antes ou após os teste de unidade.

Os principais são BeforeEach, BeforeAll, AfterEach e AfterAll e podem ser vistos dessa forma: 
![image](https://github.com/SamuelSilva15/Testes-unitarios/assets/80695387/85345488-e8b7-490f-b296-a23c4a00ed3b)
