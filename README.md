# ☕ Coffee Delivery 

Um e-commerce de cafés especiais com carrinho de compras e checkout completo.

## 🚀 Tecnologias

- **ReactJS** - Biblioteca principal
- **TypeScript** - Tipagem estática
- **Styled Components** - Estilização
- **React Hook Form** - Formulários
- **Zod** - Validação de dados
- **Context API** - Gerenciamento de estado
- **Phosphor Icons** - Ícones

## ✨ Funcionalidades

✔️ Catálogo de cafés  
✔️ Adicionar/remover itens do carrinho  
✔️ Ajustar quantidades  
✔️ Formulário de endereço com validação  
✔️ Seleção de método de pagamento  
✔️ Página de confirmação de pedido  

## 🎨 Design System

```ts
export const defaultTheme = {
  // Cores base
  white: '#FFFFFF',
  background: '#FAFAFA',
  
  // Cores de texto
  'base-title': '#272221',
  'base-subtitle': '#403937',
  'base-text': '#574F4D',
  
  // Cores de componentes
  'purple-dark': '#4B2995',
  purple: '#8047F8',
  'yellow-dark': '#C47F17',
  yellow: '#DBAC2C',
};
```

## 📦 Estrutura do Projeto

```
src/
├── assets/
├── components/
│   ├── Cart/
│   ├── CoffeeCard/
│   ├── Counter/
│   ├── DeliveryInfo/
│   ├── Header/
│   ├── PaymentMethod/
│   └── Success/
├── contexts/
├── pages/
│   ├── Checkout/
│   ├── Home/
│   └── Success/
├── styles/
└── App.tsx
```

## 🛠️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/rocketseat-education/ignite-challenge-solution-reactjs-coffee-delivery.git
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor:
```bash
npm run dev
```

4. Acesse no navegador:
```
http://localhost:3000
```

---

Desenvolvido como parte do programa Ignite da [Rocketseat](https://www.rocketseat.com.br/) 🚀
