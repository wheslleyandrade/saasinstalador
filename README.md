# Passo 1 – Acessar sua VPS via SSH e rodar o seguinte comando
apt update && apt upgrade
# Passo 2 – Após a atualização e upgrade da VPS vamos instalar o aaPanel. Para isso
copie e cole o comando abaixo no terminal
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo
bash install.sh aapanel
# Passo 3 – Após a instalação do aaPanel anote o link, usuário e senha que foi fornecido
no terminal para que tenha essas informações salvas. Em seguida acesse o link, digite o
usuário e senha e faça login no painel.
# Passo 4 – Dentro do painel acesse o menu “Files” e entre na pasta home. Dentro da
pasta home vamos clonar o repositório saasinstalador. Para isso acesse o terminal,
insira a senha do usuário root da VPS e rode o seguinte comando:
git clone https://github.com/wheslleyandrade/saasinstalador.git
