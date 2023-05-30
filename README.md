![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | JS Basic Algorithms

Bienvenue à votre premier laboratoire JavaScript chez Ironhack !

Cet exercice vise à vous familiariser avec les structures de données primitives en JavaScript, que nous avons abordées en classe. N'hésitez pas à vous référer aux supports de cours et ne vous limitez pas ; soyez curieux et utilisez Google pour explorer plusieurs solutions.

<br>

![lab-js-basic-algorithms-code-collaboration-gif](https://education-team-2020.s3.eu-west-1.amazonaws.com/web-dev/lab-js-basic-algorithms-code-collaboration-gif.gif)

<br>

<details>
  <summary>
   <h2>Objectifs d'apprentissage</h2>
  </summary>

  Cet exercice vous permet de pratiquer et d'appliquer les concepts et les techniques enseignés en classe.

  À la fin de cet exercice, vous serez capable de :

  - Déclarer des variables à l'aide des mots-clés `const` et `let` et les utiliser pour stocker des valeurs.
  - Assigner des valeurs aux variables à l'aide d'opérateurs d'assignation (`=` , `+=` , `-=` , etc.).
  - Utiliser des instructions conditionnelles (`if`, `else if`, `else`) et des opérateurs logiques (AND, OR, NOT) pour contrôler le flux du programme.
  - Accéder et comparer des caractères, des sous-chaînes et des longueurs de chaînes de caractères.
  - Manipuler des chaînes de caractères à l'aide de méthodes de base (`toUpperCase()`, `toLowerCase()`, etc.).
  - Comparer des valeurs à l'aide des opérateurs de comparaison (`<` , `>` , `<=` , `>=` , `===`).
  - Utiliser des boucles `for` ou `while` pour itérer sur des chaînes de caractères dans l'ordre normal et inverse.

  <br>
  <hr> 

</details>

## Introduction

Pour cette activité de **pair-programming**, nous utiliserons un [REPL](https://en.wikipedia.org/wiki/Read–eval–print_loop). Pour simplifier les choses autant que possible, nous allons utiliser un REPL JavaScript intégré au navigateur fourni par l'IDE basé sur le navigateur, [repl.it](https://replit.com/languages/javascript).

Prêt à commencer ?

## Exigences

- Forker ce repo
- Cloner ce repo
- Rendez-vous sur [repl.it](https://repl.it/languages/nodejs) et créez un compte (ou connectez-vous si vous en avez un)
- Créez une nouvelle réponse en cliquant sur <kbd>+ Create Repl</kbd>
- apez ceci dans *Code Editor* (l'Éditeur de code) (panneau de gauche)
  ```javascript
  console.log("I'm ready!");
  ```
- Appuyez sur  `run ►`
- Si vous pouvez voir le message dans le panneau de droite, vous êtes vraiment prêt(e) !

  ![lab-js-basic-algorithms-replit-ready](https://education-team-2020.s3.eu-west-1.amazonaws.com/web-dev/lab-js-basic-algorithms-replit-ready.png)

- **Lorsque vous avez terminé complètement, ou à n'importe quel moment après la première itération, copiez votre code dans le fichier `index.js` et suivez les étapes pour la soumission.**

## Soumission

Une fois terminé, exécutez les commandes suivantes :

```bash
git add .
git commit -m "done"
git push origin master
```

Créez une demande d'extraction (Pull Request) afin que les TAs puissent vérifier votre travail.

*Vous devriez faire une demande d'extraction (Pull Request) lorsque vous effectuez une modification significative. Vous ne devriez pas attendre d'avoir terminé complètement cet exercice ou tout autre exercice pour effectuer la demande d'extraction (Pull Request). Après avoir effectué la première demande d'extraction (Pull Request), chaque fois que vous poussez les modifications (en suivant les trois étapes précédentes), votre modification apparaîtra automatiquement dans la demande d'extraction (Pull Request) et les TAs pourront la vérifier.*

<!-- ## Submission -->

<!-- When you are done and you have checked that everything works fine, click on the **Share** button and copy the link from the *Share Link* field. Send this link to your TAs so they can check up on your work.
![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_b2aa98f91affe5d4c5f12f216b069184.png) -->

## Instructions

### Itération 1: Noms et entrées

  1.1 Créez une variable `hacker1` avec le nom du conducteur. <br>
  1.2 Affichez `"The driver's name is XXXX"`. ("Le nom du conducteur est XXXX".) <br>
  1.3 Créez une variable `hacker2` avec le nom du navigateur. <br>
  1.4 Affichez `"The navigator's name is YYYY"` ("Le nom du navigateur est YYYY".)

### Itération 2 : Conditionnelles

  2.1. Selon lequel des noms [est le plus long](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length), affichez :
  <br>
    - `The driver has the longest name, it has XX characters.` (Le conducteur a le nom le plus long, il comporte XX caractères.) or <br>
    - `It seems that the navigator has the longest name, it has XX characters.` (Il semble que le navigateur ait le nom le plus long, il comporte XX caractères.) or <br>
    - `Wow, you both have equally long names, XX characters!` (Wow, vous avez tous les deux des noms de longueur équivalente, XX caractères !).

### Itération 3 : Boucles

  3.1 Imprimez les caractères du nom du conducteur, séparés par un espace, et [en majuscules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase), c'est-à-dire `"J O H N"`.

  3.2 Imprimez tous les caractères du nom du navigateur dans l'ordre inverse, c'est-à-dire `"nhoJ"`.

  3.3 En fonction de l'ordre [lexicographique](https://en.wikipedia.org/wiki/Lexicographical_order) des chaînes, imprimez : <br>
  - `The driver's name goes first.` <br>
  - `Yo, the navigator goes first, definitely.` <br>
  - `What?! You both have the same name?`

### Temps bonus !

#### Bonus 1:

Allez sur le site du [générateur de texte Lorem Ipsum](http://www.lipsum.com/) et :

  - Générez 3 paragraphes. Enregistrez le texte dans une nouvelle variable de chaîne appelée `longText`.
  - Faites compter le nombre de mots dans la chaîne par votre programme.
  - Faites compter le nombre de fois où le mot latin [`et`](https://en.wiktionary.org/wiki/et#Latin)  apparaît par votre programme.

#### Bonus 2:

Créez une nouvelle variable, `phraseToCheck`, contenant une valeur de chaîne de caractères. Écrivez un code pour vérifier si la valeur attribuée à cette variable est un [Palindrome](https://en.wikipedia.org/wiki/Palindrome). Voici quelques exemples de palindromes :

  - "A man, a plan, a canal, Panama!"
  - "Amor, Roma"
  - "race car"
  - "stack cats"
  - "step on no pets"
  - "taco cat"
  - "put it up"
  - "Was it a car or a cat I saw?" and "No 'x' in Nixon".

  **IMPORTANT** : Si vous utilisez Google pour vous aider à trouver une solution à cette itération, vous pourriez tomber sur des solutions avancées qui utilisent des méthodes de chaîne ou de tableau (telles que *join()*, *reverse()*, etc.). Cependant, nous souhaitons que vous appliquiez vos connaissances actuelles et que vous essayiez de trouver une solution en utilisant simplement la boucle `for`, les instructions `if-else` avec certains `break` et `continue`.

__Joyeux codage !__ :heart:

## Extra Resources

- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)

<br>

## FAQs

<br>

<details>
  <summary>Je suis bloqué(e) dans l'exercice et je ne sais pas comment résoudre le problème ni par où commencer.</summary>
  <br>

  Si vous êtes bloqué(e) dans votre code et que vous ne savez pas comment résoudre le problème ou par où commencer, vous devriez prendre du recul et essayer de formuler une question claire sur le problème spécifique auquel vous êtes confronté(e). Cela vous aidera à réduire le problème et à envisager des solutions potentielles.

  Par exemple, s'agit-il d'un concept que vous ne comprenez pas, ou bien recevez-vous un message d'erreur que vous ne savez pas comment corriger ? Il est généralement utile d'essayer d'exprimer le problème le plus clairement possible, y compris tous les messages d'erreur que vous recevez. Cela peut vous aider à communiquer le problème à d'autres personnes et à obtenir éventuellement de l'aide de vos camarades de classe ou de ressources en ligne.

  Une fois que vous avez une compréhension claire du problème, vous pourrez commencer à travailler vers la solution.

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment trouver la longueur d'une chaîne de caractères en JavaScript ?</summary>
  <br>

  Pour trouver la longueur d'une chaîne de caractères, vous pouvez utiliser la propriété `length`. Voici un exemple :

  ```js
  const str = "Hello, world!"";
  console.log(str.length); // 13
  ```

  La propriété `length` renvoie le nombre de caractères dans la chaîne, y compris les espaces et les caractères spéciaux.

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment puis-je boucler sur une chaîne de caractères ?</summary>
  <br>

  Voici un exemple d'utilisation d'une boucle `for` pour boucler sur une chaîne de caractères :

  ```js
  let str = "ironhack";

  for (let i = 0; i < str.length; i++) {
    console.log(str[i]);
  }
  ```

  Ce code va itérer sur chaque caractère de la chaîne `str`. La boucle s'exécutera autant de fois qu'il y a de caractères dans la chaîne.
  À chaque itération, la boucle affichera le caractère actuel dans la console.

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment vérifier si une sous-chaîne existe dans une chaîne donnée ?</summary>
  <br>

  Vous pouvez utiliser la méthode `includes()` pour vérifier si une sous-chaîne existe dans une chaîne donnée.

  Cette méthode renvoie une valeur booléenne (`true` ou `false`) indiquant si la chaîne sur laquelle elle est appelée inclut la sous-chaîne spécifiée en tant qu'argument.

  Exemple:

  ```js
  let str = "hello world";

  console.log(str.includes("hello"));  // true
  console.log(str.includes("world"));  // true
  console.log(str.includes("bye"));    // false
  ```

  <br>

  Vous pouvez également utiliser la méthode `indexOf()`, qui renvoie l'index de la première occurrence de la sous-chaîne dans la chaîne, ou -1 si la sous-chaîne n'est pas trouvée.

  Example:

  ```js
  let str = "hello world";

  console.log(str.indexOf("h"));      // 0
  console.log(str.indexOf("world"));  // 6
  console.log(str.indexOf("bye"));    // -1
  ```

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment convertir une chaîne de caractères en lettres majuscules ou minuscules?</summary>
  <br>

  #### Uppercase

  Pour convertir une chaîne de caractères en lettres majuscules, utilisez la méthode `toUpperCase()`. La méthode `toUpperCase()` renvoie une nouvelle chaîne de caractères avec tous les caractères en majuscules.

  Exemple:

  ```js
  let str = "ironhack";

  console.log(str.toUpperCase());  // "IRONHACK"
  ```

  <br>

  #### Lowercase

  Pour convertir une chaîne de caractères en lettres minuscules, vous pouvez utiliser la méthode `toLowerCase()`. Cette méthode renvoie une nouvelle chaîne de caractères avec tous les caractères en minuscules.

  Exemple:

  ```js
  let str = "IRONHACK";

  console.log(str.toLowerCase());  // "ironhack"
  ```

  Il est important de noter que les méthodes `toUpperCase()` et `toLowerCase()` ne modifient pas la chaîne de caractères originale. Elles renvoient une nouvelle chaîne de caractères qui a été convertie dans le cas désiré.

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment inverser une chaîne de caractères ?</summary>
  <br>

  Vous pouvez utiliser une boucle `for` pour itérer sur les caractères de la chaîne et les ajouter dans l'ordre inverse à une nouvelle chaîne.

  Exemple:

  ```js
  let str = "drawer";
  let reversed = "";

  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }

  console.log(reversed);  // "reward"
  ```

  L'exemple ci-dessus utilise une boucle `for` pour itérer sur les caractères de la chaîne `str` dans l'ordre inverse, en commençant par le dernier caractère et en terminant par le premier caractère. À chaque itération, il ajoute le caractère courant à la chaîne `reversed`.

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Comment créer une chaîne de caractères multi-lignes en JavaScript ?</summary>
  <br>

  Pour créer une chaîne de caractères multi-lignes en JavaScript, vous devez utiliser des gabarits littéraux (template literals). Les gabarits littéraux sont des littéraux de chaîne de caractères indiqués avec des backticks (`). Ils vous permettent d'intégrer des expressions à l'intérieur des valeurs de chaîne de caractères et de créer des chaînes qui s'étendent sur plusieurs lignes.

  Example:

  ```js
  let str = `This is an
  example of a
  multi-line string.`;

  console.log(str);
  ```

  [Retour en haut](#faqs)
</details>

<details>
  <summary>Je ne peux pas pousser les modifications vers le repo. Que dois-je faire ?</summary>
  <br>

Il existe quelques raisons possibles pour lesquelles vous pourriez ne pas être en mesure de *push* (pousser) des modifications vers un dépôt Git :

1. **Vous n'avez pas validé vos modifications** : Avant de pouvoir pousser vos modifications vers le dépôt, vous devez les valider en utilisant la commande `git commit`. Assurez-vous d'avoir validé vos modifications et essayez de pousser à nouveau. Pour ce faire, exécutez les commandes suivantes dans votre terminal à partir du dossier du projet :
  ```bash
  git add .
  git commit -m "Your commit message"
  git push
  ```
2. **Vous n'avez pas la permission de pousser vers le dépôt** : Si vous avez cloné le dépôt directement à partir du dépôt principal d'Ironhack sans effectuer un *Fork* au préalable, vous n'avez pas les droits d'écriture sur le dépôt.
Pour vérifier quel dépôt distant vous avez cloné, exécutez la commande suivante dans votre terminal à partir du dossier du projet :
  ```bash
  git remote -v
  ```
Si le lien affiché est le même que celui du dépôt principal d'Ironhack, vous devrez d'abord faire un Fork du dépôt vers votre compte GitHub, puis cloner votre Fork sur votre machine locale pour pouvoir pousser les modifications.

**Note** : Vous devriez faire une copie de votre code local pour éviter de le perdre lors du processus.

  [Back to top](#faqs)

</details>

