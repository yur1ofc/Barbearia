# RHD Cortes — Site Completo + Painel Admin 💈

## Acesso ao Painel Admin

**Senha padrão:** `rhd2025`

Para mudar a senha: abra `index.html`, procure por `ADMIN_PASS = 'rhd2025'` e troque.

---

## Como acessar o Admin

1. No site, clique no botão **⚙ Admin** (canto superior direito)
2. No celular: menu hamburguer → Admin
3. Digite a senha: `rhd2025`
4. Faça as alterações e clique em **💾 Salvar Todas as Alterações**

---

## O que o Admin controla

### 🔧 Controles (ligar/desligar)
| Toggle | O que faz |
|---|---|
| **Modo Ordem de Chegada** | Suspende agendamentos online, exibe aviso em vermelho no site e bloqueia o formulário |
| **Exibir Promoção** | Ativa a seção de promoção na página |

### 🎯 Promoção
- Título, descrição, preço original, preço promocional e serviço incluído
- Aparece como banner dourado no topo e seção dedicada

### 💰 Preços dos Serviços
- Corte Masculino
- Barba Modelada
- Combo (Corte + Barba)
- Hot Towel Shave
- Pigmentação
- Hidratação Capilar

### 🕐 Horário de Funcionamento
- Horário de abertura e fechamento

---

## Logo RHD

O site usa um **SVG inline** estilizado com a identidade RHD (dourado, circular).

**Para usar a logo real enviada:**
1. Salve o arquivo da logo como `logo-rhd.png` na mesma pasta
2. No `index.html`, substitua as linhas com `data:image/svg+xml...` pelo caminho:
   ```
   src="logo-rhd.png"
   ```
   Busque por `nav-logo-img` e `hero-logo-img` no arquivo.

---

## Personalizar

| O que | Onde no código |
|---|---|
| Número WhatsApp | Troque `5577999999999` pelo número real |
| Senha admin | `ADMIN_PASS = 'rhd2025'` |
| Endereço | Já está: Rua Ruy Barbosa, 405 — Centro, Barreiras BA |
| Instagram | Já está: @rhd_cortes |

---

## Como publicar

### Netlify (grátis — mais fácil)
1. Acesse **netlify.com/drop**
2. Arraste a pasta `rhd/`
3. Site no ar em segundos

### Hospedagem tradicional
- Faça upload do `index.html` via FTP/cPanel para `public_html/`

---

## Dados salvos automaticamente
O painel admin usa **localStorage** — as configurações ficam salvas no navegador do dono. 
Para compartilhar configurações entre dispositivos, considere upgrade para versão com backend.
