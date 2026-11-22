# Painel de manutenção, equipe 5

Trabalho do semestre de Visualização de Dados (TCD024), etapa 3.

**Integrantes:** Adriana de Jesus Freitas, Allan Gomes de Amorim, Luiz Miguel Silva de Assis, Wesley Dutra de Freitas.

## O que é

Painel interativo (uma página HTML, sem dependências) com:

- título conclusivo e três indicadores, cada um com numerador e denominador;
- figura principal: taxa de quebra por faixa de 25 min de uso, com intervalo de Wilson de 95% (botão para ver a taxa por faixa de torque);
- figura de apoio: modos de falha antes e a partir de 200 min de uso;
- frase para o responsável pela manutenção, com o limite da conclusão.

## Como abrir

- Online (GitHub Pages): ver o link na descrição do repositório.
- Local: baixe `index.html` e abra no navegador.

## Origem dos números

Os valores da página foram copiados das tabelas geradas no notebook da etapa 3 (`TABELA_USO`, `TABELA_TORQUE` e a tabela de modos de falha). Os intervalos usam a função `intervalo` do notebook (Wilson, 95%).

## Dados e limites

- Base: AI4I 2020 Predictive Maintenance Dataset, UCI Machine Learning Repository, DOI 10.24432/C5HS5C, licença CC BY 4.0. Dados simulados.
- O corte de 200 min é só o recorte usado para comparar os registros, não um limiar validado de manutenção.
- A comparação descreve associação nestes registros e não prova causa.
- Faixas com menos de 100 peças aparecem com ponto vazado (taxa instável).
