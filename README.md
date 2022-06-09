# Consulta2
POO:
C - CONFIAVEL
O - OPORTUNO
M - MANUTENIVEL
E - EXTENSIVEL
R - REUTILIZAVEL
N - NATURAL

Polimorfismo é o princípio pelo qual duas ou mais classes derivadas de uma mesma superclasse podem invocar métodos que têm a mesma identificação (assinatura) mas comportamentos distintos, especializados para cada classe derivada, usando para tanto uma referência a um objeto do tipo da superclasse.
O Polimorfismo pode ser Estático ou Dinâmico. O primeiro é também conhecido como
sobrecarga ou overloading, é representado com o nome do método igual e
argumentos diferentes. A decisão do método a ser chamado é tomada em tempo de
compilação de acordo com os argumentos passados. Professor, o que você quer dizer
com argumentos diferentes?
Ora, pode ser uma diferença no tipo do argumento ou quantidade de argumentos.
O segundo é também conhecido como sobrescrita, redefinição ou overriding. Ele está
associado ao conceito de herança e é representado com o nome e argumentos do
método iguais. A subclasse redefine o método da superclasse e a decisão do método
a ser chamado é tomada em tempo de execução. 

Correto:
Um objeto eh uma construcao de sogtware que encapsula estado e comportamento
Uma classe define os atributos e comportamentos compartilhados por um tipo de objeto
Em uma linguagem POO pura, tudo eh um objeto, desde os tipos mais basicos
Uma variavel interna eh um calor mantido dentro do objeto
Atributos sao as caracteristicas de uma classe visiveis externamente
O estado de um objeto eh o significado combinado das variaveis internas do objeto
Classes sao tipos abstratos de dados
Objetos sao instancias de uma classe
Subclasse eh uma classe definida por meio de outra classe
O compilador fornece um construtor padrao sem parametros em qualquer classe que nao inclui explicitamente um construtor
A heranca permite basear uma nova classe na definicao de outra classe
Com o mecanismo de heranca, eh possivel estabelecer relacionamentos "eh um" entre classes
Utilizar acesso protected oferece um nivel intermediario entre public e private
A especializacao permite que voce remova da classe filha comportamento e atributos
Os metodos de acesso privado nao sao herdados pela filha
O polimorfismo permite que um unico nome expresse muitos comportamentos diferemtes. Um tipo de polimorfismo eh sobrecarga, que permite que possa ser declarado o mesmo metodo varias vezes, sendo que cada declaracao difere simplesmente no numero e tipo de argumentos
Faz parte da assinatura de um metodo: seu nome; a quantidade de parametros; os tipos dos seus parametros

Niveis de acesso POO:
publico
privado
protegido - acesso apenas para aquele objeto e suas subclasses

3 pilares:
Encapsulamento - Protecao de atributos e operacoes de classes, fazendo com que estas se comuniquem com o meio externo por meio de suas interfaces
Heranca
Polimorfismo - Conceito que permite escrever programas que processam objetos que compartilham a mesma superclasse como se todos fossem objetos dessa superclasse
Polimorfismo - "de inclusao", "parametrico", "sobrecarga", "sobreposicao"

Atributo - Caracteristicas de uma classe que eh visivel
Classe - Define os atributos e comportamentos comuns
Comportamento - Acao executada por um objeto
Dominio - Espaco onde o problema reside
Objeto - Construcao de software que encapsula estado e comportamento
Objeto - Instanciacao de uma classe
Construtor - Metodos usados para inicializar objetos durante a instanciacao
Acessor - Metodos que dao acesso aos dados internos
Mutante - Metodos que permitem que se altere o estado de um objeto
Tipos - Define as diferentes especies de valores que podem ser usados
Interface - Define o que uma entidade pode fazer com o objeto
Abstracao - Representar uma unidade incluindo apenas seus atributos mais relevantes
Metodo abstrato - declarado, mas nao implementado
Sobrecarga - Quando se utiliza, dentro de uma mesma classe, um mesmo nome de metodo para muitos metodos diferentes

Incorreto: 
Uma classe eh uma instancia de um objeto
Comportamento sao as caracteristicas de uma classe invisiveis externamente
Atributos sao subprogramas que definem as operacoes em objetos de uma classe
Um construtor pode ter um nome diferente de sua classe
Se uma classe nao incluir um construtor, as variaveis de instancia nao sao inicializadas
Nao existe conceito de construtor na linguagem JAVA
Nao se pode sobrepor um comportamento de uma superclasse em uma subclasse
Os membros private de uma superclasse sao herdados pelas suas subclasses
Um metodo public da superclasse pode tornar-se um metodo protected ou private na subclasse
Um metodo protected da superclasse pode tornar-se um metodo private da subclasse
A superclasse herda os atributos e comportamentos da subclasse
Protegido eh o nivel de acesso onde se restringe o acesso a classe atual e as suas filhas









1. A análise e o projeto orientados a objetos têm como meta identificar o melhor conjunto de objetos para descrever um sistema de software. O funcionamento desse sistema se dá por meio do relacionamento e troca de mensagens entre esses objetos. Na programação orientada a objetos, implementa-se um conjunto de classes que definem os objetos presentes no sistema de software. Com relação à herança múltipla é correto afirmar
(ANO: 2009 BANCA: TJPR ÓRGÃO: TJ-PR PROVA: INFORMÁTICA - ANALISTA DE SISTEMAS):

O usuário não necessita conhecer detalhes do funcionamento interno do sistema para poder utilizá-lo

É o princípio pelo qual duas ou mais classes derivadas de uma mesma superclasse podem invocar métodos que têm a mesma identificação mas comportamentos distintos

As mensagens enviadas a um objeto podem mudar o valor de um ou mais atributos

Possibilita que uma classe herde atributos e métodos de duas ou mais classes **CORRETA**

2. Controlar a complexidade pela ênfase em características essenciais e pela supressão de detalhes em orientação a objetos é denominado(a)
(ANO: 2009 BANCA: TJPR ÓRGÃO: TJ-PR PROVA: INFORMÁTICA - ANALISTA DE SISTEMAS):

abstração **CORRETA**

herança

analogia

visibilidade

3. Na orientação a objetos, o conceito que garante que nenhum acesso direto é concedido aos dados é atribuído por meio do(a)
(FUNCAB - 2013 - CODATA - Auxiliar de Informática - Apoio ao Usuário ):

polimorfismo. 

herança.

agregação.

abstração.

encapsulamento. **CORRETA**

4. Assinale a opção correta quanto à abordagem conceitual de abstração sob o paradigma de programação orientada a objetos.
(CESPE - 2013 - TRE-MS - Técnico Judiciário - Programação de Sistemas)

As abstrações, idealmente, caracterizam-se por não serem grandes demais em comparação aos módulos, pois senão elas se tornam multifuncionais e de difícil compreensão. Como consequência, a abstração deve ser implementada apenas no nível de estruturas de dados necessários para se atingir o objetivo pretendido.

Abstração consiste em uma linguagem puramente lógica. A motivação para isso veio em parte da vontade de se reconciliar o uso da lógica como uma linguagem declarativa de representação do conhecimento com a representação procedimental do conhecimento.

Abstração é uma linguagem declarativa que permite acesso à base de dados mediante a utilização da teoria dos conjuntos e da álgebra relacional como fundamento de seu funcionamento.

Abstração é um conceito segundo o qual o sistema ou software é dividido em partes distintas. Compõe o ferramental necessário para um programa mais legível com uma melhor manutenção e melhor desempenho por meio da programação orientada a objetos.

Abstração é a habilidade de se concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais. Em modelagem orientada a objetos, uma classe é uma abstração de entidades existentes no domínio do sistema de software. **CORRETA**

5. Na orientação a objetos, a sobrecarga é utilizada por meio do conceito de:
(FUNCAB - 2013 - CODATA - Auxiliar de Informática - Apoio ao Usuário)

encapsulamento.

herança.

agregação.

polimorfismo. **CORRETA**

abstração.

6. O trecho de código mostrado abaixo é um exemplo de encapsulamento.
(CESPE - 2013 - TRT - 10ª REGIÃO (DF e TO) - Analista Judiciário - Tecnologia da Informação)

public class Animal
{
    public String nome;
    public String tipo;
    public String cor;

    public String getNome(){ return nome; }
    public void setNome(String nome){ this.nome = nome; }
    public String getTipo(){ return tipo; }
    public void setTipo(String tipo){ this.tipo = tipo; }
    public String getCor(){ return cor; }
    public void setCor(String cor){ this.cor = cor; }
}
C) Certo 
E) Errado **CORRETA**

7. No contexto de programação orientada a objetos, considere as afirmativas abaixo.
(FCC - 2012 - TJ-RJ - Analista Judiciário - Análise de Sistemas)

Objetos são instâncias de classes. **CORRETA**

Herança é uma relação entre objetos.

Mensagens são formas de executar métodos. **CORRETA**

Classes são apenas agrupamentos de métodos.

Ocorre herança múltipla quando mais de um método é herdado.

Herança é uma relação entre classes. **CORRETA**

Está correto o que se afirma APENAS em

I, III e IV.

I, III e VI. **CORRETA**

III, IV e VI.

II, III e V.

II, IV e V.

8. Sobre orientação a objetos é correto afirmar:
(FCC - 2012 - TRF - 2ª REGIÃO - Técnico Judiciário - Informática)

Na hierarquia de classes, se superclasse é uma generalização de subclasses, pode-se inferir que a subclasse é uma especialização de superclasse. **CORRETA**

Numa árvore genealógica de classes, a classe mais baixa herda os atributos e métodos somente da superclasse no nível imediatamente acima.

As variáveis de uma classe só podem ser alteradas por métodos definidos nos seus objetos.

O polimorfismo se caracteriza quando, para mensagens distintas, objetos diferentes responderem ou agirem de forma idêntica.

Os objetos de uma classe são idênticos no que se refere à sua interface e ao seu estado.


10. A Análise e Projeto Orientado a Objetos oferece suporte a um recurso que apresenta as características listadas a seguir.
(CONSULPLAN - 2012 - TSE - Analista Judiciário - Análise de Sistemas)

Separa os aspectos externos de um objeto, que são acessíveis a outros objetos, dos detalhes internos da implementação, que estão escondidos de outros objetos.

Evita que partes de um programa se tornem tão interdependentes que uma pequena mudança tenha grandes efeitos em cascata.

Pode-se mudar a implementação de um objeto sem afetar as aplicações que o utilizam.

Esse recurso denomina-se

encapsulamento. **CORRETA**

compartilhamento.

especialização.

generalização.

11. Na orientação a objetos
(FCC - 2012 - TST - Analista Judiciário - Análise de Sistemas)

a herança permite que os membros de uma classe, chamada de classe-mãe, possam ser reaproveitados na definição de outra classe, chamada de classe-filha. Esta classe-filha tem acesso aos membros públicos e protegidos da classe-mãe. O polimorfismo, associado à herança, permite que métodos abstratos definidos em uma classe abstrata sejam implementados nas classes-filhas, podendo estes métodos, nas classes-filhas, apresentar comportamentos distintos.  **CORRETA**

atributos e métodos podem ser reaproveitados através da herança, quando uma subclasse herda as características de uma superclasse. Uma subclasse pode ter acesso aos membros de uma superclasse, independente do modificador atribuído. O polimorfismo é um recurso que permite a uma subclasse reimplementar os métodos herdados de uma superclasse, sendo este método abstrato ou não.

a herança e o polimorfismo são complementares, ou seja, devem ser aplicados em conjunto. A herança existe a partir de classes abstratas que contêm atributos e métodos abstratos. O polimorfismo obriga que as classes-filhas implementem os métodos e atributos desta classe-mãe. O acesso aos atributos da classe-mãe independe do modificador utilizado.

o conceito de herança estabelece que uma classe possa aproveitar a implementação, definições dos atributos e métodos de uma classe-base. A classe-filha pode ter acesso aos métodos e atributos públicos e protegidos da classe-base. O polimorfismo é aplicado ao caso em que existe a necessidade de implementar métodos sobrecarregados, nos quais a classe-filha necessita implementar dois métodos com o mesmo nome e parâmetros diferentes.

o polimorfismo é uma técnica que permite um objeto nascer a partir do uso de sobrecarga de construtores de uma classe, ou seja, o polimorfismo permite que um objeto possa ser instanciado de diferentes maneiras. A herança permite que uma classe sirva de base para que outras classes sejam implementadas. Entretanto, os membros com modificadores públicos da classe-base podem ser acessados pela classe-filha.

12. Sobre a orientação a objeto é correto afirmar:
(FCC - 2012 - TCE-AM - Analista de Controle Externo - Tecnologia da Informação)

Herança permite o reaproveitamento de atributos e métodos, porém, isso não altera o tempo de desenvolvimento, não diminui o número de linhas de código e não facilita futuras manutenções.

Em uma aplicação que utiliza herança múltipla, uma superclasse deve herdar atributos e métodos de diversas subclasses. Todas as linguagens de programação orientadas a objeto permitem herança múltipla.

O polimorfismo associado à herança trabalha com a redeclaração de métodos previamente herdados por uma classe. Esses métodos, embora semelhantes, diferem de alguma forma da implementação utilizada na superclasse, sendo necessário, portanto, reimplementá-los na subclasse.  **CORRETA**


A visibilidade protegida é representada pelo símbolo til (~) e significa que somente os objetos da classe detentora do atributo ou método poderão enxergá-lo ou utilizá-lo.

Em uma relação de herança é possível criar classes gerais, com características compartilhadas por muitas classes. Essas classes não podem possuir diferenças.

13. Em relação a projetos orientados a objetos, a restrição de multiplicidade
(FCC - 2012 - TJ-PE - Técnico Judiciário - Programador de Computador)

garante que uma classe seja utilizada na composição de múltiplos objetos.

descreve a quantidade de objetos que podem ser instanciados para uma determinada classe.

indica o número de instâncias de uma classe que participa da relação com as instâncias de outra classe.  **CORRETA**

expressa a possibilidade de composição de múltiplos atributos e métodos para um objeto.

reduz a complexidade, pois permite tratar múltiplos objetos como um único objeto.

14. No contexto de Programação Orientada a Objetos (OOP), sobre a relação de agregação e composição, ou relação todo-parte, considere:
(FCC - 2012 - TRT - 11ª Região (AM) - Técnico Judiciário - Tecnologia da Informação)

A relação de agregação expressa o ato ou resultado de formar um objeto usando outros objetos como seus componentes.

Na relação de agregação, as partes só existem enquanto o todo existir.

Na relação de composição, as partes são independentes da existência do todo.

Está correto o que se afirma em

I, apenas.  **CORRETA**

II, apenas.

II e III, apenas.

III, apenas.

I, II e III.

15. Na orientação a objetos, é um recurso que serve para inicializar os atributos e é executado automaticamente sempre que um novo objeto é criado:
(FCC - 2011 - NOSSA CAIXA DESENVOLVIMENTO - Analista de Sistemas)

método.

polimorfismo.

interface.

classe.

construtor.  **CORRETA**

16. A respeito da orientação a objetos, julgue os itens subsequentes.
(CESPE - 2011 - Correios - Analista de Correios - Analista de Sistemas - Desenvolvimento de Sistemas)

Na linguagem de programação Java, um método público da superclasse somente pode ser anulado por um método público da subclasse.

C) Certo 
E) Errado  **CORRETA**

17. Em relação aos conceitos fundamentais da orientação a objetos, o mecanismo pelo qual um objeto utiliza os recursos de outro, podendo ele assumir os tipos "usa um" ou "parte de", denomina-se
(FCC - 2011 - TRE-AP - Técnico Judiciário - Programação de Sistemas)

Encapsulamento.

Herança.

Método.

Polimorfismo.

Associação.  **CORRETA**

18. Em relação às assertivas abaixo, relacionadas à programação orientada a objetos,
(COPEVE-UFAL - 2011 - UFAL - Analista de Tecnologia da Informação)

Uma classe abstrata deve necessariamente possuir ao menos um método abstrato.

As hierarquias de generalização/especialização agrupam características comuns a várias classes em classes mais gerais, conhecidas como superclasses.

Em Java, o modificador final pode ser utilizado para indicar classes folha na hierarquia de generalização/especialização, isto é, classes que não podem ter subclasses herdando delas.

Em Java, o modificador static é utilizado para representar objetos que devem ser armazenados em disco rígido.

verifica-se que

apenas I e IV são verdadeiras.

apenas I, II e III são verdadeiras.

apenas III é verdadeira.

apenas III e IV são verdadeiras.

apenas II e III são verdadeiras.  **CORRETA**

19. Polimorfismo é a
(ESAF - 2010 - SUSEP - Analista Técnico - Prova 2 - Tecnologia da Informação)

utilização múltipla de programas em análise orientada a objetos.

habilidade de uma única operação ou nome de atributo ser definido em mais de uma classe e assumir diferentes implementações em cada uma dessas classes.   **CORRETA**

habilidade de um programador em desenvolver aplicações e caracterizar objetos com múltiplos atributos.

utilização de uma classe com diferentes formatos em programas com definição de objetos e atributos.

habilidade de uma única variável ser utilizada em diferentes programas orientados a objetos.   

20. Sobre herança na orientação a objetos, é correto afirmar:
(FCC - 2010 - TRF - 4ª REGIÃO - Analista Judiciário - Tecnologia da Informação)

O conjunto de objetos representado por uma subclasse é, em geral, maior que o conjunto de objetos representado por sua superclasse.

Cada objeto de subclasse é um objeto de sua subclasse.

Um problema com herança é que uma subclasse pode herdar métodos que ela não necessita ou que não deveria ter.  **CORRETA**

Todo relacionamento de classe é um relacionamento de herança.

Os objetos de superclasse podem ser tratados como objetos de suas subclasses.

21. Sejam A e B duas classes em um programa orientado a objetos. Se A é de B, então objetos da classe A _ atributos que objetos da classe B.
(FEPESE - 2010 - UDESC - Analista de Sistemas)

Assinale a alternativa que completa correta e sequencialmente as lacunas do texto.

subclasse ; podem possuir mais  **CORRETA**

subclasse ; não podem possuir mais

superclasse ; possuem necessariamente mais

superclasse ; possuem necessariamente menos

subclasse ; possuem necessariamente menos

22. Sobre a orientação a objetos, é correto afirmar:
(FCC - 2010 - TRF - 4ª REGIÃO - Analista Judiciário - Tecnologia da Informação)

Variáveis e métodos de classe pública (public) existem e podem ser utilizados, mesmo se nenhum objeto dessa classe tiver sido instanciado.

Os modificadores de acesso public, private e protected controlam o acesso apenas aos métodos de uma classe.

É possível criar vários construtores sobrecarregados em uma classe para permitir que objetos dessa classe sejam inicializados de diferentes maneiras.  **CORRETA**

Um construtor invocado sem argumentos inicializa o objeto, mas causa um erro em tempo de execução, pois todo construtor de classe deve receber pelo menos um parâmetro.

Ao implementar um método de uma classe, devem ser utilizados os métodos set e get da classe para acessar apenas os dados públicos (publics) da classe.

23. Em conformidade com a metodologia orientada a objetos, com a finalidade de evitar que partes de um programa se tornem tão independentes que uma pequena alteração tenha grandes efeitos em cascata, é aplicado um recurso que separa os aspectos externos e acessíveis de um objeto dos detalhes internos de implementação.
(FGV - 2010 - SEAD-AP - Auditor da Receita do Estado - Prova 2)

Esse recurso utiliza um princípio da Orientação a Objetos que propõe ocultar determinados elementos de uma classe das demais classes. O objetivo ao colocar uma proteção ao redor é prevenir contra os efeitos colaterais indesejados ao ter essas propriedades modificadas de forma inesperada.

Este recurso é conhecido por:

a) coesão. 
b) acoplamento. 
c) polimorfismo. 
d) modularidade. 
e) encapsulamento.  **CORRETA**

24. Na orientação a objetos, ao nível de classe, são definidos os
(FCC - 2009 - SEFAZ-SP - Agente Fiscal de Rendas - Tecnologia da Informação - Prova 3)

atributos e os valores dos atributos.

atributos e a invocação das operações.

atributos e os métodos.  **CORRETA**

métodos e os valores dos atributos.

métodos e a invocação das operações.

25. Analise as seguintes afi rmações relacionadas a Orientação a Objetos:
(ESAF - 2008 - Prefeitura de Natal - RN - Auditor do Tesouro Municipal - Tecnologia da Informação - Prova 2)

O acesso a atributos públicos só pode ser feito a partir dos métodos membros da classe derivada.

A visibilidade dos atributos pode ser pública, privada ou protegida.  **CORRETA**

Os métodos protegidos podem ser acessados a partir dos métodos da classe do qual é membro.  **CORRETA**

Diferentemente dos atributos privados, o acesso a métodos privados pode ser feito a partir dos métodos membros de qualquer classe.

Indique a opção que contenha todas as afi rmações verdadeiras.

I e II.

II e III.  **CORRETA**

III e IV.

I e III.

II e IV.

26. São dois tipos de relacionamento todo-parte:
(FCC - 2008 - TRT - 18ª Região (GO) - Analista Judiciário - Tecnologia da Informação)

agregação e composição.  **CORRETA**

generalização e composição.

generalização e especialização.

composição e dependência.

especialização e agregação.

27. Considere as classes abaixo:
(CESGRANRIO - 2008 - Petrobrás - Analista de Sistemas Júnior - Engenharia de Software)

public class Produto {
    private Fabricante fabricante;

    public Fabricante getFabricante(){ return fabricante; }
    public void setFabricante(Fabricante fabricante){ this.fabricante = fabricante; }
}

public class Fabricante {
    private List<Produto> produtos;

    public Fabricante(){
        this.produtos = new ArrayList<>();
    }

    public List<Produto> getProdutos(){ return produtos; }
}
Assinale o diagrama de classe que expressa corretamente a implementação mostrada acima, em Java, das classes Produto e Fabricante, bem como da associação entre as mesmas

produto fabricante1.jpg

produto fabricante2.jpg

produto fabricante3.jpg

produto fabricante4.jpg

produto fabricante5.jpg

28. Considere: Casas ABC Ltda., Empresa e Nome da Empresa.
(FCC - 2008 - TCE-AL - Programador)

Na orientação a objetos, os itens acima representam, respectivamente,

atributo, classe e objeto.

classe, atributo e objeto.

classe, objeto e atributo.

objeto, atributo e classe.

objeto, classe e atributo.  **CORRETA**

29. Que característica NÃO é fundamental em uma linguagem de programação orientada a objeto?
(CESGRANRIO - 2007 - EPE - Analista de Gestão Corporativa Júnior - Área Tecnologia da Informação)

Criação de classes.

Encapsulamento.

Herança múltipla.  **CORRETA**

Herança simples.

Instanciação de objetos.

30. Em programação orientada a objetos, é correto afirmar que herança múltipla:
(CESGRANRIO - 2006 - DNPM - Técnico Administrativo - Especialidade - Informática)

é a instância de uma classe abstrata.

define no máximo uma classe pai.

permite que uma classe herde atributos e métodos de duas ou mais classes.

ocorre quando uma classe é a instância de vários objetos.

significa o mesmo que polimorfismo.

31. Em algumas linguagens de Programação Orientadas a Objetos, como por exemplo Java, ao se derivar uma classe a partir de uma classe base, a classe base pode ser herdada como public, protected ou private. Quando a derivação é do tipo public, os membros
(ESAF - 2006 - CGU - Analista de Finanças e Controle - Área - Tecnologia da Informação - Prova 3)

public e protected da classe base tornam-se, respectivamente, membros public e protected da classe derivada.

private da classe base serão acessados e utilizados diretamente a partir da classe derivada.

public e protected da classe base tornam-se membros public da classe derivada.

public e protected da classe base tornam-se membros protected da classe derivada.

public, protected e private da classe base tornam-se, todos, membros private na classe derivada, independentemente do tipo de herança utilizada.

32. Na programação orientada a objetos, o encapsulamento
(ESAF - 2005 - Receita Federal - Auditor Fiscal da Receita Federal - Área Tecnologia da Informação - Prova 3)

é a base de toda a abordagem dessa metodologia de programação e diz-se que um dado está encapsulado quando envolvido por código de forma que só é visível na rotina onde foi criado; o mesmo acontece com uma rotina, que sendo encapsulada, suas operações internas são invisíveis às outras rotinas.

pode ser entendido como sendo um conjunto de instâncias criadas a partir de um outro conjunto de instâncias com características semelhantes.

é defi nido como sendo uma técnica que permite a um código possuir "vários comportamentos" ou produzir "vários comportamentos".

possibilita a criação de uma nova classe de modo que essa classe (denominada subclasse, classe-filha ou classe derivada) herda todas as características da classe-mãe (denominada superclasse, classe base ou classe primitiva); podendo, ainda, a classe-filha possuir propriedades e métodos próprios.

é considerado como a habilidade de modelar características do mundo real do problema que o programador esteja tentando resolver.

33. Classes e objetos são dois conceitos-chave da programação orientada a objetos. Com relação a estes conceitos, é correto afirmar que
(ESAF - 2005 - Receita Federal - Auditor Fiscal da Receita Federal - Área Tecnologia da Informação - Prova 3)

se pode definir uma classe como um pacote de software, de modo que, com a herança, um objeto define comportamento e forma-padrão para a construção de uma nova classe abstrata.

uma classe é uma descrição de um ou mais objetos por meio de um conjunto uniforme de atributos e serviços. Além disso, pode conter uma descrição de como criar novos objetos na classe.

uma classe é uma abstração de alguma coisa no domínio de um problema ou na sua implementação, refletindo a capacidade de um sistema para manter informações sobre ela, interagir com ela ou ambos.

um objeto é um protótipo que defi ne os atributos e métodos comuns a todas as classes de um certo tipo.

o polimorfismo caracteriza-se pela possibilidade de objetos distintos possuírem métodos com nomes idênticos, mas com implementações distintas.

34. A orientação a objetos foi adotada como sendo o paradigma oficial da maioria das linguagens de programação mais recentes. Tomando por base os conceitos da orientação a objetos, atribua V (verdadeiro) ou F (falso) às afirmativas a seguir.
(COPS-UEL - 2013 - AFPR - Analista - Tecnologia da Informação)

Na programação orientada a objetos, é correto dizer que o comportamento de um objeto afeta o seu estado, assim como o seu estado afeta o seu comportamento.

O principal objetivo de um método Acessor (Acessador ou Getter) é o de alterar o valor de um atributo privado.

A sobrecarga de métodos ocorre quando um método é encontrado, tanto na superclasse quanto na subclasse, com o mesmo nome, tipo de retorno e número de parâmetros.

Uma classe pode herdar variáveis de instância e métodos de uma superclasse abstrata.

A herança permite garantir que todas as classes agrupadas sob um certo supertipo tenham todos os métodos que o supertipo tem. Assinale a alternativa que contém, de cima para baixo, a sequência correta.

A alternativa com a sequência correta é:

V, V, F, F, V.

V, F, V, F, F.

V, F, F, V, V.

F, V, V, V, F.

F, V, V, F, V.

35. Sobre programação orientada a objetos analise as afirmativas:
A POO (programação orientada a objetos) encapsula dados (atributos) e métodos (comportamento) em objetos.

Os objetos têm a propriedade de ocultar informações. Isto significa que, embora os objetos possam saber se comunicar uns com os outros, através de interfaces bem-definidas, os objetos, normalmente, não têm permissão para conhecer como os outros objetos são implementados.

O conceito de Encapsulamento (ocultamento de informação) é baseado na restrição do escopo ou visibilidade da informação, utilizada em projetos baseados em objetos, para obter melhor legibilidade, manutenibilidade e reusabilidade do software.

O método construtor de uma classe Java é um método especial, que possui o mesmo nome da classe e é executado quando a classe é instanciada. Esse método não permite a sua sobrecarga, ou seja, não podemos criar vários métodos construtores, mesmo que contenham parâmetros diferentes.

Estão corretas as afirmativas:

II, III e IV

I, II e IV

I, II e III

II e IV

I e IV

36. Na programação orientada a objetos com Java, os modificadores de acesso são padrões de visibilidade de acesso às classes, atributos e métodos. Um método com o modificador
(DPE/SP 2015 - Agente de Defensoria Pública - Área Programador - FCC)

default pode ser acessado de dentro da própria classe, de qualquer classe do pacote e de subclasses que herdam da classe que contém o método.

public pode ser acessado somente a partir de classes que estão no mesmo pacote.

protected pode ser acessado somente de dentro da própria classe ou de classes que estão no mesmo pacote.

private pode ser acessado somente de dentro da própria classe.

static pode ser acessado a partir de qualquer classe da aplicação.




