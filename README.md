

**1. Arquivos**

- Todos os arquivos de código-fonte terão um comentário PHPdoc inicial.

Exemplo:

    <?php
    /**
     * Classe para abstração de funções
     */
     ...

- A primeira linha de código no arquivo de código-fonte, após o PHPdoc inicial, terá a instrução de importações de pacotes seguidas por quaisquer instruções de importação.
    
    Exemplo:
    
    	...
    	use Zend\Stdlib\Hydrator;
        ...
    
    
- O nome do arquivo fonte deve ser o mesmo nome da classem indicando o que o mesmo faz.  Exemplo: CadastroController.php.


**2. Métodos, variáveis e constantes**
 
- Os nomes de métodos devem ser verbos e devem utilizar letras maiúsculas e minúsculas, cada palavra começando com letra maiúscula, exceto a primeira letra que deve ser minúscula (por exemplo, getRepository).
- Os nomes de variáveis devem indicar o que elas representam, devem utilizar letras maiúsculas e minúsculas e cada palavra deve começar com letra maiúscula, exceto a primeira letra que deve ser minúscula (por exemplo, $dadosDentista). As variáveis devem começar com letras. Variáveis de um único caractere (por exemplo, i, j ou k) devem ser evitadas e utilizadas somente para variáveis temporárias (por exemplo, em uma instrução for).
- Tente tornar todas as variáveis de classe não públicas e acessíveis apenas por meio de métodos.
- As constantes devem ser escritas com todas as letras em maiúsculas, com palavras separadas por um sublinhado (por exemplo, HORAS_CONSULTA).


**3. Classes**
 
- Os nomes de classes e de interfaces devem ser substantivos e utilizar letras minúsculas e maiúsculas, começando cada palavra com letra maiúscula e ter o mesmo nome do arquivo fonte (por exemplo: CadastroController).
- Listar variáveis da seguinte maneira: variáveis estáticas, variáveis de instancia (públicas, protegidas, sem acesso especificado e, então, privadas).
- Listar métodos da seguinte maneira: construtores e. depois, métodos (os métodos devem estar agrupados pela funcionalidade, não pelo escopo).

**4. Padrões gerais**

- Tente inicializar variáveis locais onde elas são declaradas.
- Evite linhas com mais de 80 caracteres.
- Cada linha deve conter apenas uma instrução.
- As instruções if-else, for, while, do e switch devem usar sempre chaves.
- Os nomes das classes devem fazer referência total ao seu objeto (atributos e métodos contidos dentro da classe).
