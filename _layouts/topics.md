-- 
layout: wrapper
--

<section id="Life_Transition">
        <header>
                <h1>{{ page.title }}</h1>
                <p>{{ page.text }}</p>
                <img src="{{ page.img }}">
        </header>
        <section id="Firsthand_Stories">
                <ul>
                        {% for i in (1..3) %}
                                <li>
                                       <h3>I've been sober for 9 months and it all began when I shifted my thinking</h3>
                                       <img src="./img/firsthand_stories_avatar.png">
                                </li>
                        {% endfor %}
                </ul>
        </section>
        <section id="Community_Conversations">   
                <h1>Community Conversations</h1>
                <ul>
                        {% for i in (1..7) %}
                                <li>
                                       <h3>I've been stuck in this really negative narrative</h3>
                                       <p>Can you help me repharase this narrative: "I drive people away because my boyfriend is now distancing himself physically and emotionally"?</p>
                                       <div class="post_footer">
                                                <div class="post_author">
                                                        <img src="../img/firsthand_stories_avatar.png">
                                                        <p><small>Abel</small></p>
                                                        <p><small>2 hrs</small></p>
                                                </div>
                                                <div class="post_interactions">
                                                        <p><i class="icon-standard">eye</i>300</p>
                                                        <p><i class="icon-standard">comment</i>200</p>
                                                </div>
                                       </div>
                                </li>
                        {% endfor %}
                </ul>     
        </section>
        <section id="Resources">
                <h1>Helpful Resources</h1>
                <ul>
                        {% for i in (1..4) reversed %}
                                <li>
                                        <img src="./img/resources_placeholder.png">
                                        <h3>Service listing or provider</h3>
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                                        <h5>City, State</h5>
                                </li>
                        {% endfor %}
                </ul>
        </section>
        <section id="Forum">
        </section>
</section>      