<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="/assets/css/style.css?v=7de3ae5b9daa8eb5960c76f230328f75915c71e2">
<!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

  <!-- Setup Google Analytics -->
  
  <!-- You can set your favicon here -->
  
  <!-- link rel="shortcut icon" type="image/x-icon" href="/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      <meta name="viewport" content="width=device-width">
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">WordPress › ReadMe
      <link rel="stylesheet" href="wp-admin/css/install.css?ver=20100228" type="text/css">
      <div style="display: flex; align-items: center;">
        <h1 id="logo">
          <a href="https://wordpress.org/">
            <svg xmlns:svg="" xmlns="http://www.w3.org/2000/svg" version="1.0" width="540" height="180" id="svg2" xml:space="preserve"></svg>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/WordPress_logo.svg/960px-WordPress_logo.svg.png" style="display:flex background-color:000" alt="Wordpress" title="Wordpress " width="414" height="74">
			</a>
		</h1>
	</div>

<p style="text-align: center">Semantic Personal Publishing Platform</p>
<h2 id="installation-famous-5-minute-install">Installation: Famous 5-minute install<a class="anchorjs-link " href="#installation-famous-5-minute-install" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<ol>
	<li>Unzip the package in an empty directory and upload everything.</li>
	<li>Open
		<span class="file">
			<a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser. It will take you through the process to set up a <code>wp-config.php</code> file with your database connection details.
	</li>
		<ol>
			<li>If for some reason this doesn’t work, don’t worry. It doesn’t work on all web hosts. Open up <code>wp-config-sample.php</code> with a text editor like WordPad or similar and fill in your database connection details.</li>
			<li>Save the file as <code>wp-config.php</code> and upload it.</li>
			<li>Open <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> in your browser.</li>
		</ol>
	&lt;/li&gt;
	<li>Once the configuration file is set up, the installer will set up the tables needed for your blog. If there is an error, double check your <code>wp-config.php</code> file, and try again. If it fails again, please go to the <a href="https://wordpress.org/support/" title="WordPress support">support forums</a> with as much data as you can gather.</li>
	<li><strong>If you did not enter a password, note the password given to you.</strong> If you did not provide a username, it will be <code>admin</code>.</li>
	<li>The installer should then send you to the <a href="wp-login.php">login page</a>. Sign in with the username and password you chose during the installation. If a password was generated for you, you can then click on “Profile” to change the password.</li>
</ol>

<h2 id="updating">Updating<a class="anchorjs-link " href="#updating" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<h3 id="using-the-automatic-updater">Using the Automatic Updater<a class="anchorjs-link " href="#using-the-automatic-updater" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
<p>If you are updating from version 2.7 or higher, you can use the automatic updater:</p>
<ol>
	<li>Open <span class="file"><a href="wp-admin/update-core.php">wp-admin/update-core.php</a></span> in your browser and follow the instructions.</li>
	<li>You wanted more, perhaps? That’s it!</li>
</ol>

<h3 id="updating-manually">Updating Manually<a class="anchorjs-link " href="#updating-manually" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
<ol>
	<li>Before you update anything, make sure you have backup copies of any files you may have modified such as <code>index.php</code>.</li>
	<li>Delete your old WordPress files, saving ones you’ve modified.</li>
	<li>Upload the new files.</li>
	<li>Point your browser to <span class="file"><a href="wp-admin/upgrade.php">/wp-admin/upgrade.php</a>.</span></li>
</ol>

<h2 id="migrating-from-other-systems">Migrating from other systems<a class="anchorjs-link " href="#migrating-from-other-systems" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<p>WordPress can <a href="https://codex.wordpress.org/Importing_Content">import from a number of systems</a>. First you need to get WordPress installed and working as described above, before using <a href="wp-admin/import.php" title="Import to WordPress">our import tools</a>.</p>

<h2 id="system-requirements">System Requirements<a class="anchorjs-link " href="#system-requirements" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<ul>
	<li><a href="https://secure.php.net/">PHP</a> version <strong>5.2.4</strong> or higher.</li>
	<li><a href="https://www.mysql.com/">MySQL</a> version <strong>5.0</strong> or higher.</li>
</ul>

<h3 id="recommendations">Recommendations<a class="anchorjs-link " href="#recommendations" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
<ul>
	<li><a href="https://secure.php.net/">PHP</a> version <strong>7</strong> or higher.</li>
	<li><a href="https://www.mysql.com/">MySQL</a> version <strong>5.6</strong> or higher.</li>
	<li>The <a href="https://httpd.apache.org/docs/2.2/mod/mod_rewrite.html">mod_rewrite</a> Apache module.</li>
	<li><a href="https://wordpress.org/news/2016/12/moving-toward-ssl/">HTTPS</a> support.</li>
	<li>A link to <a href="https://wordpress.org/">wordpress.org</a> on your site.</li>
</ul>

<h2 id="online-resources">Online Resources<a class="anchorjs-link " href="#online-resources" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<p>If you have any questions that aren’t addressed in this document, please take advantage of WordPress’ numerous online resources:</p>
<dl>
	<dt><a href="https://codex.wordpress.org/">The WordPress Codex</a></dt>
		<dd>The Codex is the encyclopedia of all things WordPress. It is the most comprehensive source of information for WordPress available.</dd>
	<dt><a href="https://wordpress.org/news/">The WordPress Blog</a></dt>
		<dd>This is where you’ll find the latest updates and news related to WordPress. Recent WordPress news appears in your administrative dashboard by default.</dd>
	<dt><a href="https://planet.wordpress.org/">WordPress Planet</a></dt>
		<dd>The WordPress Planet is a news aggregator that brings together posts from WordPress blogs around the web.</dd>
	<dt><a href="https://wordpress.org/support/">WordPress Support Forums</a></dt>
		<dd>If you’ve looked everywhere and still can’t find an answer, the support forums are very active and have a large community ready to help. To help them help you be sure to use a descriptive thread title and describe your question in as much detail as possible.</dd>
	<dt><a href="https://codex.wordpress.org/IRC">WordPress <abbr title="Internet Relay Chat">IRC</abbr> Channel</a></dt>
		<dd>There is an online chat channel that is used for discussion among people who use WordPress and occasionally support topics. The above wiki page should point you in the right direction. (<a href="irc://irc.freenode.net/wordpress">irc.freenode.net #wordpress</a>)</dd>
</dl>

<h2 id="final-notes">Final Notes<a class="anchorjs-link " href="#final-notes" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<ul>
	<li>If you have any suggestions, ideas, or comments, or if you (gasp!) found a bug, join us in the <a href="https://wordpress.org/support/">Support Forums</a>.</li>
	<li>WordPress has a robust plugin <abbr title="application programming interface">API</abbr> that makes extending the code easy. If you are a developer interested in utilizing this, see the <a href="https://developer.wordpress.org/plugins/">Plugin Developer Handbook</a>. You shouldn’t modify any of the core code.</li>
</ul>

<h2 id="license">License<a class="anchorjs-link " href="#license" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
<p>WordPress is free software, and is released under the terms of the <abbr title="GNU General Public License">GPL</abbr> version 2 or (at your option) any later version. See <a href="license.txt">license.txt</a>.</p>





      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  

</body></html>
