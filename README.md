# Let me Ask

Projeto desenvolvido durante o evento **NLW Agents** da **Rocketseat**
Confira também o [Servidor](https://github.com/LucasEmmanoel06/nlw-agents-server) do Let me Ask

## 🚀 Tecnologias Utilizadas

- **React 19** - Biblioteca principal para construção da interface
- **TypeScript** - Linguagem tipada para desenvolvimento
- **Vite** - Build tool e servidor de desenvolvimento
- **React Router DOM** - Navegação entre páginas
- **TanStack Query** - Gerenciamento de estado e cache de dados
- **Tailwind CSS** - Framework CSS para estilização
- **Shadcn/UI** - Componentes UI pré-construídos
- **Radix UI** - Primitivos de componentes acessíveis
- **Lucide React** - Biblioteca de ícones
- **Biome** - Linter e formatter de código

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── ui/          # Componentes UI reutilizáveis
├── lib/
│   └── utils.ts     # Funções utilitárias
├── pages/
│   ├── create-room.tsx
│   └── room.tsx
├── app.tsx          # Configuração principal da aplicação
└── main.tsx         # Entry point da aplicação
```

## 🔧 Configuração e Instalação

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/LucasEmmanoel06/nlw-agents-web.git
cd let-me-ask
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

### Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera o build de produção
- `npm run preview` - Preview do build de produção

## 🎨 Padrões de Projeto

- **Component-based Architecture** - Componentes reutilizáveis e modulares
- **Custom Hooks** - Lógica reutilizável com React Hooks
- **Route-based Code Splitting** - Páginas organizadas por rotas
- **Utility-first CSS** - Estilização com Tailwind CSS
- **Type Safety** - Tipagem rigorosa com TypeScript
- **Query Management** - Gerenciamento de estado com TanStack Query

## 🔧 Configurações Importantes

- **Alias de Importação**: Configurado `@` para apontar para `./src`
- **Shadcn/UI**: Configurado com tema "new-york" e variáveis CSS
- **Tailwind CSS**: Integrado via plugin do Vite
- **Biome**: Configurado para linting e formatação de código

## 📝 Funcionalidades

- Sistema de salas (rooms)
- Navegação entre páginas
- Interface responsiva e moderna
- Componentes reutilizáveis

---

Desenvolvido com ❤️ durante o **NLW Agents** da **Rocketseat**
