# hello-rails-apm

`vim influxdb_rails.rb`

## Set up your orangesys host and jwt_token

```sh
    config.client.hosts = ["<orangesys_endpoint>"]
    config.client.jwt_token = "<ornagesys_jwt_token>"
```

```sh
docker build -t hello-rails-apm .

docker run -it -d -p 4000:4000 hello-rails-apm
```
