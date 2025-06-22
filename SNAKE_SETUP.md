# Como fazer a Snake Animation funcionar

Para que a snake animation funcione no seu perfil do GitHub, siga estes passos:

## 1. Criar o repositório do perfil
- Crie um repositório com o mesmo nome do seu usuário GitHub (`bezerraluiz`)
- Torne o repositório público
- Adicione um README.md

## 2. Configurar o GitHub Actions
- Copie o arquivo `.github/workflows/snake.yml` que foi criado para o seu repositório
- Faça commit e push das alterações

## 3. Aguardar a geração
- O GitHub Actions vai executar automaticamente
- A snake animation será gerada na branch `output`
- As imagens estarão disponíveis em:
  - `https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg`
  - `https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake-dark.svg`

## 4. URLs finais para usar no README
```markdown
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/bezerraluiz/bezerraluiz/output/github-contribution-grid-snake.svg">
</picture>
```

O workflow executa automaticamente a cada 12 horas e sempre que você fizer um push para a branch master.
