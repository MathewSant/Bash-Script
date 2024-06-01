Título: Configuração de Diretórios, Grupos e Usuários

    Criação de Diretórios e Definição de Permissões
        O script cria quatro diretórios: /publico, /adm, /ven e /sec.
        As permissões para esses diretórios são definidas da seguinte forma:
            /publico tem permissões 777 (acesso total para todos os usuários).
            /adm, /ven e /sec têm permissões 770 (acesso total apenas para o dono e o grupo).

    Criação de Grupos
        Três grupos são criados: GRP_ADM, GRP_VEN e GRP_SEC.
        Os diretórios são atribuídos aos seus respectivos grupos:
            /adm é atribuído ao grupo GRP_ADM.
            /ven é atribuído ao grupo GRP_VEN.
            /sec é atribuído ao grupo GRP_SEC.

    Criação de Usuários
        Nove usuários são criados e atribuídos aos seus respectivos grupos:
            Usuários carlos, maria e joao são adicionados ao grupo GRP_ADM.
            Usuários debora, sebastiana e roberto são adicionados ao grupo GRP_VEN.
            Usuários josefina, amanda e rogerio são adicionados ao grupo GRP_SEC.
        Para cada usuário, são especificados:
            Nome completo.
            Diretório home.
            Shell de login /bin/bash.
            Senha criptografada (todos os usuários usam a senha "Senha123").

    Mensagem de Conclusão
        O script exibe a mensagem "Finalizado!" ao término de sua execução.
