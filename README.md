# Style Guide & Token System - Itaú Typography & Palette

Este repositório/documento contém a especificação do sistema de design, guias de estilo visual e tokens de tipografia e cores baseados na identidade visual do **Itaú**.

---

## 🎨 Paleta de Cores (Color Palette)

A paleta é dividida em escalas funcionais de marca, tons secundários, tons neutros (*Dark*, *Light*) e tons de destaque (*Feedback/Alert*).

### 1. Primária (Orange Core)
| Token / Nome | Hex Code | Uso Recomendado |
| :--- | :--- | :--- |
| **Primário -1** | `#CC4E00` | Sombras, estados de hover/pressed em botões primários |
| **Primário** | `#FF6200` | Cor institucional, elementos de destaque principal |
| **Primário +1** | `#FF8133` | Hover suave, fundos claros com tom da marca |

### 2. Secundária (Blue Accent)
| Token / Nome | Hex Code | Uso Recomendado |
| :--- | :--- | :--- |
| **Secundário** | `#539AE9` | Elementos interativos secundários, links |
| **Secundário +1** | `#267FE3` | Foco, hover de elementos secundários |

### 3. Escala Dark (Neutros Escuros)
| Token / Nome | Hex Code | Uso Recomendado |
| :--- | :--- | :--- |
| **Dark +1** | `#0B0A0A` | Fundo de alto contraste, texto em superfícies muito claras |
| **Dark** | `#262323` | Cor principal de texto (body text, headings) |
| **Dark -1** | `#D3DDE4` | Bordas, divisores e linhas de separação |

### 4. Escala Light (Neutros Claros)
| Token / Nome | Hex Code | Uso Recomendado |
| :--- | :--- | :--- |
| **Light -1** | `#FFFFFF` | Branco puro (fundo de cards, texto em superfícies escuras) |
| **Light** | `#F2F5F7` | Fundo principal da aplicação (background neutro) |
| **Light +1** | `#D3DDE4` | Superfícies secundárias, estados desabilitados |

### 5. Destaque / Alerta
| Token / Nome | Hex Code | Uso Recomendado |
| :--- | :--- | :--- |
| **Alert / Accent** | `#FF2705` | Feedback de erro, notificações críticas e badges de aviso |

---

## 📐 Escala Tipográfica (Typography Scale)

A hierarquia visual tipográfica do projeto é estruturada nas seguintes especificações de tamanho:

| Nível | Tamanho (px) | Exemplo de Aplicação |
| :--- | :--- | :--- |
| **H1** | `40px` | Títulos principais de páginas e banners principais |
| **H2** | `34px` | Títulos de seções e modais |
| **H3** | `28px` | Subtítulos de seções e cabeçalhos de cards |
| **H4** | `24px` | Títulos de widgets, componentes e agrupamentos |
| **H5** | `18px` | Títulos pequenos, labels de destaque e subseções |

---

## 💻 Exemplo de Tokens CSS / Tailwind

```css
:root {
  /* Brand Primary */
  --color-primary-dark: #CC4E00;
  --color-primary: #FF6200;
  --color-primary-light: #FF8133;

  /* Brand Secondary */
  --color-secondary: #539AE9;
  --color-secondary-dark: #267FE3;

  /* Neutrals Dark */
  --color-dark-plus: #0B0A0A;
  --color-dark: #262323;
  --color-dark-minus: #D3DDE4;

  /* Neutrals Light */
  --color-light-minus: #FFFFFF;
  --color-light: #F2F5F7;
  --color-light-plus: #D3DDE4;

  /* Accent / Feedback */
  --color-alert: #FF2705;

  /* Font Sizes */
  --font-h1: 40px;
  --font-h2: 34px;
  --font-h3: 28px;
  --font-h4: 24px;
  --font-h5: 18px;
}
```

---

## 📝 Licença & Uso

Este guia foi elaborado para padronizar os tokens de design do projeto com base nas especificações da marca Itaú.
