# DESENVOLVIMENTO DO BANCO DE DADOS PARA UPXII

 * Modelo lógico do banco: </br>
![Modelo lógico](https://github.com/GabrielRosa835/Trabalho-UPXII-Banco_de_Dados/assets/150252238/b7ae4d1a-ce7c-4226-ac66-b1170ca19e5f)

 * Síntese do projeto:
Criamos uma empresa teorética da qual venderia dispositivos para o controle da utilização de água em residência, fazendo a integração por meio de IOT. Dessa maneira, teríamos que ter em nosso banco de dados, no mínimo, os nossos clientes e dispositivos vendidos. Cada cliente poderia ter uma ou mais residências e consequentemente endereços, além de que cada residência poderia ter uma gama de dispositivos para cada necessidade do cliente.

 * Descrição do banco de dados:
Criamos um banco de dados com Cliente, Endereço e Dispositivo como entidades numa hierarquia de mesma ordem, ou seja, o relacionamento Cliente-Endereço é de 1-N assim como o de Endereço-Dispositivo, utilizando de tabelas ralacionais para interligar as entidades. Também criamos o encapsulamento da inserção e deleção de registros, juntamente com tabelas para históricos de deleções com seus devidos gatilhos. De forma adjunta, fizemos funções complementares e vizualizações que auxiliam tanto no desenvolvimento do banco como em sua utilização.
