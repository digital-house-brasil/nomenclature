![](./hd-header.png)

## Front-End | Convenções de nomenclatura

<details>
  <summary>1. Introdução</summary>

  > Se você estuda programação, provavelmente se vê a todo momento nomeando coisas, como variáveis, classes, métodos, funções e muito mais. Mas, afinal, será que existe alguma convenção para ajudar nesse processo de nomeação?

  > Há diversas maneiras de aplicar boas práticas no seu código, uma delas é a convenção de nomenclatura, que são recomendações para nomear identificadores ajudando a tornar seu código mais limpo e fácil de compreender, mantendo um padrão para o leitor e até mesmo podendo fornecer informações sobre a função do identificador.

  > Agora, vamos conhecer os quatro tipos mais comuns de convenções de nomenclatura para combinar palavras em uma única string. Bora lá?

</details>

<details>
  <summary>2. Camel Case</summary>

  > Camel case deve começar com a primeira letra minúscula e a primeira letra de cada nova palavra subsequente maiúscula:

  ```js
  const nomeCompleto = 'João da Silva';
  const valorFinal = 100;
  ```  
</details>

<details>

  <summary>3. Pascal Case</summary>
  
  > Pascal case deve começar com a primeira letra maiúscula e a primeira letra de cada nova palavra subsequente maiúscula:

  ```js
  const NomeCompleto = 'João da Silva';
  const ValorFinal = 100;
  ```
   
</details>

<details>
  <summary>4. Kebab Case</summary>
  
  
  > Kebab case utiliza o traço para combinar as palavras. Quando o kebab case está em caixa alta, ele é chamado de “screaming kebab case”:

  ```js
  const nome-completo = 'João da Silva';
  const valor-final = 100;
  ```

</details>


<details>
  <summary>5. Snake case</summary>

  > Em snake case, conhecido também como “underscore case”, utilizamos underline no lugar do espaço para separar as palavras. Quando o snake case está em caixa alta, ele é chamado de “screaming snake case”:

  ```js
  const nome_completo = 'João da Silva';
  const valor_final = 100;
  ```
  
</details>

<details>
  <summary>6. Convenções do JS</summary>

  - camelCase para variáveis, constantes, funções e métodos;
  - PascalCase para classes.

  ```js
  const calculoDoImc = (altura, peso) => {
    return peso / (altura * altura);
  }

  const resultadoImc = calculoDoImc(1.75, 80);
  ```
  
</details>

###### tags: `Frontend` `nodeJS` `JavaScript` `camelCase` `variáveis` `constantes` `funções` `métodos` `pascalCase` `snakeCase` `kebabCase`  `convenções` `nomenclatura`
