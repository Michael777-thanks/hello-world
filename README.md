# Comandos GIT

1. Git init

É utilizado para inicializar um repositório Git
dentro de um diretório do sistema.

2. Git clone

É utilizado para criar uma cópia de um
repositório remoto em um diretório da máquina.

3. Git status

É utilizado para verificar o status de um
repositório git, bem como o estado do repositório
central.

4. Git add

É utilizado para adicionar arquivos ao pacote de
alterações a serem feitas. É possível adicionar
um único arquivo, múltiplos arquivos de uma vez,
como git add <-arquivo1-> <-arquivo2-> ..., ou até
mesmo um diretório, a partir de seu caminho.

5. Git commit

É utilizado para criar uma nova versão do
projeto a partir de um pacote de alterações.
git commit -m "mensagem do commit"

Hardware

Noções Gerais

Comandos GIT

7. Git branch

É utilizado para criar novos ramos de
desenvolvimento, bem como visualizar quais são
os ramos existentes.

8. Git checkout

É utilizado para navegar entre as versões do
projeto, bem como entre as diferentes
ramificações criadas.
git checkout <- Hashcode do commit ->
git checkout <- nome da branch ->
git checkout -b <- nome da branch ->

6. Git log

É utilizado para ver o histórico de alterações do
projeto, onde aparecerão todos os commits feitos,
com suas respectivas mensagens e códigos
identificadores.

git log

Hardware

Noções Gerais

Comandos GIT

9. Git diff

É utilizado para visualizar modificações feitas
entre commits, sejam eles entre um commit
arbitrário e o estado atual do projeto, dois commits
arbitrários, ou até mesmo todas alterações entre
dois commits distintos.

git diff <- Hashcode do commit anterior ->

10. Git config

É usado para configurar e personalizar o ambiente Git no
seu sistema.

git config <opções> chave valor
<opções>: Pode ser global (--global) para definir
configurações para todos os repositórios no seu sistema ou
local (--local) para definir configurações específicas para um
repositório em particular.

chave: A chave de configuração que você deseja definir (por
exemplo, user.name para o nome de usuário).

valor: O valor que você deseja atribuir à chave (por
exemplo, seu nome de usuário ou endereço de e-mail).
git config --global user.name "Seu Nome"
