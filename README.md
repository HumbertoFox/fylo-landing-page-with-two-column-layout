# Frontend Mentor - Fylo landing page with two column layout solution

Esta é uma solução para o [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). 
Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Layout do projeto em tela de desktop/Notebook.

<div align="center">
  <img src="https://github.com/HumbertoFox/repository/assets/126817628/3352c607-2e4c-4e00-bdd5-66fcbf485597" width="400px"/>

  <img src="https://github.com/HumbertoFox/repository/assets/126817628/8b076917-379a-4b4d-8a52-134ff06c041c" width="400px"/>
</div>

## Layout do projeto responsivo em tela de Notebook/Tablet/Mobile.

<div align="center">
  <img src="https://github.com/HumbertoFox/repository/assets/126817628/268bb1fd-645b-4d7d-9309-7648c7db3263" width="400px"/>
</div>

### O que aprendi

```html
    <div class="div-get-early-input-button">
        <div class="div-get-early-input">
            <input type="email" placeholder="email@example.com">
            <span>
                Please check your email
            </span>
        </div>
        <button type="submit">
            Get Started For Free
        </button>
    </div>
```

```css
    span {
        display: none;
        color: #EF4877;
        font-family: 'Open Sans', sans-serif;
        font-size: 12px;
        font-weight: 400;
        letter-spacing: 0.4px;
        padding-top: 5px;
    }
    input[type="email"]:invalid {
        border: .63px solid #EF4877;
    }
    input[type="email"]:invalid + span{
        display: block;
    }
    button {
        cursor: url(../images/pointer.svg), auto;
    }
```

### Construído com

- Marcação semântica HTML5
- Propriedades personalizadas CSS
- Caixa flexível
## Desenvolvido em:

<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="30px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="30px"/>
</div>
