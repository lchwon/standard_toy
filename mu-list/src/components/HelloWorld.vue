<template>
  <!--<div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div> -->
  <div>
  <div class="preloader">
    <div class="spinner">
      <div class="dot1"></div>
      <div class="dot2"></div>
    </div>
  </div>
    <!-- End Laoding page  -->

    <!-- Begin HorizontalTab style 6 -->
    <section class="section-full image-bg">

      <div class="container">

        <div class="row">

          <div class="col-md-12">

            <a href="/"><div class="responsive-logo hidden-lg hidden-md hidden-sm"><img src="images/welcomepage_images/logo.png"></div></a>
            
            <!-- Begin .HorizontalTab -->
            <div class="VerticalTab VerticalTab_hash_scroll VerticalTab_6 tabs_ver_6">
            
              <ul class="resp-tabs-list hor_1">
                <a href="index.html"><div class="logo"><img src="images/welcomepage_images/logo.png"></div></a>
                <li class="tabs-1" data-tab-name="profile"><span class="tabs-text">{{ enter }}</span></li>
                <li class="tabs-2" data-tab-name="resume"><span class="tabs-text">About Us</span></li>
                <li class="tabs-3" data-tab-name="portfolio"><span class="tabs-text">Our Projects</span></li>             
                <li class="tabs-4" data-tab-name="contact"><span class="tabs-text">Contact Us</span></li>
              </ul>
              
              <div class="resp-tabs-container hor_1 tabs_scroll">
                
                <div class="fc-tab-1">
                
                  <div class="home-container">
                    <div class="row">
                      <div class="col-md-6">
                        <div class="left-content">
                          <div class="left-line"></div>  
                          <h2>Clean, Creative &amp; Unique <em>Short</em></h2>
                          <p>{{welcomeText}}</p>
                          <div class="primary-button">
                            <a href="#">Discover More</a>
                          </div>
                        </div>
                      </div>
                      <div class="col-md-6">
                        <div class="right-content">
                          <img src="images/welcomepage_images/home-image.jpg">
                        </div>
                      </div>
                    </div>
                  </div>
                  
                </div>
                
                <div class="fc-tab-2">
                
                  <div class="about-container">
                    <div class="row">
                      <div class="col-md-12">
                        <h2>More info about <em>Short</em></h2>
                        <div class="under-line"></div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc purus ligula, ullamcorper id velit id, vestibulum auctor sapien. Sed quis mauris eget sem <em>imperdiet rhoncus hendrerit</em> sed neque.<br><br>Praesent dictum at erat <em>consectetur imperdiet</em>. Vivamus lobortis eros quis elementum egestas. Fusce sed lorem sed tellus convallis pulvinar non eget erat. Nunc sapien mauris, molestie sed interdum vel, pharetra et metus.</p>
                        <img src="images/welcomepage_images/about-image.jpg">
                      </div>
                    </div>
                  </div>
                  
                </div>
                
                <div class="fc-tab-3">

                  <div class="owl-carousel owl-theme projects-container">
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Awesome Project</h4>
                              <a href="images/welcomepage_images/item-01.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-01.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Awesome Two</h4>
                              <a href="images/welcomepage_images/item-02.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-02.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Awesome Three</h4>
                              <a href="images/welcomepage_images/item-03.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-03.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Project Four</h4>
                              <a href="images/welcomepage_images/item-04.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-04.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Fifth Project</h4>
                              <a href="images/welcomepage_images/item-05.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-05.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Sixth Project</h4>
                              <a href="images/welcomepage_images/item-06.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-06.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Project Seven</h4>
                              <a href="images/welcomepage_images/item-07.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-07.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Awesome Eight</h4>
                              <a href="images/welcomepage_images/item-02.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-02.jpg">
                        </div>
                      </div>
                    </div>
                    <div>
                      <div class="project-item">
                        <div class="thumb-holder">
                          <div class="hover-effect">
                            <div class="hover-content">
                              <h4>Awesome Nine</h4>
                              <a href="images/welcomepage_images/item-01.jpg" data-lightbox="image-1"><img src="images/welcomepage_images/project-icon.png"></a>
                            </div>
                          </div>
                          <img src="images/welcomepage_images/project-item-01.jpg">
                        </div>
                      </div>
                    </div>
                  </div>
                  
                </div>
                
                <div class="fc-tab-4">
                
                  <div class="contact-container">
                    <div class="row">
                      <div class="col-md-6">
                        <div class="contact-form">
                          <div class="heading">
                            <h2>Say Hello</h2>
                          </div>
                          <form id="contact" action="" method="post">
                            <fieldset>
                              <input name="name" type="text" class="form-control" id="name" placeholder="Your Name" required="">
                            </fieldset>
                            <fieldset>
                              <input name="email" type="email" class="form-control" id="email" placeholder="Email" required="">
                            </fieldset>
                            <fieldset>
                              <textarea name="message" rows="6" class="form-control" id="message" placeholder="Message" required=""></textarea>
                            </fieldset>
                            <fieldset>
                              <button type="submit" id="form-submit" class="btn">Submit</button>
                            </fieldset>
                          </form>
                        </div>
                      </div>
                      <div class="col-md-6">
                        <div class="more-info">
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc purus ligula, ullamcorper id velit id, vestibulum auctor sapien. Sed quis mauris eget sem <em>imperdiet rhoncus hendrerit</em> sed neque.<br><br>Praesent dictum at erat <em>consectetur imperdiet</em>. Vivamus lobortis eros quis elementum egestas. Fusce sed lorem sed tellus convallis pulvinar non eget erat. Nunc sapien mauris, molestie sed interdum vel, pharetra et metus.<br><br><em>1142 Bee Street<br>Grand Rapids, MI 49503</em></p>
                        </div>
                      </div>
                    </div>
                  </div>
                  
                </div>
                
                
              </div>
            </div>
            <!-- End .HorizontalTab -->
          
          </div>
          
        </div>
        
      </div>

    </section>
    <!-- End HorizontalTab style 6 -->
    

      <!-- <footer>
        <p>Copyright &copy; 2017 Your Company 
                                
        | Design: <a href="http://www.templatemo.com" target="_parent"><em>template mo</em></a></p>
      </footer> -->
    </div> <!-- /container -->        

    
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    //msg: String
    enter: String,
    welcomeText: String
  }
}
</script>

<script setup>
  const welcomeText="Hello Mu-List Project";
  const enter="Mu-List Enter";
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
