<h1>Bullreset v3.0</h1> 

<b>Description:</b> My personal "bulldozer" CSS normalizer/framework

<b>It's based on</b> 6 github projects:
<ul>
<li>Normalize.css by Nicolas Gallagher https://github.com/necolas/normalize.css</li> 
<li>Formalize by Nathan Smith https://github.com/nathansmith/formalize</li> 
<li>HTML5 Boilerplate CSS https://github.com/h5bp/html5-boilerplate</li> 
<li>Bootstrap framework by Twitter https://github.com/twitter/bootstrap</li> 
<li>Inuit CSS by Harry Roberts https://github.com/csswizardry/inuit.css</li> 
<li>YUI 3 CSS Grids by Yahoo! https://github.com/yui/yui3</li> 
</ul>

<b>It's includes</b> also useful styles for cross-browsing, responsive web design, wordpress core styles, better typography, better forms, better links and useful tips&tricks.

<p><b>Author:</b> Marco Pontili<br>
<b>Author URI:</b> http://135design.com<br>
<b>Author Twitter:</b> @m135_</p>

<b>License:</b> none (public domain)

<hr>

<i>New repo coming soon...check now the JS Bin instead <b>http://jsbin.com/oyasux/25.css</b></i>


<pre><code>/*! Project: Bullframe v1.0.1 - @m135_ */ @-o-viewport{width:device-width}@-moz-viewport{width:device-width}@-ms-viewport{width:device-width}@-webkit-viewport{width:device-width}@viewport{width:device-width}*,*:after,*:before{word-wrap:break-word}html{overflow-y:scroll;font-size:100%;-webkit-text-size-adjust:100%;-ms-text-size-adjust:100%}body{min-width:0;margin:0;line-height:1.4;font-size:1em;background:#fff}article,aside,details,figcaption,figure,footer,header,hgroup,nav,section,summary{display:block}dl,menu,ol,ul{margin:1em 0}dd{margin:0 0 0 40px}menu,ol,ul{padding:0 0 0 40px}ul ul,ul ol,ol ol,ol ul{margin-bottom:0}ul.unstyled,ol.unstyled{margin-left:0;list-style:none}li>ul,li>ol{margin-bottom:0}nav ul,nav ol{margin:0;padding:0;list-style:none;list-style-image:none}.nav>li,.nav>li>a{display:inline-block;*display:inline;*zoom:1}canvas,video{display:inline-block;*display:inline;*zoom:1}video{max-width:100%;height:auto}audio:not([controls]){display:none;height:0}[hidden]{display:none}svg:not(:root){overflow:hidden}figure{margin:0}figure>img{display:block}img{width:auto\9;height:auto;max-width:100%;vertical-align:middle;border:0;color:#f00;-ms-interpolation-mode:bicubic}#map_canvas img,.google-maps img{max-width:none}iframe{max-width:100%;height:auto}body,button,input,select,textarea{font-family:"Helvetica Neue",Helvetica,Arial,Verdana,sans-serif;color:#222}h1,h2,h3,h4,h5,h6{font-family:inherit;font-weight:bold;color:inherit;-webkit-font-smoothing:antialiased;text-rendering:optimizelegibility}h1 small,h2 small,h3 small,h4 small,h5 small,h6 small{font-weight:normal;line-height:1;color:#999}h1,.h1{font-size:2em;margin:.67em 0}h2,.h2{font-size:1.5em;margin:.83em 0}h3,.h3{font-size:1.17em;margin:1em 0}h4,.h4{font-size:1em;margin:1.33em 0}h5,.h5{font-size:.83em;margin:1.67em 0}h6,.h6{font-size:.75em;margin:2.33em 0}h1 small{font-size:1.5em}h2 small{font-size:1.06em}h3 small{font-size:.87em}h4 small{font-size:.87em}hr{display:block;height:1px;border:0;border-top:1px solid #ccc;margin:1em 0;padding:0}abbr[title],acronym{border-bottom:1px dotted;cursor:help}blockquote,q{quotes:none}blockquote:before,blockquote:after,q:before,q:after{content:'';content:none}address{display:block;margin-bottom:1.25em;font-style:normal;line-height:1.25em}blockquote{margin:1em 40px}ins{background:#ff9;color:#000;text-decoration:none}mark{background:#ff0;color:#000;font-weight:bold}del,strike,s{text-decoration:line-through}p,pre{margin:1em 0}pre,code,kbd,tt,samp,xmp{font-family:Inconsolata,Monaco,Consolas,"Andale Mono","Bitstream Vera Sans Mono","Courier New",Courier,monospace;font-size:1em}pre{word-break:break-all;word-wrap:break-word;white-space:pre;white-space:pre-wrap}strong,b{font-weight:bold}address,em,i,cite,dfn,dfn[title],var{font-style:italic}u{text-decoration:underline}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}small{font-size:85%}big{font-size:115%}::selection{background:#b3d4fc;color:#000;text-shadow:none}::-moz-selection{background:#b3d4fc;color:#000;text-shadow:none}a,p a{color:#1467ff;text-decoration:none}a{-webkit-tap-highlight-color:rgba(20,103,255,0.5)}a:focus{outline:thin dotted;outline:5px auto -webkit-focus-ring-color;outline-offset:-2px}a:hover,a:active{color:#002b7a;outline:0}form{margin:0}fieldset{border:0;margin:0;padding:0}legend{border:0;padding:0;white-space:normal;*margin-left:-7px}label{cursor:pointer}button,input,select,textarea{font-size:100%;margin:0;padding:0;vertical-align:baseline;*vertical-align:middle}button,input{line-height:normal}button,input[type="color"],input[type="email"],input[type="image"],input[type="file"],input[type="number"],input[type="password"],input[type="tel"],input[type="search"],input[type="text"],input[type="date"],input[type="datetime"],input[type="datetime-local"],input[type="month"],input[type="time"],input[type="week"],input[type="time"],input[type="url"],input[type="reset"],input[type="submit"],input[type="button"],select,textarea{border:1px solid #999;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}button,html input[type="button"],input[type="reset"],input[type="submit"]{background-color:#e5e5e5;-webkit-background-clip:padding;-moz-background-clip:padding;-o-background-clip:padding-box;background-clip:padding-box;cursor:pointer;*overflow:visible;-webkit-appearance:button}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}button:focus,input:focus,select:focus,textarea:focus{z-index:1}button:focus,input:focus,input[type="file"]:focus,input[type="radio"]:focus,input[type="checkbox"]:focus,input[type="file"]:active,input[type="radio"]:active,input[type="checkbox"]:active,select:focus,textarea:focus,:invalid{-moz-box-shadow:none;-webkit-box-shadow:none;box-shadow:none}button,input[type="color"],input[type="email"],input[type="image"],input[type="number"],input[type="password"],input[type="search"],input[type="search"]::-webkit-search-decoration,input[type="search"]::-webkit-search-cancel-button,input[type="tel"],input[type="text"],input[type="week"],input[type="url"],textarea{-webkit-appearance:none}input[type="search"]{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type="radio"],input[type="checkbox"]{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;padding:0;*width:13px;*height:13px}input[type="checkbox"]{-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}select[size],select[multiple]{height:auto}textarea{height:auto;min-height:40px;overflow:auto;vertical-align:top;resize:vertical}input:invalid,textarea:invalid{background-color:#f0dddd}input::-webkit-input-placeholder,textarea::-webkit-input-placeholder{color:#888}input:-moz-placeholder,textarea:-moz-placeholder{color:#888}input:placeholder,textarea:placeholder{color:#888}input[disabled],select[disabled],textarea[disabled],input[readonly],select[readonly],textarea[readonly]{background-color:#f5f5f5;border-color:#ddd;cursor:default;cursor:not-allowed}table{width:100%;max-width:100%;border-collapse:collapse;border-spacing:0;background-color:transparent}thead th{vertical-align:bottom}th,td{vertical-align:top}th{font-weight:bold}th,caption{text-align:left}.img-r{display:block;border:0;text-indent:-999em;overflow:hidden;background-color:transparent;background-repeat:no-repeat;text-align:left;direction:ltr;*line-height:0}.img-r br{display:none}.hide-text{font:0/0 a;color:transparent;text-shadow:none;background-color:transparent;border:0}.clearfix:before,.clearfix:after{content:"";display:table;line-height:0}.clearfix:after{clear:both}.clearfix{*zoom:1}.input-block-level{display:block;width:100%;min-height:30px;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}.block{display:block;width:100%}.hidden{display:none;visibility:hidden}.show{display:block;visibility:visible}.visuallyhidden{border:0;clip:rect(0 0 0 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;width:1px}.visuallyhidden.focusable:active,.visuallyhidden.focusable:focus{clip:auto;height:auto;margin:0;overflow:visible;position:static;width:auto}.invisible{visibility:hidden}.screen-reader-text,.assistive-text{position:absolute!important;clip:rect(1px 1px 1px 1px);clip:rect(1px,1px,1px,1px)}.pull-right{float:right}.pull-left{float:left}.affix{position:fixed}.no-margin{margin:0!important}.no-margin-left{margin-left:0!important}.no-padding{padding:0!important}.no-border{border:0!important}.chromeframe{margin:.2em 0;background:#ccc;color:#000;padding:.2em 0}.flex-video-container{position:relative;padding-bottom:56.25%;padding-top:30px;height:0;overflow:hidden}.flex-video-container iframe,.flex-video-container object,.flex-video-container embed{position:absolute;top:0;left:0;width:100%;height:100%}.visible-phone{display:none!important}.visible-tablet{display:none!important}.hidden-desktop{display:none!important}.visible-desktop{display:inherit!important}#edit-with-js-bin{display:none}.alignnone{margin:5px 20px 20px 0}.aligncenter,div.aligncenter{display:block;margin:5px auto 5px auto}.alignright{float:right;margin:5px 0 20px 20px}.alignleft{float:left;margin:5px 20px 20px 0}.aligncenter{display:block;margin:5px auto 5px auto}a img.alignright{float:right;margin:5px 0 20px 20px}a img.alignnone{margin:5px 20px 20px 0}a img.alignleft{float:left;margin:5px 20px 20px 0}a img.aligncenter{display:block;margin-left:auto;margin-right:auto}.wp-caption{background:#fff;border:1px solid #f0f0f0;max-width:96%;padding:5px 3px 10px;text-align:center}.wp-caption.alignnone{margin:5px 20px 20px 0}.wp-caption.alignleft{margin:5px 20px 20px 0}.wp-caption.alignright{margin:5px 0 20px 20px}.wp-caption img{border:0 none;height:auto;margin:0;max-width:98.5%;padding:0;width:auto}.wp-caption p.wp-caption-text{font-size:11px;line-height:17px;margin:0;padding:0 4px 5px}.yui3-g{letter-spacing:-0.31em;*letter-spacing:normal;word-spacing:-0.43em}.yui3-u{display:inline-block;zoom:1;*display:inline;letter-spacing:normal;word-spacing:normal;vertical-align:top}.yui3-u-1,.yui3-u-1-2,.yui3-u-1-3,.yui3-u-2-3,.yui3-u-1-4,.yui3-u-3-4,.yui3-u-1-5,.yui3-u-2-5,.yui3-u-3-5,.yui3-u-4-5,.yui3-u-1-6,.yui3-u-5-6,.yui3-u-1-8,.yui3-u-3-8,.yui3-u-5-8,.yui3-u-7-8,.yui3-u-1-12,.yui3-u-5-12,.yui3-u-7-12,.yui3-u-11-12,.yui3-u-1-24,.yui3-u-5-24,.yui3-u-7-24,.yui3-u-11-24,.yui3-u-13-24,.yui3-u-17-24,.yui3-u-19-24,.yui3-u-23-24{display:inline-block;*display:inline;*zoom:1;letter-spacing:normal;word-spacing:normal;vertical-align:top}.yui3-u-1{display:block}.yui3-u-1-2{width:50%}.yui3-u-1-3{width:33.33333%}.yui3-u-2-3{width:66.66666%}.yui3-u-1-4{width:25%}.yui3-u-3-4{width:75%}.yui3-u-1-5{width:20%}.yui3-u-2-5{width:40%}.yui3-u-3-5{width:60%}.yui3-u-4-5{width:80%}.yui3-u-1-6{width:16.656%}.yui3-u-5-6{width:83.33%}.yui3-u-1-8{width:12.5%}.yui3-u-3-8{width:37.5%}.yui3-u-5-8{width:62.5%}.yui3-u-7-8{width:87.5%}.yui3-u-1-12{width:8.3333%}.yui3-u-5-12{width:41.6666%}.yui3-u-7-12{width:58.3333%}.yui3-u-11-12{width:91.6666%}.yui3-u-1-24{width:4.1666%}.yui3-u-5-24{width:20.8333%}.yui3-u-7-24{width:29.1666%}.yui3-u-11-24{width:45.8333%}.yui3-u-13-24{width:54.1666%}.yui3-u-17-24{width:70.8333%}.yui3-u-19-24{width:79.1666%}.yui3-u-23-24{width:95.8333%}#yui3-css-stamp.cssgrids{display:none}@media(min--moz-device-pixel-ratio:1.5),(-o-min-device-pixel-ratio:3/@media print{*{background:transparent!important;color:#000!important;box-shadow:none!important;text-shadow:none!important}a,a:visited{text-decoration:underline}pre,blockquote{border:1px solid #999;page-break-inside:avoid}thead{display:table-header-group}tr,img{page-break-inside:avoid}img{max-width:100%!important}@page{margin:.5cm}p,h2,h3{orphans:3;widows:3}h2,h3{page-break-after:avoid}}</code></pre>

