# Exercícios: Módulo 01

## 1º exercício
Crie uma função que dado o objeto a seguir:

```javascript
var endereco = {
 rua: "Rua dos pinheiros",
 numero: 1293,
 bairro: "Centro",
 cidade: "São Paulo",
 uf: "SP"
};
```

Retorne o seguinte conteúdo:

```
O usuário mora em São Paulo / SP, no bairro Centro, na rua "Rua dos Pinheiros" com
nº 1293.
```
[Visualizar](modulo01ex01.html)

## 2º exercício
Crie uma função que dado um intervalo (entre x e y) exiba todos número pares:

```javascript
function pares(x, y) {
 // código aqui
}
pares(32, 321);
```
[Visualizar](modulo01ex02.html)

## 3º exercício
Escreva uma função que verifique se o vetor de habilidades passado possui a habilidade "Javascript" e retorna um booleano _true/false_ caso exista ou não.

```javascript
function temHabilidade(skills) {
 // código aqui
}
var skills = ["Javascript", "ReactJS", "React Native"];
temHabilidade(skills); // true ou false
```
[Visualizar](modulo01ex03.html)

## 4º exercício
Escreva uma função que dado um total de anos de estudo retorna o quão experiente o usuário é:

```javascript
function experiencia(anos) {
 // código aqui
}
var anosEstudo = 7;
experiencia(anosEstudo);
// De 0-1 ano: Iniciante
// De 1-3 anos: Intermediário
// De 3-6 anos: Avançado
// De 7 acima: Jedi Master
```
[Visualizar](modulo01ex04.html)

## 5º exercício
Dado o seguinte vetor de objetos:

```javascript
var usuarios = [
 {
 nome: "Diego",
 habilidades: ["Javascript", "ReactJS", "Redux"]
 },
 {
 nome: "Gabriel",
 habilidades: ["VueJS", "Ruby on Rails", "Elixir"]
 }
];
```

Escreva uma função que produza o seguinte resultado:

```
O Diego possui as habilidades: Javascript, ReactJS, Redux
O Gabriel possui as habilidades: VueJS, Ruby on Rails, Elixir
```
[Visualizar](modulo01ex05.html)
