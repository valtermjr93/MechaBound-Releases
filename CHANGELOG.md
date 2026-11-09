# Histórico público

## v0.8.0 — 09/11/2026

Esta versão reúne todos os ajustes desde a v0.7.0.

- Fases ampliadas de 1.152 para 2.304 pixels, com distância inicial entre os mechas dobrada. Câmera acompanha o mecha e o disparo. Scroll e Page Up/Page Down controlam o zoom entre 50% e 150%, com HUD fixa e fundo preenchendo a tela.
- Três apoios de pedra e metal encaixados sob as pontes. Na fase nevada, os apoios têm neve, gelo e topos ajustados à curvatura inferior. A superfície da ponte acompanha essa curva, com movimento dos mechas, colisões e neve alinhados. Malhas e tabelas são preparadas uma vez e reutilizadas.
- Satélite fixo no centro do mapa, em x=1.152, em qualquer zoom. O emissor acompanha a mira do marcador.
- Flutuação usa o mesmo contador do movimento no chão. Ativá-la eleva o limite total do turno de 200 para 250 px, descontando o percurso já usado. A subida automática inicial de 48 px é gratuita. Movimento horizontal, vertical e diagonal consome o percurso real.
- Shift sobe e Ctrl desce no ar. S/D e ↑/↓ ajustam a mira em todas as situações, inclusive com movimento zerado. A descida para na altura inicial após a subida automática. O voo mantém espaço para passar sobre o relevo.
- Ao zerar o movimento, o mecha permanece suspenso e pode atirar o míssil padrão ou passar com F2. Ao carregar, fica vertical e imóvel. Ao fim do trajeto, F2, tempo esgotado ou golpe letal, pousa na posição horizontal em que encerrou a ação. No próximo turno jogável, o movimento normal renova para 200 px.
- Corpo inclina suavemente 45° na direção do deslocamento horizontal. Plasma azul tem ondulações, pulsação, partículas e reação ao movimento. Canhão compensa a inclinação para manter a mira correta. Corpo, faróis e peças articuladas usam suas camadas independentes.
- Dual Shot, Super Shot e Flutuação possuem 3 cargas cada por mecha e por partida. Disparar Dual/Super consome uma carga, e ativar Flutuação consome uma carga. Selecionar ou cancelar um poder de tiro conserva o saldo.
- Laser libera no 7º turno geral, contando os dois mechas. F2 e tempo esgotado avançam um turno, e oportunidades puladas automaticamente pela penalidade ficam fora da contagem. Após usar o Laser, é preciso completar 5 turnos jogáveis próprios para recarregar.
- HUD mostra turno geral, disponibilidade do Laser, cargas, movimento compartilhado e último ângulo junto da porcentagem de força do último disparo de cada mecha. O histórico atualiza no disparo, persiste ao passar a vez ou cancelar carga e é limpo ao reiniciar.
- Validação com 35 scripts Godot, 21 cenários do launcher, renderização das duas fases e poses, executável Windows exportado e atualização real pelo canal público.



## v0.7.0 — 07/11/2026

Alterações desde a v0.6.0:

- M2 — Tático no tiro padrão e em cada míssil do Dual, com arte metálica e exaustão.
- P5 — Titã no Super Shot: projétil maior e mais grosso, acompanhando a direção do voo e ricochete.
- F2 — Plasma azul na flutuação: dois propulsores separados do corpo, ignição branca/ciano e partículas animadas. Termina ao pousar, preservando faróis e articulações.
- Laser Foco Preciso: halo estreito, bordas suaves e contato compacto. Explosão Fusão no primeiro mecha atingido, com clarão, fogo, onda expansiva, faíscas e fumaça. Inclui acerto próprio, reflexão e golpe letal; erro não gera explosão.
- Brilho radial em texturas reutilizadas; neve pré-calculada preservada. Sem tremor de câmera ou dano de área adicional.
- Launcher sem Importar ZIP, Voltar à anterior ou seleção de versão. Jogar, Verificar atualizações e Cancelar preservados. Mantém a instalada ou atualiza para a última estável com confirmação; sem retorno silencioso a uma instalação anterior.
- Mesmas regras de dano, movimento, turnos, colisões e sons aprovados. Assets originais e versões anteriores preservados no histórico.
- Validação: 29 testes Godot, 21 cenários do launcher, renderização de 24 poses, revisão gráfica dos efeitos, executável Windows e atualização real pelo canal público.

Baixe o launcher para incluir o jogo e o runtime. Quem já tem o launcher pode atualizar o jogo por ele; para obter a interface simplificada, baixe também o novo pacote do launcher, que não atualiza o próprio executável. Preserve sua pasta data ao substituir os arquivos do launcher.


## v0.6.0 — 07/11/2026

Primeira distribuição pública; reúne as alterações desde a v0.5.0 privada.

- Launcher Windows portátil, confirmação antes de atualizar, consulta manual, jogo offline, SHA-256, instalações separadas e rollback.
- Downloads anônimos por este canal público, sem credenciais no launcher.
- Mechas e pontes com profundidade; corpo completo sob peças móveis, canhão e braço independentes, faróis e cockpit fixos ao torso.
- Ponte metálica e arco nevado com topo visível e sombras internas. Terreno, colisões e neve pré-calculada preservados.
- Música, efeitos, poderes, turnos, espelho, satélite e disparo automático a 100% da versão anterior preservados.
- 28 testes do jogo, 21 cenários do atualizador, revisão gráfica de 24 poses e das duas fases, executável exportado e verificação de atualização pública.
