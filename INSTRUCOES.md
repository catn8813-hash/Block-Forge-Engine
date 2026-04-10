# Como Gerar o APK da BlockForge Engine

  ## PASSO 1 — Criar conta no GitHub (gratuito)
  Acesse https://github.com e crie sua conta.

  ## PASSO 2 — Criar repositório
  1. Clique no "+" no topo > "New repository"
  2. Nome: blockforge-engine
  3. Visibilidade: Public
  4. Clique em "Create repository"

  ## PASSO 3 — Subir os arquivos
  1. Na página do repositório, clique em "uploading an existing file"
  2. Arraste TODOS os arquivos desta pasta (com as subpastas)
  3. Mensagem de commit: "Add engine"
  4. Clique em "Commit changes"

  IMPORTANTE: Suba as pastas assim:
  - www/index.html
  - www/error.html
  - res/android/provider_paths.xml
  - .github/workflows/build-apk.yml
  - config.xml
  - package.json
  - .gitignore

  ## PASSO 4 — Compilar o APK
  1. No repositório, clique em "Actions"
  2. Clique em "Build BlockForge APK" na lista
  3. Clique em "Run workflow" (botão verde) > "Run workflow"
  4. Aguarde 5-10 minutos

  ## PASSO 5 — Baixar o APK
  1. Clique no workflow concluído (bolinha verde)
  2. Role para baixo até "Artifacts"
  3. Clique em "BlockForge-APK" para baixar
  4. Descompacte e instale o .apk no Android

  ## Permissões que o APK terá:
  - Salvar projetos em /Documents/BlockForge/
  - Salvar imagens em /Pictures/BlockForge/
  - Acessar galeria do Android
  - Funcionar 100% offline

  ## Observação
  Na primeira instalação, o Android vai pedir permissão de arquivos.
  Aceite todas as permissões para o salvamento funcionar.
  