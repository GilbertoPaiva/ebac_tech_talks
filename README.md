# EBAC Tech Talks

Landing page para um evento fictício de tecnologia, desenvolvida como projeto prático do curso da EBAC.

## 📋 Descrição

Projeto educacional de uma landing page moderna e responsiva para um evento de tecnologia fictício. A página demonstra técnicas de desenvolvimento front-end, incluindo contador regressivo em tempo real, animações e design responsivo.

## 🚀 Funcionalidades

- ⏰ Contador regressivo dinâmico em JavaScript
- 📱 Design totalmente responsivo
- ✨ Animações ao rolar a página (AOS - Animate On Scroll)
- 🎨 Interface moderna e clean
- 📍 Estrutura de landing page para eventos

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **SASS/SCSS** - Pré-processador CSS para estilização
- **JavaScript** - Lógica do contador regressivo
- **Parcel** - Bundler para desenvolvimento e build
- **AOS** - Biblioteca de animações ao scroll
- **Google Fonts (Roboto)** - Tipografia

## 📁 Estrutura do Projeto

```
EBAC_TALKS/
├── src/
│   ├── index.html          # Página principal
│   ├── images/             # Imagens do projeto
│   ├── scripts/
│   │   └── main.js         # JavaScript principal
│   └── styles/
│       ├── main.scss       # Arquivo principal de estilos
│       ├── _variables.scss # Variáveis SASS
│       ├── _hero.scss      # Estilos da seção hero
│       ├── _event.scss     # Estilos das seções de eventos
│       └── components/
│           ├── _buttons.scss
│           └── _infos_bar.scss
├── package.json
└── sharp.config.json
```

## 🔧 Instalação e Uso

### Pré-requisitos

- Node.js instalado
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/ebac-talks.git
```

2. Entre na pasta do projeto:
```bash
cd EBAC_TALKS
```

3. Instale as dependências:
```bash
npm install
```

### Executando o Projeto

#### Modo Desenvolvimento

Para rodar o projeto em modo de desenvolvimento com hot reload:

```bash
npm run dev
```

O projeto estará disponível em `http://localhost:1234`

#### Build de Produção

Para gerar os arquivos otimizados para produção:

```bash
npm run build
```

Os arquivos de produção serão gerados na pasta `dist/`

## 📅 Informações do Evento (Fictício)

- **Local:** Allianz Parque - Barra Funda - São Paulo
- **Data:** 12/12/2026 às 19h
- **Preço:** A partir de R$ 120,00

> **Nota:** Este é um projeto educacional. O evento e todas as informações são fictícias, criadas apenas para fins de demonstração e aprendizado.

## 🎨 Personalização

Para personalizar cores e estilos, edite o arquivo `src/styles/_variables.scss`

Para alterar a data do evento, modifique a variável `dataDoEvento` em `src/scripts/main.js`:

```javascript
const dataDoEvento = new Date("Dec 12, 2026 19:00:00");
```

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm test` - Executa os testes (não configurado)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## 📄 Licença

Este é um projeto educacional desenvolvido como parte do curso da EBAC.

## 🎓 Objetivo do Projeto

Este projeto foi desenvolvido com fins educacionais para demonstrar:
- Uso de SASS/SCSS para estilização
- Manipulação do DOM com JavaScript
- Criação de contadores regressivos
- Implementação de animações com AOS
- Bundling com Parcel
- Boas práticas de desenvolvimento front-end

## ✨ Autor

Desenvolvido com ❤️ durante o curso EBAC

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
