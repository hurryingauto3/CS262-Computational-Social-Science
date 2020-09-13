# CS262 Computational Social Science Project
## Contributers
- [Bahzad Badvi] (https://github.com/Bahzad-Ahmed)
- [Muhammad Usaid] (https://github.com/m-usaid) 
<h2 id="abstract">Abstract</h2>
<p>Anthropocentrism and the capitalistic commodification of resources has led humans down a spiral of self-destruction, and equally increased a general disregard for nature. For most nature is an external entity, unbeknown to them that humanity is not exclusive from it. Following from this stems the negligence of intelligence shown in nature however, as we shall be exploring in our project, signs of intelligence can be found everywhere in nature. Our project deals with modelling the semi-intelligent behavior shown by an acellular organism known as Physarum Polycephalum or more commonly as Yellow slime mold. This organism has baffled biologist and researcher over its exhibition of intelligence besides the fact that it does not have a central nervous system. Surely without a central processing unit how can an organism function let alone solve difficult problems? Intriguingly enough P.Polycephalum cannot only perform basic life function but is able to solve many complex problems such as path optimization (Nakagaki et al., 2000). Research suggest that a pulsating flow of biochemicals within its tube-like structure handles P.Polycephalum’s intricate mobility and that the control of this fluid is the cause of its coordinated growth (Alim et al., 2013). Another research suggests that P.Polycephalum makes use of an external ‘spatial’ memory by using pheromones to mark visited regions (Reid et al., 2012).</p>
<h2 id="agents">Agents</h2>
<p>The agents represented in our model would be an abstract of P.Polycephalum’s nuclei and others will represent oats (food for P.Polycephalum).</p>
<h4 id="section"></h4>
<p>The agents in our model would be homogenous since our model isn’t dealing with diversity within P.polycephalum.</p>
<h2 id="environment">Environment</h2>
<p>We have narrowed down to two choices one of which would be a network-based modelling environment since our simulation would be networking intensively another choice for our model could be a geo-spacial environment where we can setup mazes/walls to show how P.Polycephalum is able to overcome such scenarios.</p>
<h2 id="interactions">Interactions</h2>
<p>There exists a collective interaction between the agents as they can identify the places the organism as a whole has visited before and hence there’s no need to visit again. The agents will also communicate the location of where the food is found so that they may concentrate themselves there. The environment does affect how they interact for example in a maze in an ideal simulation the agents would fill the maze up first and then concentrate themselves on the single most optimum path connecting the ‘food’ nodes.</p>
<h2 id="bounded-rationality">Bounded Rationality</h2>
<p>The agents themselves have only one goal that is to divide into more nuclei, find food, to metabolize and survive. This eventually leads them to work together and optimize their network based on the environment they are introduced to. Therefore, yes there is a collective rationality whilst taking decisions.</p>
<h2 id="learning">Learning</h2>
<p>Yes, the agents will learn more about their environment as mentioned earlier P.Polycephlum uses an external ‘spatial’ memory by secreting a certain chemical to mark where it has been so there’s no need to visit the same place again. Moreover, the organism moves using fluid propagation inside its tubular structure. The control of this fluid is the main decision-making mechanism which learns from feedback obtained from earlier actions.</p>
<h2 id="actions">Actions</h2>
<ul>
<li><p>Production of more agents to abstract the process of nuclear division within P.Polycephalum.</p></li>
<li><p>A random outwards motion from the starting ‘food’ node.</p></li>
<li><p>Marking of visited territories.</p></li>
<li><p>Flocking behavior exhibited when food is discovered.</p></li>
<li><p>Optimization of path connecting ‘food’ nodes through feedback and control.</p></li>
</ul>
<h2 id="time">Time</h2>
<p>In reality Slime mold grows at about a centimeter an hour so it’s ideal to have the time scale of one tick being equal to an hour. Anything less would be redundant</p>
<h2 id="output">Output</h2>
<p>We haven’t yet identified a need for an output yet other than the visual simulation itself.</p>
<h2 id="bibliography">Bibliography</h2>
<ol>
<li><p>Alim, K., Amselem, G., Peaudecerf, F., Brenner, M., &amp; Pringle, A. (2013). Random network peristalsis in Physarum polycephalum organizes fluid flows across an individual. Proceedings of the National Academy of Sciences of the United States of America, 110(33), 13306-13311. Retrieved September 12, 2020, from<br />
<a href="http://www.jstor.org/stable/42712903">http://www.jstor.org/stable/42712903</a></p></li>
<li><p>Alim, K., Andrew, N., Pringle, A., Brenner, M. (2017). Mechanism of signal propagation in Physarum polycephalum. Proceedings of the National Academy of Sciences. Retrieved September 12, 2020, from<br />
<a href="https://www.pnas.org/content/114/20/5136.short.">https://www.pnas.org/content/114/20/5136.short.</a></p></li>
<li><p>Nakagaki, T., Yamada, H. &amp; Tóth, Á. Maze-solving by an amoeboid organism. Nature 407, 470 (2000). <a href="https://doi.org/10.1038/35035159">https://doi.org/10.1038/35035159</a></p></li>
<li><p>Reid, C., Latty, T., Dussutour, A., &amp; Beekman, M. (2012). Slime mold uses an externalized spatial "memory" to navigate in complex environments. Proceedings of the National Academy of Sciences of the United States of America, 109(43), 17490-17494. Retrieved September 12, 2020, from <a href="http://www.jstor.org/stable/41829697">http://www.jstor.org/stable/41829697</a></p></li>
<li><p>Tero, A., Takagi, S., Saigusa, T., Ito, K., Bebber, D., Flicker, M., . . . Nakagaki, T. (2010). Rules for Biologically Inspired Adaptive Network Design. Science, 327(5964), new series, 439-442. Retrieved September 13, 2020, from <a href="http://www.jstor.org/stable/40508592">http://www.jstor.org/stable/40508592</a></p></li>
</ol>
