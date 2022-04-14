# my personal settings to vscode
```json
{
    // configurações gerais
    "workbench.startupEditor": "none", // ( declara o que aparecerá ao iniciar o vscode )
    "files.autoSave": "afterDelay", // ( habilita o salvamento automático )
    "explorer.confirmDelete": false, // ( desabilita a pergunta de confirmar para deletar um arquivo )
    "git.enableSmartCommit": true, // ( habilita a função start commit )
    "javascript.updateImportsOnFileMove.enabled": "always", // ( habilita função de atualizar os imports de um arquivo js )

    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },

    "files.associations": {
        ".sequelizerc": "javascript",
        ".stylelintrc": "json",
        ".prettierrc": "json",
        "*.tsx": "typescriptreact",
        ".env.*": "dotenv"
    },

    // configurações de sugestões
    "javascript.suggest.autoImports": true, // ( habilita sugestões para autoimports em arquivos javascript )
    "typescript.suggest.autoImports": true, // ( habilita sugestões para autoimports em arquivos typescript )
    
    // configurações de extensões
    "extensions.ignoreRecommendations": false,
    "extensions.autoUpdate": true,
    
    // configurações de terminal
    "terminal.integrated.fontSize": 13, // ( define o tamanho da fonte do terminal )
    "terminal.integrated.fontFamily": "Fira Code", // ( define a fonte do terminal )

    // configurações de temas e ícones
    "workbench.colorTheme": "Dracula", // ( define o tema do vscode )
    "workbench.iconTheme": "material-icon-theme", // ( define o tema de ícones de arquivos )
    "material-icon-theme.showWelcomeMessage": false, // ( desabilita a mensagem de bem-vindo ao inicar o vscode )
    
    // configurações de polacode
    "polacode.backgroundColor": "#1f1e22",
    
    // configurações de fontes
    "editor.fontFamily": "Fira Code", // ( declara qual a fonte do editor )
    "editor.fontSize": 14, // ( altera o tamanho da fonte do editor )
    "editor.lineHeight": 2, // ( define a altura da linha )
    "editor.fontLigatures": true, // ( habilita o uso de fontes ligatures )

    // configurações de ícones
    "material-icon-theme.folders.associations": {
        "infra": "app",
        "entities": "class",
        "domain": "class",
        "schemas": "class",
        "typeorm": "database",
        "repositories": "mappings",
        "http": "container",
        "migrations": "tools",
        "modules": "components",
        "implementations": "core",
        "dtos": "typescript",
        "fakes": "mock",
        "websockets": "pipe",
        "protos": "pipe",
        "grpc": "pipe",
        "providers": "include",
        "subscribers": "messages",
        "useCases": "controller",
        "kafka": "scripts",
        "mappers": "meta",
        "_shared": "shared",
        "eslint-config": "tools",
        "kube": "kubernetes"
    },
  
    "material-icon-theme.files.associations": {
        "ormconfig.json": "database",
        "tsconfig.json": "tune",
        "*.proto": "3d",
        "*.webpack.js": "webpack"
    },
  
    "material-icon-theme.languages.associations": {
        "dotenv": "tune"
    },
    
    // configurações atualmente não utilizadas
    // 
    // "editor.rulers": [80, 120],
    // "editor.formatOnSave": false,
    // "window.zoomLevel": 0,
    // "editor.tabSize": 2,
    // "terminal.integrated.shell.linux": "/bin/zsh",
    // "editor.semanticHighlighting.enabled": false,
    // "explorer.compactFolders": false,
    // "editor.renderLineHighlight": "gutter",
    // "workbench.editor.labelFormat": "short",
    // "breadcrumbs.enabled": true,
    // "editor.parameterHints.enabled": false,
    // "explorer.confirmDragAndDrop": false,
    //
    // "files.exclude": {
    //     "**/.git": true,
    //     "**/.svn": true,
    //     "**/.hg": true,
    //     "**/CVS": true,
    //     "**/.DS_Store": true,
    //     "**/Thumbs.db": true,
    //     "**/node_modules": true
    // },
    //
    // "[prisma]": {
    //     "editor.formatOnSave": true
    // },
    //
    // "emmet.syntaxProfiles": { "javascript": "jsx" },
    // "emmet.includeLanguages": { "javascript": "javascriptreact" },
    // "gitlens.codeLens.recentChange.enabled": false,
    // "gitlens.codeLens.authors.enabled": false,
    // "gitlens.codeLens.enabled": false,
    // "terminal.integrated.shell.osx": "/bin/zsh",
    // "liveshare.featureSet": "insiders",
    // "typescript.tsserver.log": "off",
    // "material-icon-theme.activeIconPack": "nest",
    // "screencastMode.onlyKeyboardShortcuts": true,
    // "workbench.colorTheme": "Omni",
    // "window.menuBarVisibility": "toggle"
    // "typescript.updateImportsOnFileMove.enabled": "never",
    // "tabnine.experimentalAutoImports": true,
    // "cSpell.enableFiletypes": [
    //     "!asciidoc",
    //     "!c",
    //     "!cpp",
    //     "!csharp",
    //     "!go",
    //     "!handlebars",
    //     "!haskell",
    //     "!jade",
    //     "!java",
    //     "!latex",
    //     "!php",
    //     "!pug",
    //     "!python",
    //     "!restructuredtext",
    //     "!rust",
    //     "!scala",
    //     "!scss"
    // ],
    // "cSpell.language": "en,pt",
    // "editor.suggestSelection": "first",
    // "codesnap.backgroundColor": "transparent",
    // "codesnap.transparentBackground": true,
    // "codesnap.boxShadow": "0 0 0",
    // "liveServer.settings.donotVerifyTags": true,
    // "cSpell.userWords": [
    //   "chakra",
    //   "middlewares",
    //   "prefetch",
    //   "rocketseat",
    //   "upsert"
    // ],
    // "workbench.productIconTheme": "fluent-icons",
    // "terminal.integrated.showExitAlert": false,
}
```
