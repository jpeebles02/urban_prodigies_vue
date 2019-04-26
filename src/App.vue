<template>
  <div id="app">
    <header id="fh5co-header" role="banner">
      <div class="container">
        <div class="header-inner">
          <h1>
            <a href="/">Home<span>.</span></a>
          </h1>
          <nav role="navigation">
            <ul>
              <!-- <li><a href="products.html">Products</a></li> -->

              <li><a href="/artists">Ghetto Geniuses</a></li>
              <li><a href="/videos">Interviews</a></li>
              <!-- <li><a href="pricing.html">Pricing</a></li> -->
              <li><a href="/about">About</a></li>
              <!-- <li><a href="contact.html">Contact</a></li> -->
              <!-- <li class="cta"><a href="#">Get started</a></li> -->
            </ul>
          </nav>
        </div>
      </div>
    </header>
    <router-view />
    <footer id="fh5co-footer" role="contentinfo">
      <div class="container">
        <div class="col-md-3 col-sm-12 col-sm-push-0 col-xs-12 col-xs-push-0">
          <h3>References</h3>
          <p>
            <a href="https://www.sxsw.com/"> SXSW</a> |
            <a href="https://almvghty.com/"> ALMVGHTY CLOTHING</a>
          </p>
          <p>
            <a href="/about" class="btn btn-primary btn-outline with-arrow btn-sm"
              >Learn more <i class="icon-arrow-right"></i
            ></a>
          </p>
        </div>

        <div class="col-md-2 col-md-push-1 col-sm-12 col-sm-push-0 col-xs-12 col-xs-push-0">
          <h3>Follow Us</h3>
          <ul class="fh5co-social">
            <li>
              <a href="https://twitter.com/"><i class="icon-twitter"></i></a>
            </li>
            <li>
              <a href="https://www.facebook.com/"><i class="icon-facebook"></i></a>
            </li>
            <li>
              <a
                href="https://accounts.google.com/signin/v2/identifier?passive=1209600&continue=https%3A%2F%2Faboutme.google.com%2Fu%2F0%2F%3Freferer%3Dgplus&followup=https%3A%2F%2Faboutme.google.com%2Fu%2F0%2F%3Freferer%3Dgplus&flowName=GlifWebSignIn&flowEntry=ServiceLogin"
                ><i class="icon-google-plus"></i
              ></a>
            </li>
            <li>
              <a href="https://www.instagram.com/?hl=en"><i class="icon-instagram"></i></a>
            </li>
          </ul>
        </div>

        <div class="col-md-12 fh5co-copyright text-center">
          <p>
            &copy; 2016 Undergraduate Research Symposium: Gheto Genius Universe. All Rights Reserved.
            <!-- <span
              >Designed with <i class="icon-heart"></i> by
              <a href="http://freehtml5.co/" target="_blank">FreeHTML5.co</a> Colored Icons by
              <a href="https://dribbble.com/TrinhHo" target="_blank">Trinh Ho</a> Demo Images by
              <a href="http://unsplash.com/" target="_blank">Unsplash</a></span> -->
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
#navigation {
}
</style>
