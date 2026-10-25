# Cat Food Calculator

By Joe Conlin · 24 October 2026

Canonical HTML: https://joeconlin.org/projects/cat-food-calculator/

[Try it](https://calc.catrepairwoman.com) · [Source on GitHub](https://github.com/joeconlin/cat-food-calculator) · [Cat Repairwoman](https://catrepairwoman.com)

![The Cat Food Calculator's first step, asking for a cat's name, current weight, life stage, and activity level, next to a cartoon cat.](https://joeconlin.org/images/cat-food-calculator.jpg)

The live calculator at calc.catrepairwoman.com.

Cat Food Calculator works out how much to feed a cat. Enter its weight, life stage, activity level, and body condition score, and it gives daily calories, a safe weight-loss timeline when one is needed, and a wet and dry meal plan you can print and take home. It handles multi-cat households too.

I built it for [Cat Repairwoman](https://catrepairwoman.com), a cat-only veterinary site with care guides for owners. The vet uses it during exam visits, so the phone layout and the printout are the product.

It’s one static page: no framework, no backend, no logins. The feeding math is vet-validated, and a 111-case golden-master test pins every output, so a refactor can’t quietly change a recommendation. Screenshot tests guard the mobile and print layouts.


