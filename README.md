# Instant CPF

Gerador instantâneo de CPF na barra de favoritos do navegador.

#### Instalação
Copie o código abaixo, crie um novo favorito e no lugar da URL cole o código copiado.

```sh
javascript:void(function(){function r(t){return Math.round(Math.random()*t)}function m(t,e){return Math.round(t-Math.floor(t/e)*e)}function i(t){var e=document.createElement("input");document.body.appendChild(e),e.setAttribute("id","g_cpf_g"),document.getElementById("g_cpf_g").value=t,e.select(),document.execCommand("copy"),document.body.removeChild(e)}function g(){var t=r(9),e=r(9),n=r(9),o=r(9),d=r(9),u=r(9),a=r(9),f=r(9),g=r(9),l=2*g+3*f+4*a+5*u+6*d+7*o+8*n+9*e+10*t;(l=11-m(l,11))>=10&&(l=0);var h=2*l+3*g+4*f+5*a+6*u+7*d+8*o+9*n+10*e+11*t;(h=11-m(h,11))>=10&&(h=0),c=""+t+e+n+o+d+u+a+f+g+l+h,i(c)}g();})();
```
#### Como funciona
Com o favorito adicionado, basta clicar nele que o CPF gerado estará no seu clipboard (ctrl/cmd + v).
Os CPF são gerados aleatóriamente e em cada click, ele gera um novo número.

Enjoy!