---
# The Hugo Grayscale theme is a one page theme designed to be the front page to your site.  Its content is populated via the front-matter in content/_index.md.  The page consists of, in order:
# * a navbar at top linking to the other sections, and other arbitrary links
# * an intro section presenting a header title and into text with background image
# * an about section presenting a header and text with black background
# * a download section presenting header and text with background image
# * a contact section presenting header and text with black background
# 
# The section names show up as the links in the navbar, so you may wish to rename them if, for example, you're not using it for the purpose suggested by the default section name.
# 
# The background images are selected by filename - the intro section image must be named "intro-bg.jpg" and placed in the "static/img/" directory for your site.  Similarly, the downloads section image must be named "downloads-bg.jpg" and placed in the "static/img/" directory for your site.  See the default images in the theme's static directory for file size reference.

title: "ATF"
date: 2018-09-09T00:00:00-00:00
copyright: "Jace Benson"
#mapsapikey: xxx

socialhandles:
    twitter: "jacebenson"
    github: "jacebenson/atf"
    discord: "https://discordapp.com/invite/QaMwnGd"

#menu:
#    -
#        url: "https://discord.gg/QaMwnGd"
#        name: "Discord"

intro:
    header: "OOB Automated Testing"
    text: "Automated Testing Framework tests that SHOULD have been"

about:
    header: "About Scoped ATF"
    text: '<p>OOB Automated Testing is a scoped app to capture tests for all the Out of Box servicenow applications. With this you have a place to start your own tests instead of starting from scratch. Once installed you’ll be able to run a batch of tests against the instance. One key detail about all of these tests, they are all self-contained. Meaning, you don’t need to load up any demo users, companies or groups to try these tests. They are all included in this scoped application.</p>'

download:
    rename: "Install"
    header: "Install Scoped \"ATF\""
    text: '<p>You can install it using this url: <a href="https://github.com/jacebenson/atf.git">https://github.com/jacebenson/atf.git</a>
    <div style="text-align:left;padding: 15px">
      <p>For simplicity of creating users, groups, and roles for testing, I created a custom step, "Create user with rights".  This step however requires a change in the <b>global</b> scope.  The reason for this is scoped applications cannot create, update, or delete groups out of the box.  Below is how to allow that to work.</p>
      <p>To allow this custom step to work do this;</p>
      <p>
      On <code>/sys_db_object.do?sysparm_query=name=sys_user_group</code>
      under "Application Access", check "Can create", "Can update", "Can delete", 
      and save.
      </p>
    </div>
    </p>'

contact:
    header: "Contact Us"
    text: '<p>Feel free to leave us a comment (via issues) on <a href="https://github.com/jacebenson/atf/issues/new">github</a> to give some feedback about this theme!</p>'
---
