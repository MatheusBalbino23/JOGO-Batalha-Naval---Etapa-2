# Jogo de Batalha Naval

Este é um programa em C que implementa o jogo de Batalha Naval em um tabuleiro de dimensões 4x8. O objetivo do jogo é acertar os três navios presentes no tabuleiro.

## Funcionamento

O programa inicia com um tabuleiro vazio e posiciona três navios aleatoriamente. O jogador deve tentar acertar os navios informando as coordenadas de tiro (linha e coluna). O jogo termina quando todos os navios são acertados.

## Como Executar

1. Certifique-se de ter um compilador C instalado em seu sistema.
2. Abra um terminal na pasta onde está o arquivo fonte (`batalha_naval.c`).
3. Compile o programa usando o compilador C. Por exemplo, usando o GCC:
   ```bash
   gcc -o batalha_naval batalha_naval.c
   ```
4. Execute o programa:
   ```bash
   ./batalha_naval
   ```

## Exemplo de Uso

```
        1       2       3       4       5       6       7       8
1       0       0       0       0       0       0       0       0
2       0       0       0       0       0       0       0       0
3       0       0       0       0       0       0       0       0
4       0       0       0       0       0       0       0       0

Linha: 1
Coluna: 2

        1       2       3       4       5       6       7       8
1       0       *       0       0       0       0       0       0
2       0       0       0       0       0       0       0       0
3       0       0       0       0       0       0       0       0
4       0       0       0       0       0       0       0       0

...

Voce acertou os 3 navios em 7 tentativas
        1       2       3       4       5       6       7       8
1       0       X       0       0       0       0       0       0
2       X       X       X       0       0       0       0       0
3       0       0       0       0       0       0       0       0
4       0       0       0       0       0       0       0       0
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
