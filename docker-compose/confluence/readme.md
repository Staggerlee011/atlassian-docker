# confluence

runs confluence using a postgres database with local storage. had to use a docker volume due to issues running docker on windows and using linux container.

## notes

need to run `docker volume create --name postgres-confluence-data -d local` before using `docker-compose up`

need to update host file to contain `127.0.0.1 confluence.internal`
