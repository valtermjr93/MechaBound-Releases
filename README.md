# MechaBound — Downloads

Jogo 2D de artilharia por turnos para Windows x64.

**Versão atual: [v0.11.0](https://github.com/valtermjr93/MechaBound-Releases/releases/tag/v0.11.0)**

- [Baixar launcher com o jogo incluído](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.11.0/MechaBound-Launcher-Windows-x64.zip)
- [Baixar somente o jogo](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.11.0/MechaBound-Windows-x64.zip)
- [Checksums SHA-256 dos dois pacotes](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.11.0/SHA256SUMS.txt)

## Novidades da v0.11.0

- Espelho, ventilador e gravidade reduzida duram quatro turnos gerais cada.
- Quando não há evento ativo, a chance total de iniciar um evento é de 12,5%. Os 87,5% restantes mantêm o turno sem evento. Os três tipos têm chances iguais e os blocos não se sobrepõem.
- O espelho permanece na mesma posição durante os quatro turnos.
- O ventilador usa o ícone V1 aprovado e sorteia um vento diferente em cada turno do evento.
- Fora do ventilador, o vento muda em intervalos sorteados de 7, 8 ou 9 turnos gerais. Ao terminar o evento, começa uma nova contagem sorteada.
- A gravidade reduzida usa o ícone G3 aprovado e aplica 5% da gravidade normal aos projéteis e às quedas dos mechas. O Super Shot continua 50% mais pesado que o padrão.
- A HUD prevê os próximos três turnos com espelho, sol, ventilador ou gravidade com X. A seta identifica o primeiro. O texto informa a duração restante do ventilador e da gravidade reduzida.
- O cálculo dos arcos do DoomShot acompanha a gravidade ativa e limita o planejamento ao tempo de vida dos projéteis.
- Validação com 40 testes Godot, testes do executável exportado, renderização das duas fases e 21 cenários do launcher. Atualização pública com confirmação validada após a publicação.

## Launcher

Extraia o ZIP inteiro em uma pasta pessoal e abra **MechaBound Launcher.exe**. O pacote inclui o jogo v0.11.0 e o runtime. Não precisa instalar Godot ou .NET nem executar como administrador.

Ao abrir, o launcher verifica a última versão estável e pede confirmação antes de atualizar:

- **Sim:** baixa, verifica o pacote e abre o jogo atualizado.
- **Não:** abre a versão já instalada, sem baixar o pacote novo.
- Sem internet ou sem versão mais recente, abre o jogo instalado.

Há os botões **Jogar** e **Verificar atualizações**, além de **Cancelar** durante a operação. Não há Importar ZIP, Voltar à anterior ou seleção de versões antigas. Mantém a versão instalada ou atualiza para a última estável, sempre com confirmação. Não atualiza durante uma partida. Nenhuma credencial é incluída no launcher. O launcher atualiza o jogo; nesta versão, não atualiza o próprio executável.

Mantenha as pastas `game` e `data` junto do launcher. O diretório `data` guarda as instalações e o estado das atualizações. Não apague essa pasta para atualizar o launcher manualmente.

## Jogar sem launcher

Extraia o pacote do jogo e abra **MechaBound.exe**, mantendo **MechaBound.pck** na mesma pasta. Escolha Passagem Alpina ou Travessia Nevada.

- **A / ←**: esquerda; **→**: direita.
- **S / ↑** aumenta o ângulo e **D / ↓** diminui.
- **Shift** sobe e **Ctrl** desce no ar.
- **Scroll / Page Up / Page Down** controla o zoom.
- **Espaço**: carregar; dispara ao soltar ou ao atingir 100% em 2 segundos.
- **Tab**: arsenal; **1–5**: poderes; **0**: tiro padrão.
- **F2**: passar o turno; **F1**: ajuda; **R**: reiniciar; **Q**: menu.

Windows 10/11 x64, OpenGL 3.3. Instruções e licenças acompanham os pacotes.

## Versões anteriores

O launcher mantém a versão instalada ou atualiza para a última estável e não oferece rollback. As Releases publicadas e o histórico do código são preservados. Não misture EXE e PCK de versões diferentes.

Este repositório contém somente distribuição e instruções. O código-fonte e seu histórico são mantidos separadamente em um repositório privado. [Todas as Releases](https://github.com/valtermjr93/MechaBound-Releases/releases).
