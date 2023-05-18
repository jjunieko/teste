## subindo aplicação docker em nginx e nodejs

### fiz apenas um teste para simular uma subida de site 

--para rodar imagem : docker composer build 

-- derrubar aplicação  docker compose down , ... build e up 

-- docker compose up -d -> levanta o container

-- criar comunicação combanco de dados add password na linha de comando server o arquivo não  subir por segurança

-- sudo vim/etc/post
    . setar porta  127.0.0.1   myport.localhost

 ### Subindo para digital ocean

----Envio para git primeiro
 - git init
 - git add .
 - git commit -m 'fist commit'
 - git remote add 'nome do repositorio'
 - git push origin master

 ---------
  copie a chave ssh publica
    cat ~/.ssh/id_rsa.pub

-- entrar no site da digital e publicar o site ou app 
  (entrar na maquina e fazer a sicronia da nossa aplicação com o site digital ocean). 
  clonar o repositorio dentro da digital e fazer o build da image docker.
  fazer conexões com postgress e rodar o set up do  banco de dados.
  ex. docker-compose run minha_app node /usr/appp/db_setuor/prepare.js
  pronto! Acesse o ip.

** dicas: verificar ufw - firewall

