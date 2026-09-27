# gds-mobile-engine-
 Game Dev Studio Mobile — plataforma Android para criação de jogos com IA, scripts, edição 2D/3D, testes e geração de APK.
CONFIGURAÇÃO DE PERMISSÕES

Integração GitHub + ChatGPT

Projeto: Game Dev Studio Mobile

Configurar a integração autorizada do GitHub com o ChatGPT para permitir que o ChatGPT trabalhe no repositório:

"joaodiasjorge4-pixel/gds-mobile-engine-"

1. Acesso ao repositório

Conceder acesso ao repositório:

"gds-mobile-engine-"

Permitir que a integração:

- leia arquivos;
- crie arquivos;
- atualize arquivos;
- substitua arquivos quando necessário;
- crie diretórios por meio da criação de arquivos;
- consulte branches;
- crie branches;
- consulte commits;
- crie commits;
- atualize referências de branches;
- consulte workflows do GitHub Actions;
- acompanhe execuções de build;
- consulte logs de execução;
- consulte artefatos gerados pelo build.

2. Permissão principal necessária

A permissão mais importante é:

Repository contents: Read and write

Essa permissão é necessária para permitir que a integração publique e atualize o código do Game Dev Studio no repositório.

3. GitHub Actions

Permitir acesso necessário para:

- executar workflows;
- acompanhar workflows;
- consultar o resultado dos builds;
- consultar jobs;
- consultar logs;
- consultar artefatos;
- baixar os artefatos gerados;
- repetir um workflow que tenha falhado, quando permitido.

Objetivo:

"Código → GitHub → GitHub Actions → Build Android → Validação → APK"

4. Branches e commits

Permitir, quando autorizado pelo proprietário do repositório:

- leitura de branches;
- criação de branch;
- criação de commits;
- atualização de branch;
- consulta de histórico de commits.

5. Segurança

Não conceder acesso desnecessário.

A integração NÃO deve solicitar:

- senha da conta;
- senha do GitHub;
- token pessoal informado manualmente;
- código de autenticação;
- dados bancários;
- acesso a outros repositórios que não sejam necessários.

Sempre utilizar a autorização oficial do GitHub.

6. Objetivo final

O objetivo dessa integração é permitir que o ChatGPT continue o desenvolvimento do:

Game Dev Studio Mobile

incluindo:

1. publicação do código;
2. atualização do projeto;
3. configuração do Android;
4. configuração do GitHub Actions;
5. compilação remota;
6. testes;
7. validação dos APKs;
8. geração do "GameDevStudio.apk";
9. geração do "MasterInstaller.apk";
10. disponibilização dos artefatos para download.

7. Fluxo desejado

Projeto Game Dev Studio
        ↓
GitHub
        ↓
gds-mobile-engine-
        ↓
GitHub Actions
        ↓
Build Android remoto
        ↓
Testes e validação
        ↓
GameDevStudio.apk
        +
MasterInstaller.apk
        ↓
Download
        ↓
Instalação oficial do Android

8. Regra importante

A integração deve trabalhar somente dentro das permissões autorizadas pelo proprietário da conta e do repositório.

Não deve tentar contornar mecanismos de segurança do GitHub ou do Android.

O objetivo é utilizar a infraestrutura oficial para desenvolvimento, compilação, testes e distribuição do aplicativo.


quero de permissão 