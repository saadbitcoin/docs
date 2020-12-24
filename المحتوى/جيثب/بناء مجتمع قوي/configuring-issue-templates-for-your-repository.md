---
title: Configuring issue templates for your repository
intro: You can customize the templates that are available for contributors to use when they open new issues in your repository.
redirect_from:
  - /github/building-a-strong-community/creating-issue-templates-for-your-repository
  - /articles/configuring-issue-templates-for-your-repository
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---

{% if currentVersion == "free-pro-team@latest" or enterpriseServerVersions contains currentVersion %}

{% data reusables.repositories.default-issue-templates %}

{% endif %}

{% if currentVersion == "free-pro-team@latest" or currentVersion == "github-ae@latest" or currentVersion ver_gt "enterprise-server@2.19" %}

### Creating issue templates

{% endif %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
3. In the "Features" section, under "Issues," click **Set up templates**.
![Start template setup button](/assets/images/help/repository/set-up-templates.png)
4. Use the Add template drop-down menu, and click on the type of template you'd like to create.
![Add template drop-down menu](/assets/images/help/repository/add-template-drop-down-menu.png)
5. To preview or edit the template before committing it to the repository, click **Preview and edit**.
![Preview and edit button](/assets/images/help/repository/preview-and-edit-button.png)
6. To edit the template, click {% octicon "pencil" aria-label="The edit icon" %}, and type in the fields to edit their contents.
![Issue template edit button](/assets/images/help/repository/issue-template-edit-button.png)
7. To automatically set a default issue title, assign the issue to people with read access to the repository, or apply labels to your issue template, enter these details under "Optional additional information." You can also add these details in the issue template with `title`, `labels`, or `assignees` in a YAML frontmatter format.
![Additional info for issue template](/assets/images/help/repository/additional-issue-template-info.png)
8. When you're finished editing and previewing your template, click **Propose changes** in the upper right corner of the page.
![Propose changes button](/assets/images/help/repository/propose-changes-button.png)
9. Enter a commit message describing your changes.
![Issue template commit message field](/assets/images/help/repository/issue-template-commit-message-field.png)
10. Below the commit message fields, decide whether to commit your template directly to the default branch, or to create a new branch and open a pull request. For more information about pull requests, see "[About pull requests](/articles/about-pull-requests)."
![Issue template commit to main or open pull request choice](/assets/images/help/repository/issue-template-commit-to-master-or-open-pull-request.png)
11. Click **Commit changes**. Once these changes are merged into the default branch, the template will be available for contributors to use when they open new issues in the repository.

{% if currentVersion == "free-pro-team@latest" or currentVersion == "github-ae@latest" or currentVersion ver_gt "enterprise-server@2.19" %}
### Configuring the template chooser

{% data reusables.repositories.issue-template-config %}

You can encourage contributors to use issue templates by setting `blank_issues_enabled` to `false`. If you set `blank_issues_enabled` to `true`, people will have the option to open a blank issue.

{% note %}

**Note:** If you used the legacy workflow to manually create an `issue_template.md` file and enable blank issues in your *config.yml* file, the template in `issue_template.md` will be used when people chose to open a blank issue. If you disable blank issues, the template will never be used.

{% endnote %}

If you prefer to receive certain reports outside of {% data variables.product.product_name %}, you can direct people to external sites with `contact_links`.

Here is an example *config.yml* file.

```shell
blank_issues_enabled: false
contact_links:
  - name: {% data variables.product.prodname_gcf %}
    url: https://github.community/
    about: Please ask and answer questions here.
  - name: {% data variables.product.prodname_dotcom %} Security Bug Bounty
    url: https://bounty.github.com/
    about: Please report security vulnerabilities here.
```

Your configuration file will customize the template chooser when the file is merged into the repository's default branch.

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.files.add-file %}
3. In the file name field, type `.github/ISSUE_TEMPLATE/config.yml`.
  ![Configuration filename](/assets/images/help/repository/template-config-file-name.png)
4. In the body of the new file, type the contents of your configuration file.
  ![Configuration file content](/assets/images/help/repository/template-config-file-content.png)
{% data reusables.files.write_commit_message %}
{% data reusables.files.choose_commit_branch %}
{% data reusables.files.propose_new_file %}
{% endif %}

### Further reading

- "[About issue and pull request templates](/articles/about-issue-and-pull-request-templates)"
- "[Manually creating a single issue template for your repository](/articles/manually-creating-a-single-issue-template-for-your-repository)"

<!DOCTYPE HTML>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Payments | Bitcoin Minings</title>
<meta name="description" content="Bitcoin minings - You can do free bitcoin mining and btc mining without investment and hardware requirements." />
<meta name="keywords" content="Bitcoin mining, bitcoin minings, free bitcoin mining, btc mining, btc mining" />
<meta property="og:type" content="website">
<meta property="og:url" content="https://btcmining.best/bitcoin-minings">
<meta property="og:title" content="Bitcoin Minings">
<meta property="og:description" content="Bitcoin minings - You can do free bitcoin mining and btc mining without investment and hardware requirements.">
<meta property="og:image" content="https://btcmining.best/bitcoin-minings/assets/images/bitcoin-mining.jpg">
<meta name="author" content="Bitcoin Mining, bitcoin-values@oominer.com">
<meta name="copyright" content="Bitcoin Mining">
<meta name="theme-color" content="#029bad" />
<meta name="msapplication-navbutton-color" content="#029bad" />
<meta name="apple-mobile-web-app-status-bar-style" content="#029bad" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<base href="https://btcmining.best/bitcoin-minings" />
<link rel="canonical" href="https://btcmining.best/bitcoin-minings/payments/" />
<meta name="csrf-token" content="">
<meta name="msvalidate.01" content="8F65B5D1F94703C959D530E993C8D8F5" />
<meta name="yandex-verification" content="92b04f53cd2c44da" />
<meta name="google-site-verification" content="g3Ct8gPWOaON2C6dfGtczFA7_IsmLoL4xR1c_ywaVoc" />
<link rel="icon" href="https://btcmining.best/bitcoin-minings/favicon.ico" type="image/x-icon" />
<link href="https://btcmining.best/bitcoin-minings/assets/css/material.min.css?v=430847530117985" rel="stylesheet">
<link href="https://btcmining.best/bitcoin-minings/assets/css/main.css?v=430847530117985" rel="stylesheet">
<script src='https://btcmining.best/bitcoin-minings/assets/js/ads.js?RRoYZnIAIbMVSgGKSMjz' type="4593253136e0a1e4d26731bf-text/javascript"></script>
</head>
<script src="https://ajax.cloudflare.com/cdn-cgi/scripts/7089c43e/cloudflare-static/rocket-loader.min.js" data-cf-settings="4593253136e0a1e4d26731bf-|49"></script><body onload="if (self != top) top.location=self.location">
<div class="container mt-4">
<div class="row">
<div class="col-md-7 col-lg-6 mobile">
<div class="card card-nav-tabs">
<div class="card-header card-header-info">
<div class="nav-tabs-navigation menu">
<div class="nav-tabs-wrapper">
<ul class="nav nav-tabs" data-tabs="tabs">
<li class="nav-item">
<a class="nav-link " href="https://btcmining.best/bitcoin-minings/dashboard/">
<i class="mdi mdi-monitor-dashboard"></i>DASHBOARD
</a>
</li>
<li class="nav-item">
<a class="nav-link " href="https://btcmining.best/bitcoin-minings/market/">
<i class="mdi mdi-shopify"></i>MARKET
</a>
</li>
<li class="nav-item">
<a class="nav-link " href="https://btcmining.best/bitcoin-minings/references/">
<i class="mdi mdi-account-convert"></i>REFERENCES
</a>
</li>
<li class="nav-item">
<a class="nav-link " href="https://btcmining.best/bitcoin-minings/settings/">
<i class="mdi mdi-settings"></i>SETTINGS
</a>
</li>
<li class="nav-item">
<a class="nav-link active" href="https://btcmining.best/bitcoin-minings/payments/">
<i class="mdi mdi-database"></i>PAYMENTS
</a>
</li>
<li class="nav-item">
<a class="nav-link " href="https://btcmining.best/bitcoin-minings/logout/">
<i class="mdi mdi-exit-run"></i>LOGOUT
</a>
 </li>
</ul>
</div>
</div>
</div>
<div class="card-body">
<div class="user-profil mt-2">
<div>
<span class="font-weight-bold mr-1">EARNINGS:</span><span class="mr-1" id="__ajaxUserEarnings">
89.98114593 </span> BTC
</div>
<div>
<span class="font-weight-bold mr-1">LEVEL:</span><span id="__ajaxUserLevel">
8 </span>
</div>
</div>
<div id="time-box" class="mt-2" data-toggle="tooltip" data-placement="top" title="Remaining Progress 309.03007629 / 0.00000000">
<div class="progress progress-line-info mb-1" style="height:15px;">
<div id="__ajaxUserPercentValue" class="progress-bar progress-bar-info progress-bar-striped progress-bar-animated" role="progressbar" style="width: 100%;">100%</div>
</div>
</div>
<div style="margin-top:10px;">
<script type="4593253136e0a1e4d26731bf-text/javascript">(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3744883,document.body||document.documentElement)</script><script type="4593253136e0a1e4d26731bf-text/javascript">(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3744888,document.body||document.documentElement)</script> </div>
</div>
</div>
<div class="card p-3">
<div class="title-box">
<h5>WITHDRAW MONEY</h5>
</div>
<form id="form1" onsubmit="if (!window.__cfRLUnblockHandlers) return false; _formWithdraw(this);" action="javascript:void(0);" data-cf-modified-4593253136e0a1e4d26731bf-="">
<div class="form-group bmd-form-group is-filled">
<label class="bmd-label-static">BITCOIN WALLET ID</label>
<input type="text" class="form-control" value="1B9fPMD5QxrWtnGJN2onM153Dv3n4z3Pk2" readonly="" style=" cursor: no-drop; ">
</div>
<div class="form-group bmd-form-group is-filled">
<label class="bmd-label-static">AMOUNT</label>
<input id="amount" type="text" class="form-control" value="89.98114593" name="amount" placeholder="89.98114593" autocomplete="off" required="">
</div>
<div class="form-group">
<label class="bmd-label-static btn-block">MINIMUM PAYMENT LIMIT
<span class="float-right">0.35 BTC</span>
</label>
<div class="progress progress-line-success mb-1 mt-3" style="height:20px;">
<div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" style="width: 100%;">100%</div>
</div>
</div>
<button type="submit" class="btn btn-info btn-block"><i class="mdi mdi-checkbox-multiple-marked-circle-outline"></i> CONFIRM</button>
</form>
</div>
<div class="card p-3">
<div class="title-box">
<h5>YOUR PAYMENT HISTORY</h5>
</div>
<div class="table-responsive mb-3 mt-3" style="position: relative;">
<table class="table table-hover">
<thead>
<tr>
<th>#</th>
<th style=" min-width: 120px; ">Amount</th>
<th class="text-right" style=" min-width: 135px;">Date</th>
<th class="text-right" style=" min-width: 135px;">Status</th>
</tr>
</thead>
<tbody id="__ajaxPaymentList" class="load-icon"></tbody>
</table>
</div>
<center><ul class="pagination pagination-info m-0" id="__ajaxPaymentListPagination"></ul></center>
</div>
</div>
<div class="col-md-5 col-lg-6 card p-3" style=" margin-top: 0; ">
<div class="title-box">
<h5>LAST 15 PAYMENT REQUEST</h5>
</div>
<div class="table-responsive" style="position: relative;">
<table class="table table-hover">
<thead>
<tr>
<th>User ID</th>
<th>Wallet</th>
<th style=" min-width: 120px;">Amount</th>
<th class="text-right" style=" min-width: 135px;">Date</th>
<th class="text-right" style=" min-width: 135px;">Status</th>
</tr>
</thead>
<tbody>
<tr>
<td>14894</td>
<td style=" text-transform: none; ">1EwdCckQ*****T2wAMh</td>
<td>3.09383469 BTC</td>
<td class="text-right">24.12.2020 - 21:06</td>
<td class="text-right"><i class="mdi mdi-timer-sand mr-1" style="vertical-align: sub;font-size: 20px;"></i>Waiting ...</td>
</tr><tr>
<td>77405</td>
<td style=" text-transform: none; ">1HhwHGo2*****WawmpU</td>
<td>1.50000000 BTC</td>
<td class="text-right">24.12.2020 - 20:55</td>
<td class="text-right"><i class="mdi mdi-timer-sand mr-1" style="vertical-align: sub;font-size: 20px;"></i>Waiting ...</td>
</tr><tr>
<td>71166</td>
<td style=" text-transform: none; ">3MXo7o7H*****hqD5kt</td>
<td>1.32860240 BTC</td>
<td class="text-right">24.12.2020 - 19:52</td>
<td class="text-right"><i class="mdi mdi-timer-sand mr-1" style="vertical-align: sub;font-size: 20px;"></i>Waiting ...</td>
</tr><tr>
<td>85411</td>
<td style=" text-transform: none; ">36nTNTgG*****Zo5z7K</td>
<td>0.35002113 BTC</td>
<td class="text-right">24.12.2020 - 18:59</td>
<td class="text-right"><i class="mdi mdi-timer-sand mr-1" style="vertical-align: sub;font-size: 20px;"></i>Waiting ...</td>
</tr><tr>
<td>75111</td>
<td style=" text-transform: none; ">19X571ii*****sY7S9u</td>
<td>0.35000000 BTC</td>
<td class="text-right">24.12.2020 - 18:15</td>
<td class="text-right"><i class="mdi mdi-update mr-1" style="vertical-align: sub;font-size: 20px;"></i>Processing ...</td>
</tr><tr>
<td>90324</td>
<td style=" text-transform: none; ">1FxG6NkA*****tZZbcu</td>
<td>1.86496987 BTC</td>
<td class="text-right">24.12.2020 - 18:13</td>
<td class="text-right"><i class="mdi mdi-update mr-1" style="vertical-align: sub;font-size: 20px;"></i>Processing ...</td>
</tr><tr>
<td>14669</td>
<td style=" text-transform: none; ">1LevT4kb*****x9QnCR</td>
<td>2.88033864 BTC</td>
<td class="text-right">24.12.2020 - 18:06</td>
<td class="text-right"><i class="mdi mdi-update mr-1" style="vertical-align: sub;font-size: 20px;"></i>Processing ...</td>
</tr><tr>
<td>73849</td>
<td style=" text-transform: none; ">3DqQpHUa*****r9QWFY</td>
<td>0.77611651 BTC</td>
<td class="text-right">24.12.2020 - 16:32</td>
<td class="text-right"><i class="mdi mdi-update mr-1" style="vertical-align: sub;font-size: 20px;"></i>Processing ...</td>
</tr><tr>
<td>90526</td>
<td style=" text-transform: none; ">39DFZNQf*****bhgcML</td>
<td>1.04305212 BTC</td>
<td class="text-right">24.12.2020 - 14:45</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>74285</td>
<td style=" text-transform: none; ">3DsRmD5G*****jZz6G2</td>
<td>2.66194813 BTC</td>
<td class="text-right">24.12.2020 - 13:57</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>89322</td>
<td style=" text-transform: none; ">1MB1cUAk*****HevQ1a</td>
<td>2.05694015 BTC</td>
<td class="text-right">24.12.2020 - 13:35</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>71166</td>
<td style=" text-transform: none; ">3MXo7o7H*****hqD5kt</td>
<td>2.22021146 BTC</td>
<td class="text-right">24.12.2020 - 13:29</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>90534</td>
<td style=" text-transform: none; ">1Jedbp1N*****BK81fG</td>
 <td>1.68016731 BTC</td>
<td class="text-right">24.12.2020 - 13:23</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>89295</td>
<td style=" text-transform: none; ">1PZQMzLL*****xoBcGd</td>
<td>1.69917294 BTC</td>
<td class="text-right">24.12.2020 - 12:29</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr><tr>
<td>2532</td>
<td style=" text-transform: none; ">3NFucxQT*****SNT38m</td>
<td>1.58631772 BTC</td>
<td class="text-right">24.12.2020 - 11:23</td>
<td class="text-right"><i class="mdi mdi-check mr-1" style="vertical-align: sub;font-size: 20px;"></i>Paid</td>
</tr>
</tbody>
</table>
</div>
<script type="4593253136e0a1e4d26731bf-text/javascript">(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3744883,document.body||document.documentElement)</script><script type="4593253136e0a1e4d26731bf-text/javascript">(function(s,u,z,p){s.src=u,s.setAttribute('data-zone',z),p.appendChild(s);})(document.createElement('script'),'https://iclickcdn.com/tag.min.js',3744888,document.body||document.documentElement)</script> <div id="google_translate_element"></div>
</div>
<script type="4593253136e0a1e4d26731bf-text/javascript"> function googleTranslateElementInit() { new google.translate.TranslateElement({pageLanguage: 'en', layout: google.translate.TranslateElement.InlineLayout.TOP_LEFT}, 'google_translate_element'); } </script><script type="4593253136e0a1e4d26731bf-text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
</div>
</div>
<script src="https://btcmining.best/bitcoin-minings/assets/js/jquery.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/jquery-ui.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/jquery.ui.touch-punch.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/jquery.mask.money.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/popper.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/material.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/mdtoast.min.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script src="https://btcmining.best/bitcoin-minings/assets/js/custom.js?427434532244202" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script type="4593253136e0a1e4d26731bf-text/javascript"> _paymentsList(); $('input[name="amount"]').maskMoney({thousands:'', decimal:'.', precision:8});</script>

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-106404658-16" type="4593253136e0a1e4d26731bf-text/javascript"></script>
<script type="4593253136e0a1e4d26731bf-text/javascript">
	  window.dataLayer = window.dataLayer || [];
	  function gtag(){dataLayer.push(arguments);}
	  gtag('js', new Date());

	  gtag('config', 'UA-106404658-16');
	</script>
<script src="https://ajax.cloudflare.com/cdn-cgi/scripts/7089c43e/cloudflare-static/rocket-loader.min.js" data-cf-settings="4593253136e0a1e4d26731bf-|49" defer=""></script></body>
</html>
