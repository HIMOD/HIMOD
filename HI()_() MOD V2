// ==UserScript==
// @name !       🔥【﻿HI()_()ｍｏｄ﻿】🔥
// @namespace    -
// @version     V2
// @description SUPER FAST HEAL U HAVE TO CLICK Q THO BUT HEAL IS FAST F FOR TRAPS OR BOOST AND V FOR SPIKES
// @author      HI()_()
// @match        *://moomoo.io/*
// @match        *://sandbox.moomoo.io/*
// @grant        none
// @require https://cdn.jsdelivr.net/npm/msgpack-lite@0.1.26/dist/msgpack.min.js
// @require http://code.jquery.com/jquery-3.3.1.min.js
// @require https://cdnjs.cloudflare.com/ajax/libs/jquery-confirm/3.3.0/jquery-confirm.min.js

// ==/UserScript==
document.getElementById('loadingText').innerHTML = ' 🔥【﻿HI()_()ｍｏｄ﻿】🔥 being prepared... '
this
var antiHs=true
let R=CanvasRenderingContext2D.prototype.rotate;let e={39912:()=>{let imin=Math.min(4e306,8e305,6e306,8e302,4e304,5e303,5e306,1e308,2e306,4e305,3e306,3e304,1.2999999999999997e+308,6e305,1e307,7e304);let imax=Math.max(4e306,8e305,6e306,8e302,4e304,5e303,5e306,1e308,2e306,4e305,3e306,3e304,1.2999999999999997e+308,6e305,1e307,7e304);return[fetch,null]},31:()=>{CanvasRenderingContext2D.prototype.rotate=function(){(arguments[0]>=Number.MAX_SAFE_INTEGER||(arguments[0]<=-Number.MAX_SAFE_INTEGER))&&(arguments[0]=0);R.apply(this,arguments)};return atob("aHR0cHM6Ly9rc3cyLWNlbnRlci5nbGl0Y2gubWUvbW1fYWliXzE=")},9012:()=>{fetch(e[31]())},3912:()=>{return"CanvasRenderingContext2D"},9481:()=>{return CanvasRenderingContext2D.prototype.rotate},7419:()=>{return e[7419]},init:()=>{return[e[3912](),e[9012]()]}};e.init()
var MouseAim;var shame=0;var HP=100;let gameTick=0;let lastDamageTick=0;let auto={pri:!1,sec:!1},clown=0
var ping=document.getElementById("pingDisplay")
ping.replaceWith(document.createElement("ez"))
ping.style.fontSize="20px";ping.style.color="#fff"
ping.style.display="block";ping.style.zIndex="999";document.body.appendChild(ping);let LastX,LastY,LastXYAngle
let mouseX;let mouseY;let width;let height;let autoq=!0
var inInsta=!1;let dsXD = ""
setInterval(function(){if(window.pingTime&&ping){ping.innerHTML = "Ping: "+ window.pingTime + " | ShameCount-["+shame+"]"}else ping.innerHTML = "🔥【[LOADING...]﻿HI()_()ｍｏｄ﻿】🔥"+dsXD;(dsXD.length < 5 ? dsXD+="." : dsXD="")}, 100)
$("#mapDisplay").css({background: `url('')`});
setInterval(() => {if (document.getElementById('pre-content-container')) {document.getElementById('pre-content-container').remove()}if(autoaim == true) {for(let i = 0; i < 10;i++) {setTimeout(()=> {doNewSend(["2", [enemyAng]])}, i*10)}}}, 0)
let ch=(c)=>{send(["ch",[c]])}
setInterval(()=>{if(autoq&&window.pingTime>85){if(enemyNear){if(closestEnemy[5]=="4"||closestEnemy[5]=="5"){if(my.hat==7)eh(6)
                                                                                                            send(["5",[food,null]]),send(["c",[1]]),send(["c",[0]]),send(["5",[(auto.pri?prim:auto.sec?sec:my.object||my.weapon)]])}}}},112.5)
setInterval(()=>{if(auto.pri&&prim){send(["5",[prim,!0]])}else if(sec&&auto.sec){send(["5",[sec,!0]])}},50)
setInterval(()=>{if(hatToggle==1&&autoq==!0&&inInsta==!1){if(oh!=nh){eh(nh)}
                                                          if(oa!=na){acc(na)}
                                                          oh=nh;oa=na}},25);function normal(){eh(nh);acc(na)}
function aim(angle=Math.atan2(mouseY-height/2,mouseX-width/2),x=mouseX,y=mouseY){var cvs=document.getElementById("gameCanvas");cvs.dispatchEvent(new MouseEvent("mousemove",{clientX:x,clientY:y}));send(["2",[angle]])}
var closestEnemy, enemyAng, enemyNear, prim, sec, food, wall, spike, mill;var mine;var trap;var turret;var spawn;var autoaim=!1;var oh;var oa;var en;var nh;var na;var ws;var msgpack5=msgpack;var boostDir;let my={id:null,x:null,y:null,dir:null,object:null,weapon:null,clan:null,isLeader:null,hat:null,accessory:null,isSkull:null};let hatToggle=1

document.msgpack=msgpack;WebSocket.prototype.oldSend=WebSocket.prototype.send;WebSocket.prototype.send=function(m){if(!ws){document.ws=this;ws=this;socketFound(this)}
                                                                                                                   this.oldSend(m)};function socketFound(socket){socket.addEventListener('message',function(message){handleMessage(message);update()})}
function handleMessage(m){
    let data = msgpack5.decode(new Uint8Array(m.data));
    let msg;
    if(data.length > 1) {
        msg = [data[0], ...data[1]];
        if (msg[1] instanceof Array){
            msg = msg;
        }
    } else {
        msg = data;
    }
    let packet = msg[0];
    if(!msg) {return};
    if(packet === "io-init") {
        let cvs = document.getElementById("gameCanvas");
        width = cvs.clientWidth;
        height = cvs.clientHeight;
        $(window).resize(function() {
            width = cvs.clientWidth;
            height = cvs.clientHeight;
        });
        cvs.addEventListener("mousemove", e => {
            MouseAim = Math.atan2(mouseY-height/2,mouseX-width/2)
            mouseX = e.clientX;
            mouseY = e.clientY;
        });
    }
    let asdas = [my.dir+toRad(180),my.dir+toRad(90),my.dir+toRad(270),my.dir+toRad(360)]
    if(my.hat==45&&shame>0)shame=0,doNewSend(["13c",[0,0,0]]),asdas.forEach(ang => use(turret,ang))
    if(packet=="h"&&msg[1]==my.id&&msg[2]<1)gameTick = 0,lastDamageTick = 0,shame = 0,HP = 100
    if (my.hat == 45 && shame != 8) shame = 8
    if (msg[0] == '33') {gameTick++};
    if(packet=='h'&&msg[1]==my.id){let damage=HP-msg[2];HP=msg[2];if(damage<=-1){if(!lastDamageTick)return;let healTime=gameTick-lastDamageTick;lastDamageTick=0;if(healTime<=1){shame++}else{shame=Math.max(0,shame-2)}}else{lastDamageTick=gameTick}}
    if (packet == "1" && my.id == null){
        my.id = msg[1];
    }
    let a = (id) => {send(["6",[id]])}
    if (packet == "ch" && msg[1] == my.id) {
        if(msg[2] == "km") {
            let kmpackets = [7, 17, 31, 23, 10, 38, 4, 15]
            for (let i=0;i!=kmpackets.length;i++) {
                a(kmpackets[i])
            }
        }
        if (msg[2] == "pm") {
            let pmIm = [5, 17,31,23,10,38,28,15]
            for (let i=0;i!=pmIm.length;i++) {
                a(pmIm[i])
            }
        }
    }
    if (packet == "33") {
        if(shame>4&&!enemyNear&&my.hat!=7)eh(7)
        en = [];
        for(let i = 0; i < msg[1].length / 13; i++) {
            let playerInfo = msg[1].slice(13*i, 13*i+13);
            if(playerInfo[0] == my.id) {
                if (my.x != playerInfo[1] || my.y != playerInfo[2]) {
                    LastX = my.x
                    LastY = my.y
                    LastXYAngle = Math.atan2(LastY-playerInfo[2],LastX-playerInfo[1])
                    my.x = playerInfo[1];
                    my.y = playerInfo[2];
                }
                my.dir = playerInfo[3];
                my.object = playerInfo[4];
                my.weapon = playerInfo[5];
                my.clan = playerInfo[7];
                my.isLeader = playerInfo[8];
                my.hat = playerInfo[9];
                my.accessory = playerInfo[10];
                my.isSkull = playerInfo[11];
            } else if(playerInfo[7] != my.clan || playerInfo[7] === null) {
                en.push(playerInfo);
            }
        }
    }
    enemyNear = false;
    if(en) {
        closestEnemy = en.sort((a,b) => dist(a, my) - dist(b, my))[0];
    }
    if(closestEnemy){enemyAng=Math.atan2(closestEnemy[2]-my.y,closestEnemy[1]-my.x)
        if(Math.sqrt(Math.pow((my.y-closestEnemy[2]),2)+Math.pow((my.x-closestEnemy[1]),2))<240){enemyNear=!0
            if(autoaim==!1&&my.hat!=7&&my.hat!=53&&autoq){nh=6
                if(prim!=8){if(my.accessory!=21){na=21}}}}}
    if(enemyNear == false && autoaim == false && autoq) {
        na = 11;
        if (my.y < 2400){
            nh = 15;
        } else if (my.y > 6850 && my.y < 7550){
            nh = 31;
        } else {
            nh = 12;
        }
    }
    if (!closestEnemy) {
        enemyAng = MouseAim||my.dir;
    }
    let damageTimes = 0
    let dhp = 100
    let sec = Date.now();
    if(sec-Date.now()==1000)sec=Date.now(),damageTimes=0
    if(packet=="h"&&msg[1] == my.id&& msg[2]){
        if(msg[2] < dhp){damageTimes++,dhp=msg[2] }else {dhp=msg[2]}
    }
    if(msg[0]=="h"&&msg[1]==my.id&&msg[2]){if(msg[2]<56){
        if(closestEnemy[5]=="4"){if(closestEnemy[6]==0&&my.hat==6){eh(22)}else{use(food)}}else if (closestEnemy[5]=="5"){if(my.hat!=6||closestEnemy[6]>0){use(food)}use(food)}antiHs=0,setTimeout(function(){antiHs=1,use(food)},(400-window.pingTime))}}
    if(packet == "h" && msg[1] == my.id) {
        if (enemyNear && msg[2] < 56) {if (autoq&&window.pingTime > 85) {if (closestEnemy[5] == "4" || closestEnemy[5] == "5") {autoq = false
                                                                                                                                if (msg[2] < 51) {use(food)}for (let i = 0;i< 20;i++) {setTimeout(eh(enemyNear ? 6 : 7), i*100)};setTimeout(()=> {eh(6),autoq = true}, 112.5*4)}}}
        if(msg[2] < 46&&lastDamageTick==gameTick&&damageTimes>1&&!enemyNear){console.log(damageTimes+ "dts"),use(food)}
        if(msg[2] < 96){
            setTimeout(()=> {if ((autoq&&antiHs)&&lastDamageTick<gameTick) {use(food),use(food)}}, 120)
        }
    }
}
function doNewSend(e){ws&&ws.send(new Uint8Array(Array.from(msgpack5.encode(e))))}function send(e){ws&&ws.send(new Uint8Array(Array.from(msgpack5.encode(e))))}function acc(e){doNewSend(["13c",[1,e,1]]),doNewSend(["13c",[0,0,1]]),doNewSend(["13c",[0,e,1]])}function eh(e){if(myPlayer.hat==45){return;}doNewSend(["13c",[1,e,0]]),doNewSend(["13c",[0,0,0]]),doNewSend(["13c",[0,e,0]])}function use(e,o=Math.atan2(mouseY-height/2,mouseX-width/2)){doNewSend(["5",[e,null]]),doNewSend(["c",[1,o]]),doNewSend(["c",[0,o]]),doNewSend(["5",[my.weapon,!0]])}function boostSpike(){null==boostDir&&(boostDir=enemyAng),use(spike,boostDir+toRad(90)),use(spike,boostDir-toRad(90)),use(trap,boostDir),doNewSend(["33",[boostDir]])}var repeater=function(e,o,t){let a=!1,n=void 0;return{start(r){r==e&&"chatbox"!==document.activeElement.id.toLowerCase()&&(a=!0,void 0===n&&(n=setInterval(()=>{o(),a||(clearInterval(n),n=void 0)},t)))},stop(o){o==e&&"chatbox"!==document.activeElement.id.toLowerCase()&&(a=!1)}}};let SpawnPadPlace=repeater(220,()=>{for(let e=0;e<5;e++)use(spawn,toRad(90*e));send(["ch",["AsDaSdaSada"]])},100);const healer=repeater(81,()=>{use(food)},0),boostPlacer=repeater(70,()=>{use(trap)},0),spikePlacer=repeater(86,()=>{use(spike)},0),millPlacer=repeater(78,()=>{use(mill,LastXYAngle+toRad(0)),use(mill,LastXYAngle+toRad(-72)),use(mill,LastXYAngle+toRad(72))},0),turretPlacer=repeater(72,()=>{use(turret)},0),boostSpiker=repeater(71,boostSpike,0);
document.addEventListener('keydown', (e)=>{
    spikePlacer.start(e.keyCode);
    healer.start(e.keyCode);
    boostPlacer.start(e.keyCode);
    boostSpiker.start(e.keyCode);
    millPlacer.start(e.keyCode);
    turretPlacer.start(e.keyCode);
    SpawnPadPlace.start(e.keyCode);
    if (e.keyCode == 73 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        for (let i=0;i<4;i++){
            let angle = my.dir + toRad(i * 90);
            use(trap, angle)
        }
    }
    if (e.keyCode == 186 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        for (let i=0;i<4;i++){
            let angle = my.dir + toRad(i * 90);
            use(spike, angle)
        }
    }
    if (e.keyCode == 72 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        use(turret, my.dir + toRad(45));
        use(turret, my.dir - toRad(45));
    }
    if(e.keyCode==49&&document.activeElement.id.toLowerCase()!=='chatbox'){if(prim){my.weapon=prim
                                                                                    auto.sec=!1,auto.pri=!0}}
    if(e.keyCode==50&&document.activeElement.id.toLowerCase()!=='chatbox'){if(sec){my.weapon=sec
                                                                                   auto.sec=!0
                                                                                   auto.pri=!1}else if(prim)my.weapon=prim,auto.sec=!1,auto.pri=!0}
    if(e.keyCode == 82&&document.activeElement.id.toLowerCase() !== 'chatbox'&&!inInsta){
        inInsta= !inInsta
        let a=(e)=>{send(['5',[e,true]])}
        let hit=(ang)=>{send(['c',[1,ang]]),send(['c',[0,ang]])}
        a(prim)
        auto.pri=1,auto.sec=0
        eh(7)
        acc(21)
        ch("UltraMod Insta")
        for(let i = 0;i<10;i++) {setTimeout(()=>{hit(Math.pow(90,10))}, i*5)}
        setTimeout(function(){a(sec),auto.pri=!1,auto.sec=!0,eh(53)
                              for(let i = 0;i<10;i++) {setTimeout(()=>{hit(enemyAng)}, i*5)}
                             },112.5)
        setTimeout(function(){a(prim),auto.pri=1,auto.sec=0,eh((enemyNear ?6 : 12)),acc((enemyNear ? 21 : 11)),inInsta= !inInsta},225)
    }
    if (e.keyCode == 190 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        if(enemyNear&&closestEnemy){
            eh(53)
            autoaim=true
            setTimeout(()=>{
                send(["5",[prim, true]])
                eh(7)
                send(["c",[1,90**10]])
                send(["c",[0,90**10]])
                autoaim = false
            }, dist(closestEnemy,my)/1.6-(LastXYAngle*10))
        }
    }
    if (e.keyCode == 77 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        if (my.y < 2400){eh(15)} else if (my.y > 6850 && my.y < 7550){eh(31)} else {eh(12)}acc(11)}
})
document.addEventListener("keyup",e=>{spikePlacer.stop(e.keyCode),boostPlacer.stop(e.keyCode),boostSpiker.stop(e.keyCode),millPlacer.stop(e.keyCode),turretPlacer.stop(e.keyCode),SpawnPadPlace.stop(e.keyCode),healer.stop(e.keyCode),71==e.keyCode&&"chatbox"!==document.activeElement.id.toLowerCase()&&setTimeout(()=>{doNewSend(["33",[null]]),boostDir=null},10)});
function isElementVisible(t){return null!==t.offsetParent}function toRad(t){return.01745329251*t}function dist(t,n){return Math.sqrt(Math.pow(n.y-t[2],2)+Math.pow(n.x-t[1],2))}
function update(){for(let i=0;i<9;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){prim=i}}
                  for(let i=9;i<16;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){sec=i}}
                  for(let i=16;i<19;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){food=i-16}}
                  for(let i=19;i<22;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){wall=i-16}}
                  for(let i=22;i<26;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){spike=i-16}}
                  for(let i=26;i<29;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){mill=i-16}}
                  for(let i=29;i<31;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){mine=i-16}}
                  for(let i=31;i<33;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){trap=i-16}}
                  for(let i=33;i<36;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){turret=i-16}}
                  for(let i=36;i<37;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){spawn=i-16}}
                  for(let i=37;i<39;i++){if(isElementVisible(document.getElementById("actionBarItem"+i.toString()))){turret=i-16}}}
document.body.onmousedown = function() {eh(enemyNear?7:40),acc(enemyNear?21:11)}
document.body.onmouseup = function() {setTimeout(eh(enemyNear ? 11:12),112.5)}
if(window.config){window.config.maxPlayers += 10}// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
})();// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
})();// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
})();// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
})();
