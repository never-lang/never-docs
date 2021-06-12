---
title: Never Grammar Railroad Diagram 
---

# Never Grammar Railroad Diagram

Thanks to help from the community (especially [Mingodad](https://github.com/mingodad)) Never got beautiful grammar railroad diagrams generated using [Railroad Diagram Generator](https://www.bottlecaps.de/rr/ui).

<div>
    <style type="text/css">
    ::-moz-selection
    {
      color: #FFFCF0;
      background: #0F0C00;
    }
    ::selection
    {
      color: #FFFCF0;
      background: #0F0C00;
    }
    .ebnf a, .grammar a
    {
      text-decoration: none;
    }
    .ebnf a:hover, .grammar a:hover
    {
      color: #050400;
      text-decoration: underline;
    }
    .signature
    {
      color: #806600;
      font-size: 11px;
      text-align: right;
    }
    a.button, #tabs li a
    {
      padding: 0.25em 0.5em;
      border: 1px solid #806600;
      background: #F1E8C6;
      color: #806600;
      text-decoration: none;
      font-weight: bold;
    }
    a.button:hover, #tabs li a:hover
    {
      color: #050400;
      background: #FFF6D1;
      border-color: #050400;
    }
    #tabs
    {
      padding: 3px 10px;
      margin-left: 0;
      margin-top: 58px;
      border-bottom: 1px solid #0F0C00;
    }
    #tabs li
    {
      list-style: none;
      margin-left: 5px;
      display: inline;
    }
    #tabs li a
    {
      border-bottom: 1px solid #0F0C00;
    }
    #tabs li a.active
    {
      color: #0F0C00;
      background: #FFFCF0;
      border-color: #0F0C00;
      border-bottom: 1px solid #FFFCF0;
      outline: none;
    }
    #divs div
    {
      display: none;
      overflow:auto;
    }
    #divs div.active
    {
      display: block;
    }
    #text
    {
      border-color: #806600;
      background: #FFFEFA;
      color: #050400;
    }
    .small
    {
      vertical-align: top;
      text-align: right;
      font-size: 9px;
      font-weight: normal;
      line-height: 120%;
    }
    td.small
    {
      padding-top: 0px;
    }
    .hidden
    {
      visibility: hidden;
    }
    td:hover .hidden
    {
      visibility: visible;
    }
    div.download
    {
      display: none;
      background: #FFFCF0;
      position: absolute;
      right: 34px;
      top: 94px;
      padding: 10px;
      border: 1px dotted #0F0C00;
    }
    #divs div.ebnf, .ebnf code
    {
      display: block;
      padding: 10px;
      background: #FFF6D1;
      width: 992px;
    }
    #divs div.grammar
    {
      display: block;
      padding-left: 16px;
      padding-top: 2px;
      padding-bottom: 2px;
      background: #FFF6D1;
    }
    pre
    {
      margin: 0px;
    }
    .ebnf div
    {
      padding-left: 13ch;
      text-indent: -13ch;
    }
    .ebnf code, .grammar code, textarea, pre
    {
      font:12px SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;
    }
    tr.option-line td:first-child
    {
      text-align: right
    }
    tr.option-text td
    {
      padding-bottom: 10px
    }
    table.palette
    {
      border-top: 1px solid #050400;
      border-right: 1px solid #050400;
      margin-bottom: 4px
    }
    td.palette
    {
      border-bottom: 1px solid #050400;
      border-left: 1px solid #050400;
    }
    a.palette
    {
      padding: 2px 3px 2px 10px;
      text-decoration: none;
    }
    .palette
    {
      -webkit-user-select: none;
      -khtml-user-select: none;
      -moz-user-select: none;
      -o-user-select: none;
      -ms-user-select: none;
    }
  </style><svg xmlns="http://www.w3.org/2000/svg">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs></svg></head>
   <body>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="start">start:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="199" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#never" xlink:title="never">
            <rect x="51" y="3" width="56" height="32"/>
            <rect x="49" y="1" width="56" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="21">never</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#module_decl" xlink:title="module_decl">
            <rect x="51" y="47" width="100" height="32"/>
            <rect x="49" y="45" width="100" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">module_decl</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m56 0 h10 m0 0 h44 m-140 0 h20 m120 0 h20 m-160 0 q10 0 10 10 m140 0 q0 -10 10 -10 m-150 10 v24 m140 0 v-24 m-140 24 q0 10 10 10 m120 0 q10 0 10 -10 m-130 10 h10 m100 0 h10 m23 -44 h-3"/>
         <polygon points="189 17 197 13 197 21"/>
         <polygon points="189 17 181 13 181 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#start" title="start">start</a>    ::= <a href="#never" title="never">never</a></div>
               <div>           | <a href="#module_decl" title="module_decl">module_decl</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">no references</p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="module_decl">module_decl:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="427" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="70" height="32" rx="10"/>
         <rect x="49" y="1" width="70" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">module</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="141" y="3" width="66" height="32"/>
            <rect x="139" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="149" y="21">TOK_ID</text></a><rect x="227" y="3" width="28" height="32" rx="10"/>
         <rect x="225" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="235" y="21">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#never" xlink:title="never">
            <rect x="275" y="3" width="56" height="32"/>
            <rect x="273" y="1" width="56" height="32" class="nonterminal"/>
            <text class="nonterminal" x="283" y="21">never</text></a><rect x="351" y="3" width="28" height="32" rx="10"/>
         <rect x="349" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="359" y="21">}</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_MODULE_REF" xlink:title="TOK_MODULE_REF">
            <rect x="51" y="47" width="136" height="32"/>
            <rect x="49" y="45" width="136" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">TOK_MODULE_REF</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m70 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m28 0 h10 m0 0 h10 m56 0 h10 m0 0 h10 m28 0 h10 m-368 0 h20 m348 0 h20 m-388 0 q10 0 10 10 m368 0 q0 -10 10 -10 m-378 10 v24 m368 0 v-24 m-368 24 q0 10 10 10 m348 0 q10 0 10 -10 m-358 10 h10 m136 0 h10 m0 0 h192 m23 -44 h-3"/>
         <polygon points="417 17 425 13 425 21"/>
         <polygon points="417 17 409 13 409 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#module_decl" title="module_decl">module_decl</a></div>
               <div>         ::= 'module' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#never" title="never">never</a> '}'</div>
               <div>           | <a href="#TOK_MODULE_REF" title="TOK_MODULE_REF">TOK_MODULE_REF</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#start" title="start">start</a></li>
            <li><a href="#use" title="use">use</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="never">never:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="431" height="113">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#use_list" xlink:title="use_list">
            <rect x="51" y="35" width="70" height="32"/>
            <rect x="49" y="33" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="53">use_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#decl_list" xlink:title="decl_list">
            <rect x="181" y="3" width="72" height="32"/>
            <rect x="179" y="1" width="72" height="32" class="nonterminal"/>
            <text class="nonterminal" x="189" y="21">decl_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq_list" xlink:title="seq_list">
            <rect x="293" y="35" width="70" height="32"/>
            <rect x="291" y="33" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="301" y="53">seq_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq_list" xlink:title="seq_list">
            <rect x="181" y="79" width="70" height="32"/>
            <rect x="179" y="77" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="189" y="97">seq_list</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m0 0 h80 m-110 0 h20 m90 0 h20 m-130 0 q10 0 10 10 m110 0 q0 -10 10 -10 m-120 10 v12 m110 0 v-12 m-110 12 q0 10 10 10 m90 0 q10 0 10 -10 m-100 10 h10 m70 0 h10 m40 -32 h10 m72 0 h10 m20 0 h10 m0 0 h80 m-110 0 h20 m90 0 h20 m-130 0 q10 0 10 10 m110 0 q0 -10 10 -10 m-120 10 v12 m110 0 v-12 m-110 12 q0 10 10 10 m90 0 q10 0 10 -10 m-100 10 h10 m70 0 h10 m-222 -32 h20 m222 0 h20 m-262 0 q10 0 10 10 m242 0 q0 -10 10 -10 m-252 10 v56 m242 0 v-56 m-242 56 q0 10 10 10 m222 0 q10 0 10 -10 m-232 10 h10 m70 0 h10 m0 0 h132 m23 -76 h-3"/>
         <polygon points="421 17 429 13 429 21"/>
         <polygon points="421 17 413 13 413 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#never" title="never">never</a>    ::= <a href="#use_list" title="use_list">use_list</a>? ( <a href="#decl_list" title="decl_list">decl_list</a> <a href="#seq_list" title="seq_list">seq_list</a>? | <a href="#seq_list" title="seq_list">seq_list</a> )</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#module_decl" title="module_decl">module_decl</a></li>
            <li><a href="#start" title="start">start</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="use_list">use_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="141" height="53">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#use" xlink:title="use">
            <rect x="51" y="19" width="42" height="32"/>
            <rect x="49" y="17" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">use</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m42 0 h10 m-82 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m62 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-62 0 h10 m0 0 h52 m23 32 h-3"/>
         <polygon points="131 33 139 29 139 37"/>
         <polygon points="131 33 123 29 123 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#use_list" title="use_list">use_list</a> ::= <a href="#use" title="use">use</a>+</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#never" title="never">never</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="use">use:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="379" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="44" height="32" rx="10"/>
         <rect x="29" y="1" width="44" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">use</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_STRING" xlink:title="TOK_NUM_STRING">
            <rect x="95" y="3" width="136" height="32"/>
            <rect x="93" y="1" width="136" height="32" class="nonterminal"/>
            <text class="nonterminal" x="103" y="21">TOK_NUM_STRING</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#module_decl" xlink:title="module_decl">
            <rect x="251" y="3" width="100" height="32"/>
            <rect x="249" y="1" width="100" height="32" class="nonterminal"/>
            <text class="nonterminal" x="259" y="21">module_decl</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m44 0 h10 m0 0 h10 m136 0 h10 m0 0 h10 m100 0 h10 m3 0 h-3"/>
         <polygon points="369 17 377 13 377 21"/>
         <polygon points="369 17 361 13 361 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#use" title="use">use</a>      ::= 'use' <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a> <a href="#module_decl" title="module_decl">module_decl</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#use_list" title="use_list">use_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="decl_list">decl_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="145" height="53">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#decl" xlink:title="decl">
            <rect x="51" y="19" width="46" height="32"/>
            <rect x="49" y="17" width="46" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">decl</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m46 0 h10 m-86 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m66 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-66 0 h10 m0 0 h56 m23 32 h-3"/>
         <polygon points="135 33 143 29 143 37"/>
         <polygon points="135 33 127 29 127 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#decl_list" title="decl_list">decl_list</a></div>
               <div>         ::= <a href="#decl" title="decl">decl</a>+</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#never" title="never">never</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="decl">decl:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="183" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#record" xlink:title="record">
            <rect x="51" y="3" width="60" height="32"/>
            <rect x="49" y="1" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="21">record</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#enumtype" xlink:title="enumtype">
            <rect x="51" y="47" width="84" height="32"/>
            <rect x="49" y="45" width="84" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">enumtype</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m60 0 h10 m0 0 h24 m-124 0 h20 m104 0 h20 m-144 0 q10 0 10 10 m124 0 q0 -10 10 -10 m-134 10 v24 m124 0 v-24 m-124 24 q0 10 10 10 m104 0 q10 0 10 -10 m-114 10 h10 m84 0 h10 m23 -44 h-3"/>
         <polygon points="173 17 181 13 181 21"/>
         <polygon points="173 17 165 13 165 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#decl" title="decl">decl</a>     ::= <a href="#record" title="record">record</a></div>
               <div>           | <a href="#enumtype" title="enumtype">enumtype</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#decl_list" title="decl_list">decl_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="record">record:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="457" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_RECORD" xlink:title="TOK_RECORD">
            <rect x="31" y="3" width="104" height="32"/>
            <rect x="29" y="1" width="104" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_RECORD</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="155" y="3" width="66" height="32"/>
            <rect x="153" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="163" y="21">TOK_ID</text></a><rect x="241" y="3" width="28" height="32" rx="10"/>
         <rect x="239" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="249" y="21">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_seq" xlink:title="param_seq">
            <rect x="289" y="3" width="92" height="32"/>
            <rect x="287" y="1" width="92" height="32" class="nonterminal"/>
            <text class="nonterminal" x="297" y="21">param_seq</text></a><rect x="401" y="3" width="28" height="32" rx="10"/>
         <rect x="399" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="409" y="21">}</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m104 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m28 0 h10 m0 0 h10 m92 0 h10 m0 0 h10 m28 0 h10 m3 0 h-3"/>
         <polygon points="447 17 455 13 455 21"/>
         <polygon points="447 17 439 13 439 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#record" title="record">record</a>   ::= <a href="#TOK_RECORD" title="TOK_RECORD">TOK_RECORD</a> <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#param_seq" title="param_seq">param_seq</a> '}'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#decl" title="decl">decl</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="enumtype">enumtype:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="401" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="58" height="32" rx="10"/>
         <rect x="29" y="1" width="58" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">enum</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="109" y="3" width="66" height="32"/>
            <rect x="107" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="117" y="21">TOK_ID</text></a><rect x="195" y="3" width="28" height="32" rx="10"/>
         <rect x="193" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="203" y="21">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#enum_list" xlink:title="enum_list">
            <rect x="243" y="3" width="82" height="32"/>
            <rect x="241" y="1" width="82" height="32" class="nonterminal"/>
            <text class="nonterminal" x="251" y="21">enum_list</text></a><rect x="345" y="3" width="28" height="32" rx="10"/>
         <rect x="343" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="353" y="21">}</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m58 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m28 0 h10 m0 0 h10 m82 0 h10 m0 0 h10 m28 0 h10 m3 0 h-3"/>
         <polygon points="391 17 399 13 399 21"/>
         <polygon points="391 17 383 13 383 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#enumtype" title="enumtype">enumtype</a> ::= 'enum' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#enum_list" title="enum_list">enum_list</a> '}'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#decl" title="decl">decl</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="enum_list">enum_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="191" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#enum_item" xlink:title="enum_item">
            <rect x="51" y="47" width="92" height="32"/>
            <rect x="49" y="45" width="92" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">enum_item</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m92 0 h10 m-132 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m112 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-112 0 h10 m24 0 h10 m0 0 h68 m23 44 h-3"/>
         <polygon points="181 61 189 57 189 65"/>
         <polygon points="181 61 173 57 173 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#enum_list" title="enum_list">enum_list</a></div>
               <div>         ::= <a href="#enum_item" title="enum_item">enum_item</a> ( ',' <a href="#enum_item" title="enum_item">enum_item</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#enumtype" title="enumtype">enumtype</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="enum_item">enum_item:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="373" height="113">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="31" y="3" width="66" height="32"/>
            <rect x="29" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_ID</text></a><rect x="137" y="35" width="30" height="32" rx="10"/>
         <rect x="135" y="33" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="53">=</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="187" y="35" width="48" height="32"/>
            <rect x="185" y="33" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="195" y="53">expr</text></a><rect x="137" y="79" width="28" height="32" rx="10"/>
         <rect x="135" y="77" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="97">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_seq" xlink:title="param_seq">
            <rect x="185" y="79" width="92" height="32"/>
            <rect x="183" y="77" width="92" height="32" class="nonterminal"/>
            <text class="nonterminal" x="193" y="97">param_seq</text></a><rect x="297" y="79" width="28" height="32" rx="10"/>
         <rect x="295" y="77" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="305" y="97">}</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m66 0 h10 m20 0 h10 m0 0 h198 m-228 0 h20 m208 0 h20 m-248 0 q10 0 10 10 m228 0 q0 -10 10 -10 m-238 10 v12 m228 0 v-12 m-228 12 q0 10 10 10 m208 0 q10 0 10 -10 m-218 10 h10 m30 0 h10 m0 0 h10 m48 0 h10 m0 0 h90 m-218 -10 v20 m228 0 v-20 m-228 20 v24 m228 0 v-24 m-228 24 q0 10 10 10 m208 0 q10 0 10 -10 m-218 10 h10 m28 0 h10 m0 0 h10 m92 0 h10 m0 0 h10 m28 0 h10 m23 -76 h-3"/>
         <polygon points="363 17 371 13 371 21"/>
         <polygon points="363 17 355 13 355 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#enum_item" title="enum_item">enum_item</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '=' <a href="#expr" title="expr">expr</a> | '{' <a href="#param_seq" title="param_seq">param_seq</a> '}' )?</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#enum_list" title="enum_list">enum_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="func">func:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="549" height="157">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="48" height="32" rx="10"/>
         <rect x="49" y="1" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">func</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="139" y="3" width="66" height="32"/>
            <rect x="137" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="147" y="21">TOK_ID</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#error" xlink:title="error">
            <rect x="225" y="3" width="50" height="32"/>
            <rect x="223" y="1" width="50" height="32" class="nonterminal"/>
            <text class="nonterminal" x="233" y="21">error</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func_decl" xlink:title="func_decl">
            <rect x="139" y="47" width="80" height="32"/>
            <rect x="137" y="45" width="80" height="32" class="nonterminal"/>
            <text class="nonterminal" x="147" y="65">func_decl</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func_body" xlink:title="func_body">
            <rect x="239" y="47" width="86" height="32"/>
            <rect x="237" y="45" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="247" y="65">func_body</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func_except" xlink:title="func_except">
            <rect x="365" y="79" width="96" height="32"/>
            <rect x="363" y="77" width="96" height="32" class="nonterminal"/>
            <text class="nonterminal" x="373" y="97">func_except</text></a><rect x="51" y="123" width="64" height="32" rx="10"/>
         <rect x="49" y="121" width="64" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="141">extern</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_STRING" xlink:title="TOK_NUM_STRING">
            <rect x="135" y="123" width="136" height="32"/>
            <rect x="133" y="121" width="136" height="32" class="nonterminal"/>
            <text class="nonterminal" x="143" y="141">TOK_NUM_STRING</text></a><rect x="291" y="123" width="48" height="32" rx="10"/>
         <rect x="289" y="121" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="299" y="141">func</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func_decl" xlink:title="func_decl">
            <rect x="359" y="123" width="80" height="32"/>
            <rect x="357" y="121" width="80" height="32" class="nonterminal"/>
            <text class="nonterminal" x="367" y="141">func_decl</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m48 0 h10 m20 0 h10 m66 0 h10 m0 0 h10 m50 0 h10 m0 0 h206 m-382 0 h20 m362 0 h20 m-402 0 q10 0 10 10 m382 0 q0 -10 10 -10 m-392 10 v24 m382 0 v-24 m-382 24 q0 10 10 10 m362 0 q10 0 10 -10 m-372 10 h10 m80 0 h10 m0 0 h10 m86 0 h10 m20 0 h10 m0 0 h106 m-136 0 h20 m116 0 h20 m-156 0 q10 0 10 10 m136 0 q0 -10 10 -10 m-146 10 v12 m136 0 v-12 m-136 12 q0 10 10 10 m116 0 q10 0 10 -10 m-126 10 h10 m96 0 h10 m-450 -76 h20 m470 0 h20 m-510 0 q10 0 10 10 m490 0 q0 -10 10 -10 m-500 10 v100 m490 0 v-100 m-490 100 q0 10 10 10 m470 0 q10 0 10 -10 m-480 10 h10 m64 0 h10 m0 0 h10 m136 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m80 0 h10 m0 0 h62 m23 -120 h-3"/>
         <polygon points="539 17 547 13 547 21"/>
         <polygon points="539 17 531 13 531 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#func" title="func">func</a>     ::= 'func' ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#error" title="error">error</a> | <a href="#func_decl" title="func_decl">func_decl</a> <a href="#func_body" title="func_body">func_body</a> <a href="#func_except" title="func_except">func_except</a>? )</div>
               <div>           | 'extern' <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a> 'func' <a href="#func_decl" title="func_decl">func_decl</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="func_except">func_except:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="331" height="113">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#except_list" xlink:title="except_list">
            <rect x="51" y="3" width="88" height="32"/>
            <rect x="49" y="1" width="88" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="21">except_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#except_all" xlink:title="except_all">
            <rect x="179" y="35" width="84" height="32"/>
            <rect x="177" y="33" width="84" height="32" class="nonterminal"/>
            <text class="nonterminal" x="187" y="53">except_all</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#except_all" xlink:title="except_all">
            <rect x="51" y="79" width="84" height="32"/>
            <rect x="49" y="77" width="84" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="97">except_all</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m88 0 h10 m20 0 h10 m0 0 h94 m-124 0 h20 m104 0 h20 m-144 0 q10 0 10 10 m124 0 q0 -10 10 -10 m-134 10 v12 m124 0 v-12 m-124 12 q0 10 10 10 m104 0 q10 0 10 -10 m-114 10 h10 m84 0 h10 m-252 -32 h20 m252 0 h20 m-292 0 q10 0 10 10 m272 0 q0 -10 10 -10 m-282 10 v56 m272 0 v-56 m-272 56 q0 10 10 10 m252 0 q10 0 10 -10 m-262 10 h10 m84 0 h10 m0 0 h148 m23 -76 h-3"/>
         <polygon points="321 17 329 13 329 21"/>
         <polygon points="321 17 313 13 313 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#func_except" title="func_except">func_except</a></div>
               <div>         ::= <a href="#except_list" title="except_list">except_list</a> <a href="#except_all" title="except_all">except_all</a>?</div>
               <div>           | <a href="#except_all" title="except_all">except_all</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func" title="func">func</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="except_list">except_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="161" height="53">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#except" xlink:title="except">
            <rect x="51" y="19" width="62" height="32"/>
            <rect x="49" y="17" width="62" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">except</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m62 0 h10 m-102 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m82 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-82 0 h10 m0 0 h72 m23 32 h-3"/>
         <polygon points="151 33 159 29 159 37"/>
         <polygon points="151 33 143 29 143 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#except_list" title="except_list">except_list</a></div>
               <div>         ::= <a href="#except" title="except">except</a>+</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func_except" title="func_except">func_except</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="except">except:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="355" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="56" height="32" rx="10"/>
         <rect x="29" y="1" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">catch</text>
         <rect x="107" y="3" width="26" height="32" rx="10"/>
         <rect x="105" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="115" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="153" y="3" width="66" height="32"/>
            <rect x="151" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="161" y="21">TOK_ID</text></a><rect x="239" y="3" width="26" height="32" rx="10"/>
         <rect x="237" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="247" y="21">)</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq" xlink:title="seq">
            <rect x="285" y="3" width="42" height="32"/>
            <rect x="283" y="1" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="293" y="21">seq</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m56 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m42 0 h10 m3 0 h-3"/>
         <polygon points="345 17 353 13 353 21"/>
         <polygon points="345 17 337 13 337 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#except" title="except">except</a>   ::= 'catch' '(' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ')' <a href="#seq" title="seq">seq</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#except_list" title="except_list">except_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="except_all">except_all:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="177" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="56" height="32" rx="10"/>
         <rect x="29" y="1" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">catch</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq" xlink:title="seq">
            <rect x="107" y="3" width="42" height="32"/>
            <rect x="105" y="1" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="115" y="21">seq</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m56 0 h10 m0 0 h10 m42 0 h10 m3 0 h-3"/>
         <polygon points="167 17 175 13 175 21"/>
         <polygon points="167 17 159 13 159 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#except_all" title="except_all">except_all</a></div>
               <div>         ::= 'catch' <a href="#seq" title="seq">seq</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func_except" title="func_except">func_except</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="func_body">func_body:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="175" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="28" height="32" rx="10"/>
         <rect x="49" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">{</text>
         <rect x="99" y="3" width="28" height="32" rx="10"/>
         <rect x="97" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="107" y="21">}</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq" xlink:title="seq">
            <rect x="51" y="47" width="42" height="32"/>
            <rect x="49" y="45" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">seq</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m28 0 h10 m0 0 h10 m28 0 h10 m-116 0 h20 m96 0 h20 m-136 0 q10 0 10 10 m116 0 q0 -10 10 -10 m-126 10 v24 m116 0 v-24 m-116 24 q0 10 10 10 m96 0 q10 0 10 -10 m-106 10 h10 m42 0 h10 m0 0 h34 m23 -44 h-3"/>
         <polygon points="165 17 173 13 173 21"/>
         <polygon points="165 17 157 13 157 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#func_body" title="func_body">func_body</a></div>
               <div>         ::= '{' '}'</div>
               <div>           | <a href="#seq" title="seq">seq</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func" title="func">func</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="func_decl">func_decl:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="539" height="69">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="51" y="35" width="66" height="32"/>
            <rect x="49" y="33" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="53">TOK_ID</text></a><rect x="157" y="3" width="26" height="32" rx="10"/>
         <rect x="155" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="165" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_list" xlink:title="param_list">
            <rect x="223" y="35" width="86" height="32"/>
            <rect x="221" y="33" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="231" y="53">param_list</text></a><rect x="349" y="3" width="26" height="32" rx="10"/>
         <rect x="347" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="357" y="21">)</text>
         <rect x="395" y="3" width="36" height="32" rx="10"/>
         <rect x="393" y="1" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="403" y="21">-&gt;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="451" y="3" width="60" height="32"/>
            <rect x="449" y="1" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="459" y="21">param</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m0 0 h76 m-106 0 h20 m86 0 h20 m-126 0 q10 0 10 10 m106 0 q0 -10 10 -10 m-116 10 v12 m106 0 v-12 m-106 12 q0 10 10 10 m86 0 q10 0 10 -10 m-96 10 h10 m66 0 h10 m20 -32 h10 m26 0 h10 m20 0 h10 m0 0 h96 m-126 0 h20 m106 0 h20 m-146 0 q10 0 10 10 m126 0 q0 -10 10 -10 m-136 10 v12 m126 0 v-12 m-126 12 q0 10 10 10 m106 0 q10 0 10 -10 m-116 10 h10 m86 0 h10 m20 -32 h10 m26 0 h10 m0 0 h10 m36 0 h10 m0 0 h10 m60 0 h10 m3 0 h-3"/>
         <polygon points="529 17 537 13 537 21"/>
         <polygon points="529 17 521 13 521 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#func_decl" title="func_decl">func_decl</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a>? '(' <a href="#param_list" title="param_list">param_list</a>? ')' '-&gt;' <a href="#param" title="param">param</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func" title="func">func</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="param_seq">param_seq:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="203" height="53">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="51" y="19" width="60" height="32"/>
            <rect x="49" y="17" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">param</text></a><rect x="131" y="19" width="24" height="32" rx="10"/>
         <rect x="129" y="17" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="139" y="37">;</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m60 0 h10 m0 0 h10 m24 0 h10 m-144 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m124 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-124 0 h10 m0 0 h114 m23 32 h-3"/>
         <polygon points="193 33 201 29 201 37"/>
         <polygon points="193 33 185 29 185 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#param_seq" title="param_seq">param_seq</a></div>
               <div>         ::= ( <a href="#param" title="param">param</a> ';' )+</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#enum_item" title="enum_item">enum_item</a></li>
            <li><a href="#record" title="record">record</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="param_list">param_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="159" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="51" y="47" width="60" height="32"/>
            <rect x="49" y="45" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">param</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m60 0 h10 m-100 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m80 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-80 0 h10 m24 0 h10 m0 0 h36 m23 44 h-3"/>
         <polygon points="149 61 157 57 157 65"/>
         <polygon points="149 61 141 57 141 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#param_list" title="param_list">param_list</a></div>
               <div>         ::= <a href="#param" title="param">param</a> ( ',' <a href="#param" title="param">param</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#func_decl" title="func_decl">func_decl</a></li>
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            <li><a href="#touple" title="touple">touple</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="param">param:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="255" height="113">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="35" width="42" height="32" rx="10"/>
         <rect x="49" y="33" width="42" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="53">var</text>
         <rect x="51" y="79" width="38" height="32" rx="10"/>
         <rect x="49" y="77" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="97">let</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_decl" xlink:title="param_decl">
            <rect x="133" y="3" width="94" height="32"/>
            <rect x="131" y="1" width="94" height="32" class="nonterminal"/>
            <text class="nonterminal" x="141" y="21">param_decl</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m0 0 h52 m-82 0 h20 m62 0 h20 m-102 0 q10 0 10 10 m82 0 q0 -10 10 -10 m-92 10 v12 m82 0 v-12 m-82 12 q0 10 10 10 m62 0 q10 0 10 -10 m-72 10 h10 m42 0 h10 m-72 -10 v20 m82 0 v-20 m-82 20 v24 m82 0 v-24 m-82 24 q0 10 10 10 m62 0 q10 0 10 -10 m-72 10 h10 m38 0 h10 m0 0 h4 m20 -76 h10 m94 0 h10 m3 0 h-3"/>
         <polygon points="245 17 253 13 253 21"/>
         <polygon points="245 17 237 13 237 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#param" title="param">param</a>    ::= ( 'var' | 'let' )? <a href="#param_decl" title="param_decl">param_decl</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#array" title="array">array</a></li>
            <li><a href="#func_decl" title="func_decl">func_decl</a></li>
            <li><a href="#listcomp" title="listcomp">listcomp</a></li>
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            <li><a href="#param_list" title="param_list">param_list</a></li>
            <li><a href="#param_seq" title="param_seq">param_seq</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="param_decl">param_decl:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="635" height="1397">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="51" y="3" width="66" height="32"/>
            <rect x="49" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="21">TOK_ID</text></a><rect x="157" y="35" width="24" height="32" rx="10"/>
         <rect x="155" y="33" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="165" y="53">:</text>
         <rect x="221" y="35" width="26" height="32" rx="10"/>
         <rect x="219" y="33" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="53">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_list" xlink:title="param_list">
            <rect x="267" y="35" width="86" height="32"/>
            <rect x="265" y="33" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="275" y="53">param_list</text></a><rect x="373" y="35" width="26" height="32" rx="10"/>
         <rect x="371" y="33" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="381" y="53">)</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="221" y="79" width="66" height="32"/>
            <rect x="219" y="77" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="229" y="97">TOK_ID</text></a><rect x="327" y="111" width="24" height="32" rx="10"/>
         <rect x="325" y="109" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="335" y="129">.</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="371" y="111" width="66" height="32"/>
            <rect x="369" y="109" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="379" y="129">TOK_ID</text></a><rect x="221" y="155" width="56" height="32" rx="10"/>
         <rect x="219" y="153" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="173">c_ptr</text>
         <rect x="221" y="199" width="60" height="32" rx="10"/>
         <rect x="219" y="197" width="60" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="217">string</text>
         <rect x="221" y="243" width="50" height="32" rx="10"/>
         <rect x="219" y="241" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="261">char</text>
         <rect x="221" y="287" width="66" height="32" rx="10"/>
         <rect x="219" y="285" width="66" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="305">double</text>
         <rect x="221" y="331" width="50" height="32" rx="10"/>
         <rect x="219" y="329" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="349">float</text>
         <rect x="221" y="375" width="48" height="32" rx="10"/>
         <rect x="219" y="373" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="393">long</text>
         <rect x="221" y="419" width="38" height="32" rx="10"/>
         <rect x="219" y="417" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="437">int</text>
         <rect x="221" y="463" width="48" height="32" rx="10"/>
         <rect x="219" y="461" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="229" y="481">bool</text>
         <rect x="157" y="507" width="26" height="32" rx="10"/>
         <rect x="155" y="505" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="165" y="525">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_list" xlink:title="param_list">
            <rect x="223" y="539" width="86" height="32"/>
            <rect x="221" y="537" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="231" y="557">param_list</text></a><rect x="349" y="507" width="26" height="32" rx="10"/>
         <rect x="347" y="505" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="357" y="525">)</text>
         <rect x="395" y="507" width="36" height="32" rx="10"/>
         <rect x="393" y="505" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="403" y="525">-&gt;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="451" y="507" width="60" height="32"/>
            <rect x="449" y="505" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="459" y="525">param</text></a><rect x="157" y="583" width="26" height="32" rx="10"/>
         <rect x="155" y="581" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="165" y="601">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#range_dim_list" xlink:title="range_dim_list">
            <rect x="223" y="583" width="114" height="32"/>
            <rect x="221" y="581" width="114" height="32" class="nonterminal"/>
            <text class="nonterminal" x="231" y="601">range_dim_list</text></a><rect x="357" y="583" width="26" height="32" rx="10"/>
         <rect x="355" y="581" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="365" y="601">]</text>
         <rect x="403" y="583" width="24" height="32" rx="10"/>
         <rect x="401" y="581" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="411" y="601">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="467" y="583" width="60" height="32"/>
            <rect x="465" y="581" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="475" y="601">param</text></a><rect x="467" y="627" width="58" height="32" rx="10"/>
         <rect x="465" y="625" width="58" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="475" y="645">range</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#dim_list" xlink:title="dim_list">
            <rect x="223" y="671" width="70" height="32"/>
            <rect x="221" y="669" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="231" y="689">dim_list</text></a><rect x="313" y="671" width="26" height="32" rx="10"/>
         <rect x="311" y="669" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="321" y="689">]</text>
         <rect x="359" y="671" width="24" height="32" rx="10"/>
         <rect x="357" y="669" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="367" y="689">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="403" y="671" width="60" height="32"/>
            <rect x="401" y="669" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="411" y="689">param</text></a><rect x="157" y="715" width="24" height="32" rx="10"/>
         <rect x="155" y="713" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="165" y="733">.</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="201" y="715" width="66" height="32"/>
            <rect x="199" y="713" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="209" y="733">TOK_ID</text></a><rect x="51" y="759" width="26" height="32" rx="10"/>
         <rect x="49" y="757" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="777">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_list" xlink:title="param_list">
            <rect x="117" y="759" width="86" height="32"/>
            <rect x="115" y="757" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="125" y="777">param_list</text></a><rect x="223" y="759" width="26" height="32" rx="10"/>
         <rect x="221" y="757" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="231" y="777">)</text>
         <rect x="289" y="791" width="36" height="32" rx="10"/>
         <rect x="287" y="789" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="297" y="809">-&gt;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="345" y="791" width="60" height="32"/>
            <rect x="343" y="789" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="353" y="809">param</text></a><rect x="117" y="835" width="26" height="32" rx="10"/>
         <rect x="115" y="833" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="125" y="853">)</text>
         <rect x="163" y="835" width="36" height="32" rx="10"/>
         <rect x="161" y="833" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="171" y="853">-&gt;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="219" y="835" width="60" height="32"/>
            <rect x="217" y="833" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="227" y="853">param</text></a><rect x="51" y="879" width="26" height="32" rx="10"/>
         <rect x="49" y="877" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="897">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#range_dim_list" xlink:title="range_dim_list">
            <rect x="117" y="879" width="114" height="32"/>
            <rect x="115" y="877" width="114" height="32" class="nonterminal"/>
            <text class="nonterminal" x="125" y="897">range_dim_list</text></a><rect x="251" y="879" width="26" height="32" rx="10"/>
         <rect x="249" y="877" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="259" y="897">]</text>
         <rect x="297" y="879" width="24" height="32" rx="10"/>
         <rect x="295" y="877" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="305" y="897">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="361" y="879" width="60" height="32"/>
            <rect x="359" y="877" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="369" y="897">param</text></a><rect x="361" y="923" width="58" height="32" rx="10"/>
         <rect x="359" y="921" width="58" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="369" y="941">range</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#dim_list" xlink:title="dim_list">
            <rect x="117" y="967" width="70" height="32"/>
            <rect x="115" y="965" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="125" y="985">dim_list</text></a><rect x="207" y="967" width="26" height="32" rx="10"/>
         <rect x="205" y="965" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="215" y="985">]</text>
         <rect x="253" y="967" width="24" height="32" rx="10"/>
         <rect x="251" y="965" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="261" y="985">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="297" y="967" width="60" height="32"/>
            <rect x="295" y="965" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="305" y="985">param</text></a><rect x="51" y="1011" width="56" height="32" rx="10"/>
         <rect x="49" y="1009" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1029">c_ptr</text>
         <rect x="51" y="1055" width="48" height="32" rx="10"/>
         <rect x="49" y="1053" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1073">void</text>
         <rect x="51" y="1099" width="60" height="32" rx="10"/>
         <rect x="49" y="1097" width="60" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1117">string</text>
         <rect x="51" y="1143" width="50" height="32" rx="10"/>
         <rect x="49" y="1141" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1161">char</text>
         <rect x="51" y="1187" width="66" height="32" rx="10"/>
         <rect x="49" y="1185" width="66" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1205">double</text>
         <rect x="51" y="1231" width="50" height="32" rx="10"/>
         <rect x="49" y="1229" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1249">float</text>
         <rect x="51" y="1275" width="48" height="32" rx="10"/>
         <rect x="49" y="1273" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1293">long</text>
         <rect x="51" y="1319" width="38" height="32" rx="10"/>
         <rect x="49" y="1317" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1337">int</text>
         <rect x="51" y="1363" width="48" height="32" rx="10"/>
         <rect x="49" y="1361" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1381">bool</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m66 0 h10 m20 0 h10 m0 0 h420 m-450 0 h20 m430 0 h20 m-470 0 q10 0 10 10 m450 0 q0 -10 10 -10 m-460 10 v12 m450 0 v-12 m-450 12 q0 10 10 10 m430 0 q10 0 10 -10 m-440 10 h10 m24 0 h10 m20 0 h10 m26 0 h10 m0 0 h10 m86 0 h10 m0 0 h10 m26 0 h10 m0 0 h58 m-276 0 h20 m256 0 h20 m-296 0 q10 0 10 10 m276 0 q0 -10 10 -10 m-286 10 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m66 0 h10 m20 0 h10 m0 0 h120 m-150 0 h20 m130 0 h20 m-170 0 q10 0 10 10 m150 0 q0 -10 10 -10 m-160 10 v12 m150 0 v-12 m-150 12 q0 10 10 10 m130 0 q10 0 10 -10 m-140 10 h10 m24 0 h10 m0 0 h10 m66 0 h10 m-246 -42 v20 m276 0 v-20 m-276 20 v56 m276 0 v-56 m-276 56 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m56 0 h10 m0 0 h180 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m60 0 h10 m0 0 h176 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m50 0 h10 m0 0 h186 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m66 0 h10 m0 0 h170 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m50 0 h10 m0 0 h186 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m48 0 h10 m0 0 h188 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m38 0 h10 m0 0 h198 m-266 -10 v20 m276 0 v-20 m-276 20 v24 m276 0 v-24 m-276 24 q0 10 10 10 m256 0 q10 0 10 -10 m-266 10 h10 m48 0 h10 m0 0 h188 m20 -428 h90 m-440 -10 v20 m450 0 v-20 m-450 20 v452 m450 0 v-452 m-450 452 q0 10 10 10 m430 0 q10 0 10 -10 m-440 10 h10 m26 0 h10 m20 0 h10 m0 0 h96 m-126 0 h20 m106 0 h20 m-146 0 q10 0 10 10 m126 0 q0 -10 10 -10 m-136 10 v12 m126 0 v-12 m-126 12 q0 10 10 10 m106 0 q10 0 10 -10 m-116 10 h10 m86 0 h10 m20 -32 h10 m26 0 h10 m0 0 h10 m36 0 h10 m0 0 h10 m60 0 h10 m0 0 h56 m-440 -10 v20 m450 0 v-20 m-450 20 v56 m450 0 v-56 m-450 56 q0 10 10 10 m430 0 q10 0 10 -10 m-440 10 h10 m26 0 h10 m20 0 h10 m114 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m24 0 h10 m20 0 h10 m60 0 h10 m-100 0 h20 m80 0 h20 m-120 0 q10 0 10 10 m100 0 q0 -10 10 -10 m-110 10 v24 m100 0 v-24 m-100 24 q0 10 10 10 m80 0 q10 0 10 -10 m-90 10 h10 m58 0 h10 m0 0 h2 m-344 -44 h20 m344 0 h20 m-384 0 q10 0 10 10 m364 0 q0 -10 10 -10 m-374 10 v68 m364 0 v-68 m-364 68 q0 10 10 10 m344 0 q10 0 10 -10 m-354 10 h10 m70 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m24 0 h10 m0 0 h10 m60 0 h10 m0 0 h84 m-420 -98 v20 m450 0 v-20 m-450 20 v112 m450 0 v-112 m-450 112 q0 10 10 10 m430 0 q10 0 10 -10 m-440 10 h10 m24 0 h10 m0 0 h10 m66 0 h10 m0 0 h300 m-556 -712 h20 m556 0 h20 m-596 0 q10 0 10 10 m576 0 q0 -10 10 -10 m-586 10 v736 m576 0 v-736 m-576 736 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m26 0 h10 m20 0 h10 m86 0 h10 m0 0 h10 m26 0 h10 m20 0 h10 m0 0 h126 m-156 0 h20 m136 0 h20 m-176 0 q10 0 10 10 m156 0 q0 -10 10 -10 m-166 10 v12 m156 0 v-12 m-156 12 q0 10 10 10 m136 0 q10 0 10 -10 m-146 10 h10 m36 0 h10 m0 0 h10 m60 0 h10 m-328 -32 h20 m328 0 h20 m-368 0 q10 0 10 10 m348 0 q0 -10 10 -10 m-358 10 v56 m348 0 v-56 m-348 56 q0 10 10 10 m328 0 q10 0 10 -10 m-338 10 h10 m26 0 h10 m0 0 h10 m36 0 h10 m0 0 h10 m60 0 h10 m0 0 h146 m20 -76 h142 m-566 -10 v20 m576 0 v-20 m-576 20 v100 m576 0 v-100 m-576 100 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m26 0 h10 m20 0 h10 m114 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m24 0 h10 m20 0 h10 m60 0 h10 m-100 0 h20 m80 0 h20 m-120 0 q10 0 10 10 m100 0 q0 -10 10 -10 m-110 10 v24 m100 0 v-24 m-100 24 q0 10 10 10 m80 0 q10 0 10 -10 m-90 10 h10 m58 0 h10 m0 0 h2 m-344 -44 h20 m344 0 h20 m-384 0 q10 0 10 10 m364 0 q0 -10 10 -10 m-374 10 v68 m364 0 v-68 m-364 68 q0 10 10 10 m344 0 q10 0 10 -10 m-354 10 h10 m70 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m24 0 h10 m0 0 h10 m60 0 h10 m0 0 h84 m20 -88 h126 m-566 -10 v20 m576 0 v-20 m-576 20 v112 m576 0 v-112 m-576 112 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m56 0 h10 m0 0 h480 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m48 0 h10 m0 0 h488 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m60 0 h10 m0 0 h476 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m50 0 h10 m0 0 h486 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m66 0 h10 m0 0 h470 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m50 0 h10 m0 0 h486 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m48 0 h10 m0 0 h488 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m38 0 h10 m0 0 h498 m-566 -10 v20 m576 0 v-20 m-576 20 v24 m576 0 v-24 m-576 24 q0 10 10 10 m556 0 q10 0 10 -10 m-566 10 h10 m48 0 h10 m0 0 h488 m23 -1360 h-3"/>
         <polygon points="625 17 633 13 633 21"/>
         <polygon points="625 17 617 13 617 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#param_decl" title="param_decl">param_decl</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( ':' ( '(' <a href="#param_list" title="param_list">param_list</a> ')' | <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? | 'c_ptr' | 'string' | 'char' | 'double' | 'float' | 'long' | 'int' | 'bool' )
                  | '(' <a href="#param_list" title="param_list">param_list</a>? ')' '-&gt;' <a href="#param" title="param">param</a> | '[' ( <a href="#range_dim_list" title="range_dim_list">range_dim_list</a> ']' ':' ( <a href="#param" title="param">param</a> | 'range' ) | <a href="#dim_list" title="dim_list">dim_list</a> ']' ':' <a href="#param" title="param">param</a> ) | '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )?</div>
               <div>           | '(' ( <a href="#param_list" title="param_list">param_list</a> ')' ( '-&gt;' <a href="#param" title="param">param</a> )? | ')' '-&gt;' <a href="#param" title="param">param</a> )</div>
               <div>           | '[' ( <a href="#range_dim_list" title="range_dim_list">range_dim_list</a> ']' ':' ( <a href="#param" title="param">param</a> | 'range' ) | <a href="#dim_list" title="dim_list">dim_list</a> ']' ':' <a href="#param" title="param">param</a> )</div>
               <div>           | 'c_ptr'</div>
               <div>           | 'void'</div>
               <div>           | 'string'</div>
               <div>           | 'char'</div>
               <div>           | 'double'</div>
               <div>           | 'float'</div>
               <div>           | 'long'</div>
               <div>           | 'int'</div>
               <div>           | 'bool'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#param" title="param">param</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="range_dim_list">range_dim_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="187" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#range_dim" xlink:title="range_dim">
            <rect x="51" y="47" width="88" height="32"/>
            <rect x="49" y="45" width="88" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">range_dim</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m88 0 h10 m-128 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m108 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-108 0 h10 m24 0 h10 m0 0 h64 m23 44 h-3"/>
         <polygon points="177 61 185 57 185 65"/>
         <polygon points="177 61 169 57 169 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#range_dim_list" title="range_dim_list">range_dim_list</a></div>
               <div>         ::= <a href="#range_dim" title="range_dim">range_dim</a> ( ',' <a href="#range_dim" title="range_dim">range_dim</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="range_dim">range_dim:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="299" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="51" y="3" width="66" height="32"/>
            <rect x="49" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="21">TOK_ID</text></a><rect x="137" y="3" width="28" height="32" rx="10"/>
         <rect x="135" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="21">..</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="185" y="3" width="66" height="32"/>
            <rect x="183" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="193" y="21">TOK_ID</text></a><rect x="51" y="47" width="28" height="32" rx="10"/>
         <rect x="49" y="45" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="65">..</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m66 0 h10 m0 0 h10 m28 0 h10 m0 0 h10 m66 0 h10 m-240 0 h20 m220 0 h20 m-260 0 q10 0 10 10 m240 0 q0 -10 10 -10 m-250 10 v24 m240 0 v-24 m-240 24 q0 10 10 10 m220 0 q10 0 10 -10 m-230 10 h10 m28 0 h10 m0 0 h172 m23 -44 h-3"/>
         <polygon points="289 17 297 13 297 21"/>
         <polygon points="289 17 281 13 281 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#range_dim" title="range_dim">range_dim</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '..' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div>
               <div>           | '..'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#range_dim_list" title="range_dim_list">range_dim_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="dim_list">dim_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="141" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#dim" xlink:title="dim">
            <rect x="51" y="47" width="42" height="32"/>
            <rect x="49" y="45" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">dim</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m42 0 h10 m-82 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m62 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-62 0 h10 m24 0 h10 m0 0 h18 m23 44 h-3"/>
         <polygon points="131 61 139 57 139 65"/>
         <polygon points="131 61 123 57 123 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#dim_list" title="dim_list">dim_list</a> ::= <a href="#dim" title="dim">dim</a> ( ',' <a href="#dim" title="dim">dim</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="dim">dim:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="125" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="31" y="3" width="66" height="32"/>
            <rect x="29" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_ID</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m66 0 h10 m3 0 h-3"/>
         <polygon points="115 17 123 13 123 21"/>
         <polygon points="115 17 107 13 107 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#dim" title="dim">dim</a>      ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#dim_list" title="dim_list">dim_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="expr">expr:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="709" height="2453">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="26" height="32" rx="10"/>
         <rect x="49" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_range_dim_list" xlink:title="expr_range_dim_list">
            <rect x="97" y="3" width="150" height="32"/>
            <rect x="95" y="1" width="150" height="32" class="nonterminal"/>
            <text class="nonterminal" x="105" y="21">expr_range_dim_list</text></a><rect x="267" y="3" width="26" height="32" rx="10"/>
         <rect x="265" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="275" y="21">]</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#touple" xlink:title="touple">
            <rect x="51" y="47" width="60" height="32"/>
            <rect x="49" y="45" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">touple</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="51" y="91" width="48" height="32"/>
            <rect x="49" y="89" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="109">expr</text></a><rect x="159" y="91" width="24" height="32" rx="10"/>
         <rect x="157" y="89" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="109">.</text>
         <rect x="159" y="135" width="30" height="32" rx="10"/>
         <rect x="157" y="133" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="153">::</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="229" y="91" width="66" height="32"/>
            <rect x="227" y="89" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="237" y="109">TOK_ID</text></a><rect x="159" y="179" width="30" height="32" rx="10"/>
         <rect x="157" y="177" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="197">=</text>
         <rect x="159" y="223" width="26" height="32" rx="10"/>
         <rect x="157" y="221" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="241">?</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="205" y="223" width="48" height="32"/>
            <rect x="203" y="221" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="213" y="241">expr</text></a><rect x="273" y="223" width="24" height="32" rx="10"/>
         <rect x="271" y="221" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="281" y="241">:</text>
         <rect x="159" y="267" width="50" height="32" rx="10"/>
         <rect x="157" y="265" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="285">&gt;&gt;&gt;</text>
         <rect x="159" y="311" width="50" height="32" rx="10"/>
         <rect x="157" y="309" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="329">&lt;&lt;&lt;</text>
         <rect x="159" y="355" width="50" height="32" rx="10"/>
         <rect x="157" y="353" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="373">^^^</text>
         <rect x="159" y="399" width="40" height="32" rx="10"/>
         <rect x="157" y="397" width="40" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="417">|||</text>
         <rect x="159" y="443" width="50" height="32" rx="10"/>
         <rect x="157" y="441" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="461">&amp;&amp;&amp;</text>
         <rect x="159" y="487" width="36" height="32" rx="10"/>
         <rect x="157" y="485" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="505">|&gt;</text>
         <rect x="159" y="531" width="32" height="32" rx="10"/>
         <rect x="157" y="529" width="32" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="549">||</text>
         <rect x="159" y="575" width="40" height="32" rx="10"/>
         <rect x="157" y="573" width="40" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="593">&amp;&amp;</text>
         <rect x="159" y="619" width="34" height="32" rx="10"/>
         <rect x="157" y="617" width="34" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="637">!=</text>
         <rect x="159" y="663" width="40" height="32" rx="10"/>
         <rect x="157" y="661" width="40" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="681">==</text>
         <rect x="159" y="707" width="40" height="32" rx="10"/>
         <rect x="157" y="705" width="40" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="725">&gt;=</text>
         <rect x="159" y="751" width="30" height="32" rx="10"/>
         <rect x="157" y="749" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="769">&gt;</text>
         <rect x="159" y="795" width="40" height="32" rx="10"/>
         <rect x="157" y="793" width="40" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="813">&lt;=</text>
         <rect x="159" y="839" width="30" height="32" rx="10"/>
         <rect x="157" y="837" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="857">&lt;</text>
         <rect x="159" y="883" width="34" height="32" rx="10"/>
         <rect x="157" y="881" width="34" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="901">%</text>
         <rect x="159" y="927" width="28" height="32" rx="10"/>
         <rect x="157" y="925" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="945">/</text>
         <rect x="159" y="971" width="28" height="32" rx="10"/>
         <rect x="157" y="969" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="989">*</text>
         <rect x="159" y="1015" width="26" height="32" rx="10"/>
         <rect x="157" y="1013" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="1033">-</text>
         <rect x="159" y="1059" width="30" height="32" rx="10"/>
         <rect x="157" y="1057" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="167" y="1077">+</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="337" y="179" width="48" height="32"/>
            <rect x="335" y="177" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="345" y="197">expr</text></a><rect x="139" y="1103" width="26" height="32" rx="10"/>
         <rect x="137" y="1101" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="147" y="1121">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="205" y="1135" width="74" height="32"/>
            <rect x="203" y="1133" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="213" y="1153">expr_list</text></a><rect x="319" y="1103" width="26" height="32" rx="10"/>
         <rect x="317" y="1101" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="327" y="1121">)</text>
         <rect x="139" y="1179" width="26" height="32" rx="10"/>
         <rect x="137" y="1177" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="147" y="1197">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_range_dim_list" xlink:title="expr_range_dim_list">
            <rect x="205" y="1179" width="150" height="32"/>
            <rect x="203" y="1177" width="150" height="32" class="nonterminal"/>
            <text class="nonterminal" x="213" y="1197">expr_range_dim_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="205" y="1223" width="74" height="32"/>
            <rect x="203" y="1221" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="213" y="1241">expr_list</text></a><rect x="395" y="1179" width="26" height="32" rx="10"/>
         <rect x="393" y="1177" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="403" y="1197">]</text>
         <rect x="51" y="1267" width="62" height="32" rx="10"/>
         <rect x="49" y="1265" width="62" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1285">match</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="133" y="1267" width="48" height="32"/>
            <rect x="131" y="1265" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="141" y="1285">expr</text></a><rect x="201" y="1267" width="28" height="32" rx="10"/>
         <rect x="199" y="1265" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="209" y="1285">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard_list" xlink:title="match_guard_list">
            <rect x="269" y="1299" width="130" height="32"/>
            <rect x="267" y="1297" width="130" height="32" class="nonterminal"/>
            <text class="nonterminal" x="277" y="1317">match_guard_list</text></a><rect x="439" y="1267" width="28" height="32" rx="10"/>
         <rect x="437" y="1265" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="447" y="1285">}</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#iflet" xlink:title="iflet">
            <rect x="51" y="1343" width="44" height="32"/>
            <rect x="49" y="1341" width="44" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="1361">iflet</text></a><rect x="91" y="1387" width="38" height="32" rx="10"/>
         <rect x="89" y="1385" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="99" y="1405">for</text>
         <rect x="149" y="1387" width="26" height="32" rx="10"/>
         <rect x="147" y="1385" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="157" y="1405">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="215" y="1387" width="66" height="32"/>
            <rect x="213" y="1385" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="223" y="1405">TOK_ID</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_IN" xlink:title="TOK_IN">
            <rect x="301" y="1387" width="66" height="32"/>
            <rect x="299" y="1385" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="309" y="1405">TOK_IN</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="215" y="1431" width="48" height="32"/>
            <rect x="213" y="1429" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="223" y="1449">expr</text></a><rect x="283" y="1431" width="24" height="32" rx="10"/>
         <rect x="281" y="1429" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="291" y="1449">;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="327" y="1431" width="48" height="32"/>
            <rect x="325" y="1429" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="335" y="1449">expr</text></a><rect x="395" y="1431" width="24" height="32" rx="10"/>
         <rect x="393" y="1429" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="403" y="1449">;</text>
         <rect x="91" y="1475" width="56" height="32" rx="10"/>
         <rect x="89" y="1473" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="99" y="1493">while</text>
         <rect x="167" y="1475" width="26" height="32" rx="10"/>
         <rect x="165" y="1473" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="175" y="1493">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="479" y="1387" width="48" height="32"/>
            <rect x="477" y="1385" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="487" y="1405">expr</text></a><rect x="547" y="1387" width="26" height="32" rx="10"/>
         <rect x="545" y="1385" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="555" y="1405">)</text>
         <rect x="71" y="1519" width="50" height="32" rx="10"/>
         <rect x="69" y="1517" width="50" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="79" y="1537">~~~</text>
         <rect x="71" y="1563" width="24" height="32" rx="10"/>
         <rect x="69" y="1561" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="79" y="1581">!</text>
         <rect x="71" y="1607" width="26" height="32" rx="10"/>
         <rect x="69" y="1605" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="79" y="1625">-</text>
         <rect x="71" y="1651" width="28" height="32" rx="10"/>
         <rect x="69" y="1649" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="79" y="1669">if</text>
         <rect x="119" y="1651" width="26" height="32" rx="10"/>
         <rect x="117" y="1649" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="127" y="1669">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="165" y="1651" width="48" height="32"/>
            <rect x="163" y="1649" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="173" y="1669">expr</text></a><rect x="233" y="1651" width="26" height="32" rx="10"/>
         <rect x="231" y="1649" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="241" y="1669">)</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="299" y="1683" width="48" height="32"/>
            <rect x="297" y="1681" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="307" y="1701">expr</text></a><rect x="367" y="1683" width="46" height="32" rx="10"/>
         <rect x="365" y="1681" width="46" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="375" y="1701">else</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="613" y="1387" width="48" height="32"/>
            <rect x="611" y="1385" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="621" y="1405">expr</text></a><rect x="71" y="1759" width="36" height="32" rx="10"/>
         <rect x="69" y="1757" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="79" y="1777">do</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="127" y="1759" width="48" height="32"/>
            <rect x="125" y="1757" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="135" y="1777">expr</text></a><rect x="195" y="1759" width="56" height="32" rx="10"/>
         <rect x="193" y="1757" width="56" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="203" y="1777">while</text>
         <rect x="291" y="1727" width="26" height="32" rx="10"/>
         <rect x="289" y="1725" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="299" y="1745">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="337" y="1727" width="48" height="32"/>
            <rect x="335" y="1725" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="345" y="1745">expr</text></a><rect x="405" y="1727" width="26" height="32" rx="10"/>
         <rect x="403" y="1725" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="413" y="1745">)</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq" xlink:title="seq">
            <rect x="51" y="1803" width="42" height="32"/>
            <rect x="49" y="1801" width="42" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="1821">seq</text></a><rect x="51" y="1847" width="38" height="32" rx="10"/>
         <rect x="49" y="1845" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1865">let</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func" xlink:title="func">
            <rect x="109" y="1847" width="46" height="32"/>
            <rect x="107" y="1845" width="46" height="32" class="nonterminal"/>
            <text class="nonterminal" x="117" y="1865">func</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#listcomp" xlink:title="listcomp">
            <rect x="51" y="1891" width="72" height="32"/>
            <rect x="49" y="1889" width="72" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="1909">listcomp</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#array" xlink:title="array">
            <rect x="51" y="1935" width="52" height="32"/>
            <rect x="49" y="1933" width="52" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="1953">array</text></a><rect x="51" y="1979" width="60" height="32" rx="10"/>
         <rect x="49" y="1977" width="60" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="1997">c_null</text>
         <rect x="51" y="2023" width="36" height="32" rx="10"/>
         <rect x="49" y="2021" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="2041">nil</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_STRING" xlink:title="TOK_NUM_STRING">
            <rect x="51" y="2067" width="136" height="32"/>
            <rect x="49" y="2065" width="136" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2085">TOK_NUM_STRING</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_CHAR" xlink:title="TOK_NUM_CHAR">
            <rect x="51" y="2111" width="122" height="32"/>
            <rect x="49" y="2109" width="122" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2129">TOK_NUM_CHAR</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_DOUBLE" xlink:title="TOK_NUM_DOUBLE">
            <rect x="51" y="2155" width="140" height="32"/>
            <rect x="49" y="2153" width="140" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2173">TOK_NUM_DOUBLE</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_FLOAT" xlink:title="TOK_NUM_FLOAT">
            <rect x="51" y="2199" width="126" height="32"/>
            <rect x="49" y="2197" width="126" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2217">TOK_NUM_FLOAT</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_LONG" xlink:title="TOK_NUM_LONG">
            <rect x="51" y="2243" width="124" height="32"/>
            <rect x="49" y="2241" width="124" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2261">TOK_NUM_LONG</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_NUM_INT" xlink:title="TOK_NUM_INT">
            <rect x="51" y="2287" width="110" height="32"/>
            <rect x="49" y="2285" width="110" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2305">TOK_NUM_INT</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="51" y="2331" width="66" height="32"/>
            <rect x="49" y="2329" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="2349">TOK_ID</text></a><rect x="51" y="2375" width="52" height="32" rx="10"/>
         <rect x="49" y="2373" width="52" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="2393">false</text>
         <rect x="51" y="2419" width="48" height="32" rx="10"/>
         <rect x="49" y="2417" width="48" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="2437">true</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m26 0 h10 m0 0 h10 m150 0 h10 m0 0 h10 m26 0 h10 m0 0 h368 m-650 0 h20 m630 0 h20 m-670 0 q10 0 10 10 m650 0 q0 -10 10 -10 m-660 10 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m60 0 h10 m0 0 h550 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m48 0 h10 m40 0 h10 m24 0 h10 m0 0 h6 m-70 0 h20 m50 0 h20 m-90 0 q10 0 10 10 m70 0 q0 -10 10 -10 m-80 10 v24 m70 0 v-24 m-70 24 q0 10 10 10 m50 0 q10 0 10 -10 m-60 10 h10 m30 0 h10 m20 -44 h10 m66 0 h10 m0 0 h126 m-322 0 h20 m302 0 h20 m-342 0 q10 0 10 10 m322 0 q0 -10 10 -10 m-332 10 v68 m322 0 v-68 m-322 68 q0 10 10 10 m302 0 q10 0 10 -10 m-292 10 h10 m30 0 h10 m0 0 h108 m-178 0 h20 m158 0 h20 m-198 0 q10 0 10 10 m178 0 q0 -10 10 -10 m-188 10 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m26 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m24 0 h10 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m50 0 h10 m0 0 h88 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m50 0 h10 m0 0 h88 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m50 0 h10 m0 0 h88 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m40 0 h10 m0 0 h98 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m50 0 h10 m0 0 h88 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m36 0 h10 m0 0 h102 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m32 0 h10 m0 0 h106 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m40 0 h10 m0 0 h98 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m34 0 h10 m0 0 h104 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m40 0 h10 m0 0 h98 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m40 0 h10 m0 0 h98 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m30 0 h10 m0 0 h108 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m40 0 h10 m0 0 h98 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m30 0 h10 m0 0 h108 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m34 0 h10 m0 0 h104 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m28 0 h10 m0 0 h110 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m28 0 h10 m0 0 h110 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m26 0 h10 m0 0 h112 m-168 -10 v20 m178 0 v-20 m-178 20 v24 m178 0 v-24 m-178 24 q0 10 10 10 m158 0 q10 0 10 -10 m-168 10 h10 m30 0 h10 m0 0 h108 m20 -880 h10 m48 0 h10 m0 0 h36 m-312 -10 v20 m322 0 v-20 m-322 20 v904 m322 0 v-904 m-322 904 q0 10 10 10 m302 0 q10 0 10 -10 m-312 10 h10 m26 0 h10 m20 0 h10 m0 0 h84 m-114 0 h20 m94 0 h20 m-134 0 q10 0 10 10 m114 0 q0 -10 10 -10 m-124 10 v12 m114 0 v-12 m-114 12 q0 10 10 10 m94 0 q10 0 10 -10 m-104 10 h10 m74 0 h10 m20 -32 h10 m26 0 h10 m0 0 h76 m-312 -10 v20 m322 0 v-20 m-322 20 v56 m322 0 v-56 m-322 56 q0 10 10 10 m302 0 q10 0 10 -10 m-312 10 h10 m26 0 h10 m20 0 h10 m150 0 h10 m-190 0 h20 m170 0 h20 m-210 0 q10 0 10 10 m190 0 q0 -10 10 -10 m-200 10 v24 m190 0 v-24 m-190 24 q0 10 10 10 m170 0 q10 0 10 -10 m-180 10 h10 m74 0 h10 m0 0 h76 m20 -44 h10 m26 0 h10 m20 -1088 h220 m-640 -10 v20 m650 0 v-20 m-650 20 v1156 m650 0 v-1156 m-650 1156 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m62 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m28 0 h10 m20 0 h10 m0 0 h140 m-170 0 h20 m150 0 h20 m-190 0 q10 0 10 10 m170 0 q0 -10 10 -10 m-180 10 v12 m170 0 v-12 m-170 12 q0 10 10 10 m150 0 q10 0 10 -10 m-160 10 h10 m130 0 h10 m20 -32 h10 m28 0 h10 m0 0 h194 m-640 -10 v20 m650 0 v-20 m-650 20 v56 m650 0 v-56 m-650 56 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m44 0 h10 m0 0 h566 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-600 10 h10 m38 0 h10 m0 0 h10 m26 0 h10 m20 0 h10 m66 0 h10 m0 0 h10 m66 0 h10 m0 0 h52 m-244 0 h20 m224 0 h20 m-264 0 q10 0 10 10 m244 0 q0 -10 10 -10 m-254 10 v24 m244 0 v-24 m-244 24 q0 10 10 10 m224 0 q10 0 10 -10 m-234 10 h10 m48 0 h10 m0 0 h10 m24 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m24 0 h10 m-368 -44 h20 m368 0 h20 m-408 0 q10 0 10 10 m388 0 q0 -10 10 -10 m-398 10 v68 m388 0 v-68 m-388 68 q0 10 10 10 m368 0 q10 0 10 -10 m-378 10 h10 m56 0 h10 m0 0 h10 m26 0 h10 m0 0 h246 m20 -88 h10 m48 0 h10 m0 0 h10 m26 0 h10 m-542 0 h20 m522 0 h20 m-562 0 q10 0 10 10 m542 0 q0 -10 10 -10 m-552 10 v112 m542 0 v-112 m-542 112 q0 10 10 10 m522 0 q10 0 10 -10 m-532 10 h10 m50 0 h10 m0 0 h452 m-532 -10 v20 m542 0 v-20 m-542 20 v24 m542 0 v-24 m-542 24 q0 10 10 10 m522 0 q10 0 10 -10 m-532 10 h10 m24 0 h10 m0 0 h478 m-532 -10 v20 m542 0 v-20 m-542 20 v24 m542 0 v-24 m-542 24 q0 10 10 10 m522 0 q10 0 10 -10 m-532 10 h10 m26 0 h10 m0 0 h476 m-532 -10 v20 m542 0 v-20 m-542 20 v24 m542 0 v-24 m-542 24 q0 10 10 10 m522 0 q10 0 10 -10 m-532 10 h10 m28 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m26 0 h10 m20 0 h10 m0 0 h124 m-154 0 h20 m134 0 h20 m-174 0 q10 0 10 10 m154 0 q0 -10 10 -10 m-164 10 v12 m154 0 v-12 m-154 12 q0 10 10 10 m134 0 q10 0 10 -10 m-144 10 h10 m48 0 h10 m0 0 h10 m46 0 h10 m20 -32 h140 m20 -264 h10 m48 0 h10 m-640 -10 v20 m650 0 v-20 m-650 20 v320 m650 0 v-320 m-650 320 q0 10 10 10 m630 0 q10 0 10 -10 m-620 10 h10 m0 0 h190 m-220 0 h20 m200 0 h20 m-240 0 q10 0 10 10 m220 0 q0 -10 10 -10 m-230 10 v12 m220 0 v-12 m-220 12 q0 10 10 10 m200 0 q10 0 10 -10 m-210 10 h10 m36 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m56 0 h10 m20 -32 h10 m26 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m26 0 h10 m0 0 h230 m-640 -10 v20 m650 0 v-20 m-650 20 v56 m650 0 v-56 m-650 56 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m42 0 h10 m0 0 h568 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m38 0 h10 m0 0 h10 m46 0 h10 m0 0 h506 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m72 0 h10 m0 0 h538 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m52 0 h10 m0 0 h558 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m60 0 h10 m0 0 h550 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m36 0 h10 m0 0 h574 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m136 0 h10 m0 0 h474 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m122 0 h10 m0 0 h488 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m140 0 h10 m0 0 h470 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m126 0 h10 m0 0 h484 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m124 0 h10 m0 0 h486 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m110 0 h10 m0 0 h500 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m66 0 h10 m0 0 h544 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m52 0 h10 m0 0 h558 m-640 -10 v20 m650 0 v-20 m-650 20 v24 m650 0 v-24 m-650 24 q0 10 10 10 m630 0 q10 0 10 -10 m-640 10 h10 m48 0 h10 m0 0 h562 m23 -2416 h-3"/>
         <polygon points="699 17 707 13 707 21"/>
         <polygon points="699 17 691 13 691 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#expr" title="expr">expr</a>     ::= '[' <a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a> ']'</div>
               <div>           | <a href="#touple" title="touple">touple</a></div>
               <div>           | <a href="#expr" title="expr">expr</a> ( ( '.' | '::' ) <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> | ( '=' | '?' <a href="#expr" title="expr">expr</a> ':' | '&gt;&gt;&gt;' | '&lt;&lt;&lt;' | '^^^' | '|||' | '&amp;&amp;&amp;' | '|&gt;' | '||' | '&amp;&amp;' | '!=' | '==' |
                  '&gt;=' | '&gt;' | '&lt;=' | '&lt;' | '%' | '/' | '*' | '-' | '+' ) <a href="#expr" title="expr">expr</a> | '(' <a href="#expr_list" title="expr_list">expr_list</a>? ')' | '[' ( <a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']' )</div>
               <div>           | 'match' <a href="#expr" title="expr">expr</a> '{' <a href="#match_guard_list" title="match_guard_list">match_guard_list</a>? '}'</div>
               <div>           | <a href="#iflet" title="iflet">iflet</a></div>
               <div>           | ( ( 'for' '(' ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#TOK_IN" title="TOK_IN">TOK_IN</a> | <a href="#expr" title="expr">expr</a> ';' <a href="#expr" title="expr">expr</a> ';' ) | 'while' '(' ) <a href="#expr" title="expr">expr</a> ')' | '~~~' | '!' | '-' | 'if' '(' <a href="#expr" title="expr">expr</a> ')' ( <a href="#expr" title="expr">expr</a> 'else' )? ) <a href="#expr" title="expr">expr</a></div>
               <div>           | ( 'do' <a href="#expr" title="expr">expr</a> 'while' )? '(' <a href="#expr" title="expr">expr</a> ')'</div>
               <div>           | <a href="#seq" title="seq">seq</a></div>
               <div>           | 'let' <a href="#func" title="func">func</a></div>
               <div>           | <a href="#listcomp" title="listcomp">listcomp</a></div>
               <div>           | <a href="#array" title="array">array</a></div>
               <div>           | 'c_null'</div>
               <div>           | 'nil'</div>
               <div>           | <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a></div>
               <div>           | <a href="#TOK_NUM_CHAR" title="TOK_NUM_CHAR">TOK_NUM_CHAR</a></div>
               <div>           | <a href="#TOK_NUM_DOUBLE" title="TOK_NUM_DOUBLE">TOK_NUM_DOUBLE</a></div>
               <div>           | <a href="#TOK_NUM_FLOAT" title="TOK_NUM_FLOAT">TOK_NUM_FLOAT</a></div>
               <div>           | <a href="#TOK_NUM_LONG" title="TOK_NUM_LONG">TOK_NUM_LONG</a></div>
               <div>           | <a href="#TOK_NUM_INT" title="TOK_NUM_INT">TOK_NUM_INT</a></div>
               <div>           | <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div>
               <div>           | 'false'</div>
               <div>           | 'true'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#enum_item" title="enum_item">enum_item</a></li>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#expr_list" title="expr_list">expr_list</a></li>
            <li><a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a></li>
            <li><a href="#generator" title="generator">generator</a></li>
            <li><a href="#iflet" title="iflet">iflet</a></li>
            <li><a href="#let" title="let">let</a></li>
            <li><a href="#listcomp" title="listcomp">listcomp</a></li>
            <li><a href="#match_guard" title="match_guard">match_guard</a></li>
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
            <li><a href="#touple" title="touple">touple</a></li>
            <li><a href="#var" title="var">var</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="expr_range_dim_list">expr_range_dim_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="223" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_range_dim" xlink:title="expr_range_dim">
            <rect x="51" y="47" width="124" height="32"/>
            <rect x="49" y="45" width="124" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">expr_range_dim</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m124 0 h10 m-164 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m144 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-144 0 h10 m24 0 h10 m0 0 h100 m23 44 h-3"/>
         <polygon points="213 61 221 57 221 65"/>
         <polygon points="213 61 205 57 205 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a></div>
               <div>         ::= <a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a> ( ',' <a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="expr_range_dim">expr_range_dim:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="223" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="31" y="3" width="48" height="32"/>
            <rect x="29" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">expr</text></a><rect x="99" y="3" width="28" height="32" rx="10"/>
         <rect x="97" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="107" y="21">..</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="147" y="3" width="48" height="32"/>
            <rect x="145" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="155" y="21">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m48 0 h10 m0 0 h10 m28 0 h10 m0 0 h10 m48 0 h10 m3 0 h-3"/>
         <polygon points="213 17 221 13 221 21"/>
         <polygon points="213 17 205 13 205 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a></div>
               <div>         ::= <a href="#expr" title="expr">expr</a> '..' <a href="#expr" title="expr">expr</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="seq">seq:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="225" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="28" height="32" rx="10"/>
         <rect x="29" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">{</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#seq_list" xlink:title="seq_list">
            <rect x="79" y="3" width="70" height="32"/>
            <rect x="77" y="1" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="87" y="21">seq_list</text></a><rect x="169" y="3" width="28" height="32" rx="10"/>
         <rect x="167" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="177" y="21">}</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m28 0 h10 m0 0 h10 m70 0 h10 m0 0 h10 m28 0 h10 m3 0 h-3"/>
         <polygon points="215 17 223 13 223 21"/>
         <polygon points="215 17 207 13 207 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#seq" title="seq">seq</a>      ::= '{' <a href="#seq_list" title="seq_list">seq_list</a> '}'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#except" title="except">except</a></li>
            <li><a href="#except_all" title="except_all">except_all</a></li>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#func_body" title="func_body">func_body</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="seq_list">seq_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="419" height="245">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="51" y="19" width="48" height="32"/>
            <rect x="49" y="17" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">expr</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func" xlink:title="func">
            <rect x="51" y="63" width="46" height="32"/>
            <rect x="49" y="61" width="46" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="81">func</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#var" xlink:title="var">
            <rect x="51" y="107" width="40" height="32"/>
            <rect x="49" y="105" width="40" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="125">var</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#let" xlink:title="let">
            <rect x="51" y="151" width="36" height="32"/>
            <rect x="49" y="149" width="36" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="169">let</text></a><rect x="199" y="19" width="24" height="32" rx="10"/>
         <rect x="197" y="17" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="207" y="37">;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="263" y="19" width="48" height="32"/>
            <rect x="261" y="17" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="271" y="37">expr</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func" xlink:title="func">
            <rect x="263" y="63" width="46" height="32"/>
            <rect x="261" y="61" width="46" height="32" class="nonterminal"/>
            <text class="nonterminal" x="271" y="81">func</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#var" xlink:title="var">
            <rect x="263" y="107" width="40" height="32"/>
            <rect x="261" y="105" width="40" height="32" class="nonterminal"/>
            <text class="nonterminal" x="271" y="125">var</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#let" xlink:title="let">
            <rect x="263" y="151" width="36" height="32"/>
            <rect x="261" y="149" width="36" height="32" class="nonterminal"/>
            <text class="nonterminal" x="271" y="169">let</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#func" xlink:title="func">
            <rect x="199" y="195" width="46" height="32"/>
            <rect x="197" y="193" width="46" height="32" class="nonterminal"/>
            <text class="nonterminal" x="207" y="213">func</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m48 0 h10 m-88 0 h20 m68 0 h20 m-108 0 q10 0 10 10 m88 0 q0 -10 10 -10 m-98 10 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m46 0 h10 m0 0 h2 m-78 -10 v20 m88 0 v-20 m-88 20 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m40 0 h10 m0 0 h8 m-78 -10 v20 m88 0 v-20 m-88 20 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m36 0 h10 m0 0 h12 m80 -132 h10 m24 0 h10 m20 0 h10 m48 0 h10 m-88 0 h20 m68 0 h20 m-108 0 q10 0 10 10 m88 0 q0 -10 10 -10 m-98 10 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m46 0 h10 m0 0 h2 m-78 -10 v20 m88 0 v-20 m-88 20 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m40 0 h10 m0 0 h8 m-78 -10 v20 m88 0 v-20 m-88 20 v24 m88 0 v-24 m-88 24 q0 10 10 10 m68 0 q10 0 10 -10 m-78 10 h10 m36 0 h10 m0 0 h12 m-152 -132 h20 m152 0 h20 m-192 0 q10 0 10 10 m172 0 q0 -10 10 -10 m-182 10 v156 m172 0 v-156 m-172 156 q0 10 10 10 m152 0 q10 0 10 -10 m-162 10 h10 m46 0 h10 m0 0 h86 m-192 -176 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m192 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-192 0 h10 m0 0 h182 m-232 32 h20 m232 0 h20 m-272 0 q10 0 10 10 m252 0 q0 -10 10 -10 m-262 10 v190 m252 0 v-190 m-252 190 q0 10 10 10 m232 0 q10 0 10 -10 m-242 10 h10 m0 0 h222 m23 -210 h-3"/>
         <polygon points="409 33 417 29 417 37"/>
         <polygon points="409 33 401 29 401 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#seq_list" title="seq_list">seq_list</a> ::= ( <a href="#expr" title="expr">expr</a> | <a href="#func" title="func">func</a> | <a href="#var" title="var">var</a> | <a href="#let" title="let">let</a> ) ( ';' ( <a href="#expr" title="expr">expr</a> | <a href="#func" title="func">func</a> | <a href="#var" title="var">var</a> | <a href="#let" title="let">let</a> ) | <a href="#func" title="func">func</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#never" title="never">never</a></li>
            <li><a href="#seq" title="seq">seq</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="var">var:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="305" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="42" height="32" rx="10"/>
         <rect x="29" y="1" width="42" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">var</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="93" y="3" width="66" height="32"/>
            <rect x="91" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="101" y="21">TOK_ID</text></a><rect x="179" y="3" width="30" height="32" rx="10"/>
         <rect x="177" y="1" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="187" y="21">=</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="229" y="3" width="48" height="32"/>
            <rect x="227" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="237" y="21">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m42 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m30 0 h10 m0 0 h10 m48 0 h10 m3 0 h-3"/>
         <polygon points="295 17 303 13 303 21"/>
         <polygon points="295 17 287 13 287 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#var" title="var">var</a>      ::= 'var' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '=' <a href="#expr" title="expr">expr</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="let">let:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="301" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="38" height="32" rx="10"/>
         <rect x="29" y="1" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">let</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="89" y="3" width="66" height="32"/>
            <rect x="87" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="97" y="21">TOK_ID</text></a><rect x="175" y="3" width="30" height="32" rx="10"/>
         <rect x="173" y="1" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="183" y="21">=</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="225" y="3" width="48" height="32"/>
            <rect x="223" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="233" y="21">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m38 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m30 0 h10 m0 0 h10 m48 0 h10 m3 0 h-3"/>
         <polygon points="291 17 299 13 299 21"/>
         <polygon points="291 17 283 13 283 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#let" title="let">let</a>      ::= 'let' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '=' <a href="#expr" title="expr">expr</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="expr_list">expr_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="147" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="51" y="47" width="48" height="32"/>
            <rect x="49" y="45" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">expr</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m48 0 h10 m-88 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m68 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-68 0 h10 m24 0 h10 m0 0 h24 m23 44 h-3"/>
         <polygon points="137 61 145 57 145 65"/>
         <polygon points="137 61 129 57 129 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#expr_list" title="expr_list">expr_list</a></div>
               <div>         ::= <a href="#expr" title="expr">expr</a> ( ',' <a href="#expr" title="expr">expr</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#array" title="array">array</a></li>
            <li><a href="#array_sub" title="array_sub">array_sub</a></li>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#touple" title="touple">touple</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="touple">touple:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="619" height="69">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="26" height="32" rx="10"/>
         <rect x="29" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="77" y="3" width="48" height="32"/>
            <rect x="75" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="85" y="21">expr</text></a><rect x="145" y="3" width="24" height="32" rx="10"/>
         <rect x="143" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="153" y="21">,</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="209" y="35" width="74" height="32"/>
            <rect x="207" y="33" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="217" y="53">expr_list</text></a><rect x="323" y="3" width="26" height="32" rx="10"/>
         <rect x="321" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="331" y="21">)</text>
         <rect x="369" y="3" width="24" height="32" rx="10"/>
         <rect x="367" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="377" y="21">:</text>
         <rect x="413" y="3" width="26" height="32" rx="10"/>
         <rect x="411" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="421" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param_list" xlink:title="param_list">
            <rect x="459" y="3" width="86" height="32"/>
            <rect x="457" y="1" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="467" y="21">param_list</text></a><rect x="565" y="3" width="26" height="32" rx="10"/>
         <rect x="563" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="573" y="21">)</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m26 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m24 0 h10 m20 0 h10 m0 0 h84 m-114 0 h20 m94 0 h20 m-134 0 q10 0 10 10 m114 0 q0 -10 10 -10 m-124 10 v12 m114 0 v-12 m-114 12 q0 10 10 10 m94 0 q10 0 10 -10 m-104 10 h10 m74 0 h10 m20 -32 h10 m26 0 h10 m0 0 h10 m24 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m86 0 h10 m0 0 h10 m26 0 h10 m3 0 h-3"/>
         <polygon points="609 17 617 13 617 21"/>
         <polygon points="609 17 601 13 601 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#touple" title="touple">touple</a>   ::= '(' <a href="#expr" title="expr">expr</a> ',' <a href="#expr_list" title="expr_list">expr_list</a>? ')' ':' '(' <a href="#param_list" title="param_list">param_list</a> ')'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="match_guard_list">match_guard_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="247" height="53">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 33 1 29 1 37"/>
         <polygon points="17 33 9 29 9 37"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard" xlink:title="match_guard">
            <rect x="51" y="19" width="104" height="32"/>
            <rect x="49" y="17" width="104" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="37">match_guard</text></a><rect x="175" y="19" width="24" height="32" rx="10"/>
         <rect x="173" y="17" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="183" y="37">;</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 33 h2 m20 0 h10 m104 0 h10 m0 0 h10 m24 0 h10 m-188 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -12 q0 -10 10 -10 m168 32 l20 0 m-20 0 q10 0 10 -10 l0 -12 q0 -10 -10 -10 m-168 0 h10 m0 0 h158 m23 32 h-3"/>
         <polygon points="237 33 245 29 245 37"/>
         <polygon points="237 33 229 29 229 37"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#match_guard_list" title="match_guard_list">match_guard_list</a></div>
               <div>         ::= ( <a href="#match_guard" title="match_guard">match_guard</a> ';' )+</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="match_guard">match_guard:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="375" height="125">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="46" height="32" rx="10"/>
         <rect x="49" y="1" width="46" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">else</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard_record" xlink:title="match_guard_record">
            <rect x="51" y="47" width="152" height="32"/>
            <rect x="49" y="45" width="152" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">match_guard_record</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard_item" xlink:title="match_guard_item">
            <rect x="51" y="91" width="140" height="32"/>
            <rect x="49" y="89" width="140" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="109">match_guard_item</text></a><rect x="243" y="3" width="36" height="32" rx="10"/>
         <rect x="241" y="1" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="251" y="21">-&gt;</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="299" y="3" width="48" height="32"/>
            <rect x="297" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="307" y="21">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m46 0 h10 m0 0 h106 m-192 0 h20 m172 0 h20 m-212 0 q10 0 10 10 m192 0 q0 -10 10 -10 m-202 10 v24 m192 0 v-24 m-192 24 q0 10 10 10 m172 0 q10 0 10 -10 m-182 10 h10 m152 0 h10 m-182 -10 v20 m192 0 v-20 m-192 20 v24 m192 0 v-24 m-192 24 q0 10 10 10 m172 0 q10 0 10 -10 m-182 10 h10 m140 0 h10 m0 0 h12 m20 -88 h10 m36 0 h10 m0 0 h10 m48 0 h10 m3 0 h-3"/>
         <polygon points="365 17 373 13 373 21"/>
         <polygon points="365 17 357 13 357 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#match_guard" title="match_guard">match_guard</a></div>
               <div>         ::= ( 'else' | <a href="#match_guard_record" title="match_guard_record">match_guard_record</a> | <a href="#match_guard_item" title="match_guard_item">match_guard_item</a> ) '-&gt;' <a href="#expr" title="expr">expr</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#match_guard_list" title="match_guard_list">match_guard_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="match_guard_record">match_guard_record:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="655" height="69">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="31" y="3" width="66" height="32"/>
            <rect x="29" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_ID</text></a><rect x="137" y="35" width="24" height="32" rx="10"/>
         <rect x="135" y="33" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="53">.</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="181" y="35" width="66" height="32"/>
            <rect x="179" y="33" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="189" y="53">TOK_ID</text></a><rect x="287" y="3" width="30" height="32" rx="10"/>
         <rect x="285" y="1" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="295" y="21">::</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="337" y="3" width="66" height="32"/>
            <rect x="335" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="345" y="21">TOK_ID</text></a><rect x="423" y="3" width="26" height="32" rx="10"/>
         <rect x="421" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="431" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#matchbind_list" xlink:title="matchbind_list">
            <rect x="469" y="3" width="112" height="32"/>
            <rect x="467" y="1" width="112" height="32" class="nonterminal"/>
            <text class="nonterminal" x="477" y="21">matchbind_list</text></a><rect x="601" y="3" width="26" height="32" rx="10"/>
         <rect x="599" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="609" y="21">)</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m66 0 h10 m20 0 h10 m0 0 h120 m-150 0 h20 m130 0 h20 m-170 0 q10 0 10 10 m150 0 q0 -10 10 -10 m-160 10 v12 m150 0 v-12 m-150 12 q0 10 10 10 m130 0 q10 0 10 -10 m-140 10 h10 m24 0 h10 m0 0 h10 m66 0 h10 m20 -32 h10 m30 0 h10 m0 0 h10 m66 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m112 0 h10 m0 0 h10 m26 0 h10 m3 0 h-3"/>
         <polygon points="645 17 653 13 653 21"/>
         <polygon points="645 17 637 13 637 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#match_guard_record" title="match_guard_record">match_guard_record</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? '::' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '(' <a href="#matchbind_list" title="matchbind_list">matchbind_list</a> ')'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#iflet" title="iflet">iflet</a></li>
            <li><a href="#match_guard" title="match_guard">match_guard</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="match_guard_item">match_guard_item:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="431" height="69">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="31" y="3" width="66" height="32"/>
            <rect x="29" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_ID</text></a><rect x="137" y="35" width="24" height="32" rx="10"/>
         <rect x="135" y="33" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="53">.</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="181" y="35" width="66" height="32"/>
            <rect x="179" y="33" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="189" y="53">TOK_ID</text></a><rect x="287" y="3" width="30" height="32" rx="10"/>
         <rect x="285" y="1" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="295" y="21">::</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="337" y="3" width="66" height="32"/>
            <rect x="335" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="345" y="21">TOK_ID</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m66 0 h10 m20 0 h10 m0 0 h120 m-150 0 h20 m130 0 h20 m-170 0 q10 0 10 10 m150 0 q0 -10 10 -10 m-160 10 v12 m150 0 v-12 m-150 12 q0 10 10 10 m130 0 q10 0 10 -10 m-140 10 h10 m24 0 h10 m0 0 h10 m66 0 h10 m20 -32 h10 m30 0 h10 m0 0 h10 m66 0 h10 m3 0 h-3"/>
         <polygon points="421 17 429 13 429 21"/>
         <polygon points="421 17 413 13 413 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#match_guard_item" title="match_guard_item">match_guard_item</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? '::' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#iflet" title="iflet">iflet</a></li>
            <li><a href="#match_guard" title="match_guard">match_guard</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="matchbind_list">matchbind_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="185" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#matchbind" xlink:title="matchbind">
            <rect x="51" y="47" width="86" height="32"/>
            <rect x="49" y="45" width="86" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">matchbind</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m86 0 h10 m-126 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m106 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-106 0 h10 m24 0 h10 m0 0 h62 m23 44 h-3"/>
         <polygon points="175 61 183 57 183 65"/>
         <polygon points="175 61 167 57 167 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#matchbind_list" title="matchbind_list">matchbind_list</a></div>
               <div>         ::= <a href="#matchbind" title="matchbind">matchbind</a> ( ',' <a href="#matchbind" title="matchbind">matchbind</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#match_guard_record" title="match_guard_record">match_guard_record</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="matchbind">matchbind:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="125" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="31" y="3" width="66" height="32"/>
            <rect x="29" y="1" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">TOK_ID</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m66 0 h10 m3 0 h-3"/>
         <polygon points="115 17 123 13 123 21"/>
         <polygon points="115 17 107 13 107 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#matchbind" title="matchbind">matchbind</a></div>
               <div>         ::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#matchbind_list" title="matchbind_list">matchbind_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="iflet">iflet:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="809" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="28" height="32" rx="10"/>
         <rect x="29" y="1" width="28" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">if</text>
         <rect x="79" y="3" width="38" height="32" rx="10"/>
         <rect x="77" y="1" width="38" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="87" y="21">let</text>
         <rect x="137" y="3" width="26" height="32" rx="10"/>
         <rect x="135" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="145" y="21">(</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard_record" xlink:title="match_guard_record">
            <rect x="203" y="3" width="152" height="32"/>
            <rect x="201" y="1" width="152" height="32" class="nonterminal"/>
            <text class="nonterminal" x="211" y="21">match_guard_record</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#match_guard_item" xlink:title="match_guard_item">
            <rect x="203" y="47" width="140" height="32"/>
            <rect x="201" y="45" width="140" height="32" class="nonterminal"/>
            <text class="nonterminal" x="211" y="65">match_guard_item</text></a><rect x="395" y="3" width="30" height="32" rx="10"/>
         <rect x="393" y="1" width="30" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="403" y="21">=</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="445" y="3" width="48" height="32"/>
            <rect x="443" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="453" y="21">expr</text></a><rect x="513" y="3" width="26" height="32" rx="10"/>
         <rect x="511" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="521" y="21">)</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="559" y="3" width="48" height="32"/>
            <rect x="557" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="567" y="21">expr</text></a><rect x="647" y="35" width="46" height="32" rx="10"/>
         <rect x="645" y="33" width="46" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="655" y="53">else</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="713" y="35" width="48" height="32"/>
            <rect x="711" y="33" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="721" y="53">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m28 0 h10 m0 0 h10 m38 0 h10 m0 0 h10 m26 0 h10 m20 0 h10 m152 0 h10 m-192 0 h20 m172 0 h20 m-212 0 q10 0 10 10 m192 0 q0 -10 10 -10 m-202 10 v24 m192 0 v-24 m-192 24 q0 10 10 10 m172 0 q10 0 10 -10 m-182 10 h10 m140 0 h10 m0 0 h12 m20 -44 h10 m30 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m48 0 h10 m20 0 h10 m0 0 h124 m-154 0 h20 m134 0 h20 m-174 0 q10 0 10 10 m154 0 q0 -10 10 -10 m-164 10 v12 m154 0 v-12 m-154 12 q0 10 10 10 m134 0 q10 0 10 -10 m-144 10 h10 m46 0 h10 m0 0 h10 m48 0 h10 m23 -32 h-3"/>
         <polygon points="799 17 807 13 807 21"/>
         <polygon points="799 17 791 13 791 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#iflet" title="iflet">iflet</a>    ::= 'if' 'let' '(' ( <a href="#match_guard_record" title="match_guard_record">match_guard_record</a> | <a href="#match_guard_item" title="match_guard_item">match_guard_item</a> ) '=' <a href="#expr" title="expr">expr</a> ')' <a href="#expr" title="expr">expr</a> ( 'else' <a href="#expr" title="expr">expr</a> )?</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="listcomp">listcomp:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="487" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="26" height="32" rx="10"/>
         <rect x="29" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="77" y="3" width="48" height="32"/>
            <rect x="75" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="85" y="21">expr</text></a><rect x="145" y="3" width="26" height="32" rx="10"/>
         <rect x="143" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="153" y="21">|</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#qualifier_list" xlink:title="qualifier_list">
            <rect x="191" y="3" width="98" height="32"/>
            <rect x="189" y="1" width="98" height="32" class="nonterminal"/>
            <text class="nonterminal" x="199" y="21">qualifier_list</text></a><rect x="309" y="3" width="26" height="32" rx="10"/>
         <rect x="307" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="317" y="21">]</text>
         <rect x="355" y="3" width="24" height="32" rx="10"/>
         <rect x="353" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="363" y="21">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="399" y="3" width="60" height="32"/>
            <rect x="397" y="1" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="407" y="21">param</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m26 0 h10 m0 0 h10 m48 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m98 0 h10 m0 0 h10 m26 0 h10 m0 0 h10 m24 0 h10 m0 0 h10 m60 0 h10 m3 0 h-3"/>
         <polygon points="477 17 485 13 485 21"/>
         <polygon points="477 17 469 13 469 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#listcomp" title="listcomp">listcomp</a> ::= '[' <a href="#expr" title="expr">expr</a> '|' <a href="#qualifier_list" title="qualifier_list">qualifier_list</a> ']' ':' <a href="#param" title="param">param</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="qualifier_list">qualifier_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="169" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#qualifier" xlink:title="qualifier">
            <rect x="51" y="47" width="70" height="32"/>
            <rect x="49" y="45" width="70" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">qualifier</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">;</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m70 0 h10 m-110 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m90 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-90 0 h10 m24 0 h10 m0 0 h46 m23 44 h-3"/>
         <polygon points="159 61 167 57 167 65"/>
         <polygon points="159 61 151 57 151 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#qualifier_list" title="qualifier_list">qualifier_list</a></div>
               <div>         ::= <a href="#qualifier" title="qualifier">qualifier</a> ( ';' <a href="#qualifier" title="qualifier">qualifier</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#listcomp" title="listcomp">listcomp</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="qualifier">qualifier:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="141" height="37">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#generator" xlink:title="generator">
            <rect x="31" y="3" width="82" height="32"/>
            <rect x="29" y="1" width="82" height="32" class="nonterminal"/>
            <text class="nonterminal" x="39" y="21">generator</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m82 0 h10 m3 0 h-3"/>
         <polygon points="131 17 139 13 139 21"/>
         <polygon points="131 17 123 13 123 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#qualifier" title="qualifier">qualifier</a></div>
               <div>         ::= <a href="#generator" title="generator">generator</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#qualifier_list" title="qualifier_list">qualifier_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="generator">generator:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="319" height="69">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_ID" xlink:title="TOK_ID">
            <rect x="51" y="35" width="66" height="32"/>
            <rect x="49" y="33" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="53">TOK_ID</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#TOK_IN" xlink:title="TOK_IN">
            <rect x="137" y="35" width="66" height="32"/>
            <rect x="135" y="33" width="66" height="32" class="nonterminal"/>
            <text class="nonterminal" x="145" y="53">TOK_IN</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr" xlink:title="expr">
            <rect x="243" y="3" width="48" height="32"/>
            <rect x="241" y="1" width="48" height="32" class="nonterminal"/>
            <text class="nonterminal" x="251" y="21">expr</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m0 0 h162 m-192 0 h20 m172 0 h20 m-212 0 q10 0 10 10 m192 0 q0 -10 10 -10 m-202 10 v12 m192 0 v-12 m-192 12 q0 10 10 10 m172 0 q10 0 10 -10 m-182 10 h10 m66 0 h10 m0 0 h10 m66 0 h10 m20 -32 h10 m48 0 h10 m3 0 h-3"/>
         <polygon points="309 17 317 13 317 21"/>
         <polygon points="309 17 301 13 301 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#generator" title="generator">generator</a></div>
               <div>         ::= ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#TOK_IN" title="TOK_IN">TOK_IN</a> )? <a href="#expr" title="expr">expr</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#qualifier" title="qualifier">qualifier</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="array_sub_list">array_sub_list:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="183" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 61 1 57 1 65"/>
         <polygon points="17 61 9 57 9 65"/><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#array_sub" xlink:title="array_sub">
            <rect x="51" y="47" width="84" height="32"/>
            <rect x="49" y="45" width="84" height="32" class="nonterminal"/>
            <text class="nonterminal" x="59" y="65">array_sub</text></a><rect x="51" y="3" width="24" height="32" rx="10"/>
         <rect x="49" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">,</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 61 h2 m20 0 h10 m84 0 h10 m-124 0 l20 0 m-1 0 q-9 0 -9 -10 l0 -24 q0 -10 10 -10 m104 44 l20 0 m-20 0 q10 0 10 -10 l0 -24 q0 -10 -10 -10 m-104 0 h10 m24 0 h10 m0 0 h60 m23 44 h-3"/>
         <polygon points="173 61 181 57 181 65"/>
         <polygon points="173 61 165 57 165 65"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#array_sub_list" title="array_sub_list">array_sub_list</a></div>
               <div>         ::= <a href="#array_sub" title="array_sub">array_sub</a> ( ',' <a href="#array_sub" title="array_sub">array_sub</a> )*</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#array" title="array">array</a></li>
            <li><a href="#array_sub" title="array_sub">array_sub</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="array_sub">array_sub:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="301" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="31" y="3" width="26" height="32" rx="10"/>
         <rect x="29" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="39" y="21">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#array_sub_list" xlink:title="array_sub_list">
            <rect x="97" y="3" width="110" height="32"/>
            <rect x="95" y="1" width="110" height="32" class="nonterminal"/>
            <text class="nonterminal" x="105" y="21">array_sub_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="97" y="47" width="74" height="32"/>
            <rect x="95" y="45" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="105" y="65">expr_list</text></a><rect x="247" y="3" width="26" height="32" rx="10"/>
         <rect x="245" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="255" y="21">]</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m0 0 h10 m26 0 h10 m20 0 h10 m110 0 h10 m-150 0 h20 m130 0 h20 m-170 0 q10 0 10 10 m150 0 q0 -10 10 -10 m-160 10 v24 m150 0 v-24 m-150 24 q0 10 10 10 m130 0 q10 0 10 -10 m-140 10 h10 m74 0 h10 m0 0 h36 m20 -44 h10 m26 0 h10 m3 0 h-3"/>
         <polygon points="291 17 299 13 299 21"/>
         <polygon points="291 17 283 13 283 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#array_sub" title="array_sub">array_sub</a></div>
               <div>         ::= '[' ( <a href="#array_sub_list" title="array_sub_list">array_sub_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#array_sub_list" title="array_sub_list">array_sub_list</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="array">array:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="465" height="125">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="26" height="32" rx="10"/>
         <rect x="49" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#array_sub_list" xlink:title="array_sub_list">
            <rect x="117" y="3" width="110" height="32"/>
            <rect x="115" y="1" width="110" height="32" class="nonterminal"/>
            <text class="nonterminal" x="125" y="21">array_sub_list</text></a><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="117" y="47" width="74" height="32"/>
            <rect x="115" y="45" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="125" y="65">expr_list</text></a><rect x="267" y="3" width="26" height="32" rx="10"/>
         <rect x="265" y="1" width="26" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="275" y="21">]</text>
         <rect x="51" y="91" width="36" height="32" rx="10"/>
         <rect x="49" y="89" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="109">{[</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#expr_list" xlink:title="expr_list">
            <rect x="107" y="91" width="74" height="32"/>
            <rect x="105" y="89" width="74" height="32" class="nonterminal"/>
            <text class="nonterminal" x="115" y="109">expr_list</text></a><rect x="201" y="91" width="36" height="32" rx="10"/>
         <rect x="199" y="89" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="209" y="109">]}</text>
         <rect x="333" y="3" width="24" height="32" rx="10"/>
         <rect x="331" y="1" width="24" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="341" y="21">:</text><a xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#param" xlink:title="param">
            <rect x="377" y="3" width="60" height="32"/>
            <rect x="375" y="1" width="60" height="32" class="nonterminal"/>
            <text class="nonterminal" x="385" y="21">param</text></a><path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m26 0 h10 m20 0 h10 m110 0 h10 m-150 0 h20 m130 0 h20 m-170 0 q10 0 10 10 m150 0 q0 -10 10 -10 m-160 10 v24 m150 0 v-24 m-150 24 q0 10 10 10 m130 0 q10 0 10 -10 m-140 10 h10 m74 0 h10 m0 0 h36 m20 -44 h10 m26 0 h10 m-282 0 h20 m262 0 h20 m-302 0 q10 0 10 10 m282 0 q0 -10 10 -10 m-292 10 v68 m282 0 v-68 m-282 68 q0 10 10 10 m262 0 q10 0 10 -10 m-272 10 h10 m36 0 h10 m0 0 h10 m74 0 h10 m0 0 h10 m36 0 h10 m0 0 h56 m20 -88 h10 m24 0 h10 m0 0 h10 m60 0 h10 m3 0 h-3"/>
         <polygon points="455 17 463 13 463 21"/>
         <polygon points="455 17 447 13 447 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#array" title="array">array</a>    ::= ( '[' ( <a href="#array_sub_list" title="array_sub_list">array_sub_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']' | '{[' <a href="#expr_list" title="expr_list">expr_list</a> ']}' ) ':' <a href="#param" title="param">param</a></div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><p xmlns:xhtml="http://www.w3.org/1999/xhtml" style="font-size: 14px; font-weight:bold"><a name="TOK_IN">TOK_IN:</a></p><svg xmlns="http://www.w3.org/2000/svg" width="135" height="81">
         <defs>
            <style type="text/css">
    @namespace "http://www.w3.org/2000/svg";
    .line                 {fill: none; stroke: #332900; stroke-width: 1;}
    .bold-line            {stroke: #141000; shape-rendering: crispEdges; stroke-width: 2;}
    .thin-line            {stroke: #1F1800; shape-rendering: crispEdges}
    .filled               {fill: #332900; stroke: none;}
    text.terminal         {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #141000;
                            font-weight: bold;
                          }
    text.nonterminal      {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1A1400;
                            font-weight: normal;
                          }
    text.regexp           {font-family: Verdana, Sans-serif;
                            font-size: 12px;
                            fill: #1F1800;
                            font-weight: normal;
                          }
    rect, circle, polygon {fill: #332900; stroke: #332900;}
    rect.terminal         {fill: #FFDB4D; stroke: #332900; stroke-width: 1;}
    rect.nonterminal      {fill: #FFEC9E; stroke: #332900; stroke-width: 1;}
    rect.text             {fill: none; stroke: none;}
    polygon.regexp        {fill: #FFF4C7; stroke: #332900; stroke-width: 1;}
  </style>
         </defs>
         <polygon points="9 17 1 13 1 21"/>
         <polygon points="17 17 9 13 9 21"/>
         <rect x="51" y="3" width="32" height="32" rx="10"/>
         <rect x="49" y="1" width="32" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="21">in</text>
         <rect x="51" y="47" width="36" height="32" rx="10"/>
         <rect x="49" y="45" width="36" height="32" class="terminal" rx="10"/>
         <text class="terminal" x="59" y="65">&lt;-</text>
         <path xmlns:svg="http://www.w3.org/2000/svg" class="line" d="m17 17 h2 m20 0 h10 m32 0 h10 m0 0 h4 m-76 0 h20 m56 0 h20 m-96 0 q10 0 10 10 m76 0 q0 -10 10 -10 m-86 10 v24 m76 0 v-24 m-76 24 q0 10 10 10 m56 0 q10 0 10 -10 m-66 10 h10 m36 0 h10 m23 -44 h-3"/>
         <polygon points="125 17 133 13 133 21"/>
         <polygon points="125 17 117 13 117 21"/></svg><p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <div class="ebnf"><code>
               <div><a href="#TOK_IN" title="TOK_IN">TOK_IN</a>   ::= 'in'</div>
               <div>           | '&lt;-'</div></code></div>
      </p>
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#generator" title="generator">generator</a></li>
         </ul>
      </p><br xmlns:xhtml="http://www.w3.org/1999/xhtml" /><hr xmlns:xhtml="http://www.w3.org/1999/xhtml" />
      <p xmlns:xhtml="http://www.w3.org/1999/xhtml">
         <table border="0" class="signature">
            <tr>
               <td style="width: 100%"> </td>
               <td valign="top">
                  <nobr class="signature">... generated by <a name="Railroad-Diagram-Generator" class="signature" title="https://www.bottlecaps.de/rr/ui" href="https://www.bottlecaps.de/rr/ui" target="_blank">RR - Railroad Diagram Generator</a></nobr>
               </td>
               <td><a name="Railroad-Diagram-Generator" title="https://www.bottlecaps.de/rr/ui" href="https://www.bottlecaps.de/rr/ui" target="_blank"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16">
                        <g transform="scale(0.178)">
                           <circle cx="45" cy="45" r="45" style="stroke:none; fill:#FFCC00"/>
                           <circle cx="45" cy="45" r="42" style="stroke:#332900; stroke-width:2px; fill:#FFCC00"/>
                           <line x1="15" y1="15" x2="75" y2="75" stroke="#332900" style="stroke-width:9px;"/>
                           <line x1="15" y1="75" x2="75" y2="15" stroke="#332900" style="stroke-width:9px;"/>
                           <text x="7" y="54" style="font-size:26px; font-family:Arial, Sans-serif; font-weight:bold; fill: #332900">R</text>
                           <text x="64" y="54" style="font-size:26px; font-family:Arial, Sans-serif; font-weight:bold; fill: #332900">R</text>
                        </g></svg></a></td>
            </tr>
         </table>
      </p>
</div>

