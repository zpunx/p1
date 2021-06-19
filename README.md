# Projeto 01

Crie uma página com um formulário de pesquisa.

1. Implemente o Layout da página utilizando [CSS Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/grid) e [CSS Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/flex)

2. Adicione um título principal e um sub-título na sua página.
   2.1. O título principal deve ter texto "Formulário de Pesquisa" e estar em [negrito](https://developer.mozilla.org/pt-BR/docs/Web/CSS/font-weight) e ter `28` pixels de [tamanho](https://developer.mozilla.org/pt-BR/docs/Web/CSS/font-size).
   2.2. O sub-título deve ter texto "Obrigado por tomar seu tempo para nos ajudar a melhorar nossa plataforma!" e estar em [itálico](https://www.w3.org/Style/Examples/007/fonts.pt_BR.html).

3. A página deve ter um formulário. Crie o formulário utilizando a [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/form) `<form>`.

4. Implemente um campo que o usuário possa digitar o seu nome no formulário.
   4.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/label) `<label>`, com texto "Nome".
   4.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input) `<input>`, com placeholder "Qual é o seu Nome?"

5. Implemente um campo que o usuário possa digitar o seu email no formulário.
   5.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/label) `<label>`, com texto "Email".
   5.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input) `<input>`, com placeholder "Qual é o seu Email?"

6. Implemente um campo que o usuário possa digitar a sua idade no formulário.
   6.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/label) `<label>`, com texto "Idade".
   6.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input) `<input>`, com placeholder "Qual é a sua idade?"

7. Implemente um campo que o usuário possa selecionar a sua área de atuação no formulário.
   7.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p) `<p>`, com texto "Qual opção abaixo descreve melhor a sua atuação no momento?".
   7.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/select) `<select>`, com uma opção desabilitada com texto "Selecione área de atuação".
   7.3. O campo deve ter as seguintes opções disponíveis para serem selecionadas:

   - Estudante
   - Carteira Assinada
   - Pesquisador
   - Prefiro não comentar
   - Outros

8. Implemente um campo onde o usuário possa marcar uma opção entre três outras opções:
   8.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p) `<p>`, com texto "Você recomendaria esse projeto para um amigo?".
   8.2 O campo deve ter três [tags HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Input/radio) `<input>` de tipo `radio`.
   8.3 A primeira opção deve ter texto "Definitivamente!"
   8.4 A segunda opção deve ter texto "Talvez..."
   8.5 A terceira opção deve ter texto "Não tenho certeza."

   - OBS: O usuário deve apenas conseguir escolher UMA das três opções!

9. Implemente um campo que o usuário possa selecionar a sua linguagem de programação favorita no formulário.
   9.1. O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p) `<p>`, com texto "Qual é a sua linguagem de programação favorita?".
   9.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/select) `<select>`, com uma opção desabilitada com texto "Selecione uma opção".
   9.3. O campo deve ter as seguintes opções disponíveis para serem selecionadas:

   - Javascript
   - Typescript
   - Ruby
   - Java
   - Python

10. Implemente um campo que o usuário possa marcar várias alternativas diferentes:
    10.1 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p) `<p>`, com texto "Em que você gostaria de melhorar? (Marque todas as alternativas que se aplicam)".
    10.2 O campo deve ter oito [tags HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Input/checkbox) `<input>` de tipo `checkbox`.
    10.3 A primeira opção deve ter texto "Desenvolvimento Front-end".
    10.4 A segunda opção deve ter texto "Desenvolvimento Back-end".
    10.5 A quinta opção deve ter texto "Segurança da Informação".
    10.6 A sexta opção deve ter texto "Aprendizado de máquinas (Machine Learning)".
    10.7 A sétima opção deve ter texto "Ciência de Dados".
    10.8 A oitava opção deve ter texto "Engenharia de Dados".

- OBS: O usuário deve conseguir escolher VARIAS opções!

11. Implemente um campo que o usuário possa escrever uma sugestão ou um comentário sobre o formulário que você fez.
    11.1 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p) `<p>`, com texto "Você teria algum comentário ou sugestão sobre esse projeto?".
    11.2 O campo deve ter uma [tag HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input) `<input>` de tipo `textarea`.
    11.3 O input deve ter um atributo `placeholder` com texto "Adicione seu comentário aqui...".

12. Implemente um [botão](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/button) para que o usuário possa enviar as informações que ele preencheu no formulário.
    12.1 O botão deve ser do tipo `submit` e estar DESABILITADO.

### BONUS:

1. O layout do formulário deve parecer com o formulário presente na foto abaixo:

![Screenshot 2021-06-19 at 17 26 40](https://user-images.githubusercontent.com/63159499/122654732-cd199b00-d123-11eb-9a63-2a332e5e6834.png)

2. Utilize [essa imagem](https://cdn.freecodecamp.org/testable-projects-fcc/images/survey-form-background.jpeg) para criar o efeito de [background](https://developer.mozilla.org/pt-BR/docs/Web/CSS/background) na foto acima.
