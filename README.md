# wordpress
Manifesto para instalação do Wordpress em um deployment Kubernetes

Para instalar e rodar o serviço WordPress, siga o passo a passo abaixo:

1 - Instale o MariaDB (mariadb-deployment.yaml), antes de rodar, acesse o manifesto e defina seu usupario e senha do BD nos campos "name" e "value";
2 - Instale o Nginx (nginx-deployment.yaml).
