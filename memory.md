---
name: daniella_profile
description: Perfil e contexto persistente de Daniella
metadata:
  type: user
  updated: 2026-05-16
---

# Perfil de Daniella

## Sobre você
<!-- Adicione aqui informações sobre você: nome completo, papel, experiência, conhecimentos principais, etc. -->
- **Nome**: Daniella
- **Descrição**: (a preencher)

## Preferências de trabalho
<!-- Como você prefere que Claude trabalhe com você? Detalhes técnicos, estilo de comunicação, etc. -->
- (a preencher)

## Projetos atuais
<!-- Contexto sobre o que você está trabalhando -->
- (a preencher)

## Conhecimentos e expertise
<!-- Áreas onde você é especialista ou está aprendendo -->
- (a preencher)

## Feedback e lições aprendidas
<!-- Coisas que funcionaram bem, things to avoid, padrões úteis -->
- (a preencher)

## Referências úteis
<!-- Links, documentação, recursos importantes -->
- (a preencher)

---

# Histórico de Chats

## Template para adicionar chats

```
### Chat: [Título/Assunto] | [Data]

**Data**: 2026-05-16  
**Duração**: ~XX minutos  
**Temas**: [tag1], [tag2], [tag3]  
**Resumo rápido**: Uma linha resumindo o propósito do chat

#### Conteúdo do Chat

[Cole aqui todo o conteúdo do chat do Claude Desktop]

#### Insights e Aprendizados

- Insight 1
- Insight 2
- Coisa pra lembrar

---
```

## Chats Adicionados

<!-- Adicione seus chats aqui usando o template acima -->

### Chat: Começar do Zero - Dashboard de Gestão de Projetos | 16-05-2026

**Data**: 2026-05-16  
**Duração**: ~12 minutos  
**Temas**: notion, dashboard, gestão de projetos, integração, automação  
**Resumo rápido**: Criou um database no Notion para gerenciar demandas da Dorinhos com dashboard em múltiplas views (tabela, board, calendário)

#### Conteúdo do Chat

**Daniella**: Fazer um dash de gestão de projetos conectando com o meu notion baseado nas demandas Dorinhos

**Claude**: Proposição de 3 etapas:
1. Configurar o Notion com database contendo: Nome, Status, Prioridade, Datas, Área, Observações
2. Conectar Notion ao Claude via integração
3. Montar dashboard em tempo real

Database criado com sucesso na página "Central de Projetos" com as seguintes propriedades:
- Nome do projeto (Title)
- Status (Select: Backlog / Em andamento / Pausado / Concluído)
- Prioridade (Select: Alta / Média / Baixa)
- Data de início (Date)
- Prazo (Date)
- Área (Select: TI / Fiscal / Estoque / Geral)
- Observações (Text)

Foram criadas 3 versões do dashboard:
1. **Widget inline** - Mostra dados em tempo real, mas some quando fecha a conversa
2. **Artefato HTML** - Fica salvo em "Seus artefatos", mas não sincroniza com Notion
3. **Página no Notion** - Dashboard com 4 views vinculadas ao database (tabela, board, calendário, prioridade alta)

#### Insights e Aprendizados

- **Notion é a fonte de verdade** - Todos os dados vivem lá permanentemente
- **Três tipos de dashboard**: Widget (temporal), Artefato (independente), Notion (integrado e real-time)
- **Database estruturado** facilita filtros e views automáticas
- **5 projetos iniciais** da Dorinhos já cadastrados para teste
- **Views recomendadas**: Tabela filtrada, Board Kanban, Calendário de prazos, Prioridade alta
- **Dica importante**: Usar Claude para visualizar/atualizar dashboard, mas Notion para adicionar dados reais
- **Sincronização**: Widget inline se atualiza ao pedir, Artefato não sincroniza, Notion é sempre real-time

---

### Chat: Avaliação de Exames da Tia Fátima | 12-15-05-2026

**Data**: 2026-05-12 até 2026-05-15  
**Duração**: ~5 dias de acompanhamento clínico  
**Temas**: saúde, AVC isquêmico, interpretação de laudos, tronco cerebral, medicações, sistema cardiovascular  
**Resumo rápido**: Análise detalhada de múltiplos exames da tia Fátima (74 anos) internada com AVC isquêmico no tronco cerebral após dor persistente no pescoço e pressão alta de 17

#### Conteúdo do Chat

**Histórico Clínico:**

Fátima (74 anos, F) internada em 10-11/05/2026 no Hospital São Bernardo com:
- Dor no pescoço que não passava com medicação
- Pressão arterial de 17
- Bradicardia sinusal (FC 46 bpm)
- Diagnóstico: AVC isquêmico no tronco cerebral (ponte - região esquerda)

**Exames Principais Realizados:**

1. **Tomografia de Crânio (10 e 11/05)**
   - Lacuna isquêmica no tronco cerebral (ponte) - lado esquerdo
   - Ateromatose carotídea intracraniana (placas de gordura nas artérias)
   - Atrofia cerebral compatível com idade
   - Segundo laudo (12/05) descreveu a lacuna como "antiga"
   - Microangiopatia supratentorial (lesões em substância branca)
   - Sela túrcica parcialmente vazia (achado anatômico, sem significado clínico)

2. **ECG (10 e 11/05)**
   - Bradicardia sinusal persistente (FC 46 bpm mesmo antes de medicações)
   - Alteração inespecífica de repolarização ventricular (dia 10, não confirmada dia 11)
   - Normalização completa no dia 15/05

3. **Hemograma (10 e 11/05)**
   - 10/05: Normal (56% neutrófilos, 35% linfócitos)
   - 11/05: Leucocitose com neutrofilia marcante (84% neutrófilos vs ref. máx 70%, linfócitos 9%)
   - Razão neutrofilia + linfopenia: efeito do Decadron (corticóide) ou infecção/estresse agudo
   - Dia 15: Melhorando (66% neutrófilos, 21% linfócitos)

4. **Enzimas Cardíacas e Coagulação**
   - Troponina I ultrassensível: 5,1 pg/mL (ref. < 47,8) ✅ Normal - descarta infarto
   - D-Dímero: 0,44 mg/L (ref. < 0,50) ✅ Normal - descarta tromboembolismo pulmonar
   - TAP/INR: 100% / 0,90 - coagulação normal
   - Creatinina: 0,97 mg/dL (10/05), 1,09 mg/dL (15/05) - estável
   - eGFR: 57,72 (10/05) → 51,26 (11/05) → estável em 15/05 - TFG reduzida, suspeita de DRC estágio G3a

5. **Exames Bioquímicos (22/04 - antes da internação) ⚠️ MUITO IMPORTANTE**
   - **Homocisteína elevada**: 18,8 umol/L (ref. até 13,9) 🚨 FATOR DE RISCO CRÍTICO - danifica vasos, favorece coágulos
   - **Gama GT elevada**: 91 U/L (ref. até 38) - sobrecarga hepática
   - **TGP**: 32 U/L em abril → explodiu para 155 U/L em 15/05 (mais de 3x o limite)
   - **Hemoglobina**: 16,6 g/dL (ref. até 16) - sangue mais espesso, aumenta risco vascular
   - **HOMA-IR (resistência à insulina)**: 5,48 (ref. até 3,40) - sem diabetes estabelecida, mas com resistência
   - **Uréia**: 55 mg/dL (ref. até 50) - já elevada antes da internação
   - **Cortisol**: 24,03 (ref. até 22,45) - discretamente elevado, estresse crônico
   - **Vitamina D**: 26 ng/mL - tecnicamente suficiente mas abaixo do ideal para idosos

6. **Angiotomografia (15/05)**
   - Sem estenose significativa nas artérias cerebrais ✅
   - Sem aneurisma, sem trombose venosa
   - Variação anatômica na artéria vertebral direita (hipoplasia - naturalmente menor)
   - Fluxo preservado em artérias carótidas e vertebral esquerda
   - Distensão das bainhas dos nervos ópticos (sugere hipertensão intracraniana)

7. **Ecocardiograma (15/05)**
   - Fração de ejeção: 68% ✅ Ótima
   - Relaxamento diastólico alterado (típico de idade/hipertensão)
   - Válvulas levemente espessadas (sem significado crítico)
   - Sem trombos
   - Alterações leves compatíveis com idade

**Medicações Utilizadas:**
- **Sustrate** (mononitrato de isossorbida) - vasodilatador, controla pressão
- **Versa** (verapamil) - controla pressão E frequência cardíaca (causa bradicardia)
- **Decadron** (dexametasona) - corticóide potente, reduz edema cerebral (efeito colateral: neutrofilia)
- **Dipirona** - analgésico
- **Citalor** (atorvastatina) - colesterol, estabiliza placas
- **Profenid** (cetoprofeno) - anti-inflamatório ⚠️ prejudicial para rim comprometido
- **Ringer Lactato** - soro para hidratação
- **Enoxaparina** (Clexane) - anticoagulante injetável (afina o sangue)
- **Flunarizina** - previne enxaqueca, vasodilatador cerebral
- **Meclin** (meclizina) - antivertiginoso
- **Jet** (dipirona + cafeína) - analgésico
- **Nivux** (naproxeno) - anti-inflamatório ⚠️ cuidado com rim
- **Ciclobenzaprina** - relaxante muscular

**Eventos Principais:**
- **10/05**: Internação com dor no pescoço e pressão 17
- **11/05**: Exames confirmam AVC, piora hemograma (efeito de medicação), função renal cai
- **12/05**: Segunda tomografia mostra lacuna como "antiga" (não é do evento atual?)
- **13/05**: Alta com orientação para seguimento com neurologista
- **15/05**: Volta ao hospital com dor no pescoço NOVA, faz novos exames, solicita ressonância

**Diagnóstico Diferencial e Questões em Aberto:**
- A lacuna é antiga mas a dor de pescoço voltou → Possível AVC novo que TC não mostra?
- Hipertensão intracraniana como causa da dor? (evidência: nervo óptico distendido)
- Dissecção de artéria vertebral foi descartada? (apresentação clínica era compatível)
- TGP explosiva em 15/05 → reação a qual medicação?

**Contexto Clínico Geral de Fátima:**
- Histórico cardiovascular GRAVE: já tem stents no coração (doença arterial coronariana prévia)
- Fumante por muitos anos desde jovem
- Doença vascular GENERALIZADA (coração + cérebro + rins)
- Fatores de risco acumulados: homocisteína alta, resistência à insulina, ateromatose, pressão descontrolada, tabagismo, colesterol alto (LDL 127 vs ideal <70 para quem tem stent)
- Função renal já comprometida antes da internação

#### Insights e Aprendizados

**Aprendizados Clínicos Importantes:**

- **AVC lacunar no tronco cerebral é delicado** - Região que controla equilíbrio, deglutição, frequência cardíaca. Pequenas lesões podem ter efeitos grandes.

- **TC vs RM** - TC é rápida e boa para hemorragia mas ruim para tronco cerebral. RM enxerga lesão isquêmica aguda com poucas horas. No caso de Fátima, a RM é CRÍTICA.

- **Homocisteína elevada é um fator de risco INDEPENDENTE e tratável** - Vitaminas B6, B12 e ácido fólico baixam. No caso de Fátima isso foi identificado em abril mas aparentemente não foi tratado.

- **Bradicardia neurológica vs medicamentosa** - Se ela tinha 46 bpm ANTES de tomar Versa, é neurológica (lesão do tronco afetando núcleo do vago). Somado ao Versa, fica crítico.

- **Anti-inflamatórios (AINE) prejudicam rim** - Profenid e Naproxeno são contraindicados em pacientes com eGFR reduzido. Suspeita: essas medicações podem estar causando a TGP explosiva e piora renal.

- **Dor no pescoço recorrente é alerta vermelho** - Não é normal voltar com o mesmo sintoma 2 dias após alta. Significa algo não foi resolvido ou é novo.

- **Hipertensão intracraniana é comum pós-AVC** - Distensão de nervo óptico sugere isso. Pode causar dor de pescoço persistente.

- **Planos de saúde relutam com RM** - Hapvida frequentemente nega. Solução: exigir que solicitude seja registrada no prontuário. Quando está registrado, plano assume responsabilidade legal.

- **Tabagismo é o grande vilão** - Décadas de cigarro dañam progressivamente todos os vasos. Stents no coração foram consequência. AVC foi consequência. Parar AGORA ainda faz diferença.

- **Função renal em queda é sinal de alerta** - eGFR caindo de 57 para 51 em 24h em paciente internado é anormal. Pode ser desidratação, medicação nefrotóxica, ou progressão de doença renal.

- **Doença vascular é sistêmica** - Se tem placa no coração, tem placa no cérebro, tem placa nas pernas. É a mesma doença em lugares diferentes.

- **LDL precisa estar <70 em paciente com stent** - Fátima estava em 127. Atorvastatina precisa ser otimizada.
