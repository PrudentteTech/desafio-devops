# Desafio Prudentte - DevOps/SRE

Obrigado pelo interesse em fazer parte no nosso time! Para participar do processo de seleção, é necessário que todos os interessados pela vaga façam esse desafio. Basta realizar um fork desse repositório e após a finalização, entre em contato com quem te contactou, notificando a finalização do desafio.

Se não entender algum conceito ou parte do problema, não é motivo para se preocupar! Queremos que faça o desafio até onde souber.

## Arquitetura

A arquiterura possui 4 componentes:

1. Ingress: o primeiro integrante do processo, é o responsavel pelo redirecionamento das rotas;
2. Api 1: api disponibilizada na rota /api1, ela possúi uma conexão com o banco de dados;
3. Redis DB: banco de dados da api 1;
4. Api 2: api disponibilizada na rota /api2, ela possúi uma conexão com o banco de dados;

![Infra](/Infra.png)

## O desafio

Construa a arquitetura utilizando Kubernetes:

- É necessário que cada api possua 2 replicas;
- O Ingress pode ser feito da forma que preferir, você pode construir um API Gateway, ou utilizar um Ingress NGINX ou um trafik;
- O banco de dados Redis deve ser persistido e ter apenas 1 replica;

## Diferenciais

- Boas práticas
- Arquivos de configuração (Secrets, configmaps, ...)

Qualquer dúvida, entre em contato! Boa sorte 😄
