# Boas-vindas ao repositório do projeto Tryunfo!

Para realizar o projeto, atente-se a cada passo descrito a seguir e, se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ (PR) para colocar seus códigos.

# Termos e acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Conduta e do Manual da Pessoa Estudante da Trybe.

# Entregáveis

<details>
  <summary><strong>🤷🏽‍♀️ Como entregar</strong></summary><br />

Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://app.betrybe.com/course/4d67f5b4-34a6-489f-a205-b6c7dc50fc16/) e nosso [Blog - Git & GitHub](https://blog.betrybe.com/tecnologia/git-e-github/) sempre que precisar!

</details>

<details>
  <summary><strong>👨‍💻 O que deverá ser desenvolvido</strong></summary><br />

Neste projeto você vai desenvolver um jogo no estilo Super Trunfo! Ao utilizar essa aplicação uma pessoa usuária deverá ser capaz de:

- Criar um baralho com o tema livre;

- Adicionar e remover uma carta do baralho;

- Visualizar todas as cartas que foram adicionadas ao baralho;

- Jogar com o baralho criado.

### Protótipo do projeto

Você pode acessar um protótipo no link abaixo:

https://www.figma.com/file/psAYBgwjQ1pQqBe3wJvljt/Tryunfo

</details>

<details>
  <summary><strong>:memo: Habilidades</strong></summary><br />

Neste projeto, verificamos se você é capaz de:

- Ler o estado de um componente e usá-lo para alterar o que exibimos no browser

- Inicializar um componente, dando a ele um estado pré-definido

- Atualizar o estado de um componente

- Capturar eventos utilizando a sintaxe do React

- Criar formulários utilizando sintaxe JSX com as tags: `input`, `textarea`, `select`, `form`, `checkbox`

- Transmitir informações de componentes filhos para componentes pais via callbacks
</details>

<details>
  <summary><strong>🗓 Data de Entrega</strong></summary><br />
  
  * Este projeto é individual;
  * São `X` dias de projeto;
  * Data para entrega final do projeto: `DD/MM/YYYY - 14:00h`.

</details>

# Orientações

<details>
  <summary><strong>‼️ Antes de começar a desenvolver</strong></summary><br />

1. Clone o repositório

- Use o comando: `git clone git@github.com:tryber/sd-0x-project-tryunfo.git`.
- Entre na pasta do repositório que você acabou de clonar:
  - `cd sd-0x-project-tryunfo`

2. Instale as dependências

- `npm install`.

3. Crie uma branch a partir da branch `master`

- Verifique que você está na branch `master`
  - Exemplo: `git branch`
- Se não estiver, mude para a branch `master`
  - Exemplo: `git checkout master`
- Agora crie uma branch à qual você vai submeter os `commits` do seu projeto
  - Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
  - Exemplo: `git checkout -b joaozinho-sd-0x-project-tryunfo`

4. Adicione as mudanças ao _stage_ do Git e faça um `commit`

- Verifique que as mudanças ainda não estão no _stage_
  - Exemplo: `git status` (deve aparecer listada a pasta _joaozinho_ em vermelho)
- Adicione o novo arquivo ao _stage_ do Git
  - Exemplo:
    - `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
    - `git status` (deve aparecer listado o arquivo _joaozinho/README.md_ em verde)
- Faça o `commit` inicial
  - Exemplo:
    - `git commit -m 'iniciando o projeto x'` (fazendo o primeiro commit)
    - `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

5. Adicione a sua branch com o novo `commit` ao repositório remoto

- Usando o exemplo anterior: `git push -u origin joaozinho-sd-0x-project-tryunfo`

6. Crie um novo `Pull Request` _(PR)_

- Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-0x-project-tryunfo/pulls)
- Clique no botão verde _"New pull request"_
- Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
- Coloque um título para a sua _Pull Request_
  - Exemplo: _"Cria tela de busca"_
- Clique no botão verde _"Create pull request"_
- Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
- **Não se preocupe em preencher mais nada por enquanto!**
- Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-0x-project-tryunfo/pulls) e confira que o seu _Pull Request_ está criado

</details>

<details>
  <summary><strong>⌨️ Durante o desenvolvimento</strong></summary><br />

- Faça `commits` das alterações que você fizer no código regularmente

- Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

- Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  4. `git push -u origin nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

</details>

<details>
  <summary><strong>🤝 Depois de terminar o desenvolvimento (opcional)</strong></summary><br />

Para sinalizar que o seu projeto está pronto para o _"Code Review"_, faça o seguinte:

- Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas:

  - No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**;

  - No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**;

  - No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-0x`.

Caso tenha alguma dúvida, [aqui tem um video explicativo](https://vimeo.com/362189205).

</details>

<details>
  <summary><strong>🕵🏿 Revisando um pull request</strong></summary><br />

Use o conteúdo sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os _Pull Requests_.

</details>

<details>
  <summary><strong>🎛 Linter</strong></summary><br />

Para garantir a qualidade do código, vamos utilizar neste projeto os linters `ESLint` e `StyleLint`.
Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível
e de fácil manutenção! Para rodá-los localmente no projeto, execute os comandos abaixo:

```bash
  npm run lint
  npm run lint:styles
```

⚠️ **PULL REQUESTS COM ISSUES DE LINTER NÃO SERÃO AVALIADAS.
ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!** ⚠️

Em caso de dúvidas, confira o material do course sobre [ESLint e Stylelint](https://app.betrybe.com/course/real-life-engineer/eslint).

</details>

<details>
  <summary><strong>🛠 Testes</strong></summary><br />

Para avaliar o projeto iremos utilizar [React Testing Library](https://testing-library.com/docs/react-testing-library/intro) para execução dos testes.

Esse _framework_ de testes utiliza algumas marcações no código para verificar a solução proposta, uma dessas marcações é o atributo `data-testid` e faremos uso dele aqui.

Na descrição dos requisitos (logo abaixo) será pedido que seja feita a adição de atributos `data-testid` nos elementos _HTML_. Vamos a um exemplo para deixar claro essa configuração:

Se o requisito pedir "crie um botão e adicione o id de teste (ou `data-testid`) com o valor `my-action`, você pode criar:

```html
<button data-testid="my-action"></button>
```

ou

```html
<a data-testid="my-action"></a>
```

Ou seja, o atributo `data-testid="my-action"` servirá para o React Testing Library(RTL) identificar o elemento e dessa forma, conseguiremos realizar testes focados no comportamento da aplicação.

Em alguns requisitos, utilizamos o `getByRole` para poder selecionar os elementos de forma semântica. Portanto atente-se às instruções de cada requisito. Por exemplo, se o requisito pedir explicitamente um `button`, você deverá utilizar exatamente esse elemento.

Afim de verificar a solução proposta, você pode executar todos os testes localmente, basta executar:

```bash
npm test
```

### Dica: desativando testes

Especialmente no início, quando a maioria dos testes está falhando, a saída após executar os testes é extensa. Você pode desabilitar temporariamente um teste utilizando a função `skip` junto à função `it`. Como o nome indica, esta função "pula" um teste. Veja um exemplo:

```js
it.skip("Será validado se o campo de filtro por nome renderiza na tela", () => {
  render(<App />);
  const filterNameInput = screen.getByTestId(/name-filter/i);
  expect(filterNameInput).toBeInTheDocument();
});
```

![image](skip-image.png)

Uma estratégia é pular todos os testes no início e ir implementando um teste de cada vez, removendo dele a função `skip`.

Você também pode rodar apenas um arquivo de teste, por exemplo:

```bash
npm test 01.Form.test.js
```

ou

```bash
npm test 01.Form
```

Uma outra forma para contornar esse problema é a utilização da função `.only` após o `it`. Com isso, será possível que apenas um requisito rode localmente e seja avaliado.

```js
it.only("Será validado se o campo de filtro por nome renderiza na tela", () => {
  render(<App />);
  const filterNameInput = screen.getByTestId(/name-filter/i);
  expect(filterNameInput).toBeInTheDocument();
});
```

![image](only-image.png)

⚠️ **O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido. Então, não se assuste se isso acontecer, ok?**

</details>

<details>
  <summary><strong>:convenience_store: Desenvolvimento </strong></summary><br />

Você deve desenvolver uma aplicação em React com manipulação de estados em classes. Essa aplicação simulará um jogo de **Super Trunfo**, desde a criação das cartas do seu baralho até a funcionalidade de jogar.

Na renderização das cartas, sua aplicação deverá possuir três filtros de listagem de cartas: filtro por **nome**, por **raridade** e por **Super Trunfo**. Os filtros **nome** e **raridade** são acumulativos. O filtro **Super Trunfo** funciona de forma independente.

O tema do seu baralho é **livre**, então explore a sua criatividade! Mas use seu bom senso para a criação do seu baralho. Lembre-se do código de Conduta e do Manual da Pessoa Estudante da Trybe.

### :bulb: Renderização condicional :bulb:

Em alguns requisitos será necessária a utilização de renderização condicional. Você pode verificar a documentação do React [Renderização Condicional](https://pt-br.reactjs.org/docs/conditional-rendering.html).

Este comportamento é utilizado no React para renderizar, ou não, determinado componente de acordo com uma condição _booleana_.

No exemplo abaixo, o estado `isActiveButton` começa como `false`, e ao clicar no botão `Clique em mim!`, mudamos esse estado para `true`.
Na condição da renderização, quando o estado for `false`, renderizamos o parágrafo `Não está ativo!` e quando for `true`, renderizamos o parágrafo `Está ativo!`.

```js
import React from "react";

class Componente extends React.Component {
  constructor() {
    super();
    this.state = {
      isActiveButton: false,
    };
  }

  render() {
    const { isActiveButton } = this.state;
    return (
      <div>
        <button onClick={() => this.setState({ isActiveButton: true })}>
          Clique em mim!
        </button>
        {isActiveButton ? <p>Está ativo!</p> : <p>Não está ativo!</p>}
      </div>
    );
  }
}
```

No caso acima, temos duas possibilidades, ativo ou não, ou seja, duas renderizações. Mas se for de apenas uma renderização, como por exemplo, renderizar somente se o tamanho do _array_ for maior do que 0, podemos utilizar o `&&`:

```js
...
{
  array.length > 0 && <p>Array não vazio!</p>
}
...
```

</details>

<details>
  <summary><strong>:information_source: Informações Adicionais </strong></summary><br />

### Informações sobre o Super Trunfo

O Super Trunfo é um jogo de cartas que ficou muito popular no Brasil entre as décadas de 80 e 90, mas que faz bastante sucesso até hoje. Suas regras são bastante simples, por isso ele é considerado um jogo fácil de jogar. Apesar de ter regras simples, cada baralho de Super Trunfo pode ter um tema diferente, o que o torna um jogo bastante divertido.

Originalmente, o jogo de Super Trunfo é formado por um baralho de 32 cartas. Cada carta representa um item relacionado ao tema do jogo. Em cada carta também existe uma lista com características daquele item e cada característica possui um valor numérico.

Para começar o jogo, as cartas devem ser embaralhadas e divididas igualmente para cada participante. Em cada rodada cada pessoa pega somente a primeira carta do seu monte. Na primeira rodada uma pessoa escolhe qual característica quer comparar com as cartas das outras pessoas que estão jogando. Ganha quem tiver o maior número nessa característica. A pessoa que ganhou a rodada recebe as cartas das outras pessoas e escolhe qual característica quer comparar na próxima rodada. O jogo termina quando alguma pessoa tiver todas as cartas do baralho.

Em cada baralho existe uma (e somente uma) carta Super Trunfo. Essa carta ganha de todas as outras cartas do baralho, independentemente dos valores das características.

O jogo de Super Trunfo pode ser feito com praticamente qualquer tema, mas tradicionalmente os mais comuns são: carros, países, cidades ou animais.

### Criando, lendo, atualizando e apagando informações

Quando estamos lidando com informações, temos 4 operações principais: **Create** (criar), **Read** (ler), **Update** (atualizar) e **Delete** (apagar). Com essas quatro operações, formamos o acrônimo CRUD. Esse acrônimo é um termo que será bastante utilizado daqui para frente na sua jornada como pessoa desenvolvedora.

Nesse projeto vamos começar a lidar um pouco mais com essas operações, mas não vamos fazer todas elas. Você precisará criar, ler e apagar informações, mas não precisará desenvolver a função de editar por enquanto. Não se preocupe, pois no futuro, voltaremos a implementar essas operações e nos próximos projetos você fará um CRUD completo.

</details>

<details>
  <summary><strong>🗣 Nos dê feedbacks sobre o projeto!</strong></summary><br />

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o formulário.
**Leva menos de 3 minutos!**

[FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://be-trybe.typeform.com/to/ZTeR4IbH)

</details>

<details>
  <summary><strong>🗂 Compartilhe seu portfólio!</strong></summary><br />

Você sabia que o LinkedIn é a principal rede social profissional e compartilhar o seu aprendizado lá é muito importante para quem deseja construir uma carreira de sucesso? Compartilhe esse projeto no seu LinkedIn, marque o perfil da Trybe (@trybe) e mostre para a sua rede toda a sua evolução.

</details>

<details>
  <summary><strong>:bow: Agradecimentos</strong></summary><br />

Pessoas que contribuíram com feedbacks no programa de _beta testers_ desse projeto:

- [@alanmdf](https://github.com/alanmdf);
- [@Aleilton](https://github.com/Aleilton);
- [@felipeventorim](https://github.com/felipeventorim);
- [@gusttavocaruso](https://github.com/gusttavocaruso);
- [@junglejf](https://github.com/junglejf);
- [@JVictorC](https://github.com/JVictorC);
- [@lcds90](https://github.com/lcds90);
- [@Murilo-Rainho](https://github.com/Murilo-Rainho);
- [@rafaelromanoz](https://github.com/rafaelromanoz);
- [@rogeriop1990cv](https://github.com/rogeriop1990cv);
- [@RoyMusthang](https://github.com/RoyMusthang);
- [@vdionysio](https://github.com/vdionysio).
</details>

# Requisitos

:warning: **PULL REQUESTS COM ISSUES DE LINTER NÃO SERÃO AVALIADAS.** :warning:

:warning: Os gifs são meramente ilustrativos para visualizar o fluxo da aplicação. Portanto, os nomes devem seguir os requisitos e não o gif. :warning:

## 1. Crie o formulário que será usado para adicionar cartas ao baralho

Crie um formulário que será utilizado para criar as cartas do seu baralho.

- Crie um componente chamado `Form` dentro da pasta `src/components`.

- Renderize o componente `Form` dentro do componente principal `App`.

- <details><summary>Crie os seguintes itens dentro do component <code>Form</code>:</summary>

  :bulb: **Dica:** Você pode criar um componente de input. Lembre-se de sempre ter uma label associada para cada input.

  - um campo do tipo `text` que contenha o atributo `data-testid="name-input"`. Este campo será usado para inserir o nome da carta.

  - um campo do tipo `textarea` que contenha o atributo `data-testid="description-input"`. Este campo será usado para inserir a descrição da carta.

  - um campo do tipo `number` que contenha o atributo `data-testid="attr1-input"`. Este campo será usado para inserir o primeiro atributo da carta. Ele é livre para você adicionar o atributo que mais combinar com o seu baralho.

  - um campo do tipo `number` que contenha o atributo `data-testid="attr2-input"`. Este campo será usado para inserir o segundo atributo da carta. Ele é livre para você adicionar o atributo que mais combinar com o seu baralho.

  - um campo do tipo `number` que contenha o atributo `data-testid="attr3-input"`. Este campo será usado para inserir o terceiro atributo da carta. Ele é livre para você adicionar o atributo que mais combinar com o seu baralho.

  - um campo do tipo `text` que contenha o atributo `data-testid="image-input"`. Este campo será usado para inserir o caminho para imagem da carta.

  - um campo do tipo `select` que contenha o atributo `data-testid="rare-input"`. Este campo será usado para inserir a raridade da carta e deverá ter as `options`: `normal`, `raro` e `muito raro` (é importante que as opções estejam nessa ordem).

  - um campo do tipo `checkbox` que contenha o atributo `data-testid="trunfo-input"`. Este campo será usado para inserir se a carta é o Super Trunfo.

  - um `button`que contenha o atributo `data-testid="save-button"` e que tenha o texto "Salvar".
  </details>

  <details><summary><strong>Imagem exemplo:</strong></summary>

![requisito-1](images/requisito-1.png)

  </details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se existe um input texto que possui o `data-testid="name-input"`.

- Será validado se existe um input textarea que possui o `data-testid="description-input"`.

- Será validado se existe um input number que possui o `data-testid="attr1-input"`.

- Será validado se existe um input number que possui o `data-testid="attr2-input"`.

- Será validado se existe um input number que possui o `data-testid="attr3-input"`.

- Será validado se existe um input texto que possui o `data-testid="image-input"`.

- Será validado se existe um input select que possui o `data-testid="rare-input"` com as `options`: `normal`, `raro` e `muito raro`, nesta ordem.

- Será validado se existe um input checkbox que possui o `data-testid="trunfo-input"`.

- Será validado se existe um botão que possui o `data-testid="save-button"`.
</details>

---

## 2. Adicione as props necessárias ao componente de formulário

- <details><summary>O componente <code>Form</code> deverá receber as seguintes props:</summary>

  - `cardName`, uma string;
  - `cardDescription`, uma string;
  - `cardAttr1`, uma string;
  - `cardAttr2`, uma string;
  - `cardAttr3`, uma string;
  - `cardImage`, uma string;
  - `cardRare`, uma string;
  - `cardTrunfo`, um boolean;
  - `hasTrunfo`, um boolean;
  - `isSaveButtonDisabled`, um boolean;
  - `onInputChange`, uma callback;
  - `onSaveButtonClick`, uma callback;
  </details>

- <details><summary>As props do componente <code>Form</code> deverão ser utilizadas conforme o indicado abaixo:</summary>

  - Campo `name-input`: a propriedade `value` deve receber o valor da prop `cardName` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `description-input`: a propriedade `value` deve receber o valor da prop `cardDescription` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `attr1-input`: a propriedade `value` deve receber o valor da prop `cardAttr1` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `attr2-input`: a propriedade `value` deve receber o valor da prop `cardAttr2` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `attr3-input`: a propriedade `value` deve receber o valor da prop `cardAttr3` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `image-input`: a propriedade `value` deve receber o valor da prop `cardImage` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `rare-input`: a propriedade `value` deve receber o valor da prop `cardRare` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Campo `trunfo-input`: a propriedade `checked` deve receber o valor da prop `cardTrunfo` e a prop `onChange` deve receber o valor da prop `onInputChange`.

  - Botão `save-button`: a propriedade `disabled` deve receber o valor da prop `isSaveButtonDisabled` e a prop `onClick` deve receber o valor da prop `onSaveButtonClick`.

  **:bulb: Obs:** por enquanto a prop `hasTrunfo` ainda não foi utilizada, mas não se preocupe, pois ela será usada em breve.
  </details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o campo de nome recebe o valor da prop `cardName` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo de descrição recebe o valor da prop `cardDescription` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo do atributo 1 recebe o valor da prop `cardAttr1` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo do atributo 2 recebe o valor da prop `cardAttr2` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo do atributo 3 recebe o valor da prop `cardAttr3` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo de imagem recebe o valor da prop `cardImage` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo de raridade recebe o valor da prop `cardRare` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o campo de Super Trufo recebe o valor da prop `cardTrunfo` e se a callback `onInputChange` é chamada quando o campo sofre alguma alteração.

- Será validado se o botão de salvar é habilitado se o valor da prop `isSaveButtonDisabled` for `false`.

- Será validado se o botão de salvar é desabilitado se o valor da prop `isSaveButtonDisabled` for `true`.

- Será validado se a callback `onSaveButtonClick` é chamada quando o botão é clicado.
</details>

---

## 3. Crie e renderize o componente Card com as props necessárias

- <details><summary>Crie um componente com o nome <code>Card</code> na pasta <code>src/components</code> e renderize-o  no componente principal <code>App</code>. O componente <code>Card</code> deve receber as seguintes props: </summary>

  - `cardName`, uma string;
  - `cardDescription`, uma string;
  - `cardAttr1`, uma string;
  - `cardAttr2`, uma string;
  - `cardAttr3`, uma string;
  - `cardImage`, uma string;
  - `cardRare`, uma string;
  - `cardTrunfo`, um boolean;
  </details>

- <details><summary>Renderize o componente <code>Card</code> dentro do componente principal <code>App</code>:</summary>

  - Exiba o valor da prop `cardName`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="name-card"`.

  - Exiba a imagem usando a tag HTML `img`, com o atributo `src` que tenha o valor da prop `cardImage` e o atributo `alt` com o valor da prop `cardName`. Essa imagem também deve ter o atributo `data-testid="image-card"`

  - Exiba o valor da prop `cardDescription`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="description-card"`.

  - Exiba o valor da prop `cardAttr1`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="attr1-card"`.

  - Exiba o valor da prop `cardAttr2`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="attr2-card"`
  - Exiba o valor da prop `cardAttr3`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="attr3-card"`.

  - Exiba o valor da prop `cardRare`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="rare-card"`.

  - Exiba o texto `Super Trunfo` somente quando o valor da prop `cardTrunfo` for `true`. Você pode usar qualquer tag HTML que faça sentido, desde que ela tenha o atributo `data-testid="trunfo-card"`.

  **Dica: Você pode utilizar renderização condicional para renderizar ou não o texto do super trunfo.**
  </details>

<details><summary>Imagem Exemplo:</summary>

![requisito-3](images/requisito-3.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />
  
  - Será validado se o componente `data-testid="name-card"` é exibido e possui o valor da prop `cardName`.
  - Será validado se o componente `data-testid="image-card"` é exibido e possui o atributo `src` com o valor da prop `cardImage` e o atributo alt com o valor da prop `cardName`.
  - Será validado se o componente `data-testid="description-card"` é exibido e possui o valor da prop `cardDescription`.
  - Será validado se o componente `data-testid="attr1-card"` é exibido e possui o valor da prop `cardAttr1`.
  - Será validado se o componente `data-testid="attr2-card"` é exibido e possui o valor da prop `cardAttr2`.
  - Será validado se o componente `data-testid="attr3-card"` é exibido e possui o valor da prop `cardAttr3`.
  - Será validado se o componente `data-testid="rare-card"` é exibido e possui o valor da prop `cardRare`.
  - Será validado se o componente `data-testid="trunfo-card"` é exibido quando a prop `cardTrunfo` tiver o valor `true`.
  - Será validado se o componente `data-testid="trunfo-card"` **não** é exibido quando a prop `cardTrunfo` tiver o valor `false`.
</details>

---

## 4. Crie o preview da carta que está sendo criada pelo formulário

Até o momento você criou dois componentes que recebem `props`, agora está na hora de criar o estado dos componentes.
Os componentes `Form` e `Card` irão compartilhar o mesmo estado para exibir as mesmas informações (isso já te dá uma dica de onde o estado deve estar, não é mesmo?).
Quando alguma informação é digitada em algum campo do formulário, o componente `Card` deve exibir a mesma informação em tempo real, criando um preview da carta antes de ela ser salva no baralho (a funcionalidade de salvar será feita nos próximos requisitos).

Você deverá usar a prop `onInputChange` para passar uma callback para lidar com os eventos de `onChange` dos inputs do formulário. Não se esqueça que os valores dos inputs (que também são passados por props) também devem ser salvos em um estado.

**:bulb: Dica:** o mesmo estado usado para controlar os inputs do formulário podem ser passados para o componente `Card`.

<details><summary><strong>Informações técnicas:</strong></summary>

- Ao digitar algo no campo com o `data-testid="name-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="name-card"`.

- Ao digitar algo no campo com o `data-testid="description-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="description-card"`.

- Ao digitar algo no campo com o `data-testid="image-input"` do formulário, o mesmo valor deverá ser passado para o componente `Card`, e ser usado no atributo `src` do elemento com o `data-testid="image-card"`.

- Ao digitar algo no campo com o `data-testid="attr1-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="attr1-card"`.

- Ao digitar algo no campo com o `data-testid="attr2-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="attr2-card"`.

- Ao digitar algo no campo com o `data-testid="attr3-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="attr3-card"`.

- Ao selecionar algum valor no `select` com o `data-testid="rare-input"` do formulário, o mesmo valor deverá ser renderizado no componente `Card`, no elemento com o `data-testid="rare-card"`.

- Quando o campo do tipo `checkbox` que possui o `data-testid="trunfo-input"` estiver `checked`, deverá ser renderizado no componente `Card` o texto `Super Trunfo` dentro do elemento com o `data-testid="trunfo-card"`.

**:bulb: Dica:** para campos que precisem de um valor padrão (como o campo de raridade, por exemplo) você pode iniciar o estado já com esse valor.

![requisito-4](images/requisito-4.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se é renderizado no preview da carta o valor digitado no input Nome do formulário.
- Será validado se é renderizado no preview da carta o valor digitado no input Descrição do formulário.
- Será validado se é renderizado no preview da carta o valor digitado no input referente ao atributo 1 no formulário.
- Será validado se é renderizado no preview da carta o valor digitado no input referente ao atributo 2 no formulário.
- Será validado se é renderizado no preview da carta o valor digitado no input referente ao atributo 3 no formulário.
- Será validado se é renderizado no preview da carta o `data-testid="trunfo-card"` se o checkbox Super Trunfo for selecionado.
</details>

---

## 5. Faça a validação do botão de Salvar no formulário

<details><summary>O botão que possui o atributo <code>data-testid="save-button"</code> só deve estar habilitado se todas as informações do formulário estiverem preenchidas corretamente, seguindo as seguintes regras:</summary>

- Os campos `Nome`, `Descrição`, `Imagem` e `Raridade ` devem conter alguma informação (ou seja, os `inputs` não podem estar vazios).

- A soma dos valores dos 3 atributos (`attr1-input`, `attr2-input` e `attr3-input`) não pode ultrapassar o valor **210**.

- Cada um dos três atributos pode ter **no máximo 90 pontos cada**.

- Os atributos não podem receber valores negativos.
</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o botão `salvar` está desabilitado quando a página é renderizada pela primeira vez.
- Será validado se o botão `salvar` está desabilitado se o campo nome estiver vazio.
- Será validado se o botão `salvar` está desabilitado se o campo imagem estiver vazio.
- Será validado se o botão `salvar` está desabilitado se o campo descrição estiver vazio.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 1 for maior que 90.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 1 for menor que 0.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 2 for maior que 90.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 2 for menor que 0.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 3 for maior que 90.
- Será validado se o botão `salvar` está desabilitado se o campo do atributo 3 for menor que 0.
- Será validado se o botão `salvar` está desabilitado se a somatória dos campos de atributos for maior que 210.
- Será validado se o botão `salvar` é habilitado ao preencher todos os campos do formulário corretamente.
</details>

---

## 6. Crie a função do botão salvar

<details><summary>Agora que o botão de salvar já está validado, você pode adicionar uma nova carta ao seu baralho. Isso significa que você precisará criar um novo estado na sua aplicação para salvar a lista de cartas existentes no seu baralho.</summary>

:bulb: **Dica:** você pode salvar cada carta em um formato de objeto e ter um _array_ com esses objetos no seu estado.

- Ao clicar no botão que possui o atributo `data-testid="save-button"`, as informações que foram preenchidas no formulário deverão ser salvas no estado da sua aplicação.

- Após salvar as informações, os `inputs` do formulário `Nome`, `Descrição` e `Imagem` e o conteúdo do preview da carta deverão ser limpos.

- Após salvar as informações, os três campos de atributos devem ter valor 0.

- Após salvar as informações, o campo `Raridade` deve conter o valor `normal`.
</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se os campos do formulário `Nome`, `Descrição` e `Imagem` são limpos após clicar em `salvar`.

- Será validado se o os três campos de atributos têm o valor `0` após clicar em `salvar`.

- Será validado se o campo de `Raridade` tem o valor `normal` após clicar em `salvar`.
</details>

---

## 7. Crie a validação do Super Trunfo

<details><summary>Em um baralho de Super Trunfo pode existir apenas <strong>uma carta Super Trunfo</strong>. Por isso é necessário fazer uma validação para que somente 1 carta Super Trunfo seja salva no seu baralho:</summary>

- Para que uma carta seja salva como Super Trunfo é preciso que o input com o `data-testid="trunfo-input"` esteja `checked` na hora de salvar a carta. Por isso, a validação será feita nesse campo. Para fazer essa validação, você deve usar o prop `hasTrunfo` do componente `Form`.

- Caso já exista uma carta Super Trunfo em seu baralho, o formulário de criação de carta não deverá exibir o `checkbox` `data-testid="trunfo-input"`. No seu lugar deve ser renderizada a frase: "Você já tem um Super Trunfo em seu baralho".

**Dica: Lembre-se de utilizar a renderização condicional (na seção [:convenience_store: Desenvolvimento](#orientações)) do React nesse requisito.**

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o checkbox do Super Trunfo é renderizado ao carregar a página.

- Será validado se o texto "Você já tem um Super Trunfo em seu baralho" é renderizado caso já exista uma carta Super Trunfo no baralho.
</details>

---

## 8. Exiba a lista de cartas que estão salvas no estado

Você já tem várias cartas legais em seu baralho, agora é a hora de listá-las para que você possa ver toda sua coleção!

- Renderize dentro do component `App` uma lista com todas as cartas que você tem no estado da aplicação.
- Garanta que sempre que uma carta for adicionada, a lista é atualizada automaticamente.

:bulb: **Dica:** você pode reutilizar o componente `Card` nesse requisito. :bulb:

<details><summary>Imagem Exemplo:</summary>

![requisito-8](images/requisito-8.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se a carta é renderizada na página ao salvá-la.
- Será validado se a lista é atualizada automaticamente quando uma carta é adicionada.
</details>

---

## 9. Crie um botão para remover uma carta do baralho

- <details><summary>Criar em cada carta que está sendo renderizada do seu baralho um <code>button</code> com o texto <code>Excluir</code> e o atributo <code>data-testid="delete-button"</code>.</summary>

  - A carta de _preview_ **não pode ter esse botão**.

  - Ao clicar neste botão, a carta deve ser excluída do seu baralho, ou seja, não deverá mais ser renderizada na página.
    **Dica: Lembre-se que o baralho está sendo renderizado a partir do estado do seu componente!**

  - Se a carta excluída for uma carta Super Trunfo, o `checkbox` do formulário deverá aparecer novamente, tornando possível a criação de uma nova carta Super Trunfo.

  ![requisito-9](images/requisito-9.png)
  </details>

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o botão `Excluir` é renderizado na tela apenas nas cartas adicionadas ao baralho.
- Será validado se ao adicionar uma carta e excluí-la em seguida, a carta não é renderizada.
- Será validado se ao adicionar duas cartas e excluir uma em seguida, a carta não é renderizada.
- Será validado se ao excluir uma carta Super Trunfo, o checkbox no formulário é renderizado novamente.
</details>

---

# Requisitos bônus

Sua aplicação terá três filtros de listagem de cartas: filtro por **nome**, por **raridade** e por **Super Trunfo**. Os filtros **nome** e **raridade** são acumulativos. O filtro **Super Trunfo** funciona de forma independente.

## 10. Crie o filtro pelo nome da carta

<details><summary>Para filtro do <strong>nome</strong>, você deverá criar um campo do tipo <code>text</code> e adicionar o atributo <code>data-testid="name-filter"</code>:</summary>
  
  * Este campo deve ser renderizado sempre, mesmo se não existirem cartas salvas no baralho.
  
  * Ao digitar neste campo, deve ser renderizado na página apenas as cartas que contenham no `nome` o texto digitado.

![requisito-10](images/requisito-10.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o campo de filtro por nome renderiza na tela.
- Será validado se apenas as cartas correspondentes aparecem após o filtro.
- Será validado se não renderiza nenhuma carta se não houver nome correspondente.
</details>

---

## 11. Crie o filtro por raridade da carta

<details><summary>Para filtrar por <strong>raridade</strong>, você deverá criar um campo do tipo <code>select</code> e adicionar o atributo <code>data-testid="rare-filter"</code>:</summary>
  
  * Este `select` deve possuir as seguintes `options`: 
    - `todas`
    - `normal`
    - `raro`
    - `muito raro`
  
  * Por padrão, a opção `todas` já estará selecionada;
  
  * Ao selecionar uma das opções, apenas as cartas que possuem a raridade especificada deverão ser renderizadas. Caso esteja selecionada `todas`, não deve ter filtro de raridade aplicado na lista.
  
  * Se o campo do filtro `Nome` estiver preenchido, os dois filtros (por nome e por raridade) devem funcionar em conjunto.

![requisito-11](images/requisito-11.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />

- Será validado se o campo de filtro por Raridade renderiza na tela.
- Será validado se somente as cartas com raridade `normal` são exibidas após o filtro.
- Será validado se somente as cartas com raridade `raro` são exibidas após o filtro.
- Será validado se somente as cartas com raridade `muito raro` são exibidas após o filtro.
- Será validado se todas as cartas são exibidas quando o filtro de raridade está com a opção `todas` selecionada.
- Será validado se não renderiza nenhuma carta se não houver raridade correspondente.
</details>

---

## 12. Crie o filtro de Super Trunfo

<details><summary>Para filtrar por <strong>Super Trunfo</strong>, você deverá criar um campo do tipo <code>checkbox</code> com a <code>label</code> Super Trunfo e o atributo <code>data-testid="trunfo-filter"</code>:</summary>
  
  * Ao selecionar este `checkbox`, apenas a carta **Super Trunfo** deverá ser renderizada.
  
  * Enquanto o `checkbox` estiver com o atributo `checked`, ou seja, se estiver selecionado, os `inputs` dos filtros por nome e por raridade deverão ficar com o atributo `disabled`.

- Se o `checkbox` não estiver selecionado, as cartas devem ser renderizadas normalmente, seguindo apenas as regras dos filtros anteriores.

![requisito-12](images/requisito-12.png)

</details><br />

<details>
  <summary><strong>O que será verificado</strong></summary><br />
  - Será validado se somente a carta de super trunfo é exibida quando esse filtro é selecionado.
</details>

---

# Requisitos não avaliativos

Você já criou o baralho do seu Tryunfo. Agora você pode criar uma funcionalidade para jogar com outras pessoas estudantes! Abaixo iremos apresentar uma **sugestão** de como essa funcionalidade pode ser criada! **Esses requisitos não serão avaliados pelo Evaluator**, portanto, fique livre para desenvolver da maneira que você achar melhor! Use os conhecimentos que você aprendeu e desenvolveu ao longo dos módulos anteriores e exerça a sua criatividade!

<details><summary><strong>Regras do Jogo</strong></summary>

Antes de iniciar o desenvolvimento, vamos relembrar como funciona o jogo:

- Primeiramente, cada pessoa deve "pegar" uma carta aleatória do seu baralho.
- A primeira pessoa irá escolher um atributo para comparar com a carta da outra pessoa. Lembre-se que no Tryunfo os atributos podem ter nomes diferentes em cada baralho, por isso o ideal é se basear pela posição do atributo, ou seja, comparar o primeiro atributo da sua carta com o primeiro atributo da carta da pessoa rival.
- Ganha a rodada quem tiver o número maior no atributo escolhido.
- Ao término da rodada, cada pessoa deve "pegar" uma nova carta aleatória.
- A cada rodada é alternada a vez de quem escolhe o atributo para comparação.
</details><br />

<details><summary><strong>O que será necessário</strong></summary>

Para poder jogar, será necessário ter desenvolvido os seguintes passos:

1.  Criar baralho com N cartas (já desenvolvido nos requisitos anteriores).
2.  Criar uma função que embaralhe as cartas e renderize a primeira carta do baralho.
3.  Criar um botão para renderizar a próxima carta do baralho.
4.  Na ultima carta, ter um botão para recomeçar o jogo, embaralhando novamente.
</details>

---

## 13. Iniciar o jogo

- Crie um botão com o texto `Jogar`;

- Crie um novo estado na sua aplicação, que receberá as cartas do seu baralho em ordem aleatória;

- Ao clicar no botão `Jogar`, este novo estado deve receber as cartas que estão salvas no seu baralho, mas em ordem **aleatória**
  veja neste link [como implementar uma função que embaralha um array](https://flaviocopes.com/how-to-shuffle-array-javascript/).

- Crie um novo estado na sua aplicação que irá controlar a posição no array da carta que será renderizada.

- Para renderizar na página, você pode utilizar **renderização condicional** para mostrar a carta apenas quando um jogo estiver em andamento.

**Lembre-se que há várias formas possíveis para montar esta função. Isso é apenas uma sugestão.**

---

## 14. Criar botão Próxima Carta

- Após clicar em `Jogar` e embaralhar as cartas existentes, exiba a primeira carta na tela, ou seja, a carta que está na posição `0` do array.

- Exiba um botão com o texto `Próxima carta`.

- Ao clicar no botão "Próxima carta", a próxima carta do seu baralho "embaralhado" deve ser renderizada. Você pode usar o estado criado no requisito anterior e incrementá-lo em cada rodada.

<details><summary>Imagem Exemplo:</summary>

![requisito-14](images/requisito-14.png)

</details>

---

## 15. Recomeçar o jogo

- Quando a última carta do baralho estiver sendo renderizada, ou seja, quando você estiver na última posição do array de cartas embaralhadas, o botão "Próxima carta" não deve ser renderizado na tela.

- Um novo botão deve ser exibido com o texto `Embaralhar cartas`.

- Ao clicar no botão `Embaralhar cartas` o baralho deve ser embaralhado novamente e o estado que controla a posição da carta exibida deve ser `0` novamente.

<details><summary>Imagem Exemplo:</summary>

![requisito-15](images/requisito-15.png)

</details>

---
