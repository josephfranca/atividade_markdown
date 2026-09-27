# Atividade sobre versionamento e documentação

## O passo a passo da criação e envio
---
## Como você cria um repositório vazio diretamente no GitHub? Quais configurações iniciais são necessárias?
---
### Para criar um repositório vazio, clique na opção "New repository", ao selecionar essa opção abrirá uma nova tela que contém duas partes, a primeira "General" (Geral) contém dois campos obrigatórios: Owner (Dono) e Repository name (Nome do repositório), e um campo chamado Description (Descrição) que não é obrigatório colocar mas ajuda a entender e ter um breve contexto sobre o que é aquele projeto e também, consiste em boas práticas de documentação.
A segunda parte Configuration (Configurações) contém as seguintes opções: Choose visibility (Escolha de visibilidade) que define quem pode ver e contribuir com esse repositório. Add README(Adicionar README) que permite que tenha um arquivo README, geralmente esse arquivo serve para explicar o projeto, as tecnologias que foi utilizadas nele e tutoriais de instalação e como rodar. Add .gitignore(Adicionar .gitignore) que serve para que certos arquivos sejam ignorados na hora de subir para o github. Add License (Adicionar Licença) adiciona uma licença que protege o seu projeto de copias e/ou outras questões relacionadas com a propriedade intelectual.
Após preencher os campos obrigatórios, clique no botão verde "Create repository" para enfim criar o seu repositório.
---
## A Conexão: Explique o processo de vincular uma pasta local no seu computador a esse repositório remoto criado na nuvem.
---
### Vincular uma pasta local a um repositório remoto significa apontar o seu git local para o endereço na nuvem, permitindo a troca de arquivos entre o seu computador e o github.
---
##  O Primeiro Envio: Descreva a sequência exata de ações ou comandos necessários para pegar os arquivos da sua máquina e fazer com que eles apareçam na página do seu repositório no GitHub.

O processo começa inicializando o git na pasta com git init, preparando os arquivos com o comando git add . e salvando uma versão com git commit -m "Mensagem sobre o que você está "commitando"".
Em seguida, o comando git remote add origin <URL> Cria essa ponte de comunicação salvando o link do servidor remoto. Por fim, ao executar git push -u origin main, você envia seus arquivos locais para a nuvem e estabelece o rastreamento entre essas duas pontas
---
### A anatomia do README perfeito
---
## Propósito: O README, como dito anteriormente, tem a função de explicar o projeto, e serve como um manual para outros programadores, recrutadores técnicos e estudantes que queriam conhecer seu trabalho.
---
### Dados Fundamentais
---
## Um bom README precisa conter o título do projeto, uma descrição do projeto, como por exemplo: para qual intuito o projeto foi criado e quem foram os criadores, a lista de tecnologias utilizadas e onde elas foram aplicadas, como instalar e rodar o seu projeto, e também, uma forma de contato.
---
### O Poder do markdown
---
## O Markdown é utilizado no arquivo README.MD por ser uma linguagem de marcação leve que combina simplicidade de escrita com uma formatação rica. Ele permite estrutar documentações completas diretamente em texto puro, sendo nativamente interpretado pelo github.
---
### O Mapa das Atualizações (Commits e Pushes)
---
## Github Online
---
## Permite editar arquivos e fazer commits diretamente pelo site. É ideal para pequenos ajustes e correções de texto no dia a dia, mas limitado por não permitir testar o código antes de salvar e nem editar múltiplos arquivos simultaneamente.
---
## Git via linha de comando (Terminal)
---
## Funciona através do ciclo git status, git add, git commit e git push. É o padrão mais tradicional por oferecer controle total, alta precisão e funcionar em qualquer ambiente, inclusive em servidores remotos sem interface gráfica.
---
## Github Desktop: Aplicativo visual dedicado ao Git que simplifica a navegação por meio de botões claros (Commit, Push, Fetch). Facilita a visualização do histórico e das diferenças de código, sendo excelente para iniciantes ou quem prefere uma experiência 100% gráfica.
---
## A filosofia da atualização
---
## Fazer commits pequenos e contínuos facilita a localização e correção de erros, evita conflitos complexos de código (merge conflicts) e torna as revisões de equipe muito mais ágeis e eficientes do que enviar grandes blocos de alterações de uma só vez.

