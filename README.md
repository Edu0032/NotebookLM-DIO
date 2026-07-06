# Caderno Temático no NotebookLM: Diagnóstico e Evolução do Arremesso no Basquete

## Sumário

1. Contexto do projeto  
2. Objetivos de estudo  
3. Questão norteadora  
4. Fontes selecionadas  
5. Como o caderno foi organizado no NotebookLM  
6. Engenharia de prompts e registros de teste  
7. Matriz 5D do Arremesso  
8. Sistema de avaliação por descrição do usuário  
9. Miniguia de estudo  
10. Glossário  
11. Prompts reutilizáveis  
12. Plano de treino técnico  
13. Critérios de evolução  

---

## 1. Contexto do Projeto

Este repositório documenta a criação de um caderno temático no NotebookLM sobre o tema **como fazer um arremesso no basquete**.

O objetivo do projeto não foi criar apenas um resumo sobre fundamentos do arremesso. A proposta foi desenvolver um material de estudo capaz de funcionar como um **sistema de análise técnica**, isto é, um guia que consiga interpretar a descrição de um jogador, identificar possíveis falhas no arremesso e sugerir correções práticas.

A escolha do tema surgiu porque o arremesso é um dos fundamentos mais importantes do basquete, mas também um dos mais mal compreendidos. Muitos jogadores recebem orientações vagas, como “alinhe o cotovelo”, “use mais as pernas” ou “termine com o punho quebrado”, mas nem sempre entendem quando, por que e como aplicar essas correções.

Neste projeto, a Inteligência Artificial foi usada como ferramenta de aprendizagem ativa para transformar fontes técnicas em um material organizado, verificável e aplicável.

---

## 2. Objetivos de Estudo

Os objetivos definidos para o caderno foram:

1. Compreender os fundamentos técnicos do arremesso no basquete.
2. Estudar a relação entre base, equilíbrio, linha corporal, mão de arremesso, mão guia, ponto de mira, trajetória da bola e follow-through.
3. Diferenciar sintomas aparentes de causas técnicas reais.
4. Criar um método de avaliação capaz de analisar o arremesso a partir da descrição escrita de um jogador.
5. Construir prompts de diagnóstico que não gerem respostas genéricas.
6. Desenvolver um miniguia com fundamentos, glossário, exercícios e critérios de evolução.
7. Integrar conceitos básicos de biomecânica, repetição técnica e tomada de decisão.
8. Produzir uma documentação clara o suficiente para ser usada em um portfólio técnico no GitHub.

---

## 3. Questão Norteadora

A pergunta central do projeto foi:

> Como transformar fontes confiáveis sobre arremesso no basquete em um sistema prático de diagnóstico, estudo e evolução técnica?

A partir dessa pergunta, o caderno foi construído com foco em três funções:

1. **Ensinar:** explicar os fundamentos do arremesso com clareza.
2. **Diagnosticar:** interpretar relatos de erro feitos por jogadores.
3. **Corrigir:** indicar exercícios e prioridades de melhoria.

---

## 4. Fontes Selecionadas

As fontes abaixo foram selecionadas por serem abertas, verificáveis e complementares. Elas combinam materiais instrucionais, fontes institucionais e pesquisa científica sobre biomecânica e trajetória da bola.

### Fonte 1: Jr. NBA — How to Shoot a Basketball

- Link: https://jr.nba.com/shooting/
- Tipo: artigo instrucional.
- Motivo da escolha: apresenta os fundamentos do arremesso, incluindo postura, flexão dos joelhos, posição da mão de arremesso, função da mão guia, mira, extensão do braço, follow-through e backspin.
- Uso no caderno: serviu como base para a explicação dos fundamentos iniciais e para a criação de exercícios de forma curta.

### Fonte 2: Jr. NBA — Fundamentals of Shooting

- Link: https://jr.nba.com/video/fundamentals-of-shooting/
- Tipo: vídeo instrucional aberto.
- Motivo da escolha: apresenta uma explicação visual sobre técnica e movimento do arremesso.
- Uso no caderno: foi usada como apoio para transformar conceitos técnicos em sinais observáveis no movimento do jogador.

### Fonte 3: USA Basketball — 4 Steps to a Perfect Shot

- Link: https://www.usab.com/news/2014/01/4-steps-to-a-perfect-shot
- Tipo: artigo técnico.
- Motivo da escolha: trabalha a ideia de linha de força, conectando pé, joelho, quadril, ombro, cotovelo, mão e olhos do lado de arremesso.
- Uso no caderno: serviu para estruturar a análise de alinhamento corporal e direção da bola.

### Fonte 4: FIBA — WABC Level 1 Coaches Course Manual

- Link: https://assets.fiba.basketball/image/upload/documents-corporate-wabc-coaching-level-manuals-level-1-eng.pdf
- Página oficial dos documentos da FIBA: https://about.fiba.basketball/en/wabc-documents
- Tipo: manual institucional em PDF.
- Motivo da escolha: material voltado à formação de treinadores, útil para estruturar progressões, observação técnica e ensino de fundamentos.
- Uso no caderno: ajudou a organizar a ideia de progressão pedagógica, partindo de exercícios simples até situações mais próximas do jogo.

### Fonte 5: Ball Path Curvature and In-Game Free Throw Shooting Proficiency in the National Basketball Association

- Link: https://arxiv.org/abs/2506.13779
- Versão HTML: https://arxiv.org/html/2506.13779v1
- Tipo: artigo científico aberto.
- Autores: Ruoqian Zhu, Dave Love e Scott Powers.
- Motivo da escolha: o estudo analisa a relação entre suavidade da trajetória da bola, curvatura perto da soltura e desempenho em lances livres na NBA.
- Uso no caderno: serviu como base para a seção avançada sobre suavidade final, controle de trajetória e consistência no momento da soltura.

---

## 5. Como o Caderno Foi Organizado no NotebookLM

O caderno foi organizado em quatro blocos:

### Bloco 1: Fundamentos

Neste bloco foram reunidas informações sobre:

- Base;
- Equilíbrio;
- Flexão dos joelhos;
- Mão de arremesso;
- Mão guia;
- Cotovelo;
- Mira;
- Follow-through;
- Backspin;
- Repetição em curta distância.

### Bloco 2: Diagnóstico de Erros

Neste bloco, as fontes foram usadas para responder perguntas sobre sintomas comuns:

- Bola saindo para a direita;
- Bola saindo para a esquerda;
- Bola batendo na frente do aro;
- Bola muito forte;
- Arremesso sem arco;
- Rotação lateral;
- Falta de força;
- Diferença entre arremesso no treino e no jogo.

### Bloco 3: Técnica Avançada

Neste bloco, foram reunidos conceitos como:

- Linha de força;
- Ritmo;
- Transferência de energia;
- Suavidade da trajetória;
- Ponto de soltura;
- Controle terminal da bola;
- Tomada de decisão em situação de jogo.

### Bloco 4: Prompts e Revisões

Neste bloco foram salvos prompts reutilizáveis para:

- Diagnóstico completo;
- Correção por erro específico;
- Comparação entre técnica básica e técnica avançada;
- Planejamento de treino;
- Análise de descrições incompletas;
- Revisão ativa por perguntas.

---

## 6. Engenharia de Prompts e Registros de Teste

As respostas abaixo representam a evolução documentada de consultas feitas ao caderno temático.

---

### Teste 1: Diagnóstico de bola saindo para o lado

#### Prompt usado

> Um jogador destro descreveu o arremesso assim: “minha bola costuma sair para a esquerda, meu cotovelo abre um pouco e minha mão guia parece empurrar a bola no final”. Analise o problema com base nas fontes do caderno. Separe a resposta em sintoma, causa provável, teste simples, correção principal e exercício recomendado.

#### Resultado

**Sintoma observado:**  
A bola sai para a esquerda com frequência. O jogador também percebe abertura do cotovelo e interferência da mão guia.

**Causa provável:**  
O erro principal está relacionado à direção da força aplicada na bola. Se o cotovelo abre para fora, a linha de força deixa de apontar de forma limpa para o aro. Além disso, quando a mão guia empurra a bola no final, ela deixa de ser apenas uma mão estabilizadora e passa a interferir na trajetória.

**Relação com as fontes:**  
A Jr. NBA orienta que a mão oposta deve funcionar apenas como guia e que o arremesso deve ser feito com a mão de arremesso. A mesma fonte também destaca a importância de manter o cotovelo alinhado e finalizar com o braço estendido. A USA Basketball reforça a ideia de uma linha de força no lado dominante do corpo, envolvendo pé, joelho, quadril, ombro, cotovelo, mão e olhos.

**Teste simples:**  
O jogador deve fazer dez arremessos curtos usando apenas a mão dominante. Se a bola deixar de sair tanto para a esquerda ou passar a girar de forma mais reta, a mão guia provavelmente estava interferindo no arremesso.

**Correção principal:**  
Reduzir a participação da mão guia e estabilizar o cotovelo abaixo da bola.

**Exercício recomendado:**  
Arremesso de forma curta com uma mão, próximo à cesta. O jogador deve segurar a finalização por dois segundos, observando se o punho termina apontado para o aro e se a bola gira para trás, sem rotação lateral.

#### Cicatriz do teste

A primeira versão desse prompt gerou uma resposta com muitas dicas ao mesmo tempo. Isso deixou o diagnóstico menos útil, porque o jogador poderia tentar corrigir cotovelo, base, punho, mira e força na mesma sessão.

#### Ajuste feito

Foi acrescentada a exigência de separar a resposta em sintoma, causa provável, teste simples, correção principal e exercício recomendado. Isso obrigou a IA a priorizar o problema em vez de listar dicas soltas.

---

### Teste 2: Mesmo sintoma, causas diferentes

#### Prompt usado

> Dois jogadores erram curto no arremesso. O jogador A diz que a bola bate na frente do aro e ele sente que força muito o braço. O jogador B diz que a bola também bate na frente do aro, mas ele sente que solta a bola tarde e cai para trás. Compare os dois casos. Não dê a mesma correção para ambos.

#### Resultado

**Jogador A:**  
O erro curto parece estar ligado à falta de transferência de energia das pernas para a bola. Quando o jogador sente que precisa forçar muito o braço, isso indica que a força pode estar sendo produzida principalmente pela parte superior do corpo. Nesse caso, o problema não é apenas “falta de força”, mas falta de sequência entre base, flexão, subida e soltura.

**Correção para o jogador A:**  
Trabalhar ritmo. O exercício principal deve ser o arremesso curto com movimento contínuo: flexionar, subir, estender e soltar sem pausa. A distância só deve aumentar quando a mecânica permanecer igual.

**Jogador B:**  
O erro curto tem outra origem provável. Se o jogador solta a bola tarde e cai para trás, a energia do corpo está se afastando do alvo. Isso pode reduzir a força útil transferida para a bola e prejudicar o arco.

**Correção para o jogador B:**  
Trabalhar equilíbrio e ponto de soltura. O exercício principal deve ser arremesso parado com foco em cair no mesmo lugar, mantendo o tronco estável e soltando a bola antes de perder o eixo corporal.

**Conclusão comparativa:**  
Os dois jogadores erram curto, mas não devem receber a mesma correção. O jogador A precisa melhorar a transferência de energia. O jogador B precisa estabilizar o corpo e corrigir o tempo da soltura.

#### Cicatriz do teste

A IA inicialmente tratou “errar curto” como um único problema. Esse foi um erro importante, porque o mesmo sintoma pode ter causas diferentes.

#### Ajuste feito

O prompt foi reescrito para obrigar a comparação entre dois casos. A frase “não dê a mesma correção para ambos” melhorou a qualidade da resposta.

---

### Teste 3: Tradução de conceito científico para treino

#### Prompt usado

> Explique o conceito de suavidade final da trajetória da bola usando a fonte científica sobre curvatura do arremesso. Depois, traduza o conceito para sinais visíveis em quadra e proponha um exercício prático.

#### Resultado

**Conceito técnico:**  
A suavidade final da trajetória se refere ao controle da bola perto do momento de soltura. O estudo sobre curvatura da trajetória em lances livres da NBA indica que a curvatura terminal, isto é, a curvatura próxima à soltura, tem forte relação com o desempenho. Em linguagem prática, isso sugere que o final do movimento precisa ser limpo, controlado e repetível.

**Sinais visíveis em quadra:**  

1. A bola não muda bruscamente de direção perto da soltura.
2. O jogador não faz uma correção de última hora com o punho.
3. A mão guia não empurra a bola no final.
4. A bola sai com rotação para trás, não com giro lateral.
5. O follow-through termina parecido em diferentes tentativas.

**Interpretação prática:**  
A suavidade final não significa arremessar devagar. Significa que, no momento em que a bola sai da mão, o caminho da bola e o movimento do braço estão organizados. Um arremesso pode ser rápido e ainda assim ser suave, desde que não tenha travamentos ou correções bruscas na soltura.

**Exercício recomendado:**  
Fazer séries de cinco arremessos curtos, filmados de lado. O objetivo não é contar apenas os acertos, mas observar se a bola sobe de forma parecida em todas as tentativas e se a soltura acontece sem quebra no movimento. Depois da série, o jogador deve avaliar três pontos: rotação, altura da soltura e estabilidade do follow-through.

#### Cicatriz do teste

Quando o prompt pediu apenas uma explicação científica, a resposta ficou técnica demais e pouco aplicável. O conceito de curvatura apareceu, mas não ficou claro como um jogador comum poderia observar isso em treino.

#### Ajuste feito

Foi acrescentada a ordem “traduza o conceito para sinais visíveis em quadra”. Esse comando transformou um conceito acadêmico em critério prático de avaliação.

---

### Teste 4: Diferença entre arremesso rápido e arremesso apressado

#### Prompt usado

> Explique a diferença entre arremessar rápido e arremessar apressado. Use o tema do arremesso em movimento e da preparação dos pés. Depois, dê um exemplo de treino para melhorar essa diferença.

#### Resultado

**Arremessar rápido:**  
É executar o arremesso em pouco tempo sem perder a estrutura do movimento. O jogador prepara os pés antes ou durante a recepção, alinha o corpo, sobe em equilíbrio e mantém o follow-through. O gesto é veloz, mas organizado.

**Arremessar apressado:**  
É tentar acelerar o arremesso sacrificando a técnica. O jogador recebe a bola sem base, gira o corpo durante a subida, solta a bola sem equilíbrio ou interrompe o follow-through. O resultado é um arremesso que sai rápido, mas instável.

**Ponto central:**  
A velocidade do arremesso não deve vir da pressa, mas da preparação antecipada. O jogador que prepara os pés antes de receber a bola não precisa corrigir tudo no ar.

**Exemplo de treino:**  
Treino de catch and shoot com preparação antecipada. O jogador começa fora da posição de arremesso, desloca-se até o ponto, prepara os pés antes de receber o passe e arremessa. Depois de dominar sem pressão, um defensor se aproxima com a mão levantada, sem contato. O objetivo é manter equilíbrio, alinhamento e follow-through mesmo com menos tempo.

#### Cicatriz do teste

A resposta inicial confundia velocidade com simples redução do tempo de execução. Isso não era suficiente para explicar a diferença entre técnica rápida e técnica desorganizada.

#### Ajuste feito

Foi adicionada a exigência de relacionar a resposta com preparação dos pés. Isso tornou o resultado mais específico e útil para situações reais de jogo.

---

### Teste 5: Avaliação por pontuação

#### Prompt usado

> Crie uma rubrica de avaliação de arremesso com nota de 0 a 4 para cada critério. Os critérios devem permitir avaliar uma descrição textual do jogador, mesmo sem vídeo. Inclua direção, distância, trajetória, dinâmica corporal e decisão.

#### Resultado

| Dimensão | 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|---|
| Direção | A bola erra muito para os lados e o jogador não identifica padrão | Há erro lateral frequente, mas sem causa clara | O jogador identifica o lado do erro | O erro lateral diminui com ajustes simples | A bola sai alinhada com frequência |
| Distância | A bola raramente chega bem ao aro | Erra curto ou forte com muita frequência | Tem alcance, mas pouca consistência | Controla melhor a força em distâncias próximas | Mantém força estável em diferentes distâncias |
| Trajetória | A bola sai reta ou sem arco | O arco aparece, mas varia muito | A trajetória é aceitável perto da cesta | O arco se repete em média distância | A trajetória é estável e suave |
| Dinâmica corporal | O jogador perde equilíbrio constantemente | A base muda muito entre tentativas | Há equilíbrio em arremessos parados | Mantém equilíbrio após passe ou drible | Mantém técnica mesmo em ritmo de jogo |
| Decisão | Arremessa sem considerar distância ou marcação | Força arremessos fora do alcance | Escolhe melhor no treino do que no jogo | Reconhece bons arremessos em parte das situações | Arremessa com seleção consciente e técnica estável |

**Interpretação da pontuação:**

- 0 a 7 pontos: o foco deve ser reconstrução da base técnica.
- 8 a 13 pontos: o foco deve ser consistência em curta e média distância.
- 14 a 17 pontos: o foco deve ser transferência para situações de jogo.
- 18 a 20 pontos: o foco deve ser refinamento avançado, velocidade e pressão defensiva.

#### Cicatriz do teste

A primeira tentativa criou critérios muito vagos, como “bom”, “regular” e “ruim”. Isso não ajudava a avaliar descrições reais.

#### Ajuste feito

O prompt foi reescrito exigindo notas de 0 a 4 com comportamentos observáveis. Isso tornou a rubrica mais objetiva.

---

### Teste 6: Descrição incompleta do jogador

#### Prompt usado

> Um jogador diz apenas: “meu arremesso é torto e eu erro muito”. Analise o que é possível concluir, o que ainda é hipótese e quais perguntas devem ser feitas antes de indicar uma correção definitiva.

#### Resultado

**O que é possível concluir:**  
A descrição indica um problema de direção ou consistência, mas não permite definir a causa. “Arremesso torto” pode significar erro para um lado, rotação lateral, cotovelo aberto, mão guia empurrando, corpo girando ou base desalinhada.

**Hipóteses possíveis:**  

1. A mão guia pode estar interferindo na soltura.
2. O cotovelo pode estar abrindo para fora.
3. O corpo pode estar girando durante o salto.
4. A finalização do punho pode estar apontando para fora do alvo.
5. A base pode estar desalinhada antes da subida.

**Perguntas necessárias:**  

1. A bola sai mais para a direita ou para a esquerda?
2. Você é destro ou canhoto?
3. A rotação da bola é para trás ou lateral?
4. Sua mão guia empurra a bola?
5. Seu cotovelo fica abaixo da bola ou abre para fora?
6. Você cai equilibrado ou para o lado?
7. O erro acontece mais parado, após drible ou em jogo?

**Correção provisória:**  
Antes de indicar uma correção definitiva, o jogador pode fazer arremessos curtos com uma mão para observar se a bola sai mais reta. Esse exercício não resolve todos os problemas, mas ajuda a testar se a mão guia está interferindo.

#### Cicatriz do teste

A IA tende a tentar resolver a descrição incompleta imediatamente. Isso pode gerar diagnóstico falso.

#### Ajuste feito

O prompt passou a exigir três partes: conclusão segura, hipótese e perguntas de refinamento. Isso tornou o diagnóstico mais responsável.

---

## 7. Matriz 5D do Arremesso

A partir dos testes, foi criada a **Matriz 5D do Arremesso**, uma ferramenta própria para avaliar o arremesso por descrição textual.

As cinco dimensões são:

1. Direção;
2. Distância;
3. Desenho da trajetória;
4. Dinâmica corporal;
5. Decisão.

---

### D1: Direção

A direção avalia se a bola sai alinhada ao aro ou se desvia para os lados.

**Perguntas de diagnóstico:**

- A bola sai mais para a direita ou para a esquerda?
- A rotação da bola é reta ou lateral?
- O cotovelo abre para fora?
- A mão guia empurra a bola?
- O punho termina apontado para o aro ou para o lado?

**Erros comuns:**

- Mão guia participando da soltura;
- Cotovelo desalinhado;
- Punho finalizando para fora;
- Ombros girando durante o movimento;
- Base apontando para uma direção diferente do alvo.

**Correção prioritária:**

Treinar arremesso curto com uma mão, observando rotação e follow-through.

---

### D2: Distância

A distância avalia se a bola chega curta, forte ou com variação excessiva.

**Perguntas de diagnóstico:**

- A bola bate mais na frente ou no fundo do aro?
- O jogador sente que precisa forçar o braço?
- A mecânica muda quando a distância aumenta?
- As pernas participam do movimento?
- A soltura acontece cedo ou tarde?

**Erros comuns:**

- Uso excessivo do braço;
- Pouca participação das pernas;
- Pausa antes da soltura;
- Tronco caindo para trás;
- Tentativa de arremessar de longe antes de dominar a forma.

**Correção prioritária:**

Melhorar o ritmo entre base, subida, extensão e soltura.

---

### D3: Desenho da Trajetória

O desenho da trajetória avalia o arco da bola e a suavidade do caminho até a soltura.

**Perguntas de diagnóstico:**

- A bola sai muito reta?
- O arco muda a cada tentativa?
- O movimento parece travado?
- A bola sai com toque ou como se fosse empurrada?
- Há mudança brusca perto da soltura?

**Erros comuns:**

- Trajetória baixa;
- Tensão no ombro;
- Finalização incompleta;
- Correção de última hora com o punho;
- Falta de repetição do ponto de soltura.

**Correção prioritária:**

Treinar a suavidade final do movimento, filmando a soltura de lado.

---

### D4: Dinâmica Corporal

A dinâmica corporal avalia como pés, joelhos, quadril, tronco, ombro, cotovelo, punho e dedos trabalham juntos.

**Perguntas de diagnóstico:**

- O jogador está equilibrado antes do arremesso?
- Ele cai no mesmo lugar?
- O corpo gira durante a subida?
- O movimento começa nas pernas ou apenas nos braços?
- A base se repete?

**Erros comuns:**

- Base instável;
- Queda para trás;
- Corpo girando no ar;
- Ombros desalinhados;
- Falta de conexão entre pernas e braço.

**Correção prioritária:**

Treinar arremesso parado com foco em cair equilibrado e repetir a base.

---

### D5: Decisão

A decisão avalia se o arremesso escolhido é adequado ao contexto do jogo.

**Perguntas de diagnóstico:**

- O jogador arremessa equilibrado ou pressionado?
- Ele força arremessos fora do alcance atual?
- Ele prepara os pés antes de receber a bola?
- O aproveitamento muda muito entre treino e jogo?
- Ele sabe diferenciar arremesso rápido de arremesso apressado?

**Erros comuns:**

- Arremessar longe demais;
- Acelerar sem base;
- Não ler a distância do defensor;
- Alterar a técnica por pressa;
- Tentar arremessos que ainda não domina.

**Correção prioritária:**

Treinar catch and shoot com preparação antecipada dos pés e pressão gradual.

---

## 8. Sistema de Avaliação por Descrição do Usuário

Para avaliar o arremesso, o usuário deve preencher um relato técnico. Quanto mais precisa for a descrição, melhor será o diagnóstico.

### Formulário de descrição

1. Você é destro ou canhoto?
2. De onde costuma arremessar?
3. A bola costuma errar curto, forte, para direita ou para esquerda?
4. A rotação da bola é para trás ou lateral?
5. Você sente que usa mais braço ou pernas?
6. Sua mão guia interfere na bola?
7. Seu cotovelo fica alinhado ou abre para fora?
8. Você termina equilibrado ou cai para algum lado?
9. O erro acontece mais parado, após drible, após passe ou em jogo?
10. O arremesso muda muito quando você aumenta a distância?

### Modelo de resposta diagnóstica

A resposta da IA deve seguir esta estrutura:

1. Diagnóstico provável;
2. Evidências na descrição;
3. Causa mecânica;
4. Prioridade de correção;
5. Exercício principal;
6. Sinal de progresso;
7. Erro a evitar;
8. Pergunta de acompanhamento.

---

## 9. Miniguia de Estudo

### 9.1 Base

A base é o ponto inicial do arremesso. Ela precisa oferecer equilíbrio, estabilidade e repetição. Uma base instável obriga o corpo a compensar durante a subida, o que prejudica direção, força e trajetória.

O jogador não precisa copiar exatamente a posição de outro atleta, mas precisa encontrar uma base repetível. O pé do lado dominante pode ficar levemente à frente, desde que isso não provoque rotação exagerada.

### 9.2 Mão de Arremesso

A mão de arremesso deve controlar a bola pelos dedos, não pela palma. Isso permite melhor toque e facilita a produção de rotação para trás.

Sinais de erro:

- Bola sem rotação;
- Bola saindo com giro lateral;
- Punho rígido;
- Finalização para o lado.

### 9.3 Mão Guia

A mão guia deve estabilizar a bola antes da soltura. Ela não deve empurrar, girar ou direcionar a bola no final.

Uma forma simples de testar interferência da mão guia é fazer arremessos curtos com apenas uma mão. Se a bola sair mais reta, a mão guia provavelmente estava atrapalhando.

### 9.4 Cotovelo

O cotovelo deve trabalhar próximo à linha da bola e do alvo. Quando ele abre excessivamente, a força pode ser desviada para o lado.

O objetivo não é deixar o corpo rígido, mas impedir que o cotovelo crie uma força lateral.

### 9.5 Mira

A mira deve ser consistente. O jogador pode mirar a parte de trás do aro, a frente do aro ou uma referência central, mas não deve trocar o alvo a cada tentativa.

A consistência visual ajuda a transformar o arremesso em um gesto repetível.

### 9.6 Ritmo

Ritmo é a conexão entre preparação, flexão, subida, extensão e soltura.

Um arremesso com bom ritmo parece uma sequência única. Um arremesso com ritmo ruim parece dividido em partes separadas.

Sinais de ritmo ruim:

- Pausa antes da soltura;
- Uso excessivo do braço;
- Bola curta em distâncias maiores;
- Movimento diferente a cada tentativa.

### 9.7 Follow-Through

O follow-through é a finalização do movimento. Ele ajuda a manter direção, toque e repetição.

Um bom follow-through apresenta:

- Braço estendido;
- Punho relaxado;
- Dedos apontando para o alvo;
- Equilíbrio após a soltura;
- Repetição entre tentativas.

### 9.8 Suavidade Final

A suavidade final é um conceito avançado. Ela representa a qualidade do movimento perto da soltura da bola.

O estudo sobre curvatura da trajetória em lances livres da NBA indica que a parte final do caminho da bola é especialmente importante. Isso reforça a necessidade de evitar correções bruscas no último instante.

Na prática, o jogador deve buscar uma soltura limpa, com rotação para trás e follow-through estável.

### 9.9 Arremesso em Movimento

Depois de dominar a forma parada, o jogador deve levar a técnica para situações em movimento.

A progressão recomendada é:

1. Arremesso parado perto da cesta;
2. Arremesso após passe;
3. Arremesso após um drible;
4. Arremesso após deslocamento lateral;
5. Arremesso com aproximação de defensor;
6. Arremesso em situação de jogo.

### 9.10 Técnica em Jogo

A técnica em jogo depende de decisão. Um jogador pode ter boa mecânica parado e ainda errar em partidas se não preparar os pés, se apressar a finalização ou escolher arremessos fora do próprio alcance.

A técnica ideal não é apenas bonita. Ela precisa sobreviver à velocidade do jogo.

---

## 10. Glossário

**Arco:** curva da bola no caminho até o aro.

**Backspin:** rotação para trás produzida pelos dedos e pelo punho no momento da soltura.

**Base:** posição dos pés e distribuição do peso antes do arremesso.

**Catch and shoot:** arremesso feito logo após receber um passe.

**Cotovelo alinhado:** posição em que o cotovelo do braço de arremesso fica próximo da linha da bola e do alvo.

**Curvatura terminal:** curvatura da trajetória da bola perto do momento de soltura.

**Follow-through:** finalização do movimento após soltar a bola.

**Linha de força:** alinhamento funcional entre pé, joelho, quadril, ombro, cotovelo, mão e alvo.

**Mão guia:** mão que estabiliza a bola antes da soltura, sem empurrar.

**Ponto de mira:** referência visual escolhida pelo jogador no aro.

**Ponto de soltura:** posição e instante em que a bola sai dos dedos.

**Rotação lateral:** giro da bola para o lado, normalmente associado a interferência da mão guia ou finalização desalinhada.

**Ritmo:** continuidade entre base, subida, extensão e soltura.

**Suavidade final:** controle do movimento perto da soltura da bola.

---

## 11. Prompts Reutilizáveis

### Prompt 1: Diagnóstico completo

> Você é um analista técnico de arremesso no basquete. Avalie a descrição do jogador usando as fontes do caderno. Organize a resposta em diagnóstico provável, evidências na descrição, causa mecânica, prioridade de correção, exercício principal, sinal de progresso, erro a evitar e pergunta de acompanhamento. Descrição: “[cole aqui]”.

### Prompt 2: Mesmo erro, causas diferentes

> Dois jogadores apresentam o mesmo sintoma: “[descrever sintoma]”. O primeiro relata: “[descrição A]”. O segundo relata: “[descrição B]”. Compare os dois casos e explique por que eles não devem receber exatamente a mesma correção.

### Prompt 3: Correção por dimensão da Matriz 5D

> Avalie a descrição abaixo usando a Matriz 5D do Arremesso: direção, distância, desenho da trajetória, dinâmica corporal e decisão. Dê nota de 0 a 4 em cada dimensão e justifique cada nota. Descrição: “[cole aqui]”.

### Prompt 4: Técnica avançada em linguagem simples

> Explique o conceito técnico abaixo em linguagem de treino. Para cada conceito, apresente explicação simples, sinal visível em quadra, erro comum e exercício de correção. Conceito: “[cole aqui]”.

### Prompt 5: Plano de treino personalizado

> Crie um treino de arremesso de 20 minutos para o seguinte problema: “[descrever problema]”. O treino deve conter aquecimento técnico, exercício principal, exercício de transferência para jogo e critério objetivo de progresso.

### Prompt 6: Descrição incompleta

> A descrição do jogador está incompleta: “[cole aqui]”. Separe a resposta em: o que é possível concluir, o que ainda é hipótese, quais perguntas precisam ser feitas e qual exercício provisório pode ser usado sem risco de reforçar um erro.

### Prompt 7: Revisão ativa

> Crie perguntas de revisão sobre arremesso no basquete. As perguntas devem exigir raciocínio técnico, não memorização. Inclua perguntas sobre diagnóstico, causa mecânica, exercício corretivo e tomada de decisão.

---

## 12. Plano de Treino Técnico

### Treino de 20 minutos para corrigir arremesso torto

**Objetivo:** melhorar direção, mão guia e follow-through.

**Minuto 0 a 4 — Forma curta com uma mão**  
Arremessar próximo à cesta usando apenas a mão dominante. Observar se a bola gira para trás e se o punho termina apontado para o aro.

**Minuto 4 a 8 — Mão guia silenciosa**  
Posicionar a bola com as duas mãos, mas retirar a pressão da mão guia no momento da soltura. O foco é impedir que a mão guia empurre a bola.

**Minuto 8 a 12 — Arremesso com pausa na finalização**  
Arremessar e segurar o follow-through por dois segundos. Observar se o braço termina alinhado ao alvo.

**Minuto 12 a 16 — Catch and shoot curto**  
Receber passe próximo à cesta, preparar os pés e arremessar mantendo o mesmo gesto técnico.

**Minuto 16 a 20 — Registro técnico**  
Fazer 10 arremessos e registrar: acertos, erros para direita, erros para esquerda, bolas curtas, bolas fortes e tipo de rotação.

---

## 13. Critérios de Evolução

O jogador está evoluindo quando:

1. Os erros laterais diminuem.
2. A rotação lateral aparece com menos frequência.
3. A bola passa a girar para trás.
4. O follow-through se repete.
5. A mecânica não muda tanto quando a distância aumenta.
6. O jogador consegue explicar a causa provável do próprio erro.
7. O aproveitamento melhora em zonas específicas da quadra.
8. A técnica permanece mais estável sob pressão.
9. O jogador diferencia arremesso rápido de arremesso apressado.
10. O treino deixa de ser apenas contagem de acertos e passa a incluir observação técnica.
