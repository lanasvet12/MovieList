# MovieList
MovieList on React

 <article class="markdown-body entry-content container-lg" itemprop="text"><h2><a id="user-content-задание-этап-1" class="anchor" aria-hidden="true" href="#задание-этап-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" </path></svg></a>The task. Stage 1</h2>
<ol>
<li>In the main component of the App, create the MovieList component, in which the cards of all films will be displayed, take the movie data from the moviesData.js file and write it to the state of the component and then transfer it to the MovieList</li>
<li>
In the MovieList component, map the resulting movie array and
pass each element to the MovieItem component, in which the movie card will be displayed
(разметка <a href="https://getbootstrap.com/docs/4.1/components/card/#example" rel="nofollow">https://getbootstrap.com/docs/4.1/components/card/#example</a>)</li>
<li>
In the App component in state, write down the list of movies that the user wants to watch (moviesWillWatch: []), create the MovieListWillWatch component, which will display:</li>
</ol>
<ul>
<li>number of films the user wants to watch</li>
<li>
list of movies the user wants to watch
(markup <a href = "https://getbootstrap.com/docs/4.1/components/list-group/" rel="nofollow">https://getbootstrap.com/docs/4.1/components/list-group/</a>)</li>
</ul>
<ol start="4">
<li>
In the MovieItem component, add the Will Watch button, when clicked on, a new movie that the user wants to watch will get into the MovieListWillWatch component.
Accordingly, when pressed again, remove this movie from the WillWatch list
(change the button styles depending on whether or not this movie wants to be watched - for example, its color,
hint: depending on the state of the MovieItem component)</li>
</ol>
<p>he output should be <a href="https://reactwarriors.github.io/reactwarriors-stage-1/" rel="nofollow">https://lanasvet12.github.io/MovieList/</a></p>
<h2> <a id = "user-content-image-path-for-component-movieitem" class = "anchor" aria-hidden = "true" href = "# component-image-path-for-component- movieitem "> <svg class =" octicon octicon-link "viewBox =" 0 0 16 16 "version =" 1.1 "width =" 16 "height =" 16 "aria-hidden =" true "> </a> Path to Images for MovieItem </h2>
<pre> <code> https://image.tmdb.org/t/p/w500${path}
</code></pre>
</article>

