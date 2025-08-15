# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de Git e Github.

## Configuração inicial
Rode os comandos a seguir no terminal(cmd) do seu computador.
```bash
git config --global user.name "Renan S. M. Amaral"
git config --global user.email "renan.amaral01@fatec.sp.gov.br"
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador, utilizamos o init.
**NOTA:** "init" é executado apenas 1 vez.
```bash
git init
```

Para vincular o projeto ao Github, utiliza-se o comando remote, basta o repositório estar criado no Github
e seguir a segunda opção da lista de comandos que aparece no site.
**NOTA:** Depois do remote deve ser executados os outros 2 comandos da página.
```bash
git remote add origin < url_repositorio_github >
```

Para verificar a situação do Repositório (Pasta), utiliza-se o comando "status" a qualquer momento.
```bash
git status
```
Quando o status mostrar arquivos em vermelho é necessário executar o comando "add" para adicionar os arquivos a serem salvos.
```bash
git add # Adiciona pasta por pasta individualmente.

git add . # Adiciona tudo de uma só vez.
```

Para commitar mudanças, utiliza-se o comando "commit -m (mensagem)".
```bash
git commit -m (mensagem)
```

Para Enviar/Baixar arquivos, pastas, etc, em relação a Nuvem. Utiliza-se os comandos "pull" / "push"

Para baixar as alterações que estão apenas no Github, utiliza-se o "pull". <br>
**NOTA:** Sempre deve baixar a última versão da nuvem antes de enviar a atual do computador.
```bash
git pull
```

Para enviar os commits do PC Local para o Github, utiliza-se o "push".
```bash
git push
```
