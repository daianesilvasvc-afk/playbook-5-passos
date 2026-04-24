# 🪮 Playbook 5 Passos — Gestão & Assinatura em Barbearias

Playbook estratégico com navegação interativa. Pronto para hospedar no GitHub Pages.

---

## 📋 O que está incluído

- **Passo 1:** Diagnóstico Estruturado
- **Passo 2:** Mentalidade do Dono
- **Passo 3:** Números que Importam (KPIs)
- **Passo 4:** Fidelização de Profissionais
- **Passo 5:** Modelo de Assinatura

---

## 🚀 Como Hospedar no GitHub Pages

### 1. Crie um repositório no GitHub

```bash
# No terminal, dentro da pasta do projeto
git init
git add .
git commit -m "Initial commit: Playbook 5 passos"
git remote add origin https://github.com/seu-usuario/playbook-5-passos.git
git branch -M main
git push -u origin main
```

### 2. Ative GitHub Pages

1. Vá para o repositório no GitHub
2. Clique em **Settings**
3. Na seção esquerda, clique em **Pages**
4. Em "Source", selecione **main branch**
5. Clique em **Save**

GitHub vai gerar um link assim: `https://seu-usuario.github.io/playbook-5-passos`

### 3. Acesso ao Playbook

Seu playbook estará disponível em:
```
https://seu-usuario.github.io/playbook-5-passos
```

---

## 📁 Estrutura do Repositório

```
playbook-5-passos/
├── README.md (este arquivo)
├── index.html (o playbook — renomeie playbook_5_passos.html para isso)
└── .gitignore (opcional)
```

---

## 🎨 Customizações Possíveis

### Mudar Cores

No arquivo `index.html`, procure por:

```css
background: linear-gradient(135deg, #d4a574 0%, #8b6f47 100%);
```

Substitua os códigos HEX pelas cores que você quer:
- `#d4a574` → Cor principal (ouro/bronze)
- `#0f0f1e` → Cor de fundo escuro
- `#8b9dc3` → Cor de texto secundário

### Adicionar Logo

Procure por `<header>` e adicione uma tag `<img>` antes do `<h1>`:

```html
<header>
    <img src="logo.png" alt="Logo Podium" style="max-width: 150px; margin-bottom: 1rem;">
    <h1>🪮 Playbook 5 Passos</h1>
    ...
</header>
```

### Adicionar Google Analytics

Antes de `</body>`, adicione:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## 📊 Funcionalidades Interativas

- ✅ Navegação por abas (5 passos)
- ✅ Checklists que você pode marcar (salva na sessão)
- ✅ Design responsivo (mobile + desktop)
- ✅ Sem dependências externas (HTML + CSS + JavaScript puro)

---

## 🔗 Domínio Customizado (Opcional)

Se você quiser usar um domínio próprio (ex: `playbook.podium.com.br`):

1. Vá para **Settings > Pages**
2. Em "Custom domain", adicione `playbook.podium.com.br`
3. Configure o DNS do seu domínio para apontar pro GitHub Pages:

```
Tipo: CNAME
Nome: playbook
Valor: seu-usuario.github.io
```

---

## 📝 Notas Importantes

- O arquivo principal precisa se chamar `index.html` (ou mude as configurações do GitHub Pages)
- Se você clonar este repo em outro lugar, o GitHub Pages não atualiza automaticamente — você precisa fazer `git push`
- Checklists são salvos apenas na sessão atual (refresh limpa)

---

## 🎯 Próximos Passos

1. ✅ Suba para GitHub
2. ✅ Teste o link gerado
3. ✅ Compartilhe com sua equipe de SDRs ou donos de barbearia
4. ✅ Recolha feedback e itere

---

## 📞 Suporte

Se tiver dúvidas sobre como hospedar, consulte a documentação oficial:
[GitHub Pages Docs](https://docs.github.com/en/pages)

---

**Material exclusivo Podium Educação. Não reproduzir.**

Desenvolvido com base em metodologia de gestão e performance aplicada em barbearias de alto desempenho.
