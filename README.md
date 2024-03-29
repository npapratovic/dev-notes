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

9) Process large csv in Laravel with jobs and chunks [https://laravel-news.com/how-to-process-large-csv-files-with-laravel](https://laravel-news.com/how-to-process-large-csv-files-with-laravel)
    
11) TIL after you clone repo, there is chance that now all commits will be pulled, so its necesary to do `git fetch origin` (this way you sync local with remote commits) and after that `git pull` so you have latest files locally See more: https://docs.github.com/en/pull-requests/committing-changes-to-your-project/troubleshooting-commits/commit-exists-on-github-but-not-in-my-local-clone

12) https://www.honeybadger.io/blog/laravel-artisan-processes/ An extensive guide for processes and Artisan commands in Laravel

13) How to build Laravel API from scratch https://laraveldaily.com/course/api-laravel

14) https://dev.to/mikevarenek/understanding-laravel-traits-471g Practial use of Laravel traits, nice example: API Response Trait
