# 🚀 Como Subir para o GitHub - Guia Passo a Passo

## Opção 1: Via Interface Web (Mais Fácil) 🌐

### Passo 1: Criar Repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no **+** (canto superior direito) → **New repository**
3. Preencha:
   - **Repository name:** `rastreador-habitos` (ou outro nome)
   - **Description:** `Aplicativo web para rastreamento de hábitos com dark mode neon`
   - **Public** (para que outros possam ver)
   - ✅ Marque **Add a README file** (vamos substituir depois)
   - **Add .gitignore:** None (já temos um)
   - **Choose a license:** MIT License
4. Clique em **Create repository**

### Passo 2: Upload dos Arquivos

1. No repositório criado, clique em **Add file** → **Upload files**
2. Arraste ou selecione estes arquivos:
   - ✅ `habit-tracker.html` (arquivo principal)
   - ✅ `README.md`
   - ✅ `.gitignore`
   - ✅ `CONTRIBUTING.md`
   - ✅ `CHANGELOG.md`
   - ✅ `AUDIT_REPORT.md` (opcional - documentação)
   - ✅ `FIXES_APPLIED.md` (opcional - documentação)
3. Escreva uma mensagem de commit: `feat: initial commit - rastreador de hábitos v1.0.0`
4. Clique em **Commit changes**

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** (engrenagem)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **Save**
5. Aguarde ~1 minuto
6. Seu app estará disponível em: `https://SEU-USUARIO.github.io/rastreador-habitos/habit-tracker.html`

### Passo 4: Adicionar Link no README

1. Clique em `README.md` no repositório
2. Clique no ✏️ (Edit this file)
3. Na linha do Demo, substitua:
   ```markdown
   [Demo](#) → [Demo](https://SEU-USUARIO.github.io/rastreador-habitos/habit-tracker.html)
   ```
4. Na seção GitHub Pages, substitua:
   ```markdown
   https://SEU-USUARIO.github.io/rastreador-habitos/
   ```
5. Commit as mudanças

### ✅ Pronto! Seu projeto está no GitHub!

---

## Opção 2: Via Git CLI (Mais Profissional) 💻

### Pré-requisitos
- Git instalado ([git-scm.com](https://git-scm.com/))
- Conta no GitHub

### Passo 1: Criar Repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no **+** → **New repository**
3. Preencha:
   - **Repository name:** `rastreador-habitos`
   - **Description:** `Aplicativo web para rastreamento de hábitos`
   - **Public**
   - ❌ **NÃO** marque "Add a README file"
4. Clique em **Create repository**

### Passo 2: Configurar Git Local

Abra o terminal/prompt na pasta do projeto:

```bash
# Inicializar repositório Git
git init

# Adicionar todos os arquivos
git add .

# Primeiro commit
git commit -m "feat: initial commit - rastreador de hábitos v1.0.0"

# Renomear branch para main
git branch -M main

# Conectar ao repositório remoto (substitua SEU-USUARIO)
git remote add origin https://github.com/SEU-USUARIO/rastreador-habitos.git

# Enviar para o GitHub
git push -u origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** → **Pages**
2. Source: `main` / `/ (root)`
3. Save

### ✅ Pronto!

---

## 📋 Checklist Final

Antes de considerar completo:

- [ ] Todos os arquivos enviados
- [ ] README.md atualizado com seu username
- [ ] LICENSE com seu nome
- [ ] GitHub Pages ativado e funcionando
- [ ] Link do demo testado e funcionando
- [ ] Descrição do repositório preenchida
- [ ] Topics adicionadas (habit-tracker, javascript, dark-mode, etc.)

---

## 🎨 Melhorias Opcionais

### Adicionar Topics (Tags)

No repositório, clique em ⚙️ (ao lado de About) e adicione:
- `habit-tracker`
- `javascript`
- `html5`
- `css3`
- `dark-mode`
- `productivity`
- `vanilla-javascript`
- `localstorage`

### Criar Release v1.0.0

1. No repositório, clique em **Releases**
2. **Create a new release**
3. Tag: `v1.0.0`
4. Title: `Rastreador de Hábitos v1.0.0 - Lançamento Inicial`
5. Descrição: Copie do CHANGELOG.md
6. **Publish release**

### Adicionar Screenshot

1. Tire um print do app funcionando
2. Salve como `screenshot.png`
3. Crie uma pasta `docs/` no repositório
4. Faça upload da imagem
5. Adicione no README.md:
   ```markdown
   ![Screenshot](docs/screenshot.png)
   ```

### Adicionar Badge de Build Status

No README.md, adicione mais badges:
```markdown
![Maintained](https://img.shields.io/badge/Maintained-Yes-green)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
```

---

## 🐛 Problemas Comuns

### "Permission denied"
- Verifique se está logado no GitHub
- Use HTTPS ao invés de SSH se não tiver chave configurada

### "Remote origin already exists"
```bash
git remote remove origin
git remote add origin https://github.com/SEU-USUARIO/rastreador-habitos.git
```

### GitHub Pages não funciona
- Aguarde 5-10 minutos
- Verifique se o arquivo se chama exatamente `habit-tracker.html`
- Tente renomear para `index.html` (se quiser ser a página inicial)

---

## 📞 Precisa de Ajuda?

- [GitHub Docs](https://docs.github.com)
- [Git Tutorial](https://git-scm.com/docs/gittutorial)
- [GitHub Pages Guide](https://pages.github.com/)

---

**Boa sorte com seu projeto! 🚀💜**
