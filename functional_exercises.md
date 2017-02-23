# Introduction à la programmation fonctionnelle - Exercices
---

* Créer une fonction ```add(n)``` qui additionne ```n``` à un nombre quand on l'apelle
  ```
  console.log(add(3)(5)) // 8
  ```

* Créer une fonction qui renvoie la moyenne des éléments d'un tableau
  ```
  console.log(getMoyenne([1, 2, 3, 4]) // 2.5
  ````

* Créer une fonction qui prend pour paramètre une autre fonction et un tableau, et qui renvoie la fonction donnée en paramètre avec pour argument chaque éléments du tableau
  `function(func, [arg1, arg2, arg3])` => `func(arg1, arg2, arg3)`
  
* Transformez le code suivant en utilisant la méthode map()
  ```
  function add2(numbers) {
    var result = []
    for (var i = 0; i < numbers.length; i++) {
      result.push(numbers[i] + 2)
    }
    return result
  }
  ```
* Etant donné un tableau d'objet contenant le nom et le pays d'origine de personnes, créez une fonction permettant de filtrer les personnes selon leur pays
  ```
  var users = [
    { name: 'Pierre', country: 'France' },
    { name : 'Peter', country: 'England' },
    { name: 'Pedro', country: 'Spain' }
  ]
  filterByCountry(users, 'France') // Pierre
  ```
  
* Utilisez la méthode reduce() pour renvoyer un objet contenant chaque éléments d'un tableau et le nombre de fois qu'ils apparaissent dans celui-ci
  ```
  var words = ['Apple', 'Banana', 'Apple', 'Kiwi', 'Kiwi', 'Kiwi']
  
  console.log(countWords(words)) // { Apple: 2, Banana: 1, Kiwi: 3 }
  ```
  