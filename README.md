## PeakData FE developer test task

Hello! This is the PeakData task for FE developer.

### In order to start 

1. pull this repo
2. run `composer install`
3. run `npm install`
3. run `npm run dev`
4. run `php artisan serve`
5. in the browser navigate to `http://127.0.0.1:8000/`
6. in order to go into dev-mode run `npm run watch`

**Note:** you need to create your `.env` file and specify DB connection there  

### Task

You need to implement ability to add comments and comments on comments, and [even] comments on comments on comments.

As you might already guess - a nested level of commenting must be unlimited.

Please cover the backend functionality with tests.

On the `/` page there is a hardcoded structure of how it should approx looks like.
Please feel free to reuse or create your own one.
Also, don't forget to add some styles to make it looks better.
