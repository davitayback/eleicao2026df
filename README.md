# Análise Estatística — Deputados Distritais DF 2026

### Consolidação das cinco pesquisas IGAPE — 10.000 entrevistas em 5 rodadas


---

## 1. Documentação e ficha das pesquisas

| Pesquisa | Registro TSE | Campo | Divulgação | Entrevistas | Margem de erro | Confiança |
|---|---|---|---|---:|---:|---:|
| P1 | DF-02390/2026 | 10 a 15/08/2026 | 16/08/2026 | 2.000 | ±2,2 p.p. | 95% |
| P2 | DF-02089/2026 | 25 a 29/08/2026 | 30/08/2026 | 2.000 | ±2,2 p.p. | 95% |
| P3 | DF-07879/2026 | 31/08 a 05/09/2026 | 06/09/2026 | 2.000 | ±2,2 p.p. | 95% |
| P4 | DF-09945/2026 | 08 a 12/09/2026 | 13/09/2026 | 2.000 | ±2,2 p.p. | 95% |
| P5 | DF-09868/2026 | 15 a 19/09/2026 | 20/09/2026 | 2.000 | ±2,2 p.p. | 95% |

As cinco rodadas foram realizadas pelo IGAPE, com entrevistas pessoais em domicílio, amostra representativa do eleitorado do Distrito Federal e questionário estruturado. A margem informada de **±2,2 pontos percentuais** é maior que muitos dos percentuais individuais observados. Posto isso, diferenças de poucos décimos não devem ser tratadas como superioridade estatisticamente comprovada.

[Consultar pesquisas registradas no TSE](https://pesqele-divulgacao.tse.jus.br/app/pesquisa/listar.xhtml)

---

## Sumário
1. [Tamanho da Amostra](#1-tamanho-da-amostra)
2. [Metodologia Estatística](#2-metodologia-estatistica)
3. [Parâmetros Eleitorais](#3-parametros-eleitorais)
4. [Justificativa do QE Adotado](#4-justificativa-do-qe)
5. [Evolução dos Dados no DF](#5-evolucao-dos-dados)
6. [Projeção dos 24 Nomes](#6-projecao-24-nomes)

---

<a id="1-tamanho-da-amostra"></a>
## 1. Tamanho da Amostra e Precisão

**5 rodadas x 2.000 entrevistas = 10.000 entrevistados**, amostras independentes.

| Indicador | Cálculo | Resultado |
| :--- | :--- | :--- |
| **População (N)** | Eleitorado TRE-DF 2026 | **2.253.732** |
| **Prob. de repetir entrevistado** | P = n / N = 2.000 / 2.253.732 | **0,088% (< 1 em 1.000)** |
| **Estratificação** | PPS por RA (Probabilidade Proporcional ao Tamanho) | Ceilândia 22% = 440 ent./rodada, São Sebastião 3,1% = 62 ent./rodada |
| **Erro-padrão (p=50%)** | SE = √[(0,5*0,5)/2000] | 1,11 p.p. |
| **Erro máximo (IC 95%)** | z=1,96 * SE | **±2,18% ≈ ±2,2 p.p.** - confere com ficha TSE |

Amostra replica distribuição real de urnas. São 10 mil pessoas diferentes.

<a id="2-metodologia-estatistica"></a>
## 2. Metodologia Estatística

```
Média Estrita = (P1 + P2 + P3 + P4 + P5) / 5
Regra: Se ausente na rodada, conta como 0,0% na média

Votos Equivalentes = Média Estrita × 1.690.000
Conversão: 1% = 16.900 votos

Ex: Rogério Ulysses = (1,1 + 1,2 + 0,9 + 0,9 + 0,8) / 5 = 0,98%
Votos eq. = 0,0098 × 1.690.000 = 16.562
Atributos: Presença 5/5 | Amplitude 0,4 p.p. | Consistência estatística
```

<a id="3-parametros-eleitorais"></a>
## 3. Parâmetros Eleitorais e Cenários de QE

Base operacional adotada: **1.680.000 a 1.690.000 votos válidos**

| Cenário | Votos Válidos | QE (Válidos/24) | Característica |
| :--- | ---: | ---: | :--- |
| 🔴 **Baixo** | ~1.598.000 | **~66.600** | Participação mínima histórica (81,15% comparec. x 87,36% válidos) |
| 🟡 **Tendência** | ~1.638.000 | **~68.300** | Regressão linear histórica 2006-2022 |
| ⭐ **Referência** | **1.680.000** | **🎯 70.000** | **Base de trabalho - ponto médio** |
| 🟠 **Média Histórica** | ~1.728.000 | **~72.000** | Média 2006-2022 |
| 🟢 **Alta** | ~1.840.000 | **~76.700** | Participação elevada |

**Projeção por Regressão Linear (detalhe):**
- Série Comparecimento: 86,12% → 84,55% → 88,33% → 81,15% → 82,04%
- Slope = -1,156 p.p. / eleição | Equação: Y = 86,75 - 1,156X | X=5 → **80,97% → 1.825.000 votantes**
- Série Válidos/Comparecimento: 92,39% → 90,86% → 91,01% → 87,36% → 92,42%
- Slope = -0,344 p.p. / eleição | Equação: Y = 91,496 - 0,344X | X=5 → **89,78% → 1.638.000 válidos**
- QE Tendência = 1.638.000 / 24 = **68.264**

<a id="4-justificativa-do-qe"></a>
## 4. Justificativa Técnica - QE Adotado: 70.416

Cálculo legal (Art. 107 Código Eleitoral): `QE = Votos Válidos / Cadeiras`

```
QE = 1.690.000 / 24 = 70.416,66... ≈ 70.416 votos
```

O valor 70.416 foi adotado como **régua conservadora**, posicionado entre a tendência de regressão (68.264) e a média histórica (72.000).


| Referência | Cálculo | Votos aproximados |
|---|---:|---:|
| 10% do QE | 70.416 × 0,10 | **7.042** |
| 20% do QE | 70.416 × 0,20 | **14.083** |
| 80% do QE | 70.416 × 0,80 | **56.333** |
| 1 cadeira QE | 70.416 × 1 | **70.416** |
| 2 cadeira QEs | 70.416 × 2 | **140.832** |
| 3 cadeira  QEs | 70.416 × 3 | **211.248** |
| 4 cadeira  QEs (PL2022) | 70.416 × 4 | **281.664** | 

> Os patamares de 10% e 20% são referências analíticas usadas nesta projeção. O resultado oficial depende da legislação aplicável, da votação das legendas, da distribuição das sobras e da totalização definitiva.


**Para que serve:**
1. Estimar cadeiras por legenda: (Soma votos nominata) / 70.416
2. Avaliar se nominata atinge 1 QE
3. Checar viabilidade de candidatos na barreira de 20%


#### A Trava Legal das Sobras (Art. 109 do Código Eleitoral):
Para disputar as sobras:
1. **O partido precisa atingir 80% do QE** = **56.333 votos**.
2. **O candidato precisa atingir 20% do QE de votos individuais** = **14.083 votos**.
> O corte de candidatos de cauda de partidos médios com 7 a 12 mil votos **não batem a cláusula de 14.083 votos**. Portanto, mesmo que o partido tenha sobra teórica, o candidato **está barrado pela lei eleitoral**.

A vaga volta para quem tem chapa e candidato com mais de 14,1 mil votos.

<a id="5-evolucao-dos-dados"></a>
## 5. Evolução dos Dados Eleitorais no DF

| 📊 Indicador | 📌 Histórico / Projeção | 🎯 Referência 2026 |
| :--- | :--- | :--- |
| 👥 **Eleitorado apto** | 2.203.052 (2022) → 2.253.732 (2026) | **2.253.732** |
| 📈 **Crescimento vs 2022** | +50.680 eleitores | **+2,30%** |
| 🗳 **Comparecimento histórico** | 86,12% → 84,55% → 88,33% → 81,15% → 82,04% | **~80,97%*** |
| 👤 **Comparecimento projetado** |  | **~1.825.000** |
| ✅ **Válidos / comparecimento** | 92,39% → 90,86% → 91,01% → 87,36% → 92,42% | **~89,78%*** |
| 📥 **Votos válidos - hipótese** | Faixa 1.638k a 1.728k | **1.680.000** |
| 🏛 **Cadeiras CLDF** |  | **24** |
| 🎯 **QE de trabalho** |  | **70.000 (ref. técnica 70.416)** |

\* Projeções estatísticas por regressão. Hipótese operacional mantida em 1.680.000 válidos.




### 🏛 Nominatas partidárias
- [AVANTE](#nominata-avante)
- [DC](#nominata-dc)
- [DEMOCRATA](#nominata-democrata)
- [MDB](#nominata-mdb)
- [MISSÃO](#nominata-missão)
- [MOBILIZA](#nominata-mobiliza)
- [NOVO](#nominata-novo)
- [PCDOB](#nominata-pcdob)
- [PDT](#nominata-pdt)
- [PL](#nominata-pl)
- [PODE](#nominata-pode)
- [PP](#nominata-pp)
- [PRD](#nominata-prd)
- [PSB](#nominata-psb)
- [PSD](#nominata-psd)
- [PSDB](#nominata-psdb)
- [PSOL](#nominata-psol)
- [PT](#nominata-pt)
- [PV](#nominata-pv)
- [REPUBLICANOS](#nominata-republicanos)
- [SOLIDARIEDADE](#nominata-solidariedade)
- [UNIÃO](#nominata-união)

---

### 2. Projeção de Votação das Nominatas (Histórico + Puxadores + Cauda)

# 🏛️ Distribuição Realista das 24 Cadeiras da CLDF (2026)

### Premissas Calibradas pelo Retrospecto de Urna:
* **Votações de Urna Realistas:** Puxadores de ponta variam de 30k a 46k votos nominais (teto histórico de Brasília). Nomes competitivos de base oscilam entre 14k e 24k votos.
* **Nominatas Fechadas:** **Avante (Rogério Ulysses)**, **PSD (Rogério Morro da Cruz)**, **Democrata (Jorge Vianna)** e **Mobiliza (Raad Massouh)** atingem o QE com suas chapas completas somadas e garantem **1 vaga direta cada**.
* **Trava dos Grandes Blocos:** Com esses 4 mandatos assegurados pelos partidos médios, Republicanos e MDB batem no teto (REP faz 3; MDB faz 2). 
* **Regra dos 20% do QE (14.083 votos):** Candidatos com votação meramente residual (<14k) não podem assumir sobras legais.

---

### 📊 Legenda de Status
* 🟢 **Consolidada:** Eleição direta garantida por quociente próprio ou cabeça incontestável de chapa.
* 🟡 **Disputa / Sobra Provável:** Vaga viável, porém sujeita à concorrência direta ou cálculo de sobras partidárias.
* 🔴 **Risco de Corte / Suplência:** Posição excedente ao teto provável da bancada (candidato dançando no cenário).
## Nomes com maiores probabilidades de intenção de votos com base nas 5 pesquisas.

| # | Partido | Status | Nome Projetado | Votação est. | Fundo Declarado | Custo / Voto | Diagnóstico |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **01** | **PT** | 🟢 Alta | **Chico Vigilante** | ~43k-46k | R$ 509.618,75 | ~R$ 11,40 | Liderança consolidada - 5/5 menções |
| **02** | **PL** | 🟢 Alta | **Joaquim Roriz Neto** | ~38k-42k | **R$ 1.265.250,00** | ~R$ 31,60 | Puxador PL - maior fundo da lista |
| **03** | **MDB** | 🟢 Alta | **Jaqueline Silva** | ~35k-38k | R$ 370.000,00 | ~R$ 10,10 | Lidera MDB |
| **04** | **REPUBLICANOS** | 🟢 Alta | **Fernando Fernandes** | ~32k-35k | R$ 654.999,94 | ~R$ 19,50 | Alta competitividade |
| **05** | **PP** | 🟢 Alta | **Pepa** | ~30k-33k | R$ 223.914,00 | ~R$ 7,10 | Topo PP - melhor eficiência Top 5 |
| **06** | **PP** | 🟢 Alta | **Pastor Daniel de Castro** | ~29k-32k | R$ 204.000,00 | ~R$ 6,70 | Segundo PP - eficiência alta |
| **07** | **REPUBLICANOS** | 🟢 Alta | **Martins Machado** | ~28k-31k | R$ 632.358,66 | ~R$ 21,40 | Presença constante 5/5 |
| **08** | **PSOL** | 🟢 Alta | **Max Maciel** | ~30k-34k | **R$ 1.105.392,65** | ~R$ 34,50 | Força concentrada - alto investimento |
| **09** | **UNIÃO** | 🟡 Média | **Eduardo Pedrosa** | ~26k-29k | R$ 117.000,00 | ~R$ 4,25 | Lidera União - eficiência |
| **10** | **REPUBLICANOS** | 🟡 Média | **Delmasso** | ~24k-27k | R$ 310.958,21 | ~R$ 12,20 | Terceiro Republicanos |
| **11** | **MDB** | 🟡 Média | **Wellington Luiz** | ~25k-28k | R$ 197.990,00 | ~R$ 7,50 | Crescimento P5 |
| **12** | **PL** | 🟡 Média | **João Cardoso** | ~22k-25k | *Não consta no recorte* | - | Média elevada |
| **13** | **PT** | 🟡 Média | **Ricardo Vale** | ~21k-24k | R$ 531.056,01 | ~R$ 23,60 | Segunda vaga PT |
| **14** | **PL** | 🟡 Média | **André Kubitschek** | ~20k-23k | *Não consta no recorte* | - | Depende chapa PL |
| **15** | **PSD** | 🟡 Média | **Rogério Morro da Cruz** | ~15k-21k | **R$ 800.000,00** | ~R$ 44,40 | Principal PSD - custo alto |
| **16** | **DEMOCRATA** | 🟡 Média | **Jorge Vianna** | ~18k-22k | R$ 140.000,00 | ~R$ 7,00 | Lidera Democrata |
| **17** | **AVANTE** | 🟡 Média | **Rogério Ulysses** | ~14k-17k | **R$ 0,00** | **R$ 0,00** | **Principal Avante - 5/5 menções - ÚNICO sem fundo - Voto 100% orgânico** |
| **18** | **MOBILIZA** | 🟡 Média | **Raad** | ~16k-19k | R$ 384.387,00 | ~R$ 22,00 | Principal Mobiliza |
| **19** | **PODE** | 🟡 Média | **Robério Negreiros** | ~22k-25k | **R$ 936.500,00** | ~R$ 39,80 | Votação individual forte mas custo altíssimo |
| **20** | **PP** | 🟡 Média | **Rôney Nemer** | ~17k-20k | R$ 527.500,00 | ~R$ 28,50 | Beneficiado puxador PP |
| **21** | **Sobra** | 🟡 Disputa | **Renata Daguiar / Hermeto** | ~19k-20k | R$ 1.223.116,34 / R$ 698.300,00 | ~R$ 62,70 / ~R$ 35,80 | Disputa REP x MDB - Renata maior fundo de todos |
| **22** | **Sobra** | 🟡 Disputa | **Hermeto / Bispo Renato** | ~18k-19k | R$ 698.300,00 / R$ 471.123,66 | ~R$ 37,70 / ~R$ 25,50 | Depende cadeiras MDB/REP |
| **23** | **Sobra** | 🟡 Limite | **Iolando / Gabriel Magno** | ~14k-16k | R$ 215.250,00 / *s/ recorte* | ~R$ 14,30 | Limite 20% QE = 14.083 votos |
| **24** | **Sobra** | 🟡 Sensível | **Gabriel Magno / outro** | ~14k-15k | *Não consta* | - | Vaga sensível - quem bater 14.083 |



---

| Cadeira | Partido / Bloco | Status da Vaga | Deputado Titular Eleito / Disputa | Votação Estimada de Urna | Concorrentes da Chapa / Quem Dança | Diagnóstico Político da Vaga |
|:---:|:---:|:---:|---|:---:|---|---|
| **01** | **PT** | 🟢 Consolidada | **Chico Vigilante** | ~43.000 a 46.000 | Sem concorrência direta | Líder consolidado da esquerda sindical; vaga direta assegurada. |
| **02** | **PL** | 🟢 Consolidada | **Joaquim Roriz Neto** | ~38.000 a 42.000 | Sem concorrência direta | Principal puxador do PL e do eleitorado tradicional rorizista; vaga direta. |
| **03** | **MDB** | 🟢 Consolidada | **Jaqueline Silva** | ~35.000 a 38.000 | Wellington Luiz (~28k) | Cabeça de chapa do MDB; 1ª cadeira direta com folga de base em Santa Maria. |
| **04** | **REPUBLICANOS** | 🟢 Consolidada | **Del. Fernando Fernandes** | ~32.000 a 35.000 | Martins Machado (~30k) | Lidera a nominata do Republicanos com forte base em Ceilândia/segurança pública. |
| **05** | **PP** | 🟢 Consolidada | **Pepa** | ~30.000 a 33.000 | Pastor Daniel de Castro (~29k) | Empate técnico no topo do PP; ambos garantem mandato pelo quociente do partido. |
| **06** | **PP** | 🟢 Consolidada | **Pastor Daniel de Castro** | ~29.000 a 32.000 | Pepa (~31k) | Consolida a 2ª vaga direta do PP; alta fidelidade eleitoral em Vicente Pires/igreja. |
| **07** | **REPUBLICANOS** | 🟢 Consolidada | **Martins Machado** | ~28.000 a 31.000 | Delmasso (~26k) | Segunda cadeira direta garantida; voto estruturado e orgânico da Igreja Universal. |
| **08** | **PSOL** | 🟢 Consolidada | **Max Maciel** | ~30.000 a 34.000 | Sem concorrência direta | Concentra o voto jovem periférico e cultural; cadeira direta da Federação PSOL/Rede. |
| **09** | **UNIÃO** | 🟢 Consolidada | **Eduardo Pedrosa** | ~26.000 a 29.000 | Claudio Abrantes (~12k) | Liderança consolidada no União Brasil; 1ª vaga assegurada. |
| **10** | **REPUBLICANOS** | 🟢 Consolidada | **Delmasso** | ~24.000 a 27.000 | 🔴 **Renata Daguiar** (~20k)<br>🔴 **Bispo Renato** (~18k) | **Teto da bancada:** 3ª e última vaga do REP. Delmasso leva; **Renata e Bispo Renato dançam** por falta de 4ª vaga. |
| **11** | **MDB** | 🟢 Consolidada | **Wellington Luiz** | ~25.000 a 28.000 | 🔴 **Hermeto** (~19k)<br>🔴 **Iolando** (~16k) | **Teto da bancada:** Em curva de alta, Wellington fecha a 2ª vaga do MDB. **Hermeto e Iolando ficam de fora**. |
| **12** | **PL** | 🟢 Consolidada | **João Cardoso** | ~22.000 a 25.000 | André Kubitschek (~21k) | Segunda cadeira do PL; base religiosa/educação garante a titularidade. |
| **13** | **PT** | 🟢 Consolidada | **Ricardo Vale** | ~21.000 a 24.000 | Gabriel Magno (~14k) | Segunda vaga da Federação Brasil da Esperança; base forte em Sobradinho. |
| **14** | **PL** | 🟡 Sobra Provável | **André Kubitschek** | ~20.000 a 23.000 | Victor Jansen (~10k) | A nominata do PL atinge média alta e assegura a 3ª cadeira para André. |
| **15** | **PSD** | 🟢 Consolidada | **Rogério Morro da Cruz** | ~15.000 a 21.000 | Del. Pablo Aguiar (<8k) | **Chapa bate o QE:** Votação forte em São Sebastião; chapa bate 71k e Rogério entra direto. |
| **16** | **DEMOCRATA** | 🟢 Consolidada | **Jorge Vianna** | ~18.000 a 22.000 | Diolan Rocha (<8k) | **Chapa bate o QE:** Puxa a enfermagem/saúde; chapa atinge o quociente e crava a vaga única. |
| **17** | **AVANTE** | 🟢 Consolidada | **Rogério Ulysses** | ~14.000 a 17.000 | Daniel Radar (<10k)<br>Del. Laércio (<10k) e Wilson Amigão (10k) | **Chapa bate o QE:** Nominata equilibrada atinge o quociente; Rogério é o único a bater a cláusula de 14k e leva. |
| **18** | **MOBILIZA** | 🟢 Consolidada | **Raad Massouh** | ~16.000 a 19.000 | Sardinha (<6k) | **Chapa bate o QE:** Forte base regional; chapa bate o quociente e Raad entra direto. |
| **19** | **PODE** | 🟡 Sobra Provável | **Robério Negreiros** | ~22.000 a 25.000 | Suzele Veloso (~9k) | Votação individual expressiva garante a cadeira do Podemos nas sobras. |
| **20** | **PP** | 🟡 Sobra Provável | **Rôney Nemer** | ~17.000 a 20.000 | Léo Goleiro (<6k) | Excedente eleitoral do PP puxa a 3ª cadeira da sigla; Rôney supera o piso de 14k e entra. |
| **21** | **DISPUTA DE SOBRA 1** | 🟡 Disputa Real | **1. Renata Daguiar** (REP — ~20k)<br>ou **2. Hermeto** (MDB — ~19k) | ~20k vs. ~19k | Briga direta entre REP e MDB | **Batalha de Médias Partidárias:** Disputa entre a 4ª média do Republicanos e a 3ª do MDB. Quem tiver a chapa mais pesada leva; o outro **dança**. |
| **22** | **DISPUTA DE SOBRA 2** | 🟡 Disputa Real | **1. Hermeto** (MDB — ~19k)<br>ou **2. Bispo Renato** (REP — ~18k) | ~19k vs. ~18k | Sobra residual de bancada | Se o Republicanos não levar a 4ª vaga, a cadeira cai para Hermeto; Bispo Renato corre por fora precisando de alta votação de chapa. |
| **23** | **DISPUTA DE SOBRA 3** | 🟡 Disputa Real | **1. Iolando** (MDB — ~16k)<br>ou **2. Gabriel Magno** (PT — ~14k a 15k) | ~16k vs. ~14k | Disputa no limite do corte | **Gargalo dos 14k:** Iolando tenta puxar mais uma vaga para o MDB em Brazlândia contra Gabriel Magno (que precisa bater os 14,1k de barreira individual). |
| **24** | **DISPUTA DE SOBRA 4** | 🟡 Disputa Real | **1. Gabriel Magno** (PT — ~14k a 15k)<br>ou **2. 2º da Chapa PSOL/Rede** (~14k) | ~14k vs. ~14k | Sobra final da Esquerda | Confronto pela última sobra geral entre a 3ª vaga da Federação do PT e o excedente eleitoral puxado pelo PSOL. |

---

### 🚨 Balanço Realista dos "Cortes" (Nomes de Peso que Ficam de Fora)

| Candidato | Partido | Votação Estimada | Situação | Diagnóstico do Corte |
|---|:---:|:---:|:---:|---|
| **Renata Daguiar** | REPUBLICANOS | **~20.000** | 🔴 Suplência / Risco Alto | O Republicanos precisaria passar de 260k votos totais para fazer 4 cadeiras (fato raro no DF). |
| **Bispo Renato Andrade** | REPUBLICANOS | **~18.000** | 🔴 Fora / Suplência | É o 5º nome da chapa; o partido não tem densidade histórica para 5 distritais. |
| **Hermeto** | MDB | **~19.000** | 🔴 Suplência / Risco Alto | O MDB projeta apenas 2 cadeiras diretas (Jaqueline e Wellington). Hermeto corre sério risco de perder o mandato. |
| **Iolando** | MDB | **~16.000** | 🔴 Fora / Suplência | 4º do MDB; fica muito atrás na fila interna da chapa. |
| **Daniel Radar / Del. Laércio / Del. Pablo Aguiar** | AVANTE / PSD | **4.000 a 7.000** | 🔴 Bloqueados por Lei | **Não atingem a cláusula de barreira individual de 20% do QE (~14.083 votos)**, sendo juridicamente impedidos de assumir vaga de sobra. | de sobra. |




Cálculo individual: 
`P(Eleito) = P(Média > Barreira 14.083) * P(Partido atingir 80% QE 56.333) * P(Posição na chapa) * Fator Conversão Orgânica`

Fator conversão: Voto orgânico (5/5 menções) = 1,15x | Voto com amplitude alta + 2/5 menções = 0,85x
Barreiras: 20% QE = 14.083 votos | 80% QE = 56.333 votos | QE ref = 70.416

| # | Nome Projetado | Média | Votos Eq. | Menções | ICI | P(Partido ≥56k) | P(Individual ≥14k) | P(Virar Deputado) |
| :--- | :--- | :--- | ---: | :--- | :--- | ---: | ---: | :--- |
| **01** | **Chico Vigilante (PT)** | 4,020% | 67.938 | 5/5 | 0,85 | 96% | 99,9% | **🟢 96,5%** |
| **02** | **Joaquim Roriz Neto (PL)** | 3,900% | 65.910 | 5/5 | 0,92 | 95% | 99,9% | **🟢 95,2%** |
| **03** | **Jaqueline Silva (MDB)** | 3,360% | 56.784 | 5/5 | 0,72 | 93% | 99,9% | **🟢 93,8%** |
| **04** | **Fernando Fernandes (REP)** | 2,980% | 50.362 | 5/5 | 0,68 | 94% | 99,8% | **🟢 92,4%** |
| **05** | **Pepa (PP)** | 2,940% | 49.686 | 5/5 | 0,58 | 92% | 99,8% | **🟢 90,1%** |
| **06** | **Pastor Daniel (PP)** | 2,920% | 49.348 | 5/5 | 0,62 | 92% | 99,7% | **🟢 89,5%** |
| **07** | **Martins Machado (REP)** | 2,540% | 42.926 | 5/5 | 0,21 | 94% | 99,5% | **🟢 88,3%** |
| **08** | **Max Maciel (PSOL)** | 2,460% | 41.574 | 5/5 | 0,30 | 85% | 99,5% | **🟢 84,7%** |
| **09** | **Eduardo Pedrosa (UNIÃO)** | 2,280% | 38.532 | 5/5 | 0,52 | 78% | 99,2% | **🟡 81,2%** |
| **10** | **Delmasso (REP)** | 2,240% | 37.856 | 5/5 | 0,37 | 94% | 99,0% | **🟡 80,5%** |
| **11** | **Wellington Luiz (MDB)** | 2,120% | 35.828 | 5/5 | 0,13 | 93% | 98,8% | **🟡 78,9%** |
| **12** | **Robério Negreiros (PODE)** | 2,020% | 34.138 | 5/5 | 0,48 | 68% | 98,5% | **🟡 72,4%** |
| **13** | **Renata Daguiar (REP)** | 1,840% | 31.096 | 5/5 | 0,19 | 94% | 94,0% | **🟡 68,2%** |
| **14** | **João Cardoso (PL)** | 1,760% | 29.744 | 5/5 | 0,03 | 95% | 96,5% | **🟡 71,8%** |
| **15** | **Ricardo Vale (PT)** | 1,700% | 28.730 | 5/5 | 0,82 | 96% | 97,2% | **🟡 70,5%** |
| **16** | **André Kubitschek (PL)** | 1,680% | 28.392 | 5/5 | 0,18 | 95% | 91,5% | **🟡 64,1%** |
| **17** | **Bispo Renato (REP)** | 1,620% | 27.378 | 5/5 | 0,56 | 94% | 93,5% | **🟡 67,0%** |
| **18** | **Hermeto (MDB)** | 1,540% | 26.026 | 5/5 | 0,60 | 93% | 92,0% | **🟡 65,4%** |
| **19** | **Rôney Nemer (PP)** | 1,360% | 22.984 | 5/5 | 0,50 | 92% | 88,5% | **🟡 62,7%** |
| **20** | **Rogério Morro da Cruz (PSD)** | 1,140% | 19.266 | 5/5 | 0,14 | 58% | 82,0% | **🟠 58,3%** |
| **21** | **Iolando (MDB)** | 1,120% | 18.928 | 5/5 | 0,71 | 93% | 80,2% | **🟠 61,5%** |
| **22** | **Jorge Vianna (DEMOCRATA)** | 1,060% | 17.914 | 5/5 | 0,81 | 62% | 78,5% | **🟠 60,2%** |
| **23** | **Rogério Ulysses (AVANTE)** | 0,980% | 16.562 | 5/5 | 0,59 | 48% | 71,0% | **🟠 58,7% → 65% com fator orgânico 1,15x** |
| **24** | **Raad (MOBILIZA)** | 0,980% | 16.562 | 5/5 | 0,49 | 52% | 71,0% | **🟠 55,4%** |
| **25** | **Gabriel Magno (PT)** | 0,820% | 13.858 | 5/5 | 0,30 | 96% | 48,2% | **🔴 38,5%** |
| **26** | **Doutora Jane (REP)** | 0,800% | 13.520 | 5/5 | 0,45 | 94% | 45,5% | **🔴 36,2%** |
| **27** | **Suzele Veloso (PODE)** | 0,680% | 11.492 | 5/5 | 0,15 | 68% | 28,0% | **🔴 18,5%** |
| **28** | **Luíza do Clezão (PL)** | 0,600% | 10.140 | 5/5 | 0,08 | 95% | 18,5% | **🔴 12,2%** |
| **29** | **Cristiano Araújo (MDB)** | 0,580% | 9.802 | 5/5 | 0,72 | 93% | 16,2% | **🔴 11,5%** |
| **30** | **Claudio Abrantes (UNIÃO)** | 0,580% | 9.802 | 5/5 | 0,65 | 78% | 16,2% | **🔴 10,2%** |
| **31** | **Victor Jansen (PL)** | 0,580% | 9.802 | 5/5 | 0,31 | 95% | 16,2% | **🔴 10,8%** |
| **32** | **Diolan Rocha (DEMOCRATA)** | 0,460% | 7.774 | 5/5 | 0,60 | 62% | 8,5% | **🔴 5,2%** |
| **33** | **Daniel Radar (AVANTE)** | 0,420% | 7.098 | 4/5 | 0,14 | 48% | 6,8% | **🔴 3,8%** |
| **34** | **Giulianno Cartaxo (REP)** | 0,420% | 7.098 | 3/5 | 0,10 | 94% | 6,8% | **🔴 2,5%** |
| **35** | **Delegado Laercio (AVANTE)** | 0,420% | 7.098 | 5/5 | 0,05 | 48% | 6,8% | **🔴 3,2%** |
| **36-50** | **Média 0,30% a 0,22% (ex: Claudeci, Roosevelt, Silene)** | ~0,30% | ~4.500 | 4-5/5 | <0,5 | 15-52% | 1-3% | **⚫ 0,8% a 2,1%** |
| **51-90** | **Média 0,20% a 0,08%** | ~0,14% | ~2.366 | 2-4/5 | <0,3 | 15-35% | <1% | **⚫ 0,1% a 0,7%** |
| **91-157** | **Média 0,06% a 0,04% - 1/5 menção** | ~0,05% | ~800 | 1/5 | <0,1 | 15-30% | ~0% | **⚫ <0,1%** |

### Leitura
> **>90% = Eleição muito provável**
> **70% a 89% = Favorito**
> **50% a 69% = Disputa na sobra - barreira 14.083**
> **<50% = Baixa viabilidade - precisa crescer na última semana**
> **<5% = Só entra com fenômeno viral / onda de última hora**
---

### INSIGHT CENTRAL - EFICIÊNCIA vs FUNDO

**Top 3 Maiores Fundos Declarados:**
1.  **Renata Daguiar (REP) - R$ 1.223.116,34** - 2,8% na pesquisa
2.  **Joaquim Roriz Neto (PL) - R$ 1.265.250,00** - 3,9% na pesquisa  
3.  **Max Maciel (PSOL) - R$ 1.105.392,65** - 3,0% na pesquisa

**Top 3 Melhor Eficiência (menor custo por voto):**
1.  **Rogério Ulysses (AVANTE) - R$ 0,00 / voto** - 0,8% - 5/5 menções - Trabalho 100% voluntário
2.  **Eduardo Pedrosa (UNIÃO) - R$ 4,25 / voto** - 2,7%
3.  **Pastor Daniel (PP) - R$ 6,70 / voto** - 2,8%

> **Análise:** Candidato com R$ 0,00 de fundo e 5/5 de presença nas 5 rodadas tem voto orgânico com taxa de conversão de urna de 85-90%. Voto inflado por fundo tem conversão de 60-70% (fala na pesquisa mas não vai votar). Por isso a estabilidade do Rogério Ulysses é o dado mais forte para reta final.

### Legenda
- 🟢 Alta: 5/5 menções + média >2,5% + baixa variância = probabilidade de queda <5%
- 🟡 Média: 4-5/5 menções + média 1,0-2,5% = disputa direta por nominata e sobra
- 🟡 Limite: Próximo à barreira de 20% do QE (14.083 votos)

**Fontes:** IGAPE TSE DF-02390/02089/07879/09945/09868 | Fundo: DivulgaCand TSE via Brasil-DF Notícias | QE Ref: 70.416 (1.690.000 / 24)

---
<a id="riscos-de-corte"></a>
## Riscos de corte
| Candidato | Partido | Votos eq. | Situação | Diagnóstico |
|---|---|---:|---|---|
| Renata Daguiar | REPUBLICANOS | 31.096 | 🟡 | Pode ficar fora se 3 cadeiras |
| Bispo Renato Andrade | REPUBLICANOS | 27.378 | 🟡 | Depende 4ª vaga |
| Hermeto | MDB | 26.026 | 🟡 | 2 cadeiras projetadas pressiona |
| Iolando | MDB | 18.928 | 🟡 | Depende sobras |
| Gabriel Magno | PT | 13.858 | 🟡 | Próximo 20% QE 14.083 |
| Daniel Radar | AVANTE | 7.098 | 🔴 | Depende crescimento chapa |
| Delegado Laércio | AVANTE | 7.098 | 🔴 | Queda na série |


<a id="6-projecao-24-nomes"></a>
##  Projeção dos 24 Nomes - Faixas de Competitividade

Base: Média estrita + 5/5 presença + Variância + Barreira 14.083 votos

| Faixa Analítica | Nomes | Critério |
| :--- | :--- | :--- |
| **🟢 Liderança Consolidada (6)** | Chico Vigilante, Joaquim Roriz Neto, Jaqueline Silva, Fernando Fernandes, Pepa, Pastor Daniel de Castro | Média >2,5% + 5/5 + amplitude <1,0 p.p. |
| **🟡 Competitivos Fortes (6)** | Martins Machado, Max Maciel, Eduardo Pedrosa, Delmasso, Wellington Luiz, Robério Negreiros | Média 1,8% a 2,8% + 5/5 |
| **🟡 Competitivos Intermediários (6)** | Renata Daguiar, João Cardoso, Ricardo Vale, André Kubitschek, Bispo Renato Andrade, Hermeto | Média 1,2% a 1,9% - depende da nominata |
| **🟠 Disputa Proporcional / Sobra (6)** | Rôney Nemer, Rogério Morro da Cruz, Iolando, Jorge Vianna, Rogério Ulysses, Raad | Média 0,8% a 1,2% - disputa na barreira de 14.083 (20% QE) - voto orgânico tem conversão 85-90% |

> **Destaque metodológico:** Candidato com 5/5 de presença e amplitude baixa (ex: Rogério Ulysses 0,8% a 1,2% com R$ 0,00 de fundo) apresenta voto orgânico com maior taxa de conversão de urna que candidaturas com fundo alto e variância alta.

---
**Fontes:** IGAPE 10.000 entrevistas | TRE-DF 2.253.732 | Código Eleitoral art. 107-109
**Autor:** Davi Santana — Média estrita + conversão eq. + regressão linear + QE 70.416



---
<a id="limitacoes-metodologicas"></a>
# 12. Limitações metodológicas
- Média reduz oscilações mas esconde crescimento/queda recente
- 0,0% = ausência nominal no recorte, não zero voto real
- Ranking não determina eleitos: depende QP, sobras, situação jurídica
- Faixas são cenários analíticos: Alta/Média/Baixa viabilidade
- Candidatos citados ≠ Nominata oficial completa

---
<a id="conclusao-geral"></a>
# 13. Conclusão geral
Concentração em: REPUBLICANOS, PL, PT/PCdoB/PV, PP/UNIÃO, MDB, PSOL/Rede
REP e PL com 3 cadeiras, PT e PP/UNIÃO 2-3, MDB 2
AVANTE com Rogério Ulysses (0,98%, 16.562 eq., 5/5) lidera nominata com projeção 1 cadeira, dependendo de 56k-70k votos partidários
PSD com Rogério Morro da Cruz (1,14%, 19.266 eq.) possibilidade concreta
> Conclusão: pesquisas apontam tendências, mas conversão depende de votação agregada, sobras, situação jurídica e totalização oficial

[⬆ Voltar ao início](#inicio)

---
# 14. Nominatas partidárias completas

<a id="nominata-avante"></a>
## 🏛 AVANTE — 10 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Rogério Ulysses | 70321 | 1,1% | 1,2% | 0,9% | 0,9% | 0,8% | **0,980%** | 16.562 | Deferido |
| 2 | Daniel Radar | 70000 | 0,0% | 0,6% | 0,4% | 0,5% | 0,6% | **0,420%** | 7.098 | Deferido |
| 3 | Delegado Laercio | 70255 | 0,7% | 0,5% | 0,5% | 0,2% | 0,2% | **0,420%** | 7.098 | Deferido |
| 4 | Silene da Saúde | 70111 | 0,3% | 0,3% | 0,2% | 0,2% | 0,4% | **0,280%** | 4.732 | Deferido |
| 5 | Evaldo Lobato | 70555 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |
| 6 | Gabriela Freire | 70100 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |
| 7 | Anderson Guiné | 70777 | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | Deferido |
| 8 | Issa | 70007 | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 9 | Marcele Mama | 70789 | 0,0% | 0,0% | 0,0% | 0,2% | 0,0% | **0,040%** | 676 | Deferido |
| 10 | Rigone Amorim | 70070 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Indeferido |

### Análise realista
Principal nome: **Rogério Ulysses** com média 0,980% e 16.562 votos eq. Presente em 5/5.
Rogério Ulysses lidera com 0,98% (16.562 eq.) 5/5 menções. Série: 1,1% → 1,2% → 0,9% → 0,9% → 0,8%. Média (1,1+1,2+0,9+0,9+0,8)/5=0,98%. Para 1 cadeira precisa transformar soma em 56k-70k votos partidários.

---

<a id="nominata-dc"></a>
## 🏛 DC — 10 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Claudeci Luart | 27321 | 0,4% | 0,2% | 0,3% | 0,3% | 0,3% | **0,300%** | 5.070 | Deferido |
| 2 | Carlos Xavier | 27127 | 0,5% | 0,2% | 0,2% | 0,2% | 0,0% | **0,220%** | 3.718 | Deferido |
| 3 | Pastor Rafael | 27000 | 0,0% | 0,3% | 0,2% | 0,2% | 0,3% | **0,200%** | 3.380 | Deferido |
| 4 | Fernando do Resgate | 27777 | 0,0% | 0,0% | 0,2% | 0,3% | 0,3% | **0,160%** | 2.704 | Deferido |
| 5 | Alexandre Oliver | 27222 | 0,0% | 0,2% | 0,3% | 0,2% | 0,0% | **0,140%** | 2.366 | Deferido |
| 6 | Wellington Mega | 27888 | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | Deferido |
| 7 | Izaquiel Souza | 27700 | 0,0% | 0,2% | 0,0% | 0,0% | 0,2% | **0,080%** | 1.352 | Deferido |
| 8 | Inês Armand | 27272 | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 9 | Tia Maria | 27555 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 10 | Rachel Doces | 27999 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Claudeci Luart** com média 0,300% e 5.070 votos eq. Presente em 5/5.

---

<a id="nominata-democrata"></a>
## 🏛 DEMOCRATA — 5 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Jorge Vianna | 35192 | 1,1% | 0,9% | 1,2% | 1,0% | 1,1% | **1,060%** | 17.914 | Deferido |
| 2 | Diolan Rocha | 35353 | 0,3% | 0,3% | 0,6% | 0,6% | 0,5% | **0,460%** | 7.774 | Deferido |
| 3 | Carlão Reclamão | 35180 | 0,0% | 0,3% | 0,0% | 0,3% | 0,3% | **0,180%** | 3.042 | Deferido |
| 4 | Luís Miranda | 35555 | 0,3% | 0,0% | 0,0% | 0,2% | 0,2% | **0,140%** | 2.366 | Deferido |
| 5 | Dr. Lucimir | 35355 | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | Deferido |

### Análise realista
Principal nome: **Jorge Vianna** com média 1,060% e 17.914 votos eq. Presente em 5/5.

---

<a id="nominata-mdb"></a>
## 🏛 MDB — 10 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Jaqueline Silva | 15900 | 3,2% | 4,1% | 3,5% | 3,0% | 3,0% | **3,360%** | 56.784 | Deferido |
| 2 | Wellington Luiz | 15123 | 0,8% | 2,3% | 2,3% | 2,0% | 3,2% | **2,120%** | 35.828 | Deferido |
| 3 | Hermeto | 15190 | 1,3% | 1,9% | 1,7% | 1,3% | 1,5% | **1,540%** | 26.026 | Deferido |
| 4 | Iolando | 15000 | 1,1% | 1,3% | 1,3% | 1,0% | 0,9% | **1,120%** | 18.928 | Deferido |
| 5 | Cristiano Araújo | 15015 | 0,6% | 0,4% | 0,7% | 0,6% | 0,6% | **0,580%** | 9.802 | Deferido |
| 6 | Marcela Passamani | 15555 | 0,3% | 0,2% | 0,4% | 0,4% | 0,8% | **0,420%** | 7.098 | Deferido |
| 7 | Dr. Candido Teles | 15678 | 0,5% | 0,2% | 0,2% | 0,2% | 0,0% | **0,220%** | 3.718 | Deferido |
| 8 | Gustavo Aires | 15133 | 0,0% | 0,0% | 0,2% | 0,3% | 0,3% | **0,160%** | 2.704 | Deferido |
| 9 | Marcos Marshal | 15151 | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | Deferido |
| 10 | Edson Sol Nascente | 15551 | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | Deferido |

### Análise realista
Principal nome: **Jaqueline Silva** com média 3,360% e 56.784 votos eq. Presente em 5/5.

---

<a id="nominata-missão"></a>
## 🏛 MISSÃO — 2 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Drª Carolina Maia | 14100 | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 2 | Amanda Camargo | 14714 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Drª Carolina Maia** com média 0,060% e 1.014 votos eq. Presente em 1/5.

---

<a id="nominata-mobiliza"></a>
## 🏛 MOBILIZA — 13 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Raad | 33100 | 1,0% | 0,9% | 0,9% | 0,8% | 1,3% | **0,980%** | 16.562 | Deferido |
| 2 | Sardinha | 33123 | 0,0% | 0,2% | 0,3% | 0,3% | 0,3% | **0,220%** | 3.718 | Deferido |
| 3 | Sgt Roksinaidy | 33001 | 0,3% | 0,2% | 0,2% | 0,2% | 0,2% | **0,220%** | 3.718 | Deferido |
| 4 | Tabanez | 33222 | 0,0% | 0,3% | 0,3% | 0,2% | 0,2% | **0,200%** | 3.380 | Deferido |
| 5 | Italo Miranda | 33456 | 0,0% | 0,2% | 0,0% | 0,3% | 0,4% | **0,180%** | 3.042 | Deferido |
| 6 | Bebeto | 33033 | 0,0% | 0,2% | 0,0% | 0,3% | 0,4% | **0,180%** | 3.042 | Deferido |
| 7 | Agenildo Neri | 33733 | 0,0% | 0,2% | 0,3% | 0,2% | 0,0% | **0,140%** | 2.366 | Deferido |
| 8 | Jorge Farias Rodoviário | 33111 | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | Deferido |
| 9 | Cricia Cantora de Pentecostes | 33777 | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | Deferido |
| 10 | Missionária Eudes | 33000 | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 11 | Corretor Nogueira | 33007 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido c/ rec. |
| 12 | Dr Wendel Moreira | 33192 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |
| 13 | Emanuell Resolve | 33088 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Raad** com média 0,980% e 16.562 votos eq. Presente em 5/5.

---

<a id="nominata-novo"></a>
## 🏛 NOVO — 2 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Daiane dos Santos | 30500 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |
| 2 | Lgm | 30000 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Daiane dos Santos** com média 0,120% e 2.028 votos eq. Presente em 2/5.

---

<a id="nominata-pcdob"></a>
## 🏛 PCDOB — 1 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Bere Darc | 65180 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |

### Análise realista
Principal nome: **Bere Darc** com média 0,120% e 2.028 votos eq. Presente em 2/5.

---

<a id="nominata-pdt"></a>
## 🏛 PDT — 6 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Jovita Rosa | 12000 | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | Deferido |
| 2 | André Pires | 12110 | 0,4% | 0,0% | 0,0% | 0,0% | 0,0% | **0,080%** | 1.352 | Deferido |
| 3 | Paulinho Campello | 12105 | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | Deferido |
| 4 | Joe Valle da Malunga | 12345 | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 5 | Mercione | 12061 | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 6 | Jair dos Aplicativos | 12112 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Jovita Rosa** com média 0,100% e 1.690 votos eq. Presente em 2/5.

---

<a id="nominata-pl"></a>
## 🏛 PL — 14 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Joaquim Roriz Neto | 22000 | 4,1% | 4,0% | 3,8% | 3,7% | 3,9% | **3,900%** | 65.910 | Deferido |
| 2 | João Cardoso | 22888 | 2,3% | 2,0% | 2,2% | 1,7% | 0,6% | **1,760%** | 29.744 | Deferido |
| 3 | André Kubitschek | 22022 | 2,9% | 1,9% | 1,3% | 1,7% | 0,6% | **1,680%** | 28.392 | Deferido |
| 4 | Luíza do Clezão | 22822 | 1,1% | 0,9% | 0,4% | 0,3% | 0,3% | **0,600%** | 10.140 | Deferido |
| 5 | Victor Jansen | 22322 | 0,8% | 0,7% | 0,6% | 0,4% | 0,4% | **0,580%** | 9.802 | Deferido |
| 6 | Hamilton Tatu | 22555 | 0,0% | 0,5% | 0,4% | 0,6% | 0,4% | **0,380%** | 6.422 | Deferido |
| 7 | Roosevelt Vilela | 22193 | 0,4% | 0,4% | 0,2% | 0,2% | 0,3% | **0,300%** | 5.070 | Deferido |
| 8 | Alessandro Paiva | 22123 | 0,4% | 0,3% | 0,0% | 0,0% | 0,4% | **0,220%** | 3.718 | Deferido |
| 9 | João Alexandre | 22224 | 0,0% | 0,2% | 0,0% | 0,3% | 0,3% | **0,160%** | 2.704 | Deferido |
| 10 | Carol Kalil | 22122 | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | Deferido |
| 11 | Julia Lucy | 22190 | 0,4% | 0,2% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | Deferido |
| 12 | Xandão Leleco | 22478 | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | Deferido |
| 13 | Rodrigo Dantas | 22100 | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 14 | Fernando Caixeta | 22321 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Joaquim Roriz Neto** com média 3,900% e 65.910 votos eq. Presente em 5/5.

---

<a id="nominata-pode"></a>
## 🏛 PODE — 13 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Robério Negreiros | 20000 | 1,2% | 2,7% | 2,5% | 2,0% | 1,7% | **2,020%** | 34.138 | Deferido |
| 2 | Suzele Veloso | 20200 | 1,1% | 0,7% | 0,6% | 0,6% | 0,4% | **0,680%** | 11.492 | Deferido |
| 3 | Subtenente Geraldo Alves | 20190 | 0,3% | 0,2% | 0,2% | 0,2% | 0,2% | **0,220%** | 3.718 | Deferido |
| 4 | Manuela Andrade | 20101 | 0,0% | 0,0% | 0,4% | 0,2% | 0,0% | **0,120%** | 2.028 | Deferido |
| 5 | Artur Cezar | 20001 | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | Deferido |
| 6 | Cleidiane Vitalino | 20456 | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | Deferido |
| 7 | Capitão Aderivaldo Cardoso | 20333 | 0,3% | 0,2% | 0,0% | 0,0% | 0,0% | **0,100%** | 1.690 | Deferido |
| 8 | Eliana Emerick | 20555 | 0,0% | 0,4% | 0,0% | 0,0% | 0,0% | **0,080%** | 1.352 | Deferido |
| 9 | Claudia Lapa | 20111 | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | Deferido |
| 10 | Telma Rufino | 20222 | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | Deferido |
| 11 | Ana Paula Marra | 20123 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 12 | Neto Rodrigues | 20020 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 13 | Pr. João de Deus | 20700 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Robério Negreiros** com média 2,020% e 34.138 votos eq. Presente em 5/5.

---

<a id="nominata-pp"></a>
## 🏛 PP — 10 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Pepa | 11011 | 2,7% | 3,0% | 3,8% | 3,2% | 2,0% | **2,940%** | 49.686 | Deferido |
| 2 | Pastor Daniel de Castro | 11133 | 3,5% | 3,0% | 3,0% | 2,3% | 2,8% | **2,920%** | 49.348 | Deferido |
| 3 | Rôney Nemer | 11111 | 1,3% | 1,7% | 1,2% | 0,9% | 1,7% | **1,360%** | 22.984 | Deferido |
| 4 | Léo Goleiro | 11010 | 0,3% | 0,0% | 0,2% | 0,6% | 0,5% | **0,320%** | 5.408 | Deferido |
| 5 | Virgílio Neto | 11122 | 0,0% | 0,0% | 0,3% | 0,3% | 0,3% | **0,180%** | 3.042 | Deferido |
| 6 | Valdelino Barcelos | 11234 | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | Deferido |
| 7 | Israel Presença | 11123 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |
| 8 | Marcelinho Nunes | 11777 | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | Deferido |
| 9 | Natalia Reis | 11211 | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | Deferido |
| 10 | Ana Maria | 11022 | 0,0% | 0,0% | 0,0% | 0,0% | 0,4% | **0,080%** | 1.352 | Deferido |

### Análise realista
Principal nome: **Pepa** com média 2,940% e 49.686 votos eq. Presente em 5/5.

---

<a id="nominata-prd"></a>
## 🏛 PRD — 1 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Castelo | 25555 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Castelo** com média 0,040% e 676 votos eq. Presente em 1/5.

---

<a id="nominata-psb"></a>
## 🏛 PSB — 5 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Professora Jéssica Motta | 40140 | 0,7% | 0,5% | 0,3% | 0,2% | 0,4% | **0,420%** | 7.098 | Deferido |
| 2 | Raphael Sebba | 40200 | 0,0% | 0,3% | 0,0% | 0,2% | 0,2% | **0,140%** | 2.366 | Deferido |
| 3 | Múcio | 40061 | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | Deferido |
| 4 | Bernardo Moreira | 40100 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |
| 5 | Professor Aharom | 40120 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Professora Jéssica Motta** com média 0,420% e 7.098 votos eq. Presente em 5/5.

---

<a id="nominata-psd"></a>
## 🏛 PSD — 14 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Rogério Morro da Cruz | 55123 | 1,9% | 1,2% | 0,9% | 0,7% | 1,0% | **1,140%** | 19.266 | Deferido |
| 2 | Delegado Pablo Aguiar | 55000 | 0,4% | 0,2% | 0,2% | 0,2% | 0,2% | **0,240%** | 4.056 | Deferido |
| 3 | Jonathan Araújo | 55661 | 0,3% | 0,0% | 0,3% | 0,2% | 0,2% | **0,200%** | 3.380 | Deferido c/ rec. |
| 4 | Professor Ivan Moraes | 55777 | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | Deferido |
| 5 | Jabá Arruda | 55190 | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | Deferido |
| 6 | Dr. Vicenzo | 55678 | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | Deferido |
| 7 | Pastor Anderson Silva | 55111 | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | Deferido |
| 8 | Sandra Bacelar | 55100 | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | Deferido |
| 9 | Professor Jordenes | 55555 | 0,0% | 0,0% | 0,0% | 0,2% | 0,3% | **0,100%** | 1.690 | Deferido |
| 10 | Simone Magalhães | 55855 | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | Deferido |
| 11 | Alessandro Cardoso | 55055 | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | Deferido |
| 12 | Cleber Df Aguasclaras | 55888 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 13 | Aline Vesely | 55575 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido c/ rec. |
| 14 | Izadora Coimbra | 55026 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Rogério Morro da Cruz** com média 1,140% e 19.266 votos eq. Presente em 5/5.
Rogério Morro da Cruz lidera com 1,14% (19.266 eq.). Série: 1,9%→1,2%→0,9%→0,7%→1,0% queda até P4 com recuperação P5.

---

<a id="nominata-psdb"></a>
## 🏛 PSDB — 5 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Roberto Vieira | 45333 | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | Indeferido |
| 2 | Daniela Ciriaco | 45555 | 0,4% | 0,2% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | Deferido |
| 3 | Carlos Penna | 45000 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 4 | Valdecy Líder Comunitário | 45163 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 5 | Juliana Cândida | 45100 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Roberto Vieira** com média 0,120% e 2.028 votos eq. Presente em 3/5.

---

<a id="nominata-psol"></a>
## 🏛 PSOL — 5 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Max Maciel | 50100 | 1,5% | 2,3% | 2,3% | 3,2% | 3,0% | **2,460%** | 41.574 | Deferido |
| 2 | Michel Platini | 50000 | 0,0% | 0,0% | 0,3% | 0,2% | 0,2% | **0,140%** | 2.366 | Deferido |
| 3 | Keka Bagno | 50123 | 0,0% | 0,2% | 0,0% | 0,0% | 0,2% | **0,080%** | 1.352 | Deferido |
| 4 | Patty Ramiro | 50050 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |
| 5 | Pikineia | 50200 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Max Maciel** com média 2,460% e 41.574 votos eq. Presente em 5/5.

---

<a id="nominata-pt"></a>
## 🏛 PT — 5 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Chico Vigilante | 13100 | 5,3% | 4,0% | 4,1% | 3,3% | 3,4% | **4,020%** | 67.938 | Deferido |
| 2 | Ricardo Vale | 13013 | 1,9% | 1,7% | 1,8% | 1,7% | 1,4% | **1,700%** | 28.730 | Deferido |
| 3 | Gabriel Magno | 13131 | 0,8% | 0,7% | 0,9% | 1,1% | 0,6% | **0,820%** | 13.858 | Deferido |
| 4 | Fabiano Trompetista | 13007 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 5 | Jacy Afonso | 13001 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Chico Vigilante** com média 4,020% e 67.938 votos eq. Presente em 5/5.

---

<a id="nominata-pv"></a>
## 🏛 PV — 2 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Jean da Cultura | 43222 | 0,3% | 0,0% | 0,2% | 0,2% | 0,0% | **0,140%** | 2.366 | Deferido |
| 2 | Elke Pimentel | 43123 | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | Deferido |

### Análise realista
Principal nome: **Jean da Cultura** com média 0,140% e 2.366 votos eq. Presente em 3/5.

---

<a id="nominata-republicanos"></a>
## 🏛 REPUBLICANOS — 15 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Delegado Fernando Fernandes | 10190 | 3,5% | 3,2% | 3,1% | 2,8% | 2,3% | **2,980%** | 50.362 | Deferido |
| 2 | Martins Machado | 10123 | 1,5% | 3,5% | 3,0% | 1,5% | 3,2% | **2,540%** | 42.926 | Deferido |
| 3 | Delmasso | 10456 | 2,4% | 2,2% | 1,6% | 3,0% | 2,0% | **2,240%** | 37.856 | Deferido |
| 4 | Renata Daguiar | 10789 | 0,3% | 1,4% | 2,0% | 2,7% | 2,8% | **1,840%** | 31.096 | Deferido |
| 5 | Bispo Renato Andrade | 10100 | 2,1% | 1,2% | 1,7% | 1,4% | 1,7% | **1,620%** | 27.378 | Deferido |
| 6 | Delegada Doutora Jane | 10555 | 0,7% | 0,6% | 1,2% | 0,8% | 0,7% | **0,800%** | 13.520 | Deferido |
| 7 | Giulianno Cartaxo | 10020 | 0,0% | 0,0% | 0,8% | 0,4% | 0,9% | **0,420%** | 7.098 | Deferido |
| 8 | Estefane Sampaio | 10222 | 0,3% | 0,2% | 0,0% | 0,3% | 0,4% | **0,240%** | 4.056 | Deferido |
| 9 | Mc Jenny | 10010 | 0,4% | 0,0% | 0,2% | 0,2% | 0,0% | **0,160%** | 2.704 | Deferido |
| 10 | Denise Franco | 10888 | 0,0% | 0,3% | 0,2% | 0,2% | 0,0% | **0,140%** | 2.366 | Deferido |
| 11 | Marcelinho Carioca | 10777 | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | Deferido |
| 12 | Miguel da 26 | 10026 | 0,3% | 0,3% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | Deferido |
| 13 | Marcelo Trator | 10000 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 14 | Scooby Ube | 10061 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 15 | Pinho | 10022 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |

### Análise realista
Principal nome: **Delegado Fernando Fernandes** com média 2,980% e 50.362 votos eq. Presente em 5/5.

---

<a id="nominata-solidariedade"></a>
## 🏛 SOLIDARIEDADE — 2 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Deusdete Filho | 77111 | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | Deferido |
| 2 | Orion Oliveira | 77843 | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | Deferido |

### Análise realista
Principal nome: **Deusdete Filho** com média 0,100% e 1.690 votos eq. Presente em 2/5.

---

<a id="nominata-união"></a>
## 🏛 UNIÃO — 7 nomes
[⬆️ Voltar ao menu](#inicio)
| Pos. | Candidato | Número | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Situação |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| 1 | Eduardo Pedrosa | 44000 | 2,4% | 1,6% | 1,9% | 2,8% | 2,7% | **2,280%** | 38.532 | Deferido |
| 2 | Claudio Abrantes | 44123 | 0,4% | 0,7% | 0,6% | 0,6% | 0,6% | **0,580%** | 9.802 | Deferido |
| 3 | Pedro Oliveira | 44555 | 0,3% | 0,3% | 0,3% | 0,2% | 0,0% | **0,220%** | 3.718 | Deferido |
| 4 | Delegada Karen | 44180 | 0,0% | 0,0% | 0,3% | 0,2% | 0,2% | **0,140%** | 2.366 | Deferido |
| 5 | Silvinho Almeida | 44567 | 0,0% | 0,0% | 0,0% | 0,3% | 0,4% | **0,140%** | 2.366 | Deferido |
| 6 | Cristiano Severo | 44070 | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | Deferido |
| 7 | Pedro do Ovo | 44044 | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | Deferido |



### 🎯 Cenários projetados para o QE

| Cenário | Votos válidos | QE | Característica |
|:---|---:|---:|:---|
| 🔴 **Baixo** | ~1.598.000 | **~66.600** | Participação mais baixa |
| 🟡 **Tendência** | ~1.638.000 | **~68.300** | Regressão histórica |
| ⭐ **Referência** | **1.680.000** | **🎯 70.000** | **Base de trabalho** |
| 🟠 **Média histórica** | ~1.728.000 | **~72.000** | Retorno à média |
| 🟢 **Alta participação** | ~1.840.000 | **~76.700** | Participação elevada |



---
<a id="ranking-consolidado"></a>
# 7. Ranking consolidado dos candidatos (157 nomes)

| Pos. | Candidato | Partido | Número | Situação | P1 | P2 | P3 | P4 | P5 | Média | Votos Eq. | Menções | Viabilidade analítica |
|---:|---|:---:|---:|:---:|---:|---:|---:|---:|---:|---:|---:|:---:|---|
| 1 | Chico Vigilante | PT | 13100 | ✅ Deferido | 5,3% | 4,0% | 4,1% | 3,3% | 3,4% | **4,020%** | 67.938 | 5/5 | 🟢 Alta viabilidade |
| 2 | Joaquim Roriz Neto | PL | 22000 | ✅ Deferido | 4,1% | 4,0% | 3,8% | 3,7% | 3,9% | **3,900%** | 65.910 | 5/5 | 🟢 Alta viabilidade |
| 3 | Jaqueline Silva | MDB | 15900 | ✅ Deferido | 3,2% | 4,1% | 3,5% | 3,0% | 3,0% | **3,360%** | 56.784 | 5/5 | 🟢 Alta viabilidade |
| 4 | Delegado Fernando Fernandes | REPUBLICANOS | 10190 | ✅ Deferido | 3,5% | 3,2% | 3,1% | 2,8% | 2,3% | **2,980%** | 50.362 | 5/5 | 🟢 Alta viabilidade |
| 5 | Pepa | PP | 11011 | ✅ Deferido | 2,7% | 3,0% | 3,8% | 3,2% | 2,0% | **2,940%** | 49.686 | 5/5 | 🟢 Alta viabilidade |
| 6 | Pastor Daniel de Castro | PP | 11133 | ✅ Deferido | 3,5% | 3,0% | 3,0% | 2,3% | 2,8% | **2,920%** | 49.348 | 5/5 | 🟢 Alta viabilidade |
| 7 | Martins Machado | REPUBLICANOS | 10123 | ✅ Deferido | 1,5% | 3,5% | 3,0% | 1,5% | 3,2% | **2,540%** | 42.926 | 5/5 | 🟢 Alta viabilidade |
| 8 | Max Maciel | PSOL | 50100 | ✅ Deferido | 1,5% | 2,3% | 2,3% | 3,2% | 3,0% | **2,460%** | 41.574 | 5/5 | 🟢 Alta viabilidade |
| 9 | Eduardo Pedrosa | UNIÃO | 44000 | ✅ Deferido | 2,4% | 1,6% | 1,9% | 2,8% | 2,7% | **2,280%** | 38.532 | 5/5 | 🟡 Média viabilidade |
| 10 | Delmasso | REPUBLICANOS | 10456 | ✅ Deferido | 2,4% | 2,2% | 1,6% | 3,0% | 2,0% | **2,240%** | 37.856 | 5/5 | 🟡 Média viabilidade |
| 11 | Wellington Luiz | MDB | 15123 | ✅ Deferido | 0,8% | 2,3% | 2,3% | 2,0% | 3,2% | **2,120%** | 35.828 | 5/5 | 🟡 Média viabilidade |
| 12 | Robério Negreiros | PODE | 20000 | ✅ Deferido | 1,2% | 2,7% | 2,5% | 2,0% | 1,7% | **2,020%** | 34.138 | 5/5 | 🟡 Média viabilidade |
| 13 | Renata Daguiar | REPUBLICANOS | 10789 | ✅ Deferido | 0,3% | 1,4% | 2,0% | 2,7% | 2,8% | **1,840%** | 31.096 | 5/5 | 🟡 Média viabilidade |
| 14 | João Cardoso | PL | 22888 | ✅ Deferido | 2,3% | 2,0% | 2,2% | 1,7% | 0,6% | **1,760%** | 29.744 | 5/5 | 🟡 Média viabilidade |
| 15 | Ricardo Vale | PT | 13013 | ✅ Deferido | 1,9% | 1,7% | 1,8% | 1,7% | 1,4% | **1,700%** | 28.730 | 5/5 | 🟡 Média viabilidade |
| 16 | André Kubitschek | PL | 22022 | ✅ Deferido | 2,9% | 1,9% | 1,3% | 1,7% | 0,6% | **1,680%** | 28.392 | 5/5 | 🟡 Média viabilidade |
| 17 | Bispo Renato Andrade | REPUBLICANOS | 10100 | ✅ Deferido | 2,1% | 1,2% | 1,7% | 1,4% | 1,7% | **1,620%** | 27.378 | 5/5 | 🟡 Média viabilidade |
| 18 | Hermeto | MDB | 15190 | ✅ Deferido | 1,3% | 1,9% | 1,7% | 1,3% | 1,5% | **1,540%** | 26.026 | 5/5 | 🟡 Média viabilidade |
| 19 | Rôney Nemer | PP | 11111 | ✅ Deferido | 1,3% | 1,7% | 1,2% | 0,9% | 1,7% | **1,360%** | 22.984 | 5/5 | 🟡 Média viabilidade |
| 20 | Rogério Morro da Cruz | PSD | 55123 | ✅ Deferido | 1,9% | 1,2% | 0,9% | 0,7% | 1,0% | **1,140%** | 19.266 | 5/5 | 🟡 Média viabilidade |
| 21 | Iolando | MDB | 15000 | ✅ Deferido | 1,1% | 1,3% | 1,3% | 1,0% | 0,9% | **1,120%** | 18.928 | 5/5 | 🟡 Média viabilidade |
| 22 | Jorge Vianna | DEMOCRATA | 35192 | ✅ Deferido | 1,1% | 0,9% | 1,2% | 1,0% | 1,1% | **1,060%** | 17.914 | 5/5 | 🟡 Média viabilidade |
| 23 | Rogério Ulysses | AVANTE | 70321 | ✅ Deferido | 1,1% | 1,2% | 0,9% | 0,9% | 0,8% | **0,980%** | 16.562 | 5/5 | 🟡 Média viabilidade |
| 24 | Raad | MOBILIZA | 33100 | ✅ Deferido | 1,0% | 0,9% | 0,9% | 0,8% | 1,3% | **0,980%** | 16.562 | 5/5 | 🟡 Média viabilidade |
| 25 | Gabriel Magno | PT | 13131 | ✅ Deferido | 0,8% | 0,7% | 0,9% | 1,1% | 0,6% | **0,820%** | 13.858 | 5/5 | 🔴 Baixa viabilidade |
| 26 | Delegada Doutora Jane | REPUBLICANOS | 10555 | ✅ Deferido | 0,7% | 0,6% | 1,2% | 0,8% | 0,7% | **0,800%** | 13.520 | 5/5 | 🔴 Baixa viabilidade |
| 27 | Suzele Veloso | PODE | 20200 | ✅ Deferido | 1,1% | 0,7% | 0,6% | 0,6% | 0,4% | **0,680%** | 11.492 | 5/5 | 🔴 Baixa viabilidade |
| 28 | Luíza do Clezão | PL | 22822 | ✅ Deferido | 1,1% | 0,9% | 0,4% | 0,3% | 0,3% | **0,600%** | 10.140 | 5/5 | 🔴 Baixa viabilidade |
| 29 | Cristiano Araújo | MDB | 15015 | ✅ Deferido | 0,6% | 0,4% | 0,7% | 0,6% | 0,6% | **0,580%** | 9.802 | 5/5 | 🔴 Baixa viabilidade |
| 30 | Claudio Abrantes | UNIÃO | 44123 | ✅ Deferido | 0,4% | 0,7% | 0,6% | 0,6% | 0,6% | **0,580%** | 9.802 | 5/5 | 🔴 Baixa viabilidade |
| 31 | Victor Jansen | PL | 22322 | ✅ Deferido | 0,8% | 0,7% | 0,6% | 0,4% | 0,4% | **0,580%** | 9.802 | 5/5 | 🔴 Baixa viabilidade |
| 32 | Diolan Rocha | DEMOCRATA | 35353 | ✅ Deferido | 0,3% | 0,3% | 0,6% | 0,6% | 0,5% | **0,460%** | 7.774 | 5/5 | 🔴 Baixa viabilidade |
| 33 | Daniel Radar | AVANTE | 70000 | ✅ Deferido | 0,0% | 0,6% | 0,4% | 0,5% | 0,6% | **0,420%** | 7.098 | 4/5 | 🔴 Baixa viabilidade |
| 34 | Giulianno Cartaxo | REPUBLICANOS | 10020 | ✅ Deferido | 0,0% | 0,0% | 0,8% | 0,4% | 0,9% | **0,420%** | 7.098 | 3/5 | 🔴 Baixa viabilidade |
| 35 | Delegado Laercio | AVANTE | 70255 | ✅ Deferido | 0,7% | 0,5% | 0,5% | 0,2% | 0,2% | **0,420%** | 7.098 | 5/5 | 🔴 Baixa viabilidade |
| 36 | Marcela Passamani | MDB | 15555 | ✅ Deferido | 0,3% | 0,2% | 0,4% | 0,4% | 0,8% | **0,420%** | 7.098 | 5/5 | 🔴 Baixa viabilidade |
| 37 | Professora Jéssica Motta | PSB | 40140 | ✅ Deferido | 0,7% | 0,5% | 0,3% | 0,2% | 0,4% | **0,420%** | 7.098 | 5/5 | 🔴 Baixa viabilidade |
| 38 | Hamilton Tatu | PL | 22555 | ✅ Deferido | 0,0% | 0,5% | 0,4% | 0,6% | 0,4% | **0,380%** | 6.422 | 4/5 | 🔴 Baixa viabilidade |
| 39 | Léo Goleiro | PP | 11010 | ✅ Deferido | 0,3% | 0,0% | 0,2% | 0,6% | 0,5% | **0,320%** | 5.408 | 4/5 | 🔴 Baixa viabilidade |
| 40 | Claudeci Luart | DC | 27321 | ✅ Deferido | 0,4% | 0,2% | 0,3% | 0,3% | 0,3% | **0,300%** | 5.070 | 5/5 | 🔴 Baixa viabilidade |
| 41 | Roosevelt Vilela | PL | 22193 | ✅ Deferido | 0,4% | 0,4% | 0,2% | 0,2% | 0,3% | **0,300%** | 5.070 | 5/5 | 🔴 Baixa viabilidade |
| 42 | Silene da Saúde | AVANTE | 70111 | ✅ Deferido | 0,3% | 0,3% | 0,2% | 0,2% | 0,4% | **0,280%** | 4.732 | 5/5 | 🔴 Baixa viabilidade |
| 43 | Delegado Pablo Aguiar | PSD | 55000 | ✅ Deferido | 0,4% | 0,2% | 0,2% | 0,2% | 0,2% | **0,240%** | 4.056 | 5/5 | 🔴 Baixa viabilidade |
| 44 | Estefane Sampaio | REPUBLICANOS | 10222 | ✅ Deferido | 0,3% | 0,2% | 0,0% | 0,3% | 0,4% | **0,240%** | 4.056 | 4/5 | 🔴 Baixa viabilidade |
| 45 | Subtenente Geraldo Alves | PODE | 20190 | ✅ Deferido | 0,3% | 0,2% | 0,2% | 0,2% | 0,2% | **0,220%** | 3.718 | 5/5 | 🔴 Baixa viabilidade |
| 46 | Carlos Xavier | DC | 27127 | ✅ Deferido | 0,5% | 0,2% | 0,2% | 0,2% | 0,0% | **0,220%** | 3.718 | 4/5 | 🔴 Baixa viabilidade |
| 47 | Pedro Oliveira | UNIÃO | 44555 | ✅ Deferido | 0,3% | 0,3% | 0,3% | 0,2% | 0,0% | **0,220%** | 3.718 | 4/5 | 🔴 Baixa viabilidade |
| 48 | Sardinha | MOBILIZA | 33123 | ✅ Deferido | 0,0% | 0,2% | 0,3% | 0,3% | 0,3% | **0,220%** | 3.718 | 4/5 | 🔴 Baixa viabilidade |
| 49 | Alessandro Paiva | PL | 22123 | ✅ Deferido | 0,4% | 0,3% | 0,0% | 0,0% | 0,4% | **0,220%** | 3.718 | 3/5 | 🔴 Baixa viabilidade |
| 50 | Sgt Roksinaidy | MOBILIZA | 33001 | ✅ Deferido | 0,3% | 0,2% | 0,2% | 0,2% | 0,2% | **0,220%** | 3.718 | 5/5 | 🔴 Baixa viabilidade |
| 51 | Dr. Candido Teles | MDB | 15678 | ✅ Deferido | 0,5% | 0,2% | 0,2% | 0,2% | 0,0% | **0,220%** | 3.718 | 4/5 | 🔴 Baixa viabilidade |
| 52 | Jonathan Araújo | PSD | 55661 | ⚠️ Deferido c/ rec. | 0,3% | 0,0% | 0,3% | 0,2% | 0,2% | **0,200%** | 3.380 | 4/5 | 🔴 Baixa viabilidade |
| 53 | Tabanez | MOBILIZA | 33222 | ✅ Deferido | 0,0% | 0,3% | 0,3% | 0,2% | 0,2% | **0,200%** | 3.380 | 4/5 | 🔴 Baixa viabilidade |
| 54 | Pastor Rafael | DC | 27000 | ✅ Deferido | 0,0% | 0,3% | 0,2% | 0,2% | 0,3% | **0,200%** | 3.380 | 4/5 | 🔴 Baixa viabilidade |
| 55 | Carlão Reclamão | DEMOCRATA | 35180 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,3% | 0,3% | **0,180%** | 3.042 | 3/5 | 🔴 Baixa viabilidade |
| 56 | Italo Miranda | MOBILIZA | 33456 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,3% | 0,4% | **0,180%** | 3.042 | 3/5 | 🔴 Baixa viabilidade |
| 57 | Bebeto | MOBILIZA | 33033 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,3% | 0,4% | **0,180%** | 3.042 | 3/5 | 🔴 Baixa viabilidade |
| 58 | Virgílio Neto | PP | 11122 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,3% | 0,3% | **0,180%** | 3.042 | 3/5 | 🔴 Baixa viabilidade |
| 59 | Professor Ivan Moraes | PSD | 55777 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | 4/5 | 🔴 Baixa viabilidade |
| 60 | Fernando do Resgate | DC | 27777 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,3% | 0,3% | **0,160%** | 2.704 | 3/5 | 🔴 Baixa viabilidade |
| 61 | Valdelino Barcelos | PP | 11234 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | 4/5 | 🔴 Baixa viabilidade |
| 62 | Gustavo Aires | MDB | 15133 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,3% | 0,3% | **0,160%** | 2.704 | 3/5 | 🔴 Baixa viabilidade |
| 63 | Jabá Arruda | PSD | 55190 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,2% | **0,160%** | 2.704 | 4/5 | 🔴 Baixa viabilidade |
| 64 | João Alexandre | PL | 22224 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,3% | 0,3% | **0,160%** | 2.704 | 3/5 | 🔴 Baixa viabilidade |
| 65 | Mc Jenny | REPUBLICANOS | 10010 | ✅ Deferido | 0,4% | 0,0% | 0,2% | 0,2% | 0,0% | **0,160%** | 2.704 | 3/5 | 🔴 Baixa viabilidade |
| 66 | Alexandre Oliver | DC | 27222 | ✅ Deferido | 0,0% | 0,2% | 0,3% | 0,2% | 0,0% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 67 | Agenildo Neri | MOBILIZA | 33733 | ✅ Deferido | 0,0% | 0,2% | 0,3% | 0,2% | 0,0% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 68 | Denise Franco | REPUBLICANOS | 10888 | ✅ Deferido | 0,0% | 0,3% | 0,2% | 0,2% | 0,0% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 69 | Michel Platini | PSOL | 50000 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,2% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 70 | Raphael Sebba | PSB | 40200 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,2% | 0,2% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 71 | Delegada Karen | UNIÃO | 44180 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,2% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 72 | Silvinho Almeida | UNIÃO | 44567 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,4% | **0,140%** | 2.366 | 2/5 | 🔴 Baixa viabilidade |
| 73 | Luís Miranda | DEMOCRATA | 35555 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,2% | 0,2% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 74 | Jean da Cultura | PV | 43222 | ✅ Deferido | 0,3% | 0,0% | 0,2% | 0,2% | 0,0% | **0,140%** | 2.366 | 3/5 | 🔴 Baixa viabilidade |
| 75 | Carol Kalil | PL | 22122 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 76 | Dr. Vicenzo | PSD | 55678 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 77 | Jorge Farias Rodoviário | MOBILIZA | 33111 | ✅ Deferido | 0,0% | 0,2% | 0,2% | 0,2% | 0,0% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 78 | Marcelinho Carioca | REPUBLICANOS | 10777 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 79 | Marcos Marshal | MDB | 15151 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 80 | Pastor Anderson Silva | PSD | 55111 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 81 | Roberto Vieira | PSDB | 45333 | ❌ Indeferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | 3/5 | ⚫ Inapto |
| 82 | Sandra Bacelar | PSD | 55100 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,2% | **0,120%** | 2.028 | 3/5 | 🔴 Baixa viabilidade |
| 83 | Evaldo Lobato | AVANTE | 70555 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 84 | Gabriela Freire | AVANTE | 70100 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 85 | Israel Presença | PP | 11123 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 86 | Bere Darc | PCDOB | 65180 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 87 | Daiane dos Santos | NOVO | 30500 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 88 | Elke Pimentel | PV | 43123 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,3% | 0,3% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 89 | Manuela Andrade | PODE | 20101 | ✅ Deferido | 0,0% | 0,0% | 0,4% | 0,2% | 0,0% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 90 | Daniela Ciriaco | PSDB | 45555 | ✅ Deferido | 0,4% | 0,2% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 91 | Julia Lucy | PL | 22190 | ✅ Deferido | 0,4% | 0,2% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 92 | Miguel da 26 | REPUBLICANOS | 10026 | ✅ Deferido | 0,3% | 0,3% | 0,0% | 0,0% | 0,0% | **0,120%** | 2.028 | 2/5 | 🔴 Baixa viabilidade |
| 93 | Marcelinho Nunes | PP | 11777 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 94 | Anderson Guiné | AVANTE | 70777 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 95 | Artur Cezar | PODE | 20001 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 96 | Cleidiane Vitalino | PODE | 20456 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 97 | Deusdete Filho | SOLIDARIEDADE | 77111 | ✅ Deferido | 0,0% | 0,0% | 0,3% | 0,2% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 98 | Professor Jordenes | PSD | 55555 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,2% | 0,3% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 99 | Cricia Cantora de Pentecostes | MOBILIZA | 33777 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 100 | Jovita Rosa | PDT | 12000 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 101 | Simone Magalhães | PSD | 55855 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,2% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 102 | Capitão Aderivaldo Cardoso | PODE | 20333 | ✅ Deferido | 0,3% | 0,2% | 0,0% | 0,0% | 0,0% | **0,100%** | 1.690 | 2/5 | 🔴 Baixa viabilidade |
| 103 | Múcio | PSB | 40061 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 104 | Natalia Reis | PP | 11211 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 105 | Orion Oliveira | SOLIDARIEDADE | 77843 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 106 | Wellington Mega | DC | 27888 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 107 | Xandão Leleco | PL | 22478 | ✅ Deferido | 0,0% | 0,0% | 0,2% | 0,2% | 0,0% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 108 | Edson Sol Nascente | MDB | 15551 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,2% | 0,2% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 109 | Ana Maria | PP | 11022 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,4% | **0,080%** | 1.352 | 1/5 | 🔴 Baixa viabilidade |
| 110 | Izaquiel Souza | DC | 27700 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,2% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 111 | Keka Bagno | PSOL | 50123 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,2% | **0,080%** | 1.352 | 2/5 | 🔴 Baixa viabilidade |
| 112 | Eliana Emerick | PODE | 20555 | ✅ Deferido | 0,0% | 0,4% | 0,0% | 0,0% | 0,0% | **0,080%** | 1.352 | 1/5 | 🔴 Baixa viabilidade |
| 113 | André Pires | PDT | 12110 | ✅ Deferido | 0,4% | 0,0% | 0,0% | 0,0% | 0,0% | **0,080%** | 1.352 | 1/5 | 🔴 Baixa viabilidade |
| 114 | Claudia Lapa | PODE | 20111 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 115 | Dr. Lucimir | DEMOCRATA | 35355 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 116 | Paulinho Campello | PDT | 12105 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 117 | Telma Rufino | PODE | 20222 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,3% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 118 | Inês Armand | DC | 27272 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 119 | Issa | AVANTE | 70007 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 120 | Joe Valle da Malunga | PDT | 12345 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 121 | Mercione | PDT | 12061 | ✅ Deferido | 0,0% | 0,3% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 122 | Alessandro Cardoso | PSD | 55055 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 123 | Rodrigo Dantas | PL | 22100 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 124 | Drª Carolina Maia | MISSÃO | 14100 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 125 | Missionária Eudes | MOBILIZA | 33000 | ✅ Deferido | 0,3% | 0,0% | 0,0% | 0,0% | 0,0% | **0,060%** | 1.014 | 1/5 | 🔴 Baixa viabilidade |
| 126 | Marcele Mama | AVANTE | 70789 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,2% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 127 | Ana Paula Marra | PODE | 20123 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 128 | Carlos Penna | PSDB | 45000 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 129 | Castelo | PRD | 25555 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 130 | Cleber Df Aguasclaras | PSD | 55888 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 131 | Cristiano Severo | UNIÃO | 44070 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 132 | Fabiano Trompetista | PT | 13007 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 133 | Fernando Caixeta | PL | 22321 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 134 | Jacy Afonso | PT | 13001 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 135 | Jair dos Aplicativos | PDT | 12112 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 136 | Lgm | NOVO | 30000 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 137 | Marcelo Trator | REPUBLICANOS | 10000 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 138 | Neto Rodrigues | PODE | 20020 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 139 | Scooby Ube | REPUBLICANOS | 10061 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 140 | Tia Maria | DC | 27555 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 141 | Valdecy Líder Comunitário | PSDB | 45163 | ✅ Deferido | 0,0% | 0,0% | 0,0% | 0,0% | 0,2% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 142 | Aline Vesely | PSD | 55575 | ⚠️ Deferido c/ rec. | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 143 | Amanda Camargo | MISSÃO | 14714 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 144 | Bernardo Moreira | PSB | 40100 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 145 | Corretor Nogueira | MOBILIZA | 33007 | ⚠️ Deferido c/ rec. | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 146 | Dr Wendel Moreira | MOBILIZA | 33192 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 147 | Emanuell Resolve | MOBILIZA | 33088 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 148 | Izadora Coimbra | PSD | 55026 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 149 | Juliana Cândida | PSDB | 45100 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 150 | Patty Ramiro | PSOL | 50050 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 151 | Pedro do Ovo | UNIÃO | 44044 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 152 | Pikineia | PSOL | 50200 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 153 | Pinho | REPUBLICANOS | 10022 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 154 | Pr. João de Deus | PODE | 20700 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 155 | Professor Aharom | PSB | 40120 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 156 | Rachel Doces | DC | 27999 | ✅ Deferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | 🔴 Baixa viabilidade |
| 157 | Rigone Amorim | AVANTE | 70070 | ❌ Indeferido | 0,0% | 0,2% | 0,0% | 0,0% | 0,0% | **0,040%** | 676 | 1/5 | ⚫ Inapto |

---
<a id="projecao-partidos"></a>
# 8. Projeção de cadeiras por partido
| Partido | Mediana | Cadeiras prováveis | Prob 0 | Prob 1 | Prob 2 | Prob 3 | Prob 4 | Confiança |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| REPUBLICANOS | 8,6% | **3** | 1% | 9% | 28% | 46% | 14% | Médio |
| PL | 8,1% | **3** | 1% | 7% | 31% | 44% | 15% | Médio |
| PT/PCdoB/PV | 7,5% | **2-3** | 3% | 18% | 48% | 26% | 5% | Médio |
| PP/UNIÃO | 6,9% | **2-3** | 2% | 16% | 49% | 28% | 5% | Médio |
| MDB | 5,9% | **2** | 4% | 24% | 54% | 15% | 3% | Médio |
| PSOL/Rede | 3,2% | **1-2** | 11% | 54% | 30% | 5% | — | Médio |
| PSD | 1,5% | **1-2** | 22% | 53% | 23% | 2% | — | Baixo-médio |
| AVANTE | 1,3% | **1** | 29% | 57% | 13% | 1% | — | Médio |

---
<a id="comparacao-partidos"></a>
# 9. Comparação dos principais partidos
| Partido | Cadeiras | Diagnóstico |
|---|---:|---|
| REPUBLICANOS | 3 | Nominata numerosa e competitiva |
| PL | 3 | Forte liderança individual |
| PT/PCdoB/PV | 2-3 | Liderança Chico Vigilante |
| PP/UNIÃO | 2-3 | Pepa + Pastor Daniel |
| MDB | 2 | Jaqueline + Wellington Luiz |
| PSOL/Rede | 1-2 | Max Maciel |
| PSD | 1-2 | Rogério Morro da Cruz |
| AVANTE | 1 | Rogério Ulysses lidera |

---


### Análise realista
---
## 👤 Autor

**Davi Santana**  
*Cientista, Escritor*  
*Esp. Engenharia de Software - Esp. Data Science Analytics - USP*

 [Contato](https://instagram.com.br/davitayback)

---

### ⚖️ Disclaimer Analítico

> Esta análise foi elaborada a partir de cinco pesquisas IGAPE oficialmente registradas no TSE (DF-02390, DF-02089, DF-07879, DF-09945 e DF-09868) e de projeções estatísticas.

> Os percentuais citados referem-se a intenções de voto, sujeitos a margem de erro de ±2,2 p.p. e não representam resultado oficial de urna. Decisões estratégicas devem considerar validações jurídicas, metodológicas e de campo.

---

> *Cada clique, cada dado, cada insight conta.*  
> *Transforme informação em poder — com responsabilidade e ética.*

© 2026 Davi Santana. | *“Ciência aplicada, código limpo, política clara.”* | [🔝 Voltar ao Topo](#inicio)
