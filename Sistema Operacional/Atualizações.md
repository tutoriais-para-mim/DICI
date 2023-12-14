# Como Atualizar máquinas Linux

## Descrição
Breve tutorial de como atualizar as máquinas Linux...

### Do que se Trata? 🔍

A atualização `sudo apt update` em máquinas Linux baixa as informações mais recentes sobre os pacotes disponíveis, enquanto `sudo apt upgrade` instala as versões mais recentes desses pacotes no sistema operacional.

### Como Resolver? 🤔

Em máquinas Ubuntu ou MINT poderá ser efetuados os seguintes comandos:

    apt update && apt-get update && apt full-upgrade -f -y && apt autoremove -y && apt autoclean && apt clean && echo -e "\nAtualização e limpeza efetuadas!"

e/ou


    apt update && apt-get update && apt upgrade -y -f && apt-get upgrade -y -f && apt autoremove -y && apt autoclean && apt clean && echo -e "\nAtualização e limpeza efetuadas"

Algum código acima retornou erro? Rode este abaixo e tente algum acima novamente, quantas vezes for necessário:  💻


    apt-get install --fix-broken -f -y && dpkg --configure -a && apt install -f -y && apt autoremove -f -y && echo -e "\nCorreção de integridade efetuada."

Após estes procedimentos a atualização deverá ter sido efetuada!
