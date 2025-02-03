# html-started1
This is my first time learning html.
<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="author" content="Aditya Sarkar">
        <meta name="description" content="This page contains all the things I am learning how to create as I learn html.">
<title>My First Web Page</title>
<link rel="icon" href="hehehe.png" type="image/x-icon">
<link rel="stylesheet" href="main.css" type="text/css">
    </head>
    
    
    <body>

        <header>
        <h1>Jalwa Hai Hamara!</h1>
       
<nav aria-labelledby="primary-navigation">
    <h2 id="primary-navigation">Pointers:</h2>
    <ul>
            <li><a href="#html">Started to learn html.</a></li>
            <li><a href="#Interests">My Interests.</a></li>
            <li><a href="#Cats">Why I like cats.</a></li>
            <li><a href="#Listing">How do I list things in html.</a></li>
            <li><a href="#Marines">What I like about Marine life.</a></li>
            <li><a href="#contact">Contact me.</a></li>

    </ul>
</nav>
        </header>
        
        <hr>

<section id="html">
        <h2>Or Bhai Kya Halchal</h2>
        <p>This is my first web page.</p>

        <h3>Maja toh aarha hai yarr</h3>
        <p>khana khaliya btw.</p>
        
        <p>Bhai 4hr ki tutorial hai yarr!!!
            <br>Ok, let me write how to break a line or i could say giving space:
<br>&nbsp;&nbsp;&nbsp;...ya just like this.
<br>&nbsp;&nbsp;&nbsp;...ya ya great.
<br>&nbsp;&nbsp;&nbsp;...btw i like playing games.
        </p>
</section>

<aside>
    <details>
        <summary>My usual schedule:</summary> <br>
        <table>
            <caption>Daily schedule</caption>
            <thead>
            <tr>
                <th>The Day</th>
                <th id="time" scope="col">Time</th>
                <th scope="col">Activity</th>
            </tr>
        </thead>
    <tr>
        <th id="morning" scope="row">Mid Day</th>
        <td headers="time morning">
            <time datetime="11:00">11:00am</time>-<time datetime="02:00">02:00pm</time>
        </td>
        <td>Eating time in the morning.</td>
    </tr>
    <tbody>
    <tr>
        <th scope="row">Evening TIme</th>
        <td>
            <time datetime="05:00">05:00pm</time>-<time datetime="09:00">09:00pm</time>
        </td>    
            <td>Study time.</td>
    </tr>
    <tr>
        <th scope="row">Mid Night</th>
        <td>
            <time datetime="11:00">11:00pm</time>-<time datetime="02:00">02:00am</time>
        </td>    
            <td>Study time again.</td>
    </tr>
    <tr>
        <th scope="row">Dont Know When</th>
        <td rowspan="2">All Other Time</td>
        <td>Free Time</td>
    </tr>
    <tr>
        <th scope="row">Also Dont Know When</th>
        <td>Sleep Time</td>
    </tr>
</tbody>
<tfoot>
    <tr>
        <td colspan="3">Life sucks man!!!!!</td>
    </tr>
</tfoot>
        </table>
    </details>
</aside>
        <hr>

<main>
<article id="Interests">
        <h2>My Inerests:</h2>
        <p>Here are some of my interests:</p>
</article>


<article id="Cats">
        <h3>I like cats!!!</h3>
    <section>
            <h4>Here are some cute pics</h4>
        <img src="img/catpic.jpg" alt="CatCutePIcture1" title="Cute Cat1" width="350" height="300">
        <img src="img/catpic2.jpg" alt="CatCutePIcture2" title="Cute Cat2" width="350" height="300">
        <figure>
            <figcaption>Cute Little Kitty Cats!</figcaption>
            <p>
                <code>&lt;h1&gt;Kitty Cats&lt;/h1&gt;</code>
            </p>
        </figure>
        <p>Main reason of liking them- <em>they are super cute and adorable grimlins</em>.</p>
    </section>

    <section>
        <h4>Btw I also like <abbr title="tiger, lion, cheetah, leopard etc">big cats</abbr></h4>
        
        <ul>
        <li><p>I hoestly think they are also very adorable <strong>when they want to be</strong>.</p></li>
        </ul>

        <img src="img/tiger.jpg" alt="Tiger1" width="350" height="300">
        <img src="img/tiger2.jpg" alt="Tiger2" width="350" height="300">
        
        <ul>
     <li><p>Big cats like Tigers are usually seen places such as:</p></li>
        </ul>
        <figure>
            <img src="img/sundarbans.jpg" alt="sundarbans1" width="350" height="300">
            <img src="img/sundarbans2.jpg" alt="sundarbans2" width="350" height="300">
            <figcaption>
                The Natual Beauty Of The Sundarbans.
            </figcaption>
        </figure>
        <address>
            &nbsp;&nbsp;&nbsp;Location:
            <a href="https://en.wikipedia.org/wiki/Sundarbans">The Sundarbans</a> in the Ganges-Brahmaputra delta. <br>
            &nbsp;&nbsp;&nbsp;Khulna Division,  Bangladesh. <br>
            &nbsp;&nbsp;&nbsp;Presidency division, West Bengal, India.
        </address>
            <figure>
            <img src="img/sundarbans3.jpg" alt="sundarbans3" width="300" height="300" title="A must visit">
            <figcaption>A Must Visit Place.</figcaption>
            </figure>
            <aside>
                <details>
                    <summary>Cats are precious animals and serve essential role in the </summary>  
                    <p>We must <mark>protect</mark> them at all cost.</p>
                </details>
            </aside>

    </section>

</article>

        <!-- Soeday I will definetly visit The Sunderbans -->
        
        <hr>

    <section id="Listing">
        <h2>OK NOW NEED TO LEARN HOW TO LIST THINGS</h2>
        <p>So the process of listing are given below :</p>
               <ol>
                   <li> For listing lines type "li". </li>
                   <li> For ordered lines type "ol". </li>
</ol>
</section>


<article id="Marines">
    <h3>I also like sharks and whales!!!</h3>
<section>
    <h4>A mysterious shark:</h4>
    <dl>
        <dt>Greenland shark</dt>
        <dd>They live for a <strong>long long time</strong>.</dd>
        <dd>They are probably the most ancient fishes of the arctic oceans.</dd>
        <dd>Researchers think they probably have witnessed the WW2.</dd>
    </dl> 
        <img src="img/greenlandshark.jpg" alt="greenlandshark" width="350" height="300">
        <img src="img/greenlandshark2.jpg" alt="greenlandshark2" width="350" height="300">
</section>
<br><br><br>
    <dl>
        <dt>Whale shark</dt>
        <dd>They are the largest fish on this planet.</dd>
        <dd>Even though they are the largest sharks to roam the oceans, they are filterfiders.</dd>
        <dd>We can see them the aquariums of Okinawa too.</dd>
    </dl>
        <img src="img/whaleshark.jpg" alt="whaleshark1" width="350" height="300">
        <img src="img/whaleshark2.jpg" alt="whaleshark2" width="350" height="300">
<br><br><br>
    <dl>
        <dt>Orcas</dt>
        <dd>They are probably the most dangerous marine mamals and very very scary but they are also very <strong>intellegent</strong>.</dd>
        <dd>These are ther close relatives of the dolphins and intellegence is as par as them too.</dd>
        <dd>Thses are also very great preditor and are in the top of the foodchain.</dd>
    </dl>
        <img src="img/orca.jpg" alt="orca1" width="350" height="300">
        <img src="img/orca2.jpg" alt="orca2" width="350" height="300">
</article>


<hr>


<article id="Contact">
    <h2>Contact Me</h2>
    <p>Share your thoughts.</p>

    <form action="https://httpsbin.org/get" method="get">
        <fieldset>
            <legend>Personal Info</legend>
        <p>
            <label for="firstName">First Name:</label>
            <input type="text" name="firstname" id="firstName" autocomplete="on">
        </p>
        <p>
            <label for="lastName">Last Name:</label>
            <input type="text" name="lastName" id="lastName" autocomplete="on">
        </p>
        <p>
            <label for="password">Password:</label>
            <input type="password" name="password" id="password">
        </p>
        <p>
            <label for="phone">Phone:</label>
            <input type="tel" name="phone" id="phone" pattern="[0-9]{10}">
        </p>
        <p>
            <label for="decade">Favorite Decade:</label>
            <input type="number" name="decade" id="decade" min="1969" max="2069" step="1">
        </p>
        <p>
            <label for="coffee">Favorite Coffee</label>
            <select name="coffee" id="coffee">
                <optgroup label="Coffees">
                <option value="regular coffee">Regular Coeffe</option>
                <option value="iced coffee">Iced Coffee</option>
                <option value="chocolate coffee">Chocolate Coffee</option>
                </optgroup>
                <optgroup label="Special Drinks">
                <option value="latte">Latte</option>
                <option value="black coffee">Black Coffee</option>
                <option value="others">Others</option>
                </optgroup>
            </select>
        </p>
       <!--  <p>
            <label for="coffee">Favorite Coffee:</label>
            <input type="text" name="coffee" id="coffee" list="coffee-list">
                <datalist id="coffee-list">
                <option value="Regular coffee">
                <option value="Iced coffee">
                <option value="Chocolate coffee">
                <option value="Latte">
                <option value="Black coffee">
                <option value="Others">
                </datalist>
        </p> -->
        </fieldset>
        <br>
        <fieldset>
            <legend>Your Favorite Food</legend>
            <p>
                <input type="radio" name="food" id="biryani" value="biryani">
                <label for="biryani">Biryani</label>
            </p>
            <p>
                <input type="radio" name="food" id="friedrice" value="friedrice">
                <label for="friedrice">Friedrice</label>
            </p>
            <p>
                <input type="radio" name="food" id="polao" value="polao">
                <label for="polao">Polao</label>
            </p>
        </fieldset>
        <br>
        <fieldset>
            <legend>Your Favorite Pet</legend>
            <p>
                <input type="checkbox" name="pet" id="cat" value="cat">
                <label for="cat">Cat</label>
            </p>
            <p>
                <input type="checkbox" name="pet" id="dog" value="dog">
                <label for="dog">Dog</label>
            </p>
            <p>
                <input type="checkbox" name="pet" id="fox" value="fox">
                <label for="fox">Fox</label>
            </p>
            <p>
                <input type="checkbox" name="pet" id="otherpet" value="pet">
                <label for="otherpet">Other</label>
            </p>
        </fieldset>
        <fieldset>
            <legend>Your Note</legend>
            <p>
                <label for="message">Your Message</label>
                <br>
                <textarea name="message" id="message" cols="30" rows="10" placeholder="Type your message here."></textarea>
            </p>
        </fieldset>
        <br>
        <button type="submit">Submit</button>
        <button type="submit" formaction="https://httpspin/org/post" formmethod="post">Post</button>
        <button type="reset">Reset</button>
    </form>
    
</article>


</main>

<hr>

<footer>
<p>
    <a href="/">Back to Home</a>
</p>
<p>
    <a href="#">Back to Top</a>
</p>
<p>
    &lt;&lt;&lt; &copy;<a href="about.html">Aditya Sarkar</a> &gt;&gt;&gt;
</p>
</footer>

    </body>

</html>
