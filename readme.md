# CodeIgniter WebSocket Library Example
CodeIgniter library realtime communication by using Websocket technology and Ratchet ([Socketo.me](http://socketo.me) & [codeigniter-websocket](https://github.com/takielias/codeigniter-websocket))

## :books: Dependencies

- PHP 5.6+
- CodeIgniter Framework (3.1.* recommanded)
- Composer
- PHP sockets extension enabled

## :beginner: Installation

### :arrow_right: Step 1 : Library installation by Composer

Clone The Repository 
```sh
git clone https://github.com/takielias/codeigniter-websocket-example.git
```

Run the following command in the folder of your project :
```sh
composer install
```

### You'r almost done :heavy_check_mark:

Open you'r command prompt then type the command bellow in you'r project folder :
```sh
php index.php welcome index
```

#### :arrow_right: Test the App
Open two pages of your project on following url with different IDs :

`http://localhost/codeigniter-websocket-example/index.php/user/index/1`

`http://localhost/codeigniter-websocket-example/index.php/user/index/2`

:heavy_exclamation_mark: In my example, **recipient_id** is defined by **user_id**, as you can see, it's the **auth callback** who defines recipient ids.

If you have something like that, everything is ok for you:

![user_1](https://user-images.githubusercontent.com/38932580/57090224-21851500-6d28-11e9-9321-20d02e146d62.png)


![user_2](https://user-images.githubusercontent.com/38932580/57090269-44afc480-6d28-11e9-8ea1-30079a3a47e9.png)


## Bugs :bug: or feature :muscle:
Be free to open an issue or send pull request
