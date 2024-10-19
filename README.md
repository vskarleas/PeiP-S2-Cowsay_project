# INF203 Cowsay Project – Université Grenoble-Alpes 2021-2022
## Projet Cowsay

### 1. Présentation du Projet
Le projet débute le premier jour du cours INF203 et s’achève lors de la dernière semaine de cours. Cette dernière marque la date limite de rendu (dimanche soir minuit de la dernière semaine). Vous pouvez progresser sur le projet à votre rythme, mais il est recommandé de ne pas prendre de retard. Par exemple, la partie "Bash" doit être terminée au moment où les premiers cours de "C" débuteront.

#### 1.1 Objectif du projet
L’objectif principal du projet est de découvrir le monde de **cowsay**, un programme qui affiche des vaches avec des bulles de texte. Au cours du projet, vous réaliserez les objectifs suivants :

1. **Préliminaires** : Découvrir la commande `cowsay` via son manuel (`man cowsay`) et explorer toutes les options disponibles.
2. **Bash** : Implémenter un script Bash permettant à la vache de réciter des suites de nombres, comme les nombres premiers ou les nombres de Fibonacci.
3. **C** : Recoder `cowsay` en langage C, en y ajoutant de nouvelles fonctionnalités.
4. **Automates** : Créer un "cow-Tamagoshi" qui doit être nourri et survit aussi longtemps que possible.

#### 1.2 Rapport attendu
Le compte-rendu doit être rédigé en texte simple, Markdown, Org ou en LaTeX. Il doit inclure les codes sources, les résultats des tests et des commentaires explicites sur vos choix, difficultés rencontrées, et stratégies d’adaptation. Les idées originales et avancées seront fortement valorisées.

---

### 2. Préliminaires
Dans cette première section, vous devez explorer le programme `cowsay` en utilisant la commande suivante :
```bash
man cowsay
```
En explorant le manuel, vous devrez lister les options disponibles, les expliquer et donner des exemples d’exécution dans votre rapport.

### 3. Bash
Dans cette section, l'objectif est de créer plusieurs scripts Bash où la vache récite des suites de nombres :

1. **cow kindergarten** : La vache compte de 1 à 10 avec une pause d’une seconde entre chaque chiffre.
2. **cow primaryschool** : La vache compte jusqu’à un nombre `n` donné en argument.
3. **cow highschool** : La vache récite la suite des carrés jusqu’à `n²`.
4. **cow college** : La vache récite la suite des nombres de Fibonacci inférieurs à `n`.
5. **cow university** : La vache récite les nombres premiers inférieurs à `n`.
6. **smart cow** : La vache résout une simple opération arithmétique (ex : "3 + 11").
7. **crazy cow** : Une vache qui fait quelque chose d'original et surprenant (l’option la plus créative).

### 4. C
Dans cette seconde partie du projet, vous devez recoder `cowsay` en C en ajoutant des fonctionnalités :

1. **newcow.c** : Affiche une vache sans la bulle de texte.
2. Ajouter des options comme `--eyes` pour personnaliser les yeux de la vache.
3. Ajouter des options supplémentaires (ex : allonger la queue de la vache).
4. Créer une vache animée avec des mouvements de la langue ou des yeux.
5. Créer une "vache qui lit" (reading cow), qui lit un fichier caractère par caractère avec une pause d'une seconde entre chaque.

### 5. Automates
Dans cette dernière section, vous allez créer un jeu vidéo où vous devez nourrir une vache pour qu’elle survive le plus longtemps possible. Vous utiliserez un automate pour modéliser les trois états de la vache :

1. **Liferocks** (en pleine forme)
2. **Lifesucks** (ne se sent pas bien)
3. **Byebyelife** (décédée)

Le but du jeu est de nourrir la vache afin qu’elle survive le plus longtemps possible, avec un niveau de santé qui évolue en fonction de l'alimentation. Chaque action du joueur influencera la santé de la vache et le stock de nourriture.

### 6. Bonus
Si vous êtes créatif, vous pouvez ajouter des fonctionnalités supplémentaires pour enrichir le jeu, comme des animations plus complexes ou des interactions avec d'autres éléments du jeu.

---

## License Information

This project is licensed under the MIT License.

---

---

# INF203 – University of Grenoble-Alpes 2021-2022
## Cowsay Project

### 1. Project Overview
The project begins on the first day of the INF203 course and ends during the final week of the course. The final week marks the submission deadline (Sunday night, midnight). You can progress at your own pace, but it is recommended to stay ahead of the course schedule. For example, the "Bash" section should be completed before the first "C" lessons start.

#### 1.1 Project Objective
The main goal of this project is to explore the world of **cowsay**, a program that displays cows with speech bubbles. Throughout the project, you will complete the following objectives:

1. **Preliminaries**: Discover the `cowsay` command via its manual (`man cowsay`) and explore all available options.
2. **Bash**: Implement a Bash script that has the cow recite various number sequences, such as prime numbers or Fibonacci numbers.
3. **C**: Recoding `cowsay` in C, adding new functionalities.
4. **Automata**: Build a "cow-Tamagoshi" that needs to be fed to survive as long as possible.

#### 1.2 Report Expectations
The report should be written in plain text, Markdown, Org, or LaTeX. It should include source code, test results, and clear commentary on your choices, difficulties encountered, and strategies for adaptation. Original and advanced ideas will be highly valued.

---

### 2. Preliminaries
In this section, you must explore the `cowsay` program using the following command:
```bash
man cowsay
```
Explore the manual to list the available options, explain them, and provide execution examples in your report.

### 3. Bash
In this section, the goal is to create multiple Bash scripts where the cow recites number sequences:

1. **cow kindergarten**: The cow counts from 1 to 10 with a 1-second pause between each number.
2. **cow primaryschool**: The cow counts up to a number `n` provided as an argument.
3. **cow highschool**: The cow recites the square numbers up to `n²`.
4. **cow college**: The cow recites Fibonacci numbers less than `n`.
5. **cow university**: The cow recites prime numbers less than `n`.
6. **smart cow**: The cow solves a simple arithmetic operation (e.g., "3 + 11").
7. **crazy cow**: A cow that does something particularly crazy or original (the most creative option).

### 4. C
In this section, you will recode `cowsay` in C and add new features:

1. **newcow.c**: Displays a cow without the speech bubble.
2. Add options like `--eyes` to customize the cow's eyes.
3. Add extra features (e.g., extend the cow's tail).
4. Create an animated cow with moving eyes or tongue.
5. Create a "reading cow" that reads a file character by character with a one-second pause between each character.

### 5. Automata
In this section, you will create a video game where you need to feed a cow to help it survive as long as possible. You will use an automaton to model the cow's three states:

1. **Liferocks** (healthy)
2. **Lifesucks** (feeling unwell)
3. **Byebyelife** (deceased)

The goal is to feed the cow so it survives as long as possible, with its health level evolving based on the food intake. The player's actions will influence the cow's health and food stock.

### 6. Bonus
If you're feeling creative, you can add additional features to enhance the game, such as more complex animations or interactions with other game elements.

---

### License Information

**PeiP-S2-Cowsay_project** © 2024 by **Vasileios Filippos Skarleas** and **Nada Yacine** is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) and the MIT license. 

This work also includes content that is not the property of **Vasileios Filippos Skarleas** and **Nada Yacine** and is subject to copyright and other licenses from their respective owners.
