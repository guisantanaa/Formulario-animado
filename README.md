# Formulário animado com JS puro e CSS  Animation

- O formulário aparece, suavemente, quando a página é aberta ou atualizada.
- Os compos aparecem da esquerda para a direita, suavizando a entrada e fazendo-os entrar em momentos distintos.
- Quando preencher os dados e clicar em Login, o formulário sai da tela, indo para baixo
- Efeito diferente de timing para a saida do formulario
- Formulario diz (vibrar) ou não-não caso haja campos vazios.
- Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão tambpem). animações com tamanhos diferentes, sairem em momentos diferentes, timing diferente e animação continua.

## Animation

8 propriedades:

-animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite:

@keyframes animationname {
    0% {

    }
    100% {

    }
}

podemos ter múltiplas animações no mesmo elemento

animation: slide-top 2s, bounce 1s, fade 0.2s;
