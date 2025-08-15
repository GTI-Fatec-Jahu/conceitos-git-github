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
Para iniciar o GIT em uma pasta do computador utilizamos o init. <br>
**IMPORTANTE:** Só é executado 1 vez.
```bash
git init
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no
Github e seguir a segunda opção da lista de comandos que aparece no site.<br>
**IMPORTANTE:** Depois do remote deve ser executados os outros 2 comandos da página. 
```bash
git remote add origin < url_repositorio_github >
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

Para baixar as alterações que estão apenas no Github utilizamos o pull. <br>
**IMPORTANTE:** Sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador 
```bash
git pull
```

Para enviar os commits do pc para o Github utilizamos o push.
```bash
git push
```

Para baixar o repositório do Github em um novo computador utilizamos o clone.
```bash
git clone < url_do_repositorio_github >
```