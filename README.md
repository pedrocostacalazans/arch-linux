# Linux-Arch

----
## Comandos do linux manjaro

**sudo pacman -Sy** = sincroniza os repositórios.

**sudo pacman -Su** = procura por atualização.

**sudo pacman -Syu** = sincroniza os repositórios/procura por atualização.

**sudo pacman -Syy** = sincroniza os repositórios do Manjaro Linux.

**sudo pacman -Syyu** = sincronização total/procura por atualização.

**sudo pacman -S pacote** = instala um pacote.

**sudo pacman -R pacote** = remove um pacote.

**sudo pacman -Rs pacote** = remove o pacote junto com as dependências não usadas por outros pacotes.

**sudo pacman -Rsn pacote** = remove o pacote junto com as dependências não usadas por outros pacotes e junto com os arquivos de configuração.

**sudo pacman -Ss pacote** = procura por um pacote.

**sudo pacman -Sw pacote** = apenas baixa o pacote e não o instala.

**sudo pacman -Si pacote** = mostra informações de um pacote não instalado.

**sudo pacman -Qi pacote** = mostra informações do pacote já instalado.

**sudo pacman -Se pacote** = instala apenas as dependências.

**sudo pacman -Ql pacote** = mostra todos os arquivos pertencentes ao pacote.

**sudo pacman -Qu** = mostra os pacotes que serão atualizados.

**sudo pacman -Q** = lista todos os pacotes instalados.

**sudo pacman -Qo arquivo** = mostra a qual pacote aquele arquivo pertence.

**sudo pacman -Qdt** = lista pacotes desnecessários, sem dependências

**sudo pacman -Rns $(pacman -Qqdt)** = apaga pacotes desnecessários, sem dependências

**sudo pacman -A pacote.pkg.tar.gz** = instala um pacote local.

**sudo pacman -Sc** = deleta do cache todos os pacotes antigos.

**sudo pacman -Scc** = limpa o cache, removendo todos os pacotes existentes no /var/cache/pacman/pkg/.

**sudo pacman-optimize** = otimiza a base de dados do pacman.

**sudo pacman -Sdd** = instala ignorando as dependências.

**sudo pacman -Rdd** = elimina um pacote ignorando as dependências.

**sudo pacman-mirrors.conf** = para gerenciar pacman.cof

**sudo pacman-mirrors -g** = para gerar um novo mirrorlist

**sudo pacman -U home/user/arquivo.tar.xz** = instalar pacotes baixados no pc

**sudo pacman -U http://www.site.com/arquivo.tar.xz** = instalar pacotes baixados via download

**sudo pacman -Qem** = lista pacotes instalados do repo AUR

**sudo pacman -Rscn** = desinstala pacotes e suas dependencias e seus registros, tudo.

**sudo pacman -S pacote –noconfirm** = Instala o pacote sem precisar confirmar com “yes/no ,S/N”…

**sudo pacman -Syu –ignoregroup pacote1 , pacote2…** = sincroniza os repositórios/procura por atualização e ignora os grupos dos pacotes solicitados

yaourt -Syua –devel = sincronizar a base de dados

yaourt -Syyuua = atualizar o repo AUR

yaourt -Ss nome = pesquisar no repo AUR

yaourt -S nome = instalar pacotes do repo AUR

yaourt -R nome = remover pacotes do repo AUR

yaourt -Rsn nome = remover pacotes + dependências do repo AUR

yaourt -Syu –devel –aur = sincronizar a base de dados e atualiza pacotes
