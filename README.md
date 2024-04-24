# estudos
<style>
@charset "UTF-8";
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
*{
    margin: 0px;
    padding: 0px;
}
:root {
    --cor0:#F2F2F2;
    --cor05:#A0CED9;
    --cor1:#56A1BF;
    --cor15:#50ABBF;
    --cor2:#325A73;
    --cor25:#223549;
    --cor3:#0D0D0D;

    --fonte-padrao: 'Roboto';
    --fonte-naislanacirino: 'Playfair Display'
}
body{ 
    background-color:var(--cor0);
    font-family: var(--fonte-padrao);
    margin: 0px;
    font-size: 20px;
    font-weight: 100;
}
header{
    min-height: 150px;
    border-radius: 0px;
    margin: auto;
    text-align: center;
    display: block;
    background-image: linear-gradient(to top,var(--cor2),var(--cor1));
    padding: 0px;
    margin: auto auto 10px auto;
}
header  h1 {
    padding: 0px;
    margin: auto;
    font-family: var(--fonte-naislanacirino);
    font-size: 100px;
    color: var(--cor0);
    text-shadow: 2px 2px 0px black;
}
header  p{
    font-family: var(--fonte-padrao);
    font-size: 1.2em;
    color: var(--cor0);
    max-width: 600px;
    padding-right: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    margin: auto;
    text-shadow: 1px 1px 0px black;
}
nav{
    background-color:var(--cor2);
    padding: 5px;
    box-shadow: 0px 7px 9px rgba(0, 0, 0, 0.486);
}
nav >  a {
    text-decoration: none;
    color: var(--cor0);
    font-weight: bold;
    margin-right: 10px;
    border-radius: 5px;
    padding: 5px;
}
nav > a:hover {
    background-color: var(--cor1);
    box-shadow: inset 2px 2px 2px black;
    text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.651);
}
main{
    color: var(--cor3);
    font-family: var(--fonte-padrao);
    text-align: justify;
    background-color:var(--cor0);
    padding: 0px 0px 30px 0px;
    margin: auto;
    border-radius: 20px 20px;
    box-shadow: 4px 4px 9px 0px rgba(0, 0, 0, 0.384);
    max-width: 800px;
    min-width: 320px;
}
main  h1 {
    background-color: var(--cor2);
    color: var(--cor0);
    padding: 20px;
    text-align: center;
    text-shadow: 2px 2px 0px black;
    border-radius: 20px 20px 0px 0px;
}
main  h2 {
    font-family: var(--fonte-naislanacirino);
    background-image: linear-gradient(to right,var(--cor1),var(--cor0));
    margin: 0px;
    text-indent: 10px;
    font-weight: bolder;
    font-size: xx-large;
    text-align: center;
}
main  h3 {
    margin: 20px;
}
main  p {
    text-indent: 30px;
    font-size: larger;
    font-weight: bolder;
    margin: 15px 18px;
    padding: 0px;
    text-align: justify;
    line-height: 1.5em;
}
strong{
    color: var(--cor15);
    font-weight: bolder;
}
main a {
    text-decoration: none;
    color: white;
    background-color: var(--cor2);
    padding: 2px 6px;
    border-radius: 5px;
    font-weight: bold;
}
main a:hover{
    text-decoration: underline;
    background-color: var(--cor1);
}
main  a.botaocontato:hover {
    background-color: var(--cor1);
    box-shadow: inset 2px 2px 2px black;
    text-shadow: 2px 2px 0px rgb(0, 0, 0);
}
main  a.botaocontato {
    background-color: var(--cor2);
    color: var(--cor0);
    text-decoration: none;
    padding: 10px 10px;
    margin: 5px;
    border-radius: 5px;
    font-weight: bolder;
    box-shadow: 2px 2px 2px black;
}
main  img {
    width: 30%;
    margin: 10px;
    background-color: var(--cor2);
    padding: 5px;
    border-radius: 10px;
}
main.galeria{
    text-align: center;
}
footer{
    background-image: linear-gradient(to bottom,var(--cor2),var(--cor1));
    color: var(--cor0);
    text-align: center;
    padding: 20px;
    margin: 10px 0px 0px 0px;
}
footer h1 {
    padding: 0px;
    text-shadow: 2px 2px 0px black;
}
footer  p {
    line-height: 2em;
    display: inline-block;
    margin: 0px;
    padding: 0px;
    font-weight: 500;
}
footer a:hover{
    background-color: var(--cor2);
    box-shadow: inset 2px 2px 2px black;
}
footer a {
    font-family: 'Playfair Display';
    box-shadow: 2px 2px 2px black;
    margin: 0px;
    border-radius: 10px;
    text-decoration: none;
    padding: 5px;
    color:white;
    font-weight: bolder;
    font-size: x-large;
    background-color:var(--cor2);
}
</style>
 <h1>Curso de HTML5 e CSS3 do CursoemVideo</h1>

<p>Estou aprendendo a criar sites e agora vou gerenciar meus repositórios!<p>

<h2>Meus Projetos</h2>

<a href="https://arthurrodrigues1.github.io/NailsAnaCirino/" target= _blank>Nails Ana Cirino</a>

<h2>Exercicios</h2>

<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex001/" target= _blank>ex001</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex002/" target= _blank>ex002</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex003/" target= _blank>ex003</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex004/" target= _blank>ex004</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex006/" target= _blank>ex006</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex007/" target= _blank>ex007</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex008/" target= _blank>ex008</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex009/" target= _blank>ex009</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex010/" target= _blank>ex010</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex011/" target= _blank>ex011</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex012/" target= _blank>ex012</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex013/" target= _blank>ex013</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex014/" target= _blank>ex014</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex015/" target= _blank>ex015</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex016/" target= _blank>ex016</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex017/" target= _blank>ex017</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex018/" target= _blank>ex018</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex019/" target= _blank>ex019</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex020/" target= _blank>ex020</a>
<a href="https://arthurrodrigues1.github.io/estudos/exercicios/ex021/" target= _blank>ex021</a>

<h2>Desafios</h2>

<a href="https://arthurrodrigues1.github.io/estudos/desafios/d001/" target= _blank>d001</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d002/" target= _blank>d002</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d003/" target= _blank>d003</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d004/" target= _blank>d004</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d005/" target= _blank>d005</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d006/" target= _blank>d006</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d007/" target= _blank>d007</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d008/" target= _blank>d008</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d009/" target= _blank>d009</a>
<a href="https://arthurrodrigues1.github.io/estudos/desafios/d010/" target= _blank>d010</a>
