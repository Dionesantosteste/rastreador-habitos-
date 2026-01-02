# 📝 Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/),
e este projeto adere ao [Semantic Versioning](https://semver.org/lang/pt-BR/).

## [1.0.0] - 2024-12-29

### ✨ Adicionado
- Sistema completo de onboarding
- Dashboard com 3 cards de estatísticas (Hábitos, Streak, % Completo)
- Mini calendário de 7 dias para marcar retroativamente
- Compartilhamento com câmera/galeria
- Overlay de progresso estilo Instagram
- Tema dark mode neon completo
- 5 tipos de frequência de hábitos
- Meta de dias e meta de livros
- Sistema de streaks
- Progresso de últimos 28 dias
- Badge de recompensa
- Persistência com localStorage
- Responsivo mobile-first

### 🔧 Corrigido
- Try-catch no localStorage para prevenir crashes
- Validação de nome obrigatório ao criar hábito
- Bug de streak contando dias futuros
- Cores de texto invisíveis no dark mode

### 🎨 Design
- Paleta dark mode neon (roxo #BB86FC + ciano #03DAC6)
- Fontes: DM Sans + Crimson Pro
- Animações suaves
- Efeitos de glow em elementos ativos

### 📱 Compatibilidade
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile iOS/Android

### 🔒 Segurança
- 100% local, sem envio de dados
- Sem tracking ou analytics
- Funciona offline

---

## [Futuro] - Planejado

### 🎯 v1.1.0
- [ ] Notificações push
- [ ] Themes customizáveis
- [ ] Exportar dados (JSON/CSV)
- [ ] Estatísticas mensais/anuais
- [ ] Modo light (opcional)

### 🎯 v1.2.0
- [ ] PWA completo (Service Worker)
- [ ] Sincronização via Firebase (opcional)
- [ ] Grupos de hábitos
- [ ] Tags e categorias

### 🎯 v2.0.0
- [ ] Refactor em TypeScript
- [ ] Sistema de achievements
- [ ] Gráficos avançados
- [ ] Comparação com outros usuários (anônimo)

---

[1.0.0]: https://github.com/SEU-USUARIO/rastreador-habitos/releases/tag/v1.0.0
