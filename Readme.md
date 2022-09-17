Olá esse projeto ensina vc a usar o Git

git add --> põe o arquivo na área de stage (espera)

git add . --> esse " . " indica que add todos os arquivos disponíveis vão para espera (stage), senão dou o git add especificando o nome do arquivo que desejo enviar

git commit -m -->  manda da espera (stage) para "gravar" na branch. O '-m' é uma mnsg explica do que se trata aquele commit

git branch -M "main" --> altero o nome da branch, no caso a Master, para main

git remote add origin https://github.com/asqatester/TreinandoGit.git --> 
--> remote é a conexão do repositório local git com o repositório criado lá no GitHub
--> add é pra adcionar
--> origin é o nome que estamos dando ao caminho do repositório lá no GitHub; é o origin por ser um padrão que costumam usar mas pode ser o nome que quiser

--> até aqui só estabeleceu a conexão mas ainda não enviou nada para o repositório no GitHub. Precisa dar um push!

--> git push -u origin main --> 

feito o primeiro commite empurrado (push) ao GitHub, criarei um segundo arquivo .md só pra ver isso atualizar tudo lá no repósitório GitHub

