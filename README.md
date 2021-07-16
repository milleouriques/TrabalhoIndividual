# TrabalhoIndividual

POO: A programação orientada a objetos possui classes e objetos como base da lógica de programação 

Classe: A classe fica dentro do namespace. Possui modificadores de acesso, sendo eles: public (não restrito), protected (limitado a classe e as derivações dela), internal (pode ser acessado do mesmo projeto) e private (apenas dentro da classe). A classe define propriedades, métodos, etc. 

Método: Um método pode ser utilizado em varias variaveis. São construidos da seguinte forma: ![image](https://user-images.githubusercontent.com/50427189/125985088-006bb864-6edb-4e89-ae7f-4b43d5e5a5cb.png)
Um exemplo para utilização é a validação: ![image](https://user-images.githubusercontent.com/50427189/125985379-6fa3cd00-9a1d-46a0-89fe-16f3832d9324.png)
Assim basta chamar o método onde queira executa-lo dessa forma: ![image](https://user-images.githubusercontent.com/50427189/125985552-f30e7d13-afb2-45d7-8cdb-910dd957900d.png)
Caso o método não for estatico precisamos instansia-lo (tornando-o um objeto) e então chamar para executar: ![image](https://user-images.githubusercontent.com/50427189/125985643-559cd60e-1837-44aa-8882-bd1147db3712.png)

Herança: Pode ser criado uma clase base que é utilizada em outras classes que tenham variaveis em comum, como nome e ID. No caso da criação de classes de pessoa fisica e juridica, a classe base pode ser a pessoa que contém nome e data de nascimento: ![image](https://user-images.githubusercontent.com/50427189/125986452-981661f6-145d-4fdc-9603-b6cae9c9f3a5.png)
Assim a pessoa fisica e jurida se tornam filhas da classe base (pessoa): ![image](https://user-images.githubusercontent.com/50427189/125986549-b6701051-8b61-4408-8612-64edcf077c11.png)
![image](https://user-images.githubusercontent.com/50427189/125986596-3960dd71-f2fe-4d0b-848c-125b7d592532.png)


Composição: A composição serve para atrelar uma classe a outra, como de categoria dentro de produtos ou um endereço dentro de pessoa: ![image](https://user-images.githubusercontent.com/50427189/125987025-21ddf480-839a-4e5d-b94f-6cd252eb0d59.png)
![image](https://user-images.githubusercontent.com/50427189/125987043-8bcc718e-5b8f-450f-b3dd-67b6be0842f7.png)



Parametro: O parametro é a variavel que vai receber um valor, ja o argumento é o valor que você passa para a função ou método.

Sobrecarga de método: É quando temos 2 ou mais métodos com o mesmo nome mas parametros diferentes.

Parâmetros opcionais: É quando damos um valor default no parametro, não sendo necessario fornecer um valor no argumento.

Parâmetros nomeados: Parametros nomeados é quando precisamos dos argumentos, na ordem dos parametros, ou utilizando o nome da variavel com dois pontos ( : ).

