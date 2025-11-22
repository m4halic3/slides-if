---
marp: true
theme: default
paginate: true
backgroundImage: url('./assets/img/fundo-slide.png')
backgroundSize: cover
backgroundPosition: center
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Playfair+Display:wght@600;700&display=swap');

body {
  font-family: "Inter", sans-serif;
  color: #fff;
  margin: 0;
}

section::before {
  content: "";
  position: fixed;
  top: 50px;
  left: 50px;
  width: 200px;
  height: 70px;
  background-image: url('./assets/img/logo-if.png');
  background-size: contain;
  background-repeat: no-repeat;
  background-position: left top;
  z-index: 999999;
  pointer-events: none;
}

h1, h2 {
  font-family: "Playfair Display", serif;
}

section h1 {
  color: #014d1e;
}

section.capa h1 {
  color: #fff !important;
}

section.agradecimento h1 {
  color: #fff !important;
}

ul li,
ol li {
  color: #014d1e !important;
  font-weight: 600;
}

section:first-of-type .marp-footer {
  display: none;
}

.capa {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  padding-top: 140px;
  height: 100%;
  position: relative;
}

.capa h1 {
  font-size: 2.2rem;
  margin-top: 2rem;
  text-align: center;
}

.capa h2 {
  font-size: 1.3rem;
  margin: 0.3rem 0 1rem;
  text-align: center;
}

.capa p.nome {
  font-size: 1.1rem;
  margin: 0.2rem 0;
  text-align: center;
}

.capa .disciplina {
  position: absolute;
  bottom: 2.5rem;
  right: 0.5rem;
  text-align: right;
  font-size: 0.80rem;
}

</style>

<section class="capa">
  <h1>TÍTULO DO TRABALHO</h1>
  <h2>Subtítulo Opcional</h2>
  <p class="nome">Mariana Alice Pires Leite</p>
  <p class="disciplina">
    Disciplina: Nome da Disciplina<br>
    Professor(a): Nome do Professor
  </p>
</section>

---

# Sumário
- Tópico 1
- Tópico 2
- Tópico 3

---

# Slide 1: Introdução
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

---

# Slide 2: Objetivos
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

---

# Slide 3: Metodologia
Duis aute irure dolor in reprehenderit.

---

# Slide 4: Resultados
Excepteur sint occaecat cupidatat non proident.

---

# Muito obrigada!
</section>

---

# Referências
1. Lorem ipsum  
2. Dolor sit amet  
3. Sed do eiusmod  
