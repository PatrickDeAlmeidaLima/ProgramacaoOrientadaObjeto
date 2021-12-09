# ProgramacaoOrientadaObjeto
Material de estudo para entender melhor POO, salvar o conteúdo para a comunidade um ótimo material.

**Aula01 - Conceitos de Orientação a Objeto(POO)**

**PROGRAMAÇÃO ORIENTADA A OBJETOS**

A orientação a objetos, também conhecida como Programação Orientada a Objetos (POO) ou Object-Oriented Programming (OOP) é um paradigma de análise, projeto e programação de sistemas de software baseado na composição e interação entre diversas unidades de software chamadas de objetos.

A análise e projeto orientados a objetos têm como meta identificar o melhor conjunto de objetos para descrever um sistema de software. O funcionamento deste sistema se dá através do relacionamento e troca de mensagens entre estes objetos.

Na programação orientada a objetos, implementa-se um conjunto de classes que definem os objetos presentes no sistema de software. Cada classe determina o comportamento (definido nos métodos) e estados possíveis (atributos) de seus objetos, assim como o relacionamento com outros objetos.

Linguagem de programação que suportam Orientação a Objeto.

C++, C#, Java, Object Pascal, Objective-C, Python, Ruby e Smalltalk;

ActionScript, ColdFusion, Javascript, PHP, Perl e VB.NET.

 

**CONCEITOS**

**Classe** representa um conjunto de objetos com características afins. Uma classe define o comportamento dos objetos, através de métodos, e quais estados ele é capaz de manter, através de atributos. Exemplo de classe: Os seres humanos.

**Subclasse** é uma nova classe originada de sua classe pai.

**Objeto** é uma instância de uma classe. Um objeto é capaz de armazenar estados através de seus atributos e reagir a mensagens enviadas a ele, assim como se relacionar e enviar mensagens a outros objetos. Exemplo de objetos da classe Humanos: João, José, Maria.

**Atributos** são características de um objeto. Basicamente a estrutura de dados que vai representar a classe. Exemplos: Funcionário: nome, endereço,telefone, CPF, ....; Carro: nome, marca, ano, cor, ...; Livro: autor, editora, ano. Por sua vez, os atributos possuem valores. Por exemplo, o atributo cor pode conter o valor azul. O conjunto de valores dos atributos de um determinado objeto é chamado de estado.

**Métodos** definem as habilidades dos objetos. Bidu é uma instância da classe Cachorro, portanto tem habilidade para latir, implementada através do método deUmLatido(). Um método em uma classe é apenas uma definição. A ação só ocorre quando o método é invocado através do objeto, no caso Bidu. Dentro do programa, a utilização de um método deve afetar apenas um objeto em particular; Todos os cachorros podem latir, mas você quer que apenas Bidu dê o latido. Normalmente, uma classe possui diversos métodos, que no caso da classe Cachorro poderiam ser sente(), coma() e morda().

**Herança (ou generalização)** é o mecanismo pelo qual uma classe (sub-classe) pode estender outra classe (super-classe), aproveitando seus comportamentos (métodos) e variáveis possíveis (atributos). Há Herança múltipla quando uma sub-classe possui mais de uma super-classe. Essa relação é normalmente chamada de relação "é um". Um exemplo de herança: Mamífero é super-classe de Humano. Ou seja, um Humano é um mamífero.

**Abstração** é a habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais. Em modelagem orientada a objetos, uma classe é uma abstração de entidades existentes no domínio do sistema de software.

**Polimorfismo** é a capacidade de um método poder ser implementado de diferentes formas, ou mesmo de realizar coisas diferentes. A decisão sobre qual o método que deve ser selecionado é tomada em tempo de execução, através do mecanismo de ligação tardia. Sobrescrita e sobrecarga são dois tipos de polimorfismo. Sobrescrita - Ocorre quando uma classe filha redefine um método herdado. Os métodos têm o mesmo nome e a mesma assinatura, mas na classe filha ele está implementado de forma diferente, ou seja, ele sobrescreve o método já existente da classe pai. Ambos possuem a mesma assinatura, mas a escolha de qual método utilizar baseia-se no tipo de objeto instanciado. Sobrecarga - Ocorre quando dois ou mais métodos possuindo o mesmo nome são implementados com assinaturas diferentes, ou seja, recebem parâmetros de diferentes tipos ou em diferentes quantidades. A escolha de qual método utilizar baseia-se nos parâmetros recebidos na chamada do mesmo.

EXEMPLOS:

**Classe** representa um conjunto de objetos com características afins. Uma classe define o comportamento dos objetos, através de métodos, e quais estados ele é capaz de manter, através de atributos.

Exemplo de classe: Cachorro, Copo, Radio, Telefone, etc.

Tudo que representa uma categoria de objetos.

| Classe  |  Objeto  |
| ------------------- | ------------------- |
|  Cachorro | Poodle |
|  - |  PitBull |
|  - | Vira-Lata |

| Classe  |  Objeto  |
| ------------------- | ------------------- |
|  Radio | AM-FM |
|  - |  Toca-Fitas |
|  - | MP3 |

| Classe  |  Objeto  |
| ------------------- | ------------------- |
|  Telefone | ??? |
|  - |  ??? |
|  - | ??? |

OBS: ??? Quando encontrar este símbolo pense em mais exemplos.


**Objeto** é uma instância de uma classe. Um objeto é capaz de armazenar estados através de seus atributos e reagir a mensagens enviadas a ele, assim como se relacionar e enviar mensagens a outros objetos.

| Classe  |  Objeto  |
| ------------------- | ------------------- |
|  Homem | João |
|  - |  José |
|  - | Maria |

| Classe  |  Objeto  |
| ------------------- | ------------------- |
|  Computador | Desktop |
|  - |  LapTop |
|  - | Palmop | 	
 	
**Atributos** são características de um objeto. Basicamente a estrutura de dados que vai representar a classe.

Exemplo:

| Objeto  |  Atributos  |
| ------------------- | ------------------- |
|  Funcionario | Nome, Endereço, Telefone, CPF. |
|  Carro |  	Nome, Marca, Modelo, Ano, Cor. |
|  Livro | Autor, Editora, Ano da Publicação | 	
	

Os atributos possuem valores.

Exemplo:

| Objeto  |  Atributos  |  Valor  |
| ------------------- | ------------------- | ------------------- |
|  Carro | Nome | Gol |
|  - |  	Marca |  	VW |
|  - | Ano |  	2009 | 	

| Objeto  |  Atributos  |  Valor  |
| ------------------- | ------------------- | ------------------- |
|  Livro | Nome | Modelagem de Dados |
|  - |  	Autor |  	Claudio Mabelini |
|  - | Editora |  	Editec |
		
| Objeto  |  Atributos  |  Valor  |
| ------------------- | ------------------- | ------------------- |
|  Funcionario | Nome | Tiririca |
|  - |  	Cargo |  	Humorista |
|  - | Salario |  	R$ 5000,00 |		 


**Métodos** definem as habilidades dos objetos. Um método em uma classe é apenas uma definição. A ação só ocorre quando o método é invocado através do objeto.

| Objeto  |  Método  |
| ------------------- | ------------------- |
|  Cachorro | Acordar, Comer, Beber, Latir, Dormir. |
|  Pessoa |  	Acordar, Correr, Estudar, Trabalhar, Falar, Gritar, Emocionar. |
|  Rádio | Ligar, Tocar, Sintonizar, ??? | 	
|  Telefone | 	Discar, Tocar, ??? | 

REVISÃO:

O coletivo de lobos é alcatéia, de peixes cardume, de pessoas é população e de objetos é classe.

No Visual Studio por exemplo os objetos tem propriedades ou atributos, métodos(ação) e eventos (reação).

Um Form é um objeto que possui atributos e métodos. O mesmo acontece com um Button que executa um evento quando é clicado, um Label, ou um TextBox.

Um método de um objeto se refere àquilo que o objeto faz, ao seu funcionamento, ao seu comportamento, ou seja, a uma ação deste objeto.

Exemplo:

| Classe  |  Objeto  |  Atributos  |  Métodos  |
| ------------------- | ------------------- | ------------------- | ------------------- |
|  Eletronicos | Televisao |  Imagem |  Ligar |
|  - | Radio |  Som |  Ligar |
|  - | 	- |  Antena |  Sintonizar |

			
 	 


#Material original: http://www.cpscetec.com.br/adistancia/poovb2008/Aula01/aula01.html
