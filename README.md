# bold-react-questions
Repositório de perguntas para entrevistas de React

# Javascript
https://www.codementor.io/nihantanu/21-essential-javascript-tech-interview-practice-questions-answers-du107p62z

https://www.sitepoint.com/5-javascript-interview-exercises/

https://www.toptal.com/javascript/interview-questions

## JS EASY

**criar uma função que soma dois numeros e devolve o resultado**

**criar um elemento e fazer attach ao DOM**

## JS MID

**formas de declarar funções. diferenças entre elas.**

**como é determinado o this numa função js?**

**quais as vantagens de usar frameworks SPA?**

**o que é o prototype de um objecto em js?**

**o que fazem os métodos map/filter dos arrays?**

**vantagens e desvantagens do map/filter vs foreach ou for**

**escrever uma implementação do map e do filter baseada no reduce**

## JS ADVANCED
  **What is a “closure” in JavaScript? Provide an example**
  
  **Write a sum function which will work properly when invoked using either syntax below.**
  ```
      console.log(sum(2,3));   // Outputs 5
      console.log(sum(2)(3));  // Outputs 5
  ```

  **What will be the output of the code below?**
  ```
    var Employee = {
      company: 'xyz'
    }
    var emp1 = Object.create(Employee);
    delete emp1.company
    console.log(emp1.company);
 ```
 
  **What will be the output of code below?**
  ```
  var salary = "1000$";

  (function () {
      console.log("Original salary was " + salary);

      var salary = "5000$";

      console.log("My New Salary " + salary);
  })();
  ```

  **Consider the two functions below. Will they both return the same thing? Why or why not?**
```
function foo1()
{
  return {
      bar: "hello"
  };
}

function foo2()
{
  return
  {
      bar: "hello"
  };
}
```

**In what order will the numbers 1-4 be logged to the console when the code below is executed? Why?**
```
(function() {
    console.log(1); 
    setTimeout(function(){console.log(2)}, 1000); 
    setTimeout(function(){console.log(3)}, 0); 
    console.log(4);
})();
for(var i=10;i<100000;i++){
  console.log(i);
}
```

# React
https://www.codementor.io/blog/5-essential-reactjs-interview-questions-du1084ym1

https://tylermcginnis.com/react-interview-questions/

## React Easy

**Criar um componente Hello world**

**Formas de declarar Componentes que conheces**

**Que métodos do lifecycle conheces?**

**Criar um contador com um botao de incremento**

## React Mid

**O que é o JSX?**

**O que é o Virtual DOM?**

**Cria um Componente que carrega a info do utilizador quando monta e sempre que o user_id mude**

https://codesandbox.io/s/rzrql382n

**Diferença entre ComponentDidMount, ComponentWillMount e o construtor**

## React advanced
### State management
### Code reuse/Hooks/HOCs/Render props
### Context API
### Performance

# Engenharia
## Unit testing
## Code reviews
