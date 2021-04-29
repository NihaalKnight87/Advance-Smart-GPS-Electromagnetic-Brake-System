(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{for(var c=da,d=a.split("."),e=0;e<d.length-1;e++){var f=d[e];if(!(f in c))break a;c=c[f]}d=d[d.length-1];e=c[d];f=b(e);f!=e&&null!=f&&ba(c,d,{configurable:!0,writable:!0,value:f})}}
t("Symbol",function(a){function b(e){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c("jscomp_symbol_"+(e||"")+"_"+d++,e)}
function c(e,f){this.f=e;ba(this,"description",{configurable:!0,writable:!0,value:f})}
if(a)return a;c.prototype.toString=function(){return this.f};
var d=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ja;
if("function"==typeof Object.setPrototypeOf)ja=Object.setPrototypeOf;else{var ka;a:{var la={a:!0},ma={};try{ma.__proto__=la;ka=ma.a;break a}catch(a){}ka=!1}ja=ka?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var na=ja;
function v(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(na)na(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.J=b.prototype}
function oa(){this.l=!1;this.h=null;this.A=void 0;this.g=1;this.i=this.j=0;this.o=this.f=null}
function pa(a){if(a.l)throw new TypeError("Generator is already running");a.l=!0}
oa.prototype.m=function(a){this.A=a};
function qa(a,b){a.f={Ma:b,xa:!0};a.g=a.j||a.i}
oa.prototype["return"]=function(a){this.f={"return":a};this.g=this.i};
function ra(a,b){a.g=5;return{value:b}}
oa.prototype.qa=function(a){this.g=a};
function sa(a){a.j=2;a.i=3}
function ta(a){a.j=0;a.f=null}
function ua(a){a.o=[a.f];a.j=0;a.i=0}
function va(a){var b=a.o.splice(0)[0];(b=a.f=a.f||b)?b.xa?a.g=a.j||a.i:void 0!=b.qa&&a.i<b.qa?(a.g=b.qa,a.f=null):a.g=a.i:a.g=4}
function wa(a){this.f=new oa;this.g=a}
function xa(a,b){pa(a.f);var c=a.f.h;if(c)return ya(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.f["return"]);
a.f["return"](b);return za(a)}
function ya(a,b,c,d){try{var e=b.call(a.f.h,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.f.l=!1,e;var f=e.value}catch(g){return a.f.h=null,qa(a.f,g),za(a)}a.f.h=null;d.call(a.f,f);return za(a)}
function za(a){for(;a.f.g;)try{var b=a.g(a.f);if(b)return a.f.l=!1,{value:b.value,done:!1}}catch(c){a.f.A=void 0,qa(a.f,c)}a.f.l=!1;if(a.f.f){b=a.f.f;a.f.f=null;if(b.xa)throw b.Ma;return{value:b["return"],done:!0}}return{value:void 0,done:!0}}
function Aa(a){this.next=function(b){pa(a.f);a.f.h?b=ya(a,a.f.h.next,b,a.f.m):(a.f.m(b),b=za(a));return b};
this["throw"]=function(b){pa(a.f);a.f.h?b=ya(a,a.f.h["throw"],b,a.f.m):(qa(a.f,b),b=za(a));return b};
this["return"]=function(b){return xa(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ba(a,b){var c=new Aa(new wa(b));na&&a.prototype&&na(c,a.prototype);return c}
t("Reflect",function(a){return a?a:{}});
t("Reflect.construct",function(){return ia});
t("Reflect.setPrototypeOf",function(a){return a?a:na?function(b,c){try{return na(b,c),!0}catch(d){return!1}}:null});
function Ca(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ca(this,b,"endsWith");b+="";void 0===c&&(c=d.length);for(var e=Math.max(0,Math.min(c|0,d.length)),f=b.length;0<f&&0<e;)if(d[--e]!=b[--f])return!1;return 0>=f}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ca(this,b,"startsWith");b+="";for(var e=d.length,f=b.length,g=Math.max(0,Math.min(c|0,d.length)),h=0;h<f&&g<e;)if(d[g++]!=b[h++])return!1;return h>=f}});
t("Object.setPrototypeOf",function(a){return a||na});
function w(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var Da="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)w(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||Da});
t("Promise",function(a){function b(g){this.f=0;this.h=void 0;this.g=[];this.m=!1;var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.f=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.g=function(g){if(null==this.f){this.f=[];var h=this;this.h(function(){h.j()})}this.f.push(g)};
var e=da.setTimeout;c.prototype.h=function(g){e(g,0)};
c.prototype.j=function(){for(;this.f&&this.f.length;){var g=this.f;this.f=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.i(l)}}}this.f=null};
c.prototype.i=function(g){this.h(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.H),reject:g(this.j)}};
b.prototype.H=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.P(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.G(g):this.l(g)}};
b.prototype.G=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}"function"==typeof h?this.R(h,g):this.l(g)};
b.prototype.j=function(g){this.A(2,g)};
b.prototype.l=function(g){this.A(1,g)};
b.prototype.A=function(g,h){if(0!=this.f)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.f);this.f=g;this.h=h;2===this.f&&this.I();this.o()};
b.prototype.I=function(){var g=this;e(function(){if(g.B()){var h=da.console;"undefined"!==typeof h&&h.error(g.h)}},1)};
b.prototype.B=function(){if(this.m)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.h;return k(g)};
b.prototype.o=function(){if(null!=this.g){for(var g=0;g<this.g.length;++g)f.g(this.g[g]);this.g=null}};
var f=new c;b.prototype.P=function(g){var h=this.i();g.ga(h.resolve,h.reject)};
b.prototype.R=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(q,r){return"function"==typeof q?function(A){try{l(q(A))}catch(B){m(B)}}:r}
var l,m,p=new b(function(q,r){l=q;m=r});
this.ga(k(g,l),k(h,m));return p};
b.prototype["catch"]=function(g){return this.then(void 0,g)};
b.prototype.ga=function(g,h){function k(){switch(l.f){case 1:g(l.h);break;case 2:h(l.h);break;default:throw Error("Unexpected state: "+l.f);}}
var l=this;null==this.g?f.g(k):this.g.push(k);this.m=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),m=l.next();!m.done;m=l.next())d(m.value).ga(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,m){function p(A){return function(B){q[A]=B;r--;0==r&&l(q)}}
var q=[],r=0;do q.push(void 0),r++,d(k.value).ga(p(q.length-1),m),k=h.next();while(!k.done)})};
return b});
function Ea(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.entries",function(a){return a?a:function(){return Ea(this,function(b,c){return[b,c]})}});
t("Array.prototype.keys",function(a){return a?a:function(){return Ea(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Ea(this,function(b,c){return c})}});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length,f=c||0;for(0>f&&(f=Math.max(f+e,0));f<e;f++){var g=d[f];if(g===b||Object.is(g,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ca(this,b,"includes").indexOf(b,c||0)}});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)w(b,d)&&c.push([d,b[d]]);return c}});
t("WeakMap",function(a){function b(k){this.f=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!w(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m["delete"](k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!w(k,g))throw Error("WeakMap key fail: "+k);k[g][this.f]=l;return this};
b.prototype.get=function(k){return d(k)&&w(k,g)?k[g][this.f]:void 0};
b.prototype.has=function(k){return d(k)&&w(k,g)&&w(k[g],this.f)};
b.prototype["delete"]=function(k){return d(k)&&w(k,g)&&w(k[g],this.f)?delete k[g][this.f]:!1};
return b});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.f;return ea(function(){if(l){for(;l.head!=h.f;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.g[l];if(m&&w(h.g,l))for(var p=0;p<m.length;p++){var q=m[p];if(k!==k&&q.key!==q.key||k===q.key)return{id:l,list:m,index:p,C:q}}return{id:l,list:m,index:-1,C:void 0}}
function e(h){this.g={};this.f=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.g[l.id]=[]);l.C?l.C.value=k:(l.C={next:this.f,previous:this.f.previous,head:this.f,key:h,value:k},l.list.push(l.C),this.f.previous.next=l.C,this.f.previous=l.C,this.size++);return this};
e.prototype["delete"]=function(h){h=d(this,h);return h.C&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.g[h.id],h.C.previous.next=h.C.next,h.C.next.previous=h.C.previous,h.C.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.g={};this.f=this.f.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).C};
e.prototype.get=function(h){return(h=d(this,h).C)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
t("Set",function(a){function b(c){this.f=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.f.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.f.set(c,c);this.size=this.f.size;return this};
b.prototype["delete"]=function(c){c=this.f["delete"](c);this.size=this.f.size;return c};
b.prototype.clear=function(){this.f.clear();this.size=0};
b.prototype.has=function(c){return this.f.has(c)};
b.prototype.entries=function(){return this.f.entries()};
b.prototype.values=function(){return this.f.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.f.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)w(b,d)&&c.push(b[d]);return c}});
var x=this||self;function y(a,b,c){a=a.split(".");c=c||x;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Fa(a){if(a&&a!=x)return Ga(a.document);null===Ha&&(Ha=Ga(x.document));return Ha}
var Ia=/^[\w+/_-]+[=]{0,2}$/,Ha=null;function Ga(a){return(a=a.querySelector&&a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Ia.test(a)?a:""}
function z(a,b){for(var c=a.split("."),d=b||x,e=0;e<c.length;e++)if(d=d[c[e]],null==d)return null;return d}
function Ja(){}
function Ka(a){a.oa=void 0;a.getInstance=function(){return a.oa?a.oa:a.oa=new a}}
function La(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function C(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Na(a){return Object.prototype.hasOwnProperty.call(a,Oa)&&a[Oa]||(a[Oa]=++Pa)}
var Oa="closure_uid_"+(1E9*Math.random()>>>0),Pa=0;function Qa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ra(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function D(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?D=Qa:D=Ra;return D.apply(null,arguments)}
function Sa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function E(){return Date.now()}
function F(a,b){y(a,b,void 0)}
function G(a,b){function c(){}
c.prototype=b.prototype;a.J=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.dk=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ta(a){return a}
;function H(a){if(Error.captureStackTrace)Error.captureStackTrace(this,H);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
G(H,Error);H.prototype.name="CustomError";function Ua(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.h=!b&&/[?&]ae=1(&|$)/.test(a);this.i=!b&&/[?&]ae=2(&|$)/.test(a);if((this.f=/[?&]adurl=([^&]*)/.exec(a))&&this.f[1]){try{var c=decodeURIComponent(this.f[1])}catch(d){c=null}this.g=c}}
;function Va(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Wa=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},I=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Ya=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Za=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},$a=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
I(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function ab(a,b){a:{var c=a.length;for(var d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){c=e;break a}c=-1}return 0>c?null:"string"===typeof a?a.charAt(c):a[c]}
function bb(a,b){var c=Wa(a,b),d;(d=0<=c)&&Array.prototype.splice.call(a,c,1);return d}
function cb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function db(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function eb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function fb(a,b){var c=Ma(b),d=c?b:arguments;for(c=c?0:1;c<d.length;c++){if(null==a)return;a=a[d[c]]}return a}
function gb(a){var b=hb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ib(a){for(var b in a)return!1;return!0}
function jb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function kb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function lb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function mb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=mb(a[c]);return b}
var nb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function ob(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<nb.length;f++)c=nb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var pb;function qb(){if(void 0===pb){var a=null,b=x.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ta,createScript:Ta,createScriptURL:Ta})}catch(c){x.console&&x.console.error(c.message)}pb=a}else pb=a}return pb}
;function rb(a,b){this.f=b===sb?a:""}
rb.prototype.U=!0;rb.prototype.S=function(){return this.f.toString()};
rb.prototype.na=!0;rb.prototype.ka=function(){return 1};
function tb(a){if(a instanceof rb&&a.constructor===rb)return a.f;La(a);return"type_error:TrustedResourceUrl"}
var sb={};var ub=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function vb(a,b){if(b)a=a.replace(wb,"&amp;").replace(xb,"&lt;").replace(yb,"&gt;").replace(zb,"&quot;").replace(Ab,"&#39;").replace(Bb,"&#0;");else{if(!Cb.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(wb,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(xb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(yb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(zb,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(Ab,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(Bb,"&#0;"))}return a}
var wb=/&/g,xb=/</g,yb=/>/g,zb=/"/g,Ab=/'/g,Bb=/\x00/g,Cb=/[\x00&<>"']/;function Db(a,b){return a<b?-1:a>b?1:0}
;function J(a,b){this.f=b===Eb?a:""}
J.prototype.U=!0;J.prototype.S=function(){return this.f.toString()};
J.prototype.na=!0;J.prototype.ka=function(){return 1};
function Fb(a){if(a instanceof J&&a.constructor===J)return a.f;La(a);return"type_error:SafeUrl"}
var Gb=/^(?:audio\/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font\/\w+|image\/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video\/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\w+=(?:\w+|"[\w;,= ]+"))*$/i,Hb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Ib=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;function Jb(a){if(a instanceof J)return a;a="object"==typeof a&&a.U?a.S():String(a);Ib.test(a)||(a="about:invalid#zClosurez");return new J(a,Eb)}
var Eb={},Kb=new J("about:invalid#zClosurez",Eb);var Lb;a:{var Mb=x.navigator;if(Mb){var Nb=Mb.userAgent;if(Nb){Lb=Nb;break a}}Lb=""}function K(a){return-1!=Lb.indexOf(a)}
;function Ob(a,b,c){this.f=c===Pb?a:"";this.g=b}
Ob.prototype.na=!0;Ob.prototype.ka=function(){return this.g};
Ob.prototype.U=!0;Ob.prototype.S=function(){return this.f.toString()};
var Pb={};function Qb(a,b){var c=qb();c=c?c.createHTML(a):a;return new Ob(c,b,Pb)}
;function Rb(a,b){var c=b instanceof J?b:Jb(b);a.href=Fb(c)}
function Sb(a,b){a.src=tb(b);var c=Fa(a.ownerDocument&&a.ownerDocument.defaultView);c&&a.setAttribute("nonce",c)}
;function Tb(a){return a=vb(a,void 0)}
function Ub(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Vb=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^\\/?#]*)@)?([^\\/?#]*?)(?::([0-9]+))?(?=[\\/?#]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function Wb(a){return a?decodeURI(a):a}
function Xb(a){return Wb(a.match(Vb)[3]||null)}
function Yb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Yb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Zb(a){var b=[],c;for(c in a)Yb(c,a[c],b);return b.join("&")}
function $b(a,b){var c=Zb(b);if(c){var d=a.indexOf("#");0>d&&(d=a.length);var e=a.indexOf("?");if(0>e||e>d){e=d;var f=""}else f=a.substring(e+1,d);d=[a.substr(0,e),f,a.substr(d)];e=d[1];d[1]=c?e?e+"&"+c:c:e;c=d[0]+(d[1]?"?"+d[1]:"")+d[2]}else c=a;return c}
var ac=/#|$/;function bc(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function cc(a){cc[" "](a);return a}
cc[" "]=Ja;var dc=K("Opera"),ec=K("Trident")||K("MSIE"),fc=K("Edge"),gc=K("Gecko")&&!(-1!=Lb.toLowerCase().indexOf("webkit")&&!K("Edge"))&&!(K("Trident")||K("MSIE"))&&!K("Edge"),hc=-1!=Lb.toLowerCase().indexOf("webkit")&&!K("Edge");function ic(){var a=x.document;return a?a.documentMode:void 0}
var kc;a:{var lc="",mc=function(){var a=Lb;if(gc)return/rv:([^\);]+)(\)|;)/.exec(a);if(fc)return/Edge\/([\d\.]+)/.exec(a);if(ec)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(hc)return/WebKit\/(\S+)/.exec(a);if(dc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
mc&&(lc=mc?mc[1]:"");if(ec){var nc=ic();if(null!=nc&&nc>parseFloat(lc)){kc=String(nc);break a}}kc=lc}var oc=kc,pc={},qc;if(x.document&&ec){var rc=ic();qc=rc?rc:parseInt(oc,10)||void 0}else qc=void 0;var sc=qc;var tc=K("Firefox")||K("FxiOS"),uc=K("iPhone")&&!K("iPod")&&!K("iPad")||K("iPod"),vc=K("iPad");var wc={},xc=null;
function yc(a){var b=3;Ma(a);void 0===b&&(b=0);if(!xc){xc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));wc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===xc[h]&&(xc[h]=g)}}}b=wc[b];c=[];for(d=0;d<a.length;d+=3){var k=a[d],l=(e=d+1<a.length)?a[d+1]:0;h=(f=d+2<a.length)?a[d+2]:0;g=k>>2;k=(k&3)<<4|l>>4;l=(l&15)<<2|h>>6;h&=63;f||(h=64,e||(l=64));c.push(b[g],b[k],b[l]||"",b[h]||"")}return c.join("")}
;var L=window;function zc(a){var b=z("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||x.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Ac(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Bc[c])c=Bc[c];else{c=String(c);if(!Bc[c]){var f=/function\s+([^\(]+)/m.exec(c);Bc[c]=f?f[1]:"[Anonymous]"}c=Bc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return a}
function Ac(a,b){b||(b={});b[Cc(a)]=!0;var c=a.stack||"",d=a.ek;d&&!b[Cc(d)]&&(c+="\nCaused by: ",d.stack&&0==d.stack.indexOf(d.toString())||(c+="string"===typeof d?d:d.message+"\n"),c+=Ac(d,b));return c}
function Cc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Bc={};function Dc(a){this.f=a||{cookie:""}}
n=Dc.prototype;n.isEnabled=function(){return navigator.cookieEnabled};
n.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.nk;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ya}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);this.f.cookie=a+"="+b+(f?";domain="+f:"")+(g?";path="+g:"")+(0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString())+(d?";secure":"")+(null!=e?";samesite="+e:"")};
n.get=function(a,b){for(var c=a+"=",d=(this.f.cookie||"").split(";"),e=0,f;e<d.length;e++){f=ub(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ya:0,path:b,domain:c});return d};
n.isEmpty=function(){return!this.f.cookie};
n.clear=function(){for(var a=(this.f.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=ub(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Ec=new Dc("undefined"==typeof document?null:document);var Fc=!ec||9<=Number(sc);function Gc(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
n=Gc.prototype;n.clone=function(){return new Gc(this.x,this.y)};
n.equals=function(a){return a instanceof Gc&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
n.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
n.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
n.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};function Hc(a,b){this.width=a;this.height=b}
n=Hc.prototype;n.clone=function(){return new Hc(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.isEmpty=function(){return!(this.width*this.height)};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Ic(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Jc(a,b){eb(b,function(c,d){c&&"object"==typeof c&&c.U&&(c=c.S());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:Kc.hasOwnProperty(d)?a.setAttribute(Kc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var Kc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};
function Lc(a,b,c){var d=arguments,e=document,f=String(d[0]),g=d[1];if(!Fc&&g&&(g.name||g.type)){f=["<",f];g.name&&f.push(' name="',Tb(g.name),'"');if(g.type){f.push(' type="',Tb(g.type),'"');var h={};ob(h,g);delete h.type;g=h}f.push(">");f=f.join("")}f=Mc(e,f);g&&("string"===typeof g?f.className=g:Array.isArray(g)?f.className=g.join(" "):Jc(f,g));2<d.length&&Nc(e,f,d);return f}
function Nc(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ma(f)||C(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(C(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}I(g?cb(f):f,d)}}}
function Mc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Oc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Pc(a){var b=Qc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Rc(){var a=[];Pc(function(b){a.push(b)});
return a}
var Qc={Fb:"allow-forms",Gb:"allow-modals",Hb:"allow-orientation-lock",Ib:"allow-pointer-lock",Jb:"allow-popups",Kb:"allow-popups-to-escape-sandbox",Lb:"allow-presentation",Mb:"allow-same-origin",Nb:"allow-scripts",Ob:"allow-top-navigation",Pb:"allow-top-navigation-by-user-activation"},Sc=Va(function(){return Rc()});
function Tc(){var a=Mc(document,"IFRAME"),b={};I(Sc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;function M(){this.g=this.g;this.A=this.A}
M.prototype.g=!1;M.prototype.dispose=function(){this.g||(this.g=!0,this.u())};
function Uc(a,b){a.g?b():(a.A||(a.A=[]),a.A.push(b))}
M.prototype.u=function(){if(this.A)for(;this.A.length;)this.A.shift()()};
function Vc(a){a&&"function"==typeof a.dispose&&a.dispose()}
function Wc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ma(d)?Wc.apply(null,d):Vc(d)}}
;var Xc={};function Yc(){}
function Zc(a,b){if(b!==Xc)throw Error("Bad secret");this.f=a}
v(Zc,Yc);Zc.prototype.toString=function(){return this.f};new Zc("about:blank",Xc);new Zc("about:invalid#zTSz",Xc);function $c(a){ad();var b=qb();a=b?b.createScriptURL(a):a;return new rb(a,sb)}
var ad=Ja;function bd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var cd=(new Date).getTime();function dd(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));a=a.substring(0,a.indexOf("://"));if("http"!==a&&"https"!==a&&"chrome-extension"!==a&&"moz-extension"!==a&&"file"!==a&&"android-app"!==a&&"chrome-search"!==a&&"chrome-untrusted"!==a&&"chrome"!==a&&"app"!==a&&"devtools"!==a)throw Error("Invalid URI scheme in origin: "+
a);c="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===a&&"80"!==e||"https"===a&&"443"!==e)c=":"+e}return a+"://"+b+c}
;function ed(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(p){for(var q=g,r=0;64>r;r+=4)q[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=q[r-3]^q[r-8]^q[r-14]^q[r-16],q[r]=(p<<1|p>>>31)&4294967295;p=e[0];var A=e[1],B=e[2],U=e[3],Fd=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var Xa=U^A&(B^U);var jc=1518500249}else Xa=A^B^U,jc=1859775393;else 60>r?(Xa=A&B|U&(A|B),jc=2400959708):(Xa=A^B^U,jc=3395469782);Xa=((p<<5|p>>>27)&4294967295)+Xa+Fd+jc+q[r]&4294967295;Fd=U;U=B;B=(A<<30|A>>>2)&4294967295;A=p;p=Xa}e[0]=e[0]+p&4294967295;e[1]=e[1]+
A&4294967295;e[2]=e[2]+B&4294967295;e[3]=e[3]+U&4294967295;e[4]=e[4]+Fd&4294967295}
function c(p,q){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],A=0,B=p.length;A<B;++A)r.push(p.charCodeAt(A));p=r}q||(q=p.length);r=0;if(0==l)for(;r+64<q;)b(p.slice(r,r+64)),r+=64,m+=64;for(;r<q;)if(f[l++]=p[r++],m++,64==l)for(l=0,b(f);r+64<q;)b(p.slice(r,r+64)),r+=64,m+=64}
function d(){var p=[],q=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=q&255,q>>>=8;b(f);for(r=q=0;5>r;r++)for(var A=24;0<=A;A-=8)p[q++]=e[r]>>A&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Ka:function(){for(var p=d(),q="",r=0;r<p.length;r++)q+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return q}}}
;function fd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],I(d,function(h){e.push(h)}),gd(e.join(" "));
var f=[],g=[];I(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];I(d,function(h){e.push(h)});
a=gd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function gd(a){var b=ed();b.update(a);return b.Ka().toLowerCase()}
;function hd(a){var b=dd(String(x.location.href)),c;(c=x.__SAPISID||x.__APISID||x.__OVERRIDE_SID)?c=!0:(c=new Dc(document),c=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID"),c=!!c);if(c&&(c=(b=0==b.indexOf("https:")||0==b.indexOf("chrome-extension:")||0==b.indexOf("moz-extension:"))?x.__SAPISID:x.__APISID,c||(c=new Dc(document),c=c.get(b?"SAPISID":"APISID")||c.get("__Secure-3PAPISID")),c)){b=b?"SAPISIDHASH":"APISIDHASH";var d=String(x.location.href);return d&&c&&b?[b,fd(dd(d),
c,a||null)].join(" "):null}return null}
;function id(){this.g=[];this.f=-1}
id.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.g[a]!=b&&(this.g[a]=b,this.f=-1)};
id.prototype.get=function(a){return!!this.g[a]};
function jd(a){-1==a.f&&(a.f=$a(a.g,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.f}
;function kd(a,b){this.h=a;this.i=b;this.g=0;this.f=null}
kd.prototype.get=function(){if(0<this.g){this.g--;var a=this.f;this.f=a.next;a.next=null}else a=this.h();return a};
function ld(a,b){a.i(b);100>a.g&&(a.g++,b.next=a.f,a.f=b)}
;function md(a){x.setTimeout(function(){throw a;},0)}
var nd;
function od(){var a=x.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!K("Presto")&&(a=function(){var e=Mc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=D(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!K("Trident")&&!K("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.ua;c.ua=null;e()}};
return function(e){d.next={ua:e};d=d.next;b.port2.postMessage(0)}}return function(e){x.setTimeout(e,0)}}
;function pd(){this.g=this.f=null}
var rd=new kd(function(){return new qd},function(a){a.reset()});
pd.prototype.add=function(a,b){var c=rd.get();c.set(a,b);this.g?this.g.next=c:this.f=c;this.g=c};
pd.prototype.remove=function(){var a=null;this.f&&(a=this.f,this.f=this.f.next,this.f||(this.g=null),a.next=null);return a};
function qd(){this.next=this.scope=this.f=null}
qd.prototype.set=function(a,b){this.f=a;this.scope=b;this.next=null};
qd.prototype.reset=function(){this.next=this.scope=this.f=null};function sd(a,b){td||ud();vd||(td(),vd=!0);wd.add(a,b)}
var td;function ud(){if(x.Promise&&x.Promise.resolve){var a=x.Promise.resolve(void 0);td=function(){a.then(xd)}}else td=function(){var b=xd;
"function"!==typeof x.setImmediate||x.Window&&x.Window.prototype&&!K("Edge")&&x.Window.prototype.setImmediate==x.setImmediate?(nd||(nd=od()),nd(b)):x.setImmediate(b)}}
var vd=!1,wd=new pd;function xd(){for(var a;a=wd.remove();){try{a.f.call(a.scope)}catch(b){md(b)}ld(rd,a)}vd=!1}
;function yd(){this.g=-1}
;function zd(){this.g=64;this.f=[];this.l=[];this.m=[];this.i=[];this.i[0]=128;for(var a=1;a<this.g;++a)this.i[a]=0;this.j=this.h=0;this.reset()}
G(zd,yd);zd.prototype.reset=function(){this.f[0]=1732584193;this.f[1]=4023233417;this.f[2]=2562383102;this.f[3]=271733878;this.f[4]=3285377520;this.j=this.h=0};
function Ad(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.f[0];c=a.f[1];var g=a.f[2],h=a.f[3],k=a.f[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.f[0]=a.f[0]+b&4294967295;a.f[1]=a.f[1]+c&4294967295;a.f[2]=a.f[2]+g&4294967295;a.f[3]=a.f[3]+h&4294967295;a.f[4]=a.f[4]+k&4294967295}
zd.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.g,d=0,e=this.l,f=this.h;d<b;){if(0==f)for(;d<=c;)Ad(this,a,d),d+=this.g;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.g){Ad(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.g){Ad(this,e);f=0;break}}this.h=f;this.j+=b}};
zd.prototype.digest=function(){var a=[],b=8*this.j;56>this.h?this.update(this.i,56-this.h):this.update(this.i,this.g-(this.h-56));for(var c=this.g-1;56<=c;c--)this.l[c]=b&255,b/=256;Ad(this,this.l);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.f[c]>>d&255,++b;return a};var Bd="StopIteration"in x?x.StopIteration:{message:"StopIteration",stack:""};function Cd(){}
Cd.prototype.next=function(){throw Bd;};
Cd.prototype.K=function(){return this};
function Dd(a){if(a instanceof Cd)return a;if("function"==typeof a.K)return a.K(!1);if(Ma(a)){var b=0,c=new Cd;c.next=function(){for(;;){if(b>=a.length)throw Bd;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function Ed(a,b){if(Ma(a))try{I(a,b,void 0)}catch(c){if(c!==Bd)throw c;}else{a=Dd(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==Bd)throw c;}}}
function Gd(a){if(Ma(a))return cb(a);a=Dd(a);var b=[];Ed(a,function(c){b.push(c)});
return b}
;function Hd(a,b){this.h={};this.f=[];this.N=this.g=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Hd)for(c=Id(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Id(a){Jd(a);return a.f.concat()}
n=Hd.prototype;n.equals=function(a,b){if(this===a)return!0;if(this.g!=a.g)return!1;var c=b||Kd;Jd(this);for(var d,e=0;d=this.f[e];e++)if(!c(this.get(d),a.get(d)))return!1;return!0};
function Kd(a,b){return a===b}
n.isEmpty=function(){return 0==this.g};
n.clear=function(){this.h={};this.N=this.g=this.f.length=0};
n.remove=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)?(delete this.h[a],this.g--,this.N++,this.f.length>2*this.g&&Jd(this),!0):!1};
function Jd(a){if(a.g!=a.f.length){for(var b=0,c=0;b<a.f.length;){var d=a.f[b];Object.prototype.hasOwnProperty.call(a.h,d)&&(a.f[c++]=d);b++}a.f.length=c}if(a.g!=a.f.length){var e={};for(c=b=0;b<a.f.length;)d=a.f[b],Object.prototype.hasOwnProperty.call(e,d)||(a.f[c++]=d,e[d]=1),b++;a.f.length=c}}
n.get=function(a,b){return Object.prototype.hasOwnProperty.call(this.h,a)?this.h[a]:b};
n.set=function(a,b){Object.prototype.hasOwnProperty.call(this.h,a)||(this.g++,this.f.push(a),this.N++);this.h[a]=b};
n.forEach=function(a,b){for(var c=Id(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
n.clone=function(){return new Hd(this)};
n.K=function(a){Jd(this);var b=0,c=this.N,d=this,e=new Cd;e.next=function(){if(c!=d.N)throw Error("The map has changed since the iterator was created");if(b>=d.f.length)throw Bd;var f=d.f[b++];return a?f:d.h[f]};
return e};function Ld(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Md(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Nd(a,b){if(a.classList)var c=a.classList.contains(b);else c=a.classList?a.classList:Ld(a).match(/\S+/g)||[],c=0<=Wa(c,b);return c}
function Od(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Nd(a,"inverted-hdpi")&&Md(a,Ya(a.classList?a.classList:Ld(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var Pd=!ec||9<=Number(sc),Qd;
if(Qd=ec){var Rd;if(Object.prototype.hasOwnProperty.call(pc,"9"))Rd=pc["9"];else{for(var Sd=0,Td=ub(String(oc)).split("."),Ud=ub("9").split("."),Vd=Math.max(Td.length,Ud.length),Wd=0;0==Sd&&Wd<Vd;Wd++){var Xd=Td[Wd]||"",Yd=Ud[Wd]||"";do{var Zd=/(\d*)(\D*)(.*)/.exec(Xd)||["","","",""],$d=/(\d*)(\D*)(.*)/.exec(Yd)||["","","",""];if(0==Zd[0].length&&0==$d[0].length)break;Sd=Db(0==Zd[1].length?0:parseInt(Zd[1],10),0==$d[1].length?0:parseInt($d[1],10))||Db(0==Zd[2].length,0==$d[2].length)||Db(Zd[2],$d[2]);
Xd=Zd[3];Yd=$d[3]}while(0==Sd)}Rd=pc["9"]=0<=Sd}Qd=!Rd}var ae=Qd,be=function(){if(!x.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{x.addEventListener("test",Ja,b),x.removeEventListener("test",Ja,b)}catch(c){}return a}();function ce(a,b){this.type=a;this.f=this.target=b;this.defaultPrevented=this.g=!1}
ce.prototype.stopPropagation=function(){this.g=!0};
ce.prototype.preventDefault=function(){this.defaultPrevented=!0};function de(a,b){ce.call(this,a?a.type:"");this.relatedTarget=this.f=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.h=null;a&&this.init(a,b)}
G(de,ce);var ee={2:"touch",3:"pen",4:"mouse"};
de.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.f=b;var e=a.relatedTarget;if(e){if(gc){a:{try{cc(e.nodeName);var f=!0;break a}catch(g){}f=!1}f||(e=null)}}else"mouseover"==c?e=a.fromElement:"mouseout"==c&&(e=a.toElement);this.relatedTarget=e;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:ee[a.pointerType]||"";this.state=a.state;
this.h=a;a.defaultPrevented&&this.preventDefault()};
de.prototype.stopPropagation=function(){de.J.stopPropagation.call(this);this.h.stopPropagation?this.h.stopPropagation():this.h.cancelBubble=!0};
de.prototype.preventDefault=function(){de.J.preventDefault.call(this);var a=this.h;if(a.preventDefault)a.preventDefault();else if(a.returnValue=!1,ae)try{if(a.ctrlKey||112<=a.keyCode&&123>=a.keyCode)a.keyCode=-1}catch(b){}};var fe="closure_listenable_"+(1E6*Math.random()|0),ge=0;function he(a,b,c,d,e){this.listener=a;this.f=null;this.src=b;this.type=c;this.capture=!!d;this.ha=e;this.key=++ge;this.V=this.fa=!1}
function ie(a){a.V=!0;a.listener=null;a.f=null;a.src=null;a.ha=null}
;function je(a){this.src=a;this.listeners={};this.f=0}
je.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.f++);var g=ke(a,b,d,e);-1<g?(b=a[g],c||(b.fa=!1)):(b=new he(b,this.src,f,!!d,e),b.fa=c,a.push(b));return b};
je.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=ke(e,b,c,d);return-1<b?(ie(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.f--),!0):!1};
function le(a,b){var c=b.type;c in a.listeners&&bb(a.listeners[c],b)&&(ie(b),0==a.listeners[c].length&&(delete a.listeners[c],a.f--))}
function ke(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.V&&f.listener==b&&f.capture==!!c&&f.ha==d)return e}return-1}
;var me="closure_lm_"+(1E6*Math.random()|0),ne={},oe=0;function pe(a,b,c,d,e){if(d&&d.once)qe(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)pe(a,b[f],c,d,e);else c=re(c),a&&a[fe]?a.f.add(String(b),c,!1,C(d)?!!d.capture:!!d,e):se(a,b,c,!1,d,e)}
function se(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=C(e)?!!e.capture:!!e,h=te(a);h||(a[me]=h=new je(a));c=h.add(b,c,d,g,f);if(!c.f){d=ue();c.f=d;d.src=a;d.listener=c;if(a.addEventListener)be||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ve(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");oe++}}
function ue(){var a=we,b=Pd?function(c){return a.call(b.src,b.listener,c)}:function(c){c=a.call(b.src,b.listener,c);
if(!c)return c};
return b}
function qe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)qe(a,b[f],c,d,e);else c=re(c),a&&a[fe]?a.f.add(String(b),c,!0,C(d)?!!d.capture:!!d,e):se(a,b,c,!0,d,e)}
function xe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)xe(a,b[f],c,d,e);else(d=C(d)?!!d.capture:!!d,c=re(c),a&&a[fe])?a.f.remove(String(b),c,d,e):a&&(a=te(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=ke(b,c,d,e)),(c=-1<a?b[a]:null)&&ye(c))}
function ye(a){if("number"!==typeof a&&a&&!a.V){var b=a.src;if(b&&b[fe])le(b.f,a);else{var c=a.type,d=a.f;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ve(c),d):b.addListener&&b.removeListener&&b.removeListener(d);oe--;(c=te(b))?(le(c,a),0==c.f&&(c.src=null,b[me]=null)):ie(a)}}}
function ve(a){return a in ne?ne[a]:ne[a]="on"+a}
function ze(a,b,c,d){var e=!0;if(a=te(a))if(b=a.listeners[b.toString()])for(b=b.concat(),a=0;a<b.length;a++){var f=b[a];f&&f.capture==c&&!f.V&&(f=Ae(f,d),e=e&&!1!==f)}return e}
function Ae(a,b){var c=a.listener,d=a.ha||a.src;a.fa&&ye(a);return c.call(d,b)}
function we(a,b){if(a.V)return!0;if(!Pd){var c=b||z("window.event"),d=new de(c,this),e=!0;if(!(0>c.keyCode||void 0!=c.returnValue)){a:{var f=!1;if(0==c.keyCode)try{c.keyCode=-1;break a}catch(k){f=!0}if(f||void 0==c.returnValue)c.returnValue=!0}c=[];for(f=d.f;f;f=f.parentNode)c.push(f);f=a.type;for(var g=c.length-1;!d.g&&0<=g;g--){d.f=c[g];var h=ze(c[g],f,!0,d);e=e&&h}for(g=0;!d.g&&g<c.length;g++)d.f=c[g],h=ze(c[g],f,!1,d),e=e&&h}return e}return Ae(a,new de(b,this))}
function te(a){a=a[me];return a instanceof je?a:null}
var Be="__closure_events_fn_"+(1E9*Math.random()>>>0);function re(a){if("function"===typeof a)return a;a[Be]||(a[Be]=function(b){return a.handleEvent(b)});
return a[Be]}
;function Ce(){M.call(this);this.f=new je(this);this.j=this;this.i=null}
G(Ce,M);Ce.prototype[fe]=!0;Ce.prototype.addEventListener=function(a,b,c,d){pe(this,a,b,c,d)};
Ce.prototype.removeEventListener=function(a,b,c,d){xe(this,a,b,c,d)};
Ce.prototype.dispatchEvent=function(a){var b=this.i;if(b){var c=[];for(var d=1;b;b=b.i)c.push(b),++d}b=this.j;d=a.type||a;if("string"===typeof a)a=new ce(a,b);else if(a instanceof ce)a.target=a.target||b;else{var e=a;a=new ce(d,b);ob(a,e)}e=!0;if(c)for(var f=c.length-1;!a.g&&0<=f;f--){var g=a.f=c[f];e=De(g,d,!0,a)&&e}a.g||(g=a.f=b,e=De(g,d,!0,a)&&e,a.g||(e=De(g,d,!1,a)&&e));if(c)for(f=0;!a.g&&f<c.length;f++)g=a.f=c[f],e=De(g,d,!1,a)&&e;return e};
Ce.prototype.u=function(){Ce.J.u.call(this);if(this.f){var a=this.f,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,ie(d[e]);delete a.listeners[c];a.f--}}this.i=null};
function De(a,b,c,d){b=a.f.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.V&&g.capture==c){var h=g.listener,k=g.ha||g.src;g.fa&&le(a.f,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ee(a){var b=[];Fe(new Ge,a,b);return b.join("")}
function Ge(){}
function Fe(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Fe(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),He(d,c),c.push(":"),Fe(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":He(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Ie={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Je=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function He(a,b){b.push('"',a.replace(Je,function(c){var d=Ie[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Ie[c]=d);return d}),'"')}
;function Ke(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function N(a){this.f=0;this.m=void 0;this.i=this.g=this.h=null;this.j=this.l=!1;if(a!=Ja)try{var b=this;a.call(void 0,function(c){Le(b,2,c)},function(c){Le(b,3,c)})}catch(c){Le(this,3,c)}}
function Me(){this.next=this.context=this.onRejected=this.g=this.f=null;this.h=!1}
Me.prototype.reset=function(){this.context=this.onRejected=this.g=this.f=null;this.h=!1};
var Ne=new kd(function(){return new Me},function(a){a.reset()});
function Oe(a,b,c){var d=Ne.get();d.g=a;d.onRejected=b;d.context=c;return d}
function Pe(a){return new N(function(b,c){c(a)})}
function Qe(a,b,c){Re(a,b,c,null)||sd(Sa(b,a))}
function Se(a){return new N(function(b,c){var d=a.length,e=[];if(d)for(var f=function(l,m){d--;e[l]=m;0==d&&b(e)},g=function(l){c(l)},h=0,k;h<a.length;h++)k=a[h],Qe(k,Sa(f,h),g);
else b(e)})}
N.prototype.then=function(a,b,c){return Te(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
N.prototype.$goog_Thenable=!0;function Ue(a,b){return Te(a,null,b,void 0)}
N.prototype.cancel=function(a){if(0==this.f){var b=new Ve(a);sd(function(){We(this,b)},this)}};
function We(a,b){if(0==a.f)if(a.h){var c=a.h;if(c.g){for(var d=0,e=null,f=null,g=c.g;g&&(g.h||(d++,g.f==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.f&&1==d?We(c,b):(f?(d=f,d.next==c.i&&(c.i=d),d.next=d.next.next):Xe(c),Ye(c,e,3,b)))}a.h=null}else Le(a,3,b)}
function Ze(a,b){a.g||2!=a.f&&3!=a.f||$e(a);a.i?a.i.next=b:a.g=b;a.i=b}
function Te(a,b,c,d){var e=Oe(null,null,null);e.f=new N(function(f,g){e.g=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Ve?g(h):f(k)}catch(l){g(l)}}:g});
e.f.h=a;Ze(a,e);return e.f}
N.prototype.o=function(a){this.f=0;Le(this,2,a)};
N.prototype.B=function(a){this.f=0;Le(this,3,a)};
function Le(a,b,c){0==a.f&&(a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself")),a.f=1,Re(c,a.o,a.B,a)||(a.m=c,a.f=b,a.h=null,$e(a),3!=b||c instanceof Ve||af(a,c)))}
function Re(a,b,c,d){if(a instanceof N)return Ze(a,Oe(b||Ja,c||null,d)),!0;if(Ke(a))return a.then(b,c,d),!0;if(C(a))try{var e=a.then;if("function"===typeof e)return bf(a,e,b,c,d),!0}catch(f){return c.call(d,f),!0}return!1}
function bf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function $e(a){a.l||(a.l=!0,sd(a.A,a))}
function Xe(a){var b=null;a.g&&(b=a.g,a.g=b.next,b.next=null);a.g||(a.i=null);return b}
N.prototype.A=function(){for(var a;a=Xe(this);)Ye(this,a,this.f,this.m);this.l=!1};
function Ye(a,b,c,d){if(3==c&&b.onRejected&&!b.h)for(;a&&a.j;a=a.h)a.j=!1;if(b.f)b.f.h=null,cf(b,c,d);else try{b.h?b.g.call(b.context):cf(b,c,d)}catch(e){df.call(null,e)}ld(Ne,b)}
function cf(a,b,c){2==b?a.g.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function af(a,b){a.j=!0;sd(function(){a.j&&df.call(null,b)})}
var df=md;function Ve(a){H.call(this,a)}
G(Ve,H);Ve.prototype.name="cancel";function O(a){M.call(this);this.l=1;this.i=[];this.j=0;this.f=[];this.h={};this.m=!!a}
G(O,M);n=O.prototype;n.subscribe=function(a,b,c){var d=this.h[a];d||(d=this.h[a]=[]);var e=this.l;this.f[e]=a;this.f[e+1]=b;this.f[e+2]=c;this.l=e+3;d.push(e);return e};
function ef(a,b,c,d){if(b=a.h[b]){var e=a.f;(b=ab(b,function(f){return e[f+1]==c&&e[f+2]==d}))&&a.W(b)}}
n.W=function(a){var b=this.f[a];if(b){var c=this.h[b];0!=this.j?(this.i.push(a),this.f[a+1]=Ja):(c&&bb(c,a),delete this.f[a],delete this.f[a+1],delete this.f[a+2])}return!!b};
n.T=function(a,b){var c=this.h[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.m)for(e=0;e<c.length;e++){var g=c[e];ff(this.f[g+1],this.f[g+2],d)}else{this.j++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.f[g+1].apply(this.f[g+2],d)}finally{if(this.j--,0<this.i.length&&0==this.j)for(;c=this.i.pop();)this.W(c)}}return 0!=e}return!1};
function ff(a,b,c){sd(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.h[a];b&&(I(b,this.W,this),delete this.h[a])}else this.f.length=0,this.h={}};
n.u=function(){O.J.u.call(this);this.clear();this.i.length=0};function gf(a){this.f=a}
gf.prototype.set=function(a,b){void 0===b?this.f.remove(a):this.f.set(a,Ee(b))};
gf.prototype.get=function(a){try{var b=this.f.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
gf.prototype.remove=function(a){this.f.remove(a)};function hf(a){this.f=a}
G(hf,gf);function jf(a){this.data=a}
function kf(a){return void 0===a||a instanceof jf?a:new jf(a)}
hf.prototype.set=function(a,b){hf.J.set.call(this,a,kf(b))};
hf.prototype.g=function(a){a=hf.J.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
hf.prototype.get=function(a){if(a=this.g(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function lf(a){this.f=a}
G(lf,hf);lf.prototype.set=function(a,b,c){if(b=kf(b)){if(c){if(c<E()){lf.prototype.remove.call(this,a);return}b.expiration=c}b.creation=E()}lf.J.set.call(this,a,b)};
lf.prototype.g=function(a){var b=lf.J.g.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<E()||c&&c>E())lf.prototype.remove.call(this,a);else return b}};function mf(){}
;function nf(){}
G(nf,mf);nf.prototype.clear=function(){var a=Gd(this.K(!0)),b=this;I(a,function(c){b.remove(c)})};function of(a){this.f=a}
G(of,nf);n=of.prototype;n.isAvailable=function(){if(!this.f)return!1;try{return this.f.setItem("__sak","1"),this.f.removeItem("__sak"),!0}catch(a){return!1}};
n.set=function(a,b){try{this.f.setItem(a,b)}catch(c){if(0==this.f.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){a=this.f.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.f.removeItem(a)};
n.K=function(a){var b=0,c=this.f,d=new Cd;d.next=function(){if(b>=c.length)throw Bd;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
n.clear=function(){this.f.clear()};
n.key=function(a){return this.f.key(a)};function pf(){var a=null;try{a=window.localStorage||null}catch(b){}this.f=a}
G(pf,of);function qf(a,b){this.g=a;this.f=null;if(ec&&!(9<=Number(sc))){rf||(rf=new Hd);this.f=rf.get(a);this.f||(b?this.f=document.getElementById(b):(this.f=document.createElement("userdata"),this.f.addBehavior("#default#userData"),document.body.appendChild(this.f)),rf.set(a,this.f));try{this.f.load(this.g)}catch(c){this.f=null}}}
G(qf,nf);var sf={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},rf=null;function tf(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return sf[b]})}
n=qf.prototype;n.isAvailable=function(){return!!this.f};
n.set=function(a,b){this.f.setAttribute(tf(a),b);uf(this)};
n.get=function(a){a=this.f.getAttribute(tf(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.f.removeAttribute(tf(a));uf(this)};
n.K=function(a){var b=0,c=this.f.XMLDocument.documentElement.attributes,d=new Cd;d.next=function(){if(b>=c.length)throw Bd;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
n.clear=function(){for(var a=this.f.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);uf(this)};
function uf(a){try{a.f.save(a.g)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function vf(a,b){this.g=a;this.f=b+"::"}
G(vf,nf);vf.prototype.set=function(a,b){this.g.set(this.f+a,b)};
vf.prototype.get=function(a){return this.g.get(this.f+a)};
vf.prototype.remove=function(a){this.g.remove(this.f+a)};
vf.prototype.K=function(a){var b=this.g.K(!0),c=this,d=new Cd;d.next=function(){for(var e=b.next();e.substr(0,c.f.length)!=c.f;)e=b.next();return a?e.substr(c.f.length):c.g.get(e)};
return d};function wf(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var xf=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};y("yt.config_",xf,void 0);function P(a){wf(xf,arguments)}
function Q(a,b){return a in xf?xf[a]:b}
function yf(){return Q("PLAYER_CONFIG",{})}
;var zf=[];function Af(a){zf.forEach(function(b){return b(a)})}
function Bf(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Cf(b),Af(b)}}:a}
function Cf(a){var b=z("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0):(b=Q("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0]),P("ERRORS",b))}
function Df(a){var b=z("yt.logging.errors.log");b?b(a,"WARNING",void 0,void 0,void 0):(b=Q("ERRORS",[]),b.push([a,"WARNING",void 0,void 0,void 0]),P("ERRORS",b))}
;var Ef=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};y("yt.msgs_",Ef,void 0);function Ff(a){wf(Ef,arguments)}
;function Gf(a,b,c,d){Ec.set(""+a,b,{ya:c,path:"/",domain:void 0===d?"youtube.com":d,secure:!1})}
;function R(a){a=Hf(a);return"string"===typeof a&&"false"===a?!1:!!a}
function If(a,b){var c=Hf(a);return void 0===c&&void 0!==b?b:Number(c||0)}
function Hf(a){var b=Q("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:Q("EXPERIMENT_FLAGS",{})[a]}
;function Jf(a){a&&(a.dataset?a.dataset[Kf("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Lf(a,b){return a?a.dataset?a.dataset[Kf(b)]:a.getAttribute("data-"+b):null}
var Mf={};function Kf(a){return Mf[a]||(Mf[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;function S(a,b){"function"===typeof a&&(a=Bf(a));return window.setTimeout(a,b)}
function Nf(a){window.clearTimeout(a)}
;var Of=x.ytPubsubPubsubInstance||new O,Pf=x.ytPubsubPubsubSubscribedKeys||{},Qf=x.ytPubsubPubsubTopicToKeys||{},Rf=x.ytPubsubPubsubIsSynchronous||{};function Sf(a,b){var c=Tf();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Pf[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Rf[a]?f():S(f,0)}catch(g){Cf(g)}},void 0);
Pf[d]=!0;Qf[a]||(Qf[a]=[]);Qf[a].push(d);return d}return 0}
function Uf(a){var b=Tf();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),I(a,function(c){b.unsubscribeByKey(c);delete Pf[c]}))}
function Vf(a,b){var c=Tf();c&&c.publish.apply(c,arguments)}
function Wf(a){var b=Tf();if(b)if(b.clear(a),a)Xf(a);else for(var c in Qf)Xf(c)}
function Tf(){return x.ytPubsubPubsubInstance}
function Xf(a){Qf[a]&&(a=Qf[a],I(a,function(b){Pf[b]&&delete Pf[b]}),a.length=0)}
O.prototype.subscribe=O.prototype.subscribe;O.prototype.unsubscribeByKey=O.prototype.W;O.prototype.publish=O.prototype.T;O.prototype.clear=O.prototype.clear;y("ytPubsubPubsubInstance",Of,void 0);y("ytPubsubPubsubTopicToKeys",Qf,void 0);y("ytPubsubPubsubIsSynchronous",Rf,void 0);y("ytPubsubPubsubSubscribedKeys",Pf,void 0);var Yf=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Zf=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function $f(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Yf,""),c=c.replace(Zf,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else ag(a,b,c)}
function ag(a,b,c){c=void 0===c?null:c;var d=bg(a),e=document.getElementById(d),f=e&&Lf(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Sf(d,b),b=""+Na(b),cg[b]=f),g||(e=dg(a,d,function(){Lf(e,"loaded")||(Jf(e),Vf(d),S(Sa(Wf,d),0))},c)))}
function dg(a,b,c,d){d=void 0===d?null:d;var e=Mc(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Sb(e,$c(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function eg(a){a=bg(a);var b=document.getElementById(a);b&&(Wf(a),b.parentNode.removeChild(b))}
function fg(a,b){if(a&&b){var c=""+Na(b);(c=cg[c])&&Uf(c)}}
function bg(a){var b=document.createElement("a");Rb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Ub(a)}
var cg={};function gg(){}
function hg(a,b){return ig(a,1,b)}
;function jg(){}
v(jg,gg);function ig(a,b,c){isNaN(c)&&(c=void 0);var d=z("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):S(a,c||0)}
jg.prototype.start=function(){var a=z("yt.scheduler.instance.start");a&&a()};
jg.prototype.pause=function(){var a=z("yt.scheduler.instance.pause");a&&a()};
Ka(jg);jg.getInstance();var kg=[],lg=!1;function mg(){if(!R("disable_ad_status_on_html5_clients")&&(!R("condition_ad_status_fetch_on_consent_cookie_html5_clients")||Ec.get("CONSENT","").startsWith("YES+"))&&"1"!=fb(yf(),"args","privembed")){var a=function(){lg=!0;"google_ad_status"in window?P("DCLKSTAT",1):P("DCLKSTAT",2)};
try{$f("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}kg.push(hg(function(){lg||"google_ad_status"in window||(fg("//static.doubleclick.net/instream/ad_status.js",a),lg=!0,P("DCLKSTAT",3))},5E3))}}
function ng(){return parseInt(Q("DCLKSTAT",0),10)}
;var og=0;y("ytDomDomGetNextId",z("ytDomDomGetNextId")||function(){return++og},void 0);var pg={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function qg(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in pg||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.f=a.pageX;this.g=a.pageY}}catch(e){}}
function rg(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.f=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.g=a.clientY+b}}
qg.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
qg.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
qg.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var hb=x.ytEventsEventsListeners||{};y("ytEventsEventsListeners",hb,void 0);var sg=x.ytEventsEventsCounter||{count:0};y("ytEventsEventsCounter",sg,void 0);
function tg(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return gb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=C(e[4])&&C(d)&&kb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var ug=Va(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function vg(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=tg(a,b,c,d);if(e)return e;e=++sg.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new qg(h);if(!Oc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new qg(h);
h.currentTarget=a;return c.call(a,h)};
g=Bf(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),ug()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);hb[e]=[a,b,c,g,d];return e}
function wg(a){a&&("string"==typeof a&&(a=[a]),I(a,function(b){if(b in hb){var c=hb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?ug()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete hb[b]}}))}
;var xg=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function yg(a){this.o=a;this.f=null;this.j=0;this.m=null;this.l=0;this.h=[];for(a=0;4>a;a++)this.h.push(0);this.i=0;this.G=vg(window,"mousemove",D(this.H,this));a=D(this.B,this);"function"===typeof a&&(a=Bf(a));this.I=window.setInterval(a,25)}
G(yg,M);yg.prototype.H=function(a){void 0===a.f&&rg(a);var b=a.f;void 0===a.g&&rg(a);this.f=new Gc(b,a.g)};
yg.prototype.B=function(){if(this.f){var a=xg();if(0!=this.j){var b=this.m,c=this.f,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.j);this.h[this.i]=.5<Math.abs((d-this.l)/this.l)?1:0;for(c=b=0;4>c;c++)b+=this.h[c]||0;3<=b&&this.o();this.l=d}this.j=a;this.m=this.f;this.i=(this.i+1)%4}};
yg.prototype.u=function(){window.clearInterval(this.I);wg(this.G)};var zg={};
function Ag(a){var b=void 0===a?{}:a;a=void 0===b.Ra?!0:b.Ra;b=void 0===b.gb?!1:b.gb;if(null==z("_lact",window)){var c=parseInt(Q("LACT"),10);c=isFinite(c)?E()-Math.max(c,0):-1;y("_lact",c,window);y("_fact",c,window);-1==c&&Bg();vg(document,"keydown",Bg);vg(document,"keyup",Bg);vg(document,"mousedown",Bg);vg(document,"mouseup",Bg);a&&(b?vg(window,"touchmove",function(){Cg("touchmove",200)},{passive:!0}):(vg(window,"resize",function(){Cg("resize",200)}),vg(window,"scroll",function(){Cg("scroll",200)})));
new yg(function(){Cg("mouse",100)});
vg(document,"touchstart",Bg,{passive:!0});vg(document,"touchend",Bg,{passive:!0})}}
function Cg(a,b){zg[a]||(zg[a]=!0,hg(function(){Bg();zg[a]=!1},b))}
function Bg(){null==z("_lact",window)&&Ag();var a=E();y("_lact",a,window);-1==z("_fact",window)&&y("_fact",a,window);(a=z("ytglobal.ytUtilActivityCallback_"))&&a()}
function Dg(){var a=z("_lact",window),b;null==a?b=-1:b=Math.max(E()-a,0);return b}
;var Eg=window,T=Eg.ytcsi&&Eg.ytcsi.now?Eg.ytcsi.now:Eg.performance&&Eg.performance.timing&&Eg.performance.now&&Eg.performance.timing.navigationStart?function(){return Eg.performance.timing.navigationStart+Eg.performance.now()}:function(){return(new Date).getTime()};var Fg=If("initial_gel_batch_timeout",1E3),Gg=Math.pow(2,16)-1,Hg=null,Ig=0,Jg=void 0,Kg=0,Lg=0,Mg=0,Ng=!0,Og=x.ytLoggingTransportGELQueue_||new Map;y("ytLoggingTransportGELQueue_",Og,void 0);var Pg=x.ytLoggingTransportTokensToCttTargetIds_||{};y("ytLoggingTransportTokensToCttTargetIds_",Pg,void 0);function Qg(a){a=void 0===a?!1:a;return new N(function(b){Nf(Kg);Nf(Lg);Lg=0;Jg&&Jg.isReady()?(Rg(b,a),Og.clear()):(Sg(),b())})}
function Sg(){R("web_gel_timeout_cap")&&!Lg&&(Lg=S(Qg,6E4));Nf(Kg);var a=Q("LOGGING_BATCH_TIMEOUT",If("web_gel_debounce_ms",1E4));R("shorten_initial_gel_batch_timeout")&&Ng&&(a=Fg);Kg=S(Qg,a)}
function Rg(a,b){var c=Jg;b=void 0===b?!1:b;for(var d=Math.round(T()),e=Og.size,f=u(Og),g=f.next();!g.done;g=f.next()){var h=u(g.value);g=h.next().value;var k=h.next().value;h=mb({context:Tg(c.F||Ug())});h.events=k;(k=Pg[g])&&Vg(h,g,k);delete Pg[g];Wg(h,d);Xg(c,"log_event",h,{retry:!0,onSuccess:function(){e--;e||a();Ig=Math.round(T()-d)},
onError:function(){e--;e||a()},
tb:b});Ng=!1}}
function Wg(a,b){a.requestTimeMs=String(b);R("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);var c=Q("EVENT_ID",void 0);if(c){var d=Q("BATCH_CLIENT_COUNTER",void 0)||0;!d&&R("web_client_counter_random_seed")&&(d=Math.floor(Math.random()*Gg/2));d++;d>Gg&&(d=1);P("BATCH_CLIENT_COUNTER",d);c={serializedEventId:c,clientCounter:String(d)};a.serializedClientEventId=c;Hg&&Ig&&R("log_gel_rtt_web")&&(a.previousBatchInfo={serializedClientEventId:Hg,roundtripMs:String(Ig)});Hg=c;Ig=0}}
function Vg(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
;var Yg=x.ytLoggingGelSequenceIdObj_||{};y("ytLoggingGelSequenceIdObj_",Yg,void 0);
function Zg(a,b,c,d){d=void 0===d?{}:d;var e={};e.eventTimeMs=Math.round(d.timestamp||T());e[a]=b;e.context={lastActivityMs:String(d.timestamp?-1:Dg())};R("log_sequence_info_on_gel_web")&&d.M&&(a=e.context,b=d.M,Yg[b]=b in Yg?Yg[b]+1:0,a.sequence={index:Yg[b],groupKey:b},d.La&&delete Yg[d.M]);d=d.L;a="";d&&(a={},d.videoId?a.videoId=d.videoId:d.playlistId&&(a.playlistId=d.playlistId),Pg[d.token]=a,a=d.token);d=Og.get(a)||[];Og.set(a,d);d.push(e);c&&(Jg=new c);c=If("web_logging_max_batch")||100;e=T();
d.length>=c?Qg(!0):10<=e-Mg&&(Sg(),Mg=e)}
;function $g(){var a=ah;z("yt.ads.biscotti.getId_")||y("yt.ads.biscotti.getId_",a,void 0)}
function bh(a){y("yt.ads.biscotti.lastId_",a,void 0)}
;var ch={q:!0,search_query:!0};function dh(a){for(var b=a.split("&"),c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=decodeURIComponent((f[0]||"").replace(/\+/g," ")),h=decodeURIComponent((f[1]||"").replace(/\+/g," "));g in c?Array.isArray(c[g])?db(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(k){ch.hasOwnProperty(f[0])||(k.args=[{key:f[0],value:f[1],query:a}],Cf(k))}}return c}
function eh(a){var b=[];eb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];I(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function fh(a){"?"==a.charAt(0)&&(a=a.substr(1));return dh(a)}
function gh(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=fh(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return $b(a,e)+d}
;function hh(a){var b=ih;a=void 0===a?z("yt.ads.biscotti.lastId_")||"":a;b=Object.assign(jh(b),kh(b));b.ca_type="image";a&&(b.bid=a);return b}
function jh(a){var b={};b.dt=cd;b.flash="0";a:{try{var c=a.f.top.location.href}catch(f){a=2;break a}a=c?c===a.g.location.href?0:1:2}b=(b.frm=a,b);b.u_tz=-(new Date).getTimezoneOffset();var d=void 0===d?L:d;try{var e=d.history.length}catch(f){e=0}b.u_his=e;b.u_java=!!L.navigator&&"unknown"!==typeof L.navigator.javaEnabled&&!!L.navigator.javaEnabled&&L.navigator.javaEnabled();L.screen&&(b.u_h=L.screen.height,b.u_w=L.screen.width,b.u_ah=L.screen.availHeight,b.u_aw=L.screen.availWidth,b.u_cd=L.screen.colorDepth);
L.navigator&&L.navigator.plugins&&(b.u_nplug=L.navigator.plugins.length);L.navigator&&L.navigator.mimeTypes&&(b.u_nmime=L.navigator.mimeTypes.length);return b}
function kh(a){var b=a.f;try{var c=b.screenX;var d=b.screenY}catch(p){}try{var e=b.outerWidth;var f=b.outerHeight}catch(p){}try{var g=b.innerWidth;var h=b.innerHeight}catch(p){}b=[b.screenLeft,b.screenTop,c,d,b.screen?b.screen.availWidth:void 0,b.screen?b.screen.availTop:void 0,e,f,g,h];c=a.f.top;try{var k=(c||window).document,l="CSS1Compat"==k.compatMode?k.documentElement:k.body;var m=(new Hc(l.clientWidth,l.clientHeight)).round()}catch(p){m=new Hc(-12245933,-12245933)}k=m;m={};l=new id;x.SVGElement&&
x.document.createElementNS&&l.set(0);c=Tc();c["allow-top-navigation-by-user-activation"]&&l.set(1);c["allow-popups-to-escape-sandbox"]&&l.set(2);x.crypto&&x.crypto.subtle&&l.set(3);x.TextDecoder&&x.TextEncoder&&l.set(4);l=jd(l);m.bc=l;m.bih=k.height;m.biw=k.width;m.brdim=b.join();a=a.g;return m.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[a.visibilityState||a.webkitVisibilityState||a.mozVisibilityState||""]||0,m.wgl=!!L.WebGLRenderingContext,m}
var ih=new function(){var a=window.document;this.f=window;this.g=a};
y("yt.ads_.signals_.getAdSignalsString",function(a){return eh(hh(a))},void 0);var lh="XMLHttpRequest"in x?function(){return new XMLHttpRequest}:null;
function mh(){if(!lh)return null;var a=lh();return"open"in a?a:null}
function nh(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var oh={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},ph="app debugcss debugjs expflag force_ad_params force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address client_dev_root_url".split(" "),
qh=!1;
function rh(a,b){b=void 0===b?{}:b;if(!c)var c=window.location.href;var d=a.match(Vb)[1]||null,e=Xb(a);d&&e?(d=c,c=a.match(Vb),d=d.match(Vb),c=c[3]==d[3]&&c[1]==d[1]&&c[4]==d[4]):c=e?Xb(c)==e&&(Number(c.match(Vb)[4]||null)||null)==(Number(a.match(Vb)[4]||null)||null):!0;d=R("web_ajax_ignore_global_headers_if_set");for(var f in oh)e=Q(oh[f]),!e||!c&&Xb(a)||d&&void 0!==b[f]||(b[f]=e);if(c||!Xb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());(c||!Xb(a))&&(f="undefined"!=typeof Intl?(new Intl.DateTimeFormat).resolvedOptions().timeZone:
null)&&(b["X-YouTube-Time-Zone"]=f);if(c||!Xb(a))b["X-YouTube-Ad-Signals"]=eh(hh(void 0));return b}
function sh(a){var b=window.location.search,c=Xb(a),d=Wb(a.match(Vb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=fh(b),f={};I(ph,function(g){e[g]&&(f[g]=e[g])});
return gh(a,f||{},!1)}
function th(a,b){if(window.fetch&&"XML"!=b.format){var c={method:b.method||"GET",credentials:"same-origin"};b.headers&&(c.headers=b.headers);a=uh(a,b);var d=vh(a,b);d&&(c.body=d);b.withCredentials&&(c.credentials="include");var e=!1,f;fetch(a,c).then(function(g){if(!e){e=!0;f&&Nf(f);var h=g.ok,k=function(l){l=l||{};var m=b.context||x;h?b.onSuccess&&b.onSuccess.call(m,l,g):b.onError&&b.onError.call(m,l,g);b.ra&&b.ra.call(m,l,g)};
"JSON"==(b.format||"JSON")&&(h||400<=g.status&&500>g.status)?g.json().then(k,function(){k(null)}):k(null)}});
b.Ca&&0<b.timeout&&(f=S(function(){e||(e=!0,Nf(f),b.Ca.call(b.context||x))},b.timeout))}else wh(a,b)}
function wh(a,b){var c=b.format||"JSON";a=uh(a,b);var d=vh(a,b),e=!1,f=xh(a,function(k){if(!e){e=!0;h&&Nf(h);var l=nh(k),m=null,p=400<=k.status&&500>k.status,q=500<=k.status&&600>k.status;if(l||p||q)m=yh(a,c,k,b.fk);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=!!m}m=m||{};p=b.context||x;l?b.onSuccess&&b.onSuccess.call(p,k,m):b.onError&&b.onError.call(p,k,m);b.ra&&b.ra.call(p,k,m)}},b.method,d,b.headers,b.responseType,
b.withCredentials);
if(b.X&&0<b.timeout){var g=b.X;var h=S(function(){e||(e=!0,f.abort(),Nf(h),g.call(b.context||x,f))},b.timeout)}return f}
function uh(a,b){b.ik&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=Q("XSRF_FIELD_NAME",void 0),d=b.sb;d&&(d[c]&&delete d[c],a=gh(a,d||{},!0));return a}
function vh(a,b){var c=Q("XSRF_FIELD_NAME",void 0),d=Q("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.D,g=Q("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.hk||Xb(a)&&!b.withCredentials&&Xb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.D&&b.D[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=fh(e),ob(e,f),e=b.Da&&"JSON"==b.Da?JSON.stringify(e):Zb(e));f=e||f&&!ib(f);!qh&&f&&"POST"!=b.method&&(qh=!0,Cf(Error("AJAX request with postData should use POST")));
return e}
function yh(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Df(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?zh(a):null)e={},I(a.getElementsByTagName("*"),function(g){e[g.tagName]=Ah(g)})}d&&Bh(e);
return e}
function Bh(a){if(C(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=Qb(a[b],null);a[c]=d}else Bh(a[b])}}
function zh(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ah(a){var b="";I(a.childNodes,function(c){b+=c.nodeValue});
return b}
function xh(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Bf(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=mh();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;R("debug_forward_web_query_parameters")&&(a=sh(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=rh(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function Ch(){for(var a={},b=u(Object.entries(fh(Q("DEVICE","")))),c=b.next();!c.done;c=b.next()){var d=u(c.value);c=d.next().value;d=d.next().value;"cbrand"===c?a.deviceMake=d:"cmodel"===c?a.deviceModel=d:"cbr"===c?a.browserName=d:"cbrver"===c?a.browserVersion=d:"cos"===c?a.osName=d:"cosver"===c?a.osVersion=d:"cplatform"===c&&(a.platform=d)}return a}
;function Dh(){return"INNERTUBE_API_KEY"in xf&&"INNERTUBE_API_VERSION"in xf}
function Ug(){return{innertubeApiKey:Q("INNERTUBE_API_KEY",void 0),innertubeApiVersion:Q("INNERTUBE_API_VERSION",void 0),Sa:Q("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ta:Q("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:Q("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Va:Q("INNERTUBE_CONTEXT_HL",void 0),Ua:Q("INNERTUBE_CONTEXT_GL",void 0),Wa:Q("INNERTUBE_HOST_OVERRIDE",void 0)||"",Ya:!!Q("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Xa:!!Q("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:Q("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function Tg(a){var b={client:{hl:a.Va,gl:a.Ua,clientName:a.Ta,clientVersion:a.innertubeContextClientVersion,configInfo:a.Sa}},c=window.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=Q("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=Q("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=Q("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});
a.appInstallData&&R("web_log_app_install_experiments")&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);Q("DELEGATED_SESSION_ID")&&!R("pageid_as_header_web")&&(b.user={onBehalfOfUser:Q("DELEGATED_SESSION_ID")});b.client=Object.assign(b.client,Ch());return b}
function Eh(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||Q("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.ck||Q("AUTHORIZATION"))||(a?b="Bearer "+z("gapi.auth.getToken")().bk:b=hd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=Q("SESSION_INDEX",0),R("pageid_as_header_web")&&(d["X-Goog-PageId"]=Q("DELEGATED_SESSION_ID")));return d}
;function Fh(a){a=Object.assign({},a);delete a.Authorization;var b=hd();if(b){var c=new zd;c.update(Q("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=yc(c.digest())}return a}
;function Gh(){var a=new pf;(a=a.isAvailable()?new vf(a,"yt.innertube"):null)||(a=new qf("yt.innertube"),a=a.isAvailable()?a:null);this.f=a?new lf(a):null;this.g=document.domain||window.location.hostname}
Gh.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.f)try{this.f.set(a,b,E()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Ee(b))}catch(f){return}else e=escape(b);Gf(a,e,c,this.g)};
Gh.prototype.get=function(a,b){var c=void 0,d=!this.f;if(!d)try{c=this.f.get(a)}catch(e){d=!0}if(d&&(c=Ec.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Gh.prototype.remove=function(a){this.f&&this.f.remove(a);var b=this.g;Ec.remove(""+a,"/",void 0===b?"youtube.com":b)};var Hh;function Ih(){Hh||(Hh=new Gh);return Hh}
function Jh(a,b,c,d){if(d)return null;d=Ih().get("nextId",!0)||1;var e=Ih().get("requests",!0)||{};e[d]={method:a,request:b,authState:Fh(c),requestTime:Math.round(T())};Ih().set("nextId",d+1,86400,!0);Ih().set("requests",e,86400,!0);return d}
function Kh(a){var b=Ih().get("requests",!0)||{};delete b[a];Ih().set("requests",b,86400,!0)}
function Lh(a){var b=Ih().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=Fh(Eh(!1));kb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),Xg(a,d.method,e,{}));delete b[c]}}Ih().set("requests",b,86400,!0)}}
;new Ce;var Mh=[],Nh=!1;function Oh(a,b){Nh||(Mh.push({type:"EVENT",eventType:a,payload:b}),10<Mh.length&&Mh.shift())}
;function Ph(a){if(!a)throw Error();throw a;}
function Qh(a){return a}
function V(a){var b=this;this.g=a;this.state={status:"PENDING"};this.f=[];this.onRejected=[];this.g(function(c){if("PENDING"===b.state.status){b.state={status:"FULFILLED",value:c};c=u(b.f);for(var d=c.next();!d.done;d=c.next())d=d.value,d()}},function(c){if("PENDING"===b.state.status){b.state={status:"REJECTED",
reason:c};c=u(b.onRejected);for(var d=c.next();!d.done;d=c.next())d=d.value,d()}})}
V.all=function(a){return new V(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={O:0};f.O<a.length;f={O:f.O},++f.O)Rh(V.resolve(a[f.O]).then(function(g){return function(h){d[g.O]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})})};
V.resolve=function(a){return new V(function(b,c){a instanceof V?a.then(b,c):b(a)})};
V.reject=function(a){return new V(function(b,c){c(a)})};
V.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:Qh,e=null!==b&&void 0!==b?b:Ph;return new V(function(f,g){"PENDING"===c.state.status?(c.f.push(function(){Sh(c,c,d,f,g)}),c.onRejected.push(function(){Th(c,c,e,f,g)})):"FULFILLED"===c.state.status?Sh(c,c,d,f,g):"REJECTED"===c.state.status&&Th(c,c,e,f,g)})};
function Rh(a,b){a.then(void 0,b)}
function Sh(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof V?Uh(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Th(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof V?Uh(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Uh(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof V?Uh(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Vh(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Wh(a){return new N(function(b,c){Vh(a,b,c)})}
function W(a){return new V(function(b,c){Vh(a,b,c)})}
;function Xh(a,b){return new V(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()})}
;function Yh(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(c instanceof Array?c:fa(u(c)))}
v(Yh,Error);var Zh={},$h=(Zh.AUTH_INVALID="No user identifier specified.",Zh.EXPLICIT_ABORT="Transaction was explicitly aborted.",Zh.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Zh.MISSING_OBJECT_STORE="Object store not created.",Zh.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Zh.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Zh.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Zh);
function ai(a,b,c){b=void 0===b?{}:b;c=void 0===c?$h[a]:c;Yh.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;Object.setPrototypeOf(this,ai.prototype);Nh||(Mh.push({type:"ERROR",payload:this}),10<Mh.length&&Mh.shift())}
v(ai,Yh);function bi(a,b,c){ai.call(this,"UNKNOWN_ABORT",{objectStoreNames:a,dbName:b,mode:c});Object.setPrototypeOf(this,bi.prototype)}
v(bi,ai);function ci(a){ai.call(this,"MISSING_OBJECT_STORE",{jk:a},$h.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,ci.prototype)}
v(ci,ai);function di(a,b){this.f=a;this.options=b;this.transactionCount=0;this.h=T();this.g=!1}
n=di.prototype;n.add=function(a,b,c){return ei(this,[a],"readwrite",function(d){return fi(d,a).add(b,c)})};
n.clear=function(a){return ei(this,[a],"readwrite",function(b){return fi(b,a).clear()})};
n.close=function(){var a;this.f.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
n.count=function(a,b){return ei(this,[a],"readonly",function(c){return fi(c,a).count(b)})};
n["delete"]=function(a,b){return ei(this,[a],"readwrite",function(c){return fi(c,a)["delete"](b)})};
n.get=function(a,b){return ei(this,[a],"readwrite",function(c){return fi(c,a).get(b)})};
function gi(a,b){return ei(a,["databases"],"readwrite",function(c){c=fi(c,"databases");return W(c.f.put(b,void 0))})}
function ei(a,b,c,d){c=void 0===c?"readonly":c;a.transactionCount++;var e=a.f.transaction(b,c);e=new hi(e);d=ii(e,d);ji(a,d,b.join(),c);return d}
function ji(a,b,c,d){var e=T();Ue(b.then(function(){ki(a,!0,c,T()-e)}),function(f){var g=T(),h=a.f.name,k=a.transactionCount,l;
"QuotaExceededError"===f.name?l=new ai("QUOTA_EXCEEDED",{objectStoreNames:c,dbName:h,mode:d}):"UnknownError"===f.name&&(l=new ai("QUOTA_MAYBE_EXCEEDED",{objectStoreNames:c,dbName:h,mode:d}));l&&Oh("QUOTA_EXCEEDED",{dbName:h,objectStoreNames:c,transactionCount:k,transactionMode:d});f instanceof bi&&(Oh("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:c,transactionDuration:g-e,transactionCount:a.transactionCount,dbDuration:g-a.h}),a.g=!0);ki(a,!1,c,g-e)})}
function ki(a,b,c,d){Oh("TRANSACTION_ENDED",{objectStoreNames:c,connectionHasUnknownAbortedTransaction:a.g,duration:d,isSuccessful:b})}
function li(a){this.f=a}
n=li.prototype;n.add=function(a,b){return W(this.f.add(a,b))};
n.clear=function(){return W(this.f.clear()).then(function(){})};
n.count=function(a){return W(this.f.count(a))};
function mi(a,b){return ni(a,{query:b},function(c){return c["delete"]().then(function(){return c["continue"]()})}).then(function(){})}
n["delete"]=function(a){return a instanceof IDBKeyRange?mi(this,a):W(this.f["delete"](a))};
n.get=function(a){return W(this.f.get(a))};
n.index=function(a){return new oi(this.f.index(a))};
n.getName=function(){return this.f.name};
function ni(a,b,c){a=a.f.openCursor(b.query,b.direction);return pi(a).then(function(d){return Xh(d,c)})}
function hi(a){var b=this;this.f=a;this.g=new Map;this.aborted=!1;this.done=new N(function(c,d){b.f.addEventListener("complete",function(){c()});
b.f.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.f.error)});
b.f.addEventListener("abort",function(){var e=b.f.error;if(e)d(e);else if(!b.aborted){e=bi;for(var f=b.f.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e(g.join(),b.f.db.name,b.f.mode);d(e)}})})}
function ii(a,b){var c=new N(function(d,e){Rh(b(a).then(function(f){a.commit();d(f)}),e)});
return Se([c,a.done]).then(function(d){return u(d).next().value})}
hi.prototype.abort=function(){this.f.abort();this.aborted=!0;throw new ai("EXPLICIT_ABORT");};
hi.prototype.commit=function(){var a=this.f;a.commit&&!this.aborted&&a.commit()};
function fi(a,b){var c=a.f.objectStore(b),d=a.g.get(c);d||(d=new li(c),a.g.set(c,d));return d}
function oi(a){this.f=a}
oi.prototype.count=function(a){return W(this.f.count(a))};
oi.prototype.get=function(a){return W(this.f.get(a))};
oi.prototype.getKey=function(a){return W(this.f.getKey(a))};
function qi(a,b){this.request=a;this.cursor=b}
function pi(a){return W(a).then(function(b){return null===b?null:new qi(a,b)})}
n=qi.prototype;n.advance=function(a){this.cursor.advance(a);return pi(this.request)};
n["continue"]=function(a){this.cursor["continue"](a);return pi(this.request)};
n["delete"]=function(){return W(this.cursor["delete"]()).then(function(){})};
n.getKey=function(){return this.cursor.key};
n.getValue=function(){return this.cursor.value};
n.update=function(a){return W(this.cursor.update(a))};function ri(a,b,c){function d(){m||(m=new di(e.result,{closed:l}));return m}
var e=self.indexedDB.open(a,b),f=c.blocked,g=c.blocking,h=c.rb,k=c.upgrade,l=c.closed,m;k&&e.addEventListener("upgradeneeded",function(p){if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===e.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");var q=d(),r=new hi(e.transaction);k(q,p.oldVersion,p.newVersion,r)});
f&&e.addEventListener("blocked",function(){f()});
return Wh(e).then(function(p){g&&p.addEventListener("versionchange",function(){g(d())});
p.addEventListener("close",function(){Oh("IDB_UNEXPECTEDLY_CLOSED",{dbName:a,dbVersion:p.version});h&&h()});
return d()})}
function si(a,b,c){c=void 0===c?{}:c;return ri(a,b,c)}
function ti(a,b){b=void 0===b?{}:b;var c=self.indexedDB.deleteDatabase(a),d=b.blocked;d&&c.addEventListener("blocked",function(){d()});
return Wh(c).then(function(){})}
;var ui=uc||vc;function vi(){var a=/WebKit\/([0-9]+)/.exec(Lb);return!!(a&&600<=parseInt(a[1],10))}
function wi(){var a=/WebKit\/([0-9]+)/.exec(Lb);return!!(a&&602<=parseInt(a[1],10))}
function xi(a){var b=Lb;return b?0<=b.toLowerCase().indexOf(a):!1}
;function yi(a,b){for(var c=u(Object.keys(b.ab)),d=c.next();!d.done;d=c.next())if(d=d.value,!a.f.objectStoreNames.contains(d))return d}
function zi(a){this.name="YtIdbMeta";this.options=a;this.g=!1}
function Ai(a,b,c){c=void 0===c?{}:c;return si(a,b,c)}
zi.prototype["delete"]=function(a){a=void 0===a?{}:a;return ti(this.name,a)};
zi.prototype.open=function(){var a=this;if(!this.f){var b,c=function(){a.f===b&&(a.f=void 0)},d={blocking:function(f){f.close()},
closed:c,rb:c,upgrade:this.options.upgrade},e=function(){return Ue(Ai(a.name,a.options.version,d).then(function(f){if(tc){var g=yi(f,a.options);if(void 0!==g){if(tc&&!a.g)return a.g=!0,a["delete"]().then(function(){return e()});
throw new ci(g);}}return f}),function(f){if(f instanceof DOMException?"VersionError"===f.name:"DOMError"in self&&f instanceof DOMError?"VersionError"===f.name:f instanceof Object&&"message"in f&&"An attempt was made to open a database using a lower version than the existing version."===f.message)return Ai(a.name,void 0,Object.assign(Object.assign({},d),{upgrade:void 0}));
c();throw f;})};
this.f=b=e()}return this.f};var Bi=new zi({ab:{databases:!0},upgrade:function(a,b){1>b&&a.f.createObjectStore("databases",{keyPath:"actualName"})}});
function Ci(){var a={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0,signedIn:!1};return Bi.open().then(function(b){return b.get("databases",a.actualName).then(function(c){if(c?a.actualName!==c.actualName||a.publicName!==c.publicName||a.userIdentifier!==c.userIdentifier||a.signedIn!==c.signedIn||a.clearDataOnAuthChange!==c.clearDataOnAuthChange:1)return gi(b,a)})})}
function Di(){return Bi.open().then(function(a){return a["delete"]("databases","yt-idb-test-do-not-use")})}
;var Ei,Fi,Gi=["getAll","getAllKeys","getKey","openKeyCursor"],Hi=["getAll","getAllKeys","getKey","openKeyCursor"];
function Ii(){return bc(this,function b(){var c,d;return Ba(b,function(e){switch(e.g){case 1:if(ui&&vi()&&!wi()&&!R("ytidb_allow_on_ios_safari_v8_and_v9")||fc)return e["return"](!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e["return"](!1)}catch(f){return e["return"](!1)}if(R("ytidb_new_supported_check_with_delete"))return e["return"](new Promise(function(f){Ue(Di().then(function(){f(!0)}),function(){f(!1)})}));
if(R("ytidb_new_supported_check_with_add_and_delete"))return e["return"](new Promise(function(f){Ue(Ci().then(function(){return Di()}).then(function(){f(!0)}),function(){f(!1)})}));
sa(e);return ra(e,Ue(si("yt-idb-test-do-not-use"),function(){}));
case 5:if(d=e.A,!d)return e["return"](!1);case 3:ua(e);if(d)try{d.close()}catch(f){}va(e);break;case 2:return ta(e),e["return"](!1);case 4:return"IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype?e["return"](!0):e["return"](!1)}})})}
function Ji(){if(void 0!==Ei)return Ei;var a=T();Nh=!0;return Ei=new N(function(b){Ii().then(function(c){Nh=!1;Oh("IS_SUPPORTED_COMPLETED",{duration:T()-a,isSupported:c});b(c)})})}
function Ki(){return void 0!==Fi?Fi:Fi=Ji().then(function(a){Nh=!0;if(!a)return!1;var b=u(Gi);for(a=b.next();!a.done;a=b.next())if(!IDBObjectStore.prototype[a.value])return!1;b=u(Hi);for(a=b.next();!a.done;a=b.next())if(!IDBIndex.prototype[a.value])return!1;return IDBObjectStore.prototype.getKey?!0:!1}).then(function(a){Nh=!1;
return a})}
;function Li(){Ce.call(this);this.h=Mi();Ni(this);Oi(this)}
v(Li,Ce);function Mi(){var a=window.navigator.onLine;return void 0===a?!0:a}
function Oi(a){window.addEventListener("online",function(){a.h=!0;a.m&&a.m()})}
function Ni(a){window.addEventListener("offline",function(){a.h=!1;a.l&&a.l()})}
;function Pi(a,b){b=void 0===b?{}:b;Qi().then(function(){Li.f||(Li.f=new Li);Li.f.h!==Mi()&&Cf(Error("NetworkStatusManager isOnline does not match window status"));wh(a,b)})}
function Ri(a,b){b=void 0===b?{}:b;Qi().then(function(){wh(a,b)})}
function Qi(){return bc(this,function b(){return Ba(b,function(c){return R("networkless_logging")?(2===If("networkless_ytidb_version")&&Ki().then(function(d){return d}),c["return"](Ji())):c["return"](!1)})})}
;function Si(a){var b=this;this.F=null;a?this.F=a:Dh()&&(this.F=Ug());ig(function(){Lh(b)},0,5E3)}
Si.prototype.isReady=function(){!this.F&&Dh()&&(this.F=Ug());return!!this.F};
function Xg(a,b,c,d){!Q("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Df(new Yh("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var e=new Yh("innertube xhrclient not ready",b,c,d);Cf(e);e.sampleWeight=0;throw e;}var f={headers:{"Content-Type":"application/json"},method:"POST",D:c,Da:"JSON",X:function(){d.X()},
Ca:d.X,onSuccess:function(p,q){if(d.onSuccess)d.onSuccess(q)},
Ba:function(p){if(d.onSuccess)d.onSuccess(p)},
onError:function(p,q){if(d.onError)d.onError(q)},
kk:function(p){if(d.onError)d.onError(p)},
timeout:d.timeout,withCredentials:!0},g="";(e=a.F.Wa)&&(g=e);var h=a.F.Ya||!1,k=Eh(h,g,d);Object.assign(f.headers,k);f.headers.Authorization&&!g&&(f.headers["x-origin"]=window.location.origin);e="/youtubei/"+a.F.innertubeApiVersion+"/"+b;var l={alt:"json"};a.F.Xa&&f.headers.Authorization||(l.key=a.F.innertubeApiKey);var m=gh(""+g+e,l||{},!0);Qi().then(function(p){if(d.retry&&R("retry_web_logging_batches")&&"www.youtube-nocookie.com"!=g){if(R("networkless_gel")&&!p||!R("networkless_gel"))var q=Jh(b,
c,k,h);if(q){var r=f.onSuccess,A=f.Ba;f.onSuccess=function(B,U){Kh(q);r(B,U)};
c.Ba=function(B,U){Kh(q);A(B,U)}}}try{R("use_fetch_for_op_xhr")?th(m,f):R("networkless_gel")&&d.retry?(f.method="POST",!d.tb&&R("nwl_send_fast_on_unload")?Ri(m,f):Pi(m,f)):(f.method="POST",f.D||(f.D={}),wh(m,f))}catch(B){if("InvalidAccessError"==B.name)q&&(Kh(q),q=0),Df(Error("An extension is blocking network request."));
else throw B;}q&&ig(function(){Lh(a)},0,5E3)})}
;function Ti(a,b,c){c=void 0===c?{}:c;var d=Si;Q("ytLoggingEventsDefaultDisabled",!1)&&Si==Si&&(d=null);Zg(a,b,d,c)}
;var Ui=[{za:function(a){return"Cannot read property '"+a.key+"'"},
sa:{TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,
groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]}],Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}]}},{za:function(a){return"Cannot call '"+a.key+"'"},
sa:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}}];function Vi(){this.f=[];this.g=[]}
var Wi;var Xi=new O;var Yi=new Set,Zi=0,$i=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function aj(a){bj(a,"WARNING")}
function bj(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||Q("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||Q("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;var g=void 0===g?!1:g;if(a&&(R("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),
(window&&window.yterr||g)&&!(5<=Zi)&&0!==a.sampleWeight)){var h=zc(a);g=h.message||"Unknown Error";d=h.name||"UnknownError";e=h.lineNumber||"Not available";f=h.fileName||"Not available";h=h.stack||a.f||"Not available";if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var k=0,l=0;l<a.args.length;l++){var m=a.args[l],p="params."+l;k+=p.length;if(m)if(Array.isArray(m))for(var q=c,r=0;r<m.length&&!(m[r]&&(k+=cj(r,m[r],p,q),500<k));r++);else if("object"===typeof m)for(q in q=void 0,r=c,m){if(m[q]&&
(k+=cj(q,m[q],p,r),500<k))break}else c[p]=dj(m),k+=c[p].length;else c[p]=dj(m),k+=c[p].length;if(500<=k)break}else if(a.hasOwnProperty("params")&&a.params)if(m=a.params,"object"===typeof a.params)for(l in p=0,m){if(m[l]&&(k="params."+l,q=dj(m[l]),c[k]=q,p+=k.length+q.length,500<p))break}else c.params=dj(m);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c.vendor=navigator.vendor);c={message:g,name:d,lineNumber:e,fileName:f,stack:h,params:c};a=Number(a.columnNumber);isNaN(a)||(c.lineNumber=c.lineNumber+
":"+a);a=u(Ui);for(g=a.next();!g.done;g=a.next())if(g=g.value,g.sa[c.name])for(e=u(g.sa[c.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=c.message.match(f.regexp)){c.params["error.original"]=d[0];e=f.groups;f={};for(h=0;h<e.length;h++)f[e[h]]=d[h+1],c.params["error."+e[h]]=d[h+1];c.message=g.za(f);break}window.yterr&&"function"===typeof window.yterr&&window.yterr(c);if(!(Yi.has(c.message)||0<=c.stack.indexOf("/YouTubeCenter.js")||0<=c.stack.indexOf("/mytube.js"))){Xi.T("handleError",c);if(R("kevlar_gel_error_routing")){a=
b;a:{g=u($i);for(d=g.next();!d.done;d=g.next())if(xi(d.value.toLowerCase())){g=!0;break a}g=!1}if(!g){d={stackTrace:c.stack};c.fileName&&(d.filename=c.fileName);g=c.lineNumber&&c.lineNumber.split?c.lineNumber.split(":"):[];0!==g.length&&(1!==g.length||isNaN(Number(g[0]))?2!==g.length||isNaN(Number(g[0]))||isNaN(Number(g[1]))||(d.lineNumber=Number(g[0]),d.columnNumber=Number(g[1])):d.lineNumber=Number(g[0]));Wi||(Wi=new Vi);g=Wi;e=c.message;f=c.name;a:{h=u(g.g);for(l=h.next();!l.done;l=h.next())if(l=
l.value,c.message&&c.message.match(l.f)){h=l.weight;break a}h=u(g.f);for(l=h.next();!l.done;l=h.next())if(l=l.value,l.Ja(c)){h=l.weight;break a}h=1}e={level:"ERROR_LEVEL_UNKNOWN",message:e,errorClassName:f,sampleWeight:h};"ERROR"===a?e.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(e.level="ERROR_LEVEL_WARNNING");a={isObfuscated:!0,browserStackInfo:d};d={pageUrl:window.location.href};Q("FEXP_EXPERIMENTS")&&(d.experimentIds=Q("FEXP_EXPERIMENTS"));d.kvPairs=[{key:"client.params.errorServiceSignature",value:"msg="+
g.g.length+"&cb="+g.f.length}];if(g=c.params)for(f=u(Object.keys(g)),h=f.next();!h.done;h=f.next())h=h.value,d.kvPairs.push({key:"client."+h,value:String(g[h])});g=Q("SERVER_NAME",void 0);f=Q("SERVER_VERSION",void 0);g&&f&&(d.kvPairs.push({key:"server.name",value:g}),d.kvPairs.push({key:"server.version",value:f}));Ti("clientError",{errorMetadata:d,stackTrace:a,logMessage:e});Qg()}}if(!R("suppress_error_204_logging")){a=c.params||{};b={sb:{a:"logerror",t:"jserror",type:c.name,msg:c.message.substr(0,
250),line:c.lineNumber,level:b,"client.name":a.name},D:{url:Q("PAGE_NAME",window.location.href),file:c.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.D){c.stack&&(b.D.stack=c.stack);g=u(Object.keys(a));for(d=g.next();!d.done;d=g.next())d=d.value,b.D["client."+d]=a[d];if(a=Q("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(g=u(Object.keys(a)),d=g.next();!d.done;d=g.next())d=d.value,b.D[d]=a[d];a=Q("SERVER_NAME",void 0);g=Q("SERVER_VERSION",void 0);a&&g&&(b.D["server.name"]=
a,b.D["server.version"]=g)}wh(Q("ECATCHER_REPORT_HOST","")+"/error_204",b)}Yi.add(c.message);Zi++}}}
function cj(a,b,c,d){c+="."+a;a=dj(b);d[c]=a;return c.length+a.length}
function dj(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
function ej(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];a.args||(a.args=[]);a.args.push.apply(a.args,c instanceof Array?c:fa(u(c)))}
;function fj(){this.g=!1;this.f=null}
fj.prototype.initialize=function(a,b,c,d,e,f){var g=this;f=void 0===f?!1:f;b?(this.g=!0,$f(b,function(){g.g=!1;window.botguard?gj(g,c,d,f):(eg(b),aj(new Yh("Unable to load Botguard","from "+b)))},e)):a&&(e=Mc(document,"SCRIPT"),e.textContent=a,e.nonce=Fa(),document.head.appendChild(e),document.head.removeChild(e),window.botguard?gj(this,c,d,f):aj(Error("Unable to load Botguard from JS")))};
function gj(a,b,c,d){if(d)try{a.f=new window.botguard.bg(b,c?function(){return c(b)}:Ja)}catch(e){aj(e)}else{try{a.f=new window.botguard.bg(b)}catch(e){aj(e)}c&&c(b)}}
fj.prototype.dispose=function(){this.f=null};var hj=new fj;function ij(){return!!hj.f}
function jj(a){a=void 0===a?{}:a;a=void 0===a?{}:a;return hj.f?hj.f.invoke(void 0,void 0,a):null}
;var kj=E().toString();
function lj(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=E();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(kj)for(a=1,b=0;b<kj.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^kj.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var mj=x.ytLoggingDocDocumentNonce_||lj();y("ytLoggingDocDocumentNonce_",mj,void 0);var nj=1;function oj(a){this.f=a}
function pj(a){return new oj({trackingParams:a})}
function qj(a){var b=nj++;return new oj({veType:a,veCounter:b,elementIndex:void 0,dataElement:void 0,youtubeData:void 0})}
oj.prototype.getAsJson=function(){var a={};void 0!==this.f.trackingParams?a.trackingParams=this.f.trackingParams:(a.veType=this.f.veType,void 0!==this.f.veCounter&&(a.veCounter=this.f.veCounter),void 0!==this.f.elementIndex&&(a.elementIndex=this.f.elementIndex));void 0!==this.f.dataElement&&(a.dataElement=this.f.dataElement.getAsJson());void 0!==this.f.youtubeData&&(a.youtubeData=this.f.youtubeData);return a};
oj.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
oj.prototype.isClientVe=function(){return!this.f.trackingParams&&!!this.f.veType};function rj(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function sj(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function tj(a){return Q(sj(void 0===a?0:a),void 0)}
y("yt_logging_screen.getRootVeType",tj,void 0);function uj(a){return(a=tj(void 0===a?0:a))?new oj({veType:a,youtubeData:void 0}):null}
function vj(){var a=Q("csn-to-ctt-auth-info");a||(a={},P("csn-to-ctt-auth-info",a));return a}
function X(a){a=void 0===a?0:a;var b=Q(rj(a));if(!b&&!Q("USE_CSN_FALLBACK",!0))return null;b||0!=a||(R("kevlar_client_side_screens")||R("c3_client_side_screens")?b="UNDEFINED_CSN":b=Q("EVENT_ID"));return b?b:null}
y("yt_logging_screen.getCurrentCsn",X,void 0);function wj(a,b,c){var d=vj();(c=X(c))&&delete d[c];b&&(d[a]=b)}
function xj(a){return vj()[a]}
y("yt_logging_screen.getCttAuthInfo",xj,void 0);function yj(a,b,c,d){c=void 0===c?0:c;if(a!==Q(rj(c))||b!==Q(sj(c)))if(wj(a,d,c),P(rj(c),a),P(sj(c),b),0==c||R("web_screen_associated_all_layers"))b=function(){setTimeout(function(){a&&Zg("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:mj,clientScreenNonce:a},Si)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
y("yt_logging_screen.setCurrentScreen",yj,void 0);function zj(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=Q("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=Q("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=Xb(window.location.href);g&&f.push(g);g=Xb(d);if(0<=Wa(f,g)||!g&&0==d.lastIndexOf("/",0))if(R("autoescape_tempdata_url")&&(f=document.createElement("a"),Rb(f,d),d=f.href),d){g=d.match(Vb);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:X()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&(e=b,b="ST-"+Ub(d).toString(36),e=e?Zb(e):"",Gf(b,e,k||5))}else k=b,e="ST-"+Ub(d).toString(36),k=k?Zb(k):"",Gf(e,k,5)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var m=void 0===m?"":m;var p=void 0===p?window:p;c=p.location;a=$b(a,l)+m;a=a instanceof J?a:Jb(a);c.href=Fb(a)}return!0}
;function Aj(a,b){this.version=a;this.args=b}
;function Bj(a,b){this.topic=a;this.f=b}
Bj.prototype.toString=function(){return this.topic};var Cj=z("ytPubsub2Pubsub2Instance")||new O;O.prototype.subscribe=O.prototype.subscribe;O.prototype.unsubscribeByKey=O.prototype.W;O.prototype.publish=O.prototype.T;O.prototype.clear=O.prototype.clear;y("ytPubsub2Pubsub2Instance",Cj,void 0);var Dj=z("ytPubsub2Pubsub2SubscribedKeys")||{};y("ytPubsub2Pubsub2SubscribedKeys",Dj,void 0);var Ej=z("ytPubsub2Pubsub2TopicToKeys")||{};y("ytPubsub2Pubsub2TopicToKeys",Ej,void 0);var Fj=z("ytPubsub2Pubsub2IsAsync")||{};y("ytPubsub2Pubsub2IsAsync",Fj,void 0);
y("ytPubsub2Pubsub2SkipSubKey",null,void 0);function Gj(a,b){var c=Hj();c&&c.publish.call(c,a.toString(),a,b)}
function Ij(a,b,c){var d=Hj();if(!d)return 0;var e=d.subscribe(a.toString(),function(f,g){var h=z("ytPubsub2Pubsub2SkipSubKey");h&&h==e||(h=function(){if(Dj[e])try{if(g&&a instanceof Bj&&a!=f)try{var k=a.f,l=g;if(!l.args||!l.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!k.N){var m=new k;k.N=m.version}var p=k.N}catch(q){}if(!p||l.version!=p)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{g=Reflect.construct(k,cb(l.args))}catch(q){throw q.message=
"yt.pubsub2.Data.deserialize(): "+q.message,q;}}catch(q){throw q.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+a.toString()+": "+q.message,q;}b.call(c||window,g)}catch(q){Cf(q)}},Fj[a.toString()]?z("yt.scheduler.instance")?hg(h):S(h,0):h())});
Dj[e]=!0;Ej[a.toString()]||(Ej[a.toString()]=[]);Ej[a.toString()].push(e);return e}
function Jj(){var a=Kj,b=Ij(Lj,function(c){a.apply(void 0,arguments);Mj(b)},void 0);
return b}
function Mj(a){var b=Hj();b&&("number"===typeof a&&(a=[a]),I(a,function(c){b.unsubscribeByKey(c);delete Dj[c]}))}
function Hj(){return z("ytPubsub2Pubsub2Instance")}
;function Nj(a){Aj.call(this,1,arguments);this.csn=a}
v(Nj,Aj);var Lj=new Bj("screen-created",Nj),Oj=[],Qj=Pj,Rj=0;function Sj(a,b,c,d){c={csn:b,parentVe:c.getAsJson(),childVes:Za(d,function(f){return f.getAsJson()})};
d=u(d);for(var e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(ib(e)||!e.trackingParams&&!e.veType)&&aj(Error("Child VE logged with no data"));d={L:xj(b),M:b};"UNDEFINED_CSN"==b?Tj("visualElementAttached",c,d):a?Zg("visualElementAttached",c,a,d):Ti("visualElementAttached",c,d)}
function Uj(a,b,c){var d="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";c={csn:b,ve:c.getAsJson(),gestureType:d};d={L:xj(b),M:b};"UNDEFINED_CSN"==b?Tj("visualElementGestured",c,d):a?Zg("visualElementGestured",c,a,d):Ti("visualElementGestured",c,d)}
function Pj(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return yc(b)}
function Tj(a,b,c){Oj.push({payloadName:a,payload:b,options:c});Rj||(Rj=Jj())}
function Kj(a){if(Oj){for(var b=u(Oj),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,Zg(c.payloadName,c.payload,null,c.options));Oj.length=0}Rj=0}
;function Vj(a,b,c){Sj(R("use_default_events_client")?void 0:Si,a,b,[c])}
;var Wj={Yb:6827,Zb:29434,cc:3611,ze:3854,Pf:42993,ti:4724,aj:96370,ub:27686,vb:85013,wb:23462,yb:42016,zb:62407,Ab:26926,xb:43781,Bb:51236,Cb:79148,Db:50160,Eb:77504,Qb:87907,Rb:18630,Sb:54445,Tb:80935,Ub:105675,Vb:37521,Wb:47786,Xb:98349,ac:7282,ec:32276,dc:76278,fc:93911,hc:106531,ic:27259,jc:27262,kc:27263,lc:21759,mc:27107,nc:62936,oc:49568,pc:38408,qc:80637,sc:68727,tc:68728,uc:80353,wc:80356,xc:74610,yc:45707,zc:83962,Ac:83970,Bc:46713,Cc:89711,Dc:74612,Ec:93265,Fc:74611,Hc:113533,Ic:93252,
Jc:99357,Lc:94521,Mc:114252,Nc:113532,Oc:94522,Kc:94583,Pc:88E3,Qc:93253,Rc:93254,Sc:94387,Tc:94388,Uc:93255,Vc:97424,Gc:72502,Wc:110111,Xc:76019,Yc:89431,Zc:110466,bd:77240,cd:60508,dd:105350,ed:73393,fd:113534,gd:92098,hd:84517,jd:83759,kd:80357,ld:86113,md:72598,nd:72733,od:107349,pd:97615,qd:31402,rd:84774,sd:95117,td:98930,ud:98931,vd:98932,wd:43347,xd:45474,yd:100352,zd:84758,Ad:98443,Bd:74613,Cd:74614,Dd:64502,Ed:74615,Fd:74616,Gd:74617,Hd:77820,Id:74618,Jd:93278,Kd:93274,Ld:93275,Md:93276,
Nd:22110,Od:29433,Pd:82047,Qd:113550,Rd:75836,Sd:75837,Td:42352,Ud:84512,Vd:76065,Wd:75989,Xd:16623,Yd:32594,Zd:27240,ae:32633,be:74858,de:3945,ce:16989,ee:45520,ge:25488,he:25492,ie:25494,je:55760,ke:14057,le:18451,me:57204,ne:57203,oe:17897,pe:57205,qe:18198,re:17898,se:17909,te:43980,ue:46220,we:11721,xe:49954,ye:96369,Ae:56251,Be:25624,Ce:16906,De:99999,Ee:68172,Fe:27068,Ge:47973,He:72773,Ie:26970,Je:26971,Ke:96805,Le:17752,Me:73233,Ne:109512,Oe:22256,Pe:14115,Qe:22696,Re:89278,Se:89277,Te:109513,
Ue:43278,Ve:43459,We:43464,Xe:89279,Ye:43717,Ze:55764,af:22255,bf:89281,cf:40963,df:43277,ef:43442,ff:91824,gf:96367,hf:36850,jf:72694,kf:37414,lf:36851,mf:73491,nf:54473,pf:43375,qf:46674,rf:32473,sf:72901,tf:72906,uf:50947,vf:50612,wf:50613,xf:50942,yf:84938,zf:84943,Af:84939,Bf:84941,Cf:84944,Df:84940,Ef:84942,Ff:35585,Gf:51926,Hf:79983,If:63238,Jf:18921,Kf:63241,Lf:57893,Mf:41182,Nf:33424,Of:22207,Qf:36229,Rf:22206,Sf:22205,Tf:18993,Uf:19001,Vf:18990,Wf:18991,Xf:18997,Yf:18725,Zf:19003,ag:36874,
cg:44763,dg:33427,eg:67793,fg:22182,gg:37091,hg:34650,jg:50617,kg:47261,lg:22287,mg:25144,ng:97917,og:62397,pg:36961,qg:108035,rg:27426,sg:27857,tg:27846,ug:27854,vg:69692,wg:61411,xg:39299,yg:38696,zg:62520,Ag:36382,Bg:108701,Cg:50663,Dg:36387,Eg:14908,Fg:37533,Gg:105443,Hg:61635,Ig:62274,Jg:65702,Kg:65703,Lg:65701,Mg:76256,Ng:37671,Og:49953,Pg:36216,Qg:28237,Rg:39553,Sg:29222,Tg:26107,Ug:38050,Vg:26108,Wg:26109,Xg:26110,Yg:66881,Zg:28236,ah:14586,bh:57929,dh:74723,eh:44098,fh:44099,gh:23528,hh:61699,
ih:59149,jh:101951,kh:97346,lh:95102,mh:64882,nh:63595,oh:63349,ph:95101,qh:75240,rh:27039,sh:68823,uh:21537,vh:83464,wh:75707,xh:83113,yh:101952,zh:101953,Ah:79610,Bh:24402,Ch:24400,Dh:32925,Eh:57173,Fh:64423,Gh:64424,Hh:33986,Ih:100828,Jh:21409,Kh:11070,Lh:11074,Mh:17880,Nh:14001,Ph:30709,Qh:30707,Rh:30711,Sh:30710,Th:30708,Oh:26984,Uh:63648,Vh:63649,Wh:51879,Xh:111059,Yh:5754,Zh:20445,ai:110386,bi:113746,ci:66557,di:17310,fi:28631,gi:21589,hi:68012,ii:60480,ji:31571,ki:76980,li:41577,mi:45469,
ni:38669,oi:13768,ri:13777,si:62985,vi:59369,wi:43927,xi:43928,yi:12924,zi:100355,Bi:56219,Ci:27669,Di:10337,Ai:47896,Ei:107598,Fi:96639,Gi:107536,Hi:96661,Ii:96658,Ji:96660,Ki:104443,Li:96659,Mi:106442,Ni:63667,Oi:63668,Pi:63669,Qi:78314,Ri:55761,Si:96368,Ti:67374,Ui:48992,Vi:49956,Wi:31961,Xi:26388,Yi:23811,Zi:5E4,bj:47355,cj:47356,dj:37935,ej:45521,fj:21760,gj:83769,hj:49977,ij:49974,jj:93497,kj:93498,lj:34325,mj:100081,nj:35309,oj:68314,pj:25602,qj:100339,rj:59018,sj:18248,tj:50625,uj:9729,vj:37168,
wj:37169,xj:21667,yj:16749,zj:18635,Aj:39305,Bj:18046,Cj:53969,Dj:8213,Ej:93926,Fj:102852,Gj:110099,Hj:22678,Ij:69076,Jj:100856,Kj:17736,Lj:3832,Mj:55759,Nj:64031,Oj:93044,Pj:93045,Qj:34388,Rj:17657,Sj:17655,Tj:39579,Uj:39578,Vj:77448,Wj:8196,Xj:11357,Yj:69877,Zj:8197,ak:82039};function Xj(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||lb(b);this.assets=a.assets||{};this.attrs=a.attrs||lb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Xj.prototype.clone=function(){var a=new Xj,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==La(c)?a[b]=lb(c):a[b]=c}return a};function Yj(){M.call(this);this.f=[]}
v(Yj,M);Yj.prototype.u=function(){for(;this.f.length;){var a=this.f.pop();a.target.removeEventListener(a.name,a.Ja)}M.prototype.u.call(this)};var Zj=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function ak(a){a=a||"";if(window.spf){var b=a.match(Zj);spf.style.load(a,b?b[1]:"",void 0)}else bk(a)}
function bk(a){var b=ck(a),c=document.getElementById(b),d=c&&Lf(c,"loaded");d||c&&!d||(c=dk(a,b,function(){Lf(c,"loaded")||(Jf(c),Vf(b),S(Sa(Wf,b),0))}))}
function dk(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=$c(a);d.rel="stylesheet";d.href=tb(a).toString();(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function ck(a){var b=Mc(document,"A");Rb(b,new J(a,Eb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Ub(a)}
;function ek(a,b,c,d){M.call(this);var e=this;this.m=this.ca=a;this.H=b;this.o=!1;this.api={};this.aa=this.G=null;this.I=new O;Uc(this,Sa(Vc,this.I));this.j={};this.R=this.ba=this.i=this.ja=this.f=null;this.P=!1;this.l=this.B=null;this.da={};this.Ga=["onReady"];this.ia=null;this.ta=NaN;this.Y={};this.h=d;fk(this);this.ea("WATCH_LATER_VIDEO_ADDED",this.bb.bind(this));this.ea("WATCH_LATER_VIDEO_REMOVED",this.cb.bind(this));this.ea("onAdAnnounce",this.Ia.bind(this));this.Ha=new Yj(this);Uc(this,Sa(Vc,
this.Ha));this.Z=0;c?this.Z=S(function(){e.loadNewVideoConfig(c)},0):d&&(gk(this),hk(this))}
v(ek,M);n=ek.prototype;n.getId=function(){return this.H};
n.loadNewVideoConfig=function(a){if(!this.g){this.Z&&(Nf(this.Z),this.Z=0);a instanceof Xj||(a=new Xj(a));this.ja=a;this.f=a.clone();gk(this);this.ba||(this.ba=ik(this,this.f.args.jsapicallback||"onYouTubePlayerReady"));this.f.args.jsapicallback=null;if(a=this.f.attrs.width)this.m.style.width=bd(Number(a)||String(a));if(a=this.f.attrs.height)this.m.style.height=bd(Number(a)||String(a));hk(this);this.o&&jk(this)}};
function gk(a){var b;a.h?b=a.h.rootElementId:b=a.f.attrs.id;a.i=b||a.i;"video-player"==a.i&&(a.i=a.H,a.h?a.h.rootElementId=a.H:a.f.attrs.id=a.H);a.m.id==a.i&&(a.i+="-player",a.h?a.h.rootElementId=a.i:a.f.attrs.id=a.i)}
n.Oa=function(){return this.ja};
function jk(a){a.f&&!a.f.loaded&&(a.f.loaded=!0,"0"!=a.f.args.autoplay?a.api.loadVideoByPlayerVars(a.f.args):a.api.cueVideoByPlayerVars(a.f.args))}
function kk(a){var b=!0,c=lk(a);c&&a.f&&(a=mk(a),b=Lf(c,"version")===a);return b&&!!z("yt.player.Application.create")}
function hk(a){if(!a.g&&!a.P){var b=kk(a);if(b&&"html5"==(lk(a)?"html5":null))a.R="html5",a.o||nk(a);else if(ok(a),a.R="html5",b&&a.l)a.ca.appendChild(a.l),nk(a);else{a.f&&(a.f.loaded=!0);var c=!1;a.B=function(){c=!0;var d=pk(a,"player_bootstrap_method")?z("yt.player.Application.createAlternate")||z("yt.player.Application.create"):z("yt.player.Application.create");var e=a.f?a.f.clone():void 0;d(a.ca,e,a.h);nk(a)};
a.P=!0;b?a.B():($f(mk(a),a.B),(b=a.h?a.h.cssUrl:a.f.assets.css)&&ak(b),qk(a)&&!c&&y("yt.player.Application.create",null,void 0))}}}
function lk(a){var b=Ic(a.i);!b&&a.m&&a.m.querySelector&&(b=a.m.querySelector("#"+a.i));return b}
function nk(a){if(!a.g){var b=lk(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);c?(a.P=!1,!pk(a,"html5_remove_not_servable_check_killswitch")&&b.isNotServable&&a.f&&b.isNotServable(a.f.args.video_id)||rk(a)):a.ta=S(function(){nk(a)},50)}}
function rk(a){fk(a);a.o=!0;var b=lk(a);b.addEventListener&&(a.G=sk(a,b,"addEventListener"));b.removeEventListener&&(a.aa=sk(a,b,"removeEventListener"));var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=0;d<c.length;d++){var e=c[d];a.api[e]||(a.api[e]=sk(a,b,e))}for(var f in a.j)a.G(f,a.j[f]);jk(a);a.ba&&a.ba(a.api);a.I.T("onReady",a.api)}
function sk(a,b,c){var d=b[c];return function(){try{return a.ia=null,d.apply(b,arguments)}catch(e){"sendAbandonmentPing"!=c&&(e.params=c,a.ia=e,Df(e))}}}
function fk(a){a.o=!1;if(a.aa)for(var b in a.j)a.aa(b,a.j[b]);for(var c in a.Y)Nf(parseInt(c,10));a.Y={};a.G=null;a.aa=null;for(var d in a.api)a.api[d]=null;a.api.addEventListener=a.ea.bind(a);a.api.removeEventListener=a.ib.bind(a);a.api.destroy=a.dispose.bind(a);a.api.getLastError=a.Pa.bind(a);a.api.getPlayerType=a.Qa.bind(a);a.api.getCurrentVideoConfig=a.Oa.bind(a);a.api.loadNewVideoConfig=a.loadNewVideoConfig.bind(a);a.api.isReady=a.Za.bind(a)}
n.Za=function(){return this.o};
n.ea=function(a,b){var c=this,d=ik(this,b);if(d){if(!(0<=Wa(this.Ga,a)||this.j[a])){var e=tk(this,a);this.G&&this.G(a,e)}this.I.subscribe(a,d);"onReady"==a&&this.o&&S(function(){d(c.api)},0)}};
n.ib=function(a,b){if(!this.g){var c=ik(this,b);c&&ef(this.I,a,c)}};
function ik(a,b){var c=b;if("string"==typeof b){if(a.da[b])return a.da[b];c=function(){var d=z(b);d&&d.apply(x,arguments)};
a.da[b]=c}return c?c:null}
function tk(a,b){var c="ytPlayer"+b+a.H;a.j[b]=c;x[c]=function(d){var e=S(function(){if(!a.g){a.I.T(b,d);var f=a.Y,g=String(e);g in f&&delete f[g]}},0);
jb(a.Y,String(e))};
return c}
n.Ia=function(a){Vf("a11y-announce",a)};
n.bb=function(a){Vf("WATCH_LATER_VIDEO_ADDED",a)};
n.cb=function(a){Vf("WATCH_LATER_VIDEO_REMOVED",a)};
n.Qa=function(){return this.R||(lk(this)?"html5":null)};
n.Pa=function(){return this.ia};
function ok(a){a.cancel();fk(a);a.R=null;a.f&&(a.f.loaded=!1);var b=lk(a);b&&(kk(a)||!qk(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));for(a=a.ca;b=a.firstChild;)a.removeChild(b)}
n.cancel=function(){if(this.B){var a=mk(this);fg(a,this.B)}Nf(this.ta);this.P=!1};
n.u=function(){ok(this);if(this.l&&this.f&&this.l.destroy)try{this.l.destroy()}catch(b){Cf(b)}this.da=null;for(var a in this.j)x[this.j[a]]=null;this.ja=this.f=this.api=null;delete this.ca;delete this.m;M.prototype.u.call(this)};
function qk(a){return a.f&&a.f.args&&a.f.args.fflags?-1!=a.f.args.fflags.indexOf("player_destroy_old_version=true"):!1}
function mk(a){return a.h?a.h.jsUrl:a.f.assets.js}
function pk(a,b){if(a.h)var c=a.h.serializedExperimentFlags;else a.f&&a.f.args&&(c=a.f.args.fflags);return"true"==dh(c||"")[b]}
;var uk={},vk="player_uid_"+(1E9*Math.random()>>>0);
function wk(a,b,c){var d="player";c=void 0===c?!0:c;var e;"string"===typeof d?e=Ic(d):e=d;d=e;e=vk+"_"+Na(d);var f=uk[e];if(f&&c)return(b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags&&a.args.fflags.includes("web_player_remove_playerproxy=true"))?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new ek(d,e,a,b);uk[e]=f;Vf("player-added",f.api);Uc(f,Sa(xk,f));return f.api}
function xk(a){delete uk[a.getId()]}
;function yk(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function zk(a,b,c){"string"===typeof a&&(a={mediaContentUrl:a,startSeconds:b,suggestedQuality:c});a:{if((b=a.mediaContentUrl)&&(b=/\/([ve]|embed)\/([^#?]+)/.exec(b))&&b[2]){b=b[2];break a}b=null}a.videoId=b;return Ak(a)}
function Ak(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Bk(a,b,c,d){if(C(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Ck(a){a=void 0===a?!1:a;M.call(this);this.f=new O(a);Uc(this,Sa(Vc,this.f))}
G(Ck,M);Ck.prototype.subscribe=function(a,b,c){return this.g?0:this.f.subscribe(a,b,c)};
Ck.prototype.j=function(a,b){this.g||this.f.T.apply(this.f,arguments)};function Dk(a,b,c){Ck.call(this);this.h=a;this.i=b;this.l=c}
v(Dk,Ck);function Ek(a,b,c){if(!a.g){var d=a.h;d.g||a.i!=d.f||(a={id:a.l,command:b},c&&(a.data=c),d.f.postMessage(Ee(a),d.i))}}
Dk.prototype.u=function(){this.i=this.h=null;Ck.prototype.u.call(this)};function Fk(a){M.call(this);this.f=a;this.f.subscribe("command",this.Ea,this);this.h={};this.j=!1}
v(Fk,M);n=Fk.prototype;n.start=function(){this.j||this.g||(this.j=!0,Ek(this.f,"RECEIVING"))};
n.Ea=function(a,b,c){if(this.j&&!this.g){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&(a=d.event,a in this.h||(c=D(this.kb,this,a),this.h[a]=c,this.addEventListener(a,c)));break;case "removeEventListener":"string"===typeof d.event&&Gk(this,d.event);break;default:this.i.isReady()&&this.i.isExternalMethodAvailable(a,c||null)&&(b=Hk(a,b||{}),c=this.i.handleExternalCall(a,b,c||null),(c=Ik(a,c))&&this.j&&!this.g&&Ek(this.f,a,c))}}};
n.kb=function(a,b){this.j&&!this.g&&Ek(this.f,a,this.la(a,b))};
n.la=function(a,b){if(null!=b)return{value:b}};
function Gk(a,b){b in a.h&&(a.removeEventListener(b,a.h[b]),delete a.h[b])}
n.u=function(){var a=this.f;a.g||ef(a.f,"command",this.Ea,this);this.f=null;for(var b in this.h)Gk(this,b);M.prototype.u.call(this)};function Jk(a,b){Fk.call(this,b);this.i=a;this.start()}
v(Jk,Fk);Jk.prototype.addEventListener=function(a,b){this.i.addEventListener(a,b)};
Jk.prototype.removeEventListener=function(a,b){this.i.removeEventListener(a,b)};
function Hk(a,b){switch(a){case "loadVideoById":return b=Ak(b),[b];case "cueVideoById":return b=Ak(b),[b];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return b=Bk(b),[b];case "cuePlaylist":return b=Bk(b),[b];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Ik(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Jk.prototype.la=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Fk.prototype.la.call(this,a,b)};
Jk.prototype.u=function(){Fk.prototype.u.call(this);delete this.i};function Kk(a,b,c){M.call(this);var d=this;c=c||Q("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.h=b||null;this.o="*";this.i=c;this.sessionId=null;this.channel="widget";this.B=!!a;this.m=function(e){a:if(!("*"!=d.i&&e.origin!=d.i||d.h&&e.source!=d.h||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.B&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.i=d.o=e.origin);d.h=e.source;d.sessionId=f.id;d.f&&(d.f(),d.f=null);break;case "command":d.j&&(!d.l||0<=Wa(d.l,f.func))&&d.j(f.func,f.args,e.origin)}}};
this.l=this.f=this.j=null;window.addEventListener("message",this.m)}
v(Kk,M);Kk.prototype.sendMessage=function(a,b){var c=b||this.h;if(c){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var d=JSON.stringify(a);c.postMessage(d,this.o)}catch(e){Df(e)}}};
Kk.prototype.u=function(){window.removeEventListener("message",this.m);M.prototype.u.call(this)};function Lk(){var a=this.g=new Kk(!!Q("WIDGET_ID_ENFORCE")),b=D(this.hb,this);a.j=b;a.l=null;this.g.channel="widget";if(a=Q("WIDGET_ID"))this.g.sessionId=a;this.i=[];this.l=!1;this.j={}}
n=Lk.prototype;n.hb=function(a,b,c){"addEventListener"==a&&b?(a=b[0],this.j[a]||"onReady"==a||(this.addEventListener(a,Mk(this,a)),this.j[a]=!0)):this.Aa(a,b,c)};
n.Aa=function(){};
function Mk(a,b){return D(function(c){this.sendMessage(b,c)},a)}
n.addEventListener=function(){};
n.Na=function(){this.l=!0;this.sendMessage("initialDelivery",this.ma());this.sendMessage("onReady");I(this.i,this.Fa,this);this.i=[]};
n.ma=function(){return null};
function Nk(a,b){a.sendMessage("infoDelivery",b)}
n.Fa=function(a){this.l?this.g.sendMessage(a):this.i.push(a)};
n.sendMessage=function(a,b){this.Fa({event:a,info:void 0==b?null:b})};
n.dispose=function(){this.g=null};function Ok(a){Lk.call(this);this.f=a;this.h=[];this.addEventListener("onReady",D(this.eb,this));this.addEventListener("onVideoProgress",D(this.ob,this));this.addEventListener("onVolumeChange",D(this.pb,this));this.addEventListener("onApiChange",D(this.jb,this));this.addEventListener("onPlaybackQualityChange",D(this.lb,this));this.addEventListener("onPlaybackRateChange",D(this.mb,this));this.addEventListener("onStateChange",D(this.nb,this));this.addEventListener("onWebglSettingsChanged",D(this.qb,
this))}
v(Ok,Lk);n=Ok.prototype;n.Aa=function(a,b,c){if(this.f.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&yk(a)){var d=b;if(C(d[0])&&!Array.isArray(d[0]))d=d[0];else{var e={};switch(a){case "loadVideoById":case "cueVideoById":e=Ak.apply(window,d);break;case "loadVideoByUrl":case "cueVideoByUrl":e=zk.apply(window,d);break;case "loadPlaylist":case "cuePlaylist":e=Bk.apply(window,d)}d=e}b.length=1;b[0]=d}this.f.handleExternalCall(a,b,c);yk(a)&&Nk(this,this.ma())}};
n.eb=function(){var a=D(this.Na,this);this.g.f=a};
n.addEventListener=function(a,b){this.h.push({eventType:a,listener:b});this.f.addEventListener(a,b)};
n.ma=function(){if(!this.f)return null;var a=this.f.getApiInterface();bb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.f[e]();b[f]=g}catch(h){}}}b.videoData=this.f.getVideoData();b.currentTimeLastUpdated_=E()/1E3;return b};
n.nb=function(a){a={playerState:a,currentTime:this.f.getCurrentTime(),duration:this.f.getDuration(),videoData:this.f.getVideoData(),videoStartBytes:0,videoBytesTotal:this.f.getVideoBytesTotal(),videoLoadedFraction:this.f.getVideoLoadedFraction(),playbackQuality:this.f.getPlaybackQuality(),availableQualityLevels:this.f.getAvailableQualityLevels(),currentTimeLastUpdated_:E()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getVideoUrl&&(a.videoUrl=
this.f.getVideoUrl());this.f.getVideoContentRect&&(a.videoContentRect=this.f.getVideoContentRect());this.f.getProgressState&&(a.progressState=this.f.getProgressState());this.f.getPlaylist&&(a.playlist=this.f.getPlaylist());this.f.getPlaylistIndex&&(a.playlistIndex=this.f.getPlaylistIndex());this.f.getStoryboardFormat&&(a.storyboardFormat=this.f.getStoryboardFormat());Nk(this,a)};
n.lb=function(a){Nk(this,{playbackQuality:a})};
n.mb=function(a){Nk(this,{playbackRate:a})};
n.jb=function(){for(var a=this.f.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.f.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.f.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
n.pb=function(){Nk(this,{muted:this.f.isMuted(),volume:this.f.getVolume()})};
n.ob=function(a){a={currentTime:a,videoBytesLoaded:this.f.getVideoBytesLoaded(),videoLoadedFraction:this.f.getVideoLoadedFraction(),currentTimeLastUpdated_:E()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getProgressState&&(a.progressState=this.f.getProgressState());Nk(this,a)};
n.qb=function(){var a={sphericalProperties:this.f.getSphericalProperties()};Nk(this,a)};
n.dispose=function(){Lk.prototype.dispose.call(this);for(var a=0;a<this.h.length;a++){var b=this.h[a];this.f.removeEventListener(b.eventType,b.listener)}this.h=[]};function Pk(a,b,c){M.call(this);this.f=a;this.i=c;this.j=vg(window,"message",D(this.l,this));this.h=new Dk(this,a,b);Uc(this,Sa(Vc,this.h))}
v(Pk,M);Pk.prototype.l=function(a){var b;if(b=!this.g)if(b=a.origin==this.i)a:{b=this.f;do{b:{var c=a.source;do{if(c==b){c=!0;break b}if(c==c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.h,c.g||c.j("command",b.command,b.data,a.origin))}};
Pk.prototype.u=function(){wg(this.j);this.f=null;M.prototype.u.call(this)};function Qk(){var a=lb(Rk),b;return Ue(new N(function(c,d){a.onSuccess=function(e){nh(e)?c(e):d(new Sk("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Sk("Unknown request error","net.unknown",e))};
a.X=function(e){d(new Sk("Request timed out","net.timeout",e))};
b=wh("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Ve&&b.abort();
return Pe(c)})}
function Sk(a,b,c){H.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Sk,H);function Tk(){this.g=0;this.f=null}
Tk.prototype.then=function(a,b,c){return 1===this.g&&a?(a=a.call(c,this.f),Ke(a)?a:Uk(a)):2===this.g&&b?(a=b.call(c,this.f),Ke(a)?a:Vk(a)):this};
Tk.prototype.getValue=function(){return this.f};
Tk.prototype.$goog_Thenable=!0;function Vk(a){var b=new Tk;a=void 0===a?null:a;b.g=2;b.f=void 0===a?null:a;return b}
function Uk(a){var b=new Tk;a=void 0===a?null:a;b.g=1;b.f=void 0===a?null:a;return b}
;function Wk(a){H.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Xk;this.isTimeout=a instanceof Sk&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Ve}
v(Wk,H);Wk.prototype.name="BiscottiError";function Xk(){H.call(this,"Biscotti ID is missing from server")}
v(Xk,H);Xk.prototype.name="BiscottiMissingError";var Rk={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Yk=null;
function ah(){if(R("disable_biscotti_fetch_on_html5_clients"))return Pe(Error("Fetching biscotti ID is disabled."));if(R("condition_biscotti_fetch_on_consent_cookie_html5_clients")&&!Ec.get("CONSENT","").startsWith("YES+"))return Pe(Error("User has not consented - not fetching biscotti id."));if("1"===fb(yf(),"args","privembed"))return Pe(Error("Biscotti ID is not available in private embed mode"));Yk||(Yk=Ue(Qk().then(Zk),function(a){return $k(2,a)}));
return Yk}
function Zk(a){a=a.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Xk;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Xk;a=a.id;bh(a);Yk=Uk(a);al(18E5,2);return a}
function $k(a,b){var c=new Wk(b);bh("");Yk=Vk(c);0<a&&al(12E4,a-1);throw c;}
function al(a,b){S(function(){Ue(Qk().then(Zk,function(c){return $k(b,c)}),Ja)},a)}
function bl(){try{var a=z("yt.ads.biscotti.getId_");return a?a():ah()}catch(b){return Pe(b)}}
;function cl(a){if("1"!==fb(yf(),"args","privembed")){a&&$g();try{bl().then(function(){},function(){}),S(cl,18E5)}catch(b){Cf(b)}}}
;var Y=z("ytglobal.prefsUserPrefsPrefs_")||{};y("ytglobal.prefsUserPrefsPrefs_",Y,void 0);function dl(){this.f=Q("ALT_PREF_COOKIE_NAME","PREF");var a=Ec.get(""+this.f,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Y[d]=c.toString())}}}
n=dl.prototype;n.get=function(a,b){el(a);fl(a);var c=void 0!==Y[a]?Y[a].toString():null;return null!=c?c:b?b:""};
n.set=function(a,b){el(a);fl(a);if(null==b)throw Error("ExpectedNotNull");Y[a]=b.toString()};
n.remove=function(a){el(a);fl(a);delete Y[a]};
n.save=function(){Gf(this.f,this.dump(),63072E3)};
n.clear=function(){for(var a in Y)delete Y[a]};
n.dump=function(){var a=[],b;for(b in Y)a.push(b+"="+encodeURIComponent(String(Y[b])));return a.join("&")};
function fl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function el(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function gl(a){a=void 0!==Y[a]?Y[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ka(dl);function hl(){this.g=new Set;this.f=new Set;this.h=new Map}
hl.prototype.clear=function(){this.g.clear();this.f.clear();this.h.clear()};
Ka(hl);var il={},jl=(il[0]=[],il[1]=[],il);function kl(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!ll(a)||c.some(function(e){return!ll(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())ml(a,d.value);return a}
function ml(a,b){for(var c in b)if(ll(b[c])){if(c in a&&!ll(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});ml(a[c],b[c])}else if(nl(b[c])){if(c in a&&!nl(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);ol(a[c],b[c])}else a[c]=b[c];return a}
function ol(a,b){for(var c=u(b),d=c.next();!d.done;d=c.next())d=d.value,ll(d)?a.push(ml({},d)):nl(d)?a.push(ol([],d)):a.push(d);return a}
function ll(a){return"object"===typeof a&&!Array.isArray(a)}
function nl(a){return"object"===typeof a&&Array.isArray(a)}
;var pl={},ql=0;
function rl(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!xi("cobalt")){if(a){a instanceof J||(a="object"==typeof a&&a.U?a.S():String(a),Ib.test(a)?a=new J(a,Eb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Hb))&&Gb.test(b[1])?new J(a,Eb):null));a=Fb(a||Kb);if("about:invalid#zClosurez"===a||a.startsWith("data"))a="";else{if(!(a instanceof Ob)){b="object"==typeof a;var f=null;b&&a.na&&(f=a.ka());a=Qb(vb(b&&a.U?a.S():String(a)),f)}a instanceof Ob&&a.constructor===Ob?a=a.f:(La(a),a="type_error:SafeHtml");
a=encodeURIComponent(String(Ee(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=Lc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)xh(a,b,"POST",e,d);else if(Q("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)xh(a,b,"GET","",d);else{b:{try{var g=new Ua({url:a});if(g.h&&g.g||g.i){var h=Wb(a.match(Vb)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(ac);d:{for(c=0;0<=(c=a.indexOf("ri",
c))&&c<l;){var m=a.charCodeAt(c-1);if(38==m||63==m){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var q=c;break d}}c+=3}q=-1}if(0>q)var r=null;else{var A=a.indexOf("&",q);if(0>A||A>l)A=l;q+=3;r=decodeURIComponent(a.substr(q,A-q).replace(/\+/g," "))}k="1"!==r}f=!k;break b}}catch(B){}f=!1}f?sl(a)?(b&&b(),f=!0):f=!1:f=!1;f||tl(a,b)}}
function sl(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function tl(a,b){var c=new Image,d=""+ql++;pl[d]=c;c.onload=c.onerror=function(){b&&pl[d]&&b();delete pl[d]};
c.src=a}
;function ul(a,b){Aj.call(this,1,arguments)}
v(ul,Aj);function vl(a,b){Aj.call(this,1,arguments)}
v(vl,Aj);var wl=new Bj("aft-recorded",ul),xl=new Bj("timing-sent",vl);var yl=window;function zl(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var Al=yl.performance||yl.mozPerformance||yl.msPerformance||yl.webkitPerformance||new zl;var Bl=!1;D(Al.clearResourceTimings||Al.webkitClearResourceTimings||Al.mozClearResourceTimings||Al.msClearResourceTimings||Al.oClearResourceTimings||Ja,Al);function Cl(a){var b=Dl(a);if(b.aft)return b.aft;a=Q((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function El(a){var b;(b=z("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},F("ytcsi."+(a||"")+"data_",b));return b}
function Fl(a){a=El(a);a.info||(a.info={});return a.info}
function Dl(a){a=El(a);a.tick||(a.tick={});return a.tick}
function Gl(a){var b=El(a).nonce;b||(b=lj(),El(a).nonce=b);return b}
function Hl(a){var b=Dl(a||""),c=Cl(a);c&&!Bl&&(Gj(wl,new ul(Math.round(c-b._start),a)),Bl=!0)}
;function Il(){var a=z("ytcsi.debug");a||(a=[],y("ytcsi.debug",a,void 0),y("ytcsi.reference",{},void 0));return a}
function Jl(a){a=a||"";var b=z("ytcsi.reference");b||(Il(),b=z("ytcsi.reference"));if(b[a])return b[a];var c=Il(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var Kl=x.ytLoggingLatencyUsageStats_||{};y("ytLoggingLatencyUsageStats_",Kl,void 0);function Ll(){this.f=0}
function Ml(){Ll.f||(Ll.f=new Ll);return Ll.f}
Ll.prototype.tick=function(a,b,c){Nl(this,"tick_"+a+"_"+b)||Ti("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c})};
Ll.prototype.info=function(a,b){var c=Object.keys(a).join("");Nl(this,"info_"+c+"_"+b)||(c=Object.assign({},a),c.clientActionNonce=b,Ti("latencyActionInfo",c))};
Ll.prototype.span=function(a,b){var c=Object.keys(a).join("");Nl(this,"span_"+c+"_"+b)||(a.clientActionNonce=b,Ti("latencyActionSpan",a))};
function Nl(a,b){Kl[b]=Kl[b]||{count:0};var c=Kl[b];c.count++;c.time=T();a.f||(a.f=ig(function(){var d=T(),e;for(e in Kl)Kl[e]&&6E4<d-Kl[e].time&&delete Kl[e];a&&(a.f=0)},0,5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Yh("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||aj(c)),!0):!1}
;var Z={},Ol=(Z.ad_allowed="adTypesAllowed",Z.yt_abt="adBreakType",Z.ad_cpn="adClientPlaybackNonce",Z.ad_docid="adVideoId",Z.yt_ad_an="adNetworks",Z.ad_at="adType",Z.aida="appInstallDataAgeMs",Z.browse_id="browseId",Z.p="httpProtocol",Z.t="transportProtocol",Z.cpn="clientPlaybackNonce",Z.ccs="creatorInfo.creatorCanaryState",Z.cseg="creatorInfo.creatorSegment",Z.csn="clientScreenNonce",Z.docid="videoId",Z.GetHome_rid="requestIds",Z.GetSearch_rid="requestIds",Z.GetPlayer_rid="requestIds",Z.GetWatchNext_rid=
"requestIds",Z.GetBrowse_rid="requestIds",Z.GetLibrary_rid="requestIds",Z.is_continuation="isContinuation",Z.is_nav="isNavigation",Z.b_p="kabukiInfo.browseParams",Z.is_prefetch="kabukiInfo.isPrefetch",Z.is_secondary_nav="kabukiInfo.isSecondaryNav",Z.prev_browse_id="kabukiInfo.prevBrowseId",Z.query_source="kabukiInfo.querySource",Z.voz_type="kabukiInfo.vozType",Z.yt_lt="loadType",Z.mver="creatorInfo.measurementVersion",Z.yt_ad="isMonetized",Z.nr="webInfo.navigationReason",Z.nrsu="navigationRequestedSameUrl",
Z.ncnp="webInfo.nonPreloadedNodeCount",Z.pnt="performanceNavigationTiming",Z.prt="playbackRequiresTap",Z.plt="playerInfo.playbackType",Z.pis="playerInfo.playerInitializedState",Z.paused="playerInfo.isPausedOnLoad",Z.yt_pt="playerType",Z.fmt="playerInfo.itag",Z.yt_pl="watchInfo.isPlaylist",Z.yt_pre="playerInfo.preloadType",Z.yt_ad_pr="prerollAllowed",Z.pa="previousAction",Z.yt_red="isRedSubscriber",Z.rce="mwebInfo.responseContentEncoding",Z.scrh="screenHeight",Z.scrw="screenWidth",Z.st="serverTimeMs",
Z.ssdm="shellStartupDurationMs",Z.br_trs="tvInfo.bedrockTriggerState",Z.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Z.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Z.label="tvInfo.label",Z.is_mdx="tvInfo.isMdx",Z.preloaded="tvInfo.isPreloaded",Z.upg_player_vis="playerInfo.visibilityState",Z.query="unpluggedInfo.query",Z.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Z.yt_vst="videoStreamType",Z.vph="viewportHeight",Z.vpw="viewportWidth",Z.yt_vis="isVisible",Z.rcl="mwebInfo.responseContentLength",
Z.GetSettings_rid="requestIds",Z.GetTrending_rid="requestIds",Z.GetMusicSearchSuggestions_rid="requestIds",Z.REQUEST_ID="requestIds",Z),Pl="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Ql={},Rl=(Ql.ccs="CANARY_STATE_",
Ql.mver="MEASUREMENT_VERSION_",Ql.pis="PLAYER_INITIALIZED_STATE_",Ql.yt_pt="LATENCY_PLAYER_",Ql.pa="LATENCY_ACTION_",Ql.yt_vst="VIDEO_STREAM_TYPE_",Ql),Sl="all_vc ap c cver cbrand cmodel cplatform ctheme ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Tl(a){return!!Q("FORCE_CSI_ON_GEL",!1)||R("csi_on_gel")||!!El(a).useGel}
function Ul(a){a=El(a);if(!("gel"in a))a.gel={gelTicks:{},gelInfos:{}};else if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}return a.gel}
;function Vl(a,b,c){if(null!==b)if(Fl(c)[a]=b,Tl(c)){var d=b;b=Ul(c);if(b.gelInfos)b.gelInfos["info_"+a]=!0;else{var e={};b.gelInfos=(e["info_"+a]=!0,e)}if(a.match("_rid")){var f=a.split("_rid")[0];a="REQUEST_ID"}if(a in Ol){b=Ol[a];0<=Wa(Pl,b)&&(d=!!d);a in Rl&&"string"===typeof d&&(d=Rl[a]+d.toUpperCase());a=d;d=b.split(".");for(var g=e={},h=0;h<d.length-1;h++){var k=d[h];g[k]={};g=g[k]}g[d[d.length-1]]="requestIds"===b?[{id:a,endpoint:f}]:a;f=kl({},e)}else 0<=Wa(Sl,a)||aj(new Yh("Unknown label logged with GEL CSI",
a)),f=void 0;f&&Tl(c)&&(b=Jl(c||""),kl(b.info,f),b=Ul(c),"gelInfos"in b||(b.gelInfos={}),kl(b.gelInfos,f),c=Gl(c),Ml().info(f,c))}else Jl(c||"").info[a]=b}
function Wl(a,b,c){var d=Dl(c);if(R("use_first_tick")&&Xl(a,c))return d[a];if(!b&&"_"!==a[0]){var e=a;Al.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),Al.mark(e))}e=b||T();d[a]=e;e=Ul(c);e.gelTicks&&(e.gelTicks["tick_"+a]=!0);c||b||T();if(Tl(c)){Jl(c||"").tick[a]=b||T();e=Gl(c);if("_start"===a){var f=Ml();Nl(f,"baseline_"+e)||Ti("latencyActionBaselined",{clientActionNonce:e},{timestamp:b})}else Ml().tick(a,e,b);Hl(c);e=!0}else e=!1;if(!e){if(!z("yt.timing."+(c||"")+"pingSent_")&&
(f=Q((c||"")+"TIMING_ACTION",void 0),e=Dl(c),z("ytglobal.timing"+(c||"")+"ready_")&&f&&Xl("_start")&&Cl(c)))if(Hl(c),c)Yl(c);else{f=!0;var g=Q("TIMING_WAIT",[]);if(g.length)for(var h=0,k=g.length;h<k;++h)if(!(g[h]in e)){f=!1;break}f&&Yl(c)}Jl(c||"").tick[a]=b||T()}return d[a]}
function Xl(a,b){var c=Dl(b);return a in c}
function Yl(a){if(!Tl(a)){var b=Dl(a),c=Fl(a),d=b._start,e=Q("CSI_SERVICE_NAME","youtube"),f={v:2,s:e,action:Q((a||"")+"TIMING_ACTION",void 0)},g=c.srt;void 0!==b.srt&&delete c.srt;b.aft=Cl(a);var h=Dl(a),k=h.pbr,l=h.vc;h=h.pbs;k&&l&&h&&k<l&&l<h&&Fl(a).yt_pvis&&"youtube"===e&&(Vl("yt_lt","hot_bg",a),e=b.vc,k=b.pbs,delete b.aft,c.aft=Math.round(k-e));for(var m in c)"_"!==m.charAt(0)&&(f[m]=c[m]);b.ps=T();m={};e=[];for(var p in b)"_"!==p.charAt(0)&&(k=Math.round(b[p]-d),m[p]=k,e.push(p+"."+k));f.rt=
e.join(",");b=!!c.ap;R("debug_csi_data")&&(c=z("yt.timing.csiData"),c||(c=[],F("yt.timing.csiData",c)),c.push({page:location.href,time:new Date,args:f}));c="";for(var q in f)f.hasOwnProperty(q)&&(c+="&"+q+"="+f[q]);f="/csi_204?"+c.substring(1);if(window.navigator&&window.navigator.sendBeacon&&b){var r=void 0===r?"":r;sl(f,r)||rl(f,void 0,void 0,void 0,r)}else rl(f);y("yt.timing."+(a||"")+"pingSent_",!0,void 0);Gj(xl,new vl(m.aft+(Number(g)||0),a))}}
var Zl=window;Zl.ytcsi&&(Zl.ytcsi.info=Vl,Zl.ytcsi.tick=Wl);function $l(){var a=this;this.i=[];this.j=[];this.f=[];this.A=!1;this.l=[];this.g=this.m=!1;this.o=new Map;R("screen_manager_wait_for_csn")&&(R("web_lifecycles")&&jl[0].push(this.B),Ij("loggingScreenCreated",function(){a.B()}),Ij("clearWaitForNavigationJobs",function(){a.l=[]}))}
function am(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.g&&a.h&&a.h();var g=X(c),h=uj(c);g&&h&&(d.csn=g,(null===(e=d.response)||void 0===e?0:e.trackingParams)&&Sj(a.client,g,h,[pj(d.response.trackingParams)]),(null===(f=d.playerResponse)||void 0===f?0:f.trackingParams)&&Sj(a.client,g,h,[pj(d.playerResponse.trackingParams)]))})}
function bm(a,b,c,d){if(a.g&&!d)a.i.push([b,c]);else{var e=X(d);c=c||uj(d);e&&c&&Sj(a.client,e,c,[b])}}
function cm(a,b){var c=void 0===c?0:c;a.o.set(b,c);"UNDEFINED_CSN"===X(c)||a.g||bm(a,b,void 0,c)}
$l.prototype.clickCommand=function(a){var b=X();if(!a.clickTrackingParams||!b)return!1;Uj(this.client,b,pj(a.clickTrackingParams));return!0};
function dm(a,b,c){c=void 0===c?{}:c;a.g=!0;a.h=function(){em(a,b,c);var f=uj(c.layer);if(f){for(var g=u(a.i),h=g.next();!h.done;h=g.next())h=h.value,bm(a,h[0],h[1]||f,c.layer);f=u(a.j);for(g=f.next();!g.done;g=f.next()){h=g.value;g=h[0];var k=h[1];if(a.g)a.j.push([g,k]);else{var l=pj(g);if(h=X())g=a.client,k={csn:h,ve:l.getAsJson(),clientData:k},l={L:xj(h),M:h},"UNDEFINED_CSN"==h?Tj("visualElementStateChanged",k,l):g?Zg("visualElementStateChanged",k,g,l):Ti("visualElementStateChanged",k,l)}}}};
X(c.layer)||a.h();if(c.wa)for(var d=u(c.wa),e=d.next();!e.done;e=d.next())am(a,e.value,c.layer);else bj(Error("Delayed screen needs a data promise."))}
function em(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.fb?c.fb:c.layer;var e=X(d);d=uj(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));if(e&&"UNDEFINED_CSN"!==e&&d){var g=a.client,h=!0,k=(h=void 0===h?!1:h)?16:8;k={csn:e,ve:d.getAsJson(),eventType:k};h={L:xj(e),M:e,La:h};"UNDEFINED_CSN"==e?Tj("visualElementHidden",k,h):g?Zg("visualElementHidden",k,g,h):Ti("visualElementHidden",
k,h)}try{var l=a.client;g=f;var m=c.va,p=c.L,q=Qj(),r={csn:q,pageVe:(new oj({veType:b,youtubeData:void 0})).getAsJson()};g&&g.visualElement?r.implicitGesture={parentCsn:g.clientScreenNonce,gesturedVe:g.visualElement.getAsJson()}:g&&aj(new Yh("newScreen() parent element does not have a VE - rootVe",b));m&&(r.cloneCsn=m);m={L:p,M:q};l?Zg("screenCreated",r,l,m):Ti("screenCreated",r,m);Gj(Lj,new Nj(q));var A=q}catch(B){ej(B,{mk:b,rootVe:d,parentVisualElement:void 0,gk:e,lk:f,va:c.va});bj(B);return}yj(A,
b,c.layer,c.L);a.f[a.f.length-1]&&!a.f[a.f.length-1].csn&&(a.f[a.f.length-1].csn=A||"");R("screen_manager_wait_for_csn")&&(y("midTransition",!1,void 0),Gj("loggingScreenCreated"),a.m=!1);Vl("csn",A);hl.getInstance().clear();a.g=!1;a.h=void 0;b=uj(c.layer);e=u(a.o);for(f=e.next();!f.done;f=e.next())f=u(f.value),A=f.next().value,f.next().value===c.layer&&b&&bm(a,A,b,c.layer);R("c3_client_side_screens")&&!a.A&&(c=qj(49980),b=qj(49981),F("historyVes",{backButtonVe:c,forwardButtonVe:b}),cm(a,c),cm(a,b),
a.A=!0)}
$l.prototype.B=function(){for(var a=u(this.l),b=a.next();!b.done;b=a.next())b=b.value,b();this.l=[]};var fm=null,gm=null,hm=null,im={};function jm(a){var b=a.id;a=qj(a.ve_type);im[b]=a;b=X();var c=uj();b&&c&&Vj(b,c,a)}
function km(){var a=fm.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function lm(a){var b=a.csn;a=a.root_ve_type;if(b&&a&&(yj(b,a),a=uj()))for(var c in im){var d=im[c];d&&Vj(b,a,d)}}
function mm(a){im[a.id]=pj(a.tracking_params)}
function nm(a){var b=X();a=im[a.id];b&&a&&Uj(R("use_default_events_client")?void 0:Si,b,a)}
function om(a){a=a.ids;var b=X();if(b)for(var c=0;c<a.length;c++){var d=im[a[c]];if(d){var e=b,f=R("use_default_events_client")?void 0:Si;d={csn:e,ve:d.getAsJson(),eventType:1};var g={L:xj(e),M:e};"UNDEFINED_CSN"==e?Tj("visualElementShown",d,g):f?Zg("visualElementShown",d,f,g):Ti("visualElementShown",d,g)}}}
;y("yt.setConfig",P,void 0);y("yt.config.set",P,void 0);y("yt.setMsg",Ff,void 0);y("yt.msgs.set",Ff,void 0);y("yt.logging.errors.log",bj,void 0);
y("writeEmbed",function(){var a=Q("PLAYER_CONFIG",void 0);if(!a){var b=Q("PLAYER_VARS",void 0);b&&(a={args:b})}cl(!0);"gvn"==a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=Q("POST_MESSAGE_ORIGIN");window!=window.top&&c&&c!=document.URL&&(a.args.loaderUrl=c);if((c=Q("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){if(!c.serializedForcedExperimentIds){var d=
window.location.href;-1!=d.indexOf("?")?(d=(d||"").split("#")[0],d=d.split("?",2),d=fh(1<d.length?d[1]:d[0])):d={};d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}a=wk(a,c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,!1)}else a=wk(a);fm=a;a.addEventListener("onScreenChanged",lm);a.addEventListener("onLogClientVeCreated",jm);a.addEventListener("onLogServerVeCreated",mm);a.addEventListener("onLogVeClicked",nm);a.addEventListener("onLogVesShown",om);a.addEventListener("onVideoDataChange",
km);c=Q("POST_MESSAGE_ID","player");Q("ENABLE_JS_API")?hm=new Ok(a):Q("ENABLE_POST_API")&&"string"===typeof c&&"string"===typeof b&&(gm=new Pk(window.parent,c,b),hm=new Jk(a,gm.h));mg()},void 0);
var pm=Bf(function(){Wl("ol");var a=dl.getInstance(),b=!!((gl("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&Nd(document.body,"exp-invert-logo"))if(c&&!Nd(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Nd(d,"inverted-hdpi")){var e=Ld(d);Md(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Nd(document.body,"inverted-hdpi")&&Od();b!=c&&(b="f"+(Math.floor(119/31)+1),d=gl(b)||0,d=c?d|67108864:
d&-67108865,0==d?delete Y[b]:(c=d.toString(16),Y[b]=c.toString()),a.save());$l.f||($l.f=new $l);a=$l.f;c=16623;var f=void 0===f?{}:f;Object.values(Wj).includes(c)||(aj(new Yh("createClientScreen() called with a non-page VE",c)),c=83769);f.isHistoryNavigation||a.f.push({rootVe:c,key:f.key||""});a.i=[];a.j=[];R("screen_manager_wait_for_csn")&&(a.m||Gj("clearWaitForNavigationJobs"),F("midTransition",!0));f.wa?dm(a,c,f):em(a,c,f)}),qm=Bf(function(){var a=fm;
a&&a.sendAbandonmentPing&&a.sendAbandonmentPing();Q("PL_ATT")&&hj.dispose();a=0;for(var b=kg.length;a<b;a++){var c=kg[a];if(!isNaN(c)){var d=z("yt.scheduler.instance.cancelJob");d?d(c):Nf(c)}}kg.length=0;eg("//static.doubleclick.net/instream/ad_status.js");lg=!1;P("DCLKSTAT",0);Wc(hm,gm);if(a=fm)a.removeEventListener("onScreenChanged",lm),a.removeEventListener("onLogClientVeCreated",jm),a.removeEventListener("onLogServerVeCreated",mm),a.removeEventListener("onLogVeClicked",nm),a.removeEventListener("onLogVesShown",
om),a.removeEventListener("onVideoDataChange",km),a.destroy();im={}});
window.addEventListener?(window.addEventListener("load",pm),window.addEventListener("unload",qm)):window.attachEvent&&(window.attachEvent("onload",pm),window.attachEvent("onunload",qm));F("yt.abuse.player.botguardInitialized",z("yt.abuse.player.botguardInitialized")||ij);F("yt.abuse.player.invokeBotguard",z("yt.abuse.player.invokeBotguard")||jj);F("yt.abuse.dclkstatus.checkDclkStatus",z("yt.abuse.dclkstatus.checkDclkStatus")||ng);F("yt.player.exports.navigate",z("yt.player.exports.navigate")||zj);
F("yt.util.activity.init",z("yt.util.activity.init")||Ag);F("yt.util.activity.getTimeSinceActive",z("yt.util.activity.getTimeSinceActive")||Dg);F("yt.util.activity.setTimestamp",z("yt.util.activity.setTimestamp")||Bg);}).call(this);
