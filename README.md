## Exercicio 1 - 
Crie a classe "Veiculo","Carro", "Moto" e "Caminhão". ​
​
Obs: use a linguagem java e siga as dicas sobre como criar classes. Faça a relação de herança que julgue adequada.

## Exercicio 2- 
Crie as classes "Funcionario", "Gerente", "Vendedor" e "Faxineiro".

Métodos:
Bater o Ponto
Fechar o Caixa
Realizar a Venda
Solicitar Material

Obs: use a linguagem java e siga as dicas sobre como criar classes. Faça a relação de herança de acordo com o slide.

## Exercicio 3 -  Interface Operação Matematica
Apenas para praticar, crie uma interface chamada "OperacaoMatematica". 
Crie também 4 métodos das operações básicas: soma, subtração, multiplicação e 
divisão implemente na classe Calculadora.
Obs: use a linguagem que gostar e siga as dicas sobre como criar classes. 
Tente não implementar algum dos métodos  e veja o que acontece.

## Exercicio 4- Interface de Pagamentos

Crie uma interface chamada Pagamento com os seguintes métodos:
calcularPagamento(): Sem parâmetros, deve ser implementado para calcular o valor do pagamento.
emitirRecibo(): Retorna um recibo detalhado da transação.
Agora, implemente essa interface em duas classes: PagamentoCartao e PagamentoDinheiro.
A classe PagamentoCartao deve incluir uma taxa de 5% sobre o valor do pagamento.
A classe PagamentoDinheiro deve aplicar um desconto de 10% sobre o valor do pagamento.
No final, crie uma classe de teste que simule o pagamento de R$100,00 com as duas formas de pagamento, calculando o valor final e emitindo um recibo.

## Exercicio 5 -Interface Autenticavel

Crie uma interface chamada Autenticavel com os seguintes métodos:
login(String usuario, String senha): Verifica se o login e a senha estão corretos.
logout(): Faz o logout do usuário.
Implemente essa interface na classe SistemaDeSeguranca. Nessa classe:
Defina os valores de um login e senha corretos, como "admin" e "1234".
No método login(), implemente a lógica para verificar se o usuário e senha inseridos correspondem aos valores corretos.
Se o login for bem-sucedido, armazene um valor booleano que indica se o usuário está autenticado ou não.
Tarefa: Crie uma classe de teste que peça ao usuário para inserir o nome de usuário e senha. Se o login estiver correto, o sistema deverá exibir uma mensagem de boas-vindas. Caso contrário, deverá pedir para tentar novamente até acertar. O sistema também deve permitir fazer o logout.
