
Microsoft Learn




Curso:
Creating your first web apps with React - 03 MÓDULOS


{OBSERVAÇÃO IVAN: há um bug nesse projeto entre o snowpack e o dropbox no mac OS e talvez em outros sistemas operacionais. O fato é que o "whatching for file changes", que é responsável pela recompilação imediata somente passou a funcionar no meu caso, quando a pasta com o projeto clonado foi colocada fora do Dropbox. Abaixo o link relacionado e com algumas outras sugestões de solucões}
https://stackoverflow.com/questions/26708205/webpack-watch-isnt-compiling-changed-files












MÓDULO 01 - Get started with React








Introduction to React
https://docs.microsoft.com/en-us/training/modules/react-get-started/1-introduction
{só teria}
[2022 09 09];














Introduction to JSX
https://docs.microsoft.com/en-us/training/modules/react-get-started/2-javascript-xml
{só teoria}
[2022 09 09];

















[2022 09 09];
Create a starter project
https://docs.microsoft.com/en-us/training/modules/react-get-started/3-clone-starter
{comandos de terminal e códigos pra praticar}
// *** praticando códigos:
# Linux or macOS
"git clone https://github.com/MicrosoftDocs/mslearn-react"
<!-- git clone http://github.com/MicrosoftDocs/mslearn-react -->




"cd mslearn-react/code/0-starter"
<!-- cd mslearn-rect/code/0-starter -->






# Windows
"git clone https://github.com/MicrosoftDocs/mslearn-react"
<!-- git clone https://github.com/MicrosoftDocs/mslearn-react -->



"cd mslearn-react\code\0-starter"
<!-- cd mslearn-react\code\0-starter -->





"npm install"
<!-- npm install -->





"code ."
<!-- code . -->



















Hello, world!
https://docs.microsoft.com/en-us/training/modules/react-get-started/4-hello-world-test
{códigos para treinar e prática}
[2022 09 09];


















Create your first component
https://docs.microsoft.com/en-us/training/modules/react-get-started/5-create-first-component
{teoria e prática}
[2022 09 09];


Relacionado:
Como funciona o import e export do JavaScript (Alura)
https://www.alura.com.br/artigos/como-funciona-o-import-e-export-do-javascript?gclid=Cj0KCQjwyOuYBhCGARIsAIdGQRNDkC9b19aseJBLlSwl_rrbUBrHtewTePdzp_hZnKHAZs08ci1AeakaAlfjEALw_wcB
{muito bom resumo}
[2022 09 09];













Display dynamic data
https://docs.microsoft.com/en-us/training/modules/react-get-started/6-dynamic-data-exercise
{teoria e prática}
[2022 09 09];











Add style
https://docs.microsoft.com/en-us/training/modules/react-get-started/7-add-style
{prática}
[2022 09 09];














Create a React project from scratch
https://docs.microsoft.com/en-us/training/modules/react-get-started/8-project-from-scratch
{prática}
[2022 09 09];














Knowledge check
https://docs.microsoft.com/en-us/training/modules/react-get-started/9-knowledge-check
{questionário 3 perguntas tranquilo}
[2022 09 09];

















Summary
https://docs.microsoft.com/en-us/training/modules/react-get-started/10-summary
[2022 09 09];





















MÓDULO 02 - Working with data and properties in React components





Introduction
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/1-introduction
{clonar o projeto no visual studio code}
[2022 09 09];















Introducing props
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/2-exercise-props
{teoria e prática}
[2022 09 09];














Work with logic in JSX files
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/3-logic
{teoria mas que implementei na prática; ressalta a importância de class x className; ternary operator; ternary operator e JSX}
[2022 09 10];
















Use complex data types as props
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/4-exercise-prop-object
{teoria e prática; bom}
[2022 09 10];

Relacionado:

Operador Condicional Ternário (MDN Mozilla)
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Conditional_Operator
{bom}
[2022 09 10];















Use map to display data inside an array
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/5-map
{teoria com exemplos, mas sem prática explícita, mas dá pra praticar, mesmo assim muito bom}
[2022 09 15];
















Display list data
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/6-exercise-lists
{muito boa prática}
[2022 09 15];















*** depois tentar ordenar pela propriedade order no ojeto steps

Challenge
https://docs.microsoft.com/en-us/training/modules/react-work-with-components-and-data/7-challenge
{boa atividade prática}












Knowledge check
https://learn.microsoft.com/en-us/training/modules/react-work-with-components-and-data/8-knowledge-check
{atenção na pergunta 2}















Summary
https://learn.microsoft.com/en-us/training/modules/react-work-with-components-and-data/9-summary
{só o resumo breve do que foi visto}
[2022 09 18];
























MÓDULO 02 - Working with data and properties in React components
React state and events
https://learn.microsoft.com/en-us/training/modules/react-states-events/





Introduction
https://learn.microsoft.com/en-us/training/modules/react-states-events/1-introduction
{teoria}
[2022 09 25];










Explore the concepts of state
https://learn.microsoft.com/en-us/training/modules/react-states-events/2-concepts
{teoria sobre props, state e immutability}
[2022 09 25];








*** fixar códigos
Add state to an application
https://learn.microsoft.com/en-us/training/modules/react-states-events/3-add-state
{useState; atividade prática}
[2022 09 26];







Work with user events
https://learn.microsoft.com/en-us/training/modules/react-states-events/4-events
{tem exemplos de códigos, mas não é propriamente uma prática; bom conteúdo: Event Listeners}
[2022 09 26];


class Demo extends React.Component {
    render() {
        <button onClick={ () => alert('Hello, world!') }>Click me!</button>
    }
}
//______________________________________________
class Demo extends React.Component {
    render() {
        <button onClick= { () => alert('Hello, world!') }>Click me!</button>
    }
}
//______________________________________________
class Demo extends React.Component {
    render() {
        <button onClick={ () => alert('Hello, world!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extends React.Component {
    render() {
        <button oncClick={ () => alert('Hello, world!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extends React.Component { 
    render() {
        <button onClick={ () => alert('Hello, world!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extends React.Component {
    render() {
        <button onClick={ () => alert('Hello, world!') }>Click me!</button>
    }
}
//____________________________________________
class Demo extends React.Component {
    render() {
        <button onClick= { () => alert('Hello, world!')}>Click me!</button>
    }
}
//____________________________________________









class Demo extends React.Component {
    displayMessage() {
        alert('Hello, world!');
    }

    render() {
        <button onClick={ () => displayMessage() }>Click me!</button>
    }
}//_____________________________________________
class Demo extends React.Component {
    displayMessage() {
        alert('Hello, world!');
    }

    render() {
        <button onClick={ () => displayMessage() }>Click me!</button>
    }
}
//______________________________________________
class Demo extends React.Component {
    displayMessage() {
        alert('Hello, world!');
    }

    render() {
        <button onclick={ () => displayMessage() }>Click me!</button>
    }
}
//______________________________________________
class Demo extends React.Component {
    displayMessage() {
        alert('Hello, world!');
    }

    render() {
        <button onClick={ () => displayMessage() }>Click me!</button>
    }
}
//______________________________________________









class Demo extends React.Component {
    displayMessage(message) {
        alert(message);
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//______________________________________________
class Demo extends React.Component {
    displayMessage(message) {
        alert(message);
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extendes React.Component {
    displayMessage(message) {
        alert(message);
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extendes React.Component {
    displayMessage(message) {
        alert(message)
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extends React.Component {
    displayMessage(message) {
        alert(message)
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//_____________________________________________
class Demo extends React.Component {
    displayMessage(message) {
        alert(message)
    }

    render() {
        <button onClick={ () => displayMessage('Clicked button!') }>Click me!</button>
    }
}
//______________________________________________


















Update state
https://learn.microsoft.com/en-us/training/modules/react-states-events/5-update-state
{tem exemplos de códigos, mas não é propriamente uma prática; bom conteúdo: Spread Sintax}
[]




let message = 'Hello, ';
message = message + 'world!';
//___________________________________
let messge = 'Hello, ';
message = message + 'world!';
//___________________________________
let message = 'Hello, ';
message = message + 'world!';
//___________________________________
let message = 'Hello, ';
message = message + 'world!';
//___________________________________
let message = 'Hello, ';
message = message + 'world!';
//___________________________________
let message = 'Hello ';
message = message + 'world!';
//__________________________________
let message = 'Hello ';
message = message + 'world!';
//__________________________________






relacionados:

*** reler futuramente para fixar e entender melhor os conceitos
spread sintax {=sintaxe de espalhamento}
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Spread_syntax
[2022 10 01];

Funções de Array JavaScript - Aula 4 - every() (6min) (canal dpw)
https://www.youtube.com/watch?v=QCqPixrujp4
[2022 10 16];








let message = {
    text: 'Hello, world',
    color: 'red'
}

let messageCopy = { ...message };
//___________________________________
let message = {
    text: 'Hello, world!',
    color: 'red'
}

let messageCopy = { ...message };
//____________________________________
let message = {
    text: 'Hello, worldQ',
    color: 'red'
}

let messageCopy = { ...message };
//____________________________________
let message = {
    text: 'Hello, world!',
    color: 'red'
}

let messageCopy ={ ...message };
//____________________________________
let message = {
    text: 'Hello, world!',
    color: 'red'
}

let messageCopy = { ...message };
//____________________________________











let message = {
    text: 'Hello, world',
    color: 'red'
}

let messageCopy = {
    ...message,
    color: 'green'
};
//________________________________
let message = {
    text: 'Hello, world',
    color: 'red'
}

let messageCopy = {
    ...message,
    color: 'green'
};
//________________________________
let message = {
    text: 'Hello, world!',
    color: 'red'
}

let messageCopy = {
    ...message,
    color: 'green'
};
//________________________________
let message = {
    message: 'Hello, world!',
    color: 'red'
}

let messageCopy = {
    ...message,
    color: 'green'
};
//________________________________
let message = {
    message: 'Hello, world!',
    color: 'red'
}

let messageCopy = {
    ...message,
    color: 'green'
};
//________________________________













// new object {novo objeto resultante do código acima}
{
    text: 'Hello, world',
    color: 'green'
}
//_______________________________
















Add event handlers and update state
https://learn.microsoft.com/en-us/training/modules/react-states-events/6-add-events
{boa atividade prática; event listener; passing a function to a componente as any other prop; props can be any JS types including functions; we can passa parameters into a prop function}
[2022 10 02];











Hooks
https://learn.microsoft.com/en-us/training/modules/react-states-events/7-hooks
{teoria e exemplos, mas sem ser propriamente uma atividade prática; Hooks; Effect Hook}
[2022 10 04];





useEffect(() => {
    // code goes here
});
//__________________________________________
useEffect(() => {

});
//__________________________________________
useEffect(() => {

});
//_________________________________________
useEffect(() => {

});
//_________________________________________
useEffect(() => {

});
//__________________________________________










useEffect(() => {
    // code goes here
}, [ someStatefulObject ]);
//_________________________________________
useEffect(() => {

}, [ someStatefulObject ]);
//_________________________________________
useEffect(() => {

}, [ someStatefulObject ]);
//_________________________________________
useEffect(() => {

}, [ someStatefulObject ]);
//_________________________________________
useEffect(() => {

}, [ someStatefulObjetc ]);
//_________________________________________
useEffect(() => {

}, [ someStatefulObject ]);
//_________________________________________














*** fixar syntax códigos
Add Hooks
https://learn.microsoft.com/en-us/training/modules/react-states-events/8-add-hooks
{useEffect; método every(); boa atividade prática}
[2022 10 06];

relacionados:

*** depois praticar os exemplos
Array.prototype.every()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every
{importante}
[2022 10 06];











Knowledge check
https://learn.microsoft.com/en-us/training/modules/react-states-events/9-knowledge-check
{questionário bem tranquilo 03 perguntas sobre useEffect e o useState}
[2022 10 06];




