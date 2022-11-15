<h1>Sistema de cadastro de Jogos</h1>

>Status do projeto: Em Desenvolvimento

Para rodar esse projeto na sua maquina, por favor digite:

```
node app.js
```
```
Passo a Passo
1 (C) > git clone https://github.com/silviomuniz17/Sistema_De_Cadastro.git
2 (D) > git pull origin main
3 (E) > git status
4 (F) > git commit -m "Descrição_Do_Que_Foi_Feito"
5 (G) > git push origin main
```
```
A) Para dara acesso para outra pessoa mudar ou alterar meu codigo

1) Abrir Github na web > configurações (Settings) > Colaboradores Primeiro no menu lateral (Collabortors) >  Botão verdade adicionar pessoa (add people).
2) Localizo a pessoa > adicionara a pessoa
3) pessoa vai receber o convite para aceitar 
```
```
B) Usuario teste

conta_teste_github
Alura_Teste
Alura_Teste_01
```
```
C) Clocar a pasta do projeto

1) abrir o CMD e ir até a pasta que deseja salvar usando o cd 
2) Depois abrir o site onde está o projeto no github e copiar a url 
3) Voltando para o CMD (já na pasta desejada) deve utilizar o comando = git clone https://github.com/silviomuniz17/Sistema_De_Cadastro.git (git clonar e o caminho)
Obs.: Se você clocar em sima da pasta já baixada você apaga tudo, então é apenas para a primeira vez
```
```
D) Atualizar a pasta do projeto

1) abrir o CMD e ir até a pasta que está salvo o projeto 
2) Depois abrir o site onde está o projeto no github e copiar a url 
3) Voltando para o CMD (já na pasta desejada) deve utilizar o comando = git pull https://github.com/silviomuniz17/Sistema_De_Cadastro.git (git atualiza e o caminho)
```
```
E) Verificar como está o status do projeto

1) abrir o CMD e ir até a pasta que está salvo o projeto
2) Já na pasta desejada deve utilizar o comando = git status
3) Com isso vai mostrar os aquivo em vermelho que está apenas na sua maquina. Em Verdade arquivos que foi commitados
```
```
F) Comitar o projeto na maquina local

1) abrir o CMD e ir até a pasta que está salvo o projeto
2) Já na pasta desejada deve utilizar o comando = git commit -m "Descrição_Do_Que_Foi_Feito"
```
```
G) Enviando o projeto da maquina local para github

1) abrir o CMD e ir até a pasta que está salvo o projeto
2) Para criar um nome para sua url deve digitar = git remote add origin https://github.com/silviomuniz17/Sistema_De_Cadastro.git 
3) Para ver caminho remotos salvos = git remote -v
4) Para remover um caminho que existe = git remote rm nomedocaminho
5) Para enviar para o github = git push origin main
```
```
H) Verificar o historico 

git log --oneline = Verificar todas alterações feitas (Historicos) * para sair precione q
git log -p = virificar todas alterções feitas com mais informaçoes (historico) * para sair precione q
```
```
I) Restaurar versão de algum commit

Existe duas formas
1) Se for restaura apenas um determinado arquivo 
git restore --source 877eb6e8cc4f2dd9e7952ba1dbc01765399ac67a index.html 
2) Se for restaurar o projeto inteiro
git restore --source 877eb6e8cc4f2dd9e7952ba1dbc01765399ac67a .

Obs.: (877eb6e8cc4f2dd9e7952ba1dbc01765399ac67a codigo so commite)
``` 
```
J) Branch (Ramificações) 

1) git checkout -b desenvolvimento = criando um galho com nome de desenvolvimento
2) git switch desenvolvimento = ir para o branch desenvolvimento
3) git branch = ver qual ramificação que estou e quais tem
4) git add .
5) git commit -m "descrição"
6) git push origin desenvolvimento
7) git switch main = ir para o branch principal
8) git merge desenvolvimento = jogando tudo que está no ramo desenvolvimento para a principal
9) git push origin main
```
