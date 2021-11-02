<h1 align="center">
  Squid Grame Discover
</h1>

<h4 align="center">
	🚧  Squid Game  🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-problemas-encontrados">Problemas encontrados</a> •
 <a href="#-layout">Layout</a> •
 <a href="#-tecnologias">CSS</a> •
</p>


## 💻 Sobre o projeto

O projeto consiste em uma página web para apresentar animações referente ao filme Squid Game. 
Este projeto foi executado com base no video apresentado por Md Irshad Ansari.
- HTML;
- CSS;
- JavaScript;

Site: 

---

## ⚙️ Funcionalidades

- [X] Adicionar audio
- [X] Adicionar efeitos
---


## ❌Problemas encontrados
- Problema: Executar audio ao acessar a tela. Solução: https://developer.chrome.com/blog/autoplay/#webaudio


## 🛠 CSS

Para adicionar o efeito da máscara com linhas verticais e horizontais
```css
// Adicionando linhas verticais
repeating-linear-gradient(
            90deg,
            var(--black-line) 0%,
            var(--black-line) 1%,
            transparent 1px,
            transparent 10px
        ),

// Adicionando linhas horizontais
  repeating-linear-gradient(
      0deg, var(--black-line) 0%, 
      var(--black-line) 1%, 
      transparent 1px, 
      transparent 10px);
```
  

  Para ter espaços entre as linhas 
  ```css 
  background-size: 10px 10px;
  ```

  Para o efeito do drop-shadow não ultrapassar para os demais cards, 
  foi adicionado "overflow" no container__card
```css 
     overflow: hidden;
  ```

Para definir o tamanho que o card vai crescer quando passar o mouse, 
foi utilizado o flex-grow;
```css
flex-grow: 3;
```

Para especificar a sobra do ícone e aumentando gradativamente, foi utilizado drop-shadow
```css
filter: 
  drop-shadow(0 0 10px var(--purple)) 
  drop-shadow(0 0 30px var(--purple)) 
  drop-shadow(0 0 60px var(--purple))
  drop-shadow(0 0 100px var(--purple)) 
  drop-shadow(0 0 150px var(--purple));
``` 
