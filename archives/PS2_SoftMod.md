# Desbloqueio SoftMod para PS2.
## Requisitos:
  * Um PS2 Já desbloqueado (caso o FreeDVDBoot não funcione para seu modelo).
  * Memory Card com wLauncher ou uLauncher.
  * Pendrive formatado em FAT32.
## Itens compactados:
  * [PS2_SoftMod.7z](https://raw.githubusercontent.com/alannssantos/recipes/refs/heads/main/archives/PS2_SoftMod.7z):
    * FMCB (1953, 1966)
    * Funtuna Fork
    * Emuladores:
      * Gameboy Advance
      * Super Nintendo
    * wLauncher ISO.
    * FreeDVDBoot ISO.
## Modo de uso:
### PS2 Totalmente Bloqueado (Sem PS2 Secundário para ajudar no desbloqueio)
   1. Formate o pendrive em FAT32 para maior compatibilidade.
   1. FreeDVDBoot ISO: (grave o DVD-ROM na menor velocidade para melhor qualidade).
      * Esse método vai funcionar em todos os Slim até mesmos nos Bloqueados, mas a linguagem do console deve está em inglês.
   1. Coloque as pastas na raiz do pendrive (os arquivos ISOS pode deixar de fora).
   1. Caso o esteja usando um console de terceiros:
      * Temos que achar um exploit que funcione no bloqueado:
        * Funtuna Fork te dá 3 opcoes na instalação manual (pesquise para saber qual é a do seu console alvo).
   1. Com o Funtuna instalado no Memory Card (entre no wLauncher no seu console bloqueado e faça a instalação do FMCB pelo console bloqueado).
   1. O desbloqueio aqui já está pronto (Veja alguns vídeos para aprender a usar o OPL).
### PS2 Totalmente Bloqueado (Com PS2 Secundário para ajudar no desbloqueio)
   1. Formate o pendrive em FAT32 para maior compatibilidade.
   1. Temos que achar uma forma de acessar o wLauncher ou uLauncher.
      * Temos que acessar o wLauncher:
        * Memory Card:
          * A maioria que tem o OPL, já vem com wLauncher.
        * wLauncher ISO: (grave o CD-ROM na menor velocidade para melhor qualidade)
          * Para usar esse método o console deve ter algum chip de desbloqueio (Matrix ou similar).
   1. Coloque as pastas na raiz do pendrive (os arquivos ISOS pode deixar de fora).
   1. Caso o esteja usando um console de terceiros:
      * Temos que achar um exploit que funcione no bloqueado:
        * Funtuna Fork te dá 3 opcoes na instalação manual (pesquise para saber qual é a do seu console alvo).
   1. Com o Funtuna instalado no Memory Card (entre no wLauncher no seu console bloqueado e faça a instalação do FMCB pelo console bloqueado).
   1. O desbloqueio aqui já está pronto (Veja alguns vídeos para aprender a usar o OPL).
## Emuladores:
   No arquivo vai ter 2 emuladores (GBA e SNES):
   1. Basta colocar os na pasta "mc?:/APPS" no Memory Card.
   1. Editar o arquivo "mc?:/SYS-CONF/FREEMCB.CNF". 
      * A parte 2 dá para editar pelo PS2, mas para deixar em ordem vai dá mais trabalho.
      * Para deixar mais pratico seria melhor copiar o FREEMCB.CNF para o pendrive e editar no PC ou SmartPhone.
   1. Roms dos emuladores:
      * Crie uma pasta para cada emulador na Raiz do Pendrive que você vai usar o OPL e coloque as Roms.
   1. Jogar com emuladores:
      * Abra o emulador encontre a Rom e seja feliz.
