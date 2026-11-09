# MechaBound — Downloads

Jogo 2D de artilharia por turnos para Windows x64.

**Versão atual: [v0.10.0](https://github.com/valtermjr93/MechaBound-Releases/releases/tag/v0.10.0)**

- [Baixar launcher com o jogo incluído](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.10.0/MechaBound-Launcher-Windows-x64.zip)
- [Baixar somente o jogo](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.10.0/MechaBound-Windows-x64.zip)
- [Checksums SHA-256 dos dois pacotes](https://github.com/valtermjr93/MechaBound-Releases/releases/download/v0.10.0/SHA256SUMS.txt)

## Novidades da v0.10.0

DoomShot Cerco Titã pelo sexto cartão do arsenal ou tecla 5. Transformação articulada em tanque, carga energética e dez mísseis de 300 de dano direto, até 3.000 no conjunto. Um uso por jogador, consumido ao selecionar. A escolha fica travada até disparar ou encerrar o turno, mesmo que a oportunidade termine sem disparo.

O especial libera após 20 turnos gerais concluídos, no turno 21, ou com vida em 15% ou menos. Vida total de 5.000 pontos, exibida em porcentagem. Míssil padrão causa 200, Dual lança dois de 200, Super causa 300 e Laser causa até 1.000. Gravidade de 360 no padrão e 540 no Super. Veja o histórico completo no CHANGELOG.

## Launcher

Extraia o ZIP inteiro em uma pasta pessoal e abra **MechaBound Launcher.exe**. O pacote inclui o jogo v0.10.0 e o runtime. Não precisa instalar Godot ou .NET nem executar como administrador.

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
