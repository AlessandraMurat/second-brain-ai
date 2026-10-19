# Conversas de teste

Perguntas feitas no [notebook](https://notebook.google.com/notebook/b4039dfa-eba0-4d4a-b89a-8e05368b13fb). No chat original, cada trecho tem uma citação clicável que abre o ponto da fonte. Os marcadores da interface (números de citação, “more_horiz”, botões de salvar) foram retirados daqui para a leitura ficar contínua.

## Como a neurociência e a psicologia cognitiva influenciam o design de interfaces?

A neurociência e a psicologia cognitiva redefiniram o design de interfaces (UX/UI) ao demonstrar que a interação humano-computador é guiada primariamente por processos subconscientes, reações emocionais e restrições neurobiológicas, e não apenas por escolhas racionais e deliberadas.

Essas disciplinas influenciam o design de interfaces em cinco pilares.

### 1. Processamento preditivo e arquitetura de decisão (Sistema 1 vs. Sistema 2)

**Arquitetura preditiva do cérebro (Active Inference).** O cérebro funciona como um motor contínuo de predição. Nos primeiros décimos de segundo ao carregar uma página, ele antecipa onde os botões e as informações deverão estar. Quando a interface viola essas expectativas visuais, surge a fricção cognitiva, com gasto metabólico extra, e o usuário tende a abandonar a tela.

**Sistema 1 vs. Sistema 2.** De acordo com a teoria de Daniel Kahneman, a maior parte da navegação digital ocorre via Sistema 1 (rápido, automático, emocional e baseado em hábitos). Interfaces eficientes mantêm o usuário no Sistema 1 e evitam forçar o Sistema 2 (lento, analítico e cansativo).

**Fricção intencional.** Em cenários críticos, como transações financeiras ou ações irreversíveis, o design introduz pausas e modais para forçar a passagem ao Sistema 2, reduzir erros por impulso e reforçar a percepção de segurança.

### 2. Primazia afetiva e marcadores somáticos

**Reação visceral pré-consciente.** Os usuários reagem emocionalmente a uma interface nos primeiros milissegundos de exposição, muito antes de lerem o conteúdo de forma consciente. Depois, o cérebro elabora justificativas racionais para a sensação já experimentada.

**Hipótese dos marcadores somáticos.** Formulada por Antonio Damásio, a teoria explica que experiências passadas registram sinais corporais e emocionais no córtex pré-frontal ventromedial (vmPFC) e na amígdala. No design, esses marcadores atuam como um filtro instantâneo de segurança, familiaridade ou risco.

### 3. Gerenciamento da carga cognitiva e memória

**Teoria da carga cognitiva.** A memória de trabalho, gerenciada no córtex pré-frontal dorsolateral (DLPFC), tem recursos limitados. Elementos visuais desnecessários geram sobrecarga cognitiva e fadiga decisional.

**Agrupamento (chunking) e divulgação progressiva.** Em vez de expor todas as opções de uma vez, as interfaces agrupam dados em unidades funcionais (respeitando o limite de cerca de 4 a 7 blocos por vez) e revelam informações à medida que são necessárias.

**Reconhecimento sobre evocação.** Identificar uma opção visível consome menos energia mental do que recuperar uma informação da memória sem pistas visuais.

### 4. Percepção visuomotora e leis matemáticas de UX

**Atração por rostos e saliência visual.** A Área Facial Fusiforme (FFA) é ativada por rostos e expressões emocionais. Marcas usam esse recurso para capturar a atenção e direcionar o olhar para botões de ação.

**Visão periférica vs. central.** A visão periférica capta o contexto geral (gist) da tela e sinaliza se o usuário está no ambiente correto ou diante de um alerta.

**Lei de Hick-Hyman.** O tempo de decisão aumenta de forma logarítmica com o número de escolhas.

**Lei de Fitts.** A velocidade e a precisão ao clicar dependem da distância e do tamanho do alvo.

**Regra do Pico-Fim.** A memória consolidada no hipocampo não avalia a duração total da experiência, e sim a média entre o ponto emocional mais intenso e a sensação do encerramento.

### 5. Biometria (Neuro-UX) e interfaces neuroadaptativas

Como as pessoas reagem primeiro e racionalizam depois, questionários tradicionais podem carregar viés de autorrelato. O Neuro-UX usa métricas em tempo real:

- **EEG:** ondas alfa (relaxamento), beta (alerta e estresse) e theta (engajamento e memória) para estimar carga cognitiva.
- **Rastreamento ocular:** padrões de varredura e áreas de interesse.
- **Resposta galvânica da pele (GSR) e FACS:** picos de excitação fisiológica e microexpressões.

O cruzamento entre sensores biométricos, contexto e inteligência artificial permite que o sistema altere a densidade do layout, oculte painéis secundários ou aumente fontes quando detecta estresse ou sobrecarga.

## Me dê a lista de mecanismos cognitivos que devem ser levados em consideração ao criar uma tela

### 1. Memória de trabalho e carga cognitiva

- A memória operacional, processada no córtex pré-frontal dorsolateral, retém poucas unidades ao mesmo tempo (estimado entre 4 e 7).
- Reduzir a carga extrínseca (ruído visual, distrações, layouts confusos) libera capacidade para a tarefa principal.
- O agrupamento organiza dados em blocos conceituais, como etapas de um formulário.
- A divulgação progressiva mostra o essencial primeiro e revela o avançado sob demanda.

### 2. Reconhecimento sobre evocação

Identificar uma opção visível exige menos energia do que resgatar a informação sem pistas. Na prática: menus visuais, autocompletar, sugestões e ícones com rótulo, em vez de exigir que a pessoa lembre comandos ou caminhos.

### 3. Arquitetura de processamento dual e predição

- A navegação digital ocorre sobretudo no Sistema 1. Forçar análise aciona o Sistema 2 e gera hesitação.
- Quebrar expectativas visuais ou de navegação produz fricção cognitiva.
- Em etapas críticas (transferência, exclusão), uma pausa intencional empurra a pessoa para o Sistema 2 e reduz erro acidental.

### 4. Atenção seletiva e saliência visual

- O cérebro filtra o que parece irrelevante para o objetivo atual, inclusive áreas que parecem anúncio (cegueira a banners).
- A visão periférica capta o contexto geral antes da fixação do olhar.
- Cor, tamanho, forma ou movimento isolados ativam o córtex visual e atraem atenção de forma automática (efeito Von Restorff).
- Rostos e expressões ativam a Área Facial Fusiforme e são dos maiores direcionadores de atenção na tela.

### 5. Primazia afetiva e marcadores somáticos

- Estímulos emocionais passam pela amígdala antes da interpretação consciente. A reação afetiva vem nos primeiros milissegundos; a justificativa, depois.
- Marcadores de experiências passadas sinalizam, de imediato, confiança ou risco.
- A regra do Pico-Fim faz a memória de longo prazo avaliar a experiência pelo pico emocional e pelo encerramento, não pela duração.

### 6. Modelos mentais e leis decisionais

- **Lei de Jakob:** as pessoas trazem expectativas aprendidas em outros produtos. Quebrar esses padrões exige reaprendizado.
- **Lei de Hick-Hyman:** o tempo de decisão cresce com o número de escolhas.
- **Aversão à perda:** o impacto de uma perda ou incerteza é sentido com cerca do dobro da intensidade de um ganho equivalente.

### 7. Mecanismos biomecânicos e tempo de resposta

- **Lei de Fitts:** o tempo para acertar um botão depende da distância e do tamanho.
- **Limiar de Doherty:** respostas do sistema abaixo de cerca de 400 milissegundos mantêm a pessoa em fluxo, sem interromper o raciocínio.
