git submodule add https://github.com/<user>/rock rock
git clone --recursive <project url>
git submodule update --init --recursive

docker image build -t <username>/repositorio:tag nameFold
docker image push <username>/repositorio:tag
docker-compose ps

docker-compose logs
docker-compose logs --tail 10 --follow "CTRL+S and CTRL+Q pauses and resumes live following."

https://www.pixelflush.com/blog/2013/03/29/fix-locale-setting-on-ubuntu-ec2-instances/

$ sudo locale-gen de_DE.UTF-8 en_US.UTF-8
$ sudo apt-get install language-pack-en

LC_ALL="en_US.UTF-8"