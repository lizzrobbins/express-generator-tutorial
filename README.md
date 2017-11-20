# express-generator-tutorial

### Technical Tutorial: How to Spin Up a Server Using express-generator


Express-generator is a skeleton made of folders, files, and code that is used to quickly spin up an Express server. Getting this set up is quick and easy!

Begin in your CLI.  If you don’t have express-generator already installed, you will need to install it:

```npm install express-generator -g```

Once installed, you will need to start initiate express-generator with the following code.  
*Please note: --git creates a .gitignore file, and --hbs makes hbs the view engine. Jade is the default view if no other is specified*

```express --git --hbs .```

After you have initiated express-generator, you will need to download the necessary dependencies:

```npm install```

You are now ready to start your server! Enter the following code into your CLI:

```npm start```

Once your server is running, go to http://localhost:3000/ to see if the Welcome Express message displays on the screen. If it does, you are one step closer to displaying data on your page!
