[Go back to README](https://github.com/leonardo-cabral67/today_i_learned/tree/main)

## Creating Routes with Laravel.

To create routes with laravel it is very simple:
1. There is a file in `__DIR__/resources/views` where we put our files with `.blade.php` extension. In this case i use blade as my template engine, but if you are using just html, you could put just `.html` as extension, or `.php` for php file.

   ![image](https://github.com/leonardo-cabral67/today_i_learned/assets/80075113/8385f23b-e939-4f5a-a8d4-f94676996bc0)
   
3. There is a file in `__DIR__/routes/web` where we can use a static method from `Route`class. We use this method from  `Illuminate\Support\Facades\Route` and there is a static method called `get` which receives two params: first is the route like "/" and second is a function that and we will return a view.
  2.1. view can receives two arguments, but just the first one is mandatory, it is just a name of our file we created in the first step, e.g. if you create a view file called `posts.blade.php`  you should pass as argument "posts".
  2.2. the other argument is an array of server side props that we will get in our view, e.g. we can fetch data and pass as server side props and display these informations in view.

    ![image](https://github.com/leonardo-cabral67/today_i_learned/assets/80075113/bff3b92e-824b-46c2-b965-95f874e1c563)
