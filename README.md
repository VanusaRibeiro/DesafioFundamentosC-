<h2>Sistema de Estacionamento desenvolvido em C#</h2><br> O objetivo do Projeto é simular um sistema interativo de Estacionamento.<br>
onde o programa solicita ao usuário dois valores: Preço inicial e o preço por hora adicional.<br>
Esses valores são usados para instanciar a classe Estacionamento.<br>
O programa possui um menu com 4 opções:<br>
- Cadastrar veículo: adiciona uma placa à lista<br>
- Remover veículo: solicita a placa e calcula o valor a pagar<br>
- Listar veículos: exibe os veículos estacionados<br>
- Encerrar: finaliza o programa
<h2></h2>
<h2>Entendendo a Estrutura de um Projeto em C#<h2>
<h3></h3>A estrutura de um projeto em C# segue uma organização hierárquica que começa com<br>
um namespace, contendo classes, structs, interfaces, enumerações e delegados, ou outros namespaces.<br> 
<h3></h3>Um projeto é composto por Classes e suas convenções.<br>
Classe:
Define o tipo de um objeto, especificando seus membros (propriedades, métodos, etc.) e como ele se comporta.<br>
É como um "molde" para criar objetos e está relacionada com conceito de abstração na programação Orientada a Objeto.<br>
uma abstração nada mais é do que voce pegar um objeto do mundo real e transformá-lo em um objeto na programação,<br>
para que voce possa trabalhar com ele e implemtentar as suas ações;<br>
Dentro de uma classe, definem-se membros como propriedades, métodos, construtores, etc. <br>
A estrutura básica inclui namespaces, classes, métodos e, opcionalmente, interfaces, structs e enumerações. <br><br>

Namespace:<br>
É um contêiner para organizar classes, structs e outros tipos, evitando conflitos de nomes. Cada arquivo pode ter um ou mais namespaces. <br>

Struct:<br>
Semelhante a uma classe, mas é um tipo de valor, enquanto classes são tipos de referência.<br><br>
Structs são mais leves e usados para representar pequenos conjuntos de dados relacionados. <br><br>
Interface:<br>
Define um contrato que uma classe ou struct deve implementar, especificando os métodos que devem ser implementados. <br><br>
Método:<br>
Bloco de código que executa uma ação específica dentro de uma classe ou struct. <br><br>
Propriedade:<br>
Membro de uma classe ou struct que encapsula um valor, permitindo acesso e modificação através de métodos get e set. <br><br>
Pastas:<br>
Projetos são frequentemente organizados em pastas para agrupar arquivos relacionados, <br>
como pastas para modelos, controladores, serviços, etc., especialmente em aplicações maiores. <br>
Soluções (.sln):<br>
Uma solução pode conter um ou mais projetos, permitindo que você gerencie múltiplos projetos relacionados em um único ambiente. <br>

<h2></h2> Como criar um projeto:<h2></h2>
abra o vs code escolha c# ;<br>
abra o terminal e digite: dot net new console;<br>

-observe que foi criado duas pastas e dois arquivos:<br>
o primeiro é o program.cs ->program é o nome da sua classe<br>
( classe é o local onde voce vai fazer a codificação no C#).<br>
Todo arquivo de classe tem a extensão .cs que identifica ser um arquivo do C#;<br>
o próximo arquivo é composto do csproj -> é um arquivo de projeto do C# <br>
(contém informações essenciais que são descritivas para o seu projeto,<br>
tambem conhecidas como metadados, que usa uma lingagem XML)<br>

  <PropertyGroup>
    <OutputType>Exe</OutputType> --> indica o tipo de saída(pode ser um arquivo executável .exe ou um arquivo de bibliotecas<br><br>
   
obj  -> É a pasta de debugs que contém arquivos de compilação;

bin que contem binares.É nessa pasta que seu código foi gerado e transformado em binario.

// See https://aka.ms/new-console-template for more information
