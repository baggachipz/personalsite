<template>
  <q-page class="q-pa-md">
    <h2 class="text-primary">Oh, hey there.</h2>
    <p class="text-body1">My name is <strong>Matt Curtis</strong>, and by day I am a mild-mannered web developer and team leader.</p>
    <p class="text-body1">
        I've been developing for the web since it became a thing, working on projects small and large. This
        includes experiences tailored to a small group of users, or a commerce site with millions of monthly
        visitors.
    </p>
    <p class="text-positive text-body1">
        If you're reading this, you may be considering hiring me.
        Please peruse this page to learn why that would be a fantastic idea.
    </p>

    <q-card class="q-mt-xl bg bg-skills">
      <q-card-section>
        <h3 class="text-primary text-left q-mb-none" title="wow. such letters. much skill.">Skills</h3>
        <div class="row wrap justify-evenly items-start content-start">
          <div class="col-md-3 self-center">
            <h5>Expertise in:</h5>
            <ul>
              <li>HTML5</li>
              <li>CSS3</li>
              <li>Javascript/ECMAScript6+</li>
              <li>Node.js</li>
              <li>Relational Databases</li>
              <li>RESTful APIs</li>
            </ul>
          </div>
          <div class="col-md-3 self-center">
            <h5>Frameworks</h5>
            <ul>
              <li>Express.js</li>
              <li>Vue.js</li>
              <li>Quasar</li>
              <li>Backbone.js &amp; Underscorejs</li>
              <li>Symfony/Silex</li>
              <li>Ionic/Cordova</li>
            </ul>
          </div>
          <div class="col-md-3 self-center">
            <h5>I also know:</h5>
            <ul>
              <li>MongoDB</li>
              <li>Redis</li>
              <li>Elastic Search</li>
              <li>iOS/Android Development</li>
              <li>PHP</li>
              <li>C#/VB.NET</li>
            </ul>
          </div>
        </div>
      </q-card-section>
    </q-card>

    <q-card class="q-mt-xl bg bg-experience" id="experience">
      <q-card-section>
        <h3 class="text-primary text-left">Experience</h3>
        <q-banner rounded class="bg-secondary text-white">
          <span class="text-subtitle1">Wow, that's a lot of alphabet soup up there. How about I describe some of the recent things I've worked on?</span>
        </q-banner>
      </q-card-section>
      <q-card-section>
        <q-list>
          <q-item>
            <div class="row">
              <div class="col-md-3 q-pb-md">
                <q-item-section top avatar>
                  <img src="~assets/logo-ox.png" alt="Open-Xchange">
                </q-item-section>
              </div>
              <div class="col-md-9">
                <q-item-section>
                  <q-item-label class="text-h6">Open-Xchange</q-item-label>
                  <p>
                      With millions of users every day and many large global customers, <a href="https://www.open-xchange.com/portfolio/ox-app-suite-users/" target="_blank">OX App Suite</a>
                      is the leading white-labeled email and productivity platform used by telecommunications and web hosting companies worldwide. Customizing OX App Suite for customers
                      involves several technologies working together to produce a scalable and accessible user experience. Frontend: HTML5, Backbone.js, jQuery, LESS, CSS3.
                  </p>
                </q-item-section>
              </div>
            </div>
          </q-item>
          <q-item>
            <div class="row">
              <div class="col-md-3 q-pb-md">
                <q-item-section top avatar>
                  <img src="~assets/logo-brainrush.png" alt="Brainrush">
                </q-item-section>
              </div>
              <div class="col-md-9">
                <q-item-section>
                  <q-item-label class="text-h6">BrainRush</q-item-label>
                  <p>
                        A project of <a href="http://en.wikipedia.org/wiki/Nolan_Bushnell" target="_blank">Nolan Bushnell</a>,
                        <a href="https://www.crunchbase.com/organization/brainrush" target="_blank">BrainRush</a>
                        was a platform for creating and playing educational games that utilize fast-paced learning techniques.
                        I was hired on from the beginning to build out the product and HTML5 games. Backend: Symfony2, Apache,
                        MySQL, MongoDB. Frontend: Backbone.js, Underscore.js, jQuery, LESS.
                    </p>
                </q-item-section>
              </div>
            </div>
          </q-item>
          <q-item>
            <div class="row">
              <div class="col-md-3 q-pb-md">
                <q-item-section top avatar>
                  <img src="~assets/logo-dell.png" class="img-outline" alt="Dell Kace">
                </q-item-section>
              </div>
              <div class="col-md-9">
                <q-item-section>
                  <q-item-label class="text-h6">ITNinja</q-item-label>
                  <p>
                      <a href="http://www.itninja.com" target="_blank">ITNinja</a> is a project conceived by the staff at
                      <a href="http://www.kace.com" target="_blank">Kace</a>, now a division of <a href="http://software.dell.com/" target="_blank">Dell Software</a>.
                      ITNinja is a community for IT administrators to trade information, links, and software. I was the second
                      developer hired on to the team, to create the product from scratch. Backend: Symfony2, Apache, MySQL, Redis, Node.js.
                      Frontend: jQuery, HTML5.
                  </p>
                </q-item-section>
              </div>
            </div>
          </q-item>
          <q-item>
            <div class="row">
              <div class="col-md-3 q-pb-md">
                <q-item-section top avatar>
                  <img src="~assets/logo-si.png" alt="Smithsonian Institution">
                </q-item-section>
              </div>
              <div class="col-md-9 q-pb-md">
                <q-item-section>
                  <q-item-label class="text-h6">si.edu</q-item-label>
                  <p>
                      As a part of my independent consulting stint, I was hired to implement the redesign of the
                      <a href="http://www.si.edu" target="_blank">Smithsonian Institution</a> site. This included the homepage,
                      exhibitions database, collections gallery, calendar (Trumba) integration and analytics. Also, the ability for non-technical
                      employees to update the site using Microsoft Visual Web Developer Express in a WYSIWYG format. Backend: ASP.NET MVC2,
                      SQL Server 2008 r2. Frontend: XHTML, jQuery.
                  </p>
                </q-item-section>
              </div>
            </div>
          </q-item>
        </q-list>
      </q-card-section>
    </q-card>

    <q-card class="q-mt-xl bg bg-education" id="education">
      <q-card-section>
        <h3 class="text-primary text-left">Education</h3>
        <div class="row">
          <div class="col-md-4 q-pb-md">
            <q-item-section middle avatar>
              <img src="~assets/logo-jmu.png" alt="James Madison University">
            </q-item-section>
          </div>
          <div class="col-md-8 self-center">
            <q-item-section>
              <q-item-label>James Madison University</q-item-label>
              <q-item-label caption>Harrisonburg, VA | 1994 - 1998</q-item-label>
              <div class="q-pt-md">
                <p>Bachelor of Science, <a href="http://isat.jmu.edu" target="_blank">Integrated Science and Technology</a>
                <br>Minor in Computer Science</p>
              </div>
            </q-item-section>
          </div>
        </div>
      </q-card-section>
    </q-card>

    <q-card class="q-mt-xl bg bg-personal" id="personal">
      <q-card-section>
        <h3 class="text-left">Personal</h3>
        <p>I enjoy new experiences and meeting new people. I've always secretly admired those who pick one passion and pursue it in perpetuity; alas, I am not one of those people.  I seek new experiences and avoid getting into a rut at all costs.</p>
        <p>Some of my favorite things to do include golf, hiking with my dogs, kickball, cooking (sometimes poorly), and karaoke (usually very poorly).  I'm also a cast member and founder of <a href="https://www.sosimprov.com" target="_blank">SOS Improv</a>. Get your tickets early, our shows sell out!</p>
        <p>So as not to lose my geek card, I am an avid Simpsons fan (encyclopedic knowledge spans seasons 1 through 10), electronics tinkerer, science/cosmology reader, and I love to play those video games all the kids are talking about.</p>
      </q-card-section>
    </q-card>

    <q-card class="q-mt-xl bg bg-contact" id="contact">
      <q-card-section>
        <h3 class="text-primary text-left">Contact</h3>
        <q-banner rounded class="bg-secondary text-white">
          So, you would like to get in touch with me. That's great!
          <div class="text-h6"><a href="mailto:matt@curtii.com" class="text-white">matt@curtii.com</a></div>
          <abbr title="Phone">P:</abbr> (704) 298-1316
        </q-banner>

        <p class="text-h4 q-pt-xl">Résumé / CV</p>
        <p>Oh, right, you probably want that.</p>
        <p class="text-center">
          <a href="/statics/MatthewCurtis.docx"><img class="shadow-2 on-left" src="~assets/icon-word.png" title="Microsoft Word Format" alt="Microsoft Word"></a>
          <a href="/statics/MatthewCurtis.pdf"><img class="shadow-2 on-left" src="~assets/icon-pdf.png" title="Acrobat (PDF) Format" alt="Adobe Acrobat"></a>
        </p>
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style lang="stylus">
  h3
    text-shadow 0px 0px 2px rgba(255, 255, 255, 0.75)
  .bg
    position relative
    z-index 1
    &::before
      content ""
      position absolute
      top 0
      left 0
      width 100%
      height 100%
      opacity .1
      z-index -1
      background-repeat no-repeat
    &.bg-skills::before
      background url('~assets/skills-bg.jpg') center center
    &.bg-experience::before
      background url('~assets/experience-bg.jpg') center center
    &.bg-education::before
      background url('~assets/education-bg.jpg') center center
    &.bg-personal::before
      background url('~assets/personal-bg.jpg') center center
      opacity .8
    &.bg-contact::before
      background url('~assets/contact-bg.jpg') center center
      opacity .2

  .img-outline
    border 1px solid $grey-5

  #personal
    h3, p, a
      color $grey-2

</style>
