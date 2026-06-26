### 📝 Mettre à jour les tableaux d'un état (Défi 1 sur 4) : Mettre à jour un élément dans le panier

- **Problème résolu :** Implémentation de la logique d'incrémentation d'un produit spécifique dans un panier. L'utilisation de la méthode `.map()` permet de cloner le tableau d'état sans le muter directement, et le _spread operator_ assure la création d'un nouvel objet pour le produit ciblé tout en conservant les autres intacts.
- **Compétence acquise :** Modification propre d'un objet niché à l'intérieur d'un tableau d'état React en combinant `.map()` pour le remplacement d'élément et la déstructuration d'objet (`{ ...product, count: product.count + 1 }`) pour respecter l'immutabilité.
- **Lien vers le code :** [Cliquez ici pour voir l'exercice](https://fr.react.dev/learn/updating-arrays-in-state)
