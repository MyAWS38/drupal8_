<!DOCTYPE html>
<html lang="en" dir="ltr" prefix="content: http://purl.org/rss/1.0/modules/content/  dc: http://purl.org/dc/terms/  foaf: http://xmlns.com/foaf/0.1/  og: http://ogp.me/ns#  rdfs: http://www.w3.org/2000/01/rdf-schema#  schema: http://schema.org/  sioc: http://rdfs.org/sioc/ns#  sioct: http://rdfs.org/sioc/types#  skos: http://www.w3.org/2004/02/skos/core#  xsd: http://www.w3.org/2001/XMLSchema# ">
  <head>
    <meta charset="utf-8" />
<meta name="title" content="Disable Drupal 8 caching during development | gai Technologies Pvt Ltd" />
<meta name="description" content="We know Drupal 8 has a many levels of caching Render caching, Dynamic page caching, Twig template caching, When you are developing a module or a theme it is better to disable cache on the development stage rather than clearing cache for every change being made .

 

Copy and rename the sites/example.settings.local.php file as sites/default/settings.local.php. 

	 " />
<meta name="keywords" content="Drupal Development Company, Drupal 8 , Drupal Development, Hire Drupal Developers ,Web Development, Dharamshala" />
<meta name="Generator" content="Drupal 8 (https://www.drupal.org)" />
<meta name="MobileOptimized" content="width" />
<meta name="HandheldFriendly" content="true" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<script src="https://www.google.com/recaptcha/api.js?hl=en" async defer></script>
<link rel="shortcut icon" href="/sites/default/files/favicon.png" type="image/png" />
<link rel="canonical" href="http://gai.co.in/disable-drupal-8-caching-during-development" />
<link rel="shortlink" href="http://gai.co.in/node/140" />
<link rel="revision" href="http://gai.co.in/disable-drupal-8-caching-during-development" />

    <title>Disable Drupal 8 caching during development | gai Technologies Pvt Ltd</title>
    <link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/ajax-progress.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/align.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/autocomplete-loading.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/fieldgroup.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/container-inline.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/clearfix.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/details.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/hidden.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/item-list.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/js.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/nowrap.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/position-container.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/progress.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/reset-appearance.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/resize.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/sticky-header.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/system-status-counter.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/system-status-report-counters.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/system-status-report-general-info.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/tabledrag.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/tablesort.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/system/components/tree-child.module.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/assets/vendor/jquery.ui/themes/base/core.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/assets/vendor/jquery.ui/themes/base/button.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/assets/vendor/jquery.ui/themes/base/resizable.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/assets/vendor/jquery.ui/themes/base/dialog.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/assets/vendor/jquery.ui/themes/base/theme.css?ptef3q" />
<link rel="stylesheet" media="all" href="/modules/ubercart/uc_order/css/uc_order.css?ptef3q" />
<link rel="stylesheet" media="all" href="/modules/ubercart/uc_product/css/uc_product.css?ptef3q" />
<link rel="stylesheet" media="all" href="/modules/ubercart/uc_store/css/uc_store.css?ptef3q" />
<link rel="stylesheet" media="all" href="/modules/extlink/extlink.css?ptef3q" />
<link rel="stylesheet" media="all" href="/core/themes/stable/css/filter/filter.admin.css?ptef3q" />
<link rel="stylesheet" media="all" href="/themes/himalaya/css/style.css?ptef3q" />
<link rel="stylesheet" media="all" href="/themes/himalaya/css/responsive.css?ptef3q" />
<link rel="stylesheet" media="all" href="/themes/himalaya/css/custom.css?ptef3q" />

    
<!--[if lte IE 8]>
<script src="/core/assets/vendor/html5shiv/html5shiv.min.js?v=3.7.3"></script>
<![endif]-->
<script src="/core/assets/vendor/modernizr/modernizr.min.js?v=3.3.1"></script>

       <script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-84209558-1', 'auto');
  ga('send', 'pageview');

</script>

  </head>
  <body class="page-node-140 path-node node--type-blogs">
    <a href="#main-content" class="visually-hidden focusable skip-link">
      Skip to main content
    </a>
    
      <div class="dialog-off-canvas-main-canvas" data-off-canvas-main-canvas>
    <div id="page-wrapper" class="section">
  <div id="page">
    <header id="header" role="banner" aria-label="Site header">
      <nav id="navigation" class="margin_bottom">
        <div class="container mean-container">
                      <div class="logo">
                <div>
    <div id="block-himalaya-branding">
  
    
        <a href="/" title="Home" rel="home">
      <img src="/sites/default/files/gai-logo_0.jpg" alt="Home" />
    </a>
      
</div>

  </div>

            </div>
                    <div class="mean-bar">
                          <a href="#nav" class="meanmenu-reveal">
                <span></span>
                <span></span>
                <span></span>
              </a>
              <nav class="mean-nav submenu">
                  <div>
    <nav role="navigation" aria-labelledby="block-gaimainnavigaition-menu" id="block-gaimainnavigaition">
            
  <h2 class="visually-hidden" id="block-gaimainnavigaition-menu">Gai Main Navigaition</h2>
  

        
               <ul class="menu main-menu menu-level--0">
                    <li class="menu-item">
        <a href="/our-services" data-drupal-link-system-path="node/197">Our Services</a>
              </li>
                <li class="menu-item menu-item--expanded">
        <a href="/" title="Drupal projects and CSR activities" data-drupal-link-system-path="&lt;front&gt;">Our Work</a>
                                 <ul class="menu sub-menu-himalaya menu-level--1">
                    <li class="menu-item">
        <a href="/our-work" data-drupal-link-system-path="node/14">All</a>
              </li>
                <li class="menu-item">
        <a href="/education" data-drupal-link-system-path="education">Education</a>
              </li>
                <li class="menu-item">
        <a href="/nonprofit" data-drupal-link-system-path="nonprofit">Non Profits</a>
              </li>
                <li class="menu-item">
        <a href="/case-studies" data-drupal-link-system-path="case-studies">Case Studies</a>
              </li>
                <li class="menu-item">
        <a href="/white-papers" data-drupal-link-system-path="white-papers">White Papers</a>
              </li>
        </ul>
  
              </li>
                <li class="menu-item">
        <a href="/blogs" data-drupal-link-system-path="blogs">Blog</a>
              </li>
                <li class="menu-item">
        <a href="/about-us" data-drupal-link-system-path="node/196">About Us</a>
              </li>
                <li class="menu-item">
        <a href="/faq" data-drupal-link-system-path="node/159">FAQ</a>
              </li>
                <li class="menu-item">
        <a href="/contact" data-drupal-link-system-path="contact">Contact Us</a>
              </li>
        </ul>
  


  </nav>

  </div>
  
              </nav>
              
          </div>
                    <div id="main-menu">
                <div>
    <nav role="navigation" aria-labelledby="block-gaimainnavigaition-menu" id="block-gaimainnavigaition">
            
  <h2 class="visually-hidden" id="block-gaimainnavigaition-menu">Gai Main Navigaition</h2>
  

        
               <ul class="menu main-menu menu-level--0">
                    <li class="menu-item">
        <a href="/our-services" data-drupal-link-system-path="node/197">Our Services</a>
              </li>
                <li class="menu-item menu-item--expanded">
        <a href="/" title="Drupal projects and CSR activities" data-drupal-link-system-path="&lt;front&gt;">Our Work</a>
                                 <ul class="menu sub-menu-himalaya menu-level--1">
                    <li class="menu-item">
        <a href="/our-work" data-drupal-link-system-path="node/14">All</a>
              </li>
                <li class="menu-item">
        <a href="/education" data-drupal-link-system-path="education">Education</a>
              </li>
                <li class="menu-item">
        <a href="/nonprofit" data-drupal-link-system-path="nonprofit">Non Profits</a>
              </li>
                <li class="menu-item">
        <a href="/case-studies" data-drupal-link-system-path="case-studies">Case Studies</a>
              </li>
                <li class="menu-item">
        <a href="/white-papers" data-drupal-link-system-path="white-papers">White Papers</a>
              </li>
        </ul>
  
              </li>
                <li class="menu-item">
        <a href="/blogs" data-drupal-link-system-path="blogs">Blog</a>
              </li>
                <li class="menu-item">
        <a href="/about-us" data-drupal-link-system-path="node/196">About Us</a>
              </li>
                <li class="menu-item">
        <a href="/faq" data-drupal-link-system-path="node/159">FAQ</a>
              </li>
                <li class="menu-item">
        <a href="/contact" data-drupal-link-system-path="contact">Contact Us</a>
              </li>
        </ul>
  


  </nav>

  </div>

            </div>
                 </div>
      </nav>
    </header>
  <div class="main-content-wrapper">
         
      <div class="">
        <div class="help-wrapper float_left col-100">
            <div>
    <div data-drupal-messages-fallback class="hidden"></div>

  </div>

        </div>
      </div>
     
    <div id="main-wrapper" class="clearfix paddingt">
      <div id="main" class="clearfix container">
              <div class="top-content col-100 float_left">
          
        </div>
                        <main id="content" class="col-100 float_left" role="main">
          <section class="section">
            <a id="main-content" tabindex="-1"></a>
            
                        
                          <div>
    <h1 class="node__title" id="page__node--title">
          <span>Disable Drupal 8 caching during development</span>

    </h1>
<article data-history-node-id="140" role="article" class="node margin_bottom blogs node--type-blogs node--view-mode-full clearfix" about="/disable-drupal-8-caching-during-development">
  <header>
    
        
          <div class="submitted-by">
      <div class="node__meta">
        <div class="user-picture">
         <article typeof="schema:Person" about="/user/986">
  </article>

       </div>
        <div class="submitted-by-innerwrap">
        <span>
          <span class="calendar"></span>Submitted by <span><span lang="" about="/user/986" typeof="schema:Person" property="schema:name" datatype="">amit</span></span>
 on <span>Thu, 02/08/2018 - 13:02</span>
        </span>
      </div>
        
      </div>
    </div>
      </header>
  <div class="node__content clearfix">
    
  <div>
    <div>Image</div>
              <div>  <img src="/sites/default/files/2018-02/maxresdefault_0.jpg" width="1920" height="1080" alt="Image" typeof="foaf:Image" />

</div>
          </div>

            <div><p dir="ltr"><span>We know Drupal 8 has a many levels of caching </span><strong>Render caching, Dynamic page caching, Twig template caching</strong><span>, When you are developing a module or a theme it is better to disable cache on the development stage rather than clearing cache for every change being made .</span></p>

<p dir="ltr"> </p>

<ol dir="ltr"><li><span>Copy and rename the sites/example.settings.local.php file as sites/default/settings.local.php.</span><span> </span>

	<p dir="ltr"> </p>

	<p><img alt="image" data-entity-type="file" data-entity-uuid="5754dc53-11a7-46a6-9fcf-b81f7d742066" src="/sites/default/files/inline-images/1_1.jpeg" /></p>
	</li>
	<li><span>In your settings.local.php file, locate the section that starts with "Disable the render cache". </span>
	<p> </p>

	<p dir="ltr"><img alt="Image" data-entity-type="file" data-entity-uuid="b7a92771-d01e-4549-9b68-b5aac9753f60" src="/sites/default/files/inline-images/2.jpeg" /></p>
	</li>
	<li>
	<p dir="ltr"><span>Uncomment the $settings variable for that section:</span></p>
	</li>
	<li>
	<p dir="ltr"><strong>$settings['cache']['bins']['render'] = 'cache.backend.null';</strong></p>
	</li>
	<li>
	<p dir="ltr"><strong>Dynamic page caching: </strong><span>Dynamic page caching is when Drupal takes the entire rendered output of a page and stores it in the database (or another cache store; defaults to the database). Pages will only be cached for anonymous traffic and for users that don't have session data, like items in a shopping cart</span><strong>. </strong></p>
	</li>
	<li>
	<p dir="ltr"><span>In your settings.local.php file, locate the section that starts with "Disable Dynamic Page Cache".</span></p>

	<p> </p>
	<img alt="Image" data-entity-type="file" data-entity-uuid="dd994b38-d7d3-4f70-9748-73f543501d85" src="/sites/default/files/inline-images/3_0.jpeg" /></li>
	<li><span>Uncomment the $settings variable for that section:</span>
	<p dir="ltr"><strong>$settings['cache']['bins']['dynamic_page_cache'] = 'cache.backend.null';</strong></p>
	</li>
	<li><span>Open settings.php file in sites/default directory and , locate the section that starts with "settings.local.php".</span>
	<p> </p>

	<p dir="ltr"><img alt="Image" data-entity-type="file" data-entity-uuid="a6e5616f-10af-4f0b-be86-1a29f87e13c5" src="/sites/default/files/inline-images/4_0.jpeg" /></p>
	</li>
	<li>
	<p dir="ltr"><span>Uncomment the section:</span></p>
	 

	<p dir="ltr"><strong>if (file_exists($app_root . '/' . $site_path . '/settings.local.php')) {</strong></p>

	<p dir="ltr"><strong> include $app_root . '/' . $site_path . '/settings.local.php';</strong></p>

	<p dir="ltr"><strong>}</strong></p>
	</li>
	<li><span>open development.services.yml in the sites folder and add the following lines (to disable twig cache) </span><br />
	 
	<p dir="ltr"><strong>parameters:</strong></p>

	<p dir="ltr"><strong> twig.config:</strong></p>

	<p dir="ltr"><strong>   debug: true</strong></p>

	<p dir="ltr"><strong>   auto_reload: true</strong></p>

	<p dir="ltr"><strong>   cache: false</strong></p>
	</li>
	<li>
	<p dir="ltr"><span>Your final development.services.yml should look as follows:</span></p>

	<p> </p>

	<p dir="ltr"><img alt="Image" data-entity-type="file" data-entity-uuid="f81b43da-307a-4824-a73a-b40d8b0dd48d" src="/sites/default/files/inline-images/5.jpeg" /></p>
	</li>
	<li><span>After the above steps, you need to rebuild the Drupal cache.</span><br />
	 
	<p dir="ltr"><span>1 - drush cache-rebuild </span></p>

	<p dir="ltr"><span>2 - drush cr</span></p>
	</li>
	<li>
	<p dir="ltr"><span>Now After changes done, Drupal's caching system is effectively turned off.</span></p>
	</li>
</ol></div>
      <div class="sharethis-wrapper"><span st_url="http://gai.co.in/disable-drupal-8-caching-during-development" st_title="Disable Drupal 8 caching during development" class="st_facebook"></span>
<span st_url="http://gai.co.in/disable-drupal-8-caching-during-development" st_title="Disable Drupal 8 caching during development" class="st_twitter"></span>
<span st_url="http://gai.co.in/disable-drupal-8-caching-during-development" st_title="Disable Drupal 8 caching during development" class="st_linkedin"></span>
</div>
  </div>
      <div class="node__links"><ul class="links inline"><li class="comment-add"><a href="/disable-drupal-8-caching-during-development#comment-form" title="Share your thoughts and opinions." hreflang="en">Add new comment</a></li></ul></div>
    
  <div class="back-to-page">Back</div>
</article>

    
  </div>

          </section>
        </main>
                 
        <div class="bottom col-100 float_left">
            <div>
    <div id="block-comments" class="comment-block">
  
    
      <section>
      
    <h2>Comments</h2>
    
  
    
<article role="article" data-comment-user-id="0" id="comment-1897" about="/comment/1897" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561196212"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1897#comment-1897" class="permalink" rel="bookmark" hreflang="en">cheap hotel booking</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1897#comment-1897" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">tour packages (not verified)</span></span>
 Sat, 06/22/2019 - 15:06  <span property="schema:dateCreated" content="2019-06-22T09:36:52+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p><a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_80"> Flight booking </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_80"> Flight ticket booking </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_43"> Booking hotels </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_43"> Online hotel booking </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_43"> Online hotel booking from kuwait </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_43"> Cheap hotel booking </a><br />
<a href="https://www.afrahtravel.com/"> Travel packages </a><br />
<a href="https://www.afrahtravel.com/">Holiday packages</a><br />
<a href="https://www.afrahtravel.com/">Tour packages</a><br />
<a href="https://www.afrahtravel.com/">Travel agency in kuwait</a><br />
<a href="https://www.afrahtravel.com/">Travel packages from kuwait</a><br />
<a href="https://www.afrahtravel.com/">Holiday packages from kuwait</a><br />
<a href="https://www.afrahtravel.com/">Kuwait airways online booking</a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_92"> Best prices apartment in Kuwait </a><br />
<a href="https://www.afrahtravel.com/en/Shared/CmsMainSubpage/service_80"> Cheap price of flight ticket in kuwait </a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1897">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1909" about="/comment/1909" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561345302"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1909#comment-1909" class="permalink" rel="bookmark" hreflang="en">I enjoy what youve got right…</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1909#comment-1909" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">samuelddarden (not verified)</span></span>
 Mon, 06/24/2019 - 08:31  <span property="schema:dateCreated" content="2019-06-24T03:01:42+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>I enjoy what youve got right here, adore what youre stating and the way you say it. You make it entertaining and you even now manage to help keep it wise. I cant wait to go through additional from you. <a href="https://games.lol/candy-crush-soda-saga/">candy crush soda saga</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1909">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1919" about="/comment/1919" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561441450"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1919#comment-1919" class="permalink" rel="bookmark" hreflang="en">new mobile phones</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1919#comment-1919" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">theviralvista (not verified)</span></span>
 Tue, 06/25/2019 - 11:14  <span property="schema:dateCreated" content="2019-06-25T05:44:10+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p><a href="https://www.theviralvista.com/new-xiaomi-mobile-phones-under-30000-rs">New Xiaomi Mobile phones under 30000 rs</a></p>
<p><a href="https://www.theviralvista.com/latest-vivo-mobile-phones-under-30000-rs/">Latest Vivo Mobile phones under 30000 rs  </a></p>
<p><a href="https://www.theviralvista.com/7-latest-anroid-smartphone-2019">7 Latest anroid smartphone 2019 | samsung, Redmi, Xiaomi,</a></p>
<p><a href="https://www.theviralvista.com/new-oppo-mobile-phones-under-30000-rs">New oppo Mobile phones under 30000 rs&lt;/a&gt; oppo Mobile phones  </a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1919">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1928" about="/comment/1928" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561617570"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1928#comment-1928" class="permalink" rel="bookmark" hreflang="en">base oil sn500</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1928#comment-1928" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">Base oil (not verified)</span></span>
 Thu, 06/27/2019 - 12:09  <span property="schema:dateCreated" content="2019-06-27T06:39:30+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p><a href="http://butterfly.co.com/"> Base oil </a><br />
<a href="http://butterfly.co.com/"> Base oil Sn150</a><br />
<a href="http://butterfly.co.com/"> Bright stock 150 </a><br />
<a href="http://butterfly.co.com/"> Base oil Sn500</a><br />
<a href="http://butterfly.co.com/"> Base oil Sn600 </a><br />
<a href="http://butterfly.co.com/"> White spirit</a><br />
<a href="http://butterfly.co.com/"> base oil suppliers </a><br />
<a href="http://butterfly.co.com/"> base oil traders in kuwait </a><br />
<a href="http://butterfly.co.com/"> bright stock 150 supplier in kuwait </a><br />
<a href="http://butterfly.co.com/tag/bright-stock-150-supplier-in-kuwait/"> bright stock 150 supplier in kuwait </a><br />
<a href="http://butterfly.co.com/tag/low-aromatic-white-spirit-suppliers/"> low aromatic white spirit suppliers </a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1928">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1942" about="/comment/1942" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561808408"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1942#comment-1942" class="permalink" rel="bookmark" hreflang="en">DedicatedHosting4u</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1942#comment-1942" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">DedicatedHosting4u (not verified)</span></span>
 Sat, 06/29/2019 - 17:10  <span property="schema:dateCreated" content="2019-06-29T11:40:08+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>Just seen your Article, it amazed me and surpised me with god thoughts that eveyone will benefit from it. It is really a very informative post for all those budding entreprenuers planning to take advantage of post for business expansions. You always share such a wonderful articlewhich helps us to gain knowledge .Thanks for sharing such a wonderful article, It will be deinitely helpful and fruitful article.<br />
Thanks<br />
<a href="https://www.DedicatedHosting4u.com/">DedicatedHosting4u.com</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1942">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1948" about="/comment/1948" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1561953319"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1948#comment-1948" class="permalink" rel="bookmark" hreflang="en">locksmith perth</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1948#comment-1948" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">locksmith perth (not verified)</span></span>
 Mon, 07/01/2019 - 09:25  <span property="schema:dateCreated" content="2019-07-01T03:55:19+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>All workmanship and products are guaranteed and we pride ourselves on offering outstanding value for money,<a href="https://www.guvlock.com.au/">locksmith perth</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1948">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1966" about="/comment/1966" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1562107876"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1966#comment-1966" class="permalink" rel="bookmark" hreflang="en">I luvvvv this</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1966#comment-1966" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">Jon Smith (not verified)</span></span>
 Wed, 07/03/2019 - 04:21  <span property="schema:dateCreated" content="2019-07-02T22:51:16+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p><a href="https://www.illinoiswindowreplacement.com/">https://www.illinoiswindowreplacement.com/</a><br />
<a href="https://www.replacementwindowsillinois.com/">https://www.replacementwindowsillinois.com/</a><br />
<a href="https://www.partyballoondecorationsorlandpark.com/">https://www.partyballoondecorationsorlandpark.com/</a><br />
<a href="https://www.kuksoolwonofnormal.com/">https://www.kuksoolwonofnormal.com/</a><br />
<a href="https://www.knoxvillefencepros.com/">https://www.knoxvillefencepros.com/</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1966">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1967" about="/comment/1967" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1562108209"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1967#comment-1967" class="permalink" rel="bookmark" hreflang="en">WOW</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1967#comment-1967" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">ronnie smith (not verified)</span></span>
 Wed, 07/03/2019 - 04:26  <span property="schema:dateCreated" content="2019-07-02T22:56:49+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p><a href="https://www.knoxautodetail.com/">https://www.knoxautodetail.com/</a><br />
<a href="https://partybussouthbend.com/index.html">https://partybussouthbend.com/index.html</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1967">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-1997" about="/comment/1997" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1562576930"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/1997#comment-1997" class="permalink" rel="bookmark" hreflang="en">Hotmail customer service number </a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/1997#comment-1997" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">Ehowtech (not verified)</span></span>
 Mon, 07/08/2019 - 14:38  <span property="schema:dateCreated" content="2019-07-08T09:08:50+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>Ehowtech is a informative site which solves technical problems regarding Hotmail Account. Our experts are always available for you. It provides you Hotmail Contact Number, Hotmail Phone Number UK, Hotmail Technical Support Number UK, Hotmail Contact Number UK,Hotmail Technical Support Number, so that you can talk with our experts without any issue and your problems can be solved. you can directly call us on +44 800-090-3909</p>
<p><a href="https://www.ehowtech.co.uk/"> Hotmail Customer Service Number </a><br />
<a href="https://www.ehowtech.co.uk/"> Hotmail phone number  </a><br />
<a href="https://www.ehowtech.co.uk/"> Hotmail helpline phone number </a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/1997">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-2016" about="/comment/2016" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1562718499"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/2016#comment-2016" class="permalink" rel="bookmark" hreflang="en">Thanks for the advice</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/2016#comment-2016" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">john blacken (not verified)</span></span>
 Wed, 07/10/2019 - 05:58  <span property="schema:dateCreated" content="2019-07-10T00:28:19+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>Thanks for the update. I am going to implement this on all my computers</p>
<p>J. Blacken owner of </p>
<p><a href="https://www.airductcleaningcincy.com">https://www.airductcleaningcincy.com</a><br />
<a href="https://www.dumpsterforrentdayton.com">https://www.dumpsterforrentdayton.com</a><br />
<a href="https://www.excavationdayton.com">https://www.excavationdayton.com</a><br />
<a href="https://www.springfieldpavingco.com">https://www.springfieldpavingco.com</a><br />
<a href="https://www.towtruckparma.com">https://www.towtruckparma.com</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/2016">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>
  
<article role="article" data-comment-user-id="0" id="comment-2032" about="/comment/2032" typeof="schema:Comment" class="comment by-anonymous clearfix">
  <header class="comment-header">
      <div class="comment__submitted">
        <div class="user-picture">
          <article typeof="schema:Person" about="/user/0">
  </article>

        </div>
                    </div>
  </header>
  <div class="comment__text">
        <span class="hidden new" data-comment-timestamp="1562928491"></span>
          
        <h3 property="schema:name" datatype=""><a href="/comment/2032#comment-2032" class="permalink" rel="bookmark" hreflang="en">Thanks for sharing nice…</a></h3>
      
        <p class="comment__author comment__submitted__data"><a href="/comment/2032#comment-2032" hreflang="en">Permalink</a> Submitted by <span rel="schema:author"><span lang="" typeof="schema:Person" property="schema:name" datatype="">MindtechAffiliates (not verified)</span></span>
 Fri, 07/12/2019 - 16:18  <span property="schema:dateCreated" content="2019-07-12T10:48:11+00:00" class="hidden"></span>
</p>
    <div class="comment__content">
      
            <div property="schema:text"><p>Thanks for sharing nice information with us. I like your post and all you share with us is up to date and quite informative, </p>
<p>Thanks<br />
<a href="https://www.mindtechaffiliates.com">Cpa offers</a></p>
</div>
      
    </div>
    <footer class="comment__footer">
              <nav><ul class="links inline"><li class="comment-reply"><a href="/comment/reply/node/140/field_comments/2032">Reply</a></li></ul></nav>
          </footer>
  </div>
</article>


      <h2>Add new comment</h2>
    <form class="comment-comment-form comment-form" data-drupal-selector="comment-form" action="/comment/reply/node/140/field_comments" method="post" id="comment-form" accept-charset="UTF-8">
  <div class="js-form-item form-item js-form-type-textfield form-item-name js-form-item-name">
      <label for="edit-name">Your name</label>
        <input data-drupal-default-value="Anonymous" data-drupal-selector="edit-name" type="text" id="edit-name" name="name" value="" size="30" maxlength="60" class="form-text" />

        </div>
<input autocomplete="off" data-drupal-selector="form-zljvd2rtloa6-jvrsnvotqn4tufuy474ugyola3bwbm" type="hidden" name="form_build_id" value="form-zLJVD2rtLoa6_jvRsNvotQn4tuFUy474uGYoLA3bwBM" />
<input data-drupal-selector="edit-comment-comment-form" type="hidden" name="form_id" value="comment_comment_form" />
<input data-drupal-selector="edit-honeypot-time" type="hidden" name="honeypot_time" value="FF3UKgRl3ganGMsykFtgxHzMKINKX_MQ1YT87P1vNfI" />
<div class="field--type-language field--name-langcode field--widget-language-select js-form-wrapper form-wrapper" data-drupal-selector="edit-langcode-wrapper" id="edit-langcode-wrapper">
      
  </div>
<div class="field--type-string field--name-subject field--widget-string-textfield js-form-wrapper form-wrapper" data-drupal-selector="edit-subject-wrapper" id="edit-subject-wrapper">
      <div class="js-form-item form-item js-form-type-textfield form-item-subject-0-value js-form-item-subject-0-value">
      <label for="edit-subject-0-value">Subject</label>
        <input class="js-text-full text-full form-text" data-drupal-selector="edit-subject-0-value" type="text" id="edit-subject-0-value" name="subject[0][value]" value="" size="60" maxlength="64" placeholder="" />

        </div>

  </div>
<div class="field--type-text-long field--name-comment-body field--widget-text-textarea js-form-wrapper form-wrapper" data-drupal-selector="edit-comment-body-wrapper" id="edit-comment-body-wrapper">
      <div class="js-text-format-wrapper js-form-item form-item">
  <div class="js-form-item form-item js-form-type-textarea form-item-comment-body-0-value js-form-item-comment-body-0-value">
      <label for="edit-comment-body-0-value" class="js-form-required form-required">Comment</label>
        <div>
  <textarea class="js-text-full text-full form-textarea required" data-drupal-selector="edit-comment-body-0-value" id="edit-comment-body-0-value" name="comment_body[0][value]" rows="5" cols="60" placeholder="" required="required" aria-required="true"></textarea>
</div>

        </div>
<div class="filter-wrapper js-form-wrapper form-wrapper" data-drupal-selector="edit-comment-body-0-format" id="edit-comment-body-0-format"><div class="filter-help js-form-wrapper form-wrapper" data-drupal-selector="edit-comment-body-0-format-help" id="edit-comment-body-0-format-help"><a href="/filter/tips" target="_blank" data-drupal-selector="edit-comment-body-0-format-help-about" id="edit-comment-body-0-format-help-about">About text formats</a></div>
<div class="filter-guidelines js-form-wrapper form-wrapper" data-drupal-selector="edit-comment-body-0-format-guidelines" id="edit-comment-body-0-format-guidelines"><div>
  <h4>Restricted HTML</h4>
  
  
    
          <ul>
              <li>Allowed HTML tags: &lt;a href hreflang&gt; &lt;em&gt; &lt;strong&gt; &lt;cite&gt; &lt;blockquote cite&gt; &lt;code&gt; &lt;ul type&gt; &lt;ol start type&gt; &lt;li&gt; &lt;dl&gt; &lt;dt&gt; &lt;dd&gt; &lt;h2 id&gt; &lt;h3 id&gt; &lt;h4 id&gt; &lt;h5 id&gt; &lt;h6 id&gt;</li>
              <li>Lines and paragraphs break automatically.</li>
              <li>Web page addresses and email addresses turn into links automatically.</li>
            </ul>
    
    
  
</div>
</div>
</div>

  </div>

  </div>
  <details class="captcha js-form-wrapper form-wrapper" open="open">
  <summary role="button" aria-expanded="true" aria-pressed="true">CAPTCHA</summary>
  This question is for testing whether or not you are a human visitor and to prevent automated spam submissions.
  <input data-drupal-selector="edit-captcha-sid" type="hidden" name="captcha_sid" value="45746" />
<input data-drupal-selector="edit-captcha-token" type="hidden" name="captcha_token" value="147eb4d4c7e7ae6a2efd13de9f2233e0" />
<input data-drupal-selector="edit-captcha-response" type="hidden" name="captcha_response" value="Google no captcha" />
<div class="g-recaptcha" data-sitekey="6Ld08BUUAAAAAI08633hf5ti5ugAamvojF7XhhHr" data-theme="light" data-type="image"></div>
  
</details>

<div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions"><input data-drupal-selector="edit-submit" type="submit" id="edit-submit" name="op" value="Save" class="button button--primary js-form-submit form-submit" />
<input data-drupal-selector="edit-preview" type="submit" id="edit-preview" name="op" value="Preview" class="button js-form-submit form-submit" />
</div>
<div class="url-textfield js-form-wrapper form-wrapper" style="display: none !important;"><input autocomplete="off" data-drupal-selector="edit-url" type="text" id="edit-url" name="url" value="" size="20" maxlength="128" class="form-text" />
</div>

</form>

  
</section>

  </div>

  </div>

        </div>
              </div>
    </div>
  </div>
</div>
</div>
<div id="footer">
      <div class="section section-full-colored">
      <div class="section-content center">
          <div>
    <div id="block-footerblock">
  
    
      
            <div><div class="social__link-main--wrapper">
<div class="career__detail--wrapper footer__wrapper"><a class="services-pay" href="/hosting-provider-price-details">Server Hosting PG</a></div>

<div class="contact__detail--wrapper footer__wrapper">
<ul class="detail"><li><a href="mailto:info@gai.co.in">info at gai.co.in</a></li>
	<li><a href="tel:+91 98160-88451">+91 98160-88451</a></li>
</ul></div>

<div class="social__link--wrapper footer__wrapper">
<ul class="social__link"><li><a href="https://www.facebook.com/gaitechnologies" target="_blank"><img alt="facebook" data-entity-type="file" data-entity-uuid="9d15ddca-cfd4-4c04-87e0-748169f3862e" src="/sites/default/files/inline-images/1467122681_facebook.png" /></a></li>
	<li><a href="https://twitter.com/gaitechno" target="_blank"><img alt="twitter" data-entity-type="file" data-entity-uuid="cb782893-940e-4d68-9fbb-d45a52698a40" src="/sites/default/files/inline-images/1467122673_twitter.png" /></a></li>
	<li><a href="https://www.linkedin.com/company/gai-technologies-pvt-ltd-" target="_blank"><img alt="linked" data-entity-type="file" data-entity-uuid="f4bc06cc-8a88-4e8a-b740-12b0791eca6d" src="/sites/default/files/inline-images/1467122694_linkedin.png" /></a></li>
</ul></div>
</div>
</div>
      
  </div>

  </div>

      </div>
    </div>
  </div>
<a href="#" class="scrolltop" style="display: block;" >Top</a>

  </div>

    
    <script type="application/json" data-drupal-selector="drupal-settings-json">{"path":{"baseUrl":"\/","scriptPath":null,"pathPrefix":"","currentPath":"node\/140","currentPathIsAdmin":false,"isFront":false,"currentLanguage":"en"},"pluralDelimiter":"\u0003","ajaxPageState":{"libraries":"captcha\/base,classy\/drupal.comment.threaded,comment\/drupal.comment-by-viewer,core\/drupal.collapse,core\/html5shiv,extlink\/drupal.extlink,filter\/drupal.filter,himalaya\/global-scripts,himalaya\/global-styling,sharethis\/sharethis,sharethis\/sharethispickerexternalbuttons,sharethis\/sharethispickerexternalbuttonsws,system\/base,uc_order\/uc_order.styles,uc_product\/uc_product.styles,uc_store\/uc_store.styles","theme":"himalaya","theme_token":null},"ajaxTrustedUrl":{"\/comment\/reply\/node\/140\/field_comments":true},"data":{"extlink":{"extTarget":true,"extNofollow":false,"extClass":"0","extLabel":"","extImgClass":false,"extSubdomains":false,"extExclude":"","extInclude":"","extCssExclude":"","extCssExplicit":"","extAlert":false,"extAlertText":"","mailtoClass":"0","mailtoLabel":""}},"sharethis":{"publisher":"dr-1c79cdee-d7f4-425a-5f6b-e6e9407e1712","version":"5x","doNotCopy":true,"hashAddressBar":false,"doNotHash":true},"user":{"uid":0,"permissionsHash":"a40452fa4dee80b1986abb59869c7d284a7951b9abff8af07324f6992fdfe214"}}</script>
<script src="/core/assets/vendor/domready/ready.min.js?v=1.0.8"></script>
<script src="/core/assets/vendor/jquery/jquery.min.js?v=3.2.1"></script>
<script src="/core/assets/vendor/jquery/jquery-extend-3.4.0.js?v=3.2.1"></script>
<script src="/core/assets/vendor/jquery-once/jquery.once.min.js?v=2.2.0"></script>
<script src="/core/misc/drupalSettingsLoader.js?v=8.7.3"></script>
<script src="/core/misc/drupal.js?v=8.7.3"></script>
<script src="/core/misc/drupal.init.js?v=8.7.3"></script>
<script src="/core/assets/vendor/jquery.ui/ui/data-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/disable-selection-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/form-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/labels-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/jquery-1-7-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/scroll-parent-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/tabbable-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/unique-id-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/version-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/focusable-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/ie-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/keycode-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/plugin-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/safe-active-element-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/safe-blur-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widget-min.js?v=1.12.1"></script>
<script src="/modules/sharethis/js/sharethis.js?ptef3q"></script>
<script src="/core/misc/progress.js?v=8.7.3"></script>
<script src="/core/misc/ajax.js?v=8.7.3"></script>
<script src="/core/misc/debounce.js?v=8.7.3"></script>
<script src="/core/misc/displace.js?v=8.7.3"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widgets/button-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widgets/mouse-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widgets/draggable-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/position-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widgets/resizable-min.js?v=1.12.1"></script>
<script src="/core/assets/vendor/jquery.ui/ui/widgets/dialog-min.js?v=1.12.1"></script>
<script src="/core/misc/dialog/dialog.js?v=8.7.3"></script>
<script src="/core/misc/dialog/dialog.position.js?v=8.7.3"></script>
<script src="/core/misc/dialog/dialog.jquery-ui.js?v=8.7.3"></script>
<script src="/core/misc/dialog/dialog.ajax.js?v=8.7.3"></script>
<script src="/themes/himalaya/js/site.min.js?v=8.7.3"></script>
<script src="/themes/himalaya/js/custom.js?v=8.7.3"></script>
<script src="/modules/extlink/extlink.min.js?v=8.7.3"></script>
<script src="/core/modules/comment/js/comment-by-viewer.js?v=8.7.3"></script>
<script src="https://ws.sharethis.com/button/buttons.js"></script>
<script src="/core/assets/vendor/jquery.cookie/jquery.cookie.min.js?v=1.4.1"></script>
<script src="/core/misc/form.js?v=8.7.3"></script>
<script src="/core/misc/details-aria.js?v=8.7.3"></script>
<script src="/core/misc/collapse.js?v=8.7.3"></script>
<script src="/core/modules/filter/filter.js?v=8.7.3"></script>

  </body>
</html>
