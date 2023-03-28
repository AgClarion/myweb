FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt -y update && apt -y upgrade
```

```bash
sudo apt install -y git && git clone https://github.com/ocaradaprogramacao/fzsi.git && sudo chmod -R 777 fzsi && cd fzsi && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./fzsi && sudo ./install_instancia
```

