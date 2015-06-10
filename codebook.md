


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>Getting-and-Cleaning-Data-Peer-Assesment/codebook.md at master · haizman/Getting-and-Cleaning-Data-Peer-Assesment · GitHub</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="haizman/Getting-and-Cleaning-Data-Peer-Assesment" name="twitter:title" /><meta content="Getting-and-Cleaning-Data-Peer-Assesment - Getting and Cleaning Data Peer Assesment" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/7266114?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/7266114?v=3&amp;s=400" property="og:image" /><meta content="haizman/Getting-and-Cleaning-Data-Peer-Assesment" property="og:title" /><meta content="https://github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment" property="og:url" /><meta content="Getting-and-Cleaning-Data-Peer-Assesment - Getting and Cleaning Data Peer Assesment" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    
    <meta name="pjax-timeout" content="1000">
    

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="3F7FE8C4:4ACD:196E4B:5578918E" name="octolytics-dimension-request_id" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged Out">
    <meta class="js-ga-set" name="dimension2" content="Header v3">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="4+lMiPfbMmUqaJhnFqiN1mTCMN8uRt5oQzWeV99WmJyVELmU5E6wDARtEfHnV7QmcrvzBQ8MUQziJCyb/9JUmw==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-ca63068899b9b8d1b9324df8de236c0d49416ae78cc083336c84a5692ccf9546.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-1b83a5e3cdbe8e2d3d0d957bad4e28490ded53991b08efea2ca0ad708622e92a.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="705d6d6ea883e77c09fe71a492a41357">

      
  <meta name="description" content="Getting-and-Cleaning-Data-Peer-Assesment - Getting and Cleaning Data Peer Assesment">
  <meta name="go-import" content="github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment git https://github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment.git">

  <meta content="7266114" name="octolytics-dimension-user_id" /><meta content="haizman" name="octolytics-dimension-user_login" /><meta content="20081825" name="octolytics-dimension-repository_id" /><meta content="haizman/Getting-and-Cleaning-Data-Peer-Assesment" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="20081825" name="octolytics-dimension-repository_network_root_id" /><meta content="haizman/Getting-and-Cleaning-Data-Peer-Assesment" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment/commits/master.atom" rel="alternate" title="Recent Commits to Getting-and-Cleaning-Data-Peer-Assesment:master" type="application/atom+xml">

  </head>


  <body class="logged_out  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        
        <div class="header header-logged-out" role="banner">
  <div class="container clearfix">

    <a class="header-logo-wordmark" href="https://github.com/" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
      <span class="mega-octicon octicon-logo-github"></span>
    </a>

    <div class="header-actions" role="navigation">
        <a class="btn btn-primary" href="/join" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
      <a class="btn" href="/login?return_to=%2Fhaizman%2FGetting-and-Cleaning-Data-Peer-Assesment%2Fblob%2Fmaster%2Fcodebook.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
    </div>

    <div class="site-search repo-scope js-site-search" role="search">
      <form accept-charset="UTF-8" action="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
    </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item">
            <a class="header-nav-link" href="/explore" data-ga-click="(Logged out) Header, go to explore, text:explore">Explore</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/features" data-ga-click="(Logged out) Header, go to features, text:features">Features</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://enterprise.github.com/" data-ga-click="(Logged out) Header, go to enterprise, text:enterprise">Enterprise</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="(Logged out) Header, go to blog, text:blog">Blog</a>
          </li>
      </ul>

  </div>
</div>



      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <a href="/login?return_to=%2Fhaizman%2FGetting-and-Cleaning-Data-Peer-Assesment"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <span class="octicon octicon-eye"></span>
    Watch
  </a>
  <a class="social-count" href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/watchers">
    1
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fhaizman%2FGetting-and-Cleaning-Data-Peer-Assesment"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <span class="octicon octicon-star"></span>
    Star
  </a>

    <a class="social-count js-social-count" href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/stargazers">
      0
    </a>

  </li>

    <li>
      <a href="/login?return_to=%2Fhaizman%2FGetting-and-Cleaning-Data-Peer-Assesment"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <span class="octicon octicon-repo-forked"></span>
        Fork
      </a>
      <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/network" class="social-count">
        2
      </a>
    </li>
</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/haizman" class="url fn" itemprop="url" rel="author"><span itemprop="title">haizman</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment" data-pjax="#js-repo-pjax-container">Getting-and-Cleaning-Data-Peer-Assesment</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /haizman/Getting-and-Cleaning-Data-Peer-Assesment">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /haizman/Getting-and-Cleaning-Data-Peer-Assesment/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /haizman/Getting-and-Cleaning-Data-Peer-Assesment/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /haizman/Getting-and-Cleaning-Data-Peer-Assesment/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /haizman/Getting-and-Cleaning-Data-Peer-Assesment/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/haizman/Getting-and-Cleaning-Data-Peer-Assesment" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form " data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="WO5wRAIKm/8qr5z+3lR/PlV6aVWHIoL/dK7a8WKF1iLECo9lsYSlNLMll1PTG1YHniPGsiuERakob89ngdRHoQ==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form> or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form " data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ZxkmPcAm6bqsfIJ6QfyLoSRJAxl1OaH3UX+Q+aV8oEMrr4lsDYVoR96EdvEkbANZNIoVQBroDfwi+0S15IIbgw==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save haizman/Getting-and-Cleaning-Data-Peer-Assesment to your computer and use it in GitHub Desktop." aria-label="Save haizman/Getting-and-Cleaning-Data-Peer-Assesment to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of haizman/Getting-and-Cleaning-Data-Peer-Assesment as a zip file"
                   title="Download the contents of haizman/Getting-and-Cleaning-Data-Peer-Assesment as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/blob/f71c6822bb143a71beea18ecbf902506d60bdc03/codebook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:41659786ee5f8dbfa08389424b67cc2c -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/blob/master/codebook.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">Getting-and-Cleaning-Data-Peer-Assesment</span></a></span></span><span class="separator">/</span><strong class="final-path">codebook.md</strong>
  </div>
</div>

<include-fragment class="commit commit-loader file-history-tease" src="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/contributors/master/codebook.md">
  <div class="file-history-tease-header">
    Fetching contributors&hellip;
  </div>

  <div class="participation">
    <p class="loader-loading"><img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-EAF2F5-0bdc57d34b85c4a4de9d0d1db10cd70e8a95f33ff4f46c5a8c48b4bf4e5a9abe.gif" width="16" /></p>
    <p class="loader-error">Cannot retrieve contributors at this time</p>
  </div>
</include-fragment>
<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/raw/master/codebook.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/blame/master/codebook.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/haizman/Getting-and-Cleaning-Data-Peer-Assesment/commits/master/codebook.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

          <button type="button" class="octicon-btn disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
            <span class="octicon octicon-pencil"></span>
          </button>

        <button type="button" class="octicon-btn octicon-btn-danger disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
          <span class="octicon octicon-trashcan"></span>
        </button>
    </div>

    <div class="file-info">
        84 lines (83 sloc)
        <span class="file-info-divider"></span>
      1.789 kB
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-codebook" class="anchor" href="#codebook" aria-hidden="true"><span class="octicon octicon-link"></span></a>Codebook</h1>

<ol>
<li>subjectid</li>
<li>activitylabel</li>
<li>tbodyaccmeanx</li>
<li>tbodyaccmeany</li>
<li>tbodyaccmeanz</li>
<li>tgravityaccmeanx</li>
<li>tgravityaccmeany</li>
<li>tgravityaccmeanz</li>
<li>tbodyaccjerkmeanx</li>
<li>tbodyaccjerkmeany</li>
<li>tbodyaccjerkmeanz</li>
<li>tbodygyromeanx</li>
<li>tbodygyromeany</li>
<li>tbodygyromeanz</li>
<li>tbodygyrojerkmeanx</li>
<li>tbodygyrojerkmeany</li>
<li>tbodygyrojerkmeanz</li>
<li>tbodyaccmagmean</li>
<li>tgravityaccmagmean</li>
<li>tbodyaccjerkmagmean</li>
<li>tbodygyromagmean</li>
<li>tbodygyrojerkmagmean</li>
<li>fbodyaccmeanx</li>
<li>fbodyaccmeany</li>
<li>fbodyaccmeanz</li>
<li>fbodyaccmeanfreqx</li>
<li>fbodyaccmeanfreqy</li>
<li>fbodyaccmeanfreqz</li>
<li>fbodyaccjerkmeanx</li>
<li>fbodyaccjerkmeany</li>
<li>fbodyaccjerkmeanz</li>
<li>fbodyaccjerkmeanfreqx</li>
<li>fbodyaccjerkmeanfreqy</li>
<li>fbodyaccjerkmeanfreqz</li>
<li>fbodygyromeanx</li>
<li>fbodygyromeany</li>
<li>fbodygyromeanz</li>
<li>fbodygyromeanfreqx</li>
<li>fbodygyromeanfreqy</li>
<li>fbodygyromeanfreqz</li>
<li>fbodyaccmagmean</li>
<li>fbodyaccmagmeanfreq</li>
<li>fbodybodyaccjerkmagmean</li>
<li>fbodybodyaccjerkmagmeanfreq</li>
<li>fbodybodygyromagmean</li>
<li>fbodybodygyromagmeanfreq</li>
<li>fbodybodygyrojerkmagmean</li>
<li>fbodybodygyrojerkmagmeanfreq</li>
<li>tbodyaccstdx</li>
<li>tbodyaccstdy</li>
<li>tbodyaccstdz</li>
<li>tgravityaccstdx</li>
<li>tgravityaccstdy</li>
<li>tgravityaccstdz</li>
<li>tbodyaccjerkstdx</li>
<li>tbodyaccjerkstdy</li>
<li>tbodyaccjerkstdz</li>
<li>tbodygyrostdx</li>
<li>tbodygyrostdy</li>
<li>tbodygyrostdz</li>
<li>tbodygyrojerkstdx</li>
<li>tbodygyrojerkstdy</li>
<li>tbodygyrojerkstdz</li>
<li>tbodyaccmagstd</li>
<li>tgravityaccmagstd</li>
<li>tbodyaccjerkmagstd</li>
<li>tbodygyromagstd</li>
<li>tbodygyrojerkmagstd</li>
<li>fbodyaccstdx</li>
<li>fbodyaccstdy</li>
<li>fbodyaccstdz</li>
<li>fbodyaccjerkstdx</li>
<li>fbodyaccjerkstdy</li>
<li>fbodyaccjerkstdz</li>
<li>fbodygyrostdx</li>
<li>fbodygyrostdy</li>
<li>fbodygyrostdz</li>
<li>fbodyaccmagstd</li>
<li>fbodybodyaccjerkmagstd</li>
<li>fbodybodygyromagstd</li>
<li>fbodybodygyrojerkmagstd</li>
</ol>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05765s from github-fe133-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-68c41efebc976764e6b82e425124ad913abbe691b87d1681debeb2554e8a0d3a.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-aa24a643b109a5e4952b79b58d176e8c92173833a074b1ff8f9eeae2557e66aa.js"></script>
      
      
  </body>
</html>

