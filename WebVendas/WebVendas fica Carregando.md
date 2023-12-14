# WebVendas fica em Loading

## Descrição
Erro relacionado ao Java em sua maioria das vezes
 
### Do que se Trata? 🔍

Se trata de um erro referente a execução do Java nas máquinas, essencial para a execução do WebVendas.

### Como Resolver? 🤔

A Resolução é muito simples em sua maioria, mas irei dividir aqui para diferentes SO's:

 1. **Windows 🪟:**
 
**-> Encerrar Processos do Java:** No Windows basta acessar o *Gerenciador de Tarefas* e buscar todos os Processos do Java no mesmo, após encontrar irá clicar com o botão direito do mouse sobre o processo e selecionar a opção *"Finalizar Tarefa"*.

**-> Reinicializar o Java:** Agora iremos iniciar o serviço do Java novamente, para isso necessitaremos abrir o *Windows Explorer* e acessar a pasta *"Cupom Fiscal"* nela iremos achar um arquivo denominado *"ServerCupomFiscal.jar"* dê um duplo clique nele e pronto!

2. **Linux 🐧:**
No Linux a resolução é completa via Terminal, segue os comandos abaixo:

**-> Encerrar Processos do Java:** No Linux basta utilizar o comando `killall java` que irão ser encerrados todos os processos relacionados.

**-> Reinicializar o Java:** Para a reinicialização utilizamos o comando `java -jar /CupomFiscal/ServerCupomFiscal.jar &` após isso ele irá listar o processo, algo como *4325[1]*, quando isso aparecer pressione Enter e pronto, o processo foi inicializado!

Isso deverá normalizar o WebVendas! 😁
