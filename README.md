# easy.js
easy js has many prebuit funtions and elements to making coding with javascript better and faster to write  

<style>
    html{
        scroll-behavior: smooth
    }
    h1{
            text-transform: capitalize;
    }
</style>
<br>
<nav>
    <h1>Documentation Menu</h1>
    <a href="#gettingelements">easy.js selectors</a>
    <br>
    <a href="#random">random numbers</a>
    <br>
    <a href="#platfrom">platfrom</a>
    <br>
    <a href="#model">model</a>
    <br>
    <a href="#ls">localstorage</a>
    <br>
    <a href="#show-hide">show/hide</a>
    <br>
    <a href="#code-tag">&lt;code-tag&gt;</a>
    <br>
    <a href="#comment-tag">&lt;comment-tag&gt;</a>
    <br>
    <a href="#link">link</a>
    <br>
    <a href="#link">notify</a>
    <br>
    found a problem fix on <a href="https://github.com/s0net/easy.js" target="_blank" class="github">github</a>
</nav>
    <main>
    <br>
      <section class="main-section" id="gettingelements">
        <h1>
          getting elements using easy.js
        </h1>
        <p>
          <b class="cooltext">
            using easy.js you can get elements by DOM much easier
            <br>
            easy.js give 12 options alternatives for DOM
          </b>
          <br>
        <h1 class="small">
          grab()
        </h1>
        <p>
          use ele("#id") to get an element by id
          <br>
          example
          <code id="spam">
            ele("#spam")
            <br>
            <span class="code">//try this in console</span>
          </code>
          use ele(".id") to get an elements by id
          <br>
          example
          <code class="spam">
            ele(".spam")
                              <br>
                            <span class="code">//try this in console</span>
                        </code>
        </p>
        <h1 class="small">
          intext()
        </h1>
        <p>
          use intext(".classname"/"#id") to get the inner text of a element with a id/classname
          <br>
          example
          <code>
                        intext("#foo")
                          <br>
                        <span class="code">//try this in console</span>
                    </code>
        </p>
        <h1 class="small testy">
          intext_s()
        </h1>
        <p>
          use intext_s(".classname"/"#id" , "text to replace") to set the inner text of a element with a
          id/classname
          <br>
          example
          <code>
                        intext_s(".testy", "text changed")
                          <br>
                        <span class="code">//try this in console</span>
                    </code>
        </p>
        <h1 class="small">
          inhtml()
        </h1>
        <p>
          use inhtml(".classname"/"#id") to get the inner html of a element with a id/classname
          <br>
          example
          <code>
                        inhtml("#foo")
                          <br>
                        <span class="code">//try this in console</span>
                    </code>
        </p>
        <h1 class="small la">
          inhtml_s()
        </h1>
        <p>
          use inhtml_s(".classname"/"#id", "changed") to change the inner html of a element with a
          id/classname
          <br>
          example
          <code>
            inhtml_s(".la", "cool?")
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
        <h1 class="small">
          src()
        </h1>
        <p>
          use src(".classname"/"#id") to get the src arrtibute of a element with a id/classname
          <br>
          example
          <code>
                      src("#script")
                          <br>
                        <span class="code">//try this in console</span>
                    </code>
        </p>
        <h1 class="small bar">
          src_s()
        </h1>
        <p>
          use src_s(".classname"/"#id") to set the src arrtibute of a element with a id/classname
          <br>
          example
          <code>
                        src_s(".bar", "./easy.js")
                          <br>
                        <span class="code">//try this in console</span>
                    </code>
        </p>
        <h1 class="small">
          val_s()
        </h1>
        <p>
          use val_s(".classname"/"#id") to set the value arrtibute of a element with a id/classname
          <br>
          example
          <code>
            val_s("#noice","the value is nice")
            <br>
            <span class="code">//try this in console</span>
            <input type="submit" id="noice" style="display: none;" value="the value in noice">
          </code>
        </p>
      </section>
      <hr>
      <section class="main-section" id="random">
        <h1>
          random
        </h1>
        <p>
          random(till the number you want)
        </p>
        <p>
          <br>Let us now look a example program : <br>
        </p>
        this is used to get a random number till the number you want
        <code>
        random(100)
        <br>
        <span class="code">//try this in console</span>
        </code>
      </section>
      <hr>
      <section class="main-section" id="random-pic">
        <h1>
          random picture
        </h1>
        <p>
          is used to get a random picture this will retrun a url
        </p>
        <p>
          <br>Let us now look a example program : <br>
        </p>
        <code>
                    random_img()
                      <br>
                    <span class="code">//try this in console</span>
                </code>
      </section>
      <hr>
      <section class="main-section" id="platfrom">
        <h1>
          platfrom
        </h1>
        <p>
          this is a var to get the users platfrom like win32
        </p>
        <p>
          <br>Let us now look a example program : <br>
        </p>
        <code>
                    console.log(platfrom)
                      <br>
                    <span class="code">//try this in console</span>
                </code>
      </section>
      <hr>
      <section class="main-section" id="model">
        <h1>
          model
        </h1>
        <p>
          use this to make a model box in html
        </p>
        <p>
          <br>Let us us see all the options with the help of a code example : <br>
        </p>
        <code>
                    model("title", "text to put inside", "width in css like 100vh", "heigth again in css like 600px", "close button text", "backgound color in css", "text color in css you can use hex rgb or css colors")
                      <br>
                    <span class="code">//try this in console</span>
                </code>
        <h1 class="small">
          title
        </h1>
        <p>
          use this as the title property if there is no title use null
        </p>
        <h1 class="small">
          text
        </h1>
        <p>
          use this for the inside text you can use html in this the overflowing text will not appeare so use a br tag or
          a change the with
        </p>
        <h1 class="small">
          width
        </h1>
        <p>
          in this agrument give a css width like vh,px,pc etc. this will be the width of your model box use null for
          defalt
        </p>
        <h1 class="small">
          heigth
        </h1>
        <p>
          in this agrument give a css heigth like vh,px,pc etc. this will be the heigth of your model box use null for
          defalt
        </p>
        <h1 class="small">
          close button text
        </h1>
        <p>
          in this agrument the give text will be use to close button use null to put i as "x"
        </p>
        <h1 class="small">
          background color
        </h1>
        <p>
          in this agrument the give a css color hex rgb css color to put as background color use null to put i as
          "white"
        </p>
        <h1 class="small">
          text color
        </h1>
        <p>
          in this agrument the give a css color hex rgb css color to put as background color use null to put i as
          "white"
        </p>
      </section>
      <hr>
      <section class="main-section" id="ls">
        <h1>
          localstorage
        </h1>
        <p>
          easy.js give alternative of localstorage comands
        </p>
        <h1 class="small">
          ls()
        </h1>
        <p>
          this will retrun the localstorage ls()
          <code>
            ls()
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
        <h1 class="small">
          ls_s()
        </h1>
        <p>
          this is used to set somthing in localstorage use ls_s(id, value) this will also retrun a item id set
          <code>
            ls_s("cooltext", "hey i set this in localstorage using easy.js")
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
        <h1 class="small">
          ls_g()
        </h1>
        <p>
          this is used to get somthing from localstorage use ls_g(id) this will retrun the item
          <code>
            ls_g("cooltext")
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
        <h1 class="small">
          ls_c()
        </h1>
        <p>
          this is used to clear the localstorage ls_c()
          <code>
            ls_c()
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
        <h1 class="small">
          ls_r()
        </h1>
        <p>
          this is used to remove a item from localstorage with that id
          <code>
            ls_c("cooltext")
            <br>
            <span class="code">//try this in console</span>
          </code>
        </p>
      </section>
      <hr>
      <section class="main-section" id="show-hide">
        <h1>
          show and hide
        </h1>
        <h1 class="small">
          show()
        </h1>
        <p>
          <br>use this to show a element from a display none to disply block<br>
          use show(".classname") to use a class or use show("#id") to use id 
        </p>
        <code id="element">
          show("#cool")
          <span id="cool" style="display:none">seen now</span>
          <br>
          <span class="code">//try this in console</span>
        </code>
        <h1 class="small">
          hide()
        </h1>
        <p>
          <br>use this to hide a element from a display anything to disply none<br>
          use hide(".classname") to use a class (first element with that class name) or use hide("#id") to use id 
        </p>
        <code id="element">
          hide("#elearn")
          <span id="elearn" style="display:none">hide me</span>
          <br>
          <span class="code">//try this in console</span>
        </code>
      </section>
      <hr>
      <section class="main-section" id="code-tag">
        <h1>
          &lt;code-tag&gt;
        </h1>
        <p>
          use this to show a code element in html<br>
          example <code-tag>show()</code-tag>
        </p>
        <code id="element">
          &lt;code-tag&gt;code&lt;/code-tag&gt;
        </code>
      </section>
      <hr>
      <section class="main-section" id="comment-tag">
        <h1>
          &lt;comment-tag&gt;
        </h1>
        <p>
          use this to show a comment element in html<br>
          example <comment-tag>show()</comment-tag>
        </p>
        <code id="element">
          &lt;comment-tag&gt;code&lt;/comment-tag&gt;
        </code>
      </section>
      <hr>
      <section class="main-section" id="time-tag">
        <h1>
          &lt;time-tag&gt;
        </h1>
        <p>
          use this to show the time in format dd/mm/yyyy in html<br>
          example <time-tag></time-tag>
        </p>
        <code id="element">
          &lt;time-tag&gt;&lt;/time-tag&gt;
        </code>
      </section>
      <hr>
      <section class="main-section" id="link">
        <h1>
         link()
        </h1>
        <p>
          use this to open a link in a new tab
        </p>
        <code id="element">
          link("example.com")
          <br>
          <span class="code">//try this in console</span>
        </code>
      </section>
      <hr>
      <section class="main-section" id="link">
        <h1>
          notify()
        </h1>
        <p>
          use this to notify the user using the push notification api
        </p>
        <code id="element" onhover="notify('nice rigth')">
          notify("hi!")
          <!-- <br> -->
          <span class="code">//try this in console</span>
        </code>
      </section>
    </main>

