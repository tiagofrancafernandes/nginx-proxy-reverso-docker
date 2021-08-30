## Como fazer proxy

* Copie o exemplo para o arquivo de configuração

```shell
cp default-example.conf nginx/sites/default.conf
```

* Edite o arquivo `nginx/sites/default.conf` modificando o host para as suas necessidades.

* Se precisar de mapear mais de 1 host, descomente os hosts adicionais em `nginx/sites/default.conf` ou crie novos.

* Não se esqueça copiar o arquivo `env-example` para `.env` e ditar as portas conforme desejado.

```shell
cp env-example .env
```

* Inicie o container

```shell
docker-compose up
```