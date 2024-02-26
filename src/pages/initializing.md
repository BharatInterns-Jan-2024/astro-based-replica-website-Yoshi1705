<p>Here is a basic installation how-to.</p>
<div style="border-left: 1px solid white; padding-left: 10px;">
    <i>NOTE: I’ll have a better approach in the next unit, where we’ll install GitHub Desktop after creating a GitHub account, figuring out the credentials for you, I think it’s easier. But it’s worth mentioning how to install Git separately, too.</i>
</div>

<h3 style = "margin-bottom : 8px ">OSX</h3>
<div style = "background-color : yellow; width : 30px; height : 6px; margin-bottom: 10px;"></div>

<p>Using <a href="https://flaviocopes.com/homebrew/"style = "color :  #257cde">Homebrew</a>, you can run:</p>

<pre><code class="code-highlight"><span class="code-line">brew <span class="token function">install</span> <span class="token function">git</span>
</span></code></pre>

<h3 style = "margin-bottom : 8px ">Windows</h3>
<div style = "background-color : yellow; width : 30px; height : 6px;"></div>

<p>Download and install <a href="https://flaviocopes.com/homebrew/"style = "color :  #257cde">Git for Windows</a></p>

<h3 style = "margin-bottom : 8px ">Linux</h3>
<div style = "background-color : yellow; width : 30px; height : 6px;"></div>

<p>Use the package manager of your distribution to install Git.</p>

<p>For example this on Ubuntu:</p>


<pre><code class="code-highlight"><span class="code-line">sudo apt update

sudo apt install git</code></pre>

<p>Using this method you have to set your name and email in the terminal using these 2 commands:</p>

<pre><code class="code-highlight"><span class="code-line"><span class = "token function">git</span> config <span class = "token function">--global</span> user.name <span style = "color : green">"your name"</span>
<span class = "token function">git</span> config <span class = "token function">--global</span> user.email <span style = "color : green">"your@email.com"</span>
</code></pre>

<div style="border-left: 1px solid white; padding-left: 15px; margin-top : 10px; margin-bottom : 20px">
    <i>Make sure you enter your name and email, not those fake ones!</i>
</div>

<style>
 pre {
    margin-top: 10px;
    margin-bottom: 20px;
    line-height: 2rem;
    
}
.code-highlight {
    background-color: #1b1b1b;
}
pre>code {
    display: grid;
    padding: 15px 0;
}
.code-line {
    display: block;
    padding-left: 16px;
    padding-right: 16px;
    border-left: 4px solid rgba(0, 0, 0, 0);
}
.token.function {
    color: #61afef;
}
</style>