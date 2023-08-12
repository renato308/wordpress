# wordpress
Manifesto para instalação do Wordpress em um deployment Kubernetes

Para instalar e rodar o serviço WordPress, siga o passo a passo abaixo:

1 - Instale o MariaDB (mariadb-deployment.yaml), antes de rodar, acesse o manifesto e defina seu usupario e senha do BD nos campos "name" e "value";

2 - Instale o Nginx (nginx-deployment.yaml);

3 - Instale o serviço do MariaDB (mariadb-service.yaml);

4 - Instale o serviço do Nginx (nginx-service.yaml);

5 - Instale o Wordpress, mas antes abra o manifesto e configure os apontamentos para o banco criado (wordpress-deployment.yaml);

6 - Instale o serviço do Wordpress (wordpress-service.yaml);
