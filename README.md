# Lei da Atração e Reprogramação Mental

Landing page do curso completo de Lei da Atração e Reprogramação Mental. Site em HTML/CSS/JS puro, otimizado para GitHub Pages.

## Descrição

Página de vendas com:
- Hero e call-to-action
- Apresentação do curso e benefícios
- Lista dos 15 módulos
- Checkout com liberação imediata após pagamento

## Publicar no GitHub Pages

### 1. Criar repositório

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository**
3. Digite um nome (ex: `curso-lei-atracao`)
4. Selecione **Public**
5. Clique em **Create repository**

### 2. Enviar arquivos

No terminal, na pasta do projeto:

```bash
git init
git add .
git commit -m "Primeiro commit - site Lei da Atração"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/curso-lei-atracao.git
git push -u origin main
```

Substitua `SEU-USUARIO` e `curso-lei-atracao` pelo seu usuário e nome do repositório.

### 3. Ativar GitHub Pages

1. No repositório, vá em **Settings**
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Em **Branch**, escolha `main` e pasta `/ (root)`
5. Clique em **Save**

### 4. Acessar o link

Após alguns minutos, o site estará disponível em:

- **Repositório de projeto:** `https://SEU-USUARIO.github.io/curso-lei-atracao/`
- **Repositório de usuário:** `https://SEU-USUARIO.github.io/` (se o repositório se chamar `SEU-USUARIO.github.io`)

## Estrutura do projeto

```
/
├── index.html    (página principal)
├── README.md     (este arquivo)
├── .gitignore
└── assets/       (para imagens, fontes ou ícones, se necessário)
```

## Requisitos

- HTML, CSS e JavaScript puro
- Sem backend, build tools ou frameworks
- Compatível com GitHub Pages (HTTPS)
- Mobile-first e responsivo
