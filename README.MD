# Azeno


alias dcu="docker compose up"
alias dcub="docker compose up --build"
alias dcb="docker compose build"
alias dcbn="docker compose build --no-cache"
alias dcd="docker compose down"
alias dcdv="docker compose down -v"
alias dnp="docker network prune"
alias dip="docker images prune"
alias dvp="docker volume prune"
alias dra="docker rm $(docker ps -a -q)"
alias dce="docker compose exec"

dcesh(){
        docker compose exec "$1" sh
}
