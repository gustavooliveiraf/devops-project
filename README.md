git submodule add https://github.com/<user>/rock rock
git clone --recursive <project url>
git submodule update --init --recursive

docker image build -t <username>/repositorio:tag nameFold
docker image push <username>/repositorio:tag
docker-compose ps

docker-compose logs
docker-compose logs --tail 10 --follow "CTRL+S and CTRL+Q pauses and resumes live following."