# 🔢 Jogo: Maior, Menor ou Igual

Este é um jogo simples em C onde o jogador tenta adivinhar se o número escolhido por ele é **maior**, **menor** ou **igual** ao número sorteado pelo computador.

## ✅ Funcionalidades

- Geração de número aleatório entre 1 e 100.
- Jogador escolhe um número e o tipo de comparação (Maior, Menor ou Igual).
- Exibição do número sorteado e resultado.
- Verificação automática de vitória ou derrota.

## 🧠 Regras do Jogo

- O computador sorteia um número entre 1 e 100.
- O jogador escolhe um número e uma das opções:
  - `M` para **Maior**
  - `N` para **Menor**
  - `I` para **Igual**
- Se a comparação escolhida estiver correta em relação ao número do computador, o jogador vence. Caso contrário, perde.

## 🛠️ Compilação e Execução

Para compilar e executar o jogo, utilize um compilador C como `gcc`:

```bash
gcc maior_menor_igual.c -o jogo
./jogo
```

> Substitua `maior_menor_igual.c` pelo nome do seu arquivo, se for diferente.

## 💻 Exemplo de Uso

```plaintext
Bem-vindo ao jogo Maior, Menor ou Igual!
Você deve escolher um número e o tipo de comparação.
M. Maior
N. Menor
I. Igual
Escolha a comparação:
m
Digite seu número (entre 1 e 100): 
75
O número do computador é: 60
Você escolheu a opção maior!
Parabéns, você venceu!
```

## 📂 Estrutura do Código

- `srand(time(0))`: Inicializa a semente de aleatoriedade.
- `rand() % 100 + 1`: Gera um número aleatório de 1 a 100.
- `switch` para interpretar a opção do jogador (`M`, `N`, `I`).
- Operador ternário para verificar se a condição está correta.

## 📌 Requisitos

- Compilador C (como GCC ou TCC).
- Terminal ou console compatível.

## 📄 Licença

Este projeto é livre para fins educacionais!