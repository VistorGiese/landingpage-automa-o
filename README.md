# 🤖 Inner IA - Landing Page

Landing page profissional para a **Inner IA**, agência especializada em criação de agentes de Inteligência Artificial para automação de atendimento empresarial.

## 📋 Sobre o Projeto

Este projeto foi desenvolvido para apresentar os serviços da Inner IA, focados em:
- Agentes de IA integrados ao WhatsApp e Telegram
- Atendimento automatizado 24/7
- Qualificação inteligente de leads
- Agendamento automatizado
- Redução de até 50% nos custos operacionais

## 🎨 Paleta de Cores

```css
Azul Primário: #0066FF - Tecnologia e confiança
Roxo Secundário: #8B5CF6 - Inovação e criatividade
Verde Accent: #10B981 - Crescimento e sucesso
Cinza Escuro: #1F2937 - Profissionalismo
Branco: #FFFFFF - Clareza e modernidade
```

## 📁 Estrutura do Projeto

```
pagina-do-projeto/
├── index.html          # Estrutura HTML completa
├── style.css           # Estilos e design responsivo
├── script.js           # Interatividade e animações
└── README.md           # Esta documentação
```

## 🚀 Seções da Landing Page

### ✅ Implementadas

1. **Header/Navegação**
   - Menu fixo com scroll suave
   - Versão mobile responsiva
   - Links para todas as seções

2. **Hero Section**
   - Título impactante
   - CTAs principais
   - Stats visuais (50% redução, 24/7, +10 clientes)
   - Ilustração animada

3. **Problemas/Dores**
   - 5 cards com problemas comuns
   - Alert box destacando custos
   - Ícones SVG personalizados

4. **Solução**
   - Apresentação da Inner IA
   - Lista de benefícios
   - Chat mockup animado
   - Layout lado a lado

5. **Tipos de Agentes**
   - 3 cards principais (Atendimento, Qualificação, Agendamento)
   - Card destacado (Mais Popular)
   - Features detalhadas

6. **Benefícios**
   - 6 benefícios numerados
   - Design clean e profissional
   - CTA para conversão

7. **Equipe**
   - Vitor Giese
   - Adriano Rigonato
   - Formações e experiências
   - Skills e estatísticas

8. **Como Funciona**
   - 4 passos do processo
   - Visualização linear
   - Informações de preço
   - CTA para orçamento

9. **Contato**
   - Formulário completo
   - Features de atendimento
   - Validação de campos
   - Máscara de telefone

10. **FAQ**
    - 6 perguntas frequentes
    - Accordion funcional
    - Respostas detalhadas

11. **Footer**
    - Informações da empresa
    - Links úteis
    - Redes sociais
    - Copyright

## 🎯 Como Usar

### 1. Abrir o Projeto

Simplesmente abra o arquivo `index.html` em qualquer navegador moderno:
- Chrome
- Firefox
- Safari
- Edge

### 2. Visualizar Online

Para hospedar gratuitamente:

**Opção 1 - Vercel:**
```bash
npm i -g vercel
vercel
```

**Opção 2 - Netlify:**
1. Acesse [netlify.com](https://www.netlify.com)
2. Arraste a pasta do projeto
3. Pronto!

**Opção 3 - GitHub Pages:**
1. Crie repositório no GitHub
2. Faça upload dos arquivos
3. Ative GitHub Pages nas configurações

## ✏️ Personalizações Necessárias

### 1. Adicionar Logo

Substitua a linha no `index.html`:
```html
<div class="logo">
    <h1>Inner<span class="highlight">IA</span></h1>
</div>
```

Por:
```html
<div class="logo">
    <img src="seu-logo.png" alt="Inner IA" height="40">
</div>
```

### 2. Adicionar Fotos da Equipe

Substitua os placeholders no `index.html`:
```html
<div class="image-placeholder">
    <!-- SVG atual -->
</div>
```

Por:
```html
<img src="foto-vitor.jpg" alt="Vitor Giese">
```

### 3. Configurar Formulário

No `script.js`, substitua o código de simulação por integração real:

**Opção A - E-mail (FormSubmit):**
```html
<form action="https://formsubmit.co/seu@email.com" method="POST">
```

**Opção B - API Própria:**
```javascript
const response = await fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(data)
});
```

**Opção C - WhatsApp Direct:**
```javascript
const message = `Nome: ${data.name}\nEmail: ${data.email}\n...`;
const whatsappUrl = `https://wa.me/5500000000000?text=${encodeURIComponent(message)}`;
window.open(whatsappUrl, '_blank');
```

### 4. Atualizar Informações de Contato

No footer do `index.html`, atualize:
```html
<li>📧 contato@inneria.com.br</li>
<li>📱 WhatsApp: (00) 00000-0000</li>
```

### 5. Adicionar Analytics

Antes do `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎨 Customizações de Estilo

### Alterar Cores

No `style.css`, modifique as variáveis:
```css
:root {
    --primary: #0066FF;      /* Sua cor primária */
    --secondary: #8B5CF6;    /* Sua cor secundária */
    --accent: #10B981;       /* Sua cor de destaque */
}
```

### Alterar Fontes

Substitua no `index.html` (dentro do `<head>`):
```html
<link href="https://fonts.googleapis.com/css2?family=SuaFonte:wght@400;600;700&display=swap" rel="stylesheet">
```

E no `style.css`:
```css
:root {
    --font-primary: 'SuaFonte', sans-serif;
}
```

## 📱 Responsividade

O site é totalmente responsivo e funciona em:
- ✅ Desktop (1920px+)
- ✅ Laptop (1440px)
- ✅ Tablet (768px)
- ✅ Mobile (375px+)

## 🚀 Performance

### Otimizações Implementadas:
- ✅ CSS minificado e organizado
- ✅ Animações otimizadas
- ✅ Lazy loading preparado
- ✅ Imagens SVG inline (leves)
- ✅ JavaScript modular

### Próximas Otimizações:
- [ ] Comprimir imagens quando adicionadas
- [ ] Adicionar Service Worker para PWA
- [ ] Implementar lazy loading de seções
- [ ] Minificar HTML/CSS/JS para produção

## 🔧 Funcionalidades JavaScript

- ✅ Scroll suave entre seções
- ✅ Menu mobile funcional
- ✅ Animações ao scroll (Intersection Observer)
- ✅ FAQ accordion
- ✅ Validação de formulário
- ✅ Máscara de telefone
- ✅ Header sticky

## 📊 SEO

### Já Implementado:
- ✅ Meta tags essenciais
- ✅ Estrutura semântica HTML5
- ✅ Alt text preparado para imagens
- ✅ URLs descritivas (#solucao, #beneficios)

### Para Adicionar:
```html
<!-- Open Graph (Facebook/LinkedIn) -->
<meta property="og:title" content="Inner IA - Agentes Inteligentes">
<meta property="og:description" content="Reduza custos em 50% com IA">
<meta property="og:image" content="https://seusite.com/preview.jpg">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Inner IA">
```

## 🐛 Troubleshooting

### Formulário não envia?
- Verifique se implementou um backend
- Teste com FormSubmit.co primeiro
- Verifique console do navegador (F12)

### Animações não funcionam?
- Verifique se JavaScript está carregado
- Teste em outro navegador
- Limpe cache (Ctrl+Shift+R)

### Layout quebrado no mobile?
- Verifique viewport meta tag
- Teste em DevTools (F12 > Toggle Device)
- Valide CSS no W3C Validator

## 📞 Suporte

Desenvolvido para **Inner IA**
- Vitor Giese - Desenvolvedor Pleno IA
- Adriano Rigonato - Cientista de Dados

---

## 🎉 Próximos Passos

1. [ ] Adicionar logo da empresa
2. [ ] Adicionar fotos da equipe
3. [ ] Configurar formulário de contato
4. [ ] Atualizar informações de contato
5. [ ] Adicionar cases de sucesso (quando disponível)
6. [ ] Configurar Google Analytics
7. [ ] Hospedar online
8. [ ] Testar em dispositivos reais
9. [ ] Coletar feedback
10. [ ] Iterar e melhorar

## 📝 Licença

© 2025 Inner IA. Todos os direitos reservados.

---

**Desenvolvido com 💜 usando HTML, CSS e JavaScript puro**
