Angular 4 - Notes
====================

This repository is notes of my angular 4 journey. I didn't switched angular 2 because of some reasons. Now I decided to give a shot and getting course about ng4. I will write everthing that I learn in lectures. Maybe this repository guide you too.

Farewell my friend.


The Basics
-----------------

### Installation

To develop some applications we need to install node.js first. If you didn't know node.js, please check it before ng4. We will use angular cli. Angular cli will help us creating stuff. Its very useful tool.

```
npm i @angular/cli -g
```

We should install `@angular/cli` with global parameter. This parameter will use global node_modules folder rather than local one.

Now we can use `ng` command in terminal.

### Creating project

To create project we will use `ng` command. Try to type `ng` in terminal if you get error then you failed `Installation` step. Please go there and make sure you did this steps right.

ng command has some more arguments too. We will come to that but rightnow we just have to create a project so we should use `new` argument.

This argument will create a new project structure in current working directory. But we should give some project name to proceed. I will name the project as "my-first-app"

```
ng new my-first-app
```

After using this command in terminal some files will generated by `ng`. It will install necessary packages via npm. Wait until installation is done.

### Serving project

We just create a new project. Proceed to `my-first-app` folder. Use `serve` command of `ng`. It will do packaging stuff and create a http server.

```
cd my-first-app
ng serve
```

In terminal output, there should be a url address. If you can't figure the address then with `--port xxx` parameter, you can change port number to whatever you want.

```
ng serve --port 8080
```

Typescript compiled and Webpack packed your application.

Now try to access to [](http://localhost:8080)

