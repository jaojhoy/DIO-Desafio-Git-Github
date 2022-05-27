# Git e GitHub

O Git é um sistema de versionamento de código distribuído e o GitHub ele faz o armazenamento online.

As vantagens de se trabalhar com eles são:

-  Controle de versão
- Armazenamento em nuvem 
- Trabalho em equipe 
- Possível melhora do seu código
- Reconhecimento

Para usar o Git em sua máquina, primeiro devemos fazer a instalação do mesmo (Link disponível na aba de introdução). Depois de instalado, devemos aprender alguns comandos que serão essenciais para seu funcionamento, alguns desses comandos são:

- cd "nome da pasta" - entra na pasta solicitada
- cd .. - Volta a uma pasta anterior 
- ls - Comando para listar os arquivos dentro da pasta
- ls -a - Comando para listar os arquivos ocultos da pasta
- mkdir "nome da pasta" - Cria uma pasta com o nome escrito
- git init - inicia o git dentro da pasta 
- git status - mostra o status dos arquivos 
- git add . - adiciona todos os arquivos
- git commit -m "mensagem" - comita o arquivo
- git rm "nome arquivo" - remove o arquivo com o mesmo nome 
- git clone "link" - clona os arquivos do link 
- git remote - exibe os arquivos remotos 
- git push - enviar arquivos para o repositório remoto 
- git pull - atualiza os arquivos para evitar conflito

Aprendemos também sobre o sha1, que é algo muito importante para a criptografia, onde a encriptação gera um conjunto de caracteres identificador de 40 dígitos.

o  sha1 tem toda uma estrutura por trás, para mais devemos retornar a aula 3, onde podemos ver como o git funciona por debaixo dos panos.

Aprendemos também sobre a criação da chave ssh e do token na plataforma github, os dois foram criados para reconhecer a máquina na hora de enviar os arquivos para a nuvem. Para criar a chave devemos digitar ssh-keygen - t ed25519 - C "email do github". Para achar a chave devemos digitar cd /c/ users / nome de usuário / ssh /, depois ls para listar os arquivos e digitar cat id_ed25519.pub, nisso vai te gerar uma chave, basta copiar a mesma e jogar no github.

Depois devemos ir no git bash novamente e digitar pwd - para mostrar o caminho completo, ls para listar os arquivos, e iniciar o agente ssd, para isso digite eval $(ssh-agent-s), depois disso digita ssh-add id_ed25519, depois desse processo precisamos validar a mesma e para isso adicionamos o clone do site github, digita  git clone "caminho da chave copiada" e damos enter após isso irá perguntar se quer continuar e devemos digitar y para aceitar.

Para criar um arquivo dentro do git pela primeira vez, primeiro devemos configurar o mesmo, para isso devemos:

- Digite git config --globar user.email "email que a conta foi criada no github"

- git config --global user.name "nome que a conta foi criado no github"

Até aqui vimos um pouco sobre o Git e Github, para um melhor esclarecimento e conhecimento devemos assistir as aulas disponíveis no site da DIO no BootCamp da TQI, onde lá fala mais sobre o Git e GitHub.





