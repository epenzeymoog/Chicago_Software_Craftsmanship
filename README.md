<h1>Chicago Software Craftsmanship</h1>

<h2>The Purpose of This Website:</h2>
<p>Chicago Software Craftsmanship is a group that hosts meetings with the goal of spreading the knowledge of high 
quality software through thought-provoking topics. This website communicate the group's mission, information on 
upcoming events, as well as a list of high-quality, curated resources for developers.</p>

<h2>Check me out by:</h2>
<p>Clone the repo.</p>
<p>This project has SASS styling. You can quickly install Sass by completing the following directions 
or using <a href="http://sass-lang.com/documentation/file.SASS_REFERENCE.html#using_sass">their documentation.</a></p>
<p>Sass requires ruby, which comes pre-installed on Macs. If you're using a Windows computer, you will have to 
<a href="http://rubyinstaller.org/">install ruby</a> before you can install sass.</p>
<p>In the command line, run:</p>
<code>gem install sass</code>
<p>Sass compiles the contents of your main Sass file to your main CSS file. In order to tell Sass to do this, you can do two things:</p>
<p>Option 1: Tell Sass to find changes after you make them (this is the slower and more tedious method but better
to use until you understand how Sass works). To do this, go to your teminal and <code>cd</code> into your stylesheets folder where your CSS and Sass files are kept. The run the command:
<code>sass input.scss output.css</code> (and replace "input" and "output" with the names of your stylesheets).
<p>This will tell Sass to go through your Sass files and compile them into your CSS file.</p>
<p>Option 2: Tell Sass to run a watch so that it will constantly be looking for changes to your Sass files and compiling them into your CSS file. This is quicker and simpler. My  To do this, open a new tab in your teminal and run:</p>
<code>sass --watch style.scss:style.css</code>
<p>If you get an error when running this command, first try deleting the directory in the project called .sass-cache (don't worry, it'll all come back next time Sass compiles) and re-running the command. If you have errors in your files, they will be pointed out in the terminal and you'll have to fix them before Sass can start watching for chagnes.</p>

<p>In order to view the website locally, run
<code>open index.html</code> in your terminal or right click in the <code>index.html</code> file and select "Open in Browser."</p>