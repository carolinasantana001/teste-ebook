# Jornada Quaresmal: O Grande Recomeço

Um PWA (Progressive Web App) elegante e contemplativo para acompanhar a jornada quaresmal de 40 dias.

## 📱 Características

### Estrutura Completa de 40 Dias
- **Fase I (D01-D10)**: A Desconstrução do Ego e o Chamado ao Deserto
- **Fase II (D11-D20)**: O Atrito no Deserto e a Batalha Interior
- **Fase III (D21-D30)**: O Transbordamento da Caridade
- **Fase IV (D31-D40)**: A Ascensão ao Calvário e o Alvorecer da Ressurreição

### Conteúdo de Cada Dia
- 📖 **Versículo**: Passagem bíblica com referência
- 💭 **Reflexão**: Meditação profunda sobre o tema do dia
- ✨ **Ação Prática**: Tarefa concreta para viver a Quaresma
- 📝 **Minhas Anotações**: Espaço para reflexões pessoais (salvo localmente)
- 🎵 **Áudio do Dia**: Suporte para meditações guiadas (estrutura pronta)

### Três Pilares da Quaresma
Cada dia está associado a um dos três pilares:
- **Oração** (40% do conteúdo)
- **Jejum** (35% do conteúdo)
- **Esmola** (25% do conteúdo)

## 🎨 Design

### Filosofia de Design: Minimalismo Espiritual
- **Tipografia**: Playfair Display (títulos) + Lora (corpo)
- **Paleta de Cores**: Marrom/Dourado/Branco (elegância sóbria)
- **Espaçamento**: Generoso, criando espaço para contemplação
- **Animações**: Suaves e contemplativas

### Cores
- Fundo: `#F5F1E8` (pergaminho)
- Primário: `#8B7355` (marrom terroso)
- Acentos: `#D4A574` (dourado)
- Texto: `#2C2C2C` (cinza escuro)

## 🚀 Recursos PWA

- ✅ **Manifest.json**: Instalável em dispositivos
- ✅ **Service Worker**: Suporte offline completo
- ✅ **Responsive Design**: Funciona em mobile, tablet e desktop
- ✅ **LocalStorage**: Anotações salvas localmente
- ✅ **Meta Tags**: Otimizado para compartilhamento

## 🛠️ Tecnologia

- **Frontend**: React 19 + TypeScript
- **Estilização**: Tailwind CSS 4 + Custom CSS
- **Roteamento**: Wouter
- **Componentes**: shadcn/ui
- **Build**: Vite

## 📂 Estrutura do Projeto

```
client/
├── public/
│   ├── manifest.json          # Configuração PWA
│   └── service-worker.js      # Offline support
├── src/
│   ├── data/
│   │   └── journeyDays.ts     # 40 dias de conteúdo
│   ├── pages/
│   │   ├── Home.tsx           # Índice de fases
│   │   └── DayView.tsx        # Visualização de um dia
│   ├── App.tsx                # Rotas e setup
│   └── index.css              # Estilos globais
└── index.html                 # HTML base com meta tags PWA
```

## 🎯 Como Usar

### Começar a Jornada
1. Acesse a página inicial
2. Clique em "Começar Minha Jornada" ou selecione um dia específico
3. Leia o versículo, reflexão e ação prática
4. Escreva suas anotações pessoais
5. Navegue para o próximo dia

### Salvar Anotações
- As anotações são salvas automaticamente no localStorage
- Cada dia tem seu próprio espaço de anotações
- Clique "Salvar Anotações" para confirmar

### Instalar como App
- Em navegadores suportados, procure por "Instalar" ou "Adicionar à tela inicial"
- O app funcionará offline com todos os 40 dias disponíveis

## 📊 Estrutura Teológica

A jornada segue uma progressão teológica clara:

1. **Desconstrução** (D01-D10): Reconhecer a fragilidade e necessidade de Deus
2. **Atrito** (D11-D20): Enfrentar tentações e batalhas interiores
3. **Transbordamento** (D21-D30): Transbordar de caridade e amor
4. **Ressurreição** (D31-D40): Oferecer a cruz e ressuscitar em Cristo

## 🔧 Desenvolvimento

### Instalar Dependências
```bash
pnpm install
```

### Executar em Desenvolvimento
```bash
pnpm dev
```

### Build para Produção
```bash
pnpm build
```

## 📱 Compatibilidade

- ✅ Chrome/Edge (versão 90+)
- ✅ Firefox (versão 88+)
- ✅ Safari (versão 14+)
- ✅ Navegadores móveis (iOS Safari, Chrome Mobile)

## 💾 Dados

- Todas as anotações são armazenadas localmente no navegador
- Nenhum dado é enviado para servidores
- Limpar dados do navegador apagará as anotações

## 🙏 Propósito

Este PWA foi criado para acompanhar a Quaresma de forma contemplativa e estruturada, oferecendo um espaço sagrado para reflexão diária, oração, jejum e esmola.

> "Porque quando sou fraco, então é que sou forte." — 2 Coríntios 12:10

---

**Versão**: 1.0.0  
**Última atualização**: Fevereiro 2026
