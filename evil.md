

  
<p><walkthrough-metadata>
  <meta name="title" content="Quickstart: Introduction to using the gcloud CLI in Cloud Shell." />
  <meta name="description" content="Run a few core commands in Cloud Shell to get started with using gcloud CLI." />
  <meta name="keywords" content="gcloud, CLI, Cloud Shell, Google Cloud CLI"/>
  <meta name="component_id" content="163415" />
</walkthrough-metadata></p>

<html devsite>
  <head>
    

    

    
    
    
    

    
    
  
  












  
  
  

    <title>
  Get started with using Google Cloud CLI in Cloud Shell.
</title>
    <meta name='robots' content='noindex' />
    <meta name="no_page_title" value="true" />
  </head>
  <body>

  

   <h1 id="get-started-with-using-google-cloud-cli-in-cloud-shell." data-text="   Get started with using Google Cloud CLI in Cloud Shell. ">
  Get started with using Google Cloud CLI in Cloud Shell.
</h1>

    <section>
      <h2 id="heading" data-text=" "> </h2>
      <img src="https://cloud-dot-devsite-v2-prod.appspot.com/walkthroughs/images/intro-page.png" alt>
    </section>

    <section class="intro">
      

<p>Learn how to:</p>

<ol>
<li><p>Enable billing in a Google Cloud project.</p></li>
<li><p>Set some Google Cloud CLI default properties in Cloud Shell.</p></li>
<li><p>Run gcloud CLI core commands in Cloud Shell.</p></li>
<li><p>View information about gcloud CLI concepts.</p></li>
<li><p>Do more with gcloud CLI.</p></li>
</ol>

<p>Estimated time to complete:
<walkthrough-tutorial-duration duration="5"></walkthrough-tutorial-duration></p>

<p>To begin, click <strong>Start</strong>.</p>


    </section>

    <section class="prereqs">
      
      
    </section>

    <section class="steps">
      

<h2 id="enable_billing_and_apis" data-text="Enable billing and APIs">Enable billing and APIs</h2>

<ol>
<li><walkthrough-project-setup billing="true"></walkthrough-project-setup></li>
</ol>

<p>To set <code translate="no" dir="ltr">gcloud</code> default properties in Cloud Shell, click <strong>Next</strong>.</p>

<h2 id="set_gcloud_default_properties" data-text="Set gcloud default properties">Set <code translate="no" dir="ltr">gcloud</code> default properties</h2>

<ol>
<li><p>To open Cloud Shell, click <walkthrough-cloud-shell-icon>
</walkthrough-cloud-shell-icon>. <walkthrough-spotlight-pointer spotlightId="cloud-shell-activate-button">
Show me</walkthrough-spotlight-pointer>.</p>

<p>This operation might take some time to complete.</p></li>
<li><p>Disable color in the messages printed to the terminal:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud config set disable_color true
</code></pre></li>
<li><p>Unset this property:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud config unset disable_color
</code></pre></li>
<li><p>Read about <code translate="no" dir="ltr">gcloud</code> configurations:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud topic configurations
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
</ol>

<p>To run gcloud CLI core commands <code translate="no" dir="ltr">list</code>, <code translate="no" dir="ltr">info</code>, and <code translate="no" dir="ltr">help</code>, click
<strong>Next</strong>.</p>

<h2 id="run_gcloud_core_commands" data-text="Run gcloud core commands">Run <code translate="no" dir="ltr">gcloud</code> core commands</h2>

<ol>
<li><p>List the accounts that have credentials stored on the local system:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud auth list
</code></pre>
<p>If the <strong>Authorize Cloud Shell</strong> dialog appears and you agree to the terms,
click <strong>Authorize</strong>.</p>

<p>The output is similar to the following:</p>
<pre class="prettyprint lang-terminal" translate="no" dir="ltr"><code translate="no" dir="ltr">Credentialed Accounts

ACTIVE: *
ACCOUNT: izumi@example.com
</code></pre></li>
<li><p>List the properties in your active gcloud CLI configuration:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud config list
</code></pre></li>
<li><p>View information about your gcloud CLI installation and the
active configuration:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud info
</code></pre></li>
<li><p>View information about gcloud CLI:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud help
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
<li><p>View the help documentation for <code translate="no" dir="ltr">gcloud compute instances create</code>:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud help compute instances create
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
</ol>

<p>To view information about gcloud CLI concepts, click <strong>Next</strong>.</p>

<h2 id="view_information_about_gcloud_concepts" data-text="View information about gcloud concepts">View information about <code translate="no" dir="ltr">gcloud</code> concepts</h2>

<ol>
<li><p>See all available commands under <code translate="no" dir="ltr">gcloud topic</code>:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud help topic
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
<li><p>See information on filtering:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud topic filters
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
<li><p>Learn more about <code translate="no" dir="ltr">gcloud</code> command structure:</p>
<pre class="prettyprint lang-sh" translate="no" dir="ltr"><code translate="no" dir="ltr">gcloud topic command-conventions
</code></pre>
<p>To exit, enter <code translate="no" dir="ltr">q</code>.</p></li>
</ol>

<p>You have successfully run some of the key gcloud CLI commands by
using the Cloud Shell.</p>

<p>To learn about the next steps, click <strong>Next</strong>.</p>


    </section>

    <h2 id="next-steps" data-text="Next steps">Next steps</h2>

    
    <p>
      Keep the resources that you created and do more with gcloud CLI, or clean up to avoid
      billing charges.
    </p>
    

    <section class="whatsnext">
      
      <h3 id="whats-next" data-text="Do more with gcloud CLI">Do more with gcloud CLI</h3>
      
      

<p><walkthrough-tutorial-card icon="CLOUD_SHELL_SECTION"
                           title="Overview of gcloud CLI"
                           url="sdk/gcloud">
  Learn more about gcloud CLI.
</walkthrough-tutorial-card></p>

<p><walkthrough-tutorial-card icon="CLOUD_SHELL_SECTION"
                           title="gcloud CLI common commands"
                           url="sdk/docs/cheatsheet">
  Refer to the gcloud CLI cheat sheet for a list of commonly used
  commands.
</walkthrough-tutorial-card></p>

<p><walkthrough-tutorial-card icon="CLOUD_SHELL_SECTION"
                           title="Install the gcloud CLI locally"
                           url="sdk/docs/install">
  Install the gcloud CLI on your local machine.
</walkthrough-tutorial-card></p>

<p><walkthrough-tutorial-card icon="CLOUD_SHELL_SECTION"
                           title="Install additional components"
                           url="sdk/docs/components">
  Install additional components such as <code translate="no" dir="ltr">kubectl</code> using the
  gcloud CLI component manager.
</walkthrough-tutorial-card></p>


    </section>

    

<walkthrough-inline-feedback></walkthrough-inline-feedback>



  
