# Plataformas de Monitoramento · Educação de Lagoa da Canoa

Portal centralizador de acesso às plataformas de monitoramento pedagógico e educacional da **Secretaria Municipal de Educação de Lagoa da Canoa - AL**.

---

## 🚀 Plataformas Disponíveis

- **Educação Infantil:** [ei.provacanoa.tech](https://ei.provacanoa.tech/)
- **Ensino Fundamental I (Anos Iniciais):** [anosiniciais.provacanoa.tech](https://anosiniciais.provacanoa.tech/)
- *Outras etapas e frentes de monitoramento serão adicionadas conforme disponibilidade.*

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 semântico**
- **CSS3 Moderno** (Variáveis CSS, CSS Grid, Flexbox, efeito *glassmorphism* e responsividade total)
- **SVG / Assets Embutidos** (Página 100% autocontida, sem dependência de build, servidores externos ou frameworks pesados)

---

## 🌐 Publicação no GitHub Pages

Este projeto foi estruturado diretamente na raiz com o arquivo `index.html`, sendo compatível de forma imediata com o **GitHub Pages**:

1. No repositório no GitHub, acesse a aba **Settings** (Configurações).
2. No menu lateral esquerdo, clique em **Pages**.
3. Na seção **Build and deployment**:
   - **Source**: Selecione `Deploy from a branch`.
   - **Branch**: Selecione `main` e a pasta `/ (root)`.
4. Clique em **Save**.
5. Aguarde alguns instantes e o site estará no ar na URL do GitHub Pages:
   `https://douglas14031999.github.io/home-plataformas-monitoramento/`

---

## ➕ Como Adicionar uma Nova Plataforma

No arquivo `index.html`, localize a seção `<section class="grade" id="plataformas">` e adicione um novo bloco antes do card de "Novas plataformas em breve":

```html
<a class="card" href="https://sua-plataforma.provacanoa.tech/" style="--cor: #2d7a5a">
  <div class="capa">
    <span class="icone" aria-hidden="true">
      <!-- Ícone SVG aqui -->
    </span>
  </div>
  <div class="corpo">
    <h2>Nome da Etapa</h2>
    <p>Descrição breve do monitoramento.</p>
    <span class="dominio">sua-plataforma.provacanoa.tech</span>
    <span class="acesso">Acessar plataforma</span>
  </div>
</a>
```

Cores da identidade visual disponíveis:
- Verde: `#2d7a5a`
- Laranja: `#f47b20`
- Rosa: `#e6005c`
