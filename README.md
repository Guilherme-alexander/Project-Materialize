<p align="center">
  <a href="http://materializecss.com/">
    <img src="http://materializecss.com/res/materialize.svg" width="150">
  </a>
</p>
<h1 align="center">
  framework Css materialize
  
[Download materialize](https://materializecss.com/getting-started.html)
</h1>

## [link preview clone page](https://guilherme-alexander.github.io/Project-Materialize/)

## [link preview original page](https://materializecss.com/templates/starter-template/preview.html)

# HTML Setup
Next you just have to make sure you link the files properly in your webpage. Generally it is wise to import javascript files at the end of the body to reduce page load time. Follow the example below on how to import Materialize into your webpage.
```HTML

  <!DOCTYPE html>
  <html>
    <head>
      <!--Import Google Icon Font-->
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
      <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    </head>

    <body>

      <!--JavaScript at end of body for optimized loading-->
      <script type="text/javascript" src="js/materialize.min.js"></script>
    </body>
  </html>

```

# CDN
You can find all the versions of the CDN at [cdnjs](https://cdnjs.com/libraries/materialize)
```HTML

  <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
            

```

## code used Header

```HTML

  <nav class="light-blue lighten-1">
    <div class="nav-wraper container">
        <a id="logo-container" class="brand-logo" href="#">Minha Logo</a>
        <ul class="right hide-on-med-and-down">
          <li><a href="#">Home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">contact</a></li>
        </ul>
        <ul id="slide-out" class="sidenav">
          <li><a href="#">Home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">contact</a></li>
        </ul>
        <a href="#" data-target="slide-out" class="sidenav-trigger"><i class="material-icons">menu</i></a>
    </div>
  </nav>

```

## code used Slider
```HTML

  
<div class="section no-pad-bot" id="index-banner">

  <div class="container">

    <h1 class="header center orange-text">Stater Template</h1>

    <div class="row center">
      <h5 class="header col s12">Meu exemplo de texto do slider</h5>
    </div><!-- row -->
    <div class="row center">
      <a href="#" class="btn-large waves-effect waves-light orange">My Button</a>
    </div><!-- row -->

  </div><!-- container -->

</div><!-- section -->

```

## code used banner 
```HTML

<div class="section no-pad-bot" id="index-banner">

  <div class="container">

    <h1 class="header center orange-text">Stater Template</h1>

    <div class="row center">
      <h5 class="header col s12">Meu exemplo de texto do slider</h5>
    </div><!-- row -->
    <div class="row center">
      <a href="#" class="btn-large waves-effect waves-light orange">My Button</a>
    </div><!-- row -->

  </div><!-- container -->

</div><!-- section -->

```

## code used card
```HTML

  
<div class="container">
  <div class="section">
      
    <div class="row">
      <div class="col m4 s12">
        <div class="icon-block">
          <h2 class="center light-blue-text"><i class="material-icons">flash_on</i></h2>
          <h5 class="center orange-text">Texto da Chamada</h5>
          <p class="center">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Recusandae esse placeat voluptatibus consequatur.</p>
        </div><!-- icon-block -->
      </div><!-- col -->

      <div class="col m4 s12">
        <div class="icon-block">
          <h2 class="center light-blue-text"><i class="material-icons">flash_on</i></h2>
          <h5 class="center orange-text">Texto da Chamada</h5>
          <p class="center">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Recusandae esse placeat voluptatibus consequatur.</p>
        </div><!-- icon-block -->
      </div><!-- col -->

      <div class="col m4 s12">
        <div class="icon-block">
          <h2 class="center light-blue-text"><i class="material-icons">flash_on</i></h2>
          <h5 class="center orange-text">Texto da Chamada</h5>
          <p class="center">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Recusandae esse placeat voluptatibus consequatur.</p>
        </div><!-- icon-block -->
      </div><!-- col -->
    </div><!-- row -->

  </div><!-- section -->
</div><!-- container -->

```

## code used footer

```HTML


<footer class="page-footer light-blue">
  <div class="container">
    <div class="row">
      <div class="col l6 s12">
        <h5 class="white-text">Footer Content</h5>
        <p class="grey-text text-lighten-4">You can use rows and columns here to organize your footer content.</p>
      </div>
      <div class="col l4 offset-l2 s12">
        <h5 class="white-text">Links</h5>
        <ul>
          <li><a class="grey-text text-lighten-3" href="#!">Facebook</a></li>
          <li><a class="grey-text text-lighten-3" href="#!">Instagram</a></li>
          <li><a class="grey-text text-lighten-3" href="#!">Youtube</a></li>
          <li><a class="grey-text text-lighten-3" href="#!">Whatsapp</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="footer-copyright">
    <div class="container">
    © 2014 Copyright Name
    <a class="grey-text text-lighten-4 right" href="#!">More Links</a>
    </div>
  </div>
</footer>

```
