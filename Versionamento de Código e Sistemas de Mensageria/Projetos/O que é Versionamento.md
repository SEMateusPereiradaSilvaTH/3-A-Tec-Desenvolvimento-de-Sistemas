# O QUE É VERSIONAMENTO?
   
    Versionamento na área de TI é o processo de controlar e registrar as mudanças feitas em um projeto ao longo do tempo, seja em código-fonte, documentos ou arquivos de configuração. Ele permite acompanhar alterações, identificar quem modificou o quê e quando, além de possibilitar o retorno a versões anteriores, se necessário.

    Essa prática é essencial para garantir organização, colaboração eficiente entre equipes e maior segurança no desenvolvimento de sistemas, sendo amplamente aplicada por meio de ferramentas como Git e plataformas como GitHub.

# QUE TIPO DE VERSIONAMENTO EXISTEM?
    
### Versionamento Centralizado

    DesktopRemoto --- Push ----> ServerRemoto

    Nesse modelo, existe um servidor central que armazena todo o histórico de versões. Os desenvolvedores enviam e recebem alterações desse único local.

### Versionamento Distribuído

    DesktopRemoto --- Commit ---> RepositorioRemoto --- Push ---> ServerRemoto

    Cada desenvolvedor possui uma cópia completa do repositório, incluindo todo o histórico de versões. As alterações podem ser feitas localmente e depois sincronizadas com outros repositórios.

# O QUE É COMMIT E PUSH?

Ex: DesktopRemoto --- Commit ---> RepositorioRemoto --- Push ---> ServerRemoto

### Commit

    O commit é o registro de uma alteração no repositório.
    Quando você faz um commit, está salvando oficialmente as mudanças realizadas nos arquivos, junto com uma mensagem descritiva explicando o que foi modificado.

### Push

    O push é o envio dos commits locais para um repositório remoto.
    Ele sincroniza suas alterações com outras pessoas da equipe, publicando suas mudanças em plataformas.

# SOFTWARE DE VERSIONAMENTO

### Centralizado

    Nesse modelo, existe um único servidor que armazena todo o histórico do projeto.

    Apache Subversion (SVN) – Um dos mais conhecidos sistemas centralizados.

    CVS (Concurrent Versions System) – Um dos primeiros sistemas populares de versionamento.

    Perforce Helix Core – Muito utilizado em grandes empresas e projetos de jogos.

    Team Foundation Version Control (TFVC) – Sistema centralizado da Microsoft.

### Distribuído

    Nesse modelo, cada desenvolvedor possui uma cópia completa do repositório.

    Git – O mais utilizado atualmente no mundo.

    Mercurial – Simples e eficiente, similar ao Git.

    azaar – Desenvolvido para ser fácil de usar e flexível.

    Fossil – Sistema distribuído que já inclui wiki e controle de tickets.

