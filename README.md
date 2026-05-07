# WordGuess 🎮

Um jogo interativo de adivinhação de palavras construído com **React**, **TypeScript** e **Vite**.

## 📋 Status

🚀 **Em Produção** - Projeto em desenvolvimento ativo

## 📖 Descrição

WordGuess é um jogo onde o jogador tenta adivinhar uma palavra secreta letra por letra. A cada tentativa, o jogo fornece feedback sobre se a letra está correta ou não.

## 🛠️ Stack Tecnológico

- **Frontend**: React 19.2.5
- **Linguagem**: TypeScript
- **Build Tool**: Vite
- **Estilos**: CSS Modules
- **Runtime**: Node.js

## 📂 Estrutura do Projeto

```
src/
├── components/           # Componentes React
│   ├── Button/          # Botão reutilizável
│   ├── Header/          # Cabeçalho da aplicação
│   ├── Input/           # Campo de entrada
│   ├── Letter/          # Exibição de letras
│   ├── LettersUsed/     # Letras utilizadas
│   └── Tip/             # Dica para o jogador
├── utils/
│   └── words.ts         # Lista de palavras do jogo
├── App.tsx              # Componente principal
└── main.tsx             # Ponto de entrada

```

## 🚀 Como Executar

### Instalação

```bash
npm install
```

### Desenvolvimento

```bash
npm run dev
```

### Build para Produção

```bash
npm run build
```

### Preview de Produção

```bash
npm run preview
```

## 🎮 Gameplay

1. O jogador clica em "Iniciar Jogo"
2. Uma palavra secreta é selecionada aleatoriamente
3. O jogador adivinha uma letra por vez
4. Feedback é dado sobre acertos e erros
5. Contar as tentativas e gerenciar os erros

## 📝 Features em Desenvolvimento

- ✅ Seleção aleatória de palavras
- ✅ Validação de letras
- ✅ Histórico de letras utilizadas
- 🔄 Sistema de pontuação
- 🔄 Níveis de dificuldade
- 🔄 Persistência de dados
- 🔄 Interface responsiva

## 📄 Licença

MIT

## 👨‍💻 Autor

Desenvolvido como projeto de aprendizado.

---

**Última atualização**: Maio de 2026
