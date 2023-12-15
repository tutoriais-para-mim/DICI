# Configuração Caixa
## Descrição
Como realizar o procedimento de configuração de ECF

### Do que se Trata? 🔍

Se trata do procedimento padrão para a configuração de caixas via Script

### Como Realizar? 🤔

O primeiro passo é a obtenção do número de Série da Bematech

> O Número de Série da Bematech pode ser obtido pelo Sabium, através do caminho: Fiscal > Manutenção > ECF > Consultar

Após isso vc pode rodar o seguinte script:

    cd /tmp/ && wget http://ocs.lojasmm.com.br/filialconfig.sh && chmod 777 filialconfig.sh && sh filialconfig.sh

Ele irá pedir algumas informações como a senha mestre, o número da Filial, a ECF que será instalada, o nº de série da bematech... Após a inserção de todos esses campos ele irá realizar a configuração!

Após este procedimento, vc pode seguir com a Configuração da Impressora e/ou Pasta Scanner 😁✔️
