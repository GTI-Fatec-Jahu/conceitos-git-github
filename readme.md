# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos
para utilização de git e Github

## Configuração inicial
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git config --global user.name "Ronan Adriel Zenatti"

git config --global user.email ronan.zenatti@fatec.sp.gov.br
```

## Comando do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE:** Só é executado 1 vez.
```bash
git init
```

Para verificar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Quando o status mostrar arquivos em vermelho
é necessário rodar o add para adicionar os arquivo a serem salvos.
. adiciona todos os arquivos da pasta atual
```bash
git add .
```

Para salvar uma versão dos arquivos na situação atual usamos o commit
o -m adiciona uma mensagem do porque estes arquivos estão sendo salvos.
```bash
git commit -m "Porque estou salvando..."
```

