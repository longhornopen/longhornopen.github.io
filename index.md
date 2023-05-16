---
layout: default
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w==" crossorigin="anonymous" />

# About Us

Longhorn Open Ed Tech is an open-source consortium based at the University of Texas at Austin.  We build free, open-source apps to help teachers teach, and to help students learn.

Want to help with an existing project, or want more info?  Look at the project's Github page below.

Want to talk to us?  Contact us at:
<div class="contact-links">
  <a class="icon-link" href="mailto:longhorn_open_ed_tech@utlists.utexas.edu">
    <div class="icon"><i class="fas fa-envelope"></i></div>
    <div>longhorn_open_ed_tech@utlists.utexas.edu</div>
  </a>
</div>
<br clear="all">

# Projects

{% capture chatter_desc %}
<p>Chatter is a free discussion-board tool.  Students can talk in free-form threaded discussions, moderated by a teacher or a TA.</p>
<p>Chatter plugs into your Learning Management System as an LTI app.</p>
{% endcapture %}
{% include homepage_product_bar.html
   logo_image='images/chatter-logo.svg'
   repo_name='Chatter'
   repo_url='chatter'
   desc=chatter_desc
%}

{% capture qlti_desc %}
<p>Qualtrics LTI allows you to create a survey or quiz in Qualtrics and offer it to your students as a graded activity. Grades can be either completion grades, or a grade calculated by Qualtrics.  Qualtrics LTI plugs into your Learning Management System as an LTI app.</p>
{% endcapture %}
{% include homepage_product_bar.html
   logo_image='images/qualtrics-lti-logo.png'
   repo_name='Qualtrics LTI'
   repo_url='qualtrics-lti'
   desc=qlti_desc
%}

{% capture peer_desc %}
<p>The Peer Review Tool makes grading a peer review assignment much easier.  After your students have reviewed and graded their peers, use this tool to easily view individual grades and comments, calculate average scores, identify outliers, export grades to Excel and import average scores to the Canvas grade book.</p>
{% endcapture %}
{% include homepage_product_bar.html
   logo_image='images/canvas-peer-grading-logo.png'
   repo_name='Canvas Peer Grading'
   repo_url='canvas-peer-grade-calculator'
   desc=peer_desc
%}

<br clear="all">

# Code Libraries

We also produce a few code libraries, which may help you if you're building an app of your own.

{% capture phpcanvasapi_desc %}
<p>A PHP library allowing applications to easily talk to Canvas via the Canvas API.  This library handles the mechanics of authorization and response pagination.</p>
{% endcapture %}
{% include homepage_product_bar.html
   repo_name='PHP Canvas API'
   repo_url='php-canvas-api'
   desc=phpcanvasapi_desc
%}

{% capture laravellti_desc %}
<p>A PHP library which makes it easy to support LTI in a Laravel app.  Provides several Laravel-friendly wrappers around the <a href="https://github.com/celtic-project/LTI-PHP" target="blank">Celtic LTI</a> library.</p>
{% endcapture %}
{% include homepage_product_bar.html
   repo_name='Laravel LTI'
   repo_url='laravel-celtic-lti'
   status='beta'
   desc=laravellti_desc
%}
