# Erro de Assinatura GPG

## Descrição
![ERRO](https://1.bp.blogspot.com/-Ts5_z4XAR6A/XnfWYR-YWwI/AAAAAAAAyL4/9Z1_mlqF2p41DGxqRvOoMqJnQvLbSSDeQCLcBGAsYHQ/s640/Captura+de+tela+de+2020-03-22+18-19-17.png)
O erro se deve ao fato de você não ter adicionado a chave publica do repositório de terceiros que está tentando usar.

### Do que se Trata essa Chave? 🔑

O GnuPG é uma implementação completa e gratuita do padrão OpenPGP, conforme definido pelo RFC4880 (também conhecido como PGP). O GnuPG permite criptografar e assinar seus dados e comunicações; possui um sistema versátil de gerenciamento de chaves, além de módulos de acesso para todos os tipos de diretórios de chaves públicas. O GnuPG, também conhecido como GPG, é uma ferramenta de linha de comando com recursos para fácil integração com outros aplicativos. Uma variedade de aplicativos e bibliotecas de front-end estão disponíveis. O GnuPG também fornece suporte para S / MIME e Secure Shell (ssh).

Fonte: GnuPG

### Como Resolver? 🤔

Na Maioria das vezes na mensagem do erro GPG nos é dada a chave no final. Confira o exemplo abaixo:

    W: Erro GPG: https://dl.winehq.org/wine-builds/ubuntu disco InRelease: As assinaturas a seguir não puderam ser verificadas devido à chave pública não estar disponível: NO_PUBKEY **76F1A20FF987672F**

Para resolver o problema você deve adicionar a chave manualmente com o comando abaixo, substituindo key_informada pela key informada no erro.


    apt-key adv --keyserver keyserver.ubuntu.com --recv-keys key_informada

No nosso exemplo a key informada no erro é **76F1A20FF987672F**  
  
O nosso comando fica como abaixo.


    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 76F1A20FF987672F

Após adicionar a key atualize a lista de pacotes através do seguinte comando

    sudo apt update

Isso deve corrigir o Erro 😁
