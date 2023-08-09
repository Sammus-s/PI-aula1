# PI-aula1: Estrutura git

### branches
    Contém referências para as branches do repositório. As branches são diferentes linhas de desenvolvimento que podem conter versões diferentes do código.
### config
    Armazena as configurações específicas do repositório Git, como configurações do usuário, URLs de remotos e outras opções de configuração.
### description
    Geralmente é um arquivo de texto que pode ser usado para descrever o repositório.
### HEAD
    Aponta para o branch atual em que você está trabalhando.
### hooks
    É uma pasta que contém scripts que podem ser executados em determinados eventos do Git, como pré-commit, pós-commit, pré-push, etc.
### index
    É um arquivo que funciona como uma área de preparação (staging area) temporária, armazenando informações sobre as mudanças que serão adicionadas ao próximo commit.
### info
    Pode conter arquivos com informações extras sobre o repositório.
### logs
    Mantém informações sobre as ações realizadas no repositório, como histórico de commits, atualizações de refs, etc.
### objects
    É onde os objetos do Git são armazenados. Os objetos são os blobs (conteúdo de arquivos), trees (árvore de diretórios) e commits que compõem o repositório.
### refs
    Armazena referências a branches, tags e HEAD.
#### refs/heads
     Contém ponteiros para as branches do repositório
#### refs/tags
     Armazena as referências para as tags criadas no repositório.