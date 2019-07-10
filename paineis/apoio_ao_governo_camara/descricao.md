## Objetivo:

Visualizar o apoio que o governo recebe dos partidos nas votações em plenário na Câmara dos Deputados.

## Dados

- Votacões dos deputados
- Orientação das bancadas

## Tabelas

Schema: `analysis_congresso_apoio`

## Gráficos

1. Taxa de apoio geral do governo mais recente + variação
Tipo: Número + variação
Dados: 
    - Número: taxa de apoio geral
    - Variação: variação da taxa de apoio no intervalo de tempo t

2. Taxa de apoio geral comparada com outras legislaturas
Tipo: Barra
Dados: 
    - X: Legislatura [Acronimo do presidente, e.g. Lula 1]
    - Y: Taxa de apoio geral

3. Variação histórica da taxa de apoio geral
Tipo: Linha
Dados:
    - X: Mês e Ano
    - Y: Média do apoio por mês

4. Proporção de votacões que o governo foi favorável neste delta t
Tipo: Número
Dados: 
    - Número: Proporção
    - Variação: variação da proporção no intervalo de tempo t

5. Proporção de votacões que o governo foi favorável comparada com outras legislaturas
Tipo: Barra
Dados: 
    - X: Legislatura [Acronimo do presidente, e.g. Lula 1]
    - Y: Proporção de Votacão

6. Variação histórica da proporção de votacões que o governo foi favorável
Tipo: Linha
Dados:
    - X: Mês e Ano
    - Y: Proporção de votacões por mês


-- Ideia
4. Proporção de matérias votadas de autoria do Governo
Tipo: Linha
Dados:
