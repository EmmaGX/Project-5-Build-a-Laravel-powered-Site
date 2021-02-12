# Project-5-Build-a-Laravel-powered-Site
Project Instructions
To complete this project, follow the instructions below. If you get stuck, 
ask a question on Slack or in the Treehouse Community.

 10 steps
1. IGNORE PACKAGES! When creating a new repository, you can choose 
    "Git Ignore" and then "Laravel" to ignore the vendor folder. 
    You can also add or edit your .gitignore folder.
2. Use the supplied mockup files to build a Pet Adoption application using Laravel.
3. Use composer to install Laravel and its dependencies and create a Laravel app using the following command:
composer create-project --prefer-dist laravel/laravel=^6 <app name> 
Save all static assets such as css, js, and the favicon.ico into the public directory, accordingly.

4. Add necessary routes for each page or view: index, cats and dogs
5. Create index.blade.php view as the homepage. This view contains a featured pet and lists of both cat and dog images.
6. Create cats.blade.php view as the cats page. This view contains only cat images.
7. Create dogs.blade.php view as the dogs page. This view contains only dog images.
8. Create views for the head, nav, and footer as follows: head.blade.php, nav.blade.php, and footer.blade.php.
9.Refactor views by moving code into their own views, using @include for the head, nav, and footer. The body content is different on each page so leave the body content in place.
