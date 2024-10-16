# 各式 Web 前端開發工具整理

這裡收集了一系列各式各樣與「網頁前端」相關的開發工具、函式庫與參考文件，這些工具僅針對一般桌上型/筆記型電腦的顯示環境為主 (不含平板或手機等行動版網頁相關工具)。


## 程式碼編寫工具 (Coding Tools)


###### 工作流程/建置/組合 (Workflow/Builds/Assemblers)

* [lumbar](http://walmartlabs.github.io/lumbar/)
* [brunch](http://brunch.io/)
* [grunt](http://gruntjs.com/)
	* [lineman](https://github.com/testdouble/lineman)
	* [yeoman](http://yeoman.io/)
	* [Takeoff](http://tsvensen.github.io/Takeoff/)
* [mimosa](http://mimosajs.com/) 
* [codeKit](http://incident57.com/codekit/)
* [liveReload](http://livereload.com/)
* [stealJS](http://javascriptmvc.com/docs.html#!stealjs)
* [anvil.js](https://github.com/anviljs/anvil.js/)
* [modjs](http://modulejs.github.io/modjs/)
* [AUTOMATON](http://indigounited.com/automaton/)
* [Fire.app](http://fireapp.handlino.com/)

---

###### 瀏覽器套件管理員 (Browser Package Managers) (參見: [Front-End Package Manager Comparison](https://github.com/wilmoore/frontend-packagers))

* [bower](http://bower.io)
* [component](https://github.com/component/component)
* [ender](http://ender.jit.su/)
* [jam](http://jamjs.org/)

---

###### CSS 基底樣式/樣板
* [normalize.css](http://necolas.github.com/normalize.css/)

---

###### CSS 框架 (參見: [框架比較](http://responsive.vermilion.com/compare.php) 或 [前端 CSS 框架](http://usablica.github.com/front-end-frameworks/compare.html)) 

* [foundation](http://foundation.zurb.com/)
* [bootstrap](http://twitter.github.com/bootstrap/)
* [HTML KickStart](http://www.99lime.com/elements/)
* [kube](http://imperavi.com/kube/)
* [skeleton](http://www.getskeleton.com/)
* [baseline](http://baselinecss.com/)
* [gumby](http://gumbyframework.com)
* [Groundwork](http://groundwork.sidereel.com/?url=home)
* [topcoat](http://topcoat.io/)
* [purecss](http://purecss.io/)
* [tuktuk](http://tuktuk.tapquo.com/)
* [Metro UI CSS](http://metroui.org.ua/)
* [workless](http://workless.ikreativ.com/)
* [99lime](http://www.99lime.com/)
* [SUSY](http://susy.oddbird.net/)

---

###### HTML 基底結構/樣板

* [HTML5 Boilerplate](http://html5boilerplate.com/)
* [Rock Hammer](http://stuffandnonsense.co.uk/projects/rock-hammer/)
* [html5bones](http://html5bones.com/)
* [dCodes](http://www.dcodes.net/2/docs/index.html)

---

###### 操作 DOM 的相關函式庫 (FYI: dojo, yui, ext, qooxdoo 都有自己的 DOM 工具)
* [jQuery](http://jquery.com/)
	*  [jQuery++](http://jquerypp.com/)
* [zepto](http://zeptojs.com/)
* [tire](http://tirejs.com/)
* [mooTools](http://mootools.net/)
* [DOMAssistant](http://www.domassistant.com/)
* [Enders The Jeesh](https://github.com/ender-js/jeesh)
 	* [domReady](https://github.com/ded/domready)
 	* [query](https://github.com/ded/qwery)
	* [bonzo](https://github.com/ded/bonzo)
	* [bean](https://github.com/fat/bean)
	
---

###### 各式 JavaScript 輔助工具/函式庫
* [lo-dash](http://lodash.com/)
* [lazy.js](http://danieltao.com/lazy.js/)
* [string.js](http://stringjs.com/)
* [boiler.js](http://www.boilerjs.com/)
* [underscore](http://underscorejs.org/)
	* [underscore.string](http://epeli.github.io/underscore.string/)
* [sugar.js](http://sugarjs.com/)
* [craft.js](http://craftjs.org/)
* [valentine](https://github.com/ded/valentine)
* [platform.js](https://github.com/bestiejs/platform.js)
* [modernizr](http://modernizr.com/)
	* [yepnope](http://yepnopejs.com/)
* [JSON3](http://bestiejs.github.io/json3/)
* [uri.js](https://github.com/medialize/URI.js)
* [moment.js](http://momentjs.com/)
* [wait.js](https://github.com/elving/wait)
* [Numeral.js](http://numeraljs.com/)
* [accounting.js](http://josscrowcroft.github.io/accounting.js/)
* [Upcast](https://github.com/rowanmanning/upcast)
* [taffydb](http://www.taffydb.com/)
* [communist](http://communistjs.com/)

---

###### 鍵盤控制相關工具/函式庫
* [keys.js](https://github.com/bitwalker/keys.js)
* [mousestrap](http://craig.is/killing/mice)

---

###### 事件相關輔助工具/函式庫 (mouse/touch/pointer)
* [pointer.js](https://github.com/mozilla/pointer.js)
* [thumbs.js](http://mwbrooks.github.io/thumbs.js/)
* [Hammer.js](https://github.com/EightMedia/hammer.js)
* [Event.js](https://github.com/mudcube/Event.js)
* [DeepTissue.js](http://deeptissuejs.com)

---

###### CSS 關輔助工具/函式庫
* [-prefix-free](http://leaverou.github.io/prefixfree/)
* [CSScomb](http://csscomb.com)

---

###### 模組與指令碼載入工具/函式庫 (參見: [Javascript Loaders Comparison](https://spreadsheets.google.com/spreadsheet/lv?key=0Aqln2akPWiMIdERkY3J2OXdOUVJDTkNSQ2ZsV3hoWVE&f=true&noheader=true&gid=2))
* [require.js](http://requirejs.org/)
	* [almond](https://github.com/jrburke/almond)
* [cajon](https://github.com/requirejs/cajon)
* [browserify](https://github.com/substack/node-browserify)
* [curl](https://github.com/cujojs/curl)
* [shepherd-js](http://xcambar.github.io/shepherd-js/)
* [UMD (Universal Module Definition)](https://github.com/umdjs/umd)
	* [UMD-inspired Module Boilerplate](https://gist.github.com/3880415)
* [Inject](https://github.com/linkedin/inject)
* [volo](http://volojs.org/)
* [controlJS](http://controljs.org/)
* [JAL](https://github.com/tail-f-systems/JAL)
* [yepnope](http://yepnopejs.com/)
* [AXEL](https://github.com/amol-/axel)
* [lmd](http://lmdjs.org/)
* [LazyJS](http://bevacqua.github.io/lazyjs/)

---

###### JavaScript 範本引擎 ([template chooser](http://garann.github.io/template-chooser))
* [handlebars](http://handlebarsjs.com/)
* [pure](http://beebole.com/pure/)
* [dust](http://akdubya.github.io/dustjs/)
* [transparency](http://leonidas.github.io/transparency/)
* [plates](https://github.com/flatiron/plates)
* [mustache](http://mustache.github.com/)
	* [hogan.js](http://twitter.github.io/hogan.js/)
* [icanhaz](http://icanhazjs.com/)
* [doT.js](http://olado.github.io/doT/)
* [underscore](http://underscorejs.org/#template)
* [mold](https://github.com/idottv/Mold)

---

###### UI Widgets ([comparison](http://uiwidgets.t7interactive.com/))
* [chico-ui](http://chico-ui.com.ar/)
* [google closure](http://closure-library.googlecode.com/svn/trunk/closure/goog/demos/index.html)
* [DHTMLX](http://dhtmlx.com/)
* [extJS](http://www.sencha.com/products/extjs/examples/)
* [kendoUI](http://www.kendoui.com/)
* [qooxdoo](http://qooxdoo.org/)
* [bootstrap components & javascript](http://twitter.github.com/bootstrap/javascript.html)
	* [Fuel UX](http://exacttarget.github.com/fuelux/)
* [wijmo](http://wijmo.com/)
* [YUI3 Widgets](http://yuilibrary.com/yui/docs/guides/)
* [dojo dijits](http://dojotoolkit.org/reference-guide/1.8/dijit/index.html)
* [jQuery UI](http://jqueryui.com/)
* [Zino UI](http://zinoui.com/)
* [JKIT](http://jquery-jkit.com/)
* [w2ui](http://w2ui.com/web/)
* [basis.js](http://basisjs.com/)
* [webix](http://docs.webix.com/)


---

###### 測試執行工具 (Test Runners)

* [testem](https://github.com/airportyh/testem)
* [Karma](http://karma-runner.github.io/0.8/index.html)
* [intern](http://theintern.io/)

---

###### 使用者自動化測試工具 (User Automated Testing)

* [casperJS](http://casperjs.org/)

---

###### 測試框架 (Testing Frameworks)

* [mocha](http://visionmedia.github.com/mocha/)
* [buster.js](http://busterjs.org/)
* [qunit](http://qunitjs.com/)
* [jasmine](http://pivotal.github.com/jasmine/)
* [expect.js](https://github.com/LearnBoost/expect.js)

---

###### 其他測試函式庫 (Assertion Libraries)

* [chai](http://chaijs.com/)
* [should](https://github.com/visionmedia/should.js)
* [expect](https://github.com/LearnBoost/expect.js)

---

###### 遠端 DOM 與 JS 測試工具
* [browserstack](http://www.browserstack.com/)
* [browserling/testling](https://browserling.com/)
* [selenium](http://seleniumhq.org/)
* [JS test driver](http://code.google.com/p/js-test-driver/)

---

###### JavaScript 效能檢測工具 (JS Performance Testing)

* [benchmark.js](http://benchmarkjs.com/)
* [jsPerf — JavaScript performance playground](http://jsperf.com/)

---

###### JavaScript 自動化文件工具 (JS Auto Documentation Tools)
* [yuiDoc](http://yui.github.com/yuidoc/)
* [docco](http://jashkenas.github.com/docco/)
	* [docco-husky](https://github.com/mbrevoort/docco-husky)
* [jsduck](https://github.com/senchalabs/jsduck)
* [jsdoc](https://github.com/jsdoc3/jsdoc)
* [node-jsdoc-toolkit](https://github.com/p120ph37/node-jsdoc-toolkit)
* [dox](https://github.com/visionmedia/dox)
	* [markdox](https://github.com/cbou/markdox)

---

###### CSS 自動化文件工具 (CSS Auto Documentation Tools)
* [kss](https://github.com/kneath/kss)
* [styledocco/](http://jacobrask.github.com/styledocco/)

---

###### JavaScript 程式碼品質驗證工具 (JS Quality Validators)
* [jslint](http://www.jslint.com/)
* [jshint](http://www.jshint.com/)
* [JSLint Error Explanations](http://jslinterrors.com/)
* [jscomplexity](http://jscomplexity.org/)

---

###### CSS 品質驗證工具 (CSS Quality Validators)
* [csslint](http://csslint.net/)
* [recess](http://twitter.github.com/recess)

---

###### HTML 品質驗證工具 (HTML Quality Validators)
* [html-inspector](https://github.com/philipwalton/html-inspector)

---

###### JavaScript 最佳化/最小化/壓縮工具 (JS Optimizer/Minification/Compression Tools)
* [google closure compiler](https://developers.google.com/closure/compiler/)
* [uglifyJS](https://github.com/mishoo/UglifyJS)
* [Esprima](http://esprima.org/index.html)

---

###### CSS 最佳化/最小化/壓縮工具 (CSS Optimizer/Minification/Compression Tools)
* [ycssmin](https://github.com/yui/ycssmin)
* [CSSO](http://css.github.io/csso/)

---

###### CSS 前置處理器 (Languages Compiling to CSS)
* [Sass](http://sass-lang.com/)
	* [compass](http://compass-style.org)
	* [inuit.css](https://github.com/csswizardry/inuit.css)
	* [Bourbon](https://github.com/thoughtbot/bourbon): Mixins library for Sass
	* [Neat](https://github.com/thoughtbot/neat): Semantic CSS grid framework
* [stylus](http://learnboost.github.com/stylus/)
	* [nib](http://visionmedia.github.com/nib/)
* [less](http://lesscss.org)
	* [LESS Elements](http://lesselements.com/): Mixins library for LESS
	* [Semantic.gs](http://semantic.gs/): Semantic CSS grid system

###### JavaScript 前置處理器 (Languages Compiling to JS) ([http://altjs.org/](http://altjs.org/))
* [coffeeScript](http://coffeescript.org/)
* [dart](http://www.dartlang.org/)
* [roy](https://github.com/pufuwozu/roy)
* [ClojureScript](https://github.com/clojure/clojurescript)
* [TypeScript](http://www.typescriptlang.org/)

---

###### HTML 前置處理器 (Languages Compiling to HTML)
* [jade](http://jade-lang.com/)
* [haml](https://github.com/haml/haml)
* [markdown](http://daringfireball.net/projects/markdown/)
* [slim](http://slim-lang.com/)

---

###### 純前端應用程式框架 (Front End Application Structure) (somewhat backend agnostic)
* [backbone](http://backbonejs.org/)
	* [marionette](http://marionettejs.com)
	* [chaplin](http://chaplinjs.github.com/)
	* [aura](http://addyosmani.github.com/aura/)
	* [thorax](http://walmartlabs.github.com/thorax/)
* [ember](http://emberjs.com/)
* [knockout](http://knockoutjs.com/)
* [canjs](http://canjs.us/)
* [spine](http://spinejs.com/)
* [angularJS](http://angularjs.org/)
	* [ngmodules.org](http://ngmodules.org/)
* [maria](http://peter.michaux.ca/maria/)
* [sparky.js](http://sparkyjs.com/)
* [hoodie](http://hood.ie/)
* [lure.js](http://tylerbuchea.com/projects/lure/#/)

---

###### 包含後端技術的前端應用程式框架 (Front End Application Structure) (with backend opinions)
* [derby](http://derbyjs.com/) (requires NodeJS)
* [flatiron](http://flatironjs.org/) (requires NodeJS)
* [batman.js](http://batmanjs.org/) (requires NodeJS)
* [jsMVC](http://javascriptmvc.com/) (requires Java)
* [montage](http://montagejs.org/) (requires NodeJS)

---

###### 整合式應用程式框架 (Full Stack Application Structure/Frameworks)
* [tower.js](http://towerjs.org/) (requires NodeJS)
* [wakanda](http://www.wakanda.org/)
* [meteor](http://www.meteor.com/)

---

###### 前端 JavaScript 框架 (Frontend JavaScript Frameworks) (aka Kitchen Sink Solutions, tools below provide a mixture of the things above)
* [YUI3](http://yuilibrary.com/projects/yui3/)
* [dojo](http://dojotoolkit.org/extjs)
* [extJS](http://www.sencha.com/products/extjs/)
* [qooxdoo](http://qooxdoo.org/)
* [google closure](https://developers.google.com/closure/)


## 參考資料/教學手冊/相容性套件/程式產生器等相關工具 (Reference/Guide/Polyfill/Generator Tools)

###### 文件翻閱工具
* [DevDocs — API Documentation Reader](http://devdocs.io/)
* [DocHub | Instant Documentation Search](http://dochub.io/)

---

###### 瀏覽器相容性工具/文件 (Browser X Supports X)
* [http://caniuse.com/](http://caniuse.com/)
* [http://html5please.com/](http://html5please.com/)
* [http://html5readiness.com/](http://html5readiness.com/)
* [html5test.com](http://html5test.com/index.html)
* [http://www.browsersupport.net/](http://www.browsersupport.net/)
* [http://css3test.com/](http://css3test.com/)
* [Browserscope](http://www.browserscope.org/)
* [HTML5 & CSS3 Support](http://www.findmebyip.com/litmus/)
* [CSS4-Selectors](http://css4-selectors.com/selectors/)
* [HTML5 - Information and samples for HTML5 and related APIs](http://robertnyman.com/html5/)
* [CSS3 - Information and samples](http://robertnyman.com/css3/)
* [JavaScript tests & Compatibility tables](http://robertnyman.com/javascript/)
* [Cross Browser Handbook Knowledgebase](http://www.crossbrowserbook.com/Knowledge)
* [JS-Compatibility-Table](http://compatibility.shwups-cms.ch/de/home/?)
* [webbrowsercompatibility](http://www.webbrowsercompatibility.com/)

---

###### HTML 語言參考 & 相容性工具 (HTML Language References & Polyfills)
* [HTML5 A technical specification for Web developers](http://developers.whatwg.org/)
* [HTML Living Standard](http://www.whatwg.org/specs/web-apps/current-work/multipage/)
* [HTML5 A vocabulary and associated APIs for HTML and XHTML](http://www.w3.org/TR/html5/)
* [HTML 5 Reference A Web Developer’s Guide to HTML 5](http://dev.w3.org/html5/html-author/)
* [HyperText Markup Language (HTML), from Mozilla](https://developer.mozilla.org/en-US/docs/HTML)
* [HTML5 differences from HTML4](http://dev.w3.org/html5/html4-differences/)
* [html5shiv](https://github.com/aFarkas/html5shiv)
* [html5.js](https://github.com/bestiejs/html5.js)

---

###### HTML5 相關規格/參考資料與相容性套件 (HTML5 & Friends Specs/Ref & Polyfills)
* [webbrowsercompatibility.com](http://www.webbrowsercompatibility.com/)
* [HTML5 & Friends, from Mozilla](https://developer.mozilla.org/en-US/docs/HTML/HTML5)
* [html5rocks](http://www.html5rocks.com/en/)
* [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)
* [HTML5 - Information and samples for HTML5 and related APIs](http://robertnyman.com/html5/)
* [HTML 5 Demos and Examples](http://html5demos.com/)
* [SVG](https://developer.mozilla.org/en-US/docs/SVG)
	* [SVG-edit browser editor](http://svg-edit.googlecode.com/svn-history/r1771/trunk/editor/svg-editor.html)
	* [D3.js](http://d3js.org/)
	* [raphaeljs](http://raphaeljs.com/)
	* [bonsaijs.org](http://bonsaijs.org/)
* [Canvas](https://developer.mozilla.org/en-US/docs/HTML/Canvas)
	* [paper.js](http://paperjs.org/)
	* [fabric.js](http://fabricjs.com/)
	* [kineticjs](http://kineticjs.com/)
* [webGL](https://developer.mozilla.org/en-US/docs/WebGL)
	* [three.js](http://mrdoob.github.com/three.js/)
	* [The X Toolkit](https://github.com/xtk/X#readme)

---

###### DOM 相關規格/參考資料與相容性套件 (DOM Specs/Ref & Polyfills)
* [DOM Living Standard](http://dom.spec.whatwg.org/)
* [DOM Parsing and Serialization Living Standard](http://domparsing.spec.whatwg.org/)
* [DOM4](http://www.w3.org/TR/dom/)
* [Document Object Model (DOM) Technical Reports, from W3C](http://www.w3.org/DOM/DOMTR)
* [Document Object Model, from Microsoft](http://msdn.microsoft.com/en-us/library/ie/hh772384\(v=vs.85\).aspx)
* [Document Object Model, from Mozilla](https://developer.mozilla.org/en-US/docs/DOM)
* [Event compatibility tables](http://www.quirksmode.org/dom/events/index.html)

---

###### CSS 相關規格/參考資料與相容性套件 (CSS Specs/Ref & Polyfills)
* [CSS, from Mozilla](https://developer.mozilla.org/en-US/docs/CSS)
* [CSS SPEC-I-FI-CA-TIONS, from W3C](http://www.w3.org/Style/CSS/current-work)
* [http://cssvalues.com/](http://cssvalues.com/)
* [CSS contents and browser compatibility](http://www.quirksmode.org/css/contents.html)
* [CSS Compatibility and Internet Explorer](http://msdn.microsoft.com/en-us/library/cc351024\(VS.85\).aspx)
* [HTML5 Cross Browser Polyfills (look for CSS)](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)
* [CSS Selectors from CSS4 till CSS1](http://css4-selectors.com/selectors/)
* [css3clickchart.com](http://css3clickchart.com/)
* [CSS selectors](http://www.quirksmode.org/css/selectors/)

---

###### CSS 產生器 (CSS Generators)
* [patternify](http://www.patternify.com/)
* [Ultimate CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/)
* [patternizer](http://patternizer.com/)
* [css3please.com](http://css3please.com/)
* [cssarrowplease.com](http://cssarrowplease.com/)
* [CSS Flexbox Please](http://demo.agektmr.com/flexbox/)
* [CSS3 GENERATOR](http://www.css3.me/)
* [css3generator.com](http://css3generator.com/)
* [css3maker.com](http://www.css3maker.com/)
* [CSS3 Sandbox](http://westciv.com/tools/index.html)
* [The Shapes of Css](http://coderwall.com/p/xrxaxa)
* [CSS matic](http://www.cssmatic.com/)

---

###### CSS 編寫風格與慣例指引 (CSS Style/Conventions Guides)
* [kss](https://github.com/kneath/kss#readme)
* [SMACSS](http://smacss.com/)
* [Google HTML/CSS Style Guide](http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml#Declaration_order)
* [idiomatic-css](https://github.com/necolas/idiomatic-css)
* [Object-Oriented CSS](http://oocss.org/)
* [WordPress.org UI Style Guide](http://dotorgstyleguide.wordpress.com/)
* [Starbucks Style Guide](http://www.starbucks.com/static/reference/styleguide/)
* [Github CSS styleguide](https://github.com/styleguide/css)
* [General CSS notes, advice and guidelines](https://github.com/csswizardry/CSS-Guidelines)

---

###### JavaScript ES5 相關規格/參考資料與相容性套件 (JavaScript ES5 Specs/Ref & Polyfills)
* [ECMA-262-5 in detail](http://dmitrysoshnikov.com/ecmascript/es5-chapter-0-introduction/)
* [ECMAScript Language Specification](http://ecma-international.org/ecma-262/5.1/)
* [Annotated ECMAScript 5.1](http://es5.github.com/)
* [ECMAScript 5 compatibility table](http://kangax.github.com/es5-compat-table/)
* [Internet Explorer ECMA-262 ECMAScript Language Specification (Fifth Edition) Standards Support Document](http://msdn.microsoft.com/en-us/library/ff960769.aspx)
* [JavaScript Reference, from Mozilla](https://developer.mozilla.org/en-US/docs/JavaScript/Reference)
* [The sample usage of ECMA 5 Features Implemented in V8](https://gist.github.com/1073547)
* [Understanding JavaScript OOP](http://killdream.github.com/blog/2011/10/understanding-javascript-oop/)
* [JavaScript, aka. Web ECMAScript Living Standard](http://mathias.html5.org/specs/javascript/)
* [es5-shim](https://github.com/kriskowal/es5-shim/)
* [poly](https://github.com/cujojs/poly)
* [Augment.js](http://augmentjs.com/)

---

###### JavaScript ES6 相關規格/參考資料與相容性套件 (JavaScript ES6 Specs/Ref & Polyfills)
* [ES6 what can be shimmed and what not](https://gist.github.com/1665192)
* [ECMAScript 6 compatibility table](http://kangax.github.com/es5-compat-table/es6/)
* [Draft Specification for ES.next (Ecma-262 Edition 6)](http://wiki.ecmascript.org/doku.php?id=harmony:specification_drafts)
* [es6-shim](https://github.com/paulmillr/es6-shim)
* [ECMA-262 6th Edition/Draft](http://people.mozilla.org/~jorendorff/es6-draft.html)
 
---

###### JavaScript 編寫風格與慣例指引 (JavaScript Style/Conventions Guides)
* [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* [Felix's Node.js Style Guide](http://nodeguide.com/style.html)
* [idiomatic.js](https://github.com/rwldrn/idiomatic.js)
* [Code Conventions for the JavaScript Programming Language](http://javascript.crockford.com/code.html)
* [jsbeautifier](http://jsbeautifier.org/)
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

---

###### JSON 產生器
* [JSON Generator &ndash; tool for generating random JSON data](http://www.json-generator.com/)
* Convert JSON to TypeScript Interface(https://json-5.com/json-to-typescript)

---

###### 一般前端開發實務與開發習慣 (General Front-end Practices/Conventions)
* [isobar](http://isobar-idev.github.com/code-standards/)
* [Being A Web Developer](http://www.yellowshoe.com.au/standards/)
* [Front End Dev Guidelines](http://taitems.github.com/Front-End-Development-Guidelines/)
* [HTML and CSS code guide](https://github.com/mdo/code-guide)

## 效能調校

###### 相關工具

* [Charles](http://www.charlesproxy.com/)
* [webpagetest](http://www.webpagetest.org/)
* [PageSpeed Insights Browser Extensions](https://developers.google.com/speed/pagespeed/)
* [Chrome Developer Tools: Network Panel](https://developers.google.com/chrome-developer-tools/docs/network)
* [Chrome Developer Tools: Timeline Panel](https://developers.google.com/chrome-developer-tools/docs/timeline)
* [Chrome Developer Tools: Profiles Panel](https://developers.google.com/chrome-developer-tools/docs/profiles)
* [DOM Monster](http://mir.aculo.us/dom-monster/)
* [ImageOptim](http://imageoptim.com/)

###### 準則與實務

* [Web Performance Best Practices](https://developers.google.com/speed/docs/best-practices/rules_intro)
* [Best Practices for Speeding Up Your Web Site](http://developer.yahoo.com/performance/rules.html)
* [High Performance Web Sites - 14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/)
* [Even Faster Web Sites](http://stevesouders.com/efws/)


## 各式線上編輯器/開發工具 ([REPL](http://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop "Read–eval–print loop"))

###### JS REPL
* [repl.it](http://repl.it/)
* [jsconsole.com](http://jsconsole.com/)
* [codeboot.org](http://codeboot.org/)
* [continuum](http://benvie.github.com/continuum/)

###### JavaScript 線上編輯器 (JS focused editors)
* [jsfiddle](http://jsfiddle.net/)
* [jsbin](http://jsbin.com/)

###### 正規表示式編輯器 (Regular Expression editors)
* [Scriptular](http://scriptular.com/)
* [regexr](http://gskinner.com/RegExr/)
* [refiddle](http://refiddle.com/)
* [RegexPlanet](http://www.regexplanet.com/)
* [Debuggex: The online visual regex tester. JavaScript, Python, and PCRE.](http://www.debuggex.com/)

###### HTML/CSS 編輯器
* [dabblet](http://dabblet.com/)
* [cssdesk](http://cssdesk.com/)

###### HTML/CSS/JS 編輯器
* [tinker.io](https://tinker.io/)
* [tinkerbin](http://tinkerbin.com/)
* [Plunker](https://github.com/filearts/plunker)
* [cssdeck](http://cssdeck.com/)
* [codepen](http://codepen.io/)

###### 執行/測試代碼工具 (Execute/Test live code)
* [runnable](http://runnable.com/)

###### 雲端開發工具 (Browser IDE's)
* [koding](https://koding.com/)
* [cloud9 IDE](https://c9.io/)
* [action.io](https://www.action.io)

###### JSON 編輯器
* [jsoneditoronline.org](http://jsoneditoronline.org/)
* [JSON Tinker](http://json.bubblemix.net/)
* [JSONmat](http://jsonmate.com/)
* [JSON5 Editor](https://json-5.com/)

## 瀏覽器安全性 (Browser Security)

* [Browser Security Handbook](http://code.google.com/p/browsersec/wiki/Main)

## 各式 CSS/HTML Hacks 整理 (Browser Hacks)

* [browserhacks.com](http://www.browserhacks.com/)


## 給前端開發人員的後端服務 (Backend services for frontend developers)

* [firebase](https://www.firebase.com/index.html)
* [pusher](http://pusher.com/)
* [jaystack](http://jaystack.com/)
* [parse](https://www.parse.com)
* [singly](https://singly.com/)
* [cloud CMS](https://www.cloudcms.com/)
* [kinvey](http://www.kinvey.com/)
* [stackmob](http://www.stackmob.com/)
* [cloudmine](https://cloudmine.me/)
* [kumulos](http://www.kumulos.com/)
* [deployd](http://deployd.com/)
* [backlift.com](https://backlift.com/index.html)
* [hull.io](http://hull.io/)
* [stormpath.com](http://stormpath.com/)

## API 開發與測試工具

* [apiary](http://apiary.io/)
* [mocky.io](http://www.mocky.io/)
* [FillText.com](http://www.filltext.com/)

## JSON 資料操作/查詢工具 (JSON Query Tools)

* [TaffyDB](http://www.taffydb.com/)
* [linq.js](http://linqjs.codeplex.com/)
* [json:select()](http://jsonselect.org/)
* [JSONiq](http://www.jsoniq.org/)
* [json-query](https://github.com/mmckegg/json-query)
* [SpahQL](http://danski.github.io/spahql/)

## 格式化工具

* [Online JavaScript beautifier](http://jsbeautifier.org/)
* [CSS Beautifier](http://html.fwpolice.com/css/)
