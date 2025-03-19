# Amigo Secreto - Lógica de Programação

## Descrição
Este projeto tem como objetivo fortalecer suas habilidades em lógica de programação. A aplicação permite adicionar nomes a uma lista e realizar um sorteio de "Amigo Secreto" entre os participantes.

## Funcionalidades
- Adicionar nomes à lista.
- Exibir a lista de participantes.
- Sortear um nome aleatoriamente entre os participantes.

## Tecnologias Utilizadas
- HTML
- CSS (opcional para estilização)
- JavaScript

## Como Usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/amigo-secreto.git
   ```
2. Abra o arquivo `index.html` em um navegador.
3. Insira nomes no campo de entrada e clique em "Adicionar".
4. Clique em "Sortear" para escolher um nome aleatoriamente.

## Estrutura do Código
O código principal está escrito em JavaScript e possui as seguintes funções:
- `adicionarAmigo()`: Adiciona um nome à lista, validando a entrada.
- `atualizarLista()`: Atualiza dinamicamente a lista de amigos exibida na tela.
- `sortearAmigo()`: Sorteia um nome aleatoriamente da lista.

## Exemplo de Uso
```js
let nomes = [];

function adicionarAmigo() {
    let input = document.getElementById("amigo");
    let nome = input.value.trim();
    
    if (nome === "") {
        alert("Por favor, insira um nome válido.");
        return;
    }
    
    nomes.push(nome);
    atualizarLista();
    input.value = "";
}
```

## Contribuição
Sinta-se à vontade para contribuir com melhorias e sugestões. Para isso:
1. Faça um fork do repositório.
2. Crie uma nova branch.
3. Faça suas alterações e envie um pull request.

## Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para utilizá-lo e modificá-lo conforme necessário.

