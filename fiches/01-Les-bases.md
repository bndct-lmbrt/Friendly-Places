---
title: Les bases de JavaScript
description: Petite présentation des variables, de la console et des opérateurs.
image_url: https://github.com/Amanda-Martinez/Friendly-Places/blob/master/fiches/img/variables.jpg?raw=true
---
# Les bases de JavaScript

## Console
La console de votre navigateur permet de dialoguer rapidement en JavaScript. Sur Firefox, vous pouvez accéder à cet outil en sélectionnant l’option *console web* dans le menu *outils*

*=> outils => développement web => console web*

Une console Web ça ressemble à :
```javascript
>>
```

Vous pouvez tester en essayant de saisir du JavaScript que la console va se charger d’interpréter.

Par exemple :
```javascript
>> 2+2
```

## Calculer
Vous pouvez utiliser les opérateurs suivants pour tester les capacités de la console en calcul mental :
- / : slash pour diviser
- * : astérisque pour multiplier
- + et - : Plus et moins pour additionner et soustraire

```javascript
>> 2+2*189/3-59
```

## Écrire
Pour que la console répète vos écrits vous pouvez utiliser les simples guillemets :

```javascript
>> 'Alan Vega, au revoir'
```

## Tester
Vous pouvez tester des expressions avec les opérateurs suivants :
- > : Supérieur - 5 > 2
- < : Inférieur - 5 < 2
- === : Équivalent - 5 === 3+2
- !== : Différent - 5 !== 6
- <= et >= : Inférieur ou égal et supérieur ou égal

```javascript
>> 'Bonjour' === 'Bonjour'
```

## Assignement
L'opérateur = permet d'assigner une valeur à un label.

```javascript
>> pi = 3.14
```

Nous venons de créer une variable *pi* en lui assignant la valeur *3.14*.

```javascript
>> pi
```

Pour séparer la partie entière de la partie décimale on utilise le point.

Pour le moment, sans rentrer dans l’explication, lorsque nous effectuerons un assignement nous utiliserons le mot clé *const* avant le label.

```javascript
>> const pi = 3.14
```

Juste une petite chose à savoir, vous ne pouvez pas réassigner une autre valeur à un même label lorsque vous utilisez *const*

```javascript
>> const pi = 3.14
>> const pi = 3.141
x SyntaxError: redeclaration of const odd
```

Si vous êtes sur la console de votre navigateur vous devrez par exemple recharger votre page pour pouvoir faire vos gammes autour des exemples que nous proposerons.