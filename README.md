# Frontend Mentor - Fylo landing page with two column layout solution

Esta é uma solução para o [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). 
Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Layout do projeto responsivo em tela de desktop/Notebook/Tablet/Mobile.

<div align="center">
  <img src="https://github.com/HumbertoFox/repository/assets/126817628/225321a2-c8c7-4b09-abe4-92cbc3e34a22" width="400px"/>
  <img src="https://github.com/HumbertoFox/repository/assets/126817628/47c3baf0-bd03-447d-a3d3-70a2d025bca2" width="400px"/>
  <img src="https://github.com/HumbertoFox/repository/assets/126817628/5930e86b-72fe-4c99-9c49-614ba44f3fc6" width="400px"/>
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
