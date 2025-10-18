# 📚 Livraria Online

Bem-vindo ao projeto **Livraria Online** — um site desenvolvido com **HTML, CSS e Bootstrap**, que tem como objetivo oferecer uma vitrine moderna e responsiva para exibição e venda de livros cristãos e de diversos gêneros.

---

## 🚀 Tecnologias utilizadas

- **HTML5**  
- **CSS3**  
- **Bootstrap 5**  


---

## 🧩 Funcionalidades

✅ Catálogo de livros com imagem, autor e preço  
✅ Layout responsivo (adaptável a celular, tablet e desktop)  
✅ Cards organizados com Bootstrap  
✅ Estrutura preparada para carrinho de compras (futura implementação)  
✅ Interface leve e moderna  

---

## 🖼️ Exemplo de exibição dos livros

Os livros são mostrados em blocos, com capa, título, autor e botão de compra:

```html
<div class="card h-100 shadow-sm">
  <img src="img/livro1.jpg" class="card-img-top" alt="Capa do livro">
  <div class="card-body text-center">
    <h5 class="card-title">O Peregrino</h5>
    <p class="text-muted mb-1">John Bunyan</p>
    <p class="fw-bold text-primary">R$ 39,90</p>
    <a href="#" class="btn btn-outline-primary w-100">Comprar</a>
  </div>
</div>

