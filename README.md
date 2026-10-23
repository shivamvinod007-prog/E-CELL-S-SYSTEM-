# E-CELL-S-SYSTEM-
S-SYSTEM 
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>S System</title>
<style>
:root{--v:#03050c;--pn:rgba(8,16,32,.88);--ed:#1f4a73;--ink:#e4f1ff;--mu:#7f98b8;--cy:#3fe0ff;--mg:#ff4fd8;--am:#ffb347;--gr:#5dffb0;--rd:#ff5d6c;--h:"Chakra Petch","Orbitron","Segoe UI",system-ui,sans-serif;--m:ui-monospace,"JetBrains Mono",Consolas,monospace}
*{box-sizing:border-box;margin:0;padding:0}
html,body{min-height:100%}
body{background:var(--v);color:var(--ink);font:14px/1.5 system-ui,-apple-system,"Segoe UI",sans-serif;padding:env(safe-area-inset-top) 0 env(safe-area-inset-bottom);overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(800px 500px at 10% -10%,rgba(63,224,255,.14),transparent 70%),radial-gradient(700px 500px at 100% 30%,rgba(255,79,216,.09),transparent 70%),linear-gradient(rgba(63,224,255,.05) 1px,transparent 1px) 0 0/42px 42px,linear-gradient(90deg,rgba(63,224,255,.05) 1px,transparent 1px) 0 0/42px 42px}
body::after{content:"";position:fixed;inset:0;z-index:60;pointer-events:none;background:repeating-linear-gradient(transparent 0 2px,rgba(0,0,0,.12) 3px);mix-blend-mode:multiply}
#st{position:fixed;inset:0;width:100%;height:100%;z-index:0;pointer-events:none}
button,input,select{font:inherit;color:inherit}
[hidden]{display:none!important}
.w{position:relative;z-index:1;max-width:1100px;margin:0 auto;padding:14px 14px 90px}
header{display:flex;justify-content:space-between;align-items:center;gap:10px;margin-bottom:12px;flex-wrap:wrap}
.br{display:flex;align-items:center;gap:10px}
.br svg{width:42px;height:42px;filter:drop-shadow(0 0 8px var(--cy))}
h1{font:700 clamp(20px,5vw,28px)/1 var(--h);letter-spacing:.12em}
h1 b{color:var(--cy);text-shadow:0 0 14px var(--cy)}
.tg{font:11px var(--h);letter-spacing:.2em;color:var(--mu)}
.hr{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.bd{font:600 12px var(--h);border:1px solid var(--cy);color:var(--cy);padding:3px 10px;border-radius:3px;letter-spacing:.1em}
.gh{background:transparent;border:1px solid var(--ed);border-radius:4px;padding:6px 12px;cursor:pointer;font:13px var(--h)}
.gh:hover{border-color:var(--cy);background:rgba(63,224,255,.1)}.gh.dg:hover{border-color:var(--rd);background:rgba(255,93,108,.12)}
.bt{background:var(--cy);color:#03121a;border:0;border-radius:4px;padding:8px 16px;cursor:pointer;font:700 13px var(--h);letter-spacing:.06em;box-shadow:0 0 14px rgba(63,224,255,.45)}
.bt.am{background:var(--am);box-shadow:0 0 14px rgba(255,179,71,.4)}.bt:disabled{opacity:.45;box-shadow:none}
.pn{--c:14px;background:var(--ed);clip-path:polygon(var(--c) 0,100% 0,100% calc(100% - var(--c)),calc(100% - var(--c)) 100%,0 100%,0 var(--c));margin-bottom:12px}
.pn>.i{margin:1px;padding:16px;background:var(--pn);backdrop-filter:blur(8px);clip-path:inherit}
h2{font:600 12px var(--h);letter-spacing:.18em;text-transform:uppercase;color:var(--cy);margin-bottom:10px;display:flex;align-items:center;gap:10px}
h2::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,var(--ed),transparent)}
.am h2,.pn.am h2{color:var(--am)}
.g{display:grid;gap:12px}
@media(min-width:860px){.g2{grid-template-columns:1fr 1fr}}
.fl{display:flex;gap:8px;flex-wrap:wrap;align-items:flex-end}
.f{display:flex;flex-direction:column;gap:3px;flex:1 1 130px;font:11px var(--h);letter-spacing:.08em;color:var(--mu)}
input,select{background:rgba(3,5,12,.7);border:1px solid var(--ed);border-radius:4px;padding:8px 10px;width:100%;min-width:0;font-size:14px}
textarea{background:rgba(3,5,12,.7);border:1px solid var(--ed);border-radius:4px;padding:8px 10px;width:100%;min-width:0;font:14px inherit;color:inherit;resize:vertical;min-height:80px}.po{padding:12px 0;border-bottom:1px solid rgba(31,74,115,.45)}.po:last-child{border:0}.po img{width:100%;border-radius:6px;margin:8px 0;display:block}
input:focus,select:focus,textarea:focus{outline:none;border-color:var(--cy);box-shadow:0 0 8px rgba(63,224,255,.35)}
.nav{position:fixed;left:0;right:0;bottom:0;z-index:20;display:flex;background:rgba(3,7,16,.96);border-top:1px solid var(--ed);padding-bottom:env(safe-area-inset-bottom)}
.nav button{flex:1;background:none;border:0;color:var(--mu);padding:10px 2px 8px;cursor:pointer;font:600 10px var(--h);letter-spacing:.05em;display:flex;flex-direction:column;align-items:center;gap:3px}
.nav button i{font-style:normal;font-size:18px}.nav button.on{color:var(--cy);text-shadow:0 0 10px var(--cy)}
.vw{display:none}.vw.on{display:block}
.id{display:flex;gap:14px;align-items:center}
.av{width:72px;height:72px;border-radius:50%;border:2px solid var(--cy);box-shadow:0 0 16px rgba(63,224,255,.4);display:grid;place-items:center;font:700 28px var(--h);background:radial-gradient(circle at 35% 30%,#1f6a85,#0a2233);flex:none}
.nm{font:700 20px var(--h);overflow-wrap:anywhere}.sb{color:var(--mu);font-size:12px;font-family:var(--h);letter-spacing:.1em}
.sp{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:12px}
.sx{border:1px solid var(--ed);border-radius:4px;padding:8px 10px;background:rgba(3,5,12,.5)}
.sx small{display:block;font:10px var(--h);letter-spacing:.12em;color:var(--mu)}.sx b{font:700 22px var(--m);color:var(--cy)}.sx.a b{color:var(--am)}
.mt{height:4px;background:rgba(255,255,255,.1);margin-top:5px;border-radius:2px;overflow:hidden}.mt i{display:block;height:100%;background:var(--cy);transition:width .5s}
.rw{max-width:400px;margin:0 auto}svg.rd{width:100%;display:block;overflow:visible}
.sw{transform-origin:180px 170px;animation:sp 6s linear infinite}@keyframes sp{to{transform:rotate(360deg)}}
.gw{display:flex;gap:14px;align-items:center}
.ga{position:relative;width:130px;height:130px;flex:none}.ga svg{transform:rotate(-90deg);width:100%}
.ga .c{position:absolute;inset:0;display:grid;place-items:center;text-align:center;font:700 34px var(--h);line-height:1}.ga .c span{display:block;font-size:17px}
.ab{margin-top:10px}.ab .l{display:flex;justify-content:space-between;font:600 13px var(--h)}.ab small{color:var(--mu);font-size:11px}
input[type=range]{-webkit-appearance:none;appearance:none;height:26px;background:transparent;padding:0;border:0;--f:50%;cursor:pointer}
input[type=range]::-webkit-slider-runnable-track{height:6px;border-radius:3px;background:linear-gradient(90deg,var(--cy) var(--f),rgba(255,255,255,.12) var(--f))}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:18px;height:18px;margin-top:-6px;border-radius:50%;background:var(--v);border:2px solid var(--cy);box-shadow:0 0 10px var(--cy)}
input[type=range]:disabled::-webkit-slider-thumb{width:0;height:0;border:0;box-shadow:none}
input[type=range]::-moz-range-track{height:6px;border-radius:3px;background:linear-gradient(90deg,var(--cy) var(--f),rgba(255,255,255,.12) var(--f))}
input[type=range]::-moz-range-thumb{width:14px;height:14px;border-radius:50%;background:var(--v);border:2px solid var(--cy)}
table{width:100%;border-collapse:collapse;font-size:13px}th{font:600 11px var(--h);letter-spacing:.1em;color:var(--mu);text-align:left;padding:6px;border-bottom:1px solid var(--ed)}
td{padding:8px 6px;border-bottom:1px solid rgba(31,74,115,.45)}tr.me{background:rgba(63,224,255,.1)}tbody tr[data-id]{cursor:pointer}
.mo{font-family:var(--m);color:var(--cy)}
.li{display:flex;justify-content:space-between;gap:10px;padding:9px 0;border-bottom:1px solid rgba(31,74,115,.45);align-items:center}.li:last-child{border:0}
.li b{font-size:13px}.li small{display:block;color:var(--mu);font-size:11px}
.tag{font:700 10px var(--h);letter-spacing:.08em;padding:2px 8px;border-radius:3px;text-transform:uppercase;border:1px solid}
.ok{color:var(--gr)}.er{color:var(--rd)}.wr{color:var(--am)}
.em{text-align:center;color:var(--mu);font:12px var(--h);letter-spacing:.1em;padding:8px}
.lg{font:12px/1.7 var(--h);border-left:2px solid var(--ed);padding-left:10px;margin-top:10px;min-height:70px}.lg em{font-style:normal;color:var(--mu);margin-right:8px}
.sc{overflow-x:auto}
#toast{position:fixed;left:50%;bottom:calc(74px + env(safe-area-inset-bottom));transform:translate(-50%,20px);opacity:0;z-index:70;background:var(--pn);border:1px solid var(--cy);padding:8px 16px;border-radius:4px;font:13px var(--h);pointer-events:none;transition:.2s;max-width:90vw;text-align:center}#toast.s{opacity:1;transform:translate(-50%,0)}
#gate,#modal{position:fixed;inset:0;z-index:50;display:grid;place-items:center;padding:20px;background:rgba(3,5,12,.94)}#modal{z-index:55;background:rgba(3,5,12,.8)}
.gb{width:min(380px,100%)}.gb svg{width:64px;display:block;margin:0 auto 6px;filter:drop-shadow(0 0 10px var(--cy))}
.gb h3{font:700 22px var(--h);letter-spacing:.2em;text-align:center}.gb h3 b{color:var(--cy)}.gb p{text-align:center;color:var(--mu);font-size:12px;margin:4px 0 12px}
.me2{color:var(--rd);font-size:12px;min-height:18px;margin:6px 0}
body.lk .w,body.lk .nav{filter:blur(6px);pointer-events:none}body:not(.lk) #gate{display:none}
.ad{display:none}body.adm .ad{display:block}body.adm .ad.fl{display:flex}
#boot{position:fixed;inset:0;z-index:80;background:var(--v);display:grid;place-items:center;font:13px/1.9 var(--m);color:var(--cy);transition:opacity .5s}#boot.o{opacity:0;pointer-events:none}
#boot .bl div{opacity:0;animation:fi .3s forwards}@keyframes fi{to{opacity:1}}
.bar{height:3px;background:rgba(255,255,255,.1);margin-top:10px}.bar i{display:block;height:100%;width:0;background:var(--cy);box-shadow:0 0 10px var(--cy);animation:bw 1.6s forwards}@keyframes bw{to{width:100%}}
@media(prefers-reduced-motion:reduce){.sw,#boot .bl div,.bar i{animation:none}#boot .bl div{opacity:1}.bar i{width:100%}}

/* lock screen */
#boot{display:flex;align-items:center;justify-content:center;overflow:hidden;background:radial-gradient(520px 420px at 50% 62%,rgba(63,224,255,.16),transparent 70%),var(--v)}
.lsw{width:min(340px,86vw);text-align:center;position:relative}
.lsc{font:300 clamp(54px,18vw,76px)/1 var(--h);letter-spacing:.08em;color:#fff;text-shadow:0 0 18px rgba(63,224,255,.75)}
.lsdt{font:11px var(--h);letter-spacing:.24em;color:var(--mu);margin-top:6px}
.holo{height:140px;display:grid;place-items:center;margin:10px 0 4px}
.holo svg{width:min(76vw,290px);overflow:visible;transform:perspective(520px) rotateX(66deg);filter:drop-shadow(0 0 10px rgba(63,224,255,.75))}
.vb{transform-box:view-box;transform-origin:150px 150px;animation:sp 9s linear infinite}.vb.rv{animation-duration:16s;animation-direction:reverse}
.fb{transform-box:fill-box;transform-origin:center;animation:sp 3s linear infinite}.fb.rv{animation-direction:reverse;animation-duration:5s}
.bl{text-align:left}
.tl5{display:flex;gap:6px;justify-content:center;margin-top:12px;flex-wrap:wrap}
.tl5 i{font:normal 8px var(--m);border:1px solid rgba(63,224,255,.4);padding:3px 6px;color:var(--cy);background:rgba(63,224,255,.06)}
.lsh{font:11px var(--h);letter-spacing:.3em;color:var(--mu);margin-top:14px;animation:bk 1.6s ease-in-out infinite}@keyframes bk{50%{opacity:.25}}
.bar i{animation-duration:3s}
.pt{position:absolute;bottom:-6px;width:3px;height:3px;border-radius:50%;background:#bff;box-shadow:0 0 6px var(--cy);animation:rise linear infinite}@keyframes rise{from{opacity:.9}to{transform:translateY(-105vh);opacity:0}}
.lsb{position:relative;display:block;margin:16px auto 0;min-width:190px;padding:11px 28px;cursor:pointer;background:linear-gradient(90deg,rgba(63,224,255,.18),rgba(47,123,255,.28));border:1px solid var(--cy);color:#fff;font:700 13px var(--h);letter-spacing:.32em;text-indent:.32em;clip-path:polygon(12px 0,100% 0,100% calc(100% - 12px),calc(100% - 12px) 100%,0 100%,0 12px);box-shadow:inset 0 0 14px rgba(63,224,255,.35);text-shadow:0 0 10px var(--cy);transition:.2s}
.lsb:hover,.lsb:focus-visible{background:linear-gradient(90deg,rgba(63,224,255,.4),rgba(47,123,255,.5));outline:none;letter-spacing:.38em}
.lsb:active{transform:scale(.97)}
/* polish */
.pn>.i{position:relative}
.pn>.i::after{content:"";position:absolute;right:6px;bottom:6px;width:16px;height:16px;border-right:2px solid var(--cy);border-bottom:2px solid var(--cy);opacity:.45;pointer-events:none}
.pn.am>.i::after{border-color:var(--am)}
.bt,.gh,.nav button{transition:.18s}.bt:hover{filter:brightness(1.12);box-shadow:0 0 22px rgba(63,224,255,.65)}.bt:active,.gh:active{transform:scale(.97)}
button:focus-visible,input:focus-visible,select:focus-visible{outline:2px solid var(--cy);outline-offset:2px}
.nav button{position:relative}.nav button.on::before{content:"";position:absolute;top:0;left:22%;right:22%;height:2px;background:var(--cy);box-shadow:0 0 10px var(--cy)}
.nav button.on i{transform:translateY(-1px) scale(1.12)}
.sx{position:relative;border-left:2px solid var(--cy)}.sx.a{border-left-color:var(--am)}
tr.me{box-shadow:inset 3px 0 0 var(--cy)}tbody tr[data-id]:hover{background:rgba(63,224,255,.06)}
.li{transition:background .18s}.li:hover{background:rgba(63,224,255,.04)}
.idc-m button{transition:.18s}.idc-m button:hover{background:rgba(63,224,255,.1);padding-left:12px}
/* access granted */
#acc{position:fixed;inset:0;z-index:75;display:grid;place-items:center;background:rgba(3,5,12,.9);opacity:0;pointer-events:none;transition:opacity .25s}#acc.on{opacity:1}
.acc-i{width:min(300px,84vw);font:13px/1.9 var(--m);color:var(--cy)}.acc-i svg{width:120px;display:block;margin:0 auto 10px;filter:drop-shadow(0 0 10px var(--cy))}
.acc-t{font:700 20px var(--h);letter-spacing:.2em;color:#fff;text-align:center;margin-bottom:8px}#accs{min-height:64px}
.idc-w{display:grid;place-items:center;margin:0 0 12px}.idc-w svg{width:110px;filter:drop-shadow(0 0 10px var(--cc))}
/* HUD marker on panel titles */
h2::before{content:"";width:7px;height:7px;background:currentColor;transform:rotate(45deg);box-shadow:0 0 8px currentColor;flex:none}
/* identity card */
#idc{--cc:#3fe0ff;max-width:640px;margin:0 auto}
.idc-card{--k:22px;background:var(--cc);padding:1px;clip-path:polygon(0 0,calc(100% - var(--k)) 0,100% var(--k),100% 100%,var(--k) 100%,0 calc(100% - var(--k)));margin-bottom:10px}
.idc-in{position:relative;overflow:hidden;clip-path:inherit;padding:12px 14px 16px;background:linear-gradient(135deg,color-mix(in srgb,var(--cc) 20%,#04101c),color-mix(in srgb,var(--cc) 7%,#030812)),var(--v)}
.idc-in::before{content:"";position:absolute;inset:0;background:linear-gradient(var(--cc) 1px,transparent 1px) 0 0/100% 18px;opacity:.07;pointer-events:none}
.idc-hex{position:absolute;right:-30px;top:30px;width:230px;color:var(--cc);opacity:.15}
.idc-t{position:relative;text-align:right;font:italic 600 11px var(--h);letter-spacing:.08em;color:var(--cc);border-bottom:1px solid color-mix(in srgb,var(--cc) 50%,transparent);padding-bottom:4px;margin-bottom:12px}
.idc-row{display:flex;gap:14px;position:relative}
.idc-ph{flex:none;width:92px;height:116px;border:1px solid var(--cc);position:relative;overflow:hidden;display:grid;place-items:center;background:radial-gradient(circle at 50% 30%,color-mix(in srgb,var(--cc) 35%,#0a2233),#06101c)}
.idc-ph b{font:700 44px var(--h);color:var(--cc);text-shadow:0 0 14px var(--cc)}
.idc-ph i{position:absolute;left:0;right:0;top:0;height:2px;background:var(--cc);box-shadow:0 0 10px var(--cc);animation:scn 2.6s ease-in-out infinite}@keyframes scn{50%{top:calc(100% - 2px)}}
.idc-f{flex:1;min-width:0}.idc-f div{border-bottom:1px solid color-mix(in srgb,var(--cc) 45%,transparent);padding:2px 0 4px;margin-bottom:6px}
.idc-f small{display:block;font:10px var(--h);color:var(--mu)}.idc-f b{font:600 15px var(--h);overflow-wrap:anywhere}
.idc-pt{display:flex;gap:10px;background:rgba(5,10,20,.92);border:1px solid var(--ed);padding:10px;margin-bottom:12px}
.idc-m{display:flex;flex-direction:column;gap:6px;flex:0 0 112px}
.idc-m button{background:rgba(255,255,255,.04);border:0;border-left:3px solid var(--ed);color:var(--mu);text-align:left;padding:9px 8px;font:600 10px var(--h);letter-spacing:.08em;text-transform:uppercase;cursor:pointer}
.idc-m button:first-child,.idc-m button:hover{color:var(--ink);border-color:var(--cc)}
.idc-d{flex:1;min-width:0;display:flex;flex-direction:column;justify-content:center;background:#050b1a;border:1px solid var(--ed);padding:12px}
.idc-n{text-align:right;font:500 clamp(28px,9vw,52px)/1 system-ui,var(--h);color:#fff;text-shadow:0 0 18px color-mix(in srgb,var(--cc) 70%,transparent);font-variant-numeric:tabular-nums}.idc-n em{font:normal 14px var(--h);margin-left:8px;color:var(--mu)}
.idc-b{height:4px;background:rgba(255,255,255,.08);margin-top:10px}.idc-b i{display:block;height:100%;width:0;background:#2f7bff;box-shadow:0 0 10px #2f7bff;transition:width .9s}
.vw.on .idc-card{animation:ci .6s cubic-bezier(.2,.8,.2,1)}@keyframes ci{from{opacity:0;transform:translateY(14px) scale(.98)}}
@media(prefers-reduced-motion:reduce){.vb,.fb,.idc-ph i,.lsh,.vw.on .idc-card{animation:none}.pt{display:none}}
/* v3 */
.idc-d{min-height:112px;padding:16px 18px}.idc-n{font-size:clamp(44px,14vw,80px);white-space:nowrap}.idc-n em{font-size:15px}
.idc-w circle{stroke:var(--cc)}.idc-w circle:nth-child(2){stroke:var(--cc)}.idc-w circle:last-child{fill:var(--cc);stroke:none}.idc-w svg{filter:drop-shadow(0 0 10px var(--cc))}
.idx{margin-top:12px}.idx .pn:last-child{margin-bottom:0}
.ib{display:grid;grid-template-columns:76px 1fr 30px;gap:10px;align-items:center;margin-bottom:9px;font:600 12px var(--h)}.ib span{color:var(--mu)}.ib b{text-align:right;font-family:var(--m)}
.ibt{height:6px;background:rgba(255,255,255,.1);border-radius:3px;overflow:hidden}.ibt i{display:block;height:100%;animation:bf .9s both}@keyframes bf{from{width:0}}
#ispk svg{width:100%;height:70px;display:block}
#scan{padding:4px 14px;font-size:11px;letter-spacing:.12em;border-radius:3px}.lg{min-height:0}.lg:empty{display:none}
#v-core .av{width:58px;height:58px;font-size:24px}
.gchip{margin-left:auto;text-align:right;font:700 26px var(--h);line-height:1}.gchip small{display:block;font:10px var(--h);color:var(--mu);letter-spacing:.14em;margin-top:4px}
.seg{display:flex;margin:-2px 0 14px;border:1px solid var(--ed);width:max-content;border-radius:4px;overflow:hidden}
.seg button{background:none;border:0;padding:6px 16px;font:600 11px var(--h);letter-spacing:.1em;color:var(--mu);cursor:pointer}.seg button.on{background:rgba(63,224,255,.18);color:var(--cy);text-shadow:0 0 8px var(--cy)}
.pdm{display:flex;justify-content:center;align-items:flex-end;gap:8px;margin:6px 0 16px}
.pd{flex:1;max-width:128px;text-align:center;min-width:0}
.pd .pa{width:52px;height:52px;margin:0 auto 6px;border-radius:50%;border:2px solid var(--cc);display:grid;place-items:center;font:700 22px var(--h);color:var(--cc);background:radial-gradient(circle at 35% 30%,color-mix(in srgb,var(--cc) 30%,#0a2233),#06101c);box-shadow:0 0 16px color-mix(in srgb,var(--cc) 55%,transparent)}
.pd.p1 .pa{width:62px;height:62px;font-size:26px;animation:pl 2.4s ease-in-out infinite}@keyframes pl{50%{box-shadow:0 0 28px var(--cc)}}
.pd strong{display:block;font:600 12px var(--h);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}.pd small{display:block;color:var(--mu);font:11px var(--m);margin-bottom:6px}
.pd i{display:grid;place-items:center;font:700 26px var(--h);font-style:normal;color:#fff;background:linear-gradient(180deg,color-mix(in srgb,var(--cc) 40%,transparent),color-mix(in srgb,var(--cc) 6%,transparent));border:1px solid var(--cc);border-bottom:0;transform-origin:bottom;animation:up .7s cubic-bezier(.2,.8,.2,1) both}
.pd.p1 i{height:84px;animation-delay:.15s}.pd.p2 i{height:62px;animation-delay:.3s}.pd.p3 i{height:46px;animation-delay:.45s}@keyframes up{from{transform:scaleY(0);opacity:0}}
.rkr{--cc:#3fe0ff;position:relative;overflow:hidden;display:grid;grid-template-columns:34px 1fr auto;gap:2px 10px;align-items:center;padding:10px 12px;margin-bottom:8px;background:linear-gradient(90deg,color-mix(in srgb,var(--cc) 9%,transparent),transparent);border-left:3px solid var(--cc);animation:ri .5s cubic-bezier(.2,.8,.2,1) both;transition:transform .18s}
.rkr:hover{transform:translateX(4px)}body.adm .rkr{cursor:pointer}@keyframes ri{from{opacity:0;transform:translateX(-22px)}}
.rk{font:700 18px var(--m);color:var(--mu);text-align:center}.rkr.t1 .rk{color:#ffd166;text-shadow:0 0 10px #ffd166}.rkr.t2 .rk{color:#d4e2f2}.rkr.t3 .rk{color:#e3955a}
.rn{display:flex;gap:10px;align-items:center;min-width:0}.rn div{min-width:0}.rav{flex:none;width:34px;height:34px;border-radius:50%;border:1.5px solid var(--cc);display:grid;place-items:center;font:700 14px var(--h);color:var(--cc)}
.rn strong{display:block;font:600 14px var(--h);overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.rn small{display:block;color:var(--mu);font-size:11px}
.rv2{text-align:right}.rv2 b{font:700 18px var(--m);color:#fff}.rv2 small{display:block;font:10px var(--h);color:var(--mu);letter-spacing:.1em}
.rb2{grid-column:2/4;height:3px;background:rgba(255,255,255,.08);margin-top:6px}.rb2 i{display:block;height:100%;width:var(--w);background:var(--cc);box-shadow:0 0 8px var(--cc);animation:bf 1s .2s both}
.rkr.me{background:linear-gradient(90deg,color-mix(in srgb,var(--cc) 22%,transparent),transparent)}
.rkr.me::after{content:"";position:absolute;top:0;bottom:0;width:60px;left:-80px;background:linear-gradient(90deg,transparent,rgba(255,255,255,.12),transparent);animation:sh 3.2s linear infinite}@keyframes sh{to{left:110%}}
@media(prefers-reduced-motion:reduce){.rkr,.rkr.me::after,.pd i,.pd.p1 .pa,.rb2 i,.ibt i{animation:none}}

/* v5 elite */
body::after{display:none}.pn>.i::after{display:none}
.g{gap:16px}.pn{margin-bottom:16px}.pn>.i{padding:18px}
h2{font-family:var(--m);font-weight:500;letter-spacing:.2em;font-size:11px;margin-bottom:14px}
.sx b,.rv2 b{font-family:var(--m)}
.nt{font:11px/1.5 var(--m);color:var(--am);border-left:2px solid var(--am);padding:2px 0 2px 10px;margin:-4px 0 14px;opacity:.9}
.holo{height:150px;margin:26px 0 24px}.tl5{margin-top:20px}
#v-core .g2{align-items:start}
.sq{width:min(100%,300px);margin:0 auto;aspect-ratio:1/1}
.sq>.i{height:calc(100% - 2px);display:flex;flex-direction:column;padding:12px 8px 8px}
.sq h2{margin-bottom:0;padding-left:4px}
.sq .rw{flex:1;min-height:0;max-width:none;width:100%;display:grid;place-items:center}
.sq svg.rd{width:100%;height:100%}
.sq .gchip{position:absolute;top:8px;right:12px;font-size:20px}.sq .gchip small{font-size:8px;margin-top:2px}
.sq #scan{align-self:center;padding:3px 14px;font-size:11px}
#sl .ab small{display:none}#sl .ab{margin-top:4px}
.seg{max-width:100%;overflow-x:auto}.seg button{white-space:nowrap}
.tk{overflow:hidden;border:1px solid var(--ed);background:rgba(3,5,12,.6);margin-bottom:12px}
.tkt{display:flex;width:max-content;padding:6px 0;font:11px var(--m);animation:tkk 45s linear infinite}.tkt span{white-space:nowrap;margin-right:24px;color:var(--mu)}.tkt b{color:#fff}
@keyframes tkk{to{transform:translateX(-50%)}}
em.up,.up{color:var(--gr)}em.dn,.dn{color:var(--rd)}em{font-style:normal}
.xr{display:flex;gap:12px;flex-wrap:wrap;align-items:baseline;font:11px var(--m);color:var(--mu);min-height:22px;margin-bottom:4px}.xr b{color:var(--ink)}.xr .px{font-size:18px;color:var(--cy)}
.glg{display:flex;gap:14px;flex-wrap:wrap;font:10px var(--m);color:var(--mu);margin-top:8px}
.ln{stroke-dasharray:1;stroke-dashoffset:1;animation:drw 1.4s ease-out forwards}@keyframes drw{to{stroke-dashoffset:0}}
.pulse{transform-box:fill-box;transform-origin:center;animation:pu 1.6s ease-out infinite}@keyframes pu{from{opacity:.8;transform:scale(1)}to{opacity:0;transform:scale(3.4)}}
.wlh,.wl{display:grid;grid-template-columns:1fr 64px 40px 52px;gap:10px;align-items:center;padding:7px 8px;font:12px var(--m)}
.wlh{color:var(--mu);font-size:10px;letter-spacing:.14em;border-bottom:1px solid var(--ed)}
.wl{border-bottom:1px solid rgba(31,74,115,.35);border-left:2px solid transparent}body.adm .wl{cursor:pointer}.wl.me{background:rgba(63,224,255,.08);border-left-color:var(--cy)}
.wn{display:flex;gap:8px;align-items:center;min-width:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;font-family:var(--h);font-weight:600}.wn i{width:7px;height:7px;border-radius:50%;flex:none}
.sk{width:64px;height:20px}.wl b{text-align:right;color:#fff}.wl em{text-align:right;font-size:11px}
@media(prefers-reduced-motion:reduce){.tkt,.ln,.pulse{animation:none}.ln{stroke-dashoffset:0}}

/* intro HUD */
#intro{position:fixed;inset:0;z-index:95;background:#000;display:grid;place-items:center;transition:opacity .7s;cursor:pointer}#intro.o{opacity:0;pointer-events:none}
#intro svg{width:min(92vw,420px);overflow:visible;transform:perspective(600px) rotateX(64deg);filter:drop-shadow(0 0 10px rgba(63,224,255,.8))}
#intro .r{transform-box:fill-box;transform-origin:center;animation:ir 7s linear infinite}#intro .r2{animation-duration:11s;animation-direction:reverse}#intro .r3{animation-duration:5s}#intro .r4{animation-duration:16s;animation-direction:reverse}
@keyframes ir{to{transform:rotate(360deg)}}
.it{position:absolute;left:0;right:0;bottom:22%;text-align:center;font:600 12px var(--h);letter-spacing:.35em;color:var(--cy);text-shadow:0 0 10px var(--cy)}
.ib{width:160px;height:3px;margin:10px auto 0;background:rgba(63,224,255,.15);overflow:hidden}.ib i{display:block;height:100%;width:0;background:var(--cy);box-shadow:0 0 10px var(--cy);animation:ib 3s ease-out forwards}@keyframes ib{to{width:100%}}
/* overall ability card */
.ova-card{--k:22px;--cc:#3fe0ff;background:#4aa8d8;padding:2px;clip-path:polygon(var(--k) 0,calc(100% - var(--k)) 0,100% var(--k),100% calc(100% - var(--k)),calc(100% - var(--k)) 100%,var(--k) 100%,0 calc(100% - var(--k)),0 var(--k));max-width:420px;margin:0 auto 12px}
.ova-in{clip-path:inherit;padding:14px;background:linear-gradient(160deg,#0f3550,#07182a 60%,#0a2a40);position:relative;overflow:hidden}
.ova-in::before{content:"";position:absolute;inset:0;background:linear-gradient(transparent 0 48%,rgba(63,224,255,.12) 50%,transparent 52%) 0 0/100% 8px;opacity:.5;pointer-events:none}
.ova-t{font:italic 700 clamp(22px,7vw,30px)/1 var(--h);color:#7fd4ff;text-shadow:0 0 12px rgba(63,224,255,.7);margin-bottom:12px}
.ova-ph{height:120px;border:2px solid #4aa8d8;background:radial-gradient(circle at 50% 35%,#1b6a8a,#08202f);display:grid;place-items:center;position:relative;overflow:hidden;margin-bottom:12px}
.ova-ph b{font:700 64px var(--h);color:#bff3ff;text-shadow:0 0 20px var(--cy)}.ova-ph i{position:absolute;left:0;right:0;height:2px;top:0;background:var(--cy);box-shadow:0 0 10px var(--cy);animation:scn 2.6s ease-in-out infinite}
.ova-nm{text-align:center;border:2px solid #4aa8d8;padding:8px;background:rgba(74,168,216,.18);margin-bottom:12px}.ova-nm small{display:block;font:11px var(--h);letter-spacing:.2em;color:#9cc7e0}.ova-nm b{font:700 clamp(20px,6vw,26px) var(--h);color:#fff;overflow-wrap:anywhere}
.ova-g{display:grid;grid-template-columns:1fr 112px 1fr;gap:8px;align-items:center;background:rgba(0,0,0,.35);padding:10px;border:1px solid #1f4a73}
.ova-col{display:grid;gap:8px}.ova-bx{border:2px solid #4aa8d8;background:rgba(5,20,34,.85);padding:6px 8px;display:flex;justify-content:space-between;align-items:center;min-height:42px}
.ova-bx small{font:10px var(--h);color:#9cc7e0;display:block;letter-spacing:.06em}.ova-bx span{font:700 24px var(--h)}.ova-bx em{font:normal 11px var(--m);color:var(--mu)}
.ova-5{grid-column:1/-1;max-width:50%;margin:0 auto;width:100%}
.ova-ring{position:relative;width:112px;height:112px}.ova-ring svg{width:100%;transform:rotate(-90deg)}.ova-ring div{position:absolute;inset:0;display:grid;place-items:center;text-align:center;font:700 44px var(--h);color:var(--am);text-shadow:0 0 16px var(--am);line-height:1}.ova-ring small{display:block;font:9px var(--h);letter-spacing:.15em;color:var(--mu);text-shadow:none}
.gS,.gA{color:var(--gr)}.gB{color:var(--cy)}.gC{color:#e8f3ff}.gD,.gE{color:var(--rd)}
.vw.on .ova-card{animation:ci .6s cubic-bezier(.2,.8,.2,1)}
@media(prefers-reduced-motion:reduce){#intro .r,.ova-ph i{animation:none}}
#v-dash,#v-rank{display:none!important}.holo{height:215px!important;margin:18px 0 6px!important}.holo img{width:min(88vw,360px);mix-blend-mode:screen;filter:drop-shadow(0 0 12px rgba(63,224,255,.6));animation:hp 3.2s ease-in-out infinite}@keyframes hp{50%{opacity:.72;filter:drop-shadow(0 0 20px rgba(63,224,255,.9))}}.tl5{margin-top:14px!important}.lsc small{font-size:.32em;letter-spacing:.05em;color:var(--cy);vertical-align:baseline;margin-left:4px}#v-ova{padding-bottom:110px}
.holo{height:200px!important}.holo svg{width:min(94vw,360px)!important;transform:perspective(560px) rotateX(63deg)!important}.lsw{width:100%!important;height:100%;display:flex;flex-direction:column;align-items:center;justify-content:space-evenly;padding:calc(6vh + env(safe-area-inset-top,0px)) 0 calc(5vh + env(safe-area-inset-bottom,0px))}.lsw .holo{height:auto!important;margin:0!important;transform:translateY(-4vh)}.lsw .lsb{margin:0!important}
/* digital clock */
.lst{position:relative;padding:18px 26px 14px}
.lst::before,.lst::after{content:"";position:absolute;width:22px;height:22px;border:2px solid var(--cy);filter:drop-shadow(0 0 6px var(--cy))}.lst::before{left:0;top:0;border-right:0;border-bottom:0}.lst::after{right:0;bottom:0;border-left:0;border-top:0}
.lsc{font-family:ui-monospace,"SF Mono",Menlo,Consolas,monospace!important;font-weight:300;font-variant-numeric:tabular-nums;background:linear-gradient(180deg,#fff 30%,#9be9ff);-webkit-background-clip:text;background-clip:text;color:transparent!important;text-shadow:none!important;filter:drop-shadow(0 0 12px rgba(63,224,255,.8));position:relative}
.lsc .cl{animation:cb 1s steps(1) infinite}@keyframes cb{50%{opacity:.15}}
.lsc small{-webkit-text-fill-color:var(--cy)}
.lsc::after{content:"";position:absolute;inset:0;background:repeating-linear-gradient(transparent 0 3px,rgba(0,0,0,.35) 3px 4px);pointer-events:none}
.lsr{height:6px;margin:10px auto 0;width:86%;background:repeating-linear-gradient(90deg,rgba(63,224,255,.35) 0 1px,transparent 1px 6px);position:relative}
.lsr i{position:absolute;left:0;top:0;height:100%;width:0;background:repeating-linear-gradient(90deg,var(--cy) 0 2px,transparent 2px 6px);filter:drop-shadow(0 0 5px var(--cy));transition:width .4s linear}
/* ability grid fit */
.ova-g{grid-template-columns:minmax(0,1fr) 96px minmax(0,1fr)!important;gap:6px!important;padding:8px!important}
.ova-ring{width:96px!important;height:96px!important}.ova-ring div{font-size:36px!important}
.ova-bx{padding:5px 6px!important;gap:4px;min-width:0}.ova-bx>div{min-width:0}.ova-bx small{font-size:9px!important;letter-spacing:.02em!important}.ova-bx span{font-size:20px!important}
.ova-card{max-width:100%!important}.ova-5{max-width:55%!important}
</style></head>
<body class="lk">
<canvas id="st"></canvas>
<div id="boot"><div class="lsw"><div class="lst"><div class="lsc" id="lsc">00:00</div><div class="lsdt" id="lsd2"></div><div class="lsr"><i id="lss"></i></div></div><div class="holo"><svg viewBox="0 0 300 300" aria-hidden="true"><g><animateTransform attributeName="transform" type="rotate" from="360 150 150" to="0 150 150" dur="30s" repeatCount="indefinite"/><circle cx="150" cy="150" r="142" fill="none" stroke="#19c8d8" stroke-width="2" stroke-dasharray="150 60 40 70 90 80"/></g><g><animateTransform attributeName="transform" type="rotate" from="0 150 150" to="360 150 150" dur="40s" repeatCount="indefinite"/><line x1="278" y1="150" x2="288" y2="150" transform="rotate(0 150 150)" stroke="#fff" stroke-width="2.5"/><line x1="278" y1="150" x2="288" y2="150" transform="rotate(90 150 150)" stroke="#fff" stroke-width="2.5"/><line x1="278" y1="150" x2="288" y2="150" transform="rotate(180 150 150)" stroke="#fff" stroke-width="2.5"/><line x1="278" y1="150" x2="288" y2="150" transform="rotate(270 150 150)" stroke="#fff" stroke-width="2.5"/></g><circle cx="150" cy="150" r="118" fill="none" stroke="#fff" stroke-width="1.6"/><g><animateTransform attributeName="transform" type="rotate" from="360 150 150" to="0 150 150" dur="14s" repeatCount="indefinite"/><path d="M249.6 186.3A106 106 0 0 1 131.6 254.4" fill="none" stroke="#2f7bff" stroke-width="14" stroke-dasharray="4 3"/></g><g><animateTransform attributeName="transform" type="rotate" from="0 150 150" to="360 150 150" dur="8s" repeatCount="indefinite"/><circle cx="150" cy="150" r="92" fill="none" stroke="#19f0ff" stroke-width="18" stroke-dasharray="400 178" transform="rotate(-90 150 150)"/><circle cx="150" cy="150" r="109" fill="none" stroke="#19f0ff" stroke-width="5" stroke-dasharray="190 495" transform="rotate(-100 150 150)"/></g><g><animateTransform attributeName="transform" type="rotate" from="360 150 150" to="0 150 150" dur="11s" repeatCount="indefinite"/><circle cx="150" cy="150" r="76" fill="none" stroke="#19c8d8" stroke-width="2" stroke-dasharray="120 80 40 90"/></g><circle cx="150" cy="150" r="62" fill="none" stroke="#19c8d8" stroke-width="1.5"><animate attributeName="opacity" values=".35;1;.35" dur="2.6s" repeatCount="indefinite"/></circle><g><animateTransform attributeName="transform" type="rotate" from="0 150 150" to="360 150 150" dur="5s" repeatCount="indefinite"/><circle cx="150" cy="150" r="52" fill="none" stroke="#2f7bff" stroke-width="2" stroke-dasharray="3 6"/></g></svg></div><button class="lsb" id="lsb">SIGN IN</button>

</div></div>


<div id="gate"><div class="pn gb"><div class="i">
<svg id="lg" viewBox="0 0 48 48"><polygon points="24,3 43,14 43,34 24,45 5,34 5,14" fill="none" stroke="#3fe0ff" stroke-width="2"/><polygon points="24,12 35,18.5 35,29.5 24,36 13,29.5 13,18.5" fill="rgba(63,224,255,.2)" stroke="#3fe0ff" stroke-width="1.5"/><circle cx="24" cy="24" r="3" fill="#3fe0ff"/></svg>
<h3><b>S</b> SYSTEM</h3><p>IDENTIFY YOURSELF · STUDENT ACCESS</p>
<label class="f">USERNAME<input id="gu" autocapitalize="none" autocomplete="username" spellcheck="false"></label><br>
<label class="f">PASSWORD<input id="gp" type="password" autocomplete="current-password"></label>
<div class="me2" id="ge"></div>
<button class="bt" id="gb" style="width:100%">ENTER</button>
</div></div></div>
<div id="modal" hidden><div class="pn gb"><div class="i" id="mb"></div></div></div>

<div class="w">
<header><div class="br"><svg viewBox="0 0 48 48"><polygon points="24,3 43,14 43,34 24,45 5,34 5,14" fill="none" stroke="#3fe0ff" stroke-width="2"/><circle cx="24" cy="24" r="5" fill="#3fe0ff"/></svg><div><h1><b>S</b> SYSTEM</h1><div class="tg">CAMPUS OPERATING SYSTEM</div></div></div>
<div class="hr"><span class="bd" id="mode">—</span><span class="mo" id="clk" style="font-size:12px"></span><button class="gh" id="out">Log out</button></div></header>

<div class="pn ad" style="--ed:#c98a1d"><div class="i"><h2 style="color:var(--am)">Subject select</h2><select id="sel"></select></div></div>

<section class="vw on" id="v-id"><div id="idc"><div class="idc-card"><div class="idc-in"><svg class="idc-hex" viewBox="0 0 100 100"><polygon points="50,4 91,27 91,73 50,96 9,73 9,27" fill="none" stroke="currentColor" stroke-width="2"/><polygon points="50,20 77,35 77,65 50,80 23,65 23,35" fill="none" stroke="currentColor" stroke-width="1.5"/><circle cx="50" cy="50" r="8" fill="none" stroke="currentColor" stroke-width="1.5"/></svg>
<div class="idc-t">Student Identity Card</div><div class="idc-row"><div class="idc-ph"><b id="iph">S</b><i></i></div><div class="idc-f"><div><small>Number</small><b id="in1"></b></div><div><small>Name</small><b id="in2"></b></div><div><small>Class</small><b id="in3"></b></div><div><small>Institution</small><b>Entrepreneurship Cell, Shobhit University</b></div></div></div></div></div>
<div class="idc-pt"><div class="idc-d"><div class="idc-n"><span id="ipn">0</span><em>PPt</em></div><div class="idc-b"><i id="ipb"></i></div><div class="nt" style="margin:10px 0 0">PPt allocation: 100,000. Subject to monthly review — deductible next month without measurable progress.</div></div></div>
<div class="sp" style="grid-template-columns:repeat(3,1fr);margin:0"><div class="sx"><small>OVERALL</small><b id="is1" style="font-size:16px"></b></div><div class="sx a"><small>POINT RANK</small><b id="is2" style="font-size:16px"></b></div><div class="sx"><small>ATTENDANCE</small><b id="is3" style="font-size:16px"></b></div><div class="sx"><small>Z-SCORE</small><b id="is4" style="font-size:16px"></b></div><div class="sx a"><small>PERCENTILE</small><b id="is5" style="font-size:16px"></b></div><div class="sx"><small>TIER</small><b id="is6" style="font-size:13px"></b></div></div><div class="idx"><div class="pn"><div class="i"><h2>Point flow</h2><div id="ispk"></div></div></div><div class="pn"><div class="i"><h2>Ability profile</h2><div id="ibars"></div></div></div><div class="pn"><div class="i"><h2>Latest activity</h2><div id="iact"></div></div></div></div></div></section>

<section class="vw" id="v-core"><div class="g g2"><div><div class="pn"><div class="i"><h2>Overall score</h2><div class="gw"><div class="ga"><svg viewBox="0 0 148 148"><circle cx="74" cy="74" r="68" fill="none" stroke="#1f4a73" stroke-dasharray="1.5 5.2"/><circle cx="74" cy="74" r="56" fill="none" stroke="rgba(255,255,255,.1)" stroke-width="9"/><circle id="arc" cx="74" cy="74" r="56" fill="none" stroke-width="9" stroke-linecap="round" stroke-dasharray="351.86" stroke-dashoffset="351"/></svg><div class="c"><div><b id="on">0</b><span id="og">E</span></div></div></div>
<div><div class="nm" id="tt" style="font-size:18px"></div><div style="color:var(--mu);font-size:12px" id="tp"></div></div></div><div id="sl"></div>
<div class="fl ad" style="margin-top:10px"><button class="bt am" id="svs">Save scores</button></div></div></div>
<div class="pn"><div class="i"><h2>Analysis</h2><div class="sp"><div class="sx"><small>ARCHETYPE</small><b id="s1" style="font-size:15px"></b></div><div class="sx"><small>RANK</small><b id="s2" style="font-size:15px"></b></div><div class="sx"><small>BALANCE</small><b id="s3" style="font-size:15px"></b><div class="mt"><i id="m3"></i></div></div><div class="sx"><small>PERCENTILE</small><b id="s4" style="font-size:15px"></b><div class="mt"><i id="m4"></i></div></div></div></div></div></div><div class="pn sq"><div class="i"><h2>Ability scanner</h2><div class="gchip" id="gchip"></div><div style="display:none"><div class="av" id="av"></div><div class="nm" id="nm"></div><div class="sb" id="sb"></div></div><div class="rw"><svg class="rd" id="rd" viewBox="0 0 360 340"></svg></div><button class="gh" id="scan">Run analysis</button><div class="lg" id="lg2" style="display:none"></div></div></div></div><div class="pn"><div class="i"><h2>Performance terminal</h2><div class="tk"><div class="tkt" id="tkt"></div></div><div class="seg" id="gm"><button data-m="oa" class="on">Overall</button><button data-m="t">Adaptive</button><button data-m="a">Academic</button><button data-m="i">Decision</button><button data-m="p">Physical</button><button data-m="s">Social</button></div><div class="xr" id="xr"></div><div id="gline"></div><div class="glg"><span style="color:var(--cy)">━ Selected</span><span style="color:#fff">╌ Cohort avg</span><span>Touch chart to read</span></div></div></div><div class="pn"><div class="i"><h2>Watchlist</h2><div class="wlh"><span>STUDENT</span><span>TREND</span><span>VALUE</span><span>Δ</span></div><div id="gbars"></div></div></div></section>

<section class="vw" id="v-dash"><div class="g g2"><div class="pn"><div class="i"><h2>Student status</h2>
<div class="sp" style="margin:0"><div class="sx"><small>PRIVATE POINTS</small><b id="pp">0</b></div><div class="sx a"><small>ATTENDANCE</small><b id="ar">—</b></div><div class="sx"><small>POINT RANK</small><b id="pr">—</b></div><div class="sx a"><small>TASKS DONE</small><b id="td">0</b></div></div>
<div class="fl" style="margin-top:12px;align-items:center"><button class="bt" id="ci">CHECK IN</button><span class="mo" id="ct"></span></div></div></div>
<div class="pn"><div class="i"><h2>Recent activity</h2><div id="act"></div></div></div></div></section>

<section class="vw" id="v-rank"><div class="pn"><div class="i"><h2>Point standings</h2><div class="nt">PPt allocation: 100,000 per student. Points may be deducted next month if no measurable progress is shown.</div><div class="seg" id="rkt"><button data-m="pp" class="on">Points</button><button data-m="oa">Overall</button></div><div id="rb"></div></div></div>
<div class="pn ad am" style="--ed:#c98a1d"><div class="i"><h2>Admin Head · registry</h2><div class="fl"><div class="f">Name<input id="an"></div><div class="f" style="flex:0 1 110px">Class<select id="ac"><option>Class S</option><option>Class A</option><option>Class B</option><option>Class C</option><option>Class D</option></select></div><button class="bt am" id="aadd">Add subject</button><button class="gh dg" id="adel">Delete selected</button></div></div></div></section>

<section class="vw" id="v-trade"><div class="pn"><div class="i"><h2>Exchange points</h2><div class="fl"><div class="f">Mode<select id="xm"><option value="t">Transfer to student</option><option value="r">Redeem / spend</option></select></div><div class="f" id="xtf">Recipient<select id="xt"></select></div><div class="f" style="flex:0 1 100px">Amount<input id="xa" type="number" min="1"></div><div class="f" style="flex:2 1 160px">Memo<input id="xo"></div><button class="bt" id="xs">Send</button></div></div></div>
<div class="pn ad am" style="--ed:#c98a1d"><div class="i"><h2>Admin · grant / deduct</h2><div class="fl"><div class="f" style="flex:0 1 120px">± Points<input id="ga2" type="number"></div><div class="f">Reason<input id="gr"></div><button class="bt am" id="gs">Apply to subject</button></div><div class="fl" style="margin-top:10px"><div class="f" style="flex:0 1 160px">Set exact balance<input id="se" type="number" min="0"></div><button class="bt am" id="sv2">Set points</button></div></div></div>
<div class="pn"><div class="i"><h2>Transaction log</h2><div id="tx"></div></div></div></section>

<section class="vw" id="v-task"><div class="pn ad"><div class="i"><h2>Post assignment (admin)</h2><div class="fl"><div class="f">Title<input id="tt2"></div><div class="f" style="flex:0 1 150px">Due<input id="td2" type="date"></div><div class="f" style="flex:0 1 130px">For<select id="tc"><option>All</option><option>Class S</option><option>Class A</option><option>Class B</option><option>Class C</option><option>Class D</option></select></div></div><div class="fl"><div class="f">Details (optional)<input id="tn2"></div><button class="bt" id="ts">Post</button></div></div></div>
<div class="pn" id="sp" style="display:none"><div class="i"><h2 id="spt">Submit work</h2><div class="fl"><div class="f">File (optional)<label class="gh" for="sf" style="display:block;text-align:center;cursor:pointer;padding:9px 10px;border-radius:4px">Choose file</label><input id="sf" type="file" style="position:absolute;left:-9999px;width:1px;height:1px;opacity:0"><small id="sfn" style="color:var(--mu);word-break:break-all">No file chosen</small></div><div class="f">Link / note<input id="sn"></div></div><div class="fl"><button class="gh" id="sc">Cancel</button><button class="bt" id="sg">Send</button></div><small style="color:var(--mu)">Only the file name is saved. If the picker does not open, paste a link in the note box instead.</small></div></div>
<div class="pn"><div class="i"><h2>Assignments</h2><div id="tl"></div></div></div></section>

<section class="vw" id="v-news"><div class="pn ad"><div class="i"><h2>Post notice (admin)</h2><div class="fl"><div class="f">Title<input id="nt"></div><div class="f" style="flex:0 1 130px">For<select id="nc"><option>All</option><option>Class S</option><option>Class A</option><option>Class B</option><option>Class C</option><option>Class D</option></select></div></div><div class="fl"><div class="f">Message<textarea id="nmsg"></textarea></div></div><div class="fl"><div class="f">Flyer (optional)<label class="gh" for="nf" style="display:block;text-align:center;cursor:pointer;padding:9px 10px;border-radius:4px">Choose image</label><input id="nf" type="file" style="position:absolute;left:-9999px;width:1px;height:1px;opacity:0"><small id="nfn" style="color:var(--mu)">No image chosen</small><img id="nprev" alt="" style="display:none;width:100%;max-height:200px;object-fit:contain;margin-top:6px"></div></div><div class="fl"><button class="bt" id="np">Post</button></div></div></div>
<div class="pn"><div class="i"><h2>Notice board</h2><div id="nl"></div></div></div></section>
<section class="vw" id="v-att"><div class="pn"><div class="i"><h2>Attendance</h2><div class="sp" style="margin:0 0 12px"><div class="sx"><small>PRESENT</small><b id="ap">0</b></div><div class="sx a"><small>ABSENT</small><b id="aa">0</b></div></div>
<div class="fl ad"><div class="f" style="flex:0 1 150px">Date<input id="ad" type="date"></div><div class="f" style="flex:0 1 120px">Status<select id="as"><option value="present">Present</option><option value="absent">Absent</option></select></div><button class="bt am" id="am">Record</button></div>
<div id="al" style="margin-top:8px"></div></div></div></section>

<section class="vw" id="v-adm"><div class="g g2"><div class="pn am" style="--ed:#c98a1d"><div class="i"><h2>Weighting</h2><div class="fl" id="pre"></div><div id="wg" style="display:grid;grid-template-columns:1fr 1fr;gap:6px 14px;margin-top:8px"></div><p style="color:var(--mu);font-size:11px;margin-top:6px">Overall = Σ(score×weight) ÷ Σ(weight)</p></div></div>
<div class="pn am" style="--ed:#c98a1d"><div class="i"><h2>Student login</h2><p style="color:var(--mu);font-size:12px;margin-bottom:8px" id="ls"></p><div class="f">Username<input id="lu"></div><div class="f" style="margin-top:6px">Password<input id="lp" placeholder="6+ characters"></div><div class="fl" style="margin-top:8px"><button class="bt am" id="lsv">Save login</button><button class="gh" id="lgn">Generate</button><button class="gh dg" id="lrm">Remove</button></div>
<label style="display:flex;gap:8px;margin-top:10px;font-size:12px;color:var(--mu)"><input type="checkbox" id="sa" style="width:auto"> Students can see full registry</label></div></div>
<div class="pn am" style="--ed:#c98a1d"><div class="i"><h2>Data · offline</h2><div class="fl" style="flex-direction:column;align-items:stretch"><button class="bt am" id="exp">Download snapshot (.html)</button><button class="gh" id="bk">Backup data (.json)</button><button class="gh" id="im">Restore backup</button><input type="file" id="imf" accept=".json" hidden><button class="gh" id="pw">Change admin password</button><button class="gh dg" id="rs">Reset all</button></div><p style="color:var(--mu);font-size:11px;margin-top:8px">Only the Admin Head can see this panel. Everything is stored in this browser. Snapshot = a full copy of this app with current data, share it by USB, LAN share or chat.</p></div></div></div></section>
</div>
<section class="vw" id="v-ova"><div class="ova-card" id="ovac"><div class="ova-in"><div class="ova-t">Over All Ability</div><div class="ova-ph"><b id="ovp">S</b><i></i></div><div class="ova-nm"><small id="ovc"></small><b id="ovn"></b></div><div class="ova-g" id="ovg"></div></div></div>
<div class="pn" style="max-width:420px;margin:0 auto 12px"><div class="i"><h2>Class standing</h2><div id="ovs"></div></div></div></section>
<div class="nav" id="nav"><button data-v="id" class="on"><i>◉</i>ID</button><button data-v="core"><i>◈</i>CORE</button><button data-v="ova"><i>◎</i>ABILITY</button><button data-v="news"><i>✉</i>NEWS</button><button data-v="trade"><i>⇄</i>TRADE</button><button data-v="task"><i>▦</i>TASKS</button><button data-v="att"><i>✓</i>ATTEND</button><button data-v="adm" class="ad" id="admtab"><i>⚙</i>ADMIN</button></div>
<div id="toast"></div>
<script id="seed" type="application/json">{"v": 2, "updatedAt": 1792494650941, "roster": [{"id": "u1792494650941", "name": "Partiyush Sharma", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "partiyush", "salt": "RcVvVLo89VY5lKGp/c1u1w==", "iter": 150000, "hash": "yN9/z4rQoAigzV849sLRBcNaH0qicEC+Lh6vhIm8WKg="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792494650942", "name": "Arush Gautam", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "arush", "salt": "oeFEIaiaQkR9Fee4jxO8ug==", "iter": 150000, "hash": "WL5wsX2HMWH7clSCRkYd86ZfYeDXaCypDrzLTzk3FJY="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792494650943", "name": "Kavya Jaiswal", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "kavya", "salt": "hrytiXDu8eLqJXYOGFIREw==", "iter": 150000, "hash": "q9jSEqcv8B1SwPyLdoH3nk6wn5ou2X9tWh9lvgX18oY="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792494650944", "name": "Bahnu Pratap", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "bahnu", "salt": "YGgi/35NfnRAJ/CibG+x4Q==", "iter": 150000, "hash": "MqQo2pz/xGpR6Vzk9DsjA9vSJ4Wy0xastYfJWeXvtpw="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792494650945", "name": "Manan Jain Naja", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "manan", "salt": "gRUajWudi1FU88+rNqJljw==", "iter": 150000, "hash": "NpNJe+wiTnBOQLgCG53VHvXMyPBGEmGiI+OVeJEAT+w="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792494650946", "name": "Abuzar", "cls": "Class S", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "abuzar", "salt": "B6n4FCm3xoEoCcYiL1IhNQ==", "iter": 150000, "hash": "VFtYFBKxSsskmYPh4y+hrhe25VKgKSPx6IXUp8V/Ugs="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1791818505695", "name": "Nikhil Chauhan", "cls": "Class A", "a": 89, "i": 75, "p": 89, "t": 85, "s": 95, "pp": 100000, "login": {"user": "nikhil", "salt": "wawAZ3fuCtLuJ4PXKv+JPA==", "iter": 150000, "hash": "hE1lMSfn2H1aETopyPtfgNEARVZCKvez7ZZcPLl5fhY="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1791818626186", "name": "Prithvi Raj Chauhan", "cls": "Class A", "a": 89, "i": 75, "p": 89, "t": 85, "s": 95, "pp": 100000, "login": {"user": "prithvi", "salt": "2hdF8zyv33SPmY/BQpqaUg==", "iter": 150000, "hash": "jediFhiFLWXQ6D6XVtrsc7x9NHD0VBVIfuBhSSGLT5Q="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1791819110374", "name": "Sanjana Sriwastwa", "cls": "Class B", "a": 64, "i": 62, "p": 90, "t": 92, "s": 62, "pp": 100000, "login": {"user": "sanjana", "salt": "KjIls2TqD3GnDYJBIIqh2A==", "iter": 150000, "hash": "J1LvUvTQVL2OjaI/maX3FJL8684yu++sjQUMLLeN1RM="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1791821614015", "name": "Nikhil Sharma", "cls": "Class B", "a": 64, "i": 74, "p": 90, "t": 92, "s": 62, "pp": 100000, "login": {"user": "nikhil12", "salt": "OVGOYgEWBppaDLU+Wcn5PA==", "iter": 150000, "hash": "OGF6ATz/OykFekn4fzaBjtUexnO+tOKhTPUovWFMaJ8="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1791821392365", "name": "Sushmita", "cls": "Class C", "a": 64, "i": 50, "p": 90, "t": 92, "s": 62, "pp": 100000, "login": {"user": "sushmita", "salt": "DtcpymY8kPqGx1NoEi69iw==", "iter": 150000, "hash": "OGocp6nv3Con47YLhaOFAt+F5MEW+jL0XwQTxp9YniE="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792489070455", "name": "Arbaj Alam", "cls": "Class C", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "arbaj", "salt": "FYV0IxCYCaj5ou8bJnpqRQ==", "iter": 150000, "hash": "Xk5gSaQisSbpjwJBfKwEbZZgLIHjbOC2NlC5zh2zXl4="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792489070456", "name": "Kanika Tomar", "cls": "Class D", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "kanika", "salt": "YSocF95Gd9AS2e9IrjjfLg==", "iter": 150000, "hash": "dr1rNECtpMyytO9/gySWNI1/TW2zkF0rD9nzXdIW9Fw="}, "att": {}, "tx": [], "tasks": [], "act": []}, {"id": "u1792489070457", "name": "Raushan Kumar", "cls": "Class D", "a": 60, "i": 60, "p": 60, "t": 60, "s": 60, "pp": 100000, "login": {"user": "raushan", "salt": "F4Gluoa0t0I0aoXaS09jGQ==", "iter": 150000, "hash": "7u2sXv49ZbVAA4L4GKn2jwwK/XA7wnw7UR85TYELaDY="}, "att": {}, "tx": [], "tasks": [], "act": []}], "weights": [1, 1, 1, 1, 2], "auth": {"salt": "mMIMffwIeCbHiyvA+M542Q==", "iter": 150000, "hash": "R7/CWmXiCO0ApomvqDoNHufnhFC044hcyN5dGSph7cg="}, "showAll": true, "rev": 6, "assign": [], "posts": []}</script>
<script>
(function(){"use strict";
var AB=[{k:'a',n:'Academic',d:'Exams, written work'},{k:'i',n:'Decision',d:'Judgment, planning'},{k:'p',n:'Physical',d:'Athletics, stamina'},{k:'t',n:'Adapt',d:'Coping with change'},{k:'s',n:'Social',d:'Teamwork, conduct'}];
var BD=[[95,'A+'],[90,'A'],[85,'A−'],[80,'B+'],[75,'B'],[70,'B−'],[65,'C+'],[60,'C'],[55,'C−'],[50,'D+'],[45,'D'],[40,'D−'],[0,'E']];
var TR={A:['Apex','Exceptional across the board.'],B:['Proficient','Strong, dependable.'],C:['Standard','Solid middle.'],D:['Watch list','Weak spots drag the total.'],E:['Critical','Needs urgent support.']};
var TC={A:'#ffd166',B:'#3fe0ff',C:'#ffe066',D:'#ff9a3c',E:'#ff5d6c'};
var PR={Balanced:[1,1,1,1,1],'Academic':[3,2,1,1,1],'Field':[1,1,3,2,1],'Leader':[1,3,1,2,3]};
var ARCH={a:'Scholar',i:'Strategist',p:'Vanguard',t:'Adaptive',s:'Diplomat'};
var KEY='s-system-v1',S,role=null,me=null,sel=null,dirty=false,cur={};
var $=function(i){return document.getElementById(i)};
var esc=function(x){return String(x).replace(/[&<>"']/g,function(c){return{'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]})};
var clamp=function(v){return Math.max(0,Math.min(100,v))};
var today=function(){var d=new Date();return d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0')};
var nowT=function(){var d=new Date();return String(d.getHours()).padStart(2,'0')+':'+String(d.getMinutes()).padStart(2,'0')};
var grade=function(n){for(var j=0;j<BD.length;j++)if(n>=BD[j][0])return BD[j][1];return'E'};
var gk=function(g){return g==='A+'?'A':g.charAt(0)};
var by=function(id){return S.roster.filter(function(r){return r.id===id})[0]||null};
function ov(o){var w=S.weights,sw=0,sm=0;AB.forEach(function(x,j){sw+=w[j];sm+=o[x.k]*w[j]});return sw?Math.round(sm/sw):0}
function load(){var e={},l=null;try{e=JSON.parse($('seed').textContent)}catch(x){}try{l=JSON.parse(localStorage.getItem(KEY))}catch(x){}
S=l||e;S.roster=S.roster||[];
if(l&&(l.rev||0)<(e.rev||0)){(e.roster||[]).forEach(function(x){var m=S.roster.filter(function(r){return r.id===x.id})[0];if(!m)S.roster.push(JSON.parse(JSON.stringify(x)));else{if(x.login)m.login=JSON.parse(JSON.stringify(x.login));m.name=x.name;m.cls=x.cls;m.pp=x.pp}});S.posts=S.posts||[];(e.posts||[]).forEach(function(x){if(!S.posts.some(function(y){return y.id===x.id}))S.posts.push(x)});S.assign=S.assign||[];(e.assign||[]).forEach(function(x){if(!S.assign.some(function(y){return y.id===x.id}))S.assign.push(x)});if(e.auth)S.auth=e.auth;S.rev=e.rev;try{localStorage.setItem(KEY,JSON.stringify(S))}catch(x){}}
S.assign=S.assign||(e.assign||[]).slice();S.posts=S.posts||(e.posts||[]).slice();S.rev=S.rev||e.rev||0;S.weights=S.weights||[1,1,1,1,1];if(!S.pp100){S.roster.forEach(function(r){if(r.pp===10000&&!(r.tx&&r.tx.length))r.pp=100000});S.pp100=1;try{localStorage.setItem(KEY,JSON.stringify(S))}catch(x){}}snap();}
function snap(){S.roster.forEach(function(r){var h=r.hist=r.hist||[],l=h[h.length-1],v={a:r.a,i:r.i,p:r.p,t:r.t,s:r.s};if(!l||(l.d!==today()&&JSON.stringify(l.v)!==JSON.stringify(v)))h.push({d:today(),v:v});if(h.length>60)h.shift()})}
function save(){S.updatedAt=Date.now();try{localStorage.setItem(KEY,JSON.stringify(S))}catch(x){}}
var tt;function toast(m){var t=$('toast');t.textContent=m;t.classList.add('s');clearTimeout(tt);tt=setTimeout(function(){t.classList.remove('s')},2400)}
var logs=[];function log(m){toast(m);logs.unshift(m);logs.length=Math.min(logs.length,5);$('lg2').innerHTML=logs.map(function(l,i){return'<div style="opacity:'+(1-i*.18)+'"><em>'+nowT()+'</em>'+esc(l)+'</div>'}).join('')}
function act(r,t){r.act.unshift({t:t,d:today(),h:nowT()});r.act.length=Math.min(r.act.length,12)}
/* auth */
var b64=function(b){var a=new Uint8Array(b),s='';for(var j=0;j<a.length;j++)s+=String.fromCharCode(a[j]);return btoa(s)},ub=function(s){var b=atob(s),a=new Uint8Array(b.length);for(var j=0;j<b.length;j++)a[j]=b.charCodeAt(j);return a};
function derive(p,salt,it){return crypto.subtle.importKey('raw',new TextEncoder().encode(p),'PBKDF2',false,['deriveBits']).then(function(k){return crypto.subtle.deriveBits({name:'PBKDF2',salt:ub(salt),iterations:it,hash:'SHA-256'},k,256)}).then(b64)}
function mk(p){var s=b64(crypto.getRandomValues(new Uint8Array(16)).buffer);return derive(p,s,150000).then(function(h){return{salt:s,iter:150000,hash:h}})}
function eq(a,b){var d=a.length^b.length;for(var j=0;j<Math.max(a.length,b.length);j++)d|=(a.charCodeAt(j)||0)^(b.charCodeAt(j)||0);return d===0}
var fails=0,lock=0;
function crypt(){return!!(window.crypto&&crypto.subtle&&window.TextEncoder)}
function studentLogin(){var u=$('gu').value.trim().toLowerCase(),p=$('gp').value,e=$('ge');e.textContent='';
if(!u||!p){e.textContent='Enter username and password.';return}
if(!crypt()){e.textContent='Open this file in a current browser (https or file://).';return}
if(Date.now()<lock){e.textContent='Locked. Wait '+Math.ceil((lock-Date.now())/1000)+'s.';return}
var rec=S.roster.filter(function(r){return r.login&&r.login.user===u})[0],a=rec?rec.login:{salt:'AAAAAAAAAAAAAAAAAAAAAA==',iter:150000,hash:''};
var tryP=function(pw){return derive(pw,a.salt,a.iter).then(function(h){return!!rec&&eq(h,a.hash)})};
tryP(p).then(function(ok){return ok||(p!==p.trim()?tryP(p.trim()):false)}).then(function(ok){if(ok){fails=0;$('gp').value='';start('student',rec.id)}else{if(++fails>=5){lock=Date.now()+30000;fails=0}e.textContent='Access denied.'}})}
function modal(mode){var m=$('modal'),b=$('mb'),inp=function(i,l){return'<label class="f" style="margin-bottom:8px">'+l+'<input type="password" id="'+i+'"></label>'};
var h='<h3 style="font:700 16px var(--h);margin-bottom:10px;color:var(--am)">'+(mode==='setup'?'Create admin password':mode==='login'?'Admin login':'Change password')+'</h3>';
if(mode==='change')h+=inp('m0','Current password');h+=inp('m1',mode==='login'?'Password':'New password (8+)');if(mode!=='login')h+=inp('m2','Confirm');
h+='<div class="me2" id="me"></div><div class="fl"><button class="gh" id="mc">Cancel</button><button class="bt am" id="mo">OK</button></div>';b.innerHTML=h;m.hidden=false;$('m1').focus?$((mode==='change')?'m0':'m1').focus():0;
var close=function(){m.hidden=true;b.innerHTML=''},er=function(t){$('me').textContent=t};$('mc').onclick=close;
$('mo').onclick=function(){if(!crypt()){er('Secure crypto unavailable.');return}
if(mode==='login'){if(Date.now()<lock){er('Locked.');return}derive($('m1').value,S.auth.salt,S.auth.iter).then(function(h){if(eq(h,S.auth.hash)){fails=0;close();start('admin')}else{if(++fails>=5){lock=Date.now()+30000;fails=0}er('Wrong password.')}});return}
var p1=$('m1').value;if(p1.length<8){er('Use 8+ characters.');return}if(p1!==$('m2').value){er('Passwords differ.');return}
var pre=mode==='change'?derive($('m0').value,S.auth.salt,S.auth.iter).then(function(h){return eq(h,S.auth.hash)}):Promise.resolve(true);
pre.then(function(ok){if(!ok){er('Current password wrong.');return}return mk(p1).then(function(a){S.auth=a;save();close();if(mode==='setup')start('admin');else toast('Password changed')})})}}
function adminEntry(){modal(S.auth?'login':'setup')}
/* session */
function start(r,id){role=r;me=id||null;var adm=r==='admin';document.body.classList.remove('lk');document.body.classList.toggle('adm',adm);
$('mode').textContent=adm?'ADMIN':(by(id)?by(id).name.split(' ')[0].toUpperCase():'');
$('admtab').style.display=adm?'flex':'none';sel=adm?(by(sel)?sel:(S.roster[0]&&S.roster[0].id)):id;fillSel();pick(sel);showV('id')}
function end(){$('boot').classList.remove('o');role=me=sel=null;document.body.classList.add('lk');document.body.classList.remove('adm');$('gp').value='';$('ge').textContent=''}
function showV(v){document.querySelectorAll('.vw').forEach(function(e){e.classList.toggle('on',e.id==='v-'+v)});document.querySelectorAll('#nav button').forEach(function(b){b.classList.toggle('on',b.dataset.v===v)});renderAll()}
function fillSel(){var h=S.roster.map(function(r){return'<option value="'+esc(r.id)+'">'+esc(r.name)+' · '+esc(r.cls)+'</option>'}).join('');$('sel').innerHTML=h;$('sel').value=sel||''}
function pick(id){var r=by(id);if(!r)return;sel=id;dirty=false;cur={a:r.a,i:r.i,p:r.p,t:r.t,s:r.s};if($('sel'))$('sel').value=id;renderAll()}
/* radar */
var NS='http://www.w3.org/2000/svg',CX=180,CY=170,R=108,rd={},disp={a:0,i:0,p:0,t:0,s:0},run=false;
function el(t,a,p){var e=document.createElementNS(NS,t);for(var k in a)e.setAttribute(k,a[k]);if(p)p.appendChild(e);return e}
function pt(i,v){var a=-Math.PI/2+i*2*Math.PI/5,r=R*v/100;return[CX+r*Math.cos(a),CY+r*Math.sin(a)]}
function ps(o){return AB.map(function(x,j){var p=pt(j,o[x.k]);return p[0].toFixed(1)+','+p[1].toFixed(1)}).join(' ')}
function build(){var s=$('rd');s.innerHTML='';var d=el('defs',{},s),f=el('filter',{id:'gl',x:'-30%',y:'-30%',width:'160%',height:'160%'},d);el('feGaussianBlur',{stdDeviation:3,result:'b'},f);var mg=el('feMerge',{},f);el('feMergeNode',{in:'b'},mg);el('feMergeNode',{in:'SourceGraphic'},mg);
[20,40,60,80,100].forEach(function(l){el('polygon',{points:ps({a:l,i:l,p:l,t:l,s:l}),fill:'none',stroke:l===100?'#1f4a73':'rgba(255,255,255,.1)'},s)});
AB.forEach(function(x,j){var e=pt(j,100);el('line',{x1:CX,y1:CY,x2:e[0],y2:e[1],stroke:'rgba(255,255,255,.1)'},s)});
var sw=el('g',{'class':'sw'},s);el('path',{d:'M180 170 L180 62 A108 108 0 0 0 '+(CX+R*Math.cos(-130*Math.PI/180)).toFixed(1)+' '+(CY+R*Math.sin(-130*Math.PI/180)).toFixed(1)+' Z',fill:'#3fe0ff','fill-opacity':.13},sw);el('line',{x1:180,y1:170,x2:180,y2:62,stroke:'#3fe0ff','stroke-opacity':.8},sw);
rd.poly=el('polygon',{fill:'rgba(63,224,255,.25)',stroke:'#3fe0ff','stroke-width':2.5,'stroke-linejoin':'round',filter:'url(#gl)'},s);rd.dots=[];rd.v=[];
AB.forEach(function(x,j){var l=pt(j,114),an=l[0]<CX-10?'end':l[0]>CX+10?'start':'middle',tp=j===0;var t=el('text',{x:l[0],y:tp?l[1]-12:l[1]+2,'text-anchor':an,'font-size':14,'font-weight':600,fill:'#7f98b8'},s);t.textContent=x.n;rd.v.push(el('text',{x:l[0],y:tp?l[1]+2:l[1]+17,'text-anchor':an,'font-size':17,'font-weight':700,fill:'#e4f1ff'},s))});
AB.forEach(function(){rd.dots.push(el('circle',{r:4.5,fill:'#3fe0ff',stroke:'#03050c','stroke-width':1.5},s))})}
function draw(){rd.poly.setAttribute('points',ps(disp));AB.forEach(function(x,j){var p=pt(j,disp[x.k]);rd.dots[j].setAttribute('cx',p[0]);rd.dots[j].setAttribute('cy',p[1]);rd.v[j].textContent=Math.round(disp[x.k])})}
function step(){var mv=false;AB.forEach(function(x){var d=cur[x.k]-disp[x.k];if(Math.abs(d)>.05){disp[x.k]+=d*.17;mv=true}else disp[x.k]=cur[x.k]});draw();if(mv)requestAnimationFrame(step);else run=false}
function kick(){if(!run){run=true;requestAnimationFrame(step)}}
/* render */
function paintCore(){var r=by(sel);if(!r)return;var o=ov(cur),g=grade(o),T=TR[gk(g)],col=TC[gk(g)];
$('gchip').innerHTML='<span style="color:'+col+';text-shadow:0 0 12px '+col+'">'+g+'</span><small>OVERALL '+o+'</small>';$('av').textContent=r.name.charAt(0).toUpperCase();$('nm').textContent=r.name;$('sb').textContent=r.cls+' · ID '+r.id.slice(-5).toUpperCase();
$('on').textContent=o;$('og').textContent=' '+g;$('og').style.color=col;$('arc').style.stroke=col;$('arc').setAttribute('stroke-dashoffset',(351.86*(1-o/100)).toFixed(1));$('arc').style.filter='drop-shadow(0 0 6px '+col+')';
$('tt').textContent=T[0];$('tt').style.color=col;$('tp').textContent=T[1];
var adm=role==='admin';AB.forEach(function(x){var i=$('in-'+x.k);if(i){i.value=cur[x.k];i.disabled=!adm;i.style.setProperty('--f',cur[x.k]+'%');$('v-'+x.k).textContent=cur[x.k]+' '+grade(cur[x.k])}});
$('svs').disabled=!dirty;
var vals=AB.map(function(x){return cur[x.k]}),mean=vals.reduce(function(a,b){return a+b},0)/5,sd=Math.sqrt(vals.reduce(function(a,b){return a+(b-mean)*(b-mean)},0)/5),bal=Math.round(clamp(100-sd*2.2));
var ord=AB.slice().sort(function(a,b){return cur[b.k]-cur[a.k]}),top=ord[0],oth=S.roster.filter(function(x){return x.id!==sel}),hi=oth.filter(function(x){return ov(x)>o}).length,lo=oth.filter(function(x){return ov(x)<o}).length,pc=oth.length?Math.round(100*lo/oth.length):100;
$('s1').textContent=bal>=82?'All-rounder':ARCH[top.k];$('s2').textContent='#'+(hi+1)+' of '+(oth.length+1);$('s3').textContent=bal+'%';$('m3').style.width=bal+'%';$('s4').textContent=pc+'th';$('m4').style.width=pc+'%';kick();paintGraph()}
function ranked(){return S.roster.slice().sort(function(a,b){return b.pp-a.pp})}
function paintDash(){var r=by(sel);if(!r)return;$('pp').textContent=r.pp.toLocaleString();var ks=Object.keys(r.att),pr=ks.filter(function(k){return r.att[k]==='present'}).length;$('ar').textContent=ks.length?Math.round(100*pr/ks.length)+'%':'—';
$('pr').textContent='#'+(ranked().indexOf(r)+1)+'/'+S.roster.length;$('td').textContent=mine().length;
var done=r.att[today()]==='present';$('ci').textContent=done?'CHECKED IN':'CHECK IN';$('ci').disabled=done;$('ct').textContent=done&&r.ci?r.ci:'';
$('act').innerHTML=r.act.length?r.act.map(function(a){return'<div class="li"><div><b>'+esc(a.t)+'</b><small>'+a.d+' · '+a.h+'</small></div></div>'}).join(''):'<div class="em">NO RECENT ACTIVITY</div>'}
function paintRankOld(){var full=role==='admin'||S.showAll,rs=ranked();if(!full)rs=rs.filter(function(r){return r.id===me});
$('rb').innerHTML=rs.map(function(r,i){var o=ov(r);return'<tr class="'+(r.id===sel?'me':'')+'" data-id="'+esc(r.id)+'"><td class="mo">'+(ranked().indexOf(r)+1)+'</td><td>'+esc(r.name)+'</td><td>'+esc(r.cls)+'</td><td>'+o+' <span style="color:'+TC[gk(grade(o))]+'">'+grade(o)+'</span></td></tr>'}).join('')}
function paintTrade(){var r=by(sel);if($('se'))$('se').value=r?r.pp:'';$('xt').innerHTML=S.roster.filter(function(x){return x.id!==sel}).map(function(x){return'<option value="'+esc(x.id)+'">'+esc(x.name)+'</option>'}).join('');$('xtf').style.display=$('xm').value==='r'?'none':'flex';
$('tx').innerHTML=r.tx.length?r.tx.slice().reverse().map(function(t){return'<div class="li"><div><b>'+esc(t.l)+'</b><small>'+esc(t.m||'—')+' · '+t.d+'</small></div><span class="mo '+(t.a<0?'er':'ok')+'">'+(t.a>0?'+':'')+t.a+' PP</span></div>'}).join(''):'<div class="em">NO TRANSACTIONS</div>'}
function mine(){var r=by(sel);return(S.assign||[]).map(function(a,i){return{a:a,i:i}}).filter(function(x){return role==='admin'||(r&&(x.a.cls==='All'||x.a.cls===r.cls))})}
var nimg='';
function shrink(file,cb){var fr=new FileReader();fr.onload=function(){var im=new Image();im.onload=function(){var k=Math.min(1,1000/Math.max(im.width,im.height)),c=document.createElement('canvas'),x=c.getContext('2d');c.width=Math.round(im.width*k);c.height=Math.round(im.height*k);x.fillStyle='#fff';x.fillRect(0,0,c.width,c.height);x.drawImage(im,0,0,c.width,c.height);var q=.8,u=c.toDataURL('image/jpeg',q);while(u.length>600000&&q>.35){q-=.1;u=c.toDataURL('image/jpeg',q)}cb(u)};im.onerror=function(){cb(/^image\/(jpeg|png|gif|webp)$/.test(file.type)&&file.size<800000?fr.result:'')};im.src=fr.result};fr.onerror=function(){cb('')};fr.readAsDataURL(file)}
function paintNews(){var r=by(sel),adm=role==='admin';var ps=(S.posts||[]).map(function(p,i){return{p:p,i:i}}).filter(function(x){return adm||x.p.cls==='All'||(r&&x.p.cls===r.cls)});
$('nl').innerHTML=ps.length?ps.map(function(x){var p=x.p;return'<div class="po"><div style="display:flex;justify-content:space-between;gap:8px;align-items:flex-start"><div><b style="font-size:14px">'+esc(p.t||'Notice')+'</b><small style="display:block;color:var(--mu);font-size:11px">'+esc(p.d)+' '+esc(p.h||'')+' · '+esc(p.cls)+'</small></div>'+(adm?'<button class="gh dg" data-pdel="'+x.i+'">✕</button>':'')+'</div>'+((p.img&&p.img.indexOf('data:image/')===0)?'<img src="'+p.img+'" alt="Flyer">':'')+(p.m?'<p style="white-space:pre-wrap;font-size:13px;margin-top:4px">'+esc(p.m)+'</p>':'')+'</div>'}).join(''):'<div class="em">NO NOTICES</div>'}
var subAid=null;
function paintTask(){var adm=role==='admin',r=adm?null:by(me);
var h=mine().sort(function(x,y){return(x.a.due||'9999')<(y.a.due||'9999')?-1:1}).map(function(x){var a=x.a,od=a.due&&today()>a.due,tag,extra='',btn='';
if(adm){var cl=S.roster.filter(function(u){return a.cls==='All'||u.cls===a.cls}),has=function(u){return u.tasks.some(function(t){return t.aid===a.id})},dn=cl.filter(has),pn=cl.filter(function(u){return!has(u)}),fn=function(u){return esc(u.name)};
extra='<small>Submitted '+dn.length+'/'+cl.length+(dn.length?' · Done: '+dn.map(fn).join(', '):'')+(pn.length?' · Pending: '+pn.map(fn).join(', '):'')+'</small>';tag=od?'overdue':'open';btn='<button class="gh dg" data-del="'+x.i+'" style="margin-left:8px">✕</button>'}
else{var sb=r?r.tasks.filter(function(t){return t.aid===a.id})[0]:null;tag=sb?(sb.st==='late'?'late':'submitted'):(od?'overdue':'open');if(sb)extra='<small>Your work: '+esc(sb.f||sb.n||'sent')+' · '+esc(sb.d)+'</small>';btn='<button class="gh" data-sub="'+x.i+'" style="margin-left:8px">'+(sb?'Resubmit':'Submit')+'</button>'}
return'<div class="li"><div><b>'+esc(a.t)+'</b><small>'+(a.n?esc(a.n)+' · ':'')+esc(a.cls)+' · due '+esc(a.due||'—')+'</small>'+extra+'</div><span class="tag '+((tag==='open'||tag==='submitted')?'ok':'er')+'">'+tag+'</span>'+btn+'</div>'}).join('');$('tl').innerHTML=h||'<div class="em">NO ASSIGNMENTS</div>'}
function paintAtt(){var r=by(sel),ks=Object.keys(r.att).sort().reverse();$('ap').textContent=ks.filter(function(k){return r.att[k]==='present'}).length;$('aa').textContent=ks.filter(function(k){return r.att[k]==='absent'}).length;
$('al').innerHTML=ks.length?ks.map(function(k){return'<div class="li"><b>'+k+'</b><span class="tag '+(r.att[k]==='present'?'ok':'er')+'">'+r.att[k]+'</span></div>'}).join(''):'<div class="em">NO RECORDS</div>'}
function paintAdm(){if(role!=='admin')return;var r=by(sel);$('ls').textContent=r?(r.login?'Login set: '+r.login.user:'No login for this subject.'):'';$('lu').value=r?(r.login?r.login.user:r.name.toLowerCase().split(' ')[0].replace(/[^a-z0-9]/g,'')):'';$('lp').value='';$('sa').checked=!!S.showAll;
Array.prototype.forEach.call($('pre').children,function(b){});S.weights.forEach(function(v,j){$('w-'+j).value=v;$('wv-'+j).textContent=v})}
function paintOva(){var r=by(sel);if(!r)return;var o=ov(r),cc=CC[r.cls]||'#3fe0ff',cl=S.roster.filter(function(u){return u.cls===r.cls}),
rk=cl.slice().sort(function(a,b){return ov(b)-ov(a)}).findIndex(function(u){return u.id===r.id})+1;
$('ovac').style.setProperty('--cc',cc);$('ovp').textContent=r.name.charAt(0).toUpperCase();$('ovc').textContent=r.cls.toUpperCase();$('ovn').textContent=r.name;
var bx=function(x,c){var v=r[x.k];return '<div class="ova-bx '+(c||'')+'"><div><small>'+x.n.toUpperCase()+'</small><em>'+v+'</em></div><span class="g'+grade(v).charAt(0)+'">'+grade(v)+'</span></div>'},C=2*Math.PI*48;
$('ovg').innerHTML='<div class="ova-col">'+bx(AB[0])+bx(AB[1])+'</div><div class="ova-ring"><svg viewBox="0 0 112 112"><circle cx="56" cy="56" r="48" fill="none" stroke="#1f4a73" stroke-width="6"/><circle cx="56" cy="56" r="48" fill="none" stroke="#ffb347" stroke-width="6" stroke-dasharray="'+C*o/100+' '+C+'" stroke-linecap="round" style="filter:drop-shadow(0 0 6px #ffb347)"/></svg><div><span>'+grade(o)+'<small>'+o+'/100</small></span></div></div><div class="ova-col">'+bx(AB[2])+bx(AB[3])+'</div><div class="ova-5">'+bx(AB[4])+'</div>';
var h='<div class="li"><b>Overall rank in '+r.cls+'</b><span class="mo">#'+rk+' / '+cl.length+'</span></div>';
AB.forEach(function(x){var k=cl.slice().sort(function(a,b){return b[x.k]-a[x.k]}).findIndex(function(u){return u.id===r.id})+1;h+='<div class="li"><b>'+x.n+'<small>'+x.d+'</small></b><span class="mo">#'+k+' · '+r[x.k]+'</span></div>'});
$('ovs').innerHTML=h}
function renderAll(){if(!role)return;paintId();paintOva();paintCore();paintDash();paintRank();paintTrade();paintTask();paintNews();paintAtt();paintAdm()}
function ui(){var h='';AB.forEach(function(x){h+='<div class="ab"><div class="l"><span>'+x.n+'</span><span class="mo" id="v-'+x.k+'"></span></div><input type="range" id="in-'+x.k+'" min="0" max="100" disabled><small>'+x.d+'</small></div>'});$('sl').innerHTML=h;
AB.forEach(function(x){$('in-'+x.k).oninput=function(e){if(role!=='admin')return;cur[x.k]=+e.target.value;dirty=true;paintCore()}});
$('pre').innerHTML=Object.keys(PR).map(function(n){return'<button class="gh" data-p="'+n+'">'+n+'</button>'}).join('');
$('wg').innerHTML=AB.map(function(x,j){return'<label style="font-size:12px;color:var(--mu)">'+x.n+' <b id="wv-'+j+'">1</b><input type="range" id="w-'+j+'" min="0" max="5" value="1"></label>'}).join('');
AB.forEach(function(x,j){$('w-'+j).oninput=function(e){S.weights[j]=+e.target.value;save();renderAll()}})}
/* export */
function dl(name,data,type){if(window.claude&&claude.use){claude.use('downloads').then(function(d){if(!d){toast('Saving files is not available here');return}return d.save({filename:name,data:data}).then(function(){toast('Saved '+name)},function(e){toast(e&&e.code==='declined'?'Save cancelled':'Could not save the file')})});return}toast('Saving files is not available here')}
function snapshot(){save();var seed=$('seed').textContent,html='<!DOCTYPE html>\n'+document.documentElement.outerHTML;
var d=JSON.stringify(S).replace(/</g,'\\u003c');html=html.replace(/(<script id="seed" type="application\/json">)[\s\S]*?(<\/script>)/,function(m,a,b){return a+d+b});
html=html.replace(/<body class="[^"]*"/,'<body class="lk"');dl('s-system.html',html,'text/html')}
function confirm2(btn,fn){if(btn._t){clearTimeout(btn._t);btn._t=null;btn.textContent=btn._l;fn();return}btn._l=btn.textContent;btn.textContent='Tap again';btn._t=setTimeout(function(){btn._t=null;btn.textContent=btn._l},3000)}
function stars(){if(matchMedia('(prefers-reduced-motion:reduce)').matches)return;var c=$('st'),x=c.getContext('2d'),w,h,P=[];function z(){w=c.width=innerWidth;h=c.height=innerHeight}z();addEventListener('resize',z);
for(var j=0;j<(innerWidth<600?45:90);j++)P.push({x:Math.random()*w,y:Math.random()*h,r:Math.random()*1.3+.3,v:Math.random()*.18+.04,t:Math.random()*6.28});
(function L(t){x.clearRect(0,0,w,h);x.fillStyle='#3fe0ff';P.forEach(function(p){p.y-=p.v;if(p.y<-2){p.y=h+2;p.x=Math.random()*w}x.globalAlpha=.2+.25*Math.sin(t/900+p.t);x.beginPath();x.arc(p.x,p.y,p.r,0,6.283);x.fill()});requestAnimationFrame(L)})(0)}
var CC={'Class S':'#18c8ff','Class A':'#ffd400','Class B':'#2f6bff','Class C':'#ff3b4e','Class D':'#2ee66b'};
function cnt(e,v){var s=+e.dataset.v||0;e.dataset.v=v;if(s===v||matchMedia('(prefers-reduced-motion:reduce)').matches){e.textContent=v.toLocaleString();return}var t0=performance.now();(function f(t){var k=Math.min(1,(t-t0)/900),x=1-Math.pow(1-k,3);e.textContent=Math.round(s+(v-s)*x).toLocaleString();if(k<1)requestAnimationFrame(f)})(t0)}
function paintId(){var r=by(sel);if(!r)return;var o=ov(r),mx=Math.max.apply(null,S.roster.map(function(u){return u.pp}).concat(1)),ks=Object.keys(r.att),pr=ks.filter(function(k){return r.att[k]==='present'}).length;
$('idc').style.setProperty('--cc',CC[r.cls]||'#3fe0ff');$('iph').textContent=r.name.charAt(0).toUpperCase();
$('in1').textContent='S01 T'+r.id.replace(/\D/g,'').slice(-6).padStart(6,'0');$('in2').textContent=r.name;$('in3').textContent=r.cls+' · Grade '+grade(o);
cnt($('ipn'),r.pp);$('ipb').style.width=Math.max(4,Math.round(100*r.pp/mx))+'%';
$('is1').textContent=o+' '+grade(o);$('is2').textContent='#'+(ranked().indexOf(r)+1)+' / '+S.roster.length;$('is3').textContent=ks.length?Math.round(100*pr/ks.length)+'%':'—';var os=S.roster.map(ov),mu=os.reduce(function(a,b){return a+b},0)/os.length,sd=Math.sqrt(os.reduce(function(a,b){return a+(b-mu)*(b-mu)},0)/os.length)||1,z=(o-mu)/sd;$('is4').textContent=(z>=0?'+':'')+z.toFixed(2)+'σ';$('is5').textContent=Math.round(100*os.filter(function(x){return x<o}).length/os.length)+'th';$('is6').textContent=o>=90?'ELITE':o>=80?'ADVANCED':o>=70?'PROFICIENT':o>=60?'STANDARD':'DEVELOPING';
$('ibars').innerHTML=AB.map(function(x){var v=r[x.k];return'<div class="ib"><span>'+x.n+'</span><div class="ibt"><i style="width:'+v+'%;background:'+TC[gk(grade(v))]+'"></i></div><b>'+v+'</b></div>'}).join('');
$('iact').innerHTML=r.act.length?r.act.slice(0,3).map(function(a){return'<div class="li"><div><b>'+esc(a.t)+'</b><small>'+esc(a.d)+' · '+esc(a.h)+'</small></div></div>'}).join(''):'<div class="em">NO RECENT ACTIVITY</div>';spark(r)}
function grant(adm){var a=$('acc'),n=by(sel),L=['IDENTITY VERIFIED','SYNCING PRIVATE POINT LEDGER','LOADING '+(adm?'ADMIN HEAD PROFILE':(n?n.name.toUpperCase():'PROFILE'))];$('accs').innerHTML='';a.classList.add('on');L.forEach(function(t,j){setTimeout(function(){var d=document.createElement('div');d.textContent='> '+t;$('accs').appendChild(d)},250*(j+1))});setTimeout(function(){a.classList.remove('on')},1700)}
var rkM='pp';
function paintRank(){var full=role==='admin'||S.showAll,all=S.roster.slice().sort(function(a,b){return rkM==='pp'?b.pp-a.pp:(ov(b)-ov(a)||b.pp-a.pp)}),rs=full?all:all.filter(function(r){return r.id===me}),val=function(r){return rkM==='pp'?r.pp:ov(r)},mx=Math.max.apply(null,all.map(val).concat(1)),u=rkM==='pp'?'PPt':'OAA';
$('rb').innerHTML=rs.map(function(r,i){var o=ov(r),k=all.indexOf(r)+1,v=val(r);return'<div class="rkr'+(r.id===sel?' me':'')+(k<4?' t'+k:'')+'" data-id="'+esc(r.id)+'" style="--cc:'+(CC[r.cls]||'#3fe0ff')+';--w:'+Math.max(3,Math.round(100*v/mx))+'%;animation-delay:'+(i*50)+'ms"><b class="rk">'+k+'</b><div class="rn"><span class="rav">'+esc(r.name.charAt(0).toUpperCase())+'</span><div><strong>'+esc(r.name)+'</strong><small>'+esc(r.cls)+' · OAA '+o+' <u style="text-decoration:none;color:'+TC[gk(grade(o))]+'">'+grade(o)+'</u></small></div></div><div class="rv2"><b>'+v.toLocaleString()+'</b><small>'+u+'</small></div><div class="rb2"><i></i></div></div>'}).join('')}

var gM='oa',GX=null,gSig='';
function gval(o,m){return m==='oa'?ov(o):o[m]}
function ro(k){var g=GX;if(!g)return;var v=g.ser[g.si],d=k>0?v[k]-v[k-1]:0,av=Math.round(g.ser.reduce(function(a,q){return a+q[k]},0)/g.ser.length);$('xr').innerHTML='<span>'+esc(g.lab[k].slice(5))+'</span><b>'+esc(g.L[g.si].name)+'</b><b class="px">'+v[k]+'</b><em class="'+(d>0?'up':d<0?'dn':'')+'">'+(d>0?'▲ +':d<0?'▼ ':'▬ ')+d+'</em><span>AVG '+av+'</span>';var h=$('xh');if(h){$('xhl').setAttribute('x1',g.X(k));$('xhl').setAttribute('x2',g.X(k));$('xhc').setAttribute('cx',g.X(k));$('xhc').setAttribute('cy',g.Y(v[k]));h.style.display=k===g.n-1?'none':''}}
function paintGraph(){if(!role||!by(sel)||!$('gline'))return;var full=role==='admin'||S.showAll,L=full?S.roster:S.roster.filter(function(r){return r.id===me}),m=gM,ds={};
L.forEach(function(r){(r.hist||[]).forEach(function(h){ds[h.d]=1})});var lab=Object.keys(ds).sort();if(!lab.length)lab=[today()];if(lab.length<2)lab.unshift(lab[0]);
var n=lab.length,W=360,H=240,pl=8,pr=40,pt=12,pb=22,X=function(k){return pl+k*(W-pl-pr)/(n-1)},si=0;
var ser=L.map(function(r,j){if(r.id===sel)si=j;var hs=r.hist||[];return lab.map(function(d,k){var v=null;hs.forEach(function(h){if(h.d<=d)v=h.v});if(!v)v=hs[0]?hs[0].v:r;if(k===n-1)v=r.id===sel?cur:r;return gval(v,m)})});
var al=[].concat.apply([],ser),mn=Math.min.apply(null,al),mx=Math.max.apply(null,al),lo=Math.max(0,Math.floor((mn-5)/10)*10),hi=Math.min(100,Math.ceil((mx+5)/10)*10);if(hi-lo<20){hi=Math.min(100,lo+20);lo=hi-20}
var Y=function(v){return pt+(hi-v)/(hi-lo)*(H-pt-pb)},sr=L[si],c=CC[sr.cls]||'#3fe0ff',vis=$('v-core').classList.contains('on'),sig=sel+m+n+L.length,an=vis&&sig!==gSig,lc=an?' ln':'';if(vis)gSig=sig;
var sv='<svg id="gsv" viewBox="0 0 '+W+' '+H+'" style="width:100%;display:block;touch-action:pan-y"><defs><linearGradient id="ga" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="'+c+'" stop-opacity=".32"/><stop offset="1" stop-color="'+c+'" stop-opacity="0"/></linearGradient></defs>',j,k;
for(j=0;j<5;j++){var q=lo+(hi-lo)*j/4;sv+='<line x1="'+pl+'" x2="'+(W-pr)+'" y1="'+Y(q)+'" y2="'+Y(q)+'" stroke="rgba(255,255,255,.07)"/><text x="'+(W-pr+5)+'" y="'+(Y(q)+3)+'" font-size="9" fill="#7f98b8" font-family="monospace">'+Math.round(q)+'</text>'}
for(k=0;k<n;k++){sv+='<line x1="'+X(k)+'" x2="'+X(k)+'" y1="'+pt+'" y2="'+(H-pb)+'" stroke="rgba(255,255,255,.04)"/>';if(k===0||k===n-1||(n<=6))sv+='<text x="'+X(k)+'" y="'+(H-7)+'" text-anchor="'+(k===0?'start':k===n-1?'end':'middle')+'" font-size="9" fill="#7f98b8" font-family="monospace">'+lab[k].slice(5,10)+'</text>'}
var pts=function(v){return v.map(function(x,k){return X(k).toFixed(1)+','+Y(x).toFixed(1)}).join(' ')};
L.forEach(function(r,j){if(j!==si)sv+='<polyline'+(an?' pathLength="1"':'')+' class="'+lc.trim()+'" points="'+pts(ser[j])+'" fill="none" stroke="'+(CC[r.cls]||'#3fe0ff')+'" stroke-width="1.2" stroke-opacity=".38" stroke-linejoin="round"/>'});
var av=lab.map(function(d,k){return ser.reduce(function(a,v){return a+v[k]},0)/ser.length}),sv2=ser[si],e=n-1,ly=Y(sv2[e]);
sv+='<polyline points="'+pts(av)+'" fill="none" stroke="#fff" stroke-width="1.2" stroke-dasharray="3 4" stroke-opacity=".7"/><polygon points="'+X(0)+','+(H-pb)+' '+pts(sv2)+' '+X(e)+','+(H-pb)+'" fill="url(#ga)"/><polyline'+(an?' pathLength="1"':'')+' class="'+lc.trim()+'" points="'+pts(sv2)+'" fill="none" stroke="'+c+'" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"/>'
+'<line x1="'+pl+'" x2="'+(W-pr)+'" y1="'+ly+'" y2="'+ly+'" stroke="'+c+'" stroke-dasharray="2 3" stroke-opacity=".7"/><circle class="pulse" cx="'+X(e)+'" cy="'+ly+'" r="4" fill="'+c+'"/><circle cx="'+X(e)+'" cy="'+ly+'" r="3.5" fill="'+c+'"/><rect x="'+(W-pr+1)+'" y="'+(ly-8)+'" width="'+(pr-2)+'" height="16" rx="2" fill="'+c+'"/><text x="'+(W-pr/2)+'" y="'+(ly+4)+'" text-anchor="middle" font-size="10" font-weight="700" fill="#03121a" font-family="monospace">'+sv2[e]+'</text>'
+'<g id="xh" style="display:none"><line id="xhl" y1="'+pt+'" y2="'+(H-pb)+'" stroke="#fff" stroke-opacity=".45" stroke-dasharray="2 3"/><circle id="xhc" r="4" fill="#fff"/></g></svg>';
$('gline').innerHTML=sv;GX={lab:lab,X:X,Y:Y,ser:ser,L:L,W:W,pl:pl,pr:pr,si:si,n:n};ro(n-1);
var dl=function(v){return v[n-1]-v[n-2]},ix=L.map(function(r,j){return j}).sort(function(a,b){return ser[b][e]-ser[a][e]}),dc=function(d){return'<em class="'+(d>0?'up':d<0?'dn':'')+'">'+(d>0?'▲'+d:d<0?'▼'+Math.abs(d):'▬ 0')+'</em>'};
var tk=ix.map(function(j){var d=dl(ser[j]);return'<span>'+esc(L[j].name.split(' ')[0].toUpperCase())+' <b>'+ser[j][e]+'</b> '+dc(d)+'</span>'}).join('');$('tkt').innerHTML=tk+tk;
$('gbars').innerHTML=ix.map(function(j){var r=L[j],v=ser[j],cc=CC[r.cls]||'#3fe0ff',sp=v.map(function(x,k){return(k*60/(n-1)).toFixed(1)+','+(2+(hi-x)/(hi-lo)*16).toFixed(1)}).join(' ');return'<div class="wl'+(r.id===sel?' me':'')+'" data-id="'+esc(r.id)+'"><span class="wn"><i style="background:'+cc+'"></i>'+esc(r.name.split(' ')[0])+'</span><svg class="sk" viewBox="0 0 60 20" preserveAspectRatio="none"><polyline points="'+sp+'" fill="none" stroke="'+cc+'" stroke-width="1.5" vector-effect="non-scaling-stroke"/></svg><b>'+v[e]+'</b>'+dc(dl(v))+'</div>'}).join('')}
function spark(r){var e=$('ispk'),t=r.tx.slice(-8),b=r.pp,pv=[b];if(!t.length){e.innerHTML='<div class="em">NO TRANSACTIONS YET</div>';return}for(var j=t.length-1;j>=0;j--){b-=t[j].a;pv.unshift(b)}var mx=Math.max.apply(null,pv),mn=Math.min.apply(null,pv),sp=(mx-mn)||1,xy=pv.map(function(v,j){return(j*300/(pv.length-1)).toFixed(1)+','+(64-(v-mn)/sp*56).toFixed(1)}).join(' ');e.innerHTML='<svg viewBox="0 0 300 70" preserveAspectRatio="none"><polygon points="0,70 '+xy+' 300,70" fill="rgba(63,224,255,.15)"/><polyline points="'+xy+'" fill="none" stroke="#3fe0ff" stroke-width="2" vector-effect="non-scaling-stroke"/></svg>'}
function pts(){$('rkt').onclick=function(e){var b=e.target.closest('button');if(!b)return;rkM=b.dataset.m;Array.prototype.forEach.call($('rkt').children,function(x){x.classList.toggle('on',x===b)});paintRank()};var b=$('boot');for(var j=0;j<16;j++){var s=document.createElement('span');s.className='pt';s.style.cssText='left:'+(Math.random()*100)+'%;animation-duration:'+(5+Math.random()*6)+'s;animation-delay:-'+(Math.random()*8)+'s';b.appendChild(s)}}
/* init */
function init(){load();ui();build();pts();
$('gb').onclick=studentLogin;$('gate').onkeydown=function(e){if(e.key==='Enter'){e.preventDefault();studentLogin()}};
var tp=0,tm;$('lg').onclick=function(){tp++;clearTimeout(tm);tm=setTimeout(function(){tp=0},2500);if(tp>=5){tp=0;adminEntry()}};
if(location.hash==='#admin'){adminEntry()}
$('out').onclick=function(){end();toast('Signed out')};
$('nav').onclick=function(e){var b=e.target.closest('button');if(b)showV(b.dataset.v)};
$('sel').onchange=function(e){pick(e.target.value)};
$('gm').onclick=function(e){var b=e.target.closest('button');if(!b)return;gM=b.dataset.m;Array.prototype.forEach.call($('gm').children,function(x){x.classList.toggle('on',x===b)});paintGraph()};
$('gbars').onclick=function(e){var r=e.target.closest('[data-id]');if(r&&role==='admin')pick(r.dataset.id)};
var gh=function(e){var g=GX;if(!g||!$('gsv'))return;var b=$('gsv').getBoundingClientRect(),x=(e.clientX-b.left)/b.width*g.W,k=Math.round((x-g.pl)/((g.W-g.pl-g.pr)/(g.n-1)));ro(Math.max(0,Math.min(g.n-1,k)))};
$('gline').onpointermove=gh;$('gline').onpointerdown=gh;$('gline').onpointerleave=function(){if(GX)ro(GX.n-1)};
$('rb').onclick=function(e){var tr=e.target.closest('[data-id]');if(tr&&role==='admin'){pick(tr.dataset.id)}};
$('scan').onclick=function(){var o=ov(cur);log('Scan: '+(by(sel)||{}).name);AB.forEach(function(x,j){setTimeout(function(){log(x.n+' '+cur[x.k]+' → '+grade(cur[x.k]))},300*(j+1))});setTimeout(function(){log('Verdict '+o+'/100 · '+grade(o));toast('Grade '+grade(o))},1800)};
$('svs').onclick=function(){if(role!=='admin')return;var r=by(sel);snap();AB.forEach(function(x){r[x.k]=cur[x.k]});r.hist.push({d:today()+' '+nowT(),v:{a:r.a,i:r.i,p:r.p,t:r.t,s:r.s}});act(r,'Scores updated by admin');dirty=false;save();renderAll();toast('Scores saved')};
$('ci').onclick=function(){var r=by(sel);if(!r||r.att[today()]==='present')return;r.att[today()]='present';r.ci=nowT();act(r,'Checked in at '+r.ci);save();renderAll();toast('Checked in')};
$('xm').onchange=paintTrade;
$('xs').onclick=function(){var r=by(sel),a=parseInt($('xa').value,10),m=$('xo').value.trim(),t=$('xm').value;if(!a||a<=0){toast('Enter a valid amount');return}if(a>r.pp){toast('Insufficient balance');return}
if(t==='t'){var to=by($('xt').value);if(!to){toast('Choose recipient');return}r.pp-=a;to.pp+=a;r.tx.push({l:'Sent to '+to.name,a:-a,m:m,d:today()});to.tx.push({l:'Received from '+r.name,a:a,m:m,d:today()});act(r,'Sent '+a+' PP to '+to.name);act(to,'Received '+a+' PP from '+r.name)}
else{r.pp-=a;r.tx.push({l:'Redeemed: '+(m||'campus item'),a:-a,m:m,d:today()});act(r,'Redeemed '+a+' PP')}
$('xa').value=$('xo').value='';save();renderAll();toast('Transaction complete')};
$('sv2').onclick=function(){if(role!=='admin')return;var r=by(sel),v=parseInt($('se').value,10);if(!r||isNaN(v)||v<0){toast('Enter a balance of 0 or more');return}var d=v-r.pp;if(!d){toast('Balance unchanged');return}r.pp=v;r.tx.push({l:'Admin set balance',a:d,m:'Set to '+v+' PP',d:today()});act(r,'Admin set balance to '+v+' PP');save();renderAll();toast('Balance set to '+v)};
$('gs').onclick=function(){if(role!=='admin')return;var r=by(sel),a=parseInt($('ga2').value,10);if(!a){toast('Enter ± points');return}r.pp=Math.max(0,r.pp+a);r.tx.push({l:a>0?'Admin grant':'Admin deduction',a:a,m:$('gr').value.trim(),d:today()});act(r,'Admin '+(a>0?'granted ':'deducted ')+Math.abs(a)+' PP');$('ga2').value=$('gr').value='';save();renderAll();toast('Applied')};
$('tl').onclick=function(e){var sb=e.target.closest('[data-sub]');if(sb&&role!=='admin'){var as=S.assign&&S.assign[+sb.dataset.sub];if(as){subAid=as.id;$('spt').textContent='Submit: '+as.t;$('sf').value='';$('sfn').textContent='No file chosen';$('sn').value='';$('sp').style.display='block';$('sp').scrollIntoView({behavior:'smooth',block:'center'})}return}var b=e.target.closest('[data-del]');if(!b||role!=='admin')return;confirm2(b,function(){var i=+b.dataset.del;if(S.assign&&S.assign[i]){S.assign.splice(i,1);save();renderAll();toast('Assignment removed')}})};
$('nf').onclick=function(){this.value=''};
$('nf').onchange=function(){var f=this.files[0];if(!f){nimg='';$('nfn').textContent='No image chosen';$('nprev').style.display='none';return}$('nfn').textContent='Preparing '+f.name+'…';shrink(f,function(u){nimg=u;if(u){$('nfn').textContent='Selected: '+f.name;$('nprev').src=u;$('nprev').style.display='block'}else{$('nfn').textContent='Could not read that file. Use a JPG or PNG image.';$('nprev').style.display='none'}})};
$('np').onclick=function(){if(role!=='admin'){toast('Admin only');return}var t=$('nt').value.trim(),m=$('nmsg').value.trim();if(!t&&!m&&!nimg){toast('Add a title, message or flyer');return}S.posts=S.posts||[];var po={id:'p'+Date.now(),t:t,m:m,cls:$('nc').value,img:nimg,d:today(),h:nowT()};S.posts.unshift(po);save();try{if(localStorage.getItem(KEY).indexOf(po.id)<0)throw 0}catch(x){toast('Posted, but device storage is full')}$('nt').value=$('nmsg').value='';$('nf').value='';nimg='';$('nfn').textContent='No image chosen';$('nprev').style.display='none';renderAll();toast('Notice posted')};
$('nl').onclick=function(e){var b=e.target.closest('[data-pdel]');if(!b||role!=='admin')return;confirm2(b,function(){var i=+b.dataset.pdel;if(S.posts&&S.posts[i]){S.posts.splice(i,1);save();renderAll();toast('Notice removed')}})};
$('sf').onchange=function(){var f=this.files[0];$('sfn').textContent=f?'Selected: '+f.name:'No file chosen'};
$('sc').onclick=function(){subAid=null;$('sp').style.display='none'};
$('sg').onclick=function(){if(role==='admin'||!me){toast('Students only');return}var r=by(me),as=(S.assign||[]).filter(function(x){return x.id===subAid})[0];if(!r||!as)return;var f=$('sf').files[0],n=$('sn').value.trim();if(!f&&!n){toast('Add a file or a note');return}r.tasks=r.tasks.filter(function(t){return t.aid!==as.id});r.tasks.push({aid:as.id,t:as.t,f:f?f.name:'',n:n,d:today(),st:(as.due&&today()>as.due)?'late':'submitted'});act(r,'Submitted '+as.t);subAid=null;$('sp').style.display='none';save();renderAll();toast('Submitted')};
$('ts').onclick=function(){if(role!=='admin'){toast('Admin only');return}var t=$('tt2').value.trim();if(!t){toast('Enter a title');return}S.assign=S.assign||[];S.assign.push({id:'a'+Date.now(),t:t,due:$('td2').value,cls:$('tc').value,n:$('tn2').value.trim()});$('tt2').value=$('td2').value=$('tn2').value='';save();renderAll();toast('Assignment posted')};
$('ad').value=today();
$('am').onclick=function(){if(role!=='admin')return;var r=by(sel),d=$('ad').value;if(!d){toast('Pick a date');return}r.att[d]=$('as').value;act(r,'Marked '+$('as').value+' for '+d);save();renderAll();toast('Recorded')};
$('aadd').onclick=function(){var n=$('an').value.trim();if(!n){toast('Enter a name');return}var id='u'+Date.now();S.roster.push({id:id,name:n,cls:$('ac').value,a:60,i:60,p:60,t:60,s:60,pp:100000,att:{},tx:[],tasks:[],act:[]});$('an').value='';save();fillSel();pick(id);toast('Subject added')};
$('adel').onclick=function(){var b=$('adel');confirm2(b,function(){S.roster=S.roster.filter(function(r){return r.id!==sel});save();sel=S.roster[0]&&S.roster[0].id;fillSel();pick(sel);toast('Deleted')})};
$('pre').onclick=function(e){var n=e.target.dataset&&e.target.dataset.p;if(!n)return;S.weights=PR[n].slice();save();renderAll()};
$('lgn').onclick=function(){var cs='abcdefghjkmnpqrstuvwxyzABCDEFGHJKLMNPQRSTUVWXYZ23456789',a=crypto.getRandomValues(new Uint8Array(10)),o='';for(var j=0;j<10;j++)o+=cs[a[j]%cs.length];$('lp').value=o};
$('lsv').onclick=function(){var r=by(sel),u=$('lu').value.trim().toLowerCase(),p=$('lp').value;if(!/^[a-z0-9._-]{3,30}$/.test(u)){toast('Username: 3-30 chars a-z 0-9 . _ -');return}if(S.roster.some(function(x){return x.id!==r.id&&x.login&&x.login.user===u})){toast('Username taken');return}
if(!p){if(r.login){r.login.user=u;save();paintAdm();toast('Username updated')}else toast('Enter a password');return}if(p.length<6){toast('6+ characters');return}
var s=b64(crypto.getRandomValues(new Uint8Array(16)).buffer);derive(p,s,150000).then(function(h){r.login={user:u,salt:s,iter:150000,hash:h};save();paintAdm();toast('Login saved. Note the password now')})};
$('lrm').onclick=function(){var r=by(sel);if(r&&r.login)confirm2($('lrm'),function(){delete r.login;save();paintAdm()})};
$('sa').onchange=function(e){S.showAll=e.target.checked;save();toast('Saved')};
$('exp').onclick=snapshot;$('bk').onclick=function(){save();dl('s-system-backup.json',JSON.stringify(S),'application/json')};
$('im').onclick=function(){$('imf').click()};$('imf').onchange=function(e){var f=e.target.files[0];if(!f)return;var fr=new FileReader();fr.onload=function(){try{var d=JSON.parse(fr.result);if(!Array.isArray(d.roster))throw 0;S=d;save();fillSel();sel=S.roster[0]&&S.roster[0].id;pick(sel);toast('Backup restored')}catch(x){toast('Invalid backup file')}};fr.readAsText(f)};
$('pw').onclick=function(){modal('change')};
$('rs').onclick=function(){confirm2($('rs'),function(){try{localStorage.removeItem(KEY)}catch(x){}load();fillSel();sel=S.roster[0]&&S.roster[0].id;pick(sel);toast('Reset to embedded data')})};
function tick(){var d=new Date(),o={hour:'2-digit',minute:'2-digit'};$('clk').textContent=d.toLocaleTimeString([],o);var z=function(n){return('0'+n).slice(-2)};$('lsc').innerHTML=z(d.getHours())+'<span class="cl">:</span>'+z(d.getMinutes())+'<small>:'+z(d.getSeconds())+'</small>';var ss=$('lss');if(ss)ss.style.width=(d.getSeconds()+1)/60*100+'%';$('lsd2').textContent=d.toLocaleDateString([],{weekday:'long',month:'long',day:'numeric'}).toUpperCase()}tick();setInterval(tick,1000);
$('lsb').onclick=function(){$('boot').classList.add('o');setTimeout(function(){var g=$('gu');if(g)g.focus()},400)};
stars()}
init();
})();
</script></body></html>
