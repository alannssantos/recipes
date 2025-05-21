# Flexget install
### Requisitos
   ```bash
   sudo apt install python3-libtorrent && \
   pip install flexget --upgrade && \
   pip install transmission-rpc --upgrade
   ```
### Crontab `/etc/crontab`.
   ```bash
   echo "*/30 *  * * *   $USER   $HOME/.local/bin/flexget execute > /tmp/dtest_erro.log 2>&1" | sudo tee -a /etc/crontab
   ```
### Editar o [arquivo](https://raw.githubusercontent.com/alannssantos/recipes/refs/heads/main/archives/config.yml) `~/.config/flexget/config.yml`.
   * Definir os destinos dos donwloads.
   * Testar se RSS estão validos.
   ```bash
   flexget --test execute
   ```
