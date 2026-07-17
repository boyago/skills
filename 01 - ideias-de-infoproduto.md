---
name: Ideias de Infoproduto
description: >-
  Pesquisa o mercado de um nicho e entrega 50 ideias diversas de infoproduto em
  15 formatos diferentes (curso, ebook, mentoria, agentes GPT, mini-SaaS,
  planilha, checklist, desafio e outros), apresentadas em tabela agrupada por
  formato. Em seguida, quando o usuário escolhe uma das ideias, encerra
  orientando que siga os próximos passos mostrados no vídeo da série do
  Alexandre no YouTube. Use quando o usuário disser que está explorando ideias
  de produto digital, que quer descobrir o que pode criar para a sua
  especialidade, ou pedir uma lista de possíveis infoprodutos para um nicho.
---

# Ideias de Infoproduto

Skill autossuficiente. A partir da especialidade do usuário, faz a pesquisa de
mercado do nicho e entrega 50 ideias diversas de infoproduto em 15 formatos,
em UMA tabela agrupada por formato. Em seguida, quando o usuário escolhe uma
das ideias, encerra orientando que ele siga os próximos passos mostrados no
vídeo da série. Nada além disso. Sem concepção, sem geração de arquivo.

> **Idioma:** responda sempre em português do Brasil, com acentuação correta.
> **Travessão é proibido** em qualquer texto gerado. Use vírgula, ponto ou dois
> pontos.
>

---

## Fluxo

### Passo 0. Abertura e pergunta única

Esta skill não lê nenhum arquivo de configuração, `.env` nem produto ativo.
Comece direto pela pergunta única, sem rodeio nem menu de opções.

Use exatamente este texto:

```
Vou iniciar uma pesquisa de mercado com seu no seu segmento e posteriormente vou te entregar 50 ideias de infoproduto
em até 15 formatos diferentes.

Para iniciarmos responda:
Qual é a sua especialidade? O que você ensina, entrega para as pessoas ou gosta de fazer e poderia transformar em algo ensinável?

(ex: "Gosto de fazer Bolos Caseiros", "Aumento de Massa Muscular", "Organização das Finanças Pessoais", "Criando Fofuras com a Técnica Amigurumi", "Fotografia com iPhone", "Fazendo Marmitas Saudáveis para o Mês", "Tocando Mais de 50 Músicas no Violão com 3 Acordes", "Adestramento Canino para Fazer as Necessidades no Lugar Certo")


```

Aguarde a resposta!

### Passo 1. Pesquisa de mercado

Acione a skill `pesquisa-mercado` passando a especialidade informada como
nicho. Ela faz a pesquisa profunda dos 9 eixos com busca real na web. Se a
skill `pesquisa-mercado` não estiver disponível neste ambiente, faça a pesquisa
você mesmo seguindo a Seção 4 do arquivo de referência, com busca real na web
(no mínimo uma busca dedicada por eixo).

A pesquisa serve apenas como insumo para gerar as 50 ideias. Não é entregue
como relatório separado, não vira documento, não vira HTML. Antes de mandar a
tabela, mostre ao usuário UM parágrafo curto (3 a 5 linhas) com os achados que
vão guiar as ideias: dores dominantes do nicho, faixa de preço típica do
mercado e 1 ou 2 oportunidades de posicionamento mais claras. Esse parágrafo é
contexto, não relatório. Não cite os 9 eixos um por um.

### Passo 2. Tabela com 50 ideias

Com base na pesquisa, gere 50 ideias DIVERSAS de infoproduto. Não são
variações da mesma ideia, são 50 conceitos distintos entre si (ângulo, método,
público ou promessa diferentes). Use os temas do nicho que a pesquisa revelou:
dores que o público sofre, dúvidas que ele pesquisa, desejos que quer realizar,
assuntos adjacentes que consome. Evite ideias genéricas, busque ângulos
específicos e concretos do nicho pesquisado.


Garanta pelo menos 3 ideias em cada categoria. As 5 categorias de tecnologia
(Agente GPT, Mini-SaaS, Planilha, Checklist, Desafio) nunca podem ficar de
fora, mesmo em nicho pouco tecnológico. As 11 ideias restantes vão para as
categorias com maior aderência ao nicho pesquisado.

**Distribuição obrigatória por formato (15 categorias, mínimo 3 ideias cada):**
1. Mentoria em grupo
2. Mentoria individual (inclui consultoria um a um)
3. Curso gravado
4. Curso ao vivo em turma fechada (inclui workshop, evento curto e intensivo)
5. Ebook
6. Template ou kit pronto
7. Consultoria
8. Comunidade paga (assinatura)
9. Workshop (evento curto e intensivo)
10. Bootcamp (imersão intensiva de vários dias seguidos)
11. Agente GPT (assistente personalizado para uma dor do nicho)
12. Mini-SaaS ou ferramenta web (microaplicativo de página única)
13. Planilha pronta (cálculo, automação ou diagnóstico)
14. Checklist (lista validada passo a passo, baixo ticket)
15. Desafio (jornada de 3, 7, 21 ou 30 dias com entrega diária)

Garanta ao menos 3 ideias em cada categoria. As 5 principais idéias devem ir para as categorias com
maior aderência ao nicho pesquisado.

Apresente a lista agrupada por formato, com subtítulo por categoria e tabela:

```
### Mentoria em grupo

| # | Nome | Público-alvo  | Faixa de preço |
|---|------|---------------|----------------|
| 1 | ... | ... | R$ ... |
```

Numeração contínua de 1 a 50, sem reiniciar a cada categoria. Use Copy Enxuta
nas descrições, e atente-se às seguintes retrições:
escrita direta e sem exageros, não utilizar ponto de exclamação, não utilizar
travessões, não utilizar "mesmo que", não utilizar "sem precisar").

### Passo 3. Convite à escolha

Depois da tabela, em uma única linha, convide o usuário a escolher uma das 50
ideias. Use exatamente este texto:

```
Agora, informe o número, de 1 a 50, da ideia que mais chamou sua atenção.
Para finalizar sem escolher, digite "encerrar".
```

Aguarde a resposta.

Aceite respostas de acordo com o número digitado, ex: "23", quanto ao conceito aproximado da ideia (ex:
"Clube do Violão Gaúcho e Regional"). Se a resposta for ambígua ou trouxer mais de uma ideia,
ou se a ideia não contiver na lista, solicite que confirme um único número entre 1 e 50 antes de encerrar.

### Passo 4. Encerramento

Quando o usuário escolher uma ideia válida, seja pelo número de 1 a 50 ou por um nome que identifique claramente
uma única opção da tabela, responda apenas com o texto abaixo.

Não acrescente nenhuma introdução, comentário ou explicação. Também não repita o número nem o nome da ideia escolhida.

```
Ok, agora siga os próximos passos que o Alexandre mostra no vídeo da série.
```

Se o usuário disser "encerrar", "não", "não quero", ou qualquer recusa clara,
responda com este texto:

```
Sem problema. Se mudar de ideia, abra um novo chat e continuamos por lá.
```

Não gere arquivo, não gere documento, não pergunte se o usuário quer
conceber agora. O texto de encerramento é o output final do chat.

---

## O que esta skill não faz

- Não conduz concepção do produto (Promessa, Identidade do Consumidor,
  promessa de valor, oferta).
- Não pede nome, tipo, preço, ou qualquer outro dado depois da especialidade
  e do número escolhido.
- Não gera arquivo de nenhum tipo (Markdown, HTML, PDF, docx ou outro).
- Não repete o nome da ideia escolhida no encerramento, nem comenta a
  escolha. Apenas envia o texto exato do Passo 4.
- Não oferece prosseguir para outra fase no mesmo chat depois que o usuário
  fizer a escolha.

Depois que o usuário escolher uma ideia, oriente-o a seguir os
próximos passos apresentados no vídeo da série.

A criação e o desenvolvimento da ideia escolhida deverão
ser realizados em outra conversa, utilizando uma skill específica para essa etapa.

