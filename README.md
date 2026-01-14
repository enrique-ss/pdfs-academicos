# 📄 PDFs Acadêmicos

Crie artigos científicos no padrão **ABNT** usando HTML e CSS como se estivesse fazendo um site. O documento já sai formatado e pronto para impressão ou PDF.

## 🎯 O que faz

* ✅ Formatação ABNT automática (margens, fontes, espaçamentos)
* 📐 Template completo (capa, resumo, seções, referências)
* 🎨 Veja o resultado enquanto escreve
* 🖨️ Exporte para PDF com `Ctrl+P`

## 🚀 Como usar

```bash
1. Baixe os arquivos (index.html + style.css)
2. Abra o index.html no navegador (duplo clique)
3. Edite o conteúdo no seu editor de texto
4. Atualize o navegador para ver as mudanças
5. Ctrl+P → Salvar como PDF quando terminar
```

**Não precisa instalar nada!** É só HTML e CSS.

## 📝 Editando seu artigo

O template já vem pronto. Basta editar o texto dentro das tags HTML:

**Título e autores:**
```html
<h1 class="article-title">DIGITE SEU TÍTULO AQUI</h1>

<div class="author-block">
    <p class="author-name">Seu Nome - Matrícula</p>
    <p class="author-affiliation">Sua instituição</p>
    <p class="author-email">seu@email.com</p>
</div>
```

**Resumo:**
```html
<section class="abstract">
    <h2>RESUMO</h2>
    <p class="abstract-content">Escreva seu resumo aqui...</p>
    <p class="keywords"><strong>Palavras-chave:</strong> Palavra 1. Palavra 2.</p>
</section>
```

**Seções do trabalho:**
```html
<section>
    <h2>1 Introdução</h2>
    <p>Seu texto aqui...</p>
</section>
```

**Citação curta:**
```html
<p>Segundo Silva (2020), "texto entre aspas" (p. 42).</p>
```

**Citação longa (+3 linhas):**
```html
<blockquote>
    Texto longo da citação, que será formatado automaticamente
    com recuo de 4cm e fonte menor.
</blockquote>
```

**Tabela:**
```html
<figure>
    <table>
        <caption>Tabela 1 - Título</caption>
        <thead>
            <tr><th>Coluna 1</th><th>Coluna 2</th></tr>
        </thead>
        <tbody>
            <tr><td>Dado 1</td><td>Dado 2</td></tr>
        </tbody>
    </table>
    <figcaption>Fonte: Autor (2025)</figcaption>
</figure>
```

## ⚙️ Personalização

**Mudar margens** (`style.css`):
```css
@page {
    margin: 3cm 2cm 2cm 2cm; /* Superior | Direita | Inferior | Esquerda */
}
```

**Mudar fonte**:
```css
body {
    font-family: 'Times New Roman', serif; /* ou Arial, sans-serif */
}
```

**Controlar quebras de página**:
```html
<!-- Não quebra no meio -->
<section class="no-break">...</section>

<!-- Inicia em nova página -->
<section class="break-before">...</section>
```

## 📋 Checklist antes de entregar

- [ ] Revisei ortografia
- [ ] Conferi numeração das seções
- [ ] Verifiquei todas as citações
- [ ] Checei tabelas e figuras
- [ ] Organizei referências em ordem alfabética
- [ ] Testei a impressão em PDF

## 🛠️ Parte técnica

**Stack:**
* HTML5 - Estrutura do documento
* CSS3 - Formatação ABNT
* @page - Configuração de impressão

**Conformidade ABNT NBR 6022:2018:**
- ✅ Margens: 3cm (superior), 2cm (demais)
- ✅ Fonte: Arial ou Times, 12pt
- ✅ Espaçamento: Simples
- ✅ Recuo de parágrafo: 1,25cm
- ✅ Citações longas: Recuo 4cm, fonte 10pt
- ✅ Títulos: Numeração progressiva
- ✅ Referências: Espaço simples, sem recuo na primeira linha
- ✅ Tabelas: Bordas apenas superior e inferior

---

**💡 Dica:** Este template é uma ferramenta auxiliar. Sempre consulte seu orientador e as normas da sua instituição.
