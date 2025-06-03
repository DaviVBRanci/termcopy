# termcopy

`termcopy` é uma ferramenta simples para facilitar a cópia e colagem de arquivos via terminal Linux. Ela disponibiliza dois comandos:

- `copy caminho/do/arquivo` — copia o arquivo para uma área temporária
- `paste caminho/da/pasta` — cola (move) o arquivo copiado para a pasta destino

---

## Instalação

Você pode baixar e instalar o pacote `.deb` diretamente da nossa [Release no GitHub](https://github.com/DaviVBRanci/termcopy/releases/tag/V1.0):

No terminal, execute:

```bash
wget https://github.com/DaviVBRanci/termcopy/releases/download/V1.0/termcopy.deb
sudo dpkg -i termcopy.deb
sudo apt-get install -f
