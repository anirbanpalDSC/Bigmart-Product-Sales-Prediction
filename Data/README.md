<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="Big Mart Sales DataSet/README.md · a152a17dee24dcfcc10bb75c77c2e88cdcf90212 · Tarun Shrivas / Datasets" property="og:title">
<meta content="Built for Data Science" property="og:description">
<meta content="https://code.datasciencedojo.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="64" property="og:image:width">
<meta content="64" property="og:image:height">
<meta content="https://code.datasciencedojo.com/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="Big Mart Sales DataSet/README.md · a152a17dee24dcfcc10bb75c77c2e88cdcf90212 · Tarun Shrivas / Datasets" property="twitter:title">
<meta content="Built for Data Science" property="twitter:description">
<meta content="https://code.datasciencedojo.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>Big Mart Sales DataSet/README.md · a152a17dee24dcfcc10bb75c77c2e88cdcf90212 · Tarun Shrivas / Datasets · GitLab</title>
<meta content="Built for Data Science" name="description">
<link rel="shortcut icon" type="image/x-icon" href="/assets/favicon-075eba76312e8421991a0c1f89a89ee81678bcde72319dd3e8047e2a47cd3a42.ico" id="favicon" />
<link rel="stylesheet" media="all" href="/assets/application-c0312ee25bc85af2c7347bf0b38e3fc63ed298d5d456975b1848b79f6be1ecb7.css" />
<link rel="stylesheet" media="print" href="/assets/print-74b3d49adeaada27337e759b75a34af7cf3d80051de91d60d40570f5a382e132.css" />


<script>
//<![CDATA[
window.gon={};gon.api_version="v4";gon.default_avatar_url="https:\/\/code.datasciencedojo.com\/assets\/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=1000;gon.asset_host=null;gon.webpack_public_path="\/assets\/webpack\/";gon.relative_url_root="";gon.shortcuts_path="\/help\/shortcuts";gon.user_color_scheme="white";gon.gitlab_url="https:\/\/code.datasciencedojo.com";gon.revision="dee2c87";gon.gitlab_logo="\/assets\/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png";gon.sprite_icons="\/assets\/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg";gon.sprite_file_icons="\/assets\/file_icons-7262fc6897e02f1ceaf8de43dc33afa5e4f9a2067f4f68ef77dcc87946575e9e.svg";gon.test_env=false;gon.suggested_label_colors=["#0033CC","#428BCA","#44AD8E","#A8D695","#5CB85C","#69D100","#004E00","#34495E","#7F8C8D","#A295D6","#5843AD","#8E44AD","#FFECDB","#AD4363","#D10069","#CC0033","#FF0000","#D9534F","#D1D100","#F0AD4E","#AD8D43"];
//]]>
</script>

<script src="/assets/webpack/webpack_runtime.bf993a5b9d06faed3c70.bundle.js" defer="defer"></script>
<script src="/assets/webpack/common.db159cd75479db13c6a5.bundle.js" defer="defer"></script>
<script src="/assets/webpack/main.b9fa1bb4b84fda196c23.bundle.js" defer="defer"></script>

<script src="/assets/webpack/pages.projects.01592773ca8dd5701db7.bundle.js" defer="defer"></script>
<script src="/assets/webpack/pages.projects.blob.show.c156a41fbff24f4bce1a.bundle.js" defer="defer"></script>

<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="LS/i/0Yx6KJzAZplvSVerM0CCPmMGtarrowZyEl5r+MkqHg01B6/5FbhwcIlESvFJeyc4bJc0AijLTXqGht8Pw==" />
<meta content="origin-when-cross-origin" name="referrer">
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">



<!-- Start of HubSpot Embed Code -->
<script async="" defer="defer" id="hs-script-loader" src="//js.hs-scripts.com/3274755.js" type="text/javascript"></script>
<!-- End of HubSpot Embed Code -->
<!-- Hotjar Tracking Code for https://code.datasciencedojo.com/ -->
<script>
  (function(h,o,t,j,a,r){
    h.hj=h.hj||function(){(h.hj.q=h.hj.q||[]).push(arguments)};
    h._hjSettings={hjid:1324429,hjsv:6};
    a=o.getElementsByTagName('head')[0];
    r=o.createElement('script');r.async=1;
    r.src=t+h._hjSettings.hjid+j+h._hjSettings.hjsv;
    a.appendChild(r);
  })(window,document,'https://static.hotjar.com/c/hotjar-','.js?sv=');
</script>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-117895423-5"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  
  gtag('config', 'UA-117895423-5');
</script>
<!-- Facebook Pixel Code includes all ad accounts -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '580603255783471');
  fbq('track', 'PageView');
</script>
<noscript>
<img height="1" src="h  ttps://www.facebook.com/  tr?id=580603255783471&amp;ev=PageView&amp;noscript=1" style="display:none" width="1">
</noscript>
<!-- End Facebook Pixel Code includes all ad accounts -->
<!-- Global site tag (gtag.js) - Google Ads: 970014373 -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=AW-970014373"></script>
<script>
  window.dataLayer = window.dataLayer || []; function gtag(){dataLayer.push(arguments);} gtag('js',   new Date()); gtag('config', 'AW-970014373');
</script>
</head>

<body class="ui_indigo " data-find-file="/tshrivas/dojoHub/find_file/a152a17dee24dcfcc10bb75c77c2e88cdcf90212" data-group="" data-page="projects:blob:show" data-project="dojoHub">


<header class="navbar navbar-gitlab qa-navbar">
<a class="sr-only gl-accessibility" href="#content-body" tabindex="1">Skip to content</a>
<div class="container-fluid">
<div class="header-content">
<div class="title-container">
<h1 class="title">
<a title="Dashboard" id="logo" href="/"><img data-src="/uploads/-/system/appearance/header_logo/1/cropped-Logo_Tori.png" class=" lazy" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
</a></h1>
<ul class="list-unstyled navbar-sub-nav">
<li class="home"><a title="Projects" class="dashboard-shortcuts-projects" href="/explore">Projects
</a></li><li class=""><a title="Groups" class="dashboard-shortcuts-groups" href="/explore/groups">Groups
</a></li><li class=""><a title="Snippets" class="dashboard-shortcuts-snippets" href="/explore/snippets">Snippets
</a></li><li>
<a title="About GitLab CE" href="/help">Help</a>
</li>
</ul>

</div>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="hidden-sm hidden-xs">
<div class="has-location-badge search search-form">
<form class="navbar-form" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="location-badge">This project</div>
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search" class="search-input dropdown-menu-toggle no-outline js-search-dashboard-options" spellcheck="false" tabindex="1" autocomplete="off" data-issues-path="/dashboard/issues" data-mr-path="/dashboard/merge_requests" aria-label="Search" />
<button class="hidden js-dropdown-search-toggle" data-toggle="dropdown" type="button"></button>
<div class="dropdown-menu dropdown-select">
<div class="dropdown-content"><ul>
<li class="dropdown-menu-empty-item">
<a>
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
<svg class="s16 search-icon"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#search"></use></svg>
<svg class="s16 clear-icon js-clear-input"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" class="js-search-group-options" />
<input type="hidden" name="project_id" id="search_project_id" value="82" class="js-search-project-options" data-project-path="dojoHub" data-name="Datasets" data-issues-path="/tshrivas/dojoHub/issues" data-mr-path="/tshrivas/dojoHub/merge_requests" data-issues-disabled="false" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<input type="hidden" name="repository_ref" id="repository_ref" value="a152a17dee24dcfcc10bb75c77c2e88cdcf90212" />

<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="82" data-autocomplete-project-ref="a152a17dee24dcfcc10bb75c77c2e88cdcf90212"></div>
</form></div>

</li>
<li class="visible-sm-inline-block visible-xs-inline-block">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#search"></use></svg>
</a></li>
<li>
<div>
<a class="btn btn-sign-in" href="/users/sign_in?redirect_to_referer=yes">Sign in / Register</a>
</div>
</li>
</ul>
</div>
<button class="navbar-toggle hidden-sm hidden-md hidden-lg" type="button">
<span class="sr-only">Toggle navigation</span>
<svg class="s12 more-icon js-navbar-toggle-right"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#more"></use></svg>
<svg class="s12 close-icon js-navbar-toggle-left"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
</button>
</div>
</div>
</header>

<div class="layout-page page-with-contextual-sidebar">
<div class="nav-sidebar">
<div class="nav-sidebar-inner-scroll">
<div class="context-header">
<a title="Datasets" href="/tshrivas/dojoHub"><div class="avatar-container s40 project-avatar">
<div class="avatar s40 avatar-tile identicon" style="background-color: #FBE9E7; color: #555">D</div>
</div>
<div class="sidebar-context-title">
Datasets
</div>
</a></div>
<ul class="sidebar-top-level-items">
<li class="home"><a class="shortcuts-project" href="/tshrivas/dojoHub"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#project"></use></svg>
</div>
<span class="nav-item-name">
Overview
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub"><strong class="fly-out-top-item-name">
Overview
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Project details" class="shortcuts-project" href="/tshrivas/dojoHub"><span>Details</span>
</a></li><li class=""><a title="Activity" class="shortcuts-project-activity" href="/tshrivas/dojoHub/activity"><span>Activity</span>
</a></li><li class=""><a title="Cycle Analytics" class="shortcuts-project-cycle-analytics" href="/tshrivas/dojoHub/cycle_analytics"><span>Cycle Analytics</span>
</a></li></ul>
</li><li class="active"><a class="shortcuts-tree" href="/tshrivas/dojoHub/tree/a152a17dee24dcfcc10bb75c77c2e88cdcf90212"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#doc_text"></use></svg>
</div>
<span class="nav-item-name">
Repository
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item active"><a href="/tshrivas/dojoHub/tree/a152a17dee24dcfcc10bb75c77c2e88cdcf90212"><strong class="fly-out-top-item-name">
Repository
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class="active"><a href="/tshrivas/dojoHub/tree/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Files
</a></li><li class=""><a href="/tshrivas/dojoHub/commits/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Commits
</a></li><li class=""><a href="/tshrivas/dojoHub/branches">Branches
</a></li><li class=""><a href="/tshrivas/dojoHub/tags">Tags
</a></li><li class=""><a href="/tshrivas/dojoHub/graphs/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Contributors
</a></li><li class=""><a href="/tshrivas/dojoHub/network/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Graph
</a></li><li class=""><a href="/tshrivas/dojoHub/compare?from=master&amp;to=a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Compare
</a></li><li class=""><a href="/tshrivas/dojoHub/graphs/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/charts">Charts
</a></li></ul>
</li><li class=""><a class="shortcuts-issues" href="/tshrivas/dojoHub/issues"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#issues"></use></svg>
</div>
<span class="nav-item-name">
Issues
</span>
<span class="badge count issue_counter">
0
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/issues"><strong class="fly-out-top-item-name">
Issues
</strong>
<span class="badge count issue_counter fly-out-badge">
0
</span>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Issues" href="/tshrivas/dojoHub/issues"><span>
List
</span>
</a></li><li class=""><a title="Board" href="/tshrivas/dojoHub/boards"><span>
Board
</span>
</a></li><li class=""><a title="Labels" href="/tshrivas/dojoHub/labels"><span>
Labels
</span>
</a></li><li class=""><a title="Milestones" href="/tshrivas/dojoHub/milestones"><span>
Milestones
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-merge_requests" href="/tshrivas/dojoHub/merge_requests"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#git-merge"></use></svg>
</div>
<span class="nav-item-name">
Merge Requests
</span>
<span class="badge count merge_counter js-merge-counter">
0
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/merge_requests"><strong class="fly-out-top-item-name">
Merge Requests
</strong>
<span class="badge count merge_counter js-merge-counter fly-out-badge">
0
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-pipelines" href="/tshrivas/dojoHub/pipelines"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#pipeline"></use></svg>
</div>
<span class="nav-item-name">
CI / CD
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/pipelines"><strong class="fly-out-top-item-name">
CI / CD
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Pipelines" class="shortcuts-pipelines" href="/tshrivas/dojoHub/pipelines"><span>
Pipelines
</span>
</a></li><li class=""><a title="Jobs" class="shortcuts-builds" href="/tshrivas/dojoHub/-/jobs"><span>
Jobs
</span>
</a></li><li class=""><a title="Schedules" class="shortcuts-builds" href="/tshrivas/dojoHub/pipeline_schedules"><span>
Schedules
</span>
</a></li><li class=""><a title="Charts" class="shortcuts-pipelines-charts" href="/tshrivas/dojoHub/pipelines/charts"><span>
Charts
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-wiki" href="/tshrivas/dojoHub/wikis/home"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#book"></use></svg>
</div>
<span class="nav-item-name">
Wiki
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/wikis/home"><strong class="fly-out-top-item-name">
Wiki
</strong>
</a></li></ul>
</li><li class=""><a class="shortcuts-snippets" href="/tshrivas/dojoHub/snippets"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#snippet"></use></svg>
</div>
<span class="nav-item-name">
Snippets
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/snippets"><strong class="fly-out-top-item-name">
Snippets
</strong>
</a></li></ul>
</li><li class=""><a title="Members" class="shortcuts-tree" href="/tshrivas/dojoHub/settings/members"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#users"></use></svg>
</div>
<span class="nav-item-name">
Members
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/tshrivas/dojoHub/project_members"><strong class="fly-out-top-item-name">
Members
</strong>
</a></li></ul>
</li><a class="toggle-sidebar-button js-toggle-sidebar" role="button" title="Toggle sidebar" type="button">
<svg class=" icon-angle-double-left"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-double-left"></use></svg>
<svg class=" icon-angle-double-right"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-double-right"></use></svg>
<span class="collapse-text">Collapse sidebar</span>
</a>
<button name="button" type="button" class="close-nav-button"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
<span class="collapse-text">Close sidebar</span>
</button>
<li class="hidden">
<a title="Activity" class="shortcuts-project-activity" href="/tshrivas/dojoHub/activity"><span>
Activity
</span>
</a></li>
<li class="hidden">
<a title="Network" class="shortcuts-network" href="/tshrivas/dojoHub/network/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Graph
</a></li>
<li class="hidden">
<a title="Charts" class="shortcuts-repository-charts" href="/tshrivas/dojoHub/graphs/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/charts">Charts
</a></li>
<li class="hidden">
<a class="shortcuts-new-issue" href="/tshrivas/dojoHub/issues/new">Create a new issue
</a></li>
<li class="hidden">
<a title="Jobs" class="shortcuts-builds" href="/tshrivas/dojoHub/-/jobs">Jobs
</a></li>
<li class="hidden">
<a title="Commits" class="shortcuts-commits" href="/tshrivas/dojoHub/commits/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">Commits
</a></li>
<li class="hidden">
<a title="Issue Boards" class="shortcuts-issue-boards" href="/tshrivas/dojoHub/boards">Issue Boards</a>
</li>
</ul>
</div>
</div>

<div class="content-wrapper">

<div class="mobile-overlay"></div>
<div class="alert-wrapper">


<nav class="breadcrumbs container-fluid container-limited" role="navigation">
<div class="breadcrumbs-container">
<button name="button" type="button" class="toggle-mobile-nav"><span class="sr-only">Open sidebar</span>
<i aria-hidden="true" data-hidden="true" class="fa fa-bars"></i>
</button><div class="breadcrumbs-links js-title-container">
<ul class="list-unstyled breadcrumbs-list js-breadcrumbs-list">
<li><a href="/tshrivas">Tarun Shrivas</a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-right"></use></svg></li> <li><a href="/tshrivas/dojoHub"><span class="breadcrumb-item-text js-breadcrumb-item-text">Datasets</span></a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-right"></use></svg></li>

<li>
<h2 class="breadcrumbs-sub-title"><a href="/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md">Repository</a></h2>
</li>
</ul>
</div>

</div>
</nav>

<div class="flash-container flash-container-page">
</div>

</div>
<div class=" ">
<div class="content" id="content-body">
<div class="container-fluid container-limited">

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-container">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/tshrivas/dojoHub/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="Big Mart Sales DataSet/README.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown" type="button" data-toggle="dropdown" data-selected="a152a17dee24dcfcc10bb75c77c2e88cdcf90212" data-ref="a152a17dee24dcfcc10bb75c77c2e88cdcf90212" data-refs-url="/tshrivas/dojoHub/refs?sort=updated_desc" data-field-name="ref" data-submit-form-on-click="true" data-visit="true"><span class="dropdown-toggle-text ">a152a17dee24dcfcc10bb75c77c2e88cdcf90212</span><i aria-hidden="true" data-hidden="true" class="fa fa-chevron-down"></i></button>
<div class="dropdown-menu dropdown-menu-paging dropdown-menu-selectable git-revision-dropdown">
<div class="dropdown-page-one">
<div class="dropdown-title"><span>Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i aria-hidden="true" data-hidden="true" class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><i aria-hidden="true" data-hidden="true" class="fa fa-search dropdown-input-search"></i><i role="button" aria-hidden="true" data-hidden="true" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li>
<a href="/tshrivas/dojoHub/tree/a152a17dee24dcfcc10bb75c77c2e88cdcf90212">dojoHub
</a></li>
<li>
<a href="/tshrivas/dojoHub/tree/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet">Big Mart Sales DataSet</a>
</li>
<li>
<a href="/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md"><strong>README.md</strong>
</a></li>
</ul>
</div>
<div class="tree-controls">
<a class="btn shortcuts-find-file" rel="nofollow" href="/tshrivas/dojoHub/find_file/a152a17dee24dcfcc10bb75c77c2e88cdcf90212"><i aria-hidden="true" data-hidden="true" class="fa fa-search"></i>
<span>Find file</span>
</a>
<div class="btn-group" role="group"><a class="btn js-blob-blame-link" href="/tshrivas/dojoHub/blame/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md">Blame</a><a class="btn" href="/tshrivas/dojoHub/commits/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md">History</a><a class="btn js-data-file-blob-permalink-url" href="/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md">Permalink</a></div>
</div>
</div>

<div class="info-well hidden-xs">
<div class="well-segment">
<ul class="blob-commit-info">
<li class="commit flex-row js-toggle-container" id="commit-74a91c3e">
<div class="avatar-cell hidden-xs">
<a href="/rahimrasool"><img alt="Rahim Rasool&#39;s avatar" src="/uploads/-/system/user/avatar/19/avatar.png" data-container="body" class="avatar s36 hidden-xs has-tooltip" title="Rahim Rasool" /></a>
</div>
<div class="commit-detail flex-list">
<div class="commit-content">
<a class="commit-row-message item-title" href="/tshrivas/dojoHub/commit/74a91c3efa69dbd1bf698c2bab857d775688991c">Update README.md</a>
<span class="commit-row-message visible-xs-inline">
&middot;
74a91c3e
</span>
<div class="commiter">
<a class="commit-author-link has-tooltip" title="rahim@datasciencedojo.com" href="/rahimrasool">Rahim Rasool</a> authored <time class="js-timeago" title="Jan 10, 2019 12:08am" datetime="2019-01-10T00:08:16Z" data-toggle="tooltip" data-placement="bottom" data-container="body">Jan 10, 2019</time>
</div>
</div>
<div class="commit-actions flex-row hidden-xs">

<div class="js-commit-pipeline-status" data-endpoint="/tshrivas/dojoHub/commit/74a91c3efa69dbd1bf698c2bab857d775688991c/pipelines"></div>
<a class="commit-sha btn btn-transparent btn-link" href="/tshrivas/dojoHub/commit/74a91c3efa69dbd1bf698c2bab857d775688991c">74a91c3e</a>
<button class="btn btn-clipboard btn-transparent" data-toggle="tooltip" data-placement="bottom" data-container="body" data-title="Copy commit SHA to clipboard" data-clipboard-text="74a91c3efa69dbd1bf698c2bab857d775688991c" type="button" title="Copy commit SHA to clipboard" aria-label="Copy commit SHA to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button>

</div>
</div>
</li>

</ul>
</div>

</div>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="js-file-title file-title-flex-parent">
<div class="file-header-content">
<i aria-hidden="true" data-hidden="true" class="fa fa-file-text-o fa-fw"></i>
<strong class="file-title-name">
README.md
</strong>
<button class="btn btn-clipboard btn-transparent prepend-left-5" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn-clipboard btn-transparent prepend-left-5" data-title="Copy file path to clipboard" data-clipboard-text="{&quot;text&quot;:&quot;Big Mart Sales DataSet/README.md&quot;,&quot;gfm&quot;:&quot;`Big Mart Sales DataSet/README.md`&quot;}" type="button" title="Copy file path to clipboard" aria-label="Copy file path to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button>
<small>
3.25 KB
</small>
</div>

<div class="file-actions">
<div class="btn-group js-blob-viewer-switcher" role="group">
<button aria-label="Display source" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="simple" title="Display source">
<i aria-hidden="true" data-hidden="true" class="fa fa-code"></i>
</button><button aria-label="Display rendered file" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="rich" title="Display rendered file">
<i aria-hidden="true" data-hidden="true" class="fa fa-file-text-o"></i>
</button></div>

<div class="btn-group" role="group"><button class="btn btn btn-sm js-copy-blob-source-btn" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn btn-sm js-copy-blob-source-btn" data-title="Copy source to clipboard" data-clipboard-target=".blob-content[data-blob-id=&#39;42a3f210aeba4a5af2178005c81af2ac88a3a10e&#39;]" type="button" title="Copy source to clipboard" aria-label="Copy source to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button><a class="btn btn-sm has-tooltip" target="_blank" rel="noopener noreferrer" title="Open raw" data-container="body" href="/tshrivas/dojoHub/raw/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md"><i aria-hidden="true" data-hidden="true" class="fa fa-file-code-o"></i></a></div>
<div class="btn-group" role="group"><button name="button" type="submit" class="btn js-edit-blob  disabled has-tooltip" title="You can only edit files when you are on a branch" data-container="body">Edit</button></div>
</div>
</div>


<div class="blob-viewer hidden" data-type="simple" data-url="/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md?format=json&amp;viewer=simple">
<div class="text-center prepend-top-default append-bottom-default">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x"></i>
</div>

</div>

<div class="blob-viewer" data-rich-type="markup" data-type="rich" data-url="/tshrivas/dojoHub/blob/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md?format=json&amp;viewer=rich">
<div class="text-center prepend-top-default append-bottom-default">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x"></i>
</div>

</div>


</article>
</div>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">&times;</a>
<h3 class="page-title">Replace README.md</h3>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form form-horizontal" data-method="put" action="/tshrivas/dojoHub/update/a152a17dee24dcfcc10bb75c77c2e88cdcf90212/Big%20Mart%20Sales%20DataSet/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="CYQM5cZ/GWh/3FN/LCWydPDEetymjH9aSXNwo7WPhw8AA5YuVFBOLlo8CNi0EccdGCruxJjKeflE0lyB5u1U0w==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or <a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="dropzone-alerts alert alert-danger data" style="display:none"></div>
<div class="form-group commit_message-group">
<label class="control-label" for="commit_message-6e14249f8b3071365e32a109fcbffe47">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-6e14249f8b3071365e32a109fcbffe47" class="form-control js-commit-message" placeholder="Replace README.md" required="required" rows="3">
Replace README.md</textarea>
</div>
</div>
</div>

<input type="hidden" name="branch_name" id="branch_name" />
<input type="hidden" name="create_merge_request" id="create_merge_request" value="1" />
<input type="hidden" name="original_branch" id="original_branch" value="a152a17dee24dcfcc10bb75c77c2e88cdcf90212" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="button" class="btn btn-create btn-upload-file" id="submit-all"><i aria-hidden="true" data-hidden="true" class="fa fa-spin fa-spinner js-loading-icon hidden"></i>
Replace file
</button><a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
<div class="inline prepend-left-10">
A new branch will be created in your fork and a new merge request will be started.
</div>

</div>
</form></div>
</div>
</div>
</div>

</div>
</div>

</div>
</div>
</div>
</div>


</body>
</html>

