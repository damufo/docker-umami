# Installation

Forked from atareao (atareao.es)
```
git clone https://github.com/damufo/docker-umami.git
cd docker-umami
cp sample.env .env
sed -i "s/umami.yourserver.org/your_fqdn/g" .env
```

Remember set parameters in file .env

```
nano .env
```

```
docker-compose -f docker-compose.yml -f docker-compose.traefik.yml up -d
docker-compose logs -f
```

