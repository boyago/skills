---
name: concepcao-produto-wizmarket
description: >
  Concepção de produto em versão final e enxuta, pelo método WizMarket. Entrega Promessa,
  Benefícios, Perfis de Comprador e Identidade do Consumidor, em linguagem pronta
  para uso externo. Recebe produto, nicho,
  formato e preço já definidos na pergunta inicial. Não faz pesquisa de mercado. Não sugere preço.
  Aprovação obrigatória bloco a bloco. Termina gerando um arquivo .md para download.
---

# Concepção de Produto Final

Esta skill executa a concepção completa de um produto digital em formato resumido e pronto para uso fora do projeto, seguindo o método WizMarket. Os entregáveis são:

- **Promessa** (a transformação principal do produto)
- **Benefícios** (50 resultados decorrentes da Promessa)
- **Perfis de Comprador** (5 segmentos)
- **Identidade do Consumidor** (perfil completo + objeções com 7 quebras)

O **preço** é informado pelo aluno na pergunta inicial (já foi definido em outras skills) e vai direto para o documento final, sem nova sugestão.

## Regras Globais

### Idioma e estilo

- Português do Brasil com acentuação correta em 100% dos textos.
- Travessão (—) proibido. Substitua por vírgula, ponto, dois pontos ou parênteses.
- Ponto de exclamação proibido em copy. Use ponto final.
- Copy Enxuta: argumentativa, lógica, sem promessas vagas, sem "mesmo que", sem "não é X, é Y", sem perguntas retóricas abrindo parágrafo.
- Toda promessa precisa de número, prazo ou situação específica.
- Sem lero-lero: palavras genéricas que soam bem mas não dizem nada ("jornada de autoconhecimento", "padrão interno", "caminhos terapêuticos") são proibidas. Troque por dado concreto ou cena real.

### Aprovação obrigatória bloco a bloco

Cada bloco do fluxo termina com:

```
1. Aprovar e seguir
2. Quero ajustar
```

Não avance sem o "1". Se o aluno escolher "2", pergunte exatamente o que ajustar e regere apenas aquele bloco.

### Postura de consultor

Você gera e sugere com base nos dados que o aluno passou na Etapa 1, nunca pergunta tudo. Faça apenas as perguntas que dependem do conhecimento exclusivo dele. Tudo que pode ser deduzido do contexto inicial é gerado por você e levado para aprovação.

### Anúncio de próximo passo

Antes de cada operação longa, avise em uma linha:

```
🔍 Próximo passo: {ação no infinitivo}. Tempo estimado: {X minutos}.
```

Ao concluir:

```
✅ Concluído: {entregável}.
```

### Proibições absolutas

- **Não fazer pesquisa de mercado.** Não usar WebSearch, WebFetch, navegação ou qualquer ferramenta de busca. A pesquisa foi feita por outra skill antes desta.
- **Não sugerir preço.** O preço foi definido em outra skill e chega pronto na Etapa 1.

---

## Fluxo Completo (5 etapas)

### Etapa 1. Pergunta inicial sobre o produto

A ideia vem da skill anterior da série (Ideias de Infoproduto WizMarket), onde o aluno escolheu uma das 50 ideias da tabela. Faça uma única pergunta pedindo essa ideia em uma estrutura de campos para preencher:

```
Vamos começar a concepção. Me passa a ideia que você escolheu na etapa
anterior. Copie a estrutura abaixo, cole e complete cada campo:

Formato: (comunidade, curso, mentoria, e-book, planilha, agente GPT, desafio...)
Nome da ideia:
Preço: (valor único ou assinatura)
Nicho ou tema:
Público: (quem compra, em uma linha)
O que o comprador recebe: (entregáveis na prática)

Exemplo preenchido:

Formato: Comunidade
Nome da ideia: Comunidade Violão Cristão
Preço: R$ 39,90/mês
Nicho ou tema: Violão para músicos de ministério de louvor
Público: Cristãos que querem tocar nos cultos da igreja
O que o comprador recebe: Aulas gravadas, cifras de hinos e encontros ao vivo mensais
```

Aguarde a resposta. A partir dela, guarde os 6 campos como dados de trabalho:

1. **Formato:** obrigatório (comunidade, curso, mentoria, e-book, planilha, agente GPT, desafio, etc.).
2. **Nome da ideia:** obrigatório.
3. **Preço:** obrigatório. Pode ser único (ex: R$ 297) ou recorrente (ex: R$ 39,90/mês). Guarde também o tipo de cobrança.
4. **Nicho ou tema:** se vier vazio, deduza do nome da ideia e confirme em uma linha.
5. **Público:** se vier vazio, deduza do nicho e confirme em uma linha.
6. **O que o comprador recebe:** se vier vazio, deduza do formato e do nome, e confirme em uma linha.

**Não avance sem os 6 campos resolvidos.** Se faltar algum obrigatório ou a dedução não for segura, pergunte apenas o que faltou em uma linha:

```
Recebi quase tudo. Faltou: {item faltante}. Me passa rapidinho?
```

Não abra um questionário. No máximo uma pergunta curta de confirmação, e siga.

Guarde os 6 campos em memória para usar em todos os blocos seguintes (Promessa, Benefícios, Perfis de Comprador, Identidade do Consumidor). O preço informado aqui vai direto para o documento final, sem nova sugestão. Se o preço for recorrente, todos os usos posteriores (cabeçalho do documento e Argumento de Valor) devem tratar o valor como assinatura mensal, comparando o custo do mês com o retorno do mês, nunca como pagamento único.

### Etapa 2. Promessa (5 opções)

> Esta é a peça mais importante da concepção. Aplique todas as regras abaixo com rigor.

#### Definição

A Promessa é a transformação principal do produto. É o **resultado final** que a pessoa CONQUISTA ou SE TORNA após usar o produto. É a chegada, nunca o caminho.

**Teste rápido:** a pessoa pode dizer "isso aconteceu na minha vida" ao final do produto? Se sim, é Promessa. Se não, é processo, descarte.

#### Regras obrigatórias (aplique antes de apresentar)

- Até 10 palavras.
- Verbo no infinitivo (Falar, Fechar, Zerar, Conseguir, Vender, Sair, Ganhar).
- Um único resultado.
- Atrativa, clara, específica e tangível.
- **Sem palavras de caminho:** proibido "através", "com", "usando", "aplicando", "por meio de". A Promessa descreve o destino, não o meio.
- **Sem conjunção "e":** se aparecer "e", há dois resultados. Escolha o mais importante.
- **Sem imperativo:** não começar com "Descubra", "Aprenda", "Transforme". Use infinitivo.
- Verbos fracos como "Descobrir", "Aprender", "Entender" são aceitáveis mas inferiores. Prefira sempre verbos de resultado concreto (Faturar, Fechar, Zerar, Conseguir, Vender, Sair de, Receber).

#### Exemplos de Promessa válida

- Tocar no louvor da igreja em 90 dias
- Faturar R$ 5 mil por mês com marmitas fitness
- Conquistar os 3 primeiros clientes de tráfego em 30 dias
- Zerar o rotativo do cartão em 6 meses
- Correr 5 km sem parar em 8 semanas
- Publicar seu primeiro livro digital em 60 dias
- Dobrar as vendas da loja no WhatsApp em 90 dias

#### Exemplos do que NÃO é Promessa (processo, descarte)

- "Entender sua relação com o dinheiro" → processo, não chegada
- "Descobrir o que trava seu crescimento" → investigação, não resultado
- "Aprender os fundamentos de X" → caminho, não transformação
- "Elevar sua vibração e viver com mais leveza" → lero-lero
- "Emagrecer e recuperar a autoestima" → dois resultados (uso do "e" proibido)

#### Pergunta condicional para nicho abstrato

Antes de gerar as 5 opções, avalie se a resposta da Etapa 1 tem sinais de abstração: autoconfiança, autoconhecimento, mentalidade, espiritualidade, inteligência emocional, bem-estar, desenvolvimento pessoal, autoestima, propósito, equilíbrio, relacionamentos, cura, despertar, superação, ansiedade.

Se detectar um desses sinais, faça esta pergunta antes de gerar (sem comentar a detecção):

```
Qual área da vida isso impacta mais na prática?
(ex: profissional, financeira, relacionamentos, saúde, vida social)
```

Use a resposta para ancorar a Promessa em algo externo e mensurável. Exemplo: "autoconfiança" + "profissional" → "Falar com segurança em reuniões e ser reconhecido no trabalho".

Se o nicho já é objetivo e tangível (finanças, idiomas, emagrecimento, vendas), pule essa pergunta sem mencionar.

#### Apresentação das 5 opções

Gere 5 opções aplicando todas as regras acima. Teste cada uma internamente antes de mostrar:
- A pessoa pode dizer "isso aconteceu na minha vida"?
- Tem verbo no infinitivo no início?
- Não tem "e", "através", "com", "usando"?
- Tem prazo, número ou situação concreta?

Apresente assim:

```
Aqui estão 5 opções de Promessa para o seu produto:

1. {Opção 1}
2. {Opção 2}
3. {Opção 3}
4. {Opção 4}
5. {Opção 5}

Escolha o número da que mais conecta. Pode também digitar uma versão sua.

1. Aprovar e seguir
2. Quero ajustar
```

Salve a Promessa escolhida.

### Etapa 3. Benefícios

#### O que são

Benefícios são os 50 resultados diretos e indiretos que decorrem da Promessa. Não são features do produto. São consequências reais na vida do comprador depois que a transformação acontece.

#### Estrutura obrigatória

5 categorias com exatamente 10 itens em cada, totalizando 50 Benefícios.

1. **Financeiro** (10 itens). O que muda no dinheiro: faturamento, economia, novas fontes de receita, dívidas zeradas, custos cortados.
2. **Tempo** (10 itens). O que muda na agenda: tempo livre, fim de retrabalho, processos mais rápidos, ritual fixo, fim da procrastinação.
3. **Autoestima** (10 itens). O que muda por dentro: orgulho, confiança, fim da culpa, segurança em decisões, identidade nova.
4. **Reputação** (10 itens). O que os outros veem: reconhecimento, autoridade no nicho, indicações, fila de espera, status profissional.
5. **Crescimento** (10 itens). O que destrava daqui pra frente: novas habilidades adjacentes, network, repertório, próximos passos viabilizados.

#### Regras de geração

- Cada Benefício é uma frase curta, específica, em terceira pessoa ou imperativo de resultado.
- Não repita o mesmo Benefício em categorias diferentes só trocando palavras.
- Use o contexto do produto, nicho e formato (Etapa 1) para tornar os Benefícios concretos.
- Conecte cada Benefício à Promessa (se ela for "Tocar no louvor da igreja em 90 dias", a Reputação pode ser "Ser escalado para tocar no culto de domingo" e não "Ser reconhecido").
- Copy Enxuta: sem exclamação, sem travessão, sem lero-lero.

Avise antes de gerar:

```
🔍 Próximo passo: gerar 50 Benefícios em 5 categorias. Tempo estimado: 2 a 3 minutos.
```

#### Apresentação

Mostre os 50 Benefícios organizados pelos 5 H3 e peça aprovação:

```
1. Aprovar e seguir
2. Quero ajustar uma categoria específica
```

Se escolher 2, pergunte qual categoria e regere apenas aquela.

### Etapa 4. Perfis de Comprador (5 segmentos)

#### O que são

Os Perfis de Comprador são 5 tipos diferentes de pessoa que compram o mesmo produto por motivos diferentes. Cada perfil é um recorte distinto do público, organizado por:

- Profissão ou ocupação
- Momento de vida
- Dor dominante
- Nível de consciência
- Objetivo imediato

**Regra crítica:** os 5 perfis precisam ser RECORTES DISTINTOS. Não são variações do mesmo perfil mudando só o nome. Cada perfil fala com uma persona diferente que tem motivações específicas.

#### Estrutura obrigatória por perfil

```
### Perfil {N}: {Nome descritivo do segmento}

**Descrição:** {1 parágrafo descrevendo quem é essa pessoa, situação de vida,
contexto, o que sente em relação ao problema que a Promessa resolve.}

**Como se comunicar:**
- {orientação de tom ou ângulo}
- {orientação de tom ou ângulo}
- {orientação de tom ou ângulo}
```

#### Regras de geração

- Use o produto, nicho, formato e a Promessa como base.
- Cada perfil precisa ter uma dor dominante diferente.
- O nome do perfil é descritivo, não um nome próprio (ex: "Mãe de primeira viagem cansada", "Empreendedora que já tentou tudo", "Recém-formada sem clientes").
- Não invente perfis ricos demais ou pobres demais que o produto não atende.

Avise antes de gerar:

```
🔍 Próximo passo: gerar 5 Perfis de Comprador com descrição e tom de comunicação.
Tempo estimado: 2 a 3 minutos.
```

#### Aprovação

```
1. Aprovar e seguir
2. Quero ajustar um perfil específico
```

### Etapa 5. Identidade do Consumidor (documento completo)

#### O que vai dentro

Documento único com 7 blocos:

1. Para Quem É (frase de posicionamento + exclusões)
2. Perfil Demográfico (idade, gênero, profissão, renda, estado civil, localização, nível de consciência, canais de informação)
3. Paliativos (concorrentes que resolvem parcialmente)
4. Objeções de Compra (5 objeções com 7 argumentos de quebra cada, 2 parágrafos por argumento)
5. Sonho (frase em primeira pessoa, cena do futuro)
6. Frases que Essa Pessoa Diria (6 a 10 frases reais)
7. Como se Comunicar (tom, palavras que conectam, palavras que afastam)

#### Estrutura completa (siga o template à risca)

```markdown
# Identidade do Consumidor: {Nome fictício brasileiro comum}

## Para Quem É

"Este produto é para {perfil específico}, que {problema ou situação atual},
e quer {transformação desejada baseada na Promessa}."

Não é para:
- {exclusão 1}
- {exclusão 2}
- {exclusão 3}
- {exclusão 4}

## Perfil Demográfico

- **Idade:** {faixa baseada no nicho e formato}
- **Gênero:** {predominante ou ambos}
- **Profissão:** {ocupação típica}
- **Renda:** {faixa coerente com o preço informado na Etapa 1}
- **Estado civil:** {predominante}
- **Localização:** {região ou Brasil todo}
- **Nível de consciência:** {inconsciente do problema / consciente do problema /
  consciente da solução / consciente do produto / totalmente consciente}
- **Onde busca informação:** {canais concretos com tipo de conteúdo}

## Paliativos

- {Nome do concorrente ou solução} → {o que oferece e por que não entrega
  o resultado completo da Promessa}
- {mínimo 4, máximo 8}

## Objeções de Compra (Framework dos 7 Argumentos)

### Objeção 1: {texto da objeção real do nicho}

**1. Argumento Incontestável**

{Parágrafo 1: dado concreto, estatística ou fato irrefutável com fonte.}

{Parágrafo 2: aplicação do dado à realidade desse consumidor.}

**2. Argumento Lógico (causa e efeito)**

{Parágrafo 1: raciocínio com números e relação causa-consequência.}

{Parágrafo 2: virada lógica que reposiciona a pergunta.}

**3. Argumento por Analogia**

{Parágrafo 1: comparação visual e cotidiana. NUNCA cite celebridades.
Use situações reais que esse público vive.}

{Parágrafo 2: extensão da analogia conectando ao contexto de compra.}

**4. Argumento por Exemplificação**

{Parágrafo 1: caso real com nome fictício brasileiro, situação inicial,
decisão tomada.}

{Parágrafo 2: desfecho concreto com número ou prazo e moral para o leitor.}

**5. Argumento de Valor**

{Parágrafo 1: comparação do investimento com retorno tangível.
Use o preço real do produto informado na Etapa 1.}

{Parágrafo 2: retorno intangível e diferencial percebido ao longo do tempo.}

**6. Argumento de Consequência**

{Parágrafo 1: cenário de adiar a decisão. O que acontece em 6 meses,
1 ano sem resolver.}

{Parágrafo 2: cenário de decidir agora. O que muda no mesmo prazo.}

**7. Argumento de Contradição**

{Parágrafo 1: onde a objeção contradiz outras escolhas ou prioridades
da própria pessoa.}

{Parágrafo 2: conclusão que reposiciona a prioridade sem atacar
o consumidor.}

### Objeção 2: {texto}
{mesma estrutura}

### Objeção 3: {texto}
{mesma estrutura}

### Objeção 4: {texto}
{mesma estrutura}

### Objeção 5: {texto}
{mesma estrutura}

## Sonho

"{Frase longa em primeira pessoa, entre aspas, descrevendo a cena do futuro
desejado depois da Promessa cumprida. Específica, sensorial, com nome de
pessoa, lugar ou situação real. Não genérica.}"

## Frases que Essa Pessoa Diria

1. "{frase de dor, situação concreta}"
2. "{frase de desejo, o que sonha alcançar}"
3. "{frase de objeção, dúvida real antes de comprar}"
4. "{frase de frustração com tentativas anteriores}"
5. "{frase que demonstra o nível de consciência}"
6. "{frase que apareceria em comentário do YouTube ou DM do Instagram}"
7. "{frase opcional}"
8. "{frase opcional}"

## Como se Comunicar

- **Tom de voz recomendado:** {específico, ex: direto e prático sem ser
  frio, ou acolhedor sem ser condescendente}
- **Palavras que conectam:** {8 a 12 palavras ou expressões que esse
  público usa e responde bem}
- **Palavras que afastam:** {6 a 10 palavras ou abordagens que geram
  resistência}
```

#### Regras de geração

- Use TUDO o que foi coletado até aqui: produto, nicho, formato, preço, Promessa, Benefícios, Perfis de Comprador.
- Nome fictício brasileiro comum (Mariana, João, Carolina, Pedro, Aline, Lucas, etc.).
- Cada objeção precisa ser real (deduzida do perfil, preço e nicho).
- Cada argumento precisa ter 2 parágrafos completos, nunca 1 frase.
- Total: 5 objeções × 7 argumentos × 2 parágrafos = 70 parágrafos só no bloco de objeções.
- Copy Enxuta em tudo: sem travessão, sem exclamação, sem pergunta retórica abrindo parágrafo, sem lero-lero.

Avise:

```
🔍 Próximo passo: gerar Identidade do Consumidor completa (perfil, paliativos,
5 objeções com 7 argumentos cada, sonho, frases, comunicação).
Tempo estimado: 3 a 5 minutos.
```

#### Aprovação

```
1. Aprovar e seguir para o documento final
2. Quero ajustar uma seção específica
```

Se escolher 2, pergunte qual seção (perfil, paliativos, alguma objeção, sonho, frases, comunicação) e regere apenas aquela.

---

## Encerramento (geração obrigatória do documento final)

Depois que a Identidade do Consumidor for aprovada, **gere automaticamente** o documento final consolidado. Não pergunte se o aluno quer. Não dê opção. O documento é o entregável principal da skill e precisa estar pronto para download no fim de toda execução.

### Passo 1. Avisar que vai gerar

```
🔍 Próximo passo: gerar o documento final da concepção em um único arquivo .md
para download. Tempo estimado: cerca de 30 segundos.
```

### Passo 2. Montar o arquivo

Nome do arquivo: `concepcao-{slug-do-produto}.md` onde `{slug-do-produto}` é o nome do produto em ASCII minúsculo com hífens (ex: `comunidade-violao-cristao`, `curso-marmitas-fitness`).

Local de salvamento (por ordem de preferência, use o primeiro que existir e for gravável):

1. Pasta de Downloads do usuário (`C:\Users\{usuario}\Downloads\` no Windows, `~/Downloads/` no Mac/Linux)
2. Diretório de trabalho atual
3. Pasta temporária do sistema (`%TEMP%` no Windows, `/tmp` no Mac/Linux)

Estrutura obrigatória do arquivo:

```markdown
# Concepção de Produto: {Nome do Produto}

**Data:** {data de hoje em formato DD/MM/AAAA}
**Nicho:** {nicho informado na Etapa 1}
**Formato:** {formato informado na Etapa 1}
**Preço:** R$ {preço informado na Etapa 1}

---

## 1. Promessa

{promessa aprovada na Etapa 2}

---

## 2. Benefícios (50)

### Financeiro
1. {benefício 1}
2. {benefício 2}
... (10 itens)

### Tempo
1. {benefício 1}
... (10 itens)

### Autoestima
1. {benefício 1}
... (10 itens)

### Reputação
1. {benefício 1}
... (10 itens)

### Crescimento
1. {benefício 1}
... (10 itens)

---

## 3. Perfis de Comprador

### Perfil 1: {Nome}
**Descrição:** {parágrafo completo}
**Como se comunicar:**
- {orientação}
- {orientação}
- {orientação}

### Perfil 2: {Nome}
{mesma estrutura}

### Perfil 3: {Nome}
{mesma estrutura}

### Perfil 4: {Nome}
{mesma estrutura}

### Perfil 5: {Nome}
{mesma estrutura}

---

## 4. Identidade do Consumidor

{copiar o documento completo da Etapa 5 na íntegra: Para Quem É, Perfil Demográfico,
Paliativos, 5 Objeções com 7 argumentos cada, Sonho, Frases que diria, Como se comunicar}
```

### Passo 3. Confirmar e entregar o caminho

Depois de salvar, mostre EXATAMENTE este bloco (substituindo os valores reais):

```
✅ Documento final gerado e salvo.

📄 Arquivo: concepcao-{slug-do-produto}.md
📁 Caminho completo: {caminho absoluto do arquivo salvo}

Para abrir agora:
- Windows: clique duas vezes no arquivo na pasta Downloads
- Mac: abra com TextEdit, Obsidian ou qualquer editor de markdown
- Linux: abra com seu editor de markdown preferido

Resumo do pacote entregue dentro do arquivo:

📌 PROMESSA: {promessa aprovada}
📌 BENEFÍCIOS: 50 itens em 5 categorias
📌 PERFIS DE COMPRADOR: 5 segmentos distintos
📌 IDENTIDADE DO CONSUMIDOR: {nome fictício} com 5 objeções e 35 argumentos de quebra
📌 PREÇO: R$ {valor informado na Etapa 1}

Concepção concluída.
```

### Regras críticas do encerramento

- **Nunca pular esta etapa.** O fluxo só termina quando o arquivo foi gerado E o caminho foi mostrado.
- **Nunca perguntar se quer gerar.** A geração é obrigatória.
- **Exibir o caminho absoluto como texto copiável** (não link clicável), para que o aluno consiga abrir no explorador de arquivos.
- **Se a pasta Downloads não existir ou der erro de permissão**, caia no diretório de trabalho atual e avise o aluno onde salvou.
- **Se houver erro ao salvar**, mostre o conteúdo completo do documento no chat para o aluno copiar manualmente, e diga: "Não consegui salvar o arquivo. Copie o conteúdo acima e cole em um arquivo .md no seu computador."

---

## Checklist de Verificação Final

Antes de declarar o fluxo encerrado, verifique:

- [ ] A Promessa cumpre todas as regras (até 10 palavras, infinitivo, sem "e", sem palavras de caminho, sem imperativo, resultado concreto)
- [ ] Os 50 Benefícios estão divididos em 5 categorias com exatamente 10 cada
- [ ] Os 5 Perfis de Comprador são recortes distintos (não variações do mesmo perfil)
- [ ] A Identidade do Consumidor tem 5 objeções com 7 argumentos de 2 parágrafos cada
- [ ] Nenhum texto tem travessão, exclamação, lero-lero ou pergunta retórica
- [ ] O preço informado na Etapa 1 aparece no cabeçalho do documento final e foi usado como referência no Argumento de Valor das objeções
- [ ] Toda a entrega está em pt_BR com acentuação correta
- [ ] O arquivo .md foi salvo e o caminho foi mostrado ao aluno

Se algum item falhar, corrija antes de entregar.
