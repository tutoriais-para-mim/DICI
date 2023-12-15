# Erro SQL - Fechamento de Venda

## Descrição
![ERRO](https://cdn.discordapp.com/attachments/1184901232414953552/1184901328288354335/image.png?ex=658da85b&is=657b335b&hm=cfeacdc9ff5c0d34b194b212f019186f458ba706825a59664caaecbc830bada7&)
 Imagem do Erro 👆

### Do que se Trata? 🔍
Este erro normalmente se trata de um Erro de Conexão com o Banco de Dados quando possuí o retorno `canceling statement due statement timeout`, ele pode ser visto analisando o alerta retornado ou atravéss das requisições, onde é mais fácil e perceptível sua visualização!
![Erro](https://cdn.discordapp.com/attachments/1052993065285066793/1184907982929145946/image.png?ex=658dae8d&is=657b398d&hm=c170ba3227c42ff6f40cdf9b4117c0b7828afd1fd7aa34c7ff94b1ad01f02388&)

### Como Resolver? 🤔
Na grande maioria dos casos trata-se de um load alto por parte do banco de dados, pode-se visualizar através de `Grafana > Home > Loads`, caso o Load esteja normal o ideal é entrar em contato com o Desenvolvimento pois pode se trata de um erro de Trigger.
