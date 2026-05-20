# Chaos Arquitetura e Urbanismo — versão GitHub/local

Esta versão foi ajustada para rodar como site estático no GitHub Pages, sem Supabase, sem login e sem banco externo.

## Como usar

1. Crie um repositório no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Ative o GitHub Pages no repositório, usando a branch principal e a pasta raiz.
4. Abra a URL gerada pelo GitHub Pages.

## Onde ficam os dados?

As propostas e configurações ficam no `localStorage` do navegador. Isso significa:

- Funciona sem Supabase.
- Não precisa de login.
- Cada computador/navegador terá seus próprios dados.
- Para não perder nada, use o botão **Backup** dentro do app e guarde o arquivo `.json`.
- Para levar para outro computador, use **Importar** e selecione o backup `.json`.

## Limitações do modo local

- Sem usuários/equipe online.
- Sem banco de dados compartilhado.
- Sem upload real de anexos em nuvem.
- Anexos ficam registrados por nome/tamanho, mas o arquivo original precisa ser guardado na pasta ou drive do projeto.

## Arquivo principal

- `index.html`
