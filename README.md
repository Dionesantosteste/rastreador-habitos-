# 📱 Rastreador de Hábitos - Habit Tracker

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Aplicativo web minimalista para rastreamento de hábitos com tema dark mode neon**

[Demo]((https://seu-usuario.github.io/rastreador-habitos/) • [Funcionalidades](#funcionalidades) • [Instalação](#instalação) • [Como Usar](#como-usar)

</div>

---

## ✨ Funcionalidades

### 🎯 Core Features
- ✅ **Rastreamento Diário** - Marque hábitos como completos a cada dia
- 📊 **Dashboard Intuitivo** - Visualize seu progresso em tempo real
- 🔥 **Sistema de Streaks** - Acompanhe dias consecutivos de sucesso
- 📅 **Mini Calendário** - Marque hábitos dos últimos 7 dias retroativamente
- 🎨 **Dark Mode Neon** - Design moderno com paleta roxa/ciano

### 📈 Tipos de Metas
- **Diário** - Hábitos para fazer todo dia
- **Segunda a Sexta** - Hábitos apenas em dias úteis
- **Fins de Semana** - Hábitos para sábado e domingo
- **Meta de Dias** - Ex: "Estudar por 240 dias"
- **Meta de Livros** - Ex: "Ler 12 livros no ano"

### 📸 Compartilhamento Social
- 📷 **Captura de Foto** - Use a câmera frontal
- 🖼️ **Upload de Galeria** - Escolha foto existente
- 🎯 **Overlay de Progresso** - Estatísticas estilo Instagram
- 💾 **Download Direto** - Salve e compartilhe nas redes

### 📊 Progresso e Estatísticas
- 📈 Calendário de últimos 28 dias
- 🔢 Taxa de conclusão percentual
- 🏆 Badges de recompensa
- 📉 Progresso individual por hábito

---

## 🚀 Instalação

### Opção 1: Download Direto

1. Baixe o arquivo `habit-tracker.html`
2. Abra no seu navegador favorito
3. Pronto! Funciona offline via localStorage

### Opção 2: Clone o Repositório

```bash
# Clone o repositório
git clone https://dionesantosteste.github.io/rastreador-habitos-/

# Entre na pasta
cd rastreador-habitos

# Abra no navegador
open habit-tracker.html
# ou
start habit-tracker.html
```

### Opção 3: GitHub Pages

Acesse diretamente: `https://SEU-USUARIO.github.io/rastreador-habitos/`

---

## 📖 Como Usar

### 1️⃣ Primeiro Acesso - Onboarding

Ao abrir pela primeira vez:
- Escolha sua área de foco (Saúde, Produtividade, etc.)
- Defina quantos hábitos quer criar (1-10)
- Configure cada hábito com nome e identidade

### 2️⃣ Dashboard Diário

**Stats Cards:**
- 🔢 **Hábitos** - Total de hábitos criados
- 🔥 **Seguidos** - Dias consecutivos
- ✅ **Completo** - % de conclusão do dia

**Mini Calendário:**
- Últimos 7 dias visíveis
- Clique em qualquer dia para marcar retroativamente
- Pontinho verde indica dias com progresso

**Lista de Hábitos:**
- Checkbox para marcar como completo
- Progresso em tempo real
- Botão de compartilhar (aparece após completar)

### 3️⃣ Compartilhar Progresso

1. Marque o hábito como completo
2. Clique em "Compartilhar Progresso"
3. Escolha: Câmera, Galeria ou Voltar
4. Tire/escolha uma foto
5. Baixe a imagem com overlay de estatísticas
6. Compartilhe nas redes sociais!

### 4️⃣ Visualizar Progresso

- Acesse a aba "Progresso"
- Veja calendário de 28 dias
- Taxa de conclusão geral
- Progresso individual por hábito

---

## 🎨 Design

### Paleta de Cores (Dark Mode)

```css
--bg: #121212         /* Fundo principal */
--surface: #1E1E1E    /* Cards e componentes */
--primary: #BB86FC    /* Roxo neon */
--accent: #03DAC6     /* Ciano neon */
--error: #CF6679      /* Coral */
--text: #FFFFFF       /* Texto branco */
```

### Fontes
- **DM Sans** - Interface geral (Google Fonts)
- **Crimson Pro** - Números e títulos (Google Fonts)

---

## 💾 Armazenamento de Dados

Todos os dados são salvos localmente no **localStorage** do navegador:

```javascript
{
  habits: [],          // Lista de hábitos
  completions: {},     // Registro de conclusões
  books: {},          // Livros (para meta de leitura)
  selectedDate: "",   // Data selecionada
  onboardingData: {}  // Dados do onboarding
}
```

### Backup Manual

1. Abra o Console (F12)
2. Execute: `localStorage.getItem('habitTrackerData')`
3. Copie o JSON e salve em arquivo .txt

### Restaurar Backup

1. Abra o Console (F12)
2. Execute: `localStorage.setItem('habitTrackerData', 'SEU_JSON_AQUI')`
3. Recarregue a página

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilização com variáveis e grid
- **Vanilla JavaScript** - Lógica (sem frameworks)
- **localStorage API** - Persistência de dados
- **getUserMedia API** - Acesso à câmera
- **html2canvas** - Geração de imagens com overlay

---

## 📱 Compatibilidade

### Navegadores Suportados
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Dispositivos
- ✅ Desktop (Windows, Mac, Linux)
- ✅ Mobile (iOS Safari, Chrome Android)
- ✅ Tablet

### Recursos Necessários
- **localStorage** - Obrigatório
- **getUserMedia** - Opcional (para câmera)
- **HTTPS** - Recomendado (para câmera)

---

## 🔒 Privacidade

- ✅ **100% Local** - Dados nunca saem do seu dispositivo
- ✅ **Sem Tracking** - Zero analytics ou cookies
- ✅ **Offline-First** - Funciona sem internet
- ✅ **Sem Servidor** - Não envia dados para ninguém

---

## 🐛 Problemas Conhecidos

### Câmera não funciona
- **Causa:** Precisa de HTTPS ou localhost
- **Solução:** Use "Da Galeria" ou hospede com HTTPS

### Dados sumiram
- **Causa:** localStorage foi limpo pelo navegador
- **Solução:** Faça backup manual regularmente

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido por Dione Herveson Mende dos Santos

---

## 📞 Contato

- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: dioneheverson@hotmail.com

---

## 🙏 Agradecimentos

- Inspiração de design: Atomic Habits por James Clear
- Ícones: Heroicons
- Fontes: Google Fonts
- Comunidade open source 💜

---

<div align="center">

**⭐ Se este projeto te ajudou, considere dar uma estrela! ⭐**

Made with 💜 and ☕

</div>
