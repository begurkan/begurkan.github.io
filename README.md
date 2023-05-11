<!doctype html>
<html>
   <head>
      <link rel="icon" href="https://avatars.githubusercontent.com/u/69230350?v=4">
      <title>BEG (thelearn-tech)</title>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <link rel="stylesheet" href="assets/css/main.css">
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
      <script src="https://cdn.jsdelivr.net/gh/google/code-prettify@master/loader/run_prettify.js?autoload=true&amp;skin=sunburst&amp;lang=css" defer=""></script>
      <!-- Version 1.0.1-->
   </head>
   <body>
      <h2></h2>
      <!-- heading 1 -->
      <h1 class="bold topp left" > $ ./Hacker-Theme.sh</h1>
      <h2></h2>
      <!-- gray text --->
      <l class="gray left" >Hacker Themed HTML Template.</l>
      <br>
      <br>
      <!-- buttons -->
      <a href="https://github.com/thelearn-tech/hacker-theme/archive/refs/heads/main.zip" class="button leftmar ">Download as .zip</a> <a href="https://github.com/thelearn-tech/hacker-theme" class="button ">View on Github</a> <a href="pages/hacker-theme-login.html" class="button ">Login</a>
      <!-- horizontal rule-->
      <hr class="hr">
      <!-- paragraph -->
      <br>
      <p>
         Text can be <h class="bold">Bold</h>, <h class="ital">italic</h>, <h class="oblique">oblique</h>, <h class="underline">underline</h>, <h class="overline">overline</h>, <h class="strickthrough">strikethrough</h>or <h class='keyword'>keyword</h>.
      </p>
      <!-- paragraph -->
      <p>
         This is page is recreation of <h class="bold">jekyll-hacker-theme </h>in HTML , CSS & JS
      </p>
      
      <!-- link -->
      <p><a href="https://github.com/pages-themes/hacker" title="jekyll-hacker-theme" target="_self" class="linkk bold">Link to Jekyll Hacker Theme.</a></p>
      
      <p>Next paragraph.</p>
      <!-- link inside a text line -->
      <p>Find details about this page on <a href="https://github.com/thelearn-tech/hacker-theme" title="hacker-theme" target="_self" class="linkk bold"> Github</a>. Original project also can be found on Github.</p>
      
      <h1 class="left topp">Heading 1</h1>
      <!-- paragraph -->
      <p>
         A paragraph following Header 1.
         <h class="bold">Github</h>
         where the world builds software.
         Millions of developers and companies build, ship, and maintain their software on GitHub. The largest and most advanced development platform in the world.
      </p>
      <h2 class="left">Heading 2</h2>
      <!-- blockquotes | make sure to add a "cite" link/' cite="#" ' or it won't work -->
      
      <blockquote cite="#" > this is a blockquote.
      </blockquote>
      <br>
      <blockquote>One day I'm gonna make, The onions cry.
      </blockquote>
      <blockquote>Do not take life too seriously. You will never get out of it alive.
      </blockquote>
      
      <h3 class="left">Heading 3</h3>
      
                  <pre class="prettyprint">
                   // Javascript with syntax highlighting
                   // thelearn-tech@github
                     
                  const files = [ 'foo.txt ', '.bar', '   ', 'baz.foo' ];
                  let filePaths = [];
                  for (let file of files) {
                    const fileName = file.trim();
                    if(fileName) {
                      const filePath = `~/cool_app/${fileName}`;
                      filePaths.push(filePath);
                    }
                  }
      // filePaths = [ '~/cool_app/foo.txt', '~/cool_app/.bar', '~/cool_app/baz.foo']</pre>
      <br>
      
                  <pre class="prettyprint">
                  # Python code with syntax highlighting
                  # thelearn-tech@github
                  from os import path
                  def check_for_file():
                      print("Does file exist:", path.exists("data.csv"))
                  if __name__=="__main__":
                      check_for_file()
      </pre>
      
      <h4 class="left" >Heading 4</h4>
      
      <ul>
         <!-- Unordered list -->
         <li>This is an unordered list, following a heading.</li>
         <li>This is an unordered list, following a heading.</li>
         <li>This is an unordered list, following a heading.</li>
      </ul>
      
      <h5 class="left" >Heading 5</h5>
      
      <ol>
         <!-- Unordered list -->
         <li>This is an ordered list, following a heading.</li>
         <li>This is an ordered list, following a heading.</li>
         <li>This is an ordered list, following a heading.</li>
      </ol>
      
      <h6 class="left">Heading 6</h6>
      
      <table class="left">
         <tr>
            <th>Name</th>
            <th class="left">Age</th>
            <th class="left">Gender</th>
         </tr>
         <tr>
            <td>Josh</td>
            <td class="left">27</td>
            <td class="left">Male</td>
         </tr>
         <tr>
            <td>Tom</td>
            <td class="left">25</td>
            <td class="left">Male</td>
         </tr>
         <tr>
            <td>Olivia</td>
            <td class="left">Never Ask</td>
            <td class="left">Female</td>
         </tr>
         <tr>
            <td>This</td>
            <td class="left">is a</td>
            <td class="left">Table</td>
         </tr>
      </table>
      <h4 class="left">Look there is a horizontal rule below this.
      <!-- horizontal rule -->
      <hr class="hr">
      <br>
      <h5 class="left">Unordered list:</h5>
      <ul>
         <!-- Unordered list -->
         <li>Milk</li>
         <li>Tea</li>
         <li>Coffee</li>
      </ul>
      <br>
      <h5 class="left">Ordered list:</h5>
      <ol>
         <!-- Unordered list -->
         <li class="mediumsize">item I</li>
         <li class="mediumsize">item II</li>
         <li class="mediumsize">item III</li>
      </ol>
      <br>
      <h5 class="left">Nested list:</h5>
      <ul>
         <!-- Unordered list -->
         <li>Category 1</li>
         <ul>
            <li>Level 1</li>
            <li>Level 2</li>
         </ul>
         <li>Category 2</li>
         <ul>
            <li>Level 1</li>
            <li>Level 2</li>
         </ul>
         <li>Category 3</li>
         <ul>
            <li>Level 1</li>
            <li>Level 2</li>
         </ul>
      </ul>
      <br>
      <!-- small images -->
      <h5 class="left">Small image</h5>
      <l class="gray left" >click on image to view source.</l>
      
      <h2></h2>
      <!-- img -->
      <a href="https://github.com/logos"><img src="https://i.ibb.co/DM5nzg9/Octocat.png" alt="github png" class="smallimg"></a>  <a href="https://www.freepnglogos.com/pics/linux"><img src="https://i.ibb.co/JQKxhJw/the-linux-kernel.png" alt="linux compiling kernel png" class="smallimg"> </a>
      <br>
      <h2></h2>
      <!-- large image -->
      <h5 class="left">Large image</h5>
      <h2></h2>
      <img src="https://i.ibb.co/M16Bj41/Friday-info.jpg" alt="friday info" class="largeimg left">
      <h2></h2>
      <!-- img --->
      <h5 class="left">Description list:</h5>
      <h2></h2>
      
      <!-- description list -->
      
      <dl class="left">
         <dt>Creator</dt>
         <dd>thelearn-tech</dd>
         <dt>Hosted on</dt>
         <dd>Github</dd>
         <dt>Language</dt>
         <dd>HTML CSS JS</dd>
      </dl>
      <!-- long commands -->
      <div class="horizontalscroll left">
         <l>For long commands or code scroll should be horizontal rather than vertical. Very longgggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggg text. </l>
      </div>
      <br>
      <div class="horizontalscroll left">
         <l>Enjoy the theme</l>
      </div>
      <br>
      <!-- footer -->
      <footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
         <button onclick="topFunction()" class="w3-button w3-light-grey" title="Go to top"><i class="fa fa-arrow-up w3-margin-right w3-light-grey"></i>To Top</button>
         <div class="w3-xlarge w3-section">
            
            <!-- small logo with redirecting link -->
            <a href="https://twitter.com/thelearn_tech/" <i class="fa fa-twitter w3-hover-opacity"></a>
            <a href="https://instagram.com/thelearn_tech/" <i class="fa fa-instagram w3-hover-opacity"></a>
            <a href="https://github.com/thelearn-tech/" <i class="fa fa-github w3-hover-opacity"></a>
            
         </div>
         <!-- page link -->
         <p>
            <a href="pages/hacker-theme-page2.html" title="" target="_self" class="w3-hover-text-green">Next</a>
            <h> & </h> <a href="pages/hacker-theme-page2.html" title="" target="_self" class="w3-hover-text-green">2</a>
            <h>, </h>
            <a href="pages/hacker-theme-page3.html" title="" target="_self" class="w3-hover-text-green">3</a>
         </p>
         <h class="w3-center"><em>Requested from </em></h>
         <h id="usrip">  </h>
         
      </footer>
      
      <script> // js for scroll to TOP
      function topFunction() {
      
      document.body.scrollTop = 0; // For Safari
      
      document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
      
      }
      
      
      </script>
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"> </script>
      <script src="assets/js/ip.js"> </script>
      
   </div>
</body>
</html>
