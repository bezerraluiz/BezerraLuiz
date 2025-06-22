# Como fazer a Snake Animation funcionar

Para que a snake animation funcione no seu perfil do GitHub, siga estes passos:

## 🚨 PROBLEMA COMUM: Por que a snake não funciona?

### Principais motivos:
1. **Repositório não existe**: Precisa criar repositório `bezerraluiz/bezerraluiz`
2. **Workflow não configurado**: Arquivo `.github/workflows/snake.yml` não existe
3. **Permissões incorretas**: GitHub Actions precisa de permissão para escrever
4. **Branch incorreta**: Workflow pode estar configurado para branch errada

## ✅ SOLUÇÃO PASSO A PASSO

### 1. Criar o repositório do perfil
- Acesse [GitHub](https://github.com) e faça login
- Clique em "New repository"
- Nome do repositório: `bezerraluiz` (exatamente igual ao seu username)
- Marque como **público**
- Marque "Add a README file"
- Clique em "Create repository"

### 2. Configurar permissões do GitHub Actions
- No seu repositório `bezerraluiz/bezerraluiz`
- Vá em **Settings** > **Actions** > **General**
- Em "Workflow permissions", selecione **"Read and write permissions"**
- Marque **"Allow GitHub Actions to create and approve pull requests"**
- Clique em **Save**

### 3. Adicionar o workflow
- No repositório, clique em **"Add file"** > **"Create new file"**
- Nome do arquivo: `.github/workflows/snake.yml`
- Cole o conteúdo do arquivo que criamos

### 4. Executar manualmente (primeiro teste)
- Vá em **Actions** no seu repositório
- Clique no workflow "Generate Snake"
- Clique em **"Run workflow"**
- Aguarde a execução (2-3 minutos)

### 5. Verificar se funcionou
- Após executar, vá em **Settings** > **Pages**
- Em "Source", selecione **"Deploy from a branch"**
- Branch: **output**, Folder: **/ (root)**
- A snake estará disponível em:
  - `https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg`

## 🔧 TROUBLESHOOTING

### Se ainda não funcionar:
1. **Verifique se o repositório é público**
2. **Confirme se as permissões do Actions estão corretas**
3. **Execute o workflow manualmente primeiro**
4. **Aguarde até 24h para a primeira execução automática**

### URLs alternativas para testar:
```markdown
<!-- Versão simples -->
![Snake animation](https://github.com/bezerraluiz/bezerraluiz/blob/output/github-contribution-grid-snake.svg)

<!-- Versão com fallback -->
<img src="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg" alt="Snake animation" />

<!-- Versão responsiva (atual no README) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg">
</picture>
```

### 💡 DICA IMPORTANTE:
A snake animation pode demorar até 24 horas para aparecer pela primeira vez. Depois disso, será atualizada automaticamente todos os dias.

## 🎯 ALTERNATIVA RÁPIDA
Se a snake não funcionar, você pode usar outros elementos visuais:
- Contribution Graph (já funciona)
- GitHub Stats (já funciona)  
- GitHub Trophies (já funciona)
- Activity Graph (já funciona)
