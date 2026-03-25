Resumo — Versionamento de Código e Deploy de Aplicações

1. Versionamento vs. Backup

O versionamento de código registra cada alteração feita no projeto, incluindo informações como autor, data e motivo da mudança. Isso permite acompanhar o histórico completo do desenvolvimento e voltar para versões anteriores quando necessário.

Já o backup é apenas uma cópia do projeto em um determinado momento, sem registro detalhado das alterações.

Diferenças principais:

* Versionamento: histórico completo, rastreabilidade e colaboração entre desenvolvedores.
* Backup: apenas cópia de segurança, sem controle de mudanças.

O uso de versionamento evita problemas como perda de código, sobrescrita de arquivos e conflitos entre membros da equipe.

2. Versionamento Semântico (SemVer)

O Versionamento Semântico (SemVer é um padrão utilizado para identificar versões de software de forma clara.

Ele utiliza o formato:
MAJOR.MINOR.PATCH

* MAJOR: mudanças grandes que quebram compatibilidade.
* MINOR: adição de novas funcionalidades sem quebrar compatibilidade.
* PATCH: correções de bugs ou pequenos ajustes.

Exemplos:

* 1.0.0 → 1.1.0: nova funcionalidade adicionada.
* 1.1.0 → 1.1.1: correção de bug.
* 1.1.0 → 2.0.0: mudança incompatível com versões anteriores.

3. Git e Controle de Versão

O Git é um sistema de controle de versão distribuído utilizado para rastrear mudanças no código e facilitar o trabalho colaborativo entre desenvolvedores.

Ele permite:

* registrar alterações por meio de commits
* sincronizar o código com plataformas como GitHub
* marcar versões importantes através de tags

Boas práticas ao usar Git:

* fazer commits frequentes
* escrever mensagens claras explicando as mudanças;
* utilizar branches para organizar o desenvolvimento;
* realizar merges cuidadosos para evitar conflitos.

4. Branches e Merge

As branches são ramificações do código que permitem desenvolver novas funcionalidades sem alterar diretamente a versão principal do projeto.

Exemplos de branches comuns:

* **main:** versão principal e estável do projeto.
* **develop:** integração de novas funcionalidades.
* **feature:** desenvolvimento de novas funções.
* **hotfix:** correção rápida de problemas.

O merge é o processo de unir alterações de uma branch com outra.
Quando duas alterações modificam a mesma parte do código, podem ocorrer **conflitos**, que precisam ser resolvidos manualmente.

5. Deploy e Hospedagem

O deploy é o processo de publicar a aplicação para que ela possa ser acessada na internet.

Esse processo pode incluir etapas como:

* compilação do código;
* execução de testes;
* publicação em um servidor.

Normalmente existem três ambientes principais:

* Local: ambiente de desenvolvimento do programador.
* Staging: ambiente de testes antes da publicação final.
* Produção: versão final disponível para os usuários.

Uma ferramenta muito utilizada é a Vercel que permite:

* deploy automático conectado ao GitHub
* hospedagem de sites e aplicações modernas;
* uso de CDN global e **serverless functions**.

6. Atividade Prática

A atividade proposta consiste em:

1. Criar um **repositório no GitHub**.
2. Desenvolver uma **página HTML básica**.
3. Versionar o projeto utilizando **Git** e criar **tags de versão**.
4. Realizar o **deploy da aplicação no Vercel**.
5. Documentar o processo com **prints e links do repositório e do site publicado**.

✅ Conclusão:
O versionamento de código com **Git** é essencial para organizar o desenvolvimento, manter histórico de mudanças e facilitar o trabalho em equipe. Já o **deploy** permite publicar a aplicação na internet de forma automatizada e segura.

https://fish-academy.vercel.app/