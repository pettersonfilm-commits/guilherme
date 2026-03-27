# Design System - Guilherme Videomaker Portfolio

## 1. Identidade Tipográfica
- **Fonte Principal (H1 / Destaques):** Fonte Sans-Serif Geométrica (ex: `Syncopate`), peso **Extremely Bold (900)**, em CAIXA ALTA (Uppercase). Letter-spacing extremamente justo (`tracking-tighter`).
- **Tagline / Texto Secundário:** Fonte Serif elegante e leve (ex: `Playfair Display`), peso **Light/Regular (300/400)**, criando contraste "Premium vs. Técnico".

## 2. Identidade de Cor e Superfície (Contraste Cinematográfico Invertido)
- **Fundo:** Branco Puro (`#FFFFFF`).
- **Texto Principal:** Preto Puro (`#000000`) para máximo contraste.
- **Texto Secundário (Tagline / Body Text):** Cinza Escuro (`#555555`).
- **Cor de Destaque / Interativa:** Degradê Ciano-Roxo.

## 3. Identidade de Layout e Componentes
- **Fotos e Vídeos:** Layouts de grade assimétrica (bento-box) ou seções fullscreen expansivas. Os vídeos devem ter `border-radius` sutil (ex: 8px) e sombras suaves em tons de cinza para destacar no fundo branco.
- **Depoimentos (Testimonials):** Cards minimalistas com fundo ligeiramente off-white (ex: `#FAFAFA`), aspas elegantes em Serif e o nome do cliente em degradê, mantendo um design limpo e espaçado (whitespace generoso).
- **Stack de Tecnologias:** Layout minimalista listando ferramentas (Premiere, After Effects, DaVinci Resolve) em grid com ícones e hover effects.

## 4. Identidade de Movimento & Animação (GSAP / Framer Motion)
- **Entrada Cinematográfica (Hero):**
  1. Reveal do fundo branco puro.
  2. Tipografia 'GUILHERME' surge em 'stagger', letra a letra, de baixo para cima.
  3. Fita 3D (Ciano-Roxo) surge tecendo as letras (2.5D de alta performance).
- **Cursor Magnético:** Personalizado, imita a flecha 3D. Estica em hover de fotos e vídeos.
- **Scroll (Parallax):**
  - Mídias (Vídeos/Fotos) têm parallax interno sutil dinâmico com o scroll.
- **Reveal on Scroll:**
  - Cards e seções surgem com fade-up (`opacity: 0 -> 1`, `y: 50 -> 0`).
- **Hover States:** Degradê ciano-roxo e zoom suave (scale `1.05`) nas thumbnails.

## 5. Stack Técnico (Desenvolvimento)
- Next.js (App Router)
- Tailwind CSS
- GSAP & Framer Motion
- Lenis (Smooth Scrolling)
