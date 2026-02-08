[index.html](https://github.com/user-attachments/files/25157620/index.html)
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2685.3">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!doctype html&gt;</p>
<p class="p1">&lt;html lang="en"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;meta charset="utf-8" /&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- iPhone: full-bleed + safe areas --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" /&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;title&gt;Valentine Postcard&lt;/title&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>:root{</p>
<p class="p1"><span class="Apple-converted-space">      </span>/* Beige + earth-tone pink, minimalist */</p>
<p class="p1"><span class="Apple-converted-space">      </span>--bg0: #f6f0e8;</p>
<p class="p1"><span class="Apple-converted-space">      </span>--bg1: #f2e6dc;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--paper: rgba(255,255,255,.62);</p>
<p class="p1"><span class="Apple-converted-space">      </span>--paper2: rgba(255,255,255,.78);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--stroke: rgba(61,47,39,.14);</p>
<p class="p1"><span class="Apple-converted-space">      </span>--stroke2: rgba(61,47,39,.10);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--text: rgba(45,36,31,.92);</p>
<p class="p1"><span class="Apple-converted-space">      </span>--muted: rgba(45,36,31,.62);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--accent: #d48a9a;</p>
<p class="p1"><span class="Apple-converted-space">      </span>--accent2:#c97a8d;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--shadow: 0 24px 70px rgba(52,38,30,.16);</p>
<p class="p1"><span class="Apple-converted-space">      </span>--radius: 28px;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>--mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;</p>
<p class="p1"><span class="Apple-converted-space">      </span>--sans: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>*{ box-sizing:border-box; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>html,body{ height:100%; margin:0; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>body{</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-family: var(--sans);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--text);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(1200px 900px at 18% 10%, rgba(212,138,154,.22), transparent 60%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(900px 700px at 92% 25%, rgba(201,122,141,.16), transparent 55%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(900px 900px at 50% 120%, rgba(255,255,255,.55), transparent 60%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(180deg, var(--bg0), var(--bg1));</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding:</p>
<p class="p1"><span class="Apple-converted-space">        </span>calc(clamp(14px, 3vw, 28px) + env(safe-area-inset-top))</p>
<p class="p1"><span class="Apple-converted-space">        </span>calc(clamp(14px, 3vw, 28px) + env(safe-area-inset-right))</p>
<p class="p1"><span class="Apple-converted-space">        </span>calc(clamp(14px, 3vw, 28px) + env(safe-area-inset-bottom))</p>
<p class="p1"><span class="Apple-converted-space">        </span>calc(clamp(14px, 3vw, 28px) + env(safe-area-inset-left));</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Subtle paper grain (very low) */</p>
<p class="p1"><span class="Apple-converted-space">    </span>body::before{</p>
<p class="p1"><span class="Apple-converted-space">      </span>content:"";</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:fixed;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.08;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(circle at 10% 20%, rgba(61,47,39,.25) 0 1px, transparent 2px) 0 0/18px 18px,</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(circle at 70% 60%, rgba(61,47,39,.18) 0 1px, transparent 2px) 0 0/22px 22px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>mix-blend-mode:multiply;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.stage{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(820px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>aspect-ratio: 16 / 10;</p>
<p class="p1"><span class="Apple-converted-space">      </span>min-height: 420px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>max-height: 80vh;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: var(--radius);</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: var(--shadow);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: linear-gradient(180deg, var(--paper2), var(--paper));</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>cursor: pointer;</p>
<p class="p1"><span class="Apple-converted-space">      </span>user-select:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>-webkit-user-select:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>touch-action: manipulation;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.topHint{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: 18px; right: 18px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>top: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:space-between;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>z-index: 20;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 10px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.pill{</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:inline-flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap:10px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 10px 12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.64);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 13px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing:.2px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>backdrop-filter: blur(10px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>-webkit-backdrop-filter: blur(10px);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.dot{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:8px;height:8px;border-radius:999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: var(--accent2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 0 0 5px rgba(212,138,154,.20);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.stepCounter{ font-family: var(--mono); opacity:.85; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.title{</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: clamp(22px, 2.5vw, 34px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 620;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing:-.02em;</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin:0;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.subtitle{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin: 10px 0 0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>line-height:1.45;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: clamp(14px, 1.7vw, 16px);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.small{ font-size: 13px; color: var(--muted); letter-spacing: .2px; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.panel{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(620px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 26px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.66);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: clamp(18px, 4vw, 28px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 50px rgba(52,38,30,.10);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.panel::before{</p>
<p class="p1"><span class="Apple-converted-space">      </span>content:"";</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:-2px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(900px 320px at 12% 0%, rgba(212,138,154,.20), transparent 55%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(900px 320px at 88% 100%, rgba(201,122,141,.12), transparent 55%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.9;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.panelInner{ position:relative; z-index:1; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Views + motion */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.view{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: clamp(18px, 4vw, 42px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translateY(8px) scale(.99);</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: opacity 360ms ease, transform 360ms ease;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.view.active{</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:1;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translateY(0) scale(1);</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:auto;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Envelope */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.envelopeWrap{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(540px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>aspect-ratio: 16 / 10;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 28px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.68);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 60px rgba(52,38,30,.12);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.envelope{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width: min(420px, 90%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>aspect-ratio: 16 / 10;</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 22px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.62);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 16px 40px rgba(52,38,30,.12);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.env-lines{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute; inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.60;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(135deg, transparent 49%, rgba(61,47,39,.14) 50%, transparent 51%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(225deg, transparent 49%, rgba(61,47,39,.14) 50%, transparent 51%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(0deg, rgba(61,47,39,.04), rgba(61,47,39,.00));</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.seal{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left:50%; top:56%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translate(-50%,-50%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>width: 54px; height: 54px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(circle at 30% 20%, rgba(255,255,255,.80), rgba(255,255,255,.18) 55%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(180deg, rgba(212,138,154,.95), rgba(201,122,141,.92));</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 16px 36px rgba(201,122,141,.22);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid rgba(255,255,255,.62);</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.seal svg{ width:22px;height:22px; opacity:.95; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>.env-caption{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>bottom: 16px; left: 16px; right: 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:flex-end;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:space-between;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 10px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(45,36,31,.72);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 13px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.addr{</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>flex-direction:column;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap:4px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 10px 12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.65);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>backdrop-filter: blur(10px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>-webkit-backdrop-filter: blur(10px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>min-width: 170px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.addr b{ font-weight: 650; letter-spacing: .2px; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Clean grid */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.gridPanel{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(680px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 28px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.64);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: clamp(18px, 4vw, 26px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 50px rgba(52,38,30,.10);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.grid{</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>grid-template-columns: repeat(6, 1fr);</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 10px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.cell{</p>
<p class="p1"><span class="Apple-converted-space">      </span>aspect-ratio: 1 / 1;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.68);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.cell::after{</p>
<p class="p1"><span class="Apple-converted-space">      </span>content:"";</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute; inset: -20%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: radial-gradient(circle at 30% 30%, rgba(212,138,154,.18), transparent 58%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.9;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: rotate(12deg);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.gridMeta{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-top: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:space-between;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:flex-end;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 13px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Quote */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.quote{</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: clamp(22px, 2.8vw, 38px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>line-height: 1.08;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing: -0.02em;</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin: 0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 640;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.quoteMark{</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-family: var(--mono);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(45,36,31,.55);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-top: 14px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Apple-like popup modal + spring-ish pop */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modalMask{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(246,240,232,.60);</p>
<p class="p1"><span class="Apple-converted-space">      </span>backdrop-filter: blur(12px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>-webkit-backdrop-filter: blur(12px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 18px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modal{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width: min(420px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 28px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.78);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 30px 90px rgba(52,38,30,.16);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>animation: pop 520ms cubic-bezier(.2, 1.3, .25, 1) both;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>@keyframes pop{</p>
<p class="p1"><span class="Apple-converted-space">      </span>0%{ transform: translateY(10px) scale(.96); opacity:0; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>100%{ transform: translateY(0) scale(1); opacity:1; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modalHeader{</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 16px 18px 10px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:space-between;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-bottom: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.traffic{ display:flex; gap:8px; opacity:.65; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>.traffic span{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:11px;height:11px;border-radius:99px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(61,47,39,.18);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border:1px solid rgba(61,47,39,.12);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modalBody{ padding: 18px; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modalBody h3{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 650;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing: -.02em;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 16px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.modalBody p{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin: 10px 0 0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>line-height:1.45;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 14px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.actions{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-top: 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 10px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:flex-end;</p>
<p class="p1"><span class="Apple-converted-space">      </span>flex-wrap: wrap;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.btn{</p>
<p class="p1"><span class="Apple-converted-space">      </span>appearance:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.68);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--text);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 10px 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 620;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing: .2px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:inline-flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 10px 30px rgba(52,38,30,.10);</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: transform 160ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.btn:active{ transform: scale(.98); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>.btn.primary{</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-color: rgba(212,138,154,.55);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: linear-gradient(180deg, rgba(212,138,154,.95), rgba(201,122,141,.92));</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(255,255,255,.95);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 16px 40px rgba(201,122,141,.20);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Movable symbol */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.symbolStage{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(680px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 28px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.64);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>height: min(420px, 55vh);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 60px rgba(52,38,30,.12);</p>
<p class="p1"><span class="Apple-converted-space">      </span>cursor: default;</p>
<p class="p1"><span class="Apple-converted-space">      </span>touch-action: none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.symbolHint{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: 16px; top: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 10px 12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.74);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 13px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>z-index:2;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.softGrid{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute; inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background-image:</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(rgba(61,47,39,.08) 1px, transparent 1px),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(90deg, rgba(61,47,39,.08) 1px, transparent 1px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background-size: 52px 52px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.55;</p>
<p class="p1"><span class="Apple-converted-space">      </span>mask-image: radial-gradient(circle at 40% 30%, black 22%, transparent 72%);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.symbol{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width: 64px; height: 64px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 22px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: 50%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>top: 56%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translate(-50%,-50%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(circle at 30% 20%, rgba(255,255,255,.90), rgba(255,255,255,.38) 55%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(180deg, rgba(255,255,255,.74), rgba(255,255,255,.52));</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 50px rgba(52,38,30,.14);</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>cursor: grab;</p>
<p class="p1"><span class="Apple-converted-space">      </span>touch-action: none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: transform 160ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.symbol:active{ cursor: grabbing; transform: translate(-50%,-50%) scale(.99); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>.symbol svg{ width: 22px; height: 22px; opacity: .88; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Heart message */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.bigHeart{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width: 130px; height: 130px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 36px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:</p>
<p class="p1"><span class="Apple-converted-space">        </span>radial-gradient(circle at 30% 20%, rgba(255,255,255,.88), rgba(255,255,255,.30) 60%),</p>
<p class="p1"><span class="Apple-converted-space">        </span>linear-gradient(180deg, rgba(212,138,154,.95), rgba(201,122,141,.92));</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid rgba(255,255,255,.65);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 26px 70px rgba(201,122,141,.22);</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:grid;</p>
<p class="p1"><span class="Apple-converted-space">      </span>place-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-bottom: 18px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: rotate(-2deg);</p>
<p class="p1"><span class="Apple-converted-space">      </span>animation: floaty 3.6s ease-in-out infinite;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.bigHeart svg{ width: 56px; height: 56px; opacity:.95; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>@keyframes floaty{</p>
<p class="p1"><span class="Apple-converted-space">      </span>0%,100%{ transform: translateY(0) rotate(-2deg); }</p>
<p class="p1"><span class="Apple-converted-space">      </span>50%{ transform: translateY(-10px) rotate(-2deg); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* YES/NO finale */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.choiceStage{</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:min(680px, 100%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 28px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.66);</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:relative;</p>
<p class="p1"><span class="Apple-converted-space">      </span>height: min(420px, 55vh);</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 18px 60px rgba(52,38,30,.12);</p>
<p class="p1"><span class="Apple-converted-space">      </span>cursor: default;</p>
<p class="p1"><span class="Apple-converted-space">      </span>touch-action: none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.choiceTop{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: 16px; right:16px; top: 14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:space-between;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>gap: 10px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>z-index:3;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.choicePill{</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 10px 12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.78);</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke2);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--muted);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 13px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.choices{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.yesBtn, .noBtn{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius: 999px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border: 1px solid var(--stroke);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 650;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing: .2px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>box-shadow: 0 14px 45px rgba(52,38,30,.12);</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:inline-flex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>align-items:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>justify-content:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>user-select:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>-webkit-user-select:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>touch-action:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>will-change: transform, left, top;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.yesBtn{</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: linear-gradient(180deg, rgba(212,138,154,.95), rgba(201,122,141,.92));</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(255,255,255,.95);</p>
<p class="p1"><span class="Apple-converted-space">      </span>min-width: 120px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>height: 46px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 0 18px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: 50%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>top: 58%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translate(-50%,-50%) scale(1);</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: transform 220ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.noBtn{</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: rgba(255,255,255,.82);</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: var(--text);</p>
<p class="p1"><span class="Apple-converted-space">      </span>min-width: 110px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>height: 46px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 0 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left: calc(50% + 160px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>top: 58%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translate(-50%,-50%);</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: left 180ms ease, top 180ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.fillOverlay{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: linear-gradient(180deg, rgba(212,138,154,.95), rgba(201,122,141,.92));</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: opacity 260ms ease;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>z-index:1;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* FINAL: Fullscreen ending with photo */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalWrap{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>overflow:hidden;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: var(--bg0);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalImg{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>width:100%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>height:100%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>object-fit:cover;</p>
<p class="p1"><span class="Apple-converted-space">      </span>/* iPhone-friendly crop bias: keep subject higher */</p>
<p class="p1"><span class="Apple-converted-space">      </span>object-position: center 30%;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: scale(1.06);</p>
<p class="p1"><span class="Apple-converted-space">      </span>filter: saturate(1.03) contrast(1.02);</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: transform 900ms cubic-bezier(.2, .9, .2, 1);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.view.active .finalImg{</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: scale(1);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalGradient{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>background: linear-gradient(</p>
<p class="p1"><span class="Apple-converted-space">        </span>180deg,</p>
<p class="p1"><span class="Apple-converted-space">        </span>rgba(246,240,232,0) 40%,</p>
<p class="p1"><span class="Apple-converted-space">        </span>rgba(246,240,232,.55) 70%,</p>
<p class="p1"><span class="Apple-converted-space">        </span>rgba(246,240,232,.92) 100%</p>
<p class="p1"><span class="Apple-converted-space">      </span>);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: opacity 700ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.view.active .finalGradient{</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:1;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalText{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>left:0; right:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>bottom: calc(clamp(28px, 6vh, 60px) + env(safe-area-inset-bottom));</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding: 0 26px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>text-align:center;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translateY(10px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transition: transform 650ms ease, opacity 650ms ease;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.view.active .finalText{</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translateY(0);</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:1;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalTitle{</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: clamp(22px, 5vw, 32px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-weight: 620;</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing:-0.02em;</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(59,48,40,.94);</p>
<p class="p1"><span class="Apple-converted-space">      </span>text-shadow: 0 10px 30px rgba(52,38,30,.10);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalBy{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-top:12px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size:14px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(59,48,40,.62);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.finalReplay{</p>
<p class="p1"><span class="Apple-converted-space">      </span>margin-top:18px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size:13px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>color: rgba(59,48,40,.45);</p>
<p class="p1"><span class="Apple-converted-space">      </span>letter-spacing:.2px;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>/* Minimal floating hearts (very subtle) */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.hearts{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>inset:0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>pointer-events:none;</p>
<p class="p1"><span class="Apple-converted-space">      </span>z-index:2;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>.heartParticle{</p>
<p class="p1"><span class="Apple-converted-space">      </span>position:absolute;</p>
<p class="p1"><span class="Apple-converted-space">      </span>font-size: 16px;</p>
<p class="p1"><span class="Apple-converted-space">      </span>opacity:.0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>transform: translateY(10px) scale(.9);</p>
<p class="p1"><span class="Apple-converted-space">      </span>filter: blur(.15px);</p>
<p class="p1"><span class="Apple-converted-space">      </span>animation: heartFloat 3.8s ease-in-out forwards;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>@keyframes heartFloat{</p>
<p class="p1"><span class="Apple-converted-space">      </span>0% <span class="Apple-converted-space">  </span>{ opacity:0; transform: translateY(18px) scale(.92); }</p>
<p class="p1"><span class="Apple-converted-space">      </span>12%<span class="Apple-converted-space">  </span>{ opacity:.22; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>55%<span class="Apple-converted-space">  </span>{ opacity:.18; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>100% { opacity:0; transform: translateY(-90px) scale(1.06); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>@media (max-width: 520px){</p>
<p class="p1"><span class="Apple-converted-space">      </span>.grid{ grid-template-columns: repeat(4, 1fr); }</p>
<p class="p1"><span class="Apple-converted-space">      </span>.stage{ aspect-ratio: 10 / 14; min-height: 540px; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>.symbolStage, .choiceStage{ height: min(460px, 58vh); }</p>
<p class="p1"><span class="Apple-converted-space">      </span>.noBtn{ left: calc(50% + 120px); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;body&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div class="stage" id="stage" role="button" aria-label="Valentine postcard. Tap to continue." tabindex="0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="topHint"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="pill"&gt;&lt;span class="dot"&gt;&lt;/span&gt;&lt;span id="tapHint"&gt;tap anywhere&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="pill stepCounter"&gt;&lt;span id="stepText"&gt;01/10&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 0: Envelope --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view active" data-step="0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="envelopeWrap"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="envelope" aria-hidden="true"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="env-lines"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="seal"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg viewBox="0 0 24 24" fill="none" aria-hidden="true"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;path d="M12 21s-7-4.4-7-10.2C5 8 6.9 6 9.4 6c1.3 0 2.4.6 3.1 1.6C13.2 6.6 14.3 6 15.6 6 18.1 6 20 8 20 10.8 20 16.6 12 21 12 21Z"</p>
<p class="p1"><span class="Apple-converted-space">                </span>stroke="rgba(255,255,255,.95)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="env-caption"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="addr"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="small"&gt;To&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;b&gt;Kerel&lt;/b&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="addr" style="text-align:right"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="small"&gt;From&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;b&gt;Chan&lt;/b&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 1: Clean grid --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="gridPanel"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="grid" aria-hidden="true"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;&lt;div class="cell"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="gridMeta"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;span class="small"&gt;clean grid&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;span class="small"&gt;click&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 2: Quote --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="panel"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="panelInner"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="quote"&gt;“Clean, right?”&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="quoteMark"&gt;— inside&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 3: Apple-like popup --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="modalMask" aria-hidden="false"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="modal" role="dialog" aria-label="Popup"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="modalHeader"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="traffic" aria-hidden="true"&gt;&lt;span&gt;&lt;/span&gt;&lt;span&gt;&lt;/span&gt;&lt;span&gt;&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="small"&gt;System&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="modalBody"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h3&gt;One thing…&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p&gt;Tap the button. Very clean.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="actions"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button class="btn" id="btnLater" type="button"&gt;Not now&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button class="btn primary" id="btnOkay" type="button"&gt;Okay&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 4 --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="panel"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="panelInner"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h1 class="title"&gt;So satisfied, right?&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="subtitle"&gt;Minimal. Clean. Just… correct.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 5: Movable symbol --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="symbolStage" id="symbolStage" aria-label="Drag the symbol"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="softGrid" aria-hidden="true"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="symbolHint"&gt;drag the symbol&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="symbol" id="symbol" role="button" aria-label="Movable symbol"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg viewBox="0 0 24 24" fill="none" aria-hidden="true"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;path d="M12 3v18M3 12h18" stroke="rgba(45,36,31,.88)" stroke-width="2" stroke-linecap="round"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 6 --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="panel"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="panelInner"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h1 class="title"&gt;Satisfied, right?&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="subtitle"&gt;Okay… one last thing.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 7 --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="7"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="panel"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="panelInner" style="display:grid; place-items:center; text-align:center;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="bigHeart" aria-hidden="true"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg viewBox="0 0 24 24" fill="none"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;path d="M12 21s-7-4.4-7-10.2C5 8 6.9 6 9.4 6c1.3 0 2.4.6 3.1 1.6C13.2 6.6 14.3 6 15.6 6 18.1 6 20 8 20 10.8 20 16.6 12 21 12 21Z"</p>
<p class="p1"><span class="Apple-converted-space">                </span>stroke="rgba(255,255,255,.95)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h1 class="title"&gt;Nothing is as satisfied as me.&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="subtitle"&gt;Be my Valentine’s.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 8: YES/NO --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="choiceStage" id="choiceStage" aria-label="Yes or no"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="fillOverlay" id="fillOverlay" aria-hidden="true"&gt;&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="choiceTop"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="choicePill"&gt;Try to press “no”.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="choicePill" id="growthPill"&gt;yes: 1.0×&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="choices" id="choices"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="yesBtn" id="yesBtn" role="button" aria-label="Yes"&gt;YES&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="noBtn" id="noBtn" role="button" aria-label="No"&gt;NO&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- STEP 9: FINAL PHOTO ENDING --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="view" data-step="9"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="finalWrap"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;!-- Put your photo in the same folder as this HTML named: valentine-final.jpg --&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;img class="finalImg" src="valentine-final.jpg" alt="Valentine photo" /&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="finalGradient" aria-hidden="true"&gt;&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;!-- subtle hearts container --&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="hearts" id="hearts" aria-hidden="true"&gt;&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="finalText"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h1 class="finalTitle"&gt;Congratulations, you have unlocked yourself a Valentine’s ❤️!&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="finalBy"&gt;— Chan&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="finalReplay"&gt;tap anywhere to replay&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;script&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>(function(){</p>
<p class="p1"><span class="Apple-converted-space">      </span>const stage = document.getElementById('stage');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const views = [...stage.querySelectorAll('.view')];</p>
<p class="p1"><span class="Apple-converted-space">      </span>const stepText = document.getElementById('stepText');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const tapHint = document.getElementById('tapHint');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>const btnOkay = document.getElementById('btnOkay');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const btnLater = document.getElementById('btnLater');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Drag symbol</p>
<p class="p1"><span class="Apple-converted-space">      </span>const symbolStage = document.getElementById('symbolStage');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const symbol = document.getElementById('symbol');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// YES/NO</p>
<p class="p1"><span class="Apple-converted-space">      </span>const choiceStage = document.getElementById('choiceStage');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const yesBtn = document.getElementById('yesBtn');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const noBtn = document.getElementById('noBtn');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const growthPill = document.getElementById('growthPill');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const fillOverlay = document.getElementById('fillOverlay');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Final hearts</p>
<p class="p1"><span class="Apple-converted-space">      </span>const heartsLayer = document.getElementById('hearts');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>let step = 0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>const last = 9;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function setStep(n){</p>
<p class="p1"><span class="Apple-converted-space">        </span>step = n;</p>
<p class="p1"><span class="Apple-converted-space">        </span>views.forEach(v =&gt; v.classList.toggle('active', Number(v.dataset.step) === step));</p>
<p class="p1"><span class="Apple-converted-space">        </span>stepText.textContent = String(step+1).padStart(2,'0') + '/10';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 5){</p>
<p class="p1"><span class="Apple-converted-space">          </span>tapHint.textContent = 'drag, then tap outside';</p>
<p class="p1"><span class="Apple-converted-space">        </span>} else if(step === 8){</p>
<p class="p1"><span class="Apple-converted-space">          </span>tapHint.textContent = 'try "no"';</p>
<p class="p1"><span class="Apple-converted-space">        </span>} else if(step === 9){</p>
<p class="p1"><span class="Apple-converted-space">          </span>tapHint.textContent = 'replay';</p>
<p class="p1"><span class="Apple-converted-space">          </span>spawnHearts(); // upgrade: subtle hearts on entry</p>
<p class="p1"><span class="Apple-converted-space">        </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">          </span>tapHint.textContent = 'tap anywhere';</p>
<p class="p1"><span class="Apple-converted-space">          </span>clearHearts();</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function advance(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>// Step 3 requires pressing modal button</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 3) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>// Step 5 interactive</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 5) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>// Step 8 interactive</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 8) return;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step &gt;= last) setStep(0);</p>
<p class="p1"><span class="Apple-converted-space">        </span>else setStep(step + 1);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Tap/click to advance</p>
<p class="p1"><span class="Apple-converted-space">      </span>stage.addEventListener('click', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(e.target.closest('.modal')) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 5 &amp;&amp; e.target.closest('#symbolStage')) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 8 &amp;&amp; e.target.closest('#choiceStage')) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>advance();</p>
<p class="p1"><span class="Apple-converted-space">      </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Keyboard</p>
<p class="p1"><span class="Apple-converted-space">      </span>stage.addEventListener('keydown', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(e.key === 'Enter' || e.key === ' '){</p>
<p class="p1"><span class="Apple-converted-space">          </span>e.preventDefault();</p>
<p class="p1"><span class="Apple-converted-space">          </span>advance();</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Modal buttons advance to step 4</p>
<p class="p1"><span class="Apple-converted-space">      </span>function closeModalAndAdvance(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step === 3) setStep(4);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>btnOkay.addEventListener('click', (e) =&gt; { e.stopPropagation(); closeModalAndAdvance(); });</p>
<p class="p1"><span class="Apple-converted-space">      </span>btnLater.addEventListener('click', (e) =&gt; { e.stopPropagation(); closeModalAndAdvance(); });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>/* =========================</p>
<p class="p1"><span class="Apple-converted-space">         </span>STEP 5: Movable symbol</p>
<p class="p1"><span class="Apple-converted-space">      </span>========================== */</p>
<p class="p1"><span class="Apple-converted-space">      </span>let dragging = false;</p>
<p class="p1"><span class="Apple-converted-space">      </span>let offsetX = 0, offsetY = 0;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function clamp(v, min, max){ return Math.max(min, Math.min(max, v)); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function pointerDown(ev){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 5) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>dragging = true;</p>
<p class="p1"><span class="Apple-converted-space">        </span>symbol.setPointerCapture(ev.pointerId);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const rect = symbol.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>offsetX = ev.clientX - rect.left;</p>
<p class="p1"><span class="Apple-converted-space">        </span>offsetY = ev.clientY - rect.top;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function pointerMove(ev){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!dragging || step !== 5) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const host = symbolStage.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const s = symbol.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const w = s.width, h = s.height;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const x = clamp(ev.clientX - host.left - offsetX, 10, host.width - w - 10);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const y = clamp(ev.clientY - host.top - offsetY, 10, host.height - h - 10);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>symbol.style.left = x + 'px';</p>
<p class="p1"><span class="Apple-converted-space">        </span>symbol.style.top = y + 'px';</p>
<p class="p1"><span class="Apple-converted-space">        </span>symbol.style.transform = 'translate(0,0)';</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function pointerUp(ev){</p>
<p class="p1"><span class="Apple-converted-space">        </span>dragging = false;</p>
<p class="p1"><span class="Apple-converted-space">        </span>try { symbol.releasePointerCapture(ev.pointerId); } catch {}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>symbol.addEventListener('pointerdown', (e)=&gt;{ e.stopPropagation(); pointerDown(e); });</p>
<p class="p1"><span class="Apple-converted-space">      </span>symbol.addEventListener('pointermove', (e)=&gt;{ e.stopPropagation(); pointerMove(e); });</p>
<p class="p1"><span class="Apple-converted-space">      </span>symbol.addEventListener('pointerup', <span class="Apple-converted-space">  </span>(e)=&gt;{ e.stopPropagation(); pointerUp(e); });</p>
<p class="p1"><span class="Apple-converted-space">      </span>symbol.addEventListener('pointercancel',(e)=&gt;{ e.stopPropagation(); pointerUp(e); });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Step 5: tap outside symbolStage -&gt; go to step 6</p>
<p class="p1"><span class="Apple-converted-space">      </span>document.addEventListener('click', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 5) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!e.target.closest('#symbolStage')){</p>
<p class="p1"><span class="Apple-converted-space">          </span>setStep(6);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}, { capture:true });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>/* =========================</p>
<p class="p1"><span class="Apple-converted-space">         </span>STEP 8: YES/NO</p>
<p class="p1"><span class="Apple-converted-space">         </span>- NO dodges away from pointer</p>
<p class="p1"><span class="Apple-converted-space">         </span>- YES grows on every “no attempt” (and taps)</p>
<p class="p1"><span class="Apple-converted-space">         </span>- When YES is huge: go to final photo page</p>
<p class="p1"><span class="Apple-converted-space">      </span>========================== */</p>
<p class="p1"><span class="Apple-converted-space">      </span>let yesScale = 1;</p>
<p class="p1"><span class="Apple-converted-space">      </span>const YES_GROWTH = 1.18;</p>
<p class="p1"><span class="Apple-converted-space">      </span>const SCALE_TO_WIN = 7.0;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function setYesScale(s){</p>
<p class="p1"><span class="Apple-converted-space">        </span>yesScale = s;</p>
<p class="p1"><span class="Apple-converted-space">        </span>yesBtn.style.transform = `translate(-50%,-50%) scale(${yesScale})`;</p>
<p class="p1"><span class="Apple-converted-space">        </span>growthPill.textContent = `yes: ${yesScale.toFixed(1)}×`;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>if(yesScale &gt;= 4.0){</p>
<p class="p1"><span class="Apple-converted-space">          </span>const t = Math.min(1, (yesScale - 4) / 3);</p>
<p class="p1"><span class="Apple-converted-space">          </span>fillOverlay.style.opacity = String(t);</p>
<p class="p1"><span class="Apple-converted-space">        </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">          </span>fillOverlay.style.opacity = "0";</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>if(yesScale &gt;= SCALE_TO_WIN){</p>
<p class="p1"><span class="Apple-converted-space">          </span>setTimeout(() =&gt; setStep(9), 220);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function rand(min, max){ return Math.random() * (max - min) + min; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function placeNoAt(x, y){</p>
<p class="p1"><span class="Apple-converted-space">        </span>// x,y are in choiceStage coordinates</p>
<p class="p1"><span class="Apple-converted-space">        </span>const host = choiceStage.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const n = noBtn.getBoundingClientRect();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const pad = 18;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const maxX = host.width - n.width - pad;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const maxY = host.height - n.height - pad;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const cx = clamp(x - n.width/2, pad, maxX) + n.width/2;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const cy = clamp(y - n.height/2, pad + 58, maxY) + n.height/2;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>noBtn.style.left = cx + 'px';</p>
<p class="p1"><span class="Apple-converted-space">        </span>noBtn.style.top<span class="Apple-converted-space">  </span>= cy + 'px';</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function moveNoAwayFrom(pointerClientX, pointerClientY){</p>
<p class="p1"><span class="Apple-converted-space">        </span>const host = choiceStage.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const px = pointerClientX - host.left;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const py = pointerClientY - host.top;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// Push direction from pointer -&gt; away vector</p>
<p class="p1"><span class="Apple-converted-space">        </span>const noRect = noBtn.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const nx = (noRect.left - host.left) + noRect.width/2;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const ny = (noRect.top<span class="Apple-converted-space">  </span>- host.top)<span class="Apple-converted-space">  </span>+ noRect.height/2;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>let vx = nx - px;</p>
<p class="p1"><span class="Apple-converted-space">        </span>let vy = ny - py;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const mag = Math.hypot(vx, vy) || 1;</p>
<p class="p1"><span class="Apple-converted-space">        </span>vx /= mag; vy /= mag;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// Make it jump away + some randomness</p>
<p class="p1"><span class="Apple-converted-space">        </span>const jump = rand(110, 170);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const rx = rand(-40, 40);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const ry = rand(-28, 28);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>placeNoAt(nx + vx*jump + rx, ny + vy*jump + ry);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function noAttempt(e){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 8) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>e.preventDefault();</p>
<p class="p1"><span class="Apple-converted-space">        </span>e.stopPropagation();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const p = e.touches ? e.touches[0] : e;</p>
<p class="p1"><span class="Apple-converted-space">        </span>moveNoAwayFrom(p.clientX, p.clientY);</p>
<p class="p1"><span class="Apple-converted-space">        </span>setYesScale(yesScale * YES_GROWTH);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function resetChoice(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>yesScale = 1;</p>
<p class="p1"><span class="Apple-converted-space">        </span>setYesScale(1);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// reset NO near-right</p>
<p class="p1"><span class="Apple-converted-space">        </span>noBtn.style.left = 'calc(50% + 160px)';</p>
<p class="p1"><span class="Apple-converted-space">        </span>noBtn.style.top = '58%';</p>
<p class="p1"><span class="Apple-converted-space">        </span>noBtn.style.transform = 'translate(-50%,-50%)';</p>
<p class="p1"><span class="Apple-converted-space">        </span>fillOverlay.style.opacity = "0";</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// NO dodges when pointer comes near</p>
<p class="p1"><span class="Apple-converted-space">      </span>function onPointerNearNo(e){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 8) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const p = e.touches ? e.touches[0] : e;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const host = choiceStage.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const px = p.clientX - host.left;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const py = p.clientY - host.top;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const n = noBtn.getBoundingClientRect();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const nx = (n.left - host.left) + n.width/2;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const ny = (n.top<span class="Apple-converted-space">  </span>- host.top)<span class="Apple-converted-space">  </span>+ n.height/2;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const d = Math.hypot(px - nx, py - ny);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// If within reach, dodge</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(d &lt; 120){</p>
<p class="p1"><span class="Apple-converted-space">          </span>moveNoAwayFrom(p.clientX, p.clientY);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>noBtn.addEventListener('pointerdown', noAttempt);</p>
<p class="p1"><span class="Apple-converted-space">      </span>noBtn.addEventListener('click', noAttempt);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Detect “near” on move (iPhone-friendly)</p>
<p class="p1"><span class="Apple-converted-space">      </span>choiceStage.addEventListener('pointermove', onPointerNearNo, { passive:true });</p>
<p class="p1"><span class="Apple-converted-space">      </span>choiceStage.addEventListener('touchmove', onPointerNearNo, { passive:true });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Any tap inside choice stage (not YES) grows YES a little</p>
<p class="p1"><span class="Apple-converted-space">      </span>choiceStage.addEventListener('pointerdown', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 8) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(e.target.closest('#yesBtn')) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(e.target.closest('#noBtn')) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>setYesScale(yesScale * 1.06);</p>
<p class="p1"><span class="Apple-converted-space">      </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// YES ends immediately (also bumps to win)</p>
<p class="p1"><span class="Apple-converted-space">      </span>yesBtn.addEventListener('pointerdown', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 8) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>e.stopPropagation();</p>
<p class="p1"><span class="Apple-converted-space">        </span>setYesScale(Math.max(yesScale, SCALE_TO_WIN));</p>
<p class="p1"><span class="Apple-converted-space">      </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>/* =========================</p>
<p class="p1"><span class="Apple-converted-space">         </span>FINAL STEP: subtle hearts</p>
<p class="p1"><span class="Apple-converted-space">      </span>========================== */</p>
<p class="p1"><span class="Apple-converted-space">      </span>let heartTimer = null;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function clearHearts(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!heartsLayer) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(heartTimer) { clearInterval(heartTimer); heartTimer = null; }</p>
<p class="p1"><span class="Apple-converted-space">        </span>heartsLayer.innerHTML = "";</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function spawnOneHeart(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 9 || !heartsLayer) return;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>const h = document.createElement('div');</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.className = 'heartParticle';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.textContent = '❤';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// soft earth pink via CSS filter-ish approach (emoji)</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.opacity = '0';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.left = (Math.random() * 88 + 6) + '%';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.top = (Math.random() * 25 + 55) + '%';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.fontSize = (Math.random() * 8 + 14) + 'px';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.animationDuration = (Math.random() * 1.2 + 3.2) + 's';</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.animationDelay = (Math.random() * 0.2) + 's';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// slight tint by shadow (subtle)</p>
<p class="p1"><span class="Apple-converted-space">        </span>h.style.textShadow = '0 10px 30px rgba(201,122,141,.22)';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>heartsLayer.appendChild(h);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>// cleanup after animation</p>
<p class="p1"><span class="Apple-converted-space">        </span>setTimeout(() =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">          </span>if(h.parentNode) h.parentNode.removeChild(h);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}, 4500);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>function spawnHearts(){</p>
<p class="p1"><span class="Apple-converted-space">        </span>clearHearts();</p>
<p class="p1"><span class="Apple-converted-space">        </span>// initial burst</p>
<p class="p1"><span class="Apple-converted-space">        </span>for(let i=0;i&lt;6;i++) setTimeout(spawnOneHeart, i*240);</p>
<p class="p1"><span class="Apple-converted-space">        </span>// gentle ongoing</p>
<p class="p1"><span class="Apple-converted-space">        </span>heartTimer = setInterval(() =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">          </span>if(step !== 9) return;</p>
<p class="p1"><span class="Apple-converted-space">          </span>spawnOneHeart();</p>
<p class="p1"><span class="Apple-converted-space">        </span>}, 720);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>/* =========================</p>
<p class="p1"><span class="Apple-converted-space">         </span>Step entry hooks</p>
<p class="p1"><span class="Apple-converted-space">      </span>========================== */</p>
<p class="p1"><span class="Apple-converted-space">      </span>const origSetStep = setStep;</p>
<p class="p1"><span class="Apple-converted-space">      </span>setStep = function(n){</p>
<p class="p1"><span class="Apple-converted-space">        </span>origSetStep(n);</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(n === 8) resetChoice();</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(n !== 9) clearHearts();</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// INIT</p>
<p class="p1"><span class="Apple-converted-space">      </span>setStep(0);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Allow step 9 tap anywhere to replay (already handled by advance() restarting from last)</p>
<p class="p1"><span class="Apple-converted-space">      </span>// but we want it to restart immediately:</p>
<p class="p1"><span class="Apple-converted-space">      </span>stage.addEventListener('click', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(step !== 9) return;</p>
<p class="p1"><span class="Apple-converted-space">        </span>// any click while on final restarts</p>
<p class="p1"><span class="Apple-converted-space">        </span>setStep(0);</p>
<p class="p1"><span class="Apple-converted-space">      </span>}, { capture:true });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>})();</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/script&gt;</p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
