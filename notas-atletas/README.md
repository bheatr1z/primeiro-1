# Notas Atletas

## Resumo do Projeto
Esta aplicação calcula a média das notas de atletas em uma competição de ginástica artística. Cada atleta recebe cinco notas de jurados, e a média é calculada com base nas três notas do meio, desconsiderando a maior e a menor nota.

## Como Usar

### Requisitos
- Node.js instalado

### Passos para Executar
1. Clone o repositório para o seu computador:
    ```bash
    git clone https://github.com/seuusuario/notas-atletas.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd notas-atletas
    ```
3. Execute o arquivo JavaScript:
    ```bash
    node notas-atletas.js
    ```

## Estrutura do Código
O código principal está no arquivo `notas-atletas.js`, onde:
- As notas dos atletas são ordenadas.
- As maiores e menores notas são removidas.
- A média das três notas restantes é calculada e exibida.

## Entrada
A entrada é uma matriz de objetos contendo o nome do atleta e as cinco notas atribuídas.

```javascript
let atletas = [
    {
      nome: "Cesar Abascal",
      notas: [10, 9.34, 8.42, 10, 7.88]
    },
    {
      nome: "Fernando Puntel",
      notas:  [8, 10, 10, 7, 9.33]
    },
    {
      nome: "Daiane Jelinsky",
      notas: [7, 10, 9.5, 9.5, 8]
    },
    {
      nome: "Bruno Castro",
      notas: [10, 10, 10, 9, 9.5]
    }
];

# Saída

Atleta: Cesar Abascal
Notas Obtidas: 10, 9.34, 8.42, 10, 7.88
Média Válida: 9.253333

Atleta: Fernando Puntel
Notas Obtidas: 8, 10, 10, 7, 9.33
Média Válida: 9.110000

Atleta: Daiane Jelinsky
Notas Obtidas: 7, 10, 9.5, 9.5, 8
Média Válida: 9.000000

Atleta: Bruno Castro
Notas Obtidas: 10, 10, 10, 9, 9.5
Média Válida: 9.833333

