# Erro no Anexo de Contratos no WebVendas

## Descrição
![enter image description here](https://cdn.discordapp.com/attachments/1185266846128160788/1185267069525176401/WhatsApp_Image_2023-12-15_at_13.57.27.jpeg?ex=658efcfa&is=657c87fa&hm=527eac44ad1e55461110d4a8f3bab280d04fbdebbb7271f5392895b2417a7f88&)
Erro retorna toast com a mensagem *"Falha de Comunicação com o Servidor! Por favor tente novamente"*
 
### Do que se Trata? 🔍

Este erro acontece pois algo está travando o Upload dos arquivos para o Banco de Dados, ou seja, o Banco não recebe os arquivos...

### Como Resolver? 🤔

> Verificar o Load do Banco ou se houve um Upload para a Produção recente, por precaução 🔃

Outra Coisa que pode ocasionar este erro é o anexo de dois documentos iguais... Neste caso o aconselhável é a análise do contrato que se está tentando realizar o Upload... Em Alguns casos os arquivos são escaneados de forma conjunta, desta forma ambos os contratos estarão no mesmo PDF, oque irá resultar no erro 😫

Algo que pode ser realizado neste caso é a divisão do Arquivo em Dois Arquivos distintos, o [ILovePDF](https://www.ilovepdf.com/pt/dividir_pdf), por exemplo, realiza esta divisão de maneira bem simples e rápida...

Outra coisa que vale prestar a atenção após a divisão do PDF é o nome dos arquivos... Eles também devem ter nomes diferentes!

Esse procedimento deve bastar para a realização do Upload! 😁✔️
