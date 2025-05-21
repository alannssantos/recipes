# Recipes:
## Sumário
  * [Batocera Dual Boot com linux](https://github.com/alannssantos/recipes/#batocera-em-dual-boot-com-linux)
  * [PS2 SoftMod](https://github.com/alannssantos/recipes/#ps2-softmod)
  * [Gerenciador de Memory Card do PS2](https://github.com/alannssantos/recipes/#gerenciador-de-memory-card-do-ps2)
  * [Firefox user.js](https://github.com/alannssantos/recipes/#firefox-user.js)
  * [Pen drive Bootável](https://github.com/alannssantos/recipes/edit/main/archives/Flexget.md#pen-drive-boot%C3%A1vel)
  * [Flexget](https://github.com/alannssantos/recipes/edit/main/archives/Flexget.md#flexget)
### Batocera em Dual Boot com linux.
   * As instruções já estão no [script](https://raw.githubusercontent.com/alannssantos/recipes/refs/heads/main/archives/15_batocera).
     * (Nunca rode um script sem saber o que ele faz ou rode caso confie em quem o fez).
### [PS2 SoftMod.](https://github.com/alannssantos/recipes/blob/main/archives/PS2_SoftMod.md)
   * Desbloqueio para PS2 sem alterar o hardware do aparelho.
### Gerenciador de Memory Card do PS2.
   * Obs.: O GUI não funciona que preste!
     ```bash
     pip install mymcplusplus
     ```
   * Instruções:
     ```bash
     mymcplusplus --help
     ```
### Firefox [user.js](https://raw.githubusercontent.com/alannssantos/recipes/refs/heads/main/archives/user.js).
   * O arquivo user.js é colocado na pasta de perfil do firefox (about:support).
### Pen drive Bootável.
   * Use o comando `lsblk` para saber qual disco ultilizar (Cuidado para formatar o Sistema).
     ```bash
     sudo dd if="<destino do arquivo>" of="/dev/<drive destino>" bs=1M status=progress
     ```
### [Flexget](https://github.com/alannssantos/recipes/blob/main/archives/Flexget.md).
   * Automatiza downloads de séries e animes via torrent.
