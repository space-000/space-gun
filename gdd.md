# Game Design Document: Space-Gun (Nome Provisório)
**Revisão:** 0.1.0
**Baseado no Template de:** Benjamin “HeadClot” Stanley

---

## Visão Geral

**Tema / Ambientação / Gênero**
Futurista / Ficção Científica / Sobrevivência / Vertical Shooter (Shmup) + Tower Defense.

**Resumo das Mecânicas Principais**
Pilotagem ágil com visão top-down, sistema de atirar e esquivar (Bullet Hell leve), coleta de power-ups, transição para modo de construção e defesa de torres (Tower Defense) e modo cooperativo para 2 jogadores.

**Plataformas-alvo**
PC (Steam), Consoles (Nintendo Switch, PlayStation, Xbox) e futuramente Mobile.

**Modelo de Monetização**
Premium (Jogo Base Pago). Expansões futuras de missões e cosméticos de naves via Microtransações.

**Escopo do Projeto**
Jogo Indie de médio escopo com foco em gameplay dinâmico e rejogabilidade cooperativa.

### Influências

* **Bloons TD 6:** Inspirou a mecânica tática de defesa planetária e o posicionamento de estruturas defensivas.
* **Xenon 2 - Megablast:** Inspirou o combate clássico de naves de rolagem vertical (Vertical Shooter) e o sistema de melhoria de tiros no espaço.

---

## O Pitch de Elevador (Elevator Pitch)
"No ano de 2999, com a Terra totalmente inabitável, você e seu parceiro são a última esperança da humanidade. Pilote através de hordas alienígenas no espaço profundo e, ao aterrissar, construa defesas táticas para proteger nosso novo lar. *Space-Gun* é uma mistura eletrizante de ação arcade e estratégia de Tower Defense para 2 jogadores."

---

## Descrição do Projeto

### Breve
*Space-Gun* acompanha a unidade de reconhecimento "Hermes", composta pelos pilotos Alex e Jeremyas, em uma missão desesperada para encontrar um novo planeta para o Projeto Gemini e a nave colossal Arca. O jogo alterna entre duas fases distintas de gameplay: combates espaciais frenéticos em formato *Vertical Shooter* e sessões táticas de *Tower Defense* ao aterrissar em planetas em potencial. 

### Detalhada
O universo do jogo se passa no ano de 2999. A Terra tornou-se um deserto tóxico e sua órbita é um cemitério impenetrável de lixo espacial. A última esperança reside na Arca, um colosso estelar abrigando os últimos 5 milhões de sobreviventes humanos, além de sementes e DNA da flora e fauna extintas. Para que a Arca possa pousar, a unidade Hermes precisa limpar o caminho e preparar o terreno.

A campanha principal é dividida em 6 grandes atos: 3 fases no espaço profundo e 3 fases em superfícies planetárias. No espaço, os jogadores controlam suas naves (Alex na Vermelha e Jeremyas na Azul/Verde) desviando de meteoros, destruindo frotas alienígenas e coletando *power-ups* que alteram seus tiros. 

Ao chegar em um planeta, o gênero do jogo muda drasticamente. A câmera permanece isométrica/top-down, mas agora os jogadores devem usar os recursos coletados no espaço para construir torres de defesa, barricadas e instalações de extração para proteger a zona de aterrissagem (Base) das hordas nativas alienígenas. Se a base sobreviver, o planeta (ou setor) é conquistado, permitindo o avanço da Arca.

### O que torna este projeto único?
* **A Fusão de Gêneros:** A transição fluida de um *Vertical Shooter* focado em reflexos para um *Tower Defense* focado em raciocínio tático.
* **Co-op Assíncrono e Dinâmico:** Os jogadores podem combinar tiros no espaço e dividir tarefas de construção e ataque na fase de defesa.
* **Progressão Contínua:** O desempenho e os recursos coletados na fase de *Shooter* afetam diretamente o poder de construção na fase de *Tower Defense*.

---

## Mecânicas Principais de Gameplay

### 1. Combate Espacial (Vertical Shooter)
**Detalhes:** A clássica rolagem de tela de baixo para cima. Ondas de inimigos, asteroides e chefes intermediários surgem do topo da tela.
**Como funciona:** Os jogadores controlam a movimentação da nave livremente pela tela. O ataque primário é contínuo. Eles devem desviar de projéteis e coletar esferas brilhantes para aumentar o nível da arma principal, adicionando tiros espalhados, lasers ou mísseis teleguiados.

### 2. Defesa Planetária (Tower Defense)
**Detalhes:** Ao passar a fase de tiro, a nave pousa em um terreno pré-definido. Hordas alienígenas começam a marchar por caminhos delineados em direção ao centro da tela (a Zona de Pouso).
**Como funciona:** Usando sucata e energia coletadas no espaço, os jogadores posicionam torres (metralhadoras, lança-chamas, geradores de escudo). Os jogadores também podem usar suas naves como "torres móveis" que podem atirar, mas são vulneráveis a dano se voarem perto demais das hordas terrestres.

### 3. Sistema de Melhorias (Upgrades e Power-ups)
**Detalhes:** O fortalecimento das naves e das torres ocorre tanto a curto prazo (durante a fase) quanto a longo prazo (na garagem da Arca).
**Como funciona:** *In-game*, os jogadores pegam cápsulas que mudam o tipo de tiro ou curam a nave. No menu entre as fases, eles usam "Créditos de Sobrevivência" para aumentar permanentemente o dano base, a vida das torres e a velocidade das naves.

### 4. Sinergia Cooperativa (2 Players)
**Detalhes:** O jogo é desenhado com foco em cooperação local ou online para 2 jogadores. 
**Como funciona:** Se os jogadores cruzarem os tiros de energia de suas naves, criam um "Tiro de Ressonância" mais poderoso. Durante o *Tower Defense*, eles podem compartilhar fundos de construção para erguer estruturas mais caras rapidamente.

---

## História e Personagens

### História (Breve)
Em 2999, a Terra é inabitável. A nave-mãe Arca procura um novo lar (Projeto Gemini). A unidade de ponta Hermes deve abrir caminho pelo espaço hostil e preparar zonas de aterrissagem em planetas não mapeados.

### Personagens Principais
* **Piloto 1 (Nave Vermelha) - Alex:** Um jovem prodígio nascido e criado dentro da nave Arca. Ele nunca viu o sol real da Terra, apenas vídeos de arquivo. Rebelde, porém com os melhores reflexos da frota, Alex pilota uma nave experimental focada em agilidade e cadência de tiro rápida. Ele luta pelo sonho de ver florestas e oceanos reais.
* **Piloto 2 (Nave Azul/Cinza) - Jeremyas:** Um veterano rabugento que viveu a época do "Êxodo da Terra". Jeremyas viu a destruição de perto e perdeu muito na fuga. Ele é o engenheiro-chefe da missão Hermes, sendo extremamente tático e metódico. Sua nave é focada em blindagem pesada, disparos de plasma condensado e construção rápida de defesas físicas.

---

## Recursos Necessários (Assets)

### Arte 2D
* **Texturas de Ambiente:** Fundo espacial estrelado com nebulosas, detritos orbitais da Terra, terrenos planetários (gelo, areia, pântano tóxico).
* **Sprites de Naves:** Nave do Alex (design aerodinâmico vermelho), Nave do Jeremyas (design robusto azul/cinza), 15+ variações de naves alienígenas.
* **Sprites de Towers:** Bases de torre, armas acopláveis (torreta dupla, laser, míssil), muros e barricadas.

### Som
* **Sons de Ambiente (Espaço):** Ruído de motor de plasma, explosões abafadas, trilha sonora eletrônica/synthwave acelerada (Xenon 2 vibes).
* **Sons de Ambiente (Planetas):** Vento alienígena, urros de monstros se aproximando, sons metálicos de construção, batidas tribais ou épicas de defesa.
* **Sons de Combate:** Tiros de laser (agudos para Alex, graves para Jeremyas), impacto, sirenes de "Escudo Baixo", barulho de moedas/sucata sendo coletada.

### Código
* **Player Controller:** Movimentação fluida top-down no espaço (8 direções), transição para sistema de grid/mouse para a construção das torres.
* **Wave Manager:** Sistema que controla o tempo de surgimento de inimigos, dificuldade das ondas e progressão de caminho (Pathfinding) dos inimigos no Tower Defense.
* **Gerenciador de Power-Ups:** Scripts para trocar temporariamente o projétil atirado pelos jogadores.

---

## Escopo e Cronograma do Projeto

### Fases do Jogo
* **Fase 1: Espaço 1 (Entrada da Órbita):** Ambientado no lixo espacial da Terra. Apresentação das mecânicas de *Shooter*.
* **Fase 2: Planeta 1 (Aterrissagem Tática):** Terreno árido. Introdução ao *Tower Defense*, limpando os alienígenas nativos mais básicos.
* **Fase 3: Espaço 2 (Cinturão de Asteroides):** Dificuldade elevada, introdução de inimigos kamikazes e chefão (Nave-Mãe Alienígena).
* **Fase 4: Planeta 2 (Biosfera Hostil):** Planeta de selva ácida. Torres sofrem desgaste natural, inimigos voadores atacam a base.
* **Fase 5: Espaço 3 (Portal Dimensional/Rota Final):** Tiroteio massivo, tela cheia de projéteis (Bullet Hell).
* **Fase 6: Planeta 3 (A Nova Terra):** Batalha de defesa final. Ondas intermináveis até que a Arca pouse em segurança.

### Marcos (Milestones)
* **Milestone 1:** Protótipo jogável do modo *Vertical Shooter* com Alex e Jeremyas e mecânica básica de atirar.
* **Milestone 2:** Protótipo do modo *Tower Defense* e grid de construção.
* **Milestone 3:** Integração das duas fases (espaço -> aterrissagem). Implementação de transição e sistema de economia (sucata compartilhada).
* **Milestone 4:** Adição de todas as artes finais, polimento de UI/UX, efeitos sonoros e tela de menu.
* **Milestone 5:** Testes de balanceamento (QA) e lançamento da versão final.
