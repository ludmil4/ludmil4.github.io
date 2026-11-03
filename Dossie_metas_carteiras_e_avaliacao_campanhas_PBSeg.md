# PBSeg — dossiê para revisão das metas e avaliação das campanhas

**Data:** 03/11/2026. **Finalidade:** transferir o contexto relevante a outra IA ou analista, permitir crítica independente e orientar a próxima campanha. Este documento consolida decisões, dados, propostas e uma nova avaliação retrospectiva da Loja Figital. Não é regulamento aprovado nem relação oficial de ganhadores.

## 1. Leitura executiva

1. **Gerentes de relacionamento:** APFIN deve ser a meta principal, com capital protegido como gatilho. Carteiras exclusivas e corbans não oferecem a mesma oportunidade; comparar percentuais brutos não mede esforço equivalente.
2. **Referência:** usar agosto–outubro, com contexto de janeiro–outubro e mudanças de produto ao longo do tempo. Outubro isolado e o pico de setembro não são boas âncoras universais.
3. **Campanha nova dos gerentes:** novembro e dezembro completos; dois clusters por função, expansão versus demais gerentes. A simulação financeira existente mantém R$ 2 mil para os 12 gerentes; o flyer propõe R$ 2 mil/R$ 1 mil, ainda sujeito a validação.
4. **Orçamento:** a distribuição por peso da carteira fecha exatamente o orçamento por construção. Isso não demonstra que o desafio é factível e não equivale à proposta ajustada pelo histórico.
5. **Figital, setembro–outubro:** há evidência descritiva de APFIN agregado melhor que no período anterior e compatível com os gatilhos do canal. Não há evidência de crescimento sustentado do capital protegido; a leitura é mista.
6. **Acessibilidade da campanha anterior:** 15 de 32 atendentes atingiriam 90% de APFIN e R$ 100 mil de capital protegido no bimestre disponível. Com o filtro adicional de orçamento, restariam 9 ou 7, dependendo da definição de “meta orçada”. São simulações condicionais, não vencedores homologados.
7. **Campanha futura da Figital:** priorizar a ponta pode fazer sentido comportamental, mas prêmios amplos de R$ 500 exigem cuidado financeiro. No cenário de volume recente e APFIN de 93%, a margem adicional simulada é de cerca de R$ 9,25 mil no bimestre; R$ 500 para 32 atendentes custariam R$ 16 mil, ou R$ 17,6 mil com taxa de voucher de 10%.
8. **Conclusão crítica:** não classificar a campanha anterior simplesmente como sucesso ou fracasso. Atingimento de taxa, crescimento de volume, acessibilidade da meta, pagamento e retorno incremental são dimensões distintas; parte delas ainda não pode ser fechada com os dados disponíveis.

## 2. Fontes e rastreabilidade

Repositório principal: `ludmil4/ludmil4.github.io`. A planilha final foi salva no GitHub no commit `e479e8927be04f3f73afe6d36b2abe09bd02189b`.

| Fonte | Conteúdo e uso | Blob Git verificado |
|---|---|---|
| [Emissões por tipo de operação](https://github.com/ludmil4/ludmil4.github.io/blob/main/Emissoes_por_Tipo_Operacao__Refin__Novo__Port_%20(7).xlsx) | 53.492 registros, janeiro–outubro/2026; elegível, integrado com seguro, produto, canal, operação e usuário | `d0c03e4c4873c5d97aedca684fc04d121febd1a5` |
| [Base consolidada de RV](https://github.com/ludmil4/ludmil4.github.io/blob/main/Etapa1_base_consolidada_RV_1.xlsx) | 283 registros originais, maio–outubro; metas, produção por pessoa/função e de-para de 308 códigos | `2cf3c0c7e42183161122ffa6b76592118fe3f9dd` |
| [Campanha Loja Figital + Gerentes](https://github.com/ludmil4/ludmil4.github.io/blob/main/CAMPANHA%20LOJA%20FIGITAL%20%2B%20GERENTES.pdf) | Campanha de 01/09 a 31/10/2026; regras, públicos, rankings e sorteios; páginas 1–7 Figital, 9–13 CE, 14–19 CM | `ab7ab9ca6791c02abbab96a776d5a3da6a5754ce` |
| [Meta comercial oficial 2026](https://github.com/ludmil4/pbseg-conte/blob/main/pbseg-meta/PBSeg_Meta_Comercial_2026_Oficial.xlsx) | Repositório privado; Base Orçamento por mês/canal/produto, versão parametrizada para setembro | `c097ab2044ea641625c7aa87a22bd6a3c136396a` |
| [Planilha final de trabalho](https://github.com/ludmil4/ludmil4.github.io/blob/main/Incentivo_novembro_metas_e_diagnostico.xlsx) | Cinco abas: RV, emissão, orçamento, metas e overview; metas e ROI simulados | `f5e3fa167f786f948bd3c2515cc7b3248c77cbea` |
| [Notas de perfil](https://github.com/ludmil4/ludmil4.github.io/blob/main/estrategia-campanha-banco-perfil-gerentes_1.md) e [cenário inicial](https://github.com/ludmil4/ludmil4.github.io/blob/main/campanha-banco-etapa1-leitura-cenario.md) | Contexto anterior; hipóteses e conclusões antigas precisam ser confrontadas com as correções deste documento | — |
| [Black HTML](https://github.com/ludmil4/ludmil4.github.io/blob/main/black-alcifmais.html) e [PNG](https://github.com/ludmil4/ludmil4.github.io/blob/main/black-alcifmais.png) | Referências visuais e campanha da ponta; não são regulamento dos gerentes | — |

Os números abaixo foram recalculados dos arquivos locais com blobs conferidos. A memória do projeto foi relida na versão 8. A emissão e a RV têm conceitos e cortes diferentes: elas são apresentadas separadamente.

## 3. Conceitos indispensáveis para a outra IA

- **APFIN:** soma do capital protegido dividido pela soma do crédito elegível no mesmo período e recorte. Nesta análise, o numerador operacional é `Regra - Total Integrado C/ Seguro (Com limitador)`; o denominador é `-Regra- Crédito Elegível`. Não usar média simples dos percentuais.
- **Capital protegido:** volume de crédito com cobertura segundo o numerador operacional; não é prêmio do seguro, receita, comissão nem lucro.
- **Penetração RV:** `Liberado Seguro / Liberado Total`; não é APFIN. Não comparar diretamente uma penetração de 11% com APFIN de 91% como se fossem o mesmo indicador.
- **Elegível de referência de novembro:** mediana mensal recente, usada para projetar oportunidade. Não é piso de venda de crédito nem orçamento individual oficial.
- **Piso protegido:** mínimo monetário para habilitar o prêmio. A exigência efetiva é `capital protegido >= máximo(piso; APFIN-meta × elegível realizado)`. Exemplo: piso de R$ 5 milhões em R$ 10 milhões elegíveis exige 50%, mesmo que a taxa anunciada seja 45%.
- **M0:** outubro/2026 disponível. **L3M:** agosto–setembro–outubro. **FY disponível:** janeiro–outubro, não ano completo fechado.
- **Potencial operacional:** estimativa com a maior entre taxa própria e P75 de pares no mesmo canal/convênio/operação, mínimo dois pares, com ampliação por convênio quando necessário. Não é teto técnico, probabilidade de atingimento nem prova de esforço insuficiente.
- **Peso da carteira:** precisa declarar o denominador. Peso dentro do canal serve ao rateio do orçamento do canal; peso nos 12 gerentes serve ao porte da carteira. Não são intercambiáveis.

### Qualidade, escopo e datas

1. Normalizar `codPromotor` para o cruzamento, preservando o código original, e respeitar `inicio_vigencia`. Não atribuir retrospectivamente toda a carteira ao gerente atual antes do vínculo.
2. O histórico anual dos parceiros hoje vinculados descreve a carteira; não prova a gestão da pessoa em todos os meses. Para veteranos, abril–outubro é a janela atribuída mais comparável após redistribuições cadastrais.
3. Estoque de lojas é contagem de códigos/pontos, não necessariamente de CNPJs. Ausência de elegível não prova ociosidade ou ausência de vendas para outros bancos.
4. Outubro na RV original é parcial até 26/10; há uma aba antiga projetada por 21/17 dias úteis. A emissão não documenta corte diário. Não projetar a emissão com o fator da RV nem declarar outubro fechado.
5. Linhas com seguro maior que elegível, elegível zero e seguro positivo ou valores negativos ficam nas fontes e são segregadas de ambos os lados na calibração. Exclusão diagnóstica não é correção contábil definitiva.
6. A RV registra a mesma produção em atendentes, coordenação e gerência. Somar hierarquias triplica o resultado. O agregado Figital usa o nível da ponta ou uma única consolidação.
7. Há denominadores/linhas diferentes entre RV e emissão, sobretudo em outubro. O APFIN é analisado pela emissão; a meta de RV é analisada pela própria RV, sem chamar a combinação de apuração oficial da campanha.

## 4. Decisões atuais para gerentes de relacionamento

**Objetivo:** fazer o gerente mobilizar promotoras e correspondentes para oferecer crédito com proteção. O gerente influencia o parceiro; quem efetiva a venda é a ponta.

- Período atual: **01/11 a 31/12/2026**, dois meses completos. A etapa só novembro e a data antiga de 23/12 foram substituídas.
- Dois clusters: **1 = demais gerentes de relacionamento; 2 = função de expansão**, não apenas tempo de casa ou tamanho. Ana Luisa, Débora e Elisângela foram explicitamente citadas como expansão; Fabiano consta como recente/expansão nas bases, mas convém confirmar o enquadramento nominal final.
- Cluster 1: APFIN individual como meta, protegido como gatilho. Prêmios de R$ 2 mil e R$ 1 mil para os clusters 1 e 2 aparecem na minuta visual; a simulação financeira solicitada continua com R$ 2 mil para todos.
- O flyer propõe apuração mensal e prêmio único ao final se as metas dos dois meses forem cumpridas. Isso ainda precisa de confirmação; não foi aprovado que um mês compense o outro nem pagamento parcial.
- A usuária pediu manter CLT, pois pode voltar. Incluí-lo no histórico e no orçamento não significa presumir recuperação plena na projeção.
- Aumento de APFIN em torno de 3–5 p.p. é intenção de desenho; não é garantia de esforço equivalente. O piso não pode esconder uma taxa implícita muito superior à anunciada.
- Novembro: elegível e piso de protegido ancorados na mediana recente conciliada. Dezembro: ajuste pelo fator de elegível orçado dezembro/novembro de cada canal, com CLT incluído; APFIN-meta igual nos dois meses.
- Estrutura atual da planilha: exatamente cinco abas solicitadas, sem retornar à versão antiga de 13 abas.

### Mudanças de produto que precisam permanecer na análise

Lud informou descontinuação do CLT em agosto e choque no SIAPE em 20/09. A extração mensal não identifica o efeito diário nem prova causalidade regulatória. Não excluir um produto de todos os meses para fingir que ele nunca existiu.

Caso central: na Sabrina, o protegido CLT caiu de R$ 4,547 milhões em julho para R$ 875 mil em agosto, redução de R$ 3,672 milhões. Outros produtos cresceram cerca de R$ 710 mil. O APFIN total caiu de aproximadamente 56,0% para 44,1%, enquanto o dos remanescentes melhorou de 26,3% para 37,3%, no recorte original da análise. Portanto, queda do agregado não equivale automaticamente a pior atuação comercial. Os números conciliados de calibração diferem ligeiramente dos brutos.

INSS e cartões aparecem frequentemente com elegível zero. A base não permite concluir, sozinha, qual vedação explica cada caso nem generalizar uma proibição regulatória. Falta elegibilidade/produção total por produto fora do denominador e histórico de regras comerciais.

## 5. Diagnóstico das carteiras de relacionamento

Indicadores recentes conciliados para a calibração, incluindo CLT. Estoque/ativos são os códigos do cadastro e os que tiveram elegível positivo em agosto–outubro. APFIN em %; elegível de referência em R$ milhões.

| Gerente | Canal predominante | Estoque/ativos L3M | Elegível ref. nov, R$ mi | APFIN ago | APFIN set | APFIN out | APFIN L3M |
|---|---|---|---|---|---|---|---|
| Patrícia | CE | 38/33 | 9,284 | 74,1% | 72,5% | 72,7% | 73,2% |
| Sheila | CM | 47/22 | 10,044 | 43,4% | 44,9% | 42,9% | 43,8% |
| Sabrina | CM | 44/20 | 7,378 | 43,6% | 37,2% | 34,7% | 38,8% |
| Senna | CM | 20/7 | 5,104 | 43,7% | 48,6% | 38,6% | 44,2% |
| Luana | CE | 29/25 | 2,878 | 64,1% | 57,9% | 67,6% | 63,2% |
| Malvaci | CE | 20/18 | 2,244 | 61,0% | 63,6% | 64,7% | 63,1% |
| Doudat | CE | 35/24 | 1,616 | 67,7% | 77,5% | 73,6% | 73,6% |
| Hingrithi | CE | 26/17 | 0,495 | 50,3% | 69,6% | 86,3% | 64,5% |
| Ana Luisa | CM | 1/1 | 0,304 | 100,0% | 15,2% | 13,2% | 18,8% |
| Débora | CM | 9/7 | 0,332 | 24,4% | 89,4% | 58,5% | 70,0% |
| Elisângela | CM | 2/2 | 0,093 | 100,0% | 30,7% | 75,6% | 76,9% |
| Fabiano | CM | 1/0 | 0,000 | — | — | — | — |

**Patrícia — CE, carteira ampla e relativamente distribuída.** 38 pontos, 33 com elegível; top 5 representam 55,7% do elegível recente. SIAPE é cerca de 19,9% do mix, muito menos que nos grandes CMs. Principais convênios: SIAPE, PM Colombo, Estado PR e TJ PR. A taxa recente é estável, mas o protegido caiu de R$ 7,30 milhões em agosto para R$ 5,46 milhões no outubro disponível. Oportunidade: recuperar volume, explorar TJ PR e bolsões abaixo da taxa própria/pares sem cobrar a taxa bruta de todo canal indistintamente. Exclusividade facilita a conversa, segundo a avaliação comercial da usuária, mas não é efeito causal medido.

**Sheila — CM com componente digital, grande volume e dependência de SIAPE.** Cadastro: 43 CMs e quatro códigos digitais; 22 de 47 tiveram elegível recente. SIAPE representa 67,5%; top 5 pontos, 65,5%. No mix recente, SIAPE converte aproximadamente 39,5%, Estado PR 49,9%, PM Maringá 85,2% e FGTS 24,3%, antes da segregação específica de linhas incompatíveis. Oportunidade principal: maiores parceiros/SIAPE, não elevar todas as carteiras à taxa dos convênios municipais. A base conciliada cai para 43,8% por inconsistências preservadas à parte, incluindo uma linha de agosto com protegido maior que elegível. Não tratar a diferença de cadastro digital como prova de inelegibilidade.

**Sabrina — CM, carteira muito concentrada e afetada pela mudança de produto.** 43 CMs e uma CE cadastradas; 20 pontos com elegível; top 5 concentram 89,2%. SIAPE é 68,9% do elegível L3M e CLT, 4,9% nessa janela, embora tenha sido muito mais relevante antes. APFIN conciliado cai de 43,6% em agosto para 34,7% em outubro. SIAPE recente em aproximadamente 36,7%, Estado PR 47,0% e FGTS 25,2% no bruto. Oportunidade: recuperação das principais promotoras, SIAPE e mix; não usar o pico CLT do primeiro semestre como obrigação futura. A meta com CLT foi recalibrada para 43%, substituindo 40,5% da versão sem CLT.

**Senna — CM altamente concentrado.** 20 pontos, sete com elegível; top 5 concentram 99,7%. SIAPE, 79,9% do elegível recente. APFIN foi de 48,6% em setembro para 38,6% no outubro disponível. Oportunidade: poucos relacionamentos de grande impacto; atuação por promotor e operação SIAPE, com atenção ao volume. Não distribuir esforço por 20 lojas como se todas tivessem a mesma relevância nem usar setembro como produção normal garantida.

**Luana — CE, rede ativa e diversificada, recuperação recente.** 29 pontos, 25 com elegível, top 5 de 56,3%; exposição SIAPE de apenas 3,4%. PM Ponta Grossa e Estado PR dominam; PM Ponta Grossa teve APFIN recente de aproximadamente 42,2%, Estado PR de 69,1%. APFIN recuperou de 57,9% em setembro para 67,6% em outubro. Oportunidade: convênios e pontos abaixo da própria rede, especialmente Ponta Grossa; a meta L3M+4 p.p. já fica perto do outubro recente, logo pode ser manutenção da recuperação e não incremento novo sobre M0.

**Malvaci — CE em melhora de conversão, com volume menor em outubro.** 20 pontos, 18 com elegível; top 5 de 61,8%. SIAPE é 35,2%; taxa recente no SIAPE de aproximadamente 46,1%, contra 82,0% em Estado PR. APFIN sobe de 61,0% para 63,6% e 64,7% em agosto–outubro, enquanto elegível de outubro recua. Oportunidade: capturar gap SIAPE e PM Arapongas, preservar convênios fortes e recuperar volume. Não confundir sua trajetória crescente com a recuperação oscilante de Luana, apesar de ambas terem base L3M próxima de 63%.

**Doudat — CE com boa conversão, menor escala e concentração intermediária/alta.** 35 pontos, 24 com elegível; top 5 de 73,8%. SIAPE de 21,7%, com taxa recente perto de 58,4%; PM Tijucas–Cartão e Estado PR têm taxas muito elevadas. Melhor APFIN recente em setembro, 77,5%; outubro em 73,6%. Oportunidade: aumentar elegível/ativação e melhorar SIAPE, preservando qualidade. O PDF registra prêmio mensal com 78% APFIN. Esse resultado é coerente com a ordem de grandeza da emissão, não com a penetração RV sobre crédito total.

**Hingrithi — Grupo Azul, CE predominante, qualidade do dado é prioridade.** 25 CEs e uma CM; 17 pontos com elegível, top 5 de 90,7%, SIAPE de 56,5%. Há volume com seguro sem elegível e recortes acima de 100%. APFIN L3M cai de cerca de 70,7% bruto para 64,5% na calibração conciliada; outubro conciliado ainda sobe a 86,3%. Oportunidade: SIAPE e institutos de previdência, mas validar cobertura, cadastro e elegibilidade antes de chamar a taxa alta de melhor desempenho ou fixar prêmio. Meta e piso permanecem pendentes.

**Ana Luisa — expansão CM, um parceiro, quase toda a oportunidade em SIAPE.** 98,6% do elegível recente é SIAPE; setembro/outubro têm cerca de R$ 304 mil/R$ 349 mil elegíveis, porém APFIN de apenas 15,2%/13,2%. O 100% de agosto veio de apenas R$ 37,8 mil, não deve ancorar uma meta irreal. Oportunidade: construir rotina de oferta e ativar novos relacionamentos, além de melhorar o atual. Meta de 22% e piso de R$ 46 mil são simulações da carteira existente, insuficientes para representar a expansão futura sem plano de novos parceiros.

**Débora — expansão CM, SIAPE integral e volatilidade.** Nove pontos, sete com elegível, top 5 de 99,3%. APFIN variou de 24,4% em agosto para 89,4% em setembro e 58,5% em outubro. Oportunidade: estabilizar oferta nos parceiros grandes e ampliar a base. Base ponderada L3M de 70% não garante que 73% seja uma exigência pequena em relação a outubro. Antes de aprovar, conferir sustentabilidade do pico e mix por parceiro/operação.

**Elisângela — expansão CM, base pequena e concentrada.** Dois pontos; um concentra aproximadamente 99,2% do elegível. SIAPE é 94,0% do mix recente. APFIN de 100%/30,7%/75,6% em agosto–outubro é muito volátil. Piso pela mediana de protegido seria R$ 93,2 mil, igual ao elegível mediano: exigiria 100%, apesar da taxa-meta sugerida de 80%. Por isso o piso foi deixado pendente. Oportunidade: crescimento da base e rotina de oferta; é preciso previsão comercial para uma meta de volume coerente.

**Fabiano — expansão/entrada comercial a confirmar, sem elegível observado.** Um ponto cadastrado, registros concentrados em INSS com elegível zero. Não atribuir APFIN zero, retorno zero potencial ou meta impossível. Oportunidade inicial: habilitar oferta elegível e ativar parceiro/convênio, com prazo e produção inicial verificáveis. Taxa e piso só após plano de entrada.

### Por que Patrícia não deve ser comparada diretamente a Sabrina

Em outubro bruto, o SIAPE era aproximadamente 20,2% do elegível de Patrícia e 73,2% de Sabrina. Mesmo dentro do SIAPE, as taxas diferiam: 68,2% e 34,3%. Uma decomposição descritiva anterior do gap de 37,99 p.p. associou 22,71 p.p. (59,8%) à composição por convênio e operação, restando 15,28 p.p. de diferenças nas taxas internas. Isso não prova efeito causal do gerente ou do canal: condições comerciais, parceiros e clientes continuam diferentes.

### Contexto anual da carteira atual — janeiro a outubro

Recalculado segregando linhas incompatíveis. Inclui meses anteriores à gestão atual quando os parceiros já existiam; serve para entender a carteira. Não é avaliação anual de responsabilidade do gerente. “Média mensal” é estatística descritiva; a taxa ponderada é a razão entre totais.

| Gerente | Meses com elegível | APFIN ponderado | Média mensal | Mediana mensal | Mínimo | Máximo |
|---|---|---|---|---|---|---|
| Patrícia | 10 | 77,4% | 77,2% | 74,9% | 72,4% | 85,5% |
| Sheila | 10 | 46,9% | 47,8% | 46,3% | 36,8% | 65,4% |
| Sabrina | 10 | 49,8% | 46,0% | 46,4% | 33,3% | 66,8% |
| Senna | 10 | 43,7% | 42,3% | 41,3% | 32,6% | 51,5% |
| Luana | 10 | 68,6% | 68,0% | 68,7% | 57,9% | 75,7% |
| Malvaci | 10 | 56,5% | 59,8% | 62,3% | 45,6% | 78,1% |
| Doudat | 10 | 64,4% | 64,4% | 63,8% | 55,4% | 77,5% |
| Hingrithi | 10 | 42,8% | 56,0% | 55,8% | 25,8% | 86,3% |
| Ana Luisa | 3 | 18,8% | 42,8% | 15,2% | 13,2% | 100,0% |
| Débora | 8 | 58,5% | 21,5% | 0,0% | 0,0% | 89,4% |
| Elisângela | 3 | 76,9% | 68,8% | 75,6% | 30,7% | 100,0% |
| Fabiano | 0 | — | — | — | — | — |

Os oito meses com elegível da carteira atual de Débora incluem produção anterior à expansão atribuída, com vários meses sem seguro. Não interpretá-los como oito meses de atuação pessoal. Para todos, data cadastral não substitui admissão nem valida mudanças de carteira.

## 6. Metas já simuladas para relacionamento — propostas, não aprovação

Taxas e pisos abaixo são os da última planilha de cinco abas, com CLT. Valores monetários em reais. São distintos do rateio puro do orçamento da seção seguinte.

| Gerente | APFIN nov/dez | Piso protegido nov | Piso protegido dez |
|---|---|---|---|
| Patrícia | 76,5% | R$ 6.735.000 | R$ 4.380.000 |
| Sheila | 47,0% | R$ 4.313.000 | R$ 3.611.000 |
| Sabrina | 43,0% | R$ 2.833.000 | R$ 2.372.000 |
| Senna | 47,5% | R$ 2.166.000 | R$ 1.813.000 |
| Luana | 67,5% | R$ 1.886.000 | R$ 1.227.000 |
| Malvaci | 66,5% | R$ 1.369.000 | R$ 890.000 |
| Doudat | 77,0% | R$ 1.094.000 | R$ 712.000 |
| Hingrithi | — | Pendente | Pendente |
| Ana Luisa | 22,0% | R$ 46.000 | R$ 39.000 |
| Débora | 73,0% | R$ 205.000 | R$ 172.000 |
| Elisângela | 80,0% | Pendente | Pendente |
| Fabiano | — | Pendente | Pendente |

A taxa-meta é obtida somando 3 p.p. à base, ou 4 p.p. para Sabrina e Luana, e arredondando para cima em passos de 0,5 p.p. O aumento efetivo fica por volta de 3–4,3 p.p. As metas dos gerentes de expansão ainda precisam de redesenho próprio e não são regras fechadas do cluster 2.

**Crítica:** o capital protegido mediano pode deixar o gatilho baixo para uma carteira em crescimento ou impor taxa implícita excessiva quando o elegível encolhe. Testar `piso / elegível previsto` junto da taxa anunciada e fazer teste de estresse de volume. Alguns pisos ficam abaixo do resultado esperado na taxa-meta; isso é coerente com o papel de gatilho, mas o cenário deve ser transparente.

### Cenário financeiro existente

- Incremento protegido simulado: **R$ 2.436.500** no bimestre.
- Margem adicional estimada: **R$ 103.434**, usando margem líquida orçada por real protegido de cada canal/mês.
- Premiação: **R$ 24.000**, R$ 2 mil × 12 gerentes; benefício calculável para dez taxas, custo reservado para os doze.
- Saldo após prêmios: **R$ 79.434**; ROI aproximado de **331%**.

Não é retorno observado nem efeito causal. Supõe volume mediano, sazonalidade do orçamento e margem unitária do mix orçado. Não inclui novos parceiros ainda sem plano, eventual taxa de voucher, custo operacional extra, tributos adicionais não incorporados ou ajustes de persistência. Se os R$ 24 mil forem valor líquido de voucher e houver 10% de taxa adicional, o custo sobe para R$ 26,4 mil e o ROI dessa mesma simulação cai para aproximadamente **291,8%**. Evitar dupla contagem se a taxa já estiver no custo informado.

Para R$ 2 mil/R$ 1 mil por cluster, recalcular o custo depois de fechar a lista. O cenário anterior de aproximadamente 360% era sem CLT e está superado.

## 7. Alternativa pedida: meta apenas por peso da carteira e orçamento

Fórmula: `protegido orçado do canal/mês × elegível conciliado L3M do gerente / elegível conciliado L3M dos gerentes do canal`. Rateio integral hipotético; não orçamento individual oficial. O banco pode ter outras carteiras nesses canais. Valores em R$ mil.

| Gerente | Canal | Peso dentro do canal | Novembro, R$ mil | Dezembro, R$ mil |
|---|---|---|---|---|
| Patrícia | CE | 54,2% | 7.571,5 | 4.931,8 |
| Luana | CE | 17,9% | 2.507,7 | 1.633,4 |
| Malvaci | CE | 13,7% | 1.916,6 | 1.248,4 |
| Doudat | CE | 11,3% | 1.583,0 | 1.031,1 |
| Hingrithi | CE | 2,8% | 396,5 | 258,3 |
| Sheila | CM | 44,3% | 4.396,0 | 3.799,8 |
| Sabrina | CM | 29,1% | 2.884,6 | 2.493,4 |
| Senna | CM | 24,2% | 2.407,4 | 2.080,9 |
| Débora | CM | 1,0% | 103,1 | 89,1 |
| Ana Luisa | CM | 1,0% | 96,8 | 83,7 |
| Elisângela | CM | 0,4% | 40,9 | 35,4 |
| Fabiano | CM | Sem base | — | — |

Orçado protegido: CE novembro **R$ 13.975.304**, dezembro **R$ 9.103.109**; CM novembro **R$ 9.928.883**, dezembro **R$ 8.582.168**. Total: **R$ 23.904.187** e **R$ 17.685.276**. O total fecha 100% por construção; Fabiano não tem rateio numérico.

Na proposta por mediana, os pisos conhecidos somam R$ 11,084 milhões CE e R$ 9,563 milhões CM em novembro; R$ 7,209 milhões CE e R$ 8,007 milhões CM em dezembro. As somas são parciais: faltam três pisos. Estar abaixo do orçamento não significa necessariamente subdimensionamento, pois o escopo do canal pode ser maior que a equipe.

Originação total do banco, outra medida: novembro R$ 202,183 milhões e dezembro R$ 160,370 milhões. A lembrança de R$ 216 milhões não se confirmou no arquivo consultado. Nunca comparar piso de protegido diretamente com toda a originação.

## 8. Campanha histórica da Loja Figital — regras lidas no PDF

**Período:** 01/09 a 31/10/2026. O PDF usa “Atendentes, Supervisores e Gerentes”. A base usa LP-A, LP-C e LP-G. A usuária mencionou superintendentes nesta solicitação, mas o material não estabelece uma campanha específica para esse cargo; LP-C não deve ser renomeado como superintendência sem confirmação.

| Público/condição | Desenho observado | Localização |
|---|---|---|
| Atendentes | R$ 100 mil de protegido, APFIN 90%, meta orçada acima de 85%; critérios por função/canal | pp. 3–4 |
| Canal Figital | APFIN mínimo 88% como habilitação coletiva | p. 4 |
| Melhor e segundo atendente | Referência de 90% APFIN; vouchers de R$ 2.000 e R$ 1.500 | p. 5, conferida visualmente |
| Supervisores | Melhor: 90%, R$ 2.000; segundo e terceiro acima de 88%, dois vouchers de R$ 500 | p. 5 |
| Gerente | 88%; um voucher CVC/Airbnb, sem valor legível/especificado nessa linha | p. 5 |
| Sorteios | Três sorteios CVC/Airbnb entre atendentes habilitados, referência 90%; valores não informados na página | p. 6 |
| Ação mensal de setembro | 90% para atendentes, supervisores e gerentes; Alexa, fone ou Xbox | p. 7 |

Há diferenças de fronteira entre “mínimo” e “acima de”. A análise diagnóstica usa APFIN >=90%, protegido >=R$100 mil e orçamento >85%; nenhum valor exatamente em 90% foi encontrado entre os atendentes nos dois meses. Ainda é necessário regulamento para desempate, acumulação de prêmios, cálculo de ranking, orçamento de referência e tratamento dos meses.

A usuária informou verba anterior do gerente em torno de **R$ 2.500**. Registrar como informação da usuária a confirmar no custo efetivo; não substituir o valor ausente da tabela do PDF por um fato documental.

**Problemas de desenho:** muitos filtros simultâneos; condição coletiva pode bloquear bom desempenho individual; ranking reconhece poucos e sorteio enfraquece a relação esforço/prêmio; metas de 90% deixam pouca folga para volume, mix e ajustes, embora sejam alcançáveis para parte da ponta. Por outro lado, viagens e prêmios mensais têm apelo e criam cadência de comunicação.

## 9. Resultado mensal observado da Figital

Escopo: três códigos 800862/800863/800864 associados à Figital no de-para, canal de origem “Call Center”. Valores da emissão, com CLT. “Conciliado” segrega linhas incompatíveis, sem alterá-las na fonte. R$ milhões.

| Mês | Elegível | Protegido bruto | APFIN bruto | Protegido conciliado | APFIN conciliado |
|---|---|---|---|---|---|
| 01/2026 | 4,512 | 4,157 | 92,1% | 4,150 | 92,1% |
| 02/2026 | 4,851 | 4,198 | 86,6% | 4,194 | 86,5% |
| 03/2026 | 4,579 | 4,166 | 91,0% | 4,129 | 90,8% |
| 04/2026 | 6,098 | 5,028 | 82,5% | 5,015 | 82,4% |
| 05/2026 | 6,113 | 5,279 | 86,4% | 5,029 | 82,3% |
| 06/2026 | 6,591 | 5,571 | 84,5% | 5,571 | 84,5% |
| 07/2026 | 6,499 | 5,626 | 86,6% | 5,561 | 86,2% |
| 08/2026 | 3,938 | 3,542 | 89,9% | 3,541 | 89,9% |
| 09/2026 | 4,919 | 4,475 | 91,0% | 4,475 | 91,0% |
| 10/2026 | 3,548 | 3,283 | 92,5% | 3,233 | 91,1% |

### O que mudou no bimestre

- Junho–agosto conciliado: APFIN **86,43%**; setembro–outubro disponível: **91,03%**, melhora descritiva de **4,60 p.p.** Janelas com cortes e mix distintos; não é estimativa causal.
- Comparando julho–agosto a setembro–outubro: elegível cai de **R$ 10,385 milhões para R$ 8,467 milhões (-18,5%)**; protegido conciliado de **R$ 9,102 milhões para R$ 7,708 milhões (-15,3%)**; APFIN sobe de **87,64% para 91,03% (+3,39 p.p.)**.
- Setembro contra agosto: protegido conciliado sobe aproximadamente **26,4%**; APFIN de **89,91% para 90,98%**.
- Outubro contra setembro, nos recortes disponíveis: elegível cai **27,9%**, protegido conciliado cai **27,8%** e APFIN quase se mantém, de **90,98% para 91,10%**. Não concluir queda de mês fechado sem o corte de outubro.
- Outubro tem cerca de **R$ 50,4 mil de protegido em linhas incompatíveis**; a taxa bruta de **92,52%** vira **91,10%** após a segregação. Não vender todo o ganho bruto como conversão real.
- O canal supera 88% e 90% em setembro, outubro conciliado e bimestre disponível. Logo, o filtro coletivo de taxa não parece ser o principal bloqueio nesse recorte.

### Produto explica parte relevante da variação

SIAPE na Figital: elegível de R$ 1,304 milhão em agosto, R$ 2,342 milhões em setembro e R$ 1,117 milhão no outubro disponível; APFIN de 78,1%, 88,3% e 85,5%. O protegido SIAPE caiu cerca de R$ 1,114 milhão de setembro para outubro, respondendo por aproximadamente 89,7% da queda total conciliada do protegido do canal nessa comparação. É decomposição contábil, não prova de efeito do evento de 20/09.

CLT foi R$ 70,8 mil elegíveis/protegidos em agosto e não aparece com volume positivo em setembro–outubro nesse escopo. Não exigir o pico passado desse produto na campanha futura sem confirmação de oferta.

**Avaliação:** a campanha foi compatível com manutenção/melhora de conversão, mas os dados não mostram expansão sustentada do volume protegido. Também não permitem dizer que sem campanha o resultado seria igual, maior ou menor.

### RV: produção e atingimento separados do APFIN

Abaixo, um único nível LP-A, sem somar novamente coordenação/gerência. Outubro é o parcial original da RV, não projetado. R$ milhões.

| Mês | Liberado total RV | Liberado seguro RV | Meta seguro RV | Ating. total | Ating. seguro |
|---|---|---|---|---|---|
| 05/2026 | 18,228 | 4,448 | 5,878 | 90,0% | 75,7% |
| 06/2026 | 22,056 | 5,078 | 9,445 | 102,7% | 53,8% |
| 07/2026 | 22,233 | 5,379 | 4,708 | 69,0% | 114,2% |
| 08/2026 | 20,047 | 3,398 | 3,182 | 88,3% | 106,8% |
| 09/2026 | 22,686 | 3,321 | 3,855 | 96,0% | 86,2% |
| 10/2026 | 21,271 | 2,375 | 3,966 | 89,9% | 59,9% |

Atingimento agregado de seguro na RV: setembro **86,2%**, outubro parcial **59,9%**. Mesmo a projeção antiga 21/17 levaria outubro a aproximadamente **74,0%**, não 100%; isso é exercício da RV, não projeção válida da emissão. A emissão registra protegido maior que o liberado seguro da RV, portanto não comparar o realizado de uma com a meta da outra sem conciliar definições.

É possível, simultaneamente, cumprir APFIN e não cumprir orçamento de volume. A campanha não deve confundir esses dois sucessos.

O orçamento oficial LP de protegido é R$ 5,479 milhões em setembro e R$ 5,894 milhões em outubro; o APFIN implícito é 93,28% e 93,63%. Se o escopo LP orçado corresponder exatamente à equipe Figital analisada, o protegido conciliado disponível representa aproximadamente 81,7% e 54,8% desses valores. Essa comparação é apenas condicional: confirmar cobertura e fechamento. Ela evidencia uma questão de desenho: o gatilho coletivo de 88% e mesmo a referência de 90% podem ser atingidos abaixo do APFIN implícito no orçamento do banco; habilitar prêmio não equivale a cumprir o planejamento.

## 10. Acessibilidade das metas para atendentes

Cruzamento diagnóstico entre nome na RV e usuário nominal da emissão, com normalização de acentos/caixa. Há 32 atendentes por mês e 32 pessoas no bimestre após unificar a abreviação de Kathia. Ana Carolina tem nome truncado na emissão; Viviane Macedo foi vinculada provisoriamente a Viviane Cristina Macedo. Esses vínculos e o cadastro devem ser homologados antes de pagamento. O vínculo de Viviane não altera o total final de habilitados pelo filtro orçamentário, mas afeta o funil anterior.

| Janela | Pessoas RV | Com elegível | Protegido ≥100 mil | APFIN ≥90% | Ambos | +85% orçamento total RV | +85% orçamento seguro RV |
|---|---|---|---|---|---|---|---|
| 09/2026 | 32 | 31 | 21 | 19 | 12 | 7 | 6 |
| 10/2026 | 32 | 23 | 17 | 15 | 11 | 7 | 4 |
| Bimestre disponível | 32 | 31 | 24 | 20 | 15 | 9 | 7 |

Os filtros mensais foram aplicados somente como diagnóstico, não como regra confirmada de pagamento mensal. No bimestre, os 85% foram testados sobre a razão de totais realizados/metas dos dois meses. Isso também depende de homologar a mecânica.

**Leitura do bimestre:** 15/32 (46,9%) passam taxa e volume; com orçamento total seriam 9/32 (28,1%); com orçamento de seguro, 7/32 (21,9%). Portanto, a meta não era impossível para todos, mas o desenho exclui a maioria e só duas posições por mérito mais três sorteios tinham premiação bimestral de atendente prevista. Não se sabe se havia acumulação; não presumir cinco ganhadores distintos.

Em outubro há nove pessoas na RV sem elegível positivo correspondente no recorte da emissão. Isso não é APFIN zero nem prova de falta de adesão: pode haver produto inelegível, corte, cadastro ou atribuição. O nome/usuário não substitui matrícula na homologação.

Não apresentar estes nove ou sete como ganhadores: falta conciliar fonte, definir “orçado”, corte, critérios estritos, cancelamentos, ranking e regra de acumulação. Não há lista oficial de pagamento nem resultado dos sorteios nos arquivos analisados.

## 11. Supervisão/coordenação e gerência Figital

A RV de maio–agosto associa Jeniffer ao código 800864, Jessyca a 800863 e Lucas a 800862. Em setembro–outubro o campo promotor dos supervisores está zerado. A leitura por equipe abaixo **supõe manutenção dessas equipes**; precisa de confirmação do de-para histórico de supervisão.

| Supervisão provisoriamente associada | APFIN set | APFIN out | APFIN bimestre | RV seguro set | RV seguro out parcial |
|---|---|---|---|---|---|
| Jeniffer Rossi Bezerra | 92,5% | 91,1% | 91,9% | 101,1% | 62,9% |
| Jessyca Crystyna de Quadros Correa | 92,0% | 94,4% | 93,0% | 79,8% | 46,7% |
| Lucas Henrique Carvalho | 89,6% | 89,2% | 89,4% | 79,2% | 66,0% |

- As três equipes superariam 88% no bimestre disponível; duas superariam 90%. No corte disponível, o desafio de taxa para supervisão é plausível, mas a de menor taxa não alcançaria 90% para disputar o topo.
- Somente Jeniffer supera 100% da meta RV de seguro em setembro; nenhuma das três no outubro parcial. Isso não anula APFIN alto: são indicadores diferentes.
- Gerência Ivan: o canal tem APFIN conciliado bimestral de 91,03%, acima de 88% e também de 90%; RV de seguro agregada de 86,2% em setembro e 59,9% no outubro parcial. Não é possível fechar pagamento porque “metas específicas” e custo do prêmio não estão integralmente definidos.
- Os fatores RV de setembro zerados são tratados no projeto como apuração não carregada; não são comprovação de ausência de remuneração ou de fracasso da campanha.
- Não foi identificada regra específica de superintendentes. Se o público pretendido for esse, solicitar hierarquia e carteira correspondentes, sem reaproveitar automaticamente LP-C.

**Recomendação de escopo futuro:** começar com atendentes, que realizam a venda, e atribuir à liderança cadência de acompanhamento. Só criar prêmio adicional para supervisão/gerência quando houver entrega adicional específica e custo contemplado no retorno. Pagar três níveis sobre o mesmo incremento pode consumir o ganho sem gerar três incrementos distintos.

## 12. Foi uma campanha efetiva?

| Dimensão | Evidência | Avaliação |
|---|---|---|
| Taxa APFIN | Canal acima de 90% no bimestre; taxa maior que no período anterior | Sinal favorável descritivo |
| Volume protegido | Setembro cresce sobre agosto; outubro disponível recua; bimestre abaixo de julho–agosto | Sem evidência de crescimento sustentado |
| Metas alcançáveis | Parte dos atendentes e equipes alcança os percentuais; funil reduz habilitados | Parcialmente acessível; filtros e comparação de carteiras precisam de revisão |
| Adesão | Há produção, mas não registros de convite, aceite, oferta, engajamento ou razões de perda | Não mensurável diretamente |
| Premiação efetiva | PDF não traz pagamentos/lista completa; sorteios sem resultados | Não verificável |
| ROI incremental | Não há custo realizado completo nem contrafactual | Não calculável como resultado causal |

**Meu julgamento:** o desenho tinha apelo, mas era complexo e premiava principalmente posições/sorte. Os dados não autorizam repetir a campanha sem ajustes nem classificá-la como fracasso. Há um sinal de conversão melhor, acompanhado de menor oferta elegível/volume e ruído de base. A campanha futura deve preservar conversão, trabalhar o volume que realmente existe e mostrar a cada participante um caminho de prêmio possível.

## 13. Proposta inicial para uma campanha Figital menor e mensurável

Esta seção é recomendação nova para discussão, não regra aprovada e não substitui o desenho dos gerentes de relacionamento.

### Meta de referência do canal

- **APFIN conciliado de referência L3M: 90,68%.** Uma primeira meta para simulação é **93%**, avanço de 2,32 p.p.; 94% deve aparecer como cenário mais exigente, não automaticamente como piso obrigatório.
- **Elegível novembro, cenário de volume recente:** R$ 3.938.146, mediana agosto–outubro. Dezembro: R$ 2.545.015, aplicando a razão de elegível LP orçado dezembro/novembro, aproximadamente 64,6%.
- **Protegido correspondente à taxa de 93%:** aproximadamente R$ 3,662 milhões em novembro e R$ 2,367 milhões em dezembro. Esses são resultados esperados no cenário, não orçamento oficial nem previsão garantida.
- Se for necessário um gatilho flat inicial, testar a mediana protegida conciliada recente de **R$ 3.540.887** em novembro e aproximadamente **R$ 2,288 milhões** em dezembro. Atingir esse piso sozinho não conquista a meta APFIN; validar volume, oferta e data de corte antes de fixá-lo.

O orçado LP é maior: elegível de R$ 5,891 milhões/R$ 3,807 milhões e protegido de R$ 5,516 milhões/R$ 3,561 milhões em novembro/dezembro, com APFIN implícito de 93,64%/93,53%. Exigir esse volume integral na equipe depende de confirmar cobertura e capacidade de originação. Não misturar o cenário de volume recente com 100% do volume orçado.

### Desafio individual a testar

1. Usar o APFIN ponderado individual L3M conciliado e uma previsão de elegível por atendente; ajustar por produto, dias de trabalho, entrada e transferência de carteira.
2. Como ponto inicial, testar +2 p.p. para bases abaixo de 90%; +1 p.p. entre 90% e 95%; para quem já está em 95% ou mais, manutenção de qualidade/conversão e crescimento monetário viável. Não obrigar uma taxa acima de 100%.
3. Validar o piso de protegido pela oportunidade monetária individual; não impor o mesmo valor a quem tem volumes muito distintos ou exigir apenas APFIN sobre uma base mínima.
4. Pagar por resultado individual adicional validado, com valor e regra conhecidos antes do início; sem sorteio. Evitar transformar um orçamento insuficiente em promessa de R$ 500 para todos.
5. Reexecutar as regras em meses anteriores e verificar proporção habilitada, distribuição por equipe e estabilidade. Não há percentual universal de sucesso: calibrar o avanço desejado e o orçamento, sem desenhar uma meta impossível para caber no custo.

**Atenção:** muitos atendentes têm taxas próximas de 100%. Uma campanha baseada só em percentual pode remunerar manutenção que já aconteceria. O desafio monetário deve considerar o elegível disponível e a margem incremental, preservando o reconhecimento de quem já converte bem.

### Onde há oportunidade observável na ponta

No outubro disponível, os maiores saldos de elegível não protegido incluem Aline (aprox. R$ 66,2 mil; APFIN 75,3%), Ariane (R$ 58,7 mil; 70,8%), Estefani (R$ 40,9 mil; 76,2%) e Miguel (R$ 28,4 mil; 81,3%). São prioridades de diagnóstico por produto/operação, não metas automáticas nem afirmação de que todo o saldo poderia ser assegurado.

Esses recortes tendem a oferecer mais ganho marginal de conversão que elevar alguém de 99% para 100%, mas é necessário validar elegibilidade efetiva, qualidade e condições comerciais antes de cobrar captura do saldo.

## 14. Como mensurar retorno sem confundir produção com benefício

### Fórmulas do cenário

```text
APFIN_base = protegido_base / elegível_base
Protegido_incremental_de_conversão = elegível_do_cenário × (APFIN_meta - APFIN_base)
Margem_unitária_proxy = margem_líquida_orçada / protegido_orçado
Margem_incremental_proxy = protegido_incremental × margem_unitária_proxy
Custo_campanha = prêmios + taxa_voucher + custos adicionais não embutidos
ROI = (margem_incremental - custo_campanha) / custo_campanha
Ponto_de_equilíbrio_protegido = custo_campanha / margem_unitária
```

Usar margem após custos variáveis, repasses e persistência compatíveis; a margem média orçada é apenas proxy da margem marginal. Nunca usar todo o capital protegido ou toda a comissão normal como “retorno da campanha”.

### Sensibilidade Figital: volume recente e sazonalidade de dezembro

Margem unitária LP orçada: aproximadamente 6,14% em novembro e 6,13% em dezembro por real protegido. Os cenários abaixo mantêm o mix/margem do orçamento e usam R$ 6,483 milhões elegíveis no bimestre. Não são previsão de adesão ou efeito causal.

| Cenário de APFIN | Incremento protegido | Margem adicional estimada |
|---|---:|---:|
| +1 p.p. sobre a base de 90,68% | R$ 64.832 | R$ 3.980 |
| +2 p.p. | R$ 129.663 | R$ 7.959 |
| 93% | R$ 150.626 | R$ 9.246 |
| 94% | R$ 215.458 | R$ 13.226 |

**R$ 500 por atendente, 32 premiados:** R$ 16.000 nominais; com taxa de 10% adicional, **R$ 17.600**. No cenário de 93%, o saldo seria de aproximadamente **–R$ 8.354**, ROI **–47,5%**. Até 94% o custo máximo ainda não se paga nesse cenário. Isso não significa que R$ 500 seja inviável em qualquer desenho; depende da quantidade de habilitados, volume, avanço, margem e custo total.

Com alvo de ROI de 50% — uma escolha gerencial ilustrativa — e margem incremental de R$ 9.246, o custo total da campanha deveria ser no máximo **R$ 6.164**. Caberiam até **11 vouchers de R$ 500 com taxa de 10%**, desde que não existam outros custos. Esse limite financeiro não é recomendação de prometer 11 prêmios por ordem de chegada ou de elevar artificialmente a meta para apenas 11 pessoas ganharem.

### Deslocar verba do gerente para a ponta

R$ 2.500 de verba liberada compram cinco prêmios de R$ 500 **sem taxa**; se a verba já tiver de cobrir a taxa de 10%, compram quatro prêmios completos de R$ 550, sobrando R$ 300. Verificar se os R$ 2.500 informados são nominais ou custo total.

Minha recomendação é testar uma campanha concentrada na ponta com prêmio percebido como relevante, escopo explícito e resultado incremental financiável; reduzir prêmio da liderança pode ajudar, mas não resolve sozinho a conta de premiar 32 pessoas. Se a intenção for premiar toda a ponta com valor relevante, será necessário aumentar volume/margem incremental, ampliar verba ou aceitar parte do gasto como investimento comercial sem ROI imediato demonstrado.

Um fundo correspondente a uma fração da margem incremental pode proteger o retorno, mas torna o valor individual incerto. Um prêmio fixo é mais claro, porém exige reservar o custo de todos os que podem se habilitar. Essa escolha deve ser assumida antes do lançamento, não resolvida depois do resultado.

## 15. Como avaliar a próxima campanha com mais rigor

**Antes:** congelar elegibilidade, matrícula/usuário, equipe, oferta vigente, baseline por produto/operação e período de corte. Definir prêmio, orçamento, tratamento de cancelamentos, dias ativos, transferências, sem elegível e prazo de contestação.

**Durante:** painel semanal por atendente e supervisor com elegível, protegido, APFIN ponderado, avanço versus própria base, distância para cada gatilho, margem incremental estimada e custo comprometido. Registrar comunicação, participação, oferta de seguro e razões de recusa para medir adesão, não apenas venda.

**Depois:** medir pelo menos cinco saídas: participantes alcançados/ativos; proporção que cumpriu cada regra e todas; APFIN ajustado pelo mix; protegido e margem adicionais; custo total e ROI. Medir também persistência/cancelamentos no prazo compatível com o produto.

Para isolar causalidade, preferir piloto com grupos comparáveis e introdução escalonada, ou grupo de comparação previamente definido; comparar evolução e controlar mix, volume e eventos comerciais. Se todos receberem a campanha ao mesmo tempo, o antes/depois será informativo, mas não prova do efeito do prêmio.

Decompor variação de protegido em efeito de elegível disponível e efeito de conversão, usando os mesmos produtos/recortes; se ambos variarem, explicitar interação ou usar decomposição simétrica. Isso evita cobrar do atendente uma contração de crédito fora de seu controle.

## 16. Lacunas que impedem o fechamento

1. Outubro fechado e data de corte/competência em ambas as fontes; eventual produção de estorno e reclassificações.
2. Definição documental de capital protegido versus liberado seguro RV e razão das diferenças entre fontes.
3. Qual “meta orçada” vale na campanha: crédito total, seguro, orçamento comercial, outro indicador? O filtro é individual, por equipe, mensal ou bimestral?
4. Regulamento com fronteiras exatas, desempates, acumulação, sorteios e relação de habilitados/premiados/pagamentos.
5. Custo realizado completo: viagens/vouchers, sorteios, eletrônicos, taxas e despesas; valor do gerente e das demais hierarquias.
6. Matrícula e histórico de equipe por atendente; validação dos nomes abreviados e das três associações de supervisão. Confirmar se há público de superintendência além de LP-C.
7. Cobertura do orçamento LP pela equipe analisada; lojas de Belmair e outros canais não devem ser incluídos sem definição. Escopos primários anteriores excluíam REG-H e DIG.
8. Projeção de originação e elegível individual, agenda de reabertura CLT e mudanças no SIAPE; não presumir volume integral orçado.
9. De-para histórico completo de gerentes e plano de parceiros/convênios da expansão, especialmente Fabiano.
10. Margem marginal e custos variáveis realizados por produto, cancelamentos e persistência; autorização de orçamento e mecânica definitiva de pagamento.

## 17. Perguntas para revisão crítica pela outra IA

- As metas equilibram desafio e atingibilidade quando se olha carteira, mix e volume, ou apenas aumentam percentuais por conveniência?
- Qual método deve pesar mais em cada carteira: histórico comparável, rateio do orçamento ou pares? Quais pesos e validações justificam a escolha?
- O piso monetário cria APFIN implícito superior à meta anunciada em cenários realistas de volume?
- Onde o prêmio vai remunerar conversão nova, onde preserva uma taxa já alta e onde depende de nova originação?
- Na expansão, faz sentido exigir o mesmo tipo de meta dos veteranos antes de existir oferta elegível e base suficiente?
- No Figital, o filtro de 85% melhora retorno ou exclui bom desempenho em seguro por fatores de crédito fora do controle individual?
- Como financiar prêmios percebidos como relevantes sem sorteio, sem ranking excessivamente restrito e sem prometer uma margem incremental inexistente?
- Quais resultados da campanha anterior são sinais úteis, quais são contaminados por corte/mix e quais ainda não podem ser medidos?

**Orientação final para continuidade:** preservar as fontes, separar fatos de hipóteses, não promover minutas a decisões aprovadas e não confundir uma simulação rentável com evidência de retorno causal. A recomendação deve poder ser explicada a cada participante em uma linha: sua meta, seu gatilho, seu prêmio, como apurar e por que o desafio é alcançável com a carteira disponível.

### Memória metodológica da nova análise Figital

A emissão foi agregada pelos três códigos do de-para Figital, mês e usuário nominal. Linhas incompatíveis foram segregadas dos dois lados da razão. O cruzamento nominal usa caixa/acentos normalizados e três equivalências: nome truncado de Ana Carolina, Kathia sem sobrenome final e Viviane Macedo/Viviane Cristina Macedo. Viviane exige confirmação explícita. As equipes de supervisão de setembro/outubro foram estimadas com os códigos documentados de maio–agosto. O funil aplica filtros independentes e depois conjuntos; no bimestre soma elegível, protegido, metas e realizado antes de dividir. Ausência de denominador não foi transformada em taxa zero. A análise não somou níveis hierárquicos e não transportou projeção da RV para a emissão.