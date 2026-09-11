# AI Aplicada à Arquitetura — Fase 1: Análise do Sítio com Muse Spark 1.3 Free (v3 Método Único)
**Faculdade de Arquitetura — Universidade de Lisboa | UC: IA Aplicada à Arquitetura (IAAA) — Módulo 1**
**Princípio metodológico: a totalidade das análises é produzida nesta plataforma (Muse Spark 1.3 Free), sem recurso obrigatório a software de terceiros.**
**Organização da turma: um grupo = uma sub-região NUTS III. A turma elabora o atlas nacional.**

> Enquadramento oficial: Portugal, NUTS 2024 = 26 NUTS III, 9 NUTS II, 3 NUTS I (Regulamento Delegado UE 2023/674, INE). A Área Metropolitana de Lisboa foi desagregada em Grande Lisboa e Península de Setúbal; foi criada a NUTS II Oeste e Vale do Tejo.

## 1. Lista oficial para escolha dos grupos (26)

**Norte (8):** Alto Minho, Cávado, Ave, Área Metropolitana do Porto, Alto Tâmega e Barroso, Tâmega e Sousa, Douro, Terras de Trás-os-Montes
**Centro (6):** Região de Aveiro, Região de Coimbra, Região de Leiria, Viseu Dão-Lafões, Beira Baixa, Beiras e Serra da Estrela
**Oeste e Vale do Tejo (3):** Oeste, Médio Tejo, Lezíria do Tejo
**Grande Lisboa (1):** Grande Lisboa
**Península de Setúbal (1):** Península de Setúbal
**Alentejo (4):** Alentejo Litoral, Baixo Alentejo, Alto Alentejo, Alentejo Central
**Algarve (1):** Algarve
**RA Açores (1):** Região Autónoma dos Açores
**RA Madeira (1):** Região Autónoma da Madeira

Regra de atribuição: a seleção observa a ordem de preferência, até esgotar as 26 sub-regiões. Cada grupo enquadra um mínimo de dois municípios e um sítio de projeto de 500 × 500 m.

## 2. Fundamentação pedagógica

Cada grupo desenvolve uma conversação estruturada (P0–P6), da qual resultam quatro pranchas normalizadas. O raciocínio permanece integralmente documentado, verificável e avaliável.

A plataforma assume as seguintes funções:
- enquadramento territorial (NUTS I/II/III, municípios, população INE/Pordata)
- leitura de imagens do sítio fornecidas pelo grupo
- síntese de ficheiro climático EPW, com cruzamento Portal do Clima/IPMA
- simplificação de extrato do PDM fornecido pelo grupo
- identificação de referências vernáculas e contemporâneas, com fontes
- síntese propositiva (SWOT, volumetrias, programa, incertezas)

Limites a explicitar aos estudantes:
- não substitui a visita ao sítio, o levantamento dimensional nem a simulação avançada;
- não produz desenho CAD/BIM autónomo nem simulação de fluidos computacional;
- instruções imprecisas ou ausência de anexos reduzem a fiabilidade — impõem-se prompts fechados, anexos obrigatórios e verificação independente.

## 3. Procedimento único em seis prompts (por ordem, na mesma conversação)

**P0 — Configuração:** "O grupo [n.] estuda a NUTS III [designação], municípios [x, y], sítio [morada]. Coordenadas do centro (WGS84): lat. [00.0000° N], long. [00.0000° W] + [00°00'00"N, 00°00'00"W]. Altitude: [___] m (fonte)."
**P1 — Território:** Enquadramento NUTS I/II/III, municípios, área, população e função regional; confirmação de coordenadas e altitude. Caracterização socioeconómica dos municípios com dados do INE e da Pordata (Fundação Francisco Manuel dos Santos): população residente e variação intercensitária, índice de envelhecimento, densidade, alojamentos, escolaridade, emprego/desemprego e poder de compra — sempre com valor, ano, nível territorial e tabela de origem. Resultado: tabela, cinco pontos e frase de conceito. Estes indicadores alimentam diretamente a SWOT em P6.

**P1-TAB — Quadro INE/Pordata (copiar para o Muse Spark):**

> P1-TAB: Com os municípios [x, y] e a NUTS III [designação], construir o quadro socioeconómico em tabela Markdown com as colunas EXATAS: Indicador | [município x] | [município y] | NUTS III | Ano | Fonte/tabela. Preencher UMA linha por indicador: população residente; variação 2011–2021 (%); índice de envelhecimento; densidade (hab/km²); alojamentos (n.º); escolaridade superior (%); taxa de desemprego (%); poder de compra per capita (índice). Fontes admitidas APENAS: INE (Censos, indicadores, destaques) e Pordata (Fundação Francisco Manuel dos Santos). Cada célula com valor + ano. Dado não confirmado → escrever "não confirmado" e indicar onde procurar. No fim, cinco pontos de síntese e uma frase de conceito. Nada de valores inventados.
**P2 — Leitura do lugar:** O grupo anexa (a) imagem Google Maps ou similar (Maps 1 km, 500 m, Earth oblíqua ou ortofoto DGT — com fonte, data, escala e norte) e (b) fotografias do sítio, se existentes (autoria, data, ponto e orientação). Caracterização obrigatória em NOVE dimensões: (1) paleta cromática dominante; (2) caracterização dos solos (DGT/LNEG); (3) vegetação e espécies animais (ICNF); (4) risco sísmico (IPMA/LNEG); (5) risco de cheia (APA); (6) risco e histórico de incêndio (ANEPC/ICNF); (7) fontes de poluição e de ruído (APA, mapas de ruído municipais); (8) oferta de serviços do lugar; (9) descrição arquitetónica do edificado. Resultado: tabela por dimensão (estado, fonte, implicação de projeto), figura-fundo e três pistas; assinalar o não verificável. Sem fotografia própria, declarar "sem verificação no local".
**P3 — Clima (EPW + IPMA + Köppen-Geiger):** O grupo anexa (1) EPW da estação mais próxima (com distância ao sítio e diferença de altitude), (2) ficha IPMA correspondente (normais e registos) e (3) categoria Köppen-Geiger do município (código + significado, ex. Csa, Csb, BSk, Cfb). Resultado: seis pontos para a volumetria, convergências/divergências EPW/IPMA e duas regras de massa.
**P4 — Regulamento (PDM):** O grupo transcreve um extrato do PDM com condicionantes. Resultado: reformulação em linguagem corrente (altura, índice, ocupação, afastamentos, património), causa de reprovação e parágrafo de risco. Não deverão ser invocados artigos não fornecidos.
**P5 — Cultura:** Três regras climáticas vernáculas com exemplos, duas obras contemporâneas de referência na proximidade (designação, autoria, ano) e uma tendência artística ou de design, com fontes. Elementos não confirmados deverão ser declarados como tal.
**P6 — Síntese:** Com base em P1–P5: matriz SWOT (dois pontos por quadrante), duas opções de volumetria (vantagens e inconvenientes), tabela preliminar de programa, incertezas e três pontos a verificar no local. Pelo menos dois pontos da SWOT decorrem diretamente dos indicadores INE/Pordata apurados em P1, com valor e ano entre parênteses.

**P6-IMG — Prancha SWOT em imagem (Google Gemini Nano Banana, 16:9, 2K):** o prompt é montado no bloco P6-CTX do diapositivo, obrigatoriamente APÓS a recolha de P1–P6 — prompts genéricos produzem imagens genéricas. Opcionalmente, o texto integral do P6 pode ser condensado nos 8 campos via Muse Spark (Meta Model API, `api.meta.ai/v1`, modelo `muse-spark-1.3`, créditos gratuitos): corre no navegador mesmo com o sítio no GitHub Pages, pois a chave fica apenas em `localStorage`. Copiar o prompt abaixo para o gerador, substituindo os parênteses pelo texto curto já verificado em P6. Rever a ortografia na imagem gerada.

> Clean architectural SWOT analysis board, infographic, 16:9 landscape. Warm off-white background. Four equal quadrants labelled, in dark navy sans-serif capitals: top-left FORÇAS, top-right FRAQUEZAS, bottom-left OPORTUNIDADES, bottom-right AMEAÇAS. Each quadrant MUST contain EXACTLY two short bullet lines in Portuguese: [S1] / [S2] // [W1] / [W2] // [O1] / [O2] // [T1] / [T2], concerning the site [NUTS III, municipalities, coordinates, altitude]. Thin gold divider lines. Narrow footer strip with: coordinates, altitude, EPW station, Köppen-Geiger code. Flat vector studio style, generous whitespace, highly legible, no photographs, no additional text.

Cada resultado corresponde a uma secção das pranchas.

## 4. Anexos obrigatórios por grupo

1. Quatro imagens do sítio: captura Google Maps ou similar (1 km e 500 m, com escala e norte) e fotografias próprias do sítio, se existentes (com autoria, data, ponto e orientação)
2. Dossiê climático: ficheiro EPW da estação mais próxima (com distância e diferença de altitude), ficha IPMA correspondente e categoria Köppen-Geiger do município
3. Dossiê socioeconómico: quadros INE e Pordata (Fundação Francisco Manuel dos Santos) dos municípios — população, envelhecimento, densidade, alojamentos, escolaridade, emprego e poder de compra, com ano e tabela de origem
3. Um extrato do PDM (reprodução do artigo ou parágrafo com altura e índice)
4. Três registos de arquitetura vernácula e dois de arquitetura contemporânea, com créditos

Na ausência de anexos, o resultado deverá ser assinalado como provisório. Esta marcação integra a avaliação (o processo prevalece sobre o produto).

## 5. Verificação e validação crítica (obrigatória)

Cada grupo apresenta a validação em quatro pontos:
- conformidade regulamentar: confirmação do artigo no sítio eletrónico do município;
- dados climáticos: confirmação de vento e radiação junto do IPMA e do Portal do Clima;
- referências culturais: confirmação da existência da obra (atelier, município, publicação especializada);
- dados socioeconómicos: reconfirmação de cada indicador usado na SWOT nas tabelas INE e Pordata (valor, ano, tabela) — sem fonte, o ponto é retirado da SWOT.

Modelo de declaração: "O grupo [n.] declara ter utilizado o Muse Spark 1.3 Free nos prompts P0–P6, em [datas]. Foram anexados [lista]. Foram verificados [três fontes]. Foi rejeitada a sugestão [x] pelo motivo [y]."

## 6. Elementos de entrega (quatro pranchas, normalizadas para as 26 sub-regiões)

1. **Território e lugar** — NUTS, plantas, figura-fundo e quadro INE/Pordata
2. **Clima** — síntese EPW e duas regras de volumetria
3. **Cultura** — três regras vernáculas, duas obras de referência e uma tendência, com créditos
4. **Síntese** — SWOT, duas volumetrias, programa, declaração de utilização de IA e validação

Avaliação da UC: participação 20% (debate e desk crits); portefólio 80% (conversação exportada, qualidade, verificação e sentido crítico de autoria).

## 7. Função docente

- Atribuição das sub-regiões, assegurando a cobertura do Norte às ilhas.
- Disponibilização de ficheiros EPW de base, ligações aos PDM e grelha de prompts.
- Desk crit intermédio sobre P2 e P3 (lugar e clima) antes da formulação volumétrica.
- Compilação final das 26 sínteses no atlas da turma.

## 8. Fontes a citar no rodapé do HTML

- Território e socioeconomia: INE (Censos, indicadores e destaques), Pordata (Fundação Francisco Manuel dos Santos), NUTS 2024, Regulamento Delegado UE 2023/674, CCDR.
- Clima: EnergyPlus/onebuilding/epwmap, Portal do Clima, IPMA normais.
- Regras: PDM municipal + DGT/SNIG + Lisboa Aberta/Dados Abertos.
- Stats IA: Chaos+Architizer 2024 (46%) + 2026 update; Automation in Construction 2025 (68.94% early-phase).
- Bibliografia UC: Elzeni & Mostafa 2025; Li et al. 2025; Peckham et al. 2025; Yiannoudes 2025; Cortiços et al. 2023/2025.
