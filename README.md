# dev-notes

1) Laravel API toolkit: https://laravel-news.com/laravel-api-toolkit

2) php artisan make:model "Cars" -m // create model with migration

3) https://laraveldaily.com/lesson/eloquent-the-expert-level/artisan-make-model-options Eloquent: The Expert Level 

4) https://benjamincrozat.com/generate-laravel-factories-chatgpt generate laravel factories with chat gpt

5) When to use Traits, Interface and Abstract classes in PHP https://www.youtube.com/watch?v=x9bj30cWolA

 - An Abstract Class **can contain method signatures as well as common methods**, but can't be instantiated on its own. Good for creating a common parent to share between classes.
 - A Trait is a group of properties and methods for code re-use - **common methods and properties**, and multiple can be added to a single class. Good for organization and reducing repetition.
 - An Interface is a set of method signatures (no properties) to **enforce implementation** in the class they're added to. Good for adding structure and standardization.

In other words, Interfaces are blueprints for classes (they contain method declarations, not body), Traits contain reusable methods and properties and each class can use multiple traits, and Abstract classes are extended, they can contain abstract functions so they have only declaration not the body, and are kind of mix of Traits and Interfaces, cannot be instantieted   

6) https://www.freecodecamp.org/news/react-hooks-useeffect-usestate-and-usecontext/ How to Use React Hooks – useEffect, useState, and useContext Code Examples

7) https://nolanlawson.com/2023/12/02/lets-learn-how-modern-javascript-frameworks-work-by-building-one/

8) https://www.youtube.com/watch?v=Uet-bpytdaw extract validation from controller to request class

9) Process large csv in Laravel with jobs and chunks https://laravel-news.com/how-to-process-large-csv-files-with-laravel?utm_medium=email&utm_campaign=Laravel%20Blade%20session%20directive%20Filament%20v31%20Processing%20large%20CSV%20files%20Tailwind%20v34%20and%20more%20-%20493&utm_content=Laravel%20Blade%20session%20directive%20Filament%20v31%20Processing%20large%20CSV%20files%20Tailwind%20v34%20and%20more%20-%20493+CID_957274ed0bd2b99edbc22cb1b269c72a&utm_source=email%20marketing&utm_term=--if%20mso%20endif--%20Read%20more--if%20mso%20endif--%20--if%20mso%20endif--

10) TIL after you clone repo, there is chance that now all commits will be pulled, so its necesary to do `git fetch origin` (this way you sync local with remote commits) and after that `git pull` so you have latest files locally See more: https://docs.github.com/en/pull-requests/committing-changes-to-your-project/troubleshooting-commits/commit-exists-on-github-but-not-in-my-local-clone  
