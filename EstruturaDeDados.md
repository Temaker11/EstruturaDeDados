# Objetivos

  - Apresentação e modelagem de estruturas 
  - Conteitos fundamentais
  - JavaScript


##  Por que JavaScript como linguagem para este curso? 

  - Linguagem da WEB 
  - Linguagem de alto nível
  - Foco no entendimento e não na construção 

### Por que estrutura de dados?

  - Organizar os dados da aplicação 
  - Entender estruturas para melhor tomada de decisão 
  - Escrever melhores algoritimos 
  - Eficiência 
  - Algumas empresas usam como requisito

# Alguns desafios diários de uso de dados são:

  - Entendimento de como estão nossos dados na aplicação 
  - Criar listas ( ordenadas, não ordenadas )
  - Repetição ou não dos dados dentro da estrutura
  - Organização os dados pelo par identificador + valor 

# O que é estrutura de dados? 


    Uma maneira de organizar e ordenar informações como textos, números, booleanos, etc e registrá-los na memória do computador.

  - Organizar dados (informações)
    - Textos, números, booleanos...
  - Como estão registrados na memória


  // Array 
  [1, 2, 3] // elementos 1, 2, 3

  // Object 
  { name: 'fulano', idade: 20} // elementos name: 'Fulano' elementos idade: 20

# Gerenciado dados

    Estrutura de dados tem a ver com a gestão das informações da aplicação

    Para esses gerenciamento, podemos dividir em 3 etapas: 

  1. Modelar a estrutura;

  2. Dar vida á estrutura(instanciar essas estrutura);

  3. Criar as funcionalidades dessas estruturas. 

    - Exemplo> inserir, excluir, buscar, ixibir, contar...

# Arrays 

  Array, vetor ou arranjo, é uma estrutura amplamente utilizaada e implementada em quase todasd as linguagens de programação 

  Uma das estruturas mais básicas, simpples de criar e utilizar. 

  ['a', 10, 'd', true] // total de 4 elementos 
  //0   1    2     3


# Características

  - Acesso pelo index 
  - Respeita a ordem de inserção dos elementos
  - Aceita valores duplicados
  - Dependendo do tamanho do Arrays, para encontrar e/ou deletar um elemento, será necessário um uso maior de performance.

# Arrays no JavaScript

  - São dinâmicos
  - Você poderá ter dados de diferentes tipos misturados dentro de um Array, Strings, Numbers, booleans, objetos, funções e até outros arrays.

  - Existem muitos métodos já implementados
    - push(), pop(), find(), filter() entre outros * 'Veja EstruturaDeDados.md'


# Matrix 

  Matriz ou Vetor multidimensional

  Significa que é um Array, dentro de outro array * 'Veja Matriz.js'

# Stack 

  A maneira mais facil de explicar Stack é imaginar uma pilha de livros 

  - Como uma pilha de livros.
   * linear, um após o outro 
   * pilha é o primeiro a sair 

  - LIFO: Last in First Out
    * O último elemento a entrar na pilha, aquele elemento do topa da pilha, é o primeiro a sair 

  * 'Veja StackCode.js'
   
## Stack no código 

  Métodos fundamentais 

    * push(): adicionar um elemento à pilha 
    * pop(): remover o elemento do topo da pilha 
    * peek(): obter o elemento do topo da pilha

  Outros métodos poderão ser implementados como size() para mostrar o tamanho da pilha.

# Queue

  Tradução de Queue é fila.

  Como uma fila em uma loja ou restaurante.

    * Linear
    * O primeiro a entrar na fila é o primeiro a sair 

  Conceitos

    * FIFO: First in First Out 
      - O primeiro elemento a entrar na fila, é o primeiro a sair dela 

    * Front(frente) é a referencia do primeiro elemento a entrar na fila

    * Back (fundo) é a referência do último elemento a entrar na fila | 'Veja Queue.js'

  Métodos fundamentais 
    * enqueue(): adicionar um elemento ao final da fila
    * dequeue(): remove o primeiro elemento a entrar na fila 

  Outros métodos poderão ser implementados como size() para mostrar o tamanho da fila ou front() para pegar o primeiro elemento da fila, dentre tantos outros 

  
 


