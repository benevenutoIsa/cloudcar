# CloudCar - Concessionária de Veículos 🚗

Site completo e moderno de concessionária de carros, desenvolvido com React e Tailwind CSS.

➡️ O projeto também está em um container Docker com toda a aplicação. Criamos uma máquina virtual na nuvem da Oracle e subimos a aplicação através do Docker nessa máquina, podendo ser acessada pelo link:
http://136.248.107.114:8080

## 🚀 Tecnologias Utilizadas

- **React 19** - Biblioteca JavaScript para construção de interfaces
- **Vite** - Build tool rápido e moderno
- **Tailwind CSS** - Framework CSS utility-first
- **React Icons** - Biblioteca de ícones (Feather Icons)
- **JavaScript (JSX)** - Sem TypeScript

## 📋 Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

## 🔧 Instalação

1. Clone o repositório ou navegue até a pasta do projeto:
```bash
cd cloudcar
```

2. Instale as dependências:
```bash
npm install
```

## ▶️ Executando o Projeto

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
```

O site estará disponível em `http://localhost:5173`

## 🏗️ Build para Produção

Para criar a versão otimizada para produção:

```bash
npm run build
```

Para visualizar a versão de produção:

```bash
npm run preview
```

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:

- ✅ Mobile (320px - 640px)
- ✅ Tablet (641px - 1024px)
- ✅ Desktop (1025px+)

## 🎨 Estrutura do Projeto

```
cloudcar/
├── src/
│   ├── componentes/
│   │   └── layout/
│   │       ├── Header.jsx          # Menu de navegação responsivo
│   │       ├── Hero.jsx            # Seção principal com background
│   │       ├── BenefitsSection.jsx # Grid de benefícios
│   │       ├── VehicleCard.jsx     # Card individual de veículo
│   │       ├── CatalogSection.jsx  # Catálogo de veículos
│   │       ├── CTASection.jsx      # Call to Action
│   │       └── Footer.jsx          # Rodapé
│   ├── App.jsx                     # Componente principal
│   ├── App.css                     # Estilos globais
│   ├── index.css                   # Tailwind CSS
│   └── main.jsx                    # Entry point
├── index.html
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── package.json
```

## 🎯 Funcionalidades

### Header
- Menu responsivo com hamburger no mobile
- Navegação suave entre seções
- Logo CloudCar com destaque

### Hero Section
- Background com imagem de carro esportivo
- Título e subtítulo impactantes
- Botões call-to-action com scroll suave

### Benefícios
- Grid com 4 benefícios principais
- Ícones animados
- Cards com hover effects

### Catálogo
- 4 veículos premium
- Especificações detalhadas (CV, combustível, km)
- Badges de ano
- Botões de ação

### Call to Action
- Botões de contato (telefone e email)
- Design moderno com gradiente
- Links funcionais

### Footer
- Informações da empresa
- Copyright dinâmico
- Design limpo e profissional

## 🎨 Paleta de Cores

- **Primária**: #3B82F6 (Azul vibrante)
- **Secundária**: #1F2937 (Cinza escuro)
- **Background**: #F9FAFB (Cinza claro)
- **Texto**: Branco e tons de cinza

## 📝 Licença

© 2024 CloudCar - Todos os direitos reservados

## 👨‍💻 Desenvolvido com ❤️

Site desenvolvido como projeto acadêmico com foco em design moderno e responsividade total.
