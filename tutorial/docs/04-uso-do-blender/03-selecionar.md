---
id: selecionar
title: Selecionar
sidebar_label: Selecionar
---

## Tipo de seleção
- `TAB`-> "*Object Mode*" or "*Edit Mode*"
- `TAB Edit Mode` `1` -> Vertex selection mode
- `TAB Edit Mode` `2` -> Edge selection mode
- `TAB Edit Mode` `3` -> Face selection mode

## Selecionar
- `LMB-CLICK SELEÇÃO`-> Selecionar algo
- `SHIFT LMB-CLICK SELEÇÃO` -> Adicionar algo em seleção, ou retirá-lo da seleção.
- `A`-> Selecionar todos as entidades selecionáveis.
- `ALT` `A` -> Deselecionar todos as entidades selecionadas.
- `B` ou `LMB-CLICK-DRAG` -> Selecionar com área retangular.
- `CTRL` `RMB-DRAG` -> Selecionar, com laço, entidades selecionáveis1
- `SHIFT` `CTRL` `RMB-DRAG` -> Retirar da Seleção, com laço, entidades selecionadas.
- `CTRL` `I` -> Inverter seleção

## Selecionar intervalo de vertex, edges ou faces
- `SELECAO origin` `CTRL-SHIFT` `SELECAO final` -> Seleção de intervalo de vertex, edges or faces, entre seleções clicadas. 

## Selecionar todo um loop
- No caso de Vertex, a orientação do loop é seguindo pela multiplicação da distância ao vertex de menor afastamento.
- No caso de Faces, a orientação do loop é seguindo pela multiplicação dos lados de menor comprimento.
- `TAB Edit Mode` `1` `ALT` `LMB-CLICK em VERTEX`-> Selecionar loop de VERTEX
- `TAB Edit Mode` `2` `ALT` `LMB-CLICK em EDGE`-> Selecionar loop de EDGES
- `TAB Edit Mode` `3` `ALT` `LMB-CLICK em FACE`-> Selecionar loop de FACES

## Selecionar edges paralelos
- `TAB Edit Mode` `2` `CTRL` `ALT` `LMB-CLICK em EDGE`-> Selecionar ring EDGES paralelos