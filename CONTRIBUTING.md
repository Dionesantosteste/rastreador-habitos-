# 🤝 Guia de Contribuição

Obrigado por considerar contribuir com o Rastreador de Hábitos! 

## 📋 Como Contribuir

### 1. Reportar Bugs

Se encontrou um bug:
- Verifique se já não foi reportado nas [Issues](https://github.com/SEU-USUARIO/rastreador-habitos/issues)
- Abra uma nova issue com:
  - Descrição clara do problema
  - Passos para reproduzir
  - Comportamento esperado vs atual
  - Screenshots (se aplicável)
  - Navegador e versão

### 2. Sugerir Features

Para novas funcionalidades:
- Abra uma issue com tag "enhancement"
- Descreva a feature detalhadamente
- Explique o caso de uso
- Mostre exemplos (se possível)

### 3. Enviar Pull Requests

#### Processo:

1. **Fork** o repositório
2. **Clone** seu fork localmente
3. **Crie uma branch** para sua feature
   ```bash
   git checkout -b feature/minha-feature
   ```
4. **Faça suas alterações**
5. **Teste** tudo completamente
6. **Commit** com mensagens claras
   ```bash
   git commit -m "Adiciona funcionalidade X"
   ```
7. **Push** para seu fork
   ```bash
   git push origin feature/minha-feature
   ```
8. **Abra um Pull Request**

#### Boas Práticas:

- ✅ Código limpo e comentado (em português)
- ✅ Mantenha o estilo de código existente
- ✅ Teste em múltiplos navegadores
- ✅ Atualize a documentação se necessário
- ✅ Um PR por feature/fix

## 📝 Padrões de Código

### JavaScript
- Use português nos comentários e variáveis
- Indentação: 4 espaços
- Use `const` e `let`, não `var`
- Funções: camelCase
- Constantes: UPPER_SNAKE_CASE

### CSS
- BEM naming ou classes descritivas
- Mobile-first
- Use variáveis CSS quando possível

### HTML
- Semântico
- Acessível (ARIA labels)
- Indentação consistente

## 🎨 Design Guidelines

- Mantenha o tema dark mode neon
- Use as cores da paleta definida
- Transitions suaves (0.3s ease)
- Mobile-first responsive

## 🧪 Testes

Antes de enviar PR, teste:
- ✅ Criação de hábitos
- ✅ Marcar/desmarcar completions
- ✅ Navegação entre telas
- ✅ Persistência no localStorage
- ✅ Responsividade mobile
- ✅ Funcionalidade de câmera/galeria

## 📚 Recursos

- [Documentação do localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- [getUserMedia API](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

## ❓ Dúvidas?

Abra uma issue ou entre em contato!

---

**Obrigado por contribuir! 💜**
