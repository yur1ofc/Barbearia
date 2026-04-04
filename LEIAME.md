# CorteNobre Barbearia — Site Completo 💈

## O que está incluso

Um site profissional e completo para barbearia, pronto para apresentar e vender.

---

## 📁 Arquivos

```
barbearia/
└── index.html    → Site completo (único arquivo, sem dependências locais)
```

---

## ✅ Seções do Site

| Seção | Descrição |
|---|---|
| 🏠 **Hero** | Banner principal com foto, título impactante e botões de ação |
| 🏆 **Sobre** | História da barbearia, diferenciais, badge de anos de experiência |
| ✂️ **Serviços** | 6 serviços com descrição e preços |
| 🖼️ **Galeria** | Grid fotográfico com efeito hover |
| 👨 **Barbeiros** | Cards com foto, especialidade e redes sociais |
| ⭐ **Avaliações** | 3 depoimentos de clientes reais |
| 💳 **Planos** | 3 planos mensais (Essencial, Premium, Black) |
| 📅 **Agendamento** | Formulário que abre WhatsApp com dados preenchidos |
| 📍 **Localização** | Endereço, horários e mapa |
| 🔗 **Footer** | Links, horários, redes sociais e copyright |

---

## 🎨 Design

- **Estilo:** Dark premium com dourado — elegante e masculino
- **Fontes:** Playfair Display (títulos) + Barlow (corpo)
- **Cursor personalizado** em desktops
- **Animações** suaves de entrada (scroll reveal)
- **Marquee** animado com os serviços
- **100% responsivo** (mobile, tablet, desktop)

---

## ⚙️ Como personalizar

### Dados da barbearia
Abra o `index.html` e substitua:

```
"CorteNobre"         → Nome da barbearia
"Salvador - BA"      → Cidade
"5571999999999"      → Número do WhatsApp (DDD + número, sem espaços)
"Rua da Barra, 420"  → Endereço real
"@cortenobre.ba"     → @Instagram
"contato@cortenobre.com.br" → E-mail
```

### Preços
Busque por `R$` no arquivo e atualize os valores.

### Fotos
As imagens usam Unsplash (gratuitas). Substitua as URLs por fotos reais da barbearia para melhor resultado.

### Cores (variáveis CSS no topo do `<style>`)
```css
--gold: #C9A84C;      /* dourado principal */
--black: #0A0A0A;     /* fundo escuro */
--light: #F5F0E8;     /* texto claro */
```

---

## 🚀 Como publicar

### Opção 1 — Gratuito (Netlify Drop)
1. Acesse **netlify.com/drop**
2. Arraste a pasta `barbearia/` para a página
3. Site no ar em segundos com URL grátis

### Opção 2 — Hospedagem tradicional
1. Faça upload do `index.html` via FTP/cPanel para a pasta `public_html/`
2. Conecte ao domínio da barbearia

### Opção 3 — GitHub Pages (grátis)
1. Crie um repositório no GitHub
2. Faça upload do `index.html`
3. Ative GitHub Pages nas configurações

---

## 💰 Sugestão de precificação para vender

| Entrega | Preço sugerido |
|---|---|
| Site básico (só personalizar dados) | R$ 500 – R$ 800 |
| Site + domínio + 1 ano de hospedagem | R$ 900 – R$ 1.400 |
| Site + configuração Google Meu Negócio | R$ 1.200 – R$ 1.800 |
| Pacote completo + manutenção mensal | R$ 1.500 + R$ 150/mês |

---

## 📱 Recursos técnicos

- HTML5 + CSS3 + JavaScript vanilla
- Zero dependências externas (apenas Google Fonts via CDN)
- Cursor customizado
- IntersectionObserver para animações
- Formulário conectado ao WhatsApp
- Scroll suave
- Meta tags SEO configuradas

---

*Site desenvolvido para portfólio e revenda. Personalize com os dados do cliente antes de entregar.*
