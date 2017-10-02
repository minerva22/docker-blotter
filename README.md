# docker-blotter
docker setup for [ffa-blotter](https://github.com/ffapb/ffa-blotter)

# Usage

- copy `production.env.dist` to `production.env` and modify the variables
- copy `build/blotter/importMarketflow.sh.dist` to `.../importMarketflow.sh` and modify
- copy `build/blotter/zipline_project/settings_producition.py.dist` to `.../settings_production.py` and modify
- `docker-compose up -d`
- standard [docker-compose-fu](https://docs.docker.com/compose/reference/overview/)

    docker-compose exec blotter pew in FFA_BLOTTER ./manage.py createsuperuser

