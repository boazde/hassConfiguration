





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-1c2c316b7a17f15536c6a26ed744654fc228a24658a7ae395cdcbf8329c8406b.css" integrity="sha256-HCwxa3oX8VU2xqJu10RlT8IookZYp645XNy/gynIQGs=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-9220ee04047cbb7ee0ee683d508378700cfaf21fbd3eea2b46ae6f847bd16e07.css" integrity="sha256-kiDuBAR8u37g7mg9UIN4cAz68h+9PuorRq5vhHvRbgc=" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>homeassistant-config/HASS Cheatsheet.md at master · arsaboo/homeassistant-config</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars1.githubusercontent.com/u/18319734?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="arsaboo/homeassistant-config" property="og:title" /><meta content="https://github.com/arsaboo/homeassistant-config" property="og:url" /><meta content="homeassistant-config - 🏡 My Home Assistant Configs. Be sure to :star2: my repo, if you like anything here!" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MjI3NzEyMTgxOjFhOGZlN2M5MDczOGMxMGFmNTFiNTBlYzdhZTYzZjg2YjM0ZDI2NWQ4MzM5MTc4MjEyYjFiNDkzMDBhY2Y0NWI=--091e592dee83ab67c1517c7ade50564ab99cc90d">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="F301:7C74:47E921:6DB7C4:5A31ADEB" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="F301:7C74:47E921:6DB7C4:5A31ADEB" name="octolytics-dimension-request_id" /><meta content="eu-central-1" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="17207198" name="octolytics-actor-id" /><meta content="boazde" name="octolytics-actor-login" /><meta content="8faeaad810231ea392648a1a7489e857153aed2c2470dfb547176752cd32b274" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="boazde">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="M2I1YTg1MTRhMWYwMmE2ODhjM2U3ZmEyMzc0Yjc4ZWIxOWM5YzMwMjQ0NWMxNDZmOTNkYmM5OGRhYzVmYWUzN3x7InJlbW90ZV9hZGRyZXNzIjoiNzcuMTI3LjEyNC4xNzQiLCJyZXF1ZXN0X2lkIjoiRjMwMTo3Qzc0OjQ3RTkyMTo2REI3QzQ6NUEzMUFERUIiLCJ0aW1lc3RhbXAiOjE1MTMyMDUyMjgsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="UNIVERSE_BANNER,FREE_TRIALS">

  <meta name="html-safe-nonce" content="cdc4cee29ec77993a25c68b3d27fe312c9651087">

  <meta http-equiv="x-pjax-version" content="f62061f64c99f74c58922598d9320372">
  

      <link href="https://github.com/arsaboo/homeassistant-config/commits/master.atom" rel="alternate" title="Recent Commits to homeassistant-config:master" type="application/atom+xml">

  <meta name="description" content="homeassistant-config - 🏡 My Home Assistant Configs. Be sure to :star2: my repo, if you like anything here!">
  <meta name="go-import" content="github.com/arsaboo/homeassistant-config git https://github.com/arsaboo/homeassistant-config.git">

  <meta content="18319734" name="octolytics-dimension-user_id" /><meta content="arsaboo" name="octolytics-dimension-user_login" /><meta content="70074515" name="octolytics-dimension-repository_id" /><meta content="arsaboo/homeassistant-config" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="70074515" name="octolytics-dimension-repository_network_root_id" /><meta content="arsaboo/homeassistant-config" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/arsaboo/homeassistant-config/blob/master/HASS%20Cheatsheet.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    
      



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/search" class="js-site-search-form" data-scoped-search-url="/arsaboo/homeassistant-config/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/arsaboo/homeassistant-config/blob/master/HASS%20Cheatsheet.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown js-menu-container">
    <span class="d-inline-block  px-2">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <details class="dropdown-details details-reset js-dropdown-details d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg aria-hidden="true" class="octicon octicon-plus float-left mr-1 mt-1" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="arsaboo/homeassistant-config">This repository</span>
  </div>
    <a class="dropdown-item" href="/arsaboo/homeassistant-config/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </details>
  </li>

  <li class="dropdown js-menu-container">

    <details class="dropdown-details details-reset js-dropdown-details d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@boazde" class="avatar float-left mr-1" src="https://avatars0.githubusercontent.com/u/17207198?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">boazde</strong>
        </li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="/boazde" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a></li>
        <li><a class="dropdown-item" href="/boazde?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a></li>
          <li><a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a></li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a></li>

        <li><a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a></li>

        <li><!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="1l0iUrGil+A9ygYXS6TZLUtMKlqCbvLkNqoMvXbO9QJengjPEfAb8WMWYzM6WL3V7TzLFK+onF+WRgM/MR022Q==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
        </form></li>
      </ul>
    </details>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="IWk68JxSjrBGkjPFUugf3J+k88EPCWot+r1Teb4ePtupqhBtPAACoRhOVuEjFHskOdQSjyLPBJZaUVz7+c39AA==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>


      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      





  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav ">
    <div class="repohead-details-container clearfix container ">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="yiWEAK+R4YNCoKUxUNYj8zN7V705wIhM/dIpmPO6blVZwoZ5LuCCZ9JbzWXs1qi/sVfYw3VzIXI/LUsbDn4jwA==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="70074515" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/arsaboo/homeassistant-config/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/arsaboo/homeassistant-config/watchers"
            aria-label="29 users are watching this repository">
            29
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/unstar" class="starred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="snqciVAlAACM2ZqSfRadvzmPs6hQN8osJgAmny5eYE9ajMXziNnGI2S8eFKA0Pqgj9IeH5wM78xjtogAqkIHfg==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar arsaboo/homeassistant-config"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/arsaboo/homeassistant-config/stargazers"
           aria-label="164 users starred this repository">
          164
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/star" class="unstarred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="HcIlP+hXRlr9rzlSt/CLb8V3HvZ+7N5Pt+mavmDsf9C9FRzHtDtM+BV2mn1VavaLdzwn3hn9HzMIFcK3O2s/dQ==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star arsaboo/homeassistant-config"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/arsaboo/homeassistant-config/stargazers"
           aria-label="164 users starred this repository">
          164
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="mG4KBcHA5I/SsIRPaidf7tsVpCKWb71mq+Ns+S0aEl4a1QjKdZKTxTLdtBbcLHgILeaXqHNbYdBeaA7OZ/lsEQ==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of arsaboo/homeassistant-config to your account"
                aria-label="Fork your own copy of arsaboo/homeassistant-config to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/arsaboo/homeassistant-config/network" class="social-count"
       aria-label="48 users forked this repository">
      48
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/arsaboo" class="url fn" rel="author">arsaboo</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/arsaboo/homeassistant-config" data-pjax="#js-repo-pjax-container">homeassistant-config</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/arsaboo/homeassistant-config" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /arsaboo/homeassistant-config" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/arsaboo/homeassistant-config/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /arsaboo/homeassistant-config/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/arsaboo/homeassistant-config/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /arsaboo/homeassistant-config/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/arsaboo/homeassistant-config/projects" class="js-selected-navigation-item reponav-item" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /arsaboo/homeassistant-config/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>
    <a href="/arsaboo/homeassistant-config/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /arsaboo/homeassistant-config/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

  <a href="/arsaboo/homeassistant-config/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /arsaboo/homeassistant-config/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/arsaboo/homeassistant-config/blob/371df43a8a9e9ead04d9b67b7d7e0d6488fea7fb/HASS%20Cheatsheet.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:137d140d8a5914a80b1f543672448457 -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/arsaboo/homeassistant-config/blob/master/HASS%20Cheatsheet.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
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

    <div class="BtnGroup float-right">
      <a href="/arsaboo/homeassistant-config/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/arsaboo/homeassistant-config"><span>homeassistant-config</span></a></span></span><span class="separator">/</span><strong class="final-path">HASS Cheatsheet.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/arsaboo/homeassistant-config/commit/38abb6007752aacdc535dc3a79c8538a8283119d" data-pjax>
          38abb60
        </a>
        <relative-time datetime="2017-10-15T22:41:25Z">Oct 15, 2017</relative-time>
      </span>
      <div>
        <img alt="@arsaboo" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/18319734?s=40&amp;v=4" width="20" />
        <a href="/arsaboo" class="user-mention" rel="author">arsaboo</a>
          <a href="/arsaboo/homeassistant-config/commit/38abb6007752aacdc535dc3a79c8538a8283119d" class="message" data-pjax="true" title="Added tip to check RPi power supply">Added tip to check RPi power supply</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@arsaboo" height="24" src="https://avatars3.githubusercontent.com/u/18319734?s=48&amp;v=4" width="24" />
            <a href="/arsaboo">arsaboo</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/arsaboo/homeassistant-config/raw/master/HASS%20Cheatsheet.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/arsaboo/homeassistant-config/blame/master/HASS%20Cheatsheet.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/arsaboo/homeassistant-config/commits/master/HASS%20Cheatsheet.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/edit/master/HASS%20Cheatsheet.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="U5CzOIXTaBBjL5vzjRXCZL19QRfklPb289yAnay4MRx4JxGYUXoDNC4swBxMRDUU1K8edRnfMSthIcOGFUWRwA==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/arsaboo/homeassistant-config/delete/master/HASS%20Cheatsheet.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="sZsjqmN0hurEDPYwFv+CIbpmrRpI/ezVXafr/0Yu1DudMTL02EOiiKp7CCfQ7rIlDY77qSDjiBW825/xIAN2Wg==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      228 lines (206 sloc)
      <span class="file-info-divider"></span>
    12.8 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a href="#if-rpi-is-not-syncing-the-time" aria-hidden="true" class="anchor" id="user-content-if-rpi-is-not-syncing-the-time"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>If RPi is not syncing the time</h1>
<p>Use the <code>systemd-timesyncd</code> service as explained <a href="https://wiki.archlinux.org/index.php/systemd-timesyncd">here</a>
Here are the <a href="https://wiki.archlinux.org/index.php/Network_Time_Protocol_daemon#Connection_to_NTP_servers">time servers</a> that I used.</p>
<pre><code>NTP=0.north-america.pool.ntp.org 1.north-america.pool.ntp.org 2.north-america.pool.ntp.org 3.north-america.pool.ntp.org
FallbackNTP=0.arch.pool.ntp.org 1.arch.pool.ntp.org 2.arch.pool.ntp.org 3.arch.pool.ntp.org
</code></pre>
<h1><a href="#configuring-winscp-to-edit-hass-files" aria-hidden="true" class="anchor" id="user-content-configuring-winscp-to-edit-hass-files"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configuring WinSCP to edit HASS files</h1>
<p>Default AIO installation does not allow editing the configuration files in WinSCP. To enable the same, you will need to change the SFTP server (in Advanced settings -&gt; Environment -&gt; SFTP).</p>
<ol>
<li>Obtain the SFTP by running <code>grep sftp /etc/ssh/sshd_config</code> at the <code>pi</code> shell. You will get something like, <code>Subsystem sftp /usr/lib/openssh/sftp-server</code>.</li>
<li>Now, set the sftp server to: <code>sudo su -c /usr/lib/openssh/sftp-server</code> (note that the <code>/usr/lib/openssh/sftp-server</code> is the same path obtained from the previous step) and set Shell to <code>sudo -s</code>.</li>
</ol>
<h1><a href="#install-homebridge-on-a-pi" aria-hidden="true" class="anchor" id="user-content-install-homebridge-on-a-pi"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install Homebridge on a Pi</h1>
<p>You can install Homebridge on a Pi using the following commands:</p>
<ol>
<li>Make sure your Pi is updated.</li>
<li>Install all the dependencies</li>
</ol>
<pre><code>sudo apt-get install git make
curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo apt-get install libavahi-compat-libdnssd-dev
</code></pre>
<ol start="3">
<li>Install both Homebridge and Homebridge-Homeassistant plugin using:</li>
</ol>
<pre><code>sudo npm install -g --unsafe-perm homebridge
sudo npm install -g homebridge-homeassistant
</code></pre>
<ol start="4">
<li>You need to modify the config.json (located at <code>/home/pi/.homebridge/config.json</code>). Here's what I'm using (Homebridge on Pi connects to my HA on a NUC):</li>
</ol>
<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>bridge<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Homebridge<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>username<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>CC:22:3D:E3:CE:34<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>port<span class="pl-pds">"</span></span>: <span class="pl-c1">51826</span>,
    <span class="pl-s"><span class="pl-pds">"</span>pin<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>031-45-155<span class="pl-pds">"</span></span>
  },

  <span class="pl-s"><span class="pl-pds">"</span>description<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>This is the main Homebridge configuration file for Home Assistant. This will bridge Home Assistant and HomeKit together!<span class="pl-pds">"</span></span>,

  <span class="pl-s"><span class="pl-pds">"</span>accessories<span class="pl-pds">"</span></span>: [
  ],
  <span class="pl-s"><span class="pl-pds">"</span>platforms<span class="pl-pds">"</span></span>: [
    {
      <span class="pl-s"><span class="pl-pds">"</span>platform<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>HomeAssistant<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>HomeAssistant<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>host<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://192.168.X.Y:8123<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>password<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>supported_types<span class="pl-pds">"</span></span>: [<span class="pl-s"><span class="pl-pds">"</span>group<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>binary_sensor<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>climate<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>cover<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>device_tracker<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>fan<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>input_boolean<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>light<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>lock<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>media_player<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>scene<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>sensor<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>switch<span class="pl-pds">"</span></span>],
      <span class="pl-s"><span class="pl-pds">"</span>logging<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
      <span class="pl-s"><span class="pl-pds">"</span>verify_ssl<span class="pl-pds">"</span></span>: <span class="pl-c1">false</span>
    }
  ]
}
</pre></div>
<ol start="5">
<li>Follow the instructions <a href="https://timleland.com/setup-homebridge-to-start-on-bootup/">here</a> to boot Homebridge on startup.</li>
<li>If you get an error "Couldn't add Homebridge" on your iOS Home App, please make sure that there are only less than 100 Homebridge entities enabled.</li>
<li>For remote access to Homebridge devices, you will need to enable 2FA on your iOS devices. If you are not able to <a href="https://github.com/nfarina/homebridge/issues/1212">remotely access</a> your Homebridge
devices, you may have to sign out, restart, and sign back in to your Apple TV.</li>
</ol>
<h1><a href="#mosquitto-operations" aria-hidden="true" class="anchor" id="user-content-mosquitto-operations"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Mosquitto operations</h1>
<p>I am using the default AIO username/password, replace them with yours</p>
<ol>
<li>You can remove a topic from Mosquitto using <code>mosquitto_pub -r -n -u 'pi' -P 'raspberry' -t 'owntracks/arsaboo/mqttrpi'</code></li>
<li>To subscribe to all the topics use <code>mosquitto_sub -h 192.168.2.212 -u 'pi' -P 'raspberry' -v -t '#'</code> (replace the IP address)</li>
<li>To publish use <code>mosquitto_pub -u 'pi' -P 'raspberry' -t 'smartthings/Driveway/switch' -m 'on'</code> (use the relevant topic).</li>
<li>You can find the path to mosquitto_pub using <code>which mosquitto_pub</code>; restart Mosquitto using <code>sudo systemctl restart mosquitto</code>.</li>
</ol>
<h1><a href="#hass-operations" aria-hidden="true" class="anchor" id="user-content-hass-operations"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>HASS operations</h1>
<ol>
<li>To check realtime logs <code>sudo journalctl -f -u home-assistant@homeassistant</code></li>
<li>To restart HA <code>sudo systemctl restart home-assistant@homeassistant</code></li>
<li>To check logs <code>sudo systemctl status -l home-assistant@homeassistant</code></li>
<li>To stop HA <code>sudo systemctl stop home-assistant@homeassistant</code></li>
<li>To start HA <code>sudo systemctl start home-assistant@homeassistant</code></li>
</ol>
<h1><a href="#backing-up-configurations-on-github" aria-hidden="true" class="anchor" id="user-content-backing-up-configurations-on-github"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Backing up Configurations on Github</h1>
<p>Thanks to @dale3h for assistance with these instructions.</p>
<ol>
<li>
<p>Install <code>git</code> using <code>sudo apt-get install git</code></p>
</li>
<li>
<p>Go to <a href="https://github.com/new">https://github.com/new</a> and create a new repository. I named mine <code>homeassistant-config</code>. Initialize with <code>readme: no</code> and <code>.gitignore: none</code>.</p>
</li>
<li>
<p>Navigate to your <code>.homeassistant</code> directory. For AIO, it should be <code>/home/hass/.homeassistant</code>, and for HASSbian, it is <code>/home/homeassistant/.homeassistant</code>.</p>
</li>
<li>
<p>Run <code>sudo su -s /bin/bash hass</code> for AIO and <code>sudo su -s /bin/bash homeassistant</code> for HASSbian.</p>
</li>
<li>
<p>Run <code>wget https://raw.githubusercontent.com/arsaboo/homeassistant-config/master/.gitignore</code> to get the <code>.gitignore</code> file from your repo (replace the link to match your repository). You can add things to your <code>.gitignore</code> file that you do not want to be uploaded.</p>
</li>
<li>
<p>Next, we need to add SSH keys to your Github account.</p>
<ul>
<li>Navigate to <code>cd /home/hass/.ssh</code> (for AIO). If you don't have <code>.ssh</code> directory, create one and change the permission <code>chmod 700 ~/.ssh</code>.</li>
<li>Run <code>ssh-keygen -t rsa -b 4096 -C "homeassistant@pi"</code>. If you want to enter a passphrase, that's up to you. If you do, you'll have to enter that passphrase any time you want to update your changes to github. If you do not want a passphrase, leave it blank and just hit <code>Enter</code>.</li>
<li>Save the key in the default location (press <code>Enter</code> when it prompts for location).</li>
<li>When you're finished, run <code>ls -al ~/.ssh</code> to confirm that you have both <code>id_rsa</code> and <code>id_rsa.pub</code> files.</li>
<li>Go to <a href="https://github.com/settings/keys">https://github.com/settings/keys</a> and click <code>New SSH key</code> button at top right. Title: <code>homeassistant@pi</code> (or whatever you want, really...it's just for you to know which key it is)</li>
<li>Run <code>cat id_rsa.pub</code> in the SSH session and copy/paste the output to that github page.</li>
<li>Then click <code>Add SSH key</code> button.</li>
</ul>
</li>
<li>
<p>Go back to your repo page on GitHub. It'll be something like <a href="https://github.com/yourusernamehere/homeassistant-config">https://github.com/yourusernamehere/homeassistant-config</a>. Click the green <code>Clone or download</code> button, and then click <code>Use SSH</code>.</p>
</li>
<li>
<p>You should see something like this in the textbox: <code>git@github.com:yourusername/homeassistant-config.git</code>. Copy that to your clipboard.</p>
</li>
<li>
<p>Now you are ready to upload the files to GitHub.</p>
<ul>
<li>Navigate to <code>cd ~/.homeassistant</code></li>
<li><code>git init</code></li>
<li><code>git add .</code></li>
<li><code>git commit -m 'initial commit'</code></li>
<li>If you get an error about <code>*** Please tell me who you are.</code>, run <code>git config --global user.email "your@email.here"</code> and <code>git config --global user.name "Your Name"</code></li>
<li>After that commit succeeds, run: <code>git remote add origin git@github.com:yourusername/homeassistant-config.git</code> (make sure you enter the correct repo URL here)</li>
<li>Just to confirm everything is right, run <code>git remote -v</code> and you should see:
<pre><code>hass@raspberrypi:~/.homeassistant$ git remote -v
origin  git@github.com:arsaboo/homeassistant-config.git (fetch)
origin  git@github.com:arsaboo/homeassistant-config.git (push)
</code></pre>
</li>
<li>Finally, run <code>git push origin master</code>.</li>
</ul>
</li>
<li>
<p>For subsequent updates:</p>
<ul>
<li><code>cd /home/homeassistant/.homeassistant</code></li>
<li><code>sudo su -s /bin/bash homeassistant</code></li>
<li><code>git add .</code></li>
<li><code>git commit -m 'your commit message'</code></li>
<li><code>git push origin master</code></li>
</ul>
</li>
<li>
<p>To restore from your Github repository (replace the URL):</p>
<div class="highlight highlight-source-shell"><pre>sudo su -s /bin/bash homeassistant
<span class="pl-c1">cd</span> /home/homeassistant
git clone git@github.com:arsaboo/homeassistant-config.git .homeassistant</pre></div>
</li>
</ol>
<h1><a href="#integrating-hass-aio-with-smartthings-using-mosquitto" aria-hidden="true" class="anchor" id="user-content-integrating-hass-aio-with-smartthings-using-mosquitto"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Integrating HASS (AIO) with Smartthings using Mosquitto</h1>
<p>If you are using AIO (which has Mosquitto pre-installed), you can use the following to integrate SmartThings and HA.</p>
<ol>
<li>Install node.js, and pm2
<div class="highlight highlight-source-shell"><pre>sudo apt-get update <span class="pl-k">&amp;&amp;</span> sudo apt-get upgrade -y
curl -sL https://deb.nodesource.com/setup_4.x <span class="pl-k">|</span> sudo -E bash -
sudo apt-get install -y nodejs
sudo npm install -g pm2
sudo su -c <span class="pl-s"><span class="pl-pds">"</span>env PATH=<span class="pl-smi">$PATH</span>:/usr/local/bin pm2 startup systemd -u pi --hp /user/pi<span class="pl-pds">"</span></span></pre></div>
</li>
<li>Install the <a href="https://github.com/stjohnjohnson/smartthings-mqtt-bridge">SmartThings MQTT Bridge</a>
<div class="highlight highlight-source-shell"><pre>$ sudo npm install -g smartthings-mqtt-bridge</pre></div>
</li>
<li>Add details of your Mosquitto to <code>config.yml</code>. For the default AIO username password, your file should look something like:
<pre><code>mqtt:
    # Specify your MQTT Broker's hostname or IP address here
    host: mqtt://192.168.2.199
    # Preface for the topics $PREFACE/$DEVICE_NAME/$PROPERTY
    preface: smartthings

    # Suffix for the state topics $PREFACE/$DEVICE_NAME/$PROPERTY/$STATE_SUFFIX
    # state_suffix: state
    # Suffix for the command topics $PREFACE/$DEVICE_NAME/$PROPERTY/$COMMAND_SUFFIX
    # command_suffix: cmd

    # Other optional settings from https://www.npmjs.com/package/mqtt#mqttclientstreambuilder-options
    username: pi
    password: raspberry

# Port number to listen on
port: 8080
</code></pre>
</li>
<li>Start ST-MQTT bridge <code>pm2 start smartthings-mqtt-bridge</code></li>
<li>Follow the rest of the instructions (from step 2) listed <a href="https://github.com/stjohnjohnson/smartthings-mqtt-bridge#usage">here</a>.</li>
<li>Once <code>pm2</code> runs the program, you can then run <code>pm2 save</code> to save the running programs into a configuration file.</li>
<li>You can then run <code>pm2</code> as a systemd or service by running the command that you get after running <code>pm2 startup systemd</code> (run this without <code>sudo</code>).</li>
</ol>
<h1><a href="#to-upgrade-hass-manually" aria-hidden="true" class="anchor" id="user-content-to-upgrade-hass-manually"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>To upgrade HASS manually:</h1>
<ul>
<li>Login to system. HASS configuration files are saved in <code>/home/homeassistant/.homeassistant</code> and the code files are saved in <code>/srv/homeassistant/lib/python3.5/site-packages/homeassistant/</code>.</li>
<li>Change to homeassistant user <code>sudo su -s /bin/bash homeassistant</code></li>
<li>Change to virtual enviroment <code>source /srv/homeassistant/bin/activate</code></li>
<li>Update HA <code>pip3 install --upgrade homeassistant</code>. To update to a different branch, use the complete git URL, <code>pip3 install --upgrade git+git://github.com/home-assistant/home-assistant.git@dev</code></li>
<li>Type <code>exit</code> to logout the hass user and return to the <code>pi</code> user.</li>
<li>Restart the Home-Assistant Service <code>sudo systemctl restart home-assistant@homeassistant</code></li>
</ul>
<h1><a href="#setting-up-mysql" aria-hidden="true" class="anchor" id="user-content-setting-up-mysql"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Setting up MySQL</h1>
<p>Follow the instructions <a href="https://community.home-assistant.io/t/large-homeassistant-database-files/4201/124">here</a> to set-up MySQL.</p>
<div class="highlight highlight-source-shell"><pre>sudo apt-get update <span class="pl-k">&amp;&amp;</span> sudo apt-get upgrade -y
sudo apt-get install mysql-server <span class="pl-k">&amp;&amp;</span> sudo apt-get install mysql-client
sudo apt-get install libmysqlclient-dev
sudo apt-get install python-dev python3-dev
sudo pip3 install --upgrade mysql-connector
sudo pip3 install mysqlclient</pre></div>
<p>Create homeassistant database and grant privileges:</p>
<div class="highlight highlight-source-shell"><pre>mysql -u root -p
CREATE DATABASE homeassistant<span class="pl-k">;</span>
CREATE USER <span class="pl-s"><span class="pl-pds">'</span>hass<span class="pl-pds">'</span></span>@<span class="pl-s"><span class="pl-pds">'</span>localhost<span class="pl-pds">'</span></span> IDENTIFIED BY <span class="pl-s"><span class="pl-pds">'</span>PASSWORD<span class="pl-pds">'</span></span><span class="pl-k">;</span>
GRANT ALL PRIVILEGES ON homeassistant.<span class="pl-k">*</span> TO <span class="pl-s"><span class="pl-pds">'</span>hass<span class="pl-pds">'</span></span>@<span class="pl-s"><span class="pl-pds">'</span>localhost<span class="pl-pds">'</span></span><span class="pl-k">;</span>
FLUSH PRIVILEGES<span class="pl-k">;</span>
<span class="pl-c1">exit</span><span class="pl-k">;</span></pre></div>
<p>Test if user works:</p>
<div class="highlight highlight-source-shell"><pre>mysql -u hass homeassistant -p
<span class="pl-c1">exit</span><span class="pl-k">;</span></pre></div>
<p>Switch to homeassistant user:</p>
<div class="highlight highlight-source-shell"><pre>sudo su -s /bin/bash homeassistant
<span class="pl-c1">source</span> /srv/homeassistant/bin/activate
pip3 install --upgrade mysqlclient
<span class="pl-c1">exit</span></pre></div>
<p>Add to configuration.yaml and restart HA.</p>
<pre><code>recorder:
  db_url: mysql://hass:********@127.0.0.1/homeassistant?charset=utf8
</code></pre>
<p>Some useful commands:</p>
<ul>
<li>Use <code>mysqlshow -h localhost -u hass -p homeassistant</code> to show the tables that are created.</li>
<li>To delete all tables and start from scratch, run <code>DROP DATABASE homeassistant;</code> and recreate homeassistant database and grant privileges.</li>
<li>Use <code>sudo apt-get remove --purge mysql\*</code> to delete anything related to packages named mysql.</li>
<li><code>show tables</code> to list all the tables.</li>
<li><code>desc states</code> to describe table <code>states</code>.</li>
<li><code>(SELECT event_id, time_fired FROM events ORDER BY event_id ASC LIMIT 1) UNION ALL (SELECT event_id, time_fired FROM events ORDER BY event_id DESC LIMIT 1);</code> to list the first and last record of <code>events</code> table.</li>
<li><code>SELECT table_schema homeassistant, sum( data_length + index_length ) / (1024 * 1024) "Data Base Size in MB" FROM information_schema.TABLES GROUP BY table_schema;</code> to list disk space used by each database.</li>
<li><code>select entity_id, count(*), sum(length(state)), sum(length(attributes))/ (1024 * 1024) siz from states group by entity_id order by siz;</code> to obtain the space (in MB) occupied by each entity in the <code>states</code> table.</li>
</ul>
<h1><a href="#miscellaneous-tipstricks" aria-hidden="true" class="anchor" id="user-content-miscellaneous-tipstricks"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Miscellaneous Tips/Tricks</h1>
<ul>
<li>You can test the Read Speed of your SD card using (note, this command takes some time to run):
<pre><code>sudo dd if=/dev/mmcblk0 of=/dev/null bs=8M count=100
sudo hdparm -t /dev/mmcblk0
</code></pre>
</li>
<li>Many of the problems with Pi are related to faulty power supply. You can use <code>vcgencmd get_throttled</code> to check if your Pi is getting adequate power supply. You want that to return <code>throttled=0x0</code>. If not it means that the Raspberry is throttling itself due to low voltage, or other factors.</li>
<li>Test Write speed (will create 200MB file in /home/pi/testfile) using <code>dd if=/dev/zero of=/home/pi/testfile bs=8M count=25</code></li>
<li>To check which files are using up all the space on your SD card, run <code>sudo du | sort -n</code>. You can delete the culprits using something like <code>sudo rm -rf ./.pm2/logs/</code> (will recursively delete folder /logs/).</li>
</ul>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.21133s from unicorn-2654731567-bwlkm">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha256-9Odkuq+Ld+wqBlNI9XovMdB/d+LerbeJSCGkOGEIwbs=" src="https://assets-cdn.github.com/assets/frameworks-f4e764baaf8b77ec2a065348f57a2f31d07f77e2deadb7894821a4386108c1bb.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha256-49+p8464StffvccWkFFzCqcnfsNlFdVPaRXKk1m//Dc=" src="https://assets-cdn.github.com/assets/github-e3dfa9f38eb84ad7dfbdc7169051730aa7277ec36515d54f6915ca9359bffc37.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

