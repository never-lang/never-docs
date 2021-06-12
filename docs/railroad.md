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
    a.button, #tabs
    {
      padding: 0.25em 0.5em;
      border: 1px solid #806600;
      background: #F1E8C6;
      color: #806600;
      text-decoration: none;
      font-weight: bold;
    }
    a.button:hover, #tabs a:hover
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
    #tabs
    {
      list-style: none;
      margin-left: 5px;
      display: inline;
    }
    #tabs a
    {
      border-bottom: 1px solid #0F0C00;
    }
    #tabs a.active
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
  </style>
      <p style="font-size: 14px; font-weight:bold"><a name="start">start:</a></p><img border="0" src="../railroad/start.png" height="81" width="199" usemap="#start.map"><map name="start.map"><area shape="rect" coords="49,1,105,33" href="#never" title="never"><area shape="rect" coords="49,45,149,77" href="#module_decl" title="module_decl"></map><p>
         <div class="ebnf"><code><div><a href="#start" title="start">start</a>&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#never" title="never">never</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#module_decl" title="module_decl">module_decl</a></div></code></div>
         </p>
      <p>no references</p><br><p style="font-size: 14px; font-weight:bold"><a name="module_decl">module_decl:</a></p><img border="0" src="../railroad/module_decl.png" height="81" width="427" usemap="#module_decl.map"><map name="module_decl.map"><area shape="rect" coords="139,1,205,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="273,1,329,33" href="#never" title="never"><area shape="rect" coords="49,45,185,77" href="#TOK_MODULE_REF" title="TOK_MODULE_REF"></map><p>
         
         <div class="ebnf"><code><div><a href="#module_decl" title="module_decl">module_decl</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'module' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#never" title="never">never</a> '}'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_MODULE_REF" title="TOK_MODULE_REF">TOK_MODULE_REF</a></div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#start" title="start">start</a></li>
            <li><a href="#use" title="use">use</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="never">never:</a></p><img border="0" src="../railroad/never.png" height="113" width="431" usemap="#never.map"><map name="never.map"><area shape="rect" coords="49,33,119,65" href="#use_list" title="use_list"><area shape="rect" coords="179,1,251,33" href="#decl_list" title="decl_list"><area shape="rect" coords="291,33,361,65" href="#seq_list" title="seq_list"><area shape="rect" coords="179,77,249,109" href="#seq_list" title="seq_list"></map><p>
         <div class="ebnf"><code><div><a href="#never" title="never">never</a>&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#use_list" title="use_list">use_list</a>? ( <a href="#decl_list" title="decl_list">decl_list</a> <a href="#seq_list" title="seq_list">seq_list</a>? | <a href="#seq_list" title="seq_list">seq_list</a> )</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#module_decl" title="module_decl">module_decl</a></li>
            <li><a href="#start" title="start">start</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="use_list">use_list:</a></p><img border="0" src="../railroad/use_list.png" height="53" width="141" usemap="#use_list.map"><map name="use_list.map"><area shape="rect" coords="49,17,91,49" href="#use" title="use"></map><p> 
         <div class="ebnf"><code><div><a href="#use_list" title="use_list">use_list</a>&nbsp;::= <a href="#use" title="use">use</a>+</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#never" title="never">never</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="use">use:</a></p><img border="0" src="../railroad/use.png" height="37" width="379" usemap="#use.map"><map name="use.map"><area shape="rect" coords="93,1,229,33" href="#TOK_NUM_STRING" title="TOK_NUM_STRING"><area shape="rect" coords="249,1,349,33" href="#module_decl" title="module_decl"></map><p>
         
         <div class="ebnf"><code><div><a href="#use" title="use">use</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'use' <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a> <a href="#module_decl" title="module_decl">module_decl</a></div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#use_list" title="use_list">use_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="decl_list">decl_list:</a></p><img border="0" src="../railroad/decl_list.png" height="53" width="145" usemap="#decl_list.map"><map name="decl_list.map"><area shape="rect" coords="49,17,95,49" href="#decl" title="decl"></map><p>
         
         <div class="ebnf"><code><div><a href="#decl_list" title="decl_list">decl_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#decl" title="decl">decl</a>+</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#never" title="never">never</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="decl">decl:</a></p><img border="0" src="../railroad/decl.png" height="81" width="183" usemap="#decl.map"><map name="decl.map"><area shape="rect" coords="49,1,109,33" href="#record" title="record"><area shape="rect" coords="49,45,133,77" href="#enumtype" title="enumtype"></map><p>
         <div class="ebnf"><code><div><a href="#decl" title="decl">decl</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#record" title="record">record</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#enumtype" title="enumtype">enumtype</a></div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#decl_list" title="decl_list">decl_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="record">record:</a></p><img border="0" src="../railroad/record.png" height="37" width="457" usemap="#record.map"><map name="record.map"><area shape="rect" coords="29,1,133,33" href="#TOK_RECORD" title="TOK_RECORD"><area shape="rect" coords="153,1,219,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="287,1,379,33" href="#param_seq" title="param_seq"></map><p>
         
         <div class="ebnf"><code><div><a href="#record" title="record">record</a>&nbsp;&nbsp;&nbsp;::= <a href="#TOK_RECORD" title="TOK_RECORD">TOK_RECORD</a> <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#param_seq" title="param_seq">param_seq</a> '}'</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#decl" title="decl">decl</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="enumtype">enumtype:</a></p><img border="0" src="../railroad/enumtype.png" height="37" width="401" usemap="#enumtype.map"><map name="enumtype.map"><area shape="rect" coords="107,1,173,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="241,1,323,33" href="#enum_list" title="enum_list"></map><p>
         
         <div class="ebnf"><code><div><a href="#enumtype" title="enumtype">enumtype</a>&nbsp;::= 'enum' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '{' <a href="#enum_list" title="enum_list">enum_list</a> '}'</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#decl" title="decl">decl</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="enum_list">enum_list:</a></p><img border="0" src="../railroad/enum_list.png" height="81" width="191" usemap="#enum_list.map"><map name="enum_list.map"><area shape="rect" coords="49,45,141,77" href="#enum_item" title="enum_item"></map><p>
         <div class="ebnf"><code><div><a href="#enum_list" title="enum_list">enum_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#enum_item" title="enum_item">enum_item</a> ( ',' <a href="#enum_item" title="enum_item">enum_item</a> )*</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#enumtype" title="enumtype">enumtype</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="enum_item">enum_item:</a></p><img border="0" src="../railroad/enum_item.png" height="113" width="373" usemap="#enum_item.map"><map name="enum_item.map"><area shape="rect" coords="29,1,95,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="185,33,233,65" href="#expr" title="expr"><area shape="rect" coords="183,77,275,109" href="#param_seq" title="param_seq"></map><p>
         
         <div class="ebnf"><code><div><a href="#enum_item" title="enum_item">enum_item</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '=' <a href="#expr" title="expr">expr</a> | '{' <a href="#param_seq" title="param_seq">param_seq</a> '}' )?</div></code></div>
         </p>
      <p>referenced by:
         <ul>
            <li><a href="#enum_list" title="enum_list">enum_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="func">func:</a></p><img border="0" src="../railroad/func.png" height="157" width="549" usemap="#func.map"><map name="func.map"><area shape="rect" coords="137,1,203,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="223,1,273,33" href="#error" title="error"><area shape="rect" coords="137,45,217,77" href="#func_decl" title="func_decl"><area shape="rect" coords="237,45,323,77" href="#func_body" title="func_body"><area shape="rect" coords="363,77,459,109" href="#func_except" title="func_except"><area shape="rect" coords="133,121,269,153" href="#TOK_NUM_STRING" title="TOK_NUM_STRING"><area shape="rect" coords="357,121,437,153" href="#func_decl" title="func_decl"></map><p>
         
         <div class="ebnf"><code><div><a href="#func" title="func">func</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'func' ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#error" title="error">error</a> | <a href="#func_decl" title="func_decl">func_decl</a> <a href="#func_body" title="func_body">func_body</a> <a href="#func_except" title="func_except">func_except</a>? )</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'extern' <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a> 'func' <a href="#func_decl" title="func_decl">func_decl</a></div></code></div></p>
      
      <p>referenced by:
         <ul>
            <li><a href="#expr" title="expr">expr</a></li>
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="func_except">func_except:</a></p><img border="0" src="../railroad/func_except.png" height="113" width="331" usemap="#func_except.map"><map name="func_except.map"><area shape="rect" coords="49,1,137,33" href="#except_list" title="except_list"><area shape="rect" coords="177,33,261,65" href="#except_all" title="except_all"><area shape="rect" coords="49,77,133,109" href="#except_all" title="except_all"></map><p>
         
         <div class="ebnf"><code><div><a href="#func_except" title="func_except">func_except</a></div> <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#except_list" title="except_list">except_list</a> <a href="#except_all" title="except_all">except_all</a>?</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#except_all" title="except_all">except_all</a></div></code></div>
         </p>
      
      <p>referenced by:
         <ul>
            <li><a href="#func" title="func">func</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="except_list">except_list:</a></p><img border="0" src="../railroad/except_list.png" height="53" width="161" usemap="#except_list.map"><map name="except_list.map"><area shape="rect" coords="49,17,111,49" href="#except" title="except"></map><p>
         
         <div class="ebnf"><code><div><a href="#except_list" title="except_list">except_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#except" title="except">except</a>+</div></code></div>
         </p>
      
      <p>referenced by:
         <ul>
            <li><a href="#func_except" title="func_except">func_except</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="except">except:</a></p><img border="0" src="../railroad/except.png" height="37" width="355" usemap="#except.map"><map name="except.map"><area shape="rect" coords="151,1,217,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="283,1,325,33" href="#seq" title="seq"></map><p>
         
         <div class="ebnf"><code><div><a href="#except" title="except">except</a>&nbsp;&nbsp;&nbsp;::= 'catch' '(' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ')' <a href="#seq" title="seq">seq</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#except_list" title="except_list">except_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="except_all">except_all:</a></p><img border="0" src="../railroad/except_all.png" height="37" width="177" usemap="#except_all.map"><map name="except_all.map"><area shape="rect" coords="105,1,147,33" href="#seq" title="seq"></map><p>
         
         <div class="ebnf"><code><div><a href="#except_all" title="except_all">except_all</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'catch' <a href="#seq" title="seq">seq</a></div></code></div></p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#func_except" title="func_except">func_except</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="func_body">func_body:</a></p><img border="0" src="../railroad/func_body.png" height="81" width="175" usemap="#func_body.map"><map name="func_body.map"><area shape="rect" coords="49,45,91,77" href="#seq" title="seq"></map><p>
         
         <div class="ebnf"><code><div><a href="#func_body" title="func_body">func_body</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= '{' '}'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#seq" title="seq">seq</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#func" title="func">func</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="func_decl">func_decl:</a></p><img border="0" src="../railroad/func_decl.png" height="69" width="539" usemap="#func_decl.map"><map name="func_decl.map"><area shape="rect" coords="49,33,115,65" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="221,33,307,65" href="#param_list" title="param_list"><area shape="rect" coords="449,1,509,33" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#func_decl" title="func_decl">func_decl</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a>? '(' <a href="#param_list" title="param_list">param_list</a>? ')' '-&gt;' <a href="#param" title="param">param</a></div></code></div>
         </p>
      
      <p>referenced by:
         <ul>
            <li><a href="#func" title="func">func</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="param_seq">param_seq:</a></p><img border="0" src="../railroad/param_seq.png" height="53" width="203" usemap="#param_seq.map"><map name="param_seq.map"><area shape="rect" coords="49,17,109,49" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#param_seq" title="param_seq">param_seq</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= ( <a href="#param" title="param">param</a> ';' )+</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#enum_item" title="enum_item">enum_item</a></li>
            
            <li><a href="#record" title="record">record</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="param_list">param_list:</a></p><img border="0" src="../railroad/param_list.png" height="81" width="159" usemap="#param_list.map"><map name="param_list.map"><area shape="rect" coords="49,45,109,77" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#param_list" title="param_list">param_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#param" title="param">param</a> ( ',' <a href="#param" title="param">param</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#func_decl" title="func_decl">func_decl</a></li>
            
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            
            <li><a href="#touple" title="touple">touple</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="param">param:</a></p><img border="0" src="../railroad/param.png" height="113" width="255" usemap="#param.map"><map name="param.map"><area shape="rect" coords="131,1,225,33" href="#param_decl" title="param_decl"></map><p>
         
         <div class="ebnf"><code><div><a href="#param" title="param">param</a>&nbsp;&nbsp;&nbsp;&nbsp;::= ( 'var' | 'let' )? <a href="#param_decl" title="param_decl">param_decl</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#array" title="array">array</a></li>
            
            <li><a href="#func_decl" title="func_decl">func_decl</a></li>
            
            <li><a href="#listcomp" title="listcomp">listcomp</a></li>
            
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            
            <li><a href="#param_list" title="param_list">param_list</a></li>
            
            <li><a href="#param_seq" title="param_seq">param_seq</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="param_decl">param_decl:</a></p><img border="0" src="../railroad/param_decl.png" height="1397" width="635" usemap="#param_decl.map"><map name="param_decl.map"><area shape="rect" coords="49,1,115,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="265,33,351,65" href="#param_list" title="param_list"><area shape="rect" coords="219,77,285,109" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="369,109,435,141" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="221,537,307,569" href="#param_list" title="param_list"><area shape="rect" coords="449,505,509,537" href="#param" title="param"><area shape="rect" coords="221,581,335,613" href="#range_dim_list" title="range_dim_list"><area shape="rect" coords="465,581,525,613" href="#param" title="param"><area shape="rect" coords="221,669,291,701" href="#dim_list" title="dim_list"><area shape="rect" coords="401,669,461,701" href="#param" title="param"><area shape="rect" coords="199,713,265,745" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="115,757,201,789" href="#param_list" title="param_list"><area shape="rect" coords="343,789,403,821" href="#param" title="param"><area shape="rect" coords="217,833,277,865" href="#param" title="param"><area shape="rect" coords="115,877,229,909" href="#range_dim_list" title="range_dim_list"><area shape="rect" coords="359,877,419,909" href="#param" title="param"><area shape="rect" coords="115,965,185,997" href="#dim_list" title="dim_list"><area shape="rect" coords="295,965,355,997" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#param_decl" title="param_decl">param_decl</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( ':' ( '(' <a href="#param_list" title="param_list">param_list</a> ')' | <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? | 'c_ptr' | 'string' | 'char' | 'double' | 'float' | 'long' | 'int' | 'bool' ) | '(' <a href="#param_list" title="param_list">param_list</a>? ')' '-&gt;' <a href="#param" title="param">param</a> | '[' ( <a href="#range_dim_list" title="range_dim_list">range_dim_list</a> ']' ':' ( <a href="#param" title="param">param</a> | 'range' ) | <a href="#dim_list" title="dim_list">dim_list</a> ']' ':' <a href="#param" title="param">param</a> ) | '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )?</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| '(' ( <a href="#param_list" title="param_list">param_list</a> ')' ( '-&gt;' <a href="#param" title="param">param</a> )? | ')' '-&gt;' <a href="#param" title="param">param</a> )</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| '[' ( <a href="#range_dim_list" title="range_dim_list">range_dim_list</a> ']' ':' ( <a href="#param" title="param">param</a> | 'range' ) | <a href="#dim_list" title="dim_list">dim_list</a> ']' ':' <a href="#param" title="param">param</a> )</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'c_ptr'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'void'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'string'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'char'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'double'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'float'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'long'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'int'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'bool'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#param" title="param">param</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="range_dim_list">range_dim_list:</a></p><img border="0" src="../railroad/range_dim_list.png" height="81" width="187" usemap="#range_dim_list.map"><map name="range_dim_list.map"><area shape="rect" coords="49,45,137,77" href="#range_dim" title="range_dim"></map><p>
         
         <div class="ebnf"><code><div><a href="#range_dim_list" title="range_dim_list">range_dim_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#range_dim" title="range_dim">range_dim</a> ( ',' <a href="#range_dim" title="range_dim">range_dim</a> )*</div></code></div></p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="range_dim">range_dim:</a></p><img border="0" src="../railroad/range_dim.png" height="81" width="299" usemap="#range_dim.map"><map name="range_dim.map"><area shape="rect" coords="49,1,115,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="183,1,249,33" href="#TOK_ID" title="TOK_ID"></map><p>
         
         <div class="ebnf"><code><div><a href="#range_dim" title="range_dim">range_dim</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '..' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| '..'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#range_dim_list" title="range_dim_list">range_dim_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="dim_list">dim_list:</a></p><img border="0" src="../railroad/dim_list.png" height="81" width="141" usemap="#dim_list.map"><map name="dim_list.map"><area shape="rect" coords="49,45,91,77" href="#dim" title="dim"></map><p>
         
         <div class="ebnf"><code><div><a href="#dim_list" title="dim_list">dim_list</a>&nbsp;::= <a href="#dim" title="dim">dim</a> ( ',' <a href="#dim" title="dim">dim</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#param_decl" title="param_decl">param_decl</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="dim">dim:</a></p><img border="0" src="../railroad/dim.png" height="37" width="125" usemap="#dim.map"><map name="dim.map"><area shape="rect" coords="29,1,95,33" href="#TOK_ID" title="TOK_ID"></map><p>
         
         <div class="ebnf"><code><div><a href="#dim" title="dim">dim</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#dim_list" title="dim_list">dim_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="expr">expr:</a></p><img border="0" src="../railroad/expr.png" height="2453" width="709" usemap="#expr.map"><map name="expr.map"><area shape="rect" coords="95,1,245,33" href="#expr_range_dim_list" title="expr_range_dim_list"><area shape="rect" coords="49,45,109,77" href="#touple" title="touple"><area shape="rect" coords="49,89,97,121" href="#expr" title="expr"><area shape="rect" coords="227,89,293,121" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="203,221,251,253" href="#expr" title="expr"><area shape="rect" coords="335,177,383,209" href="#expr" title="expr"><area shape="rect" coords="203,1133,277,1165" href="#expr_list" title="expr_list"><area shape="rect" coords="203,1177,353,1209" href="#expr_range_dim_list" title="expr_range_dim_list"><area shape="rect" coords="203,1221,277,1253" href="#expr_list" title="expr_list"><area shape="rect" coords="131,1265,179,1297" href="#expr" title="expr"><area shape="rect" coords="267,1297,397,1329" href="#match_guard_list" title="match_guard_list"><area shape="rect" coords="49,1341,93,1373" href="#iflet" title="iflet"><area shape="rect" coords="213,1385,279,1417" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="299,1385,365,1417" href="#TOK_IN" title="TOK_IN"><area shape="rect" coords="213,1429,261,1461" href="#expr" title="expr"><area shape="rect" coords="325,1429,373,1461" href="#expr" title="expr"><area shape="rect" coords="477,1385,525,1417" href="#expr" title="expr"><area shape="rect" coords="163,1649,211,1681" href="#expr" title="expr"><area shape="rect" coords="297,1681,345,1713" href="#expr" title="expr"><area shape="rect" coords="611,1385,659,1417" href="#expr" title="expr"><area shape="rect" coords="125,1757,173,1789" href="#expr" title="expr"><area shape="rect" coords="335,1725,383,1757" href="#expr" title="expr"><area shape="rect" coords="49,1801,91,1833" href="#seq" title="seq"><area shape="rect" coords="107,1845,153,1877" href="#func" title="func"><area shape="rect" coords="49,1889,121,1921" href="#listcomp" title="listcomp"><area shape="rect" coords="49,1933,101,1965" href="#array" title="array"><area shape="rect" coords="49,2065,185,2097" href="#TOK_NUM_STRING" title="TOK_NUM_STRING"><area shape="rect" coords="49,2109,171,2141" href="#TOK_NUM_CHAR" title="TOK_NUM_CHAR"><area shape="rect" coords="49,2153,189,2185" href="#TOK_NUM_DOUBLE" title="TOK_NUM_DOUBLE"><area shape="rect" coords="49,2197,175,2229" href="#TOK_NUM_FLOAT" title="TOK_NUM_FLOAT"><area shape="rect" coords="49,2241,173,2273" href="#TOK_NUM_LONG" title="TOK_NUM_LONG"><area shape="rect" coords="49,2285,159,2317" href="#TOK_NUM_INT" title="TOK_NUM_INT"><area shape="rect" coords="49,2329,115,2361" href="#TOK_ID" title="TOK_ID"></map><p>
         
         <div class="ebnf"><code><div><a href="#expr" title="expr">expr</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= '[' <a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a> ']'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#touple" title="touple">touple</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#expr" title="expr">expr</a> ( ( '.' | '::' ) <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> | ( '=' | '?' <a href="#expr" title="expr">expr</a> ':' | '&gt;&gt;&gt;' | '&lt;&lt;&lt;' | '^^^' | '|||' | '&amp;&amp;&amp;' | '|&gt;' | '||' | '&amp;&amp;' | '!=' | '==' | '&gt;=' | '&gt;' | '&lt;=' | '&lt;' | '%' | '/' | '*' | '-' | '+' ) <a href="#expr" title="expr">expr</a> | '(' <a href="#expr_list" title="expr_list">expr_list</a>? ')' | '[' ( <a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']' )</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'match' <a href="#expr" title="expr">expr</a> '{' <a href="#match_guard_list" title="match_guard_list">match_guard_list</a>? '}'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#iflet" title="iflet">iflet</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| ( ( 'for' '(' ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#TOK_IN" title="TOK_IN">TOK_IN</a> | <a href="#expr" title="expr">expr</a> ';' <a href="#expr" title="expr">expr</a> ';' ) | 'while' '(' ) <a href="#expr" title="expr">expr</a> ')' | '~~~' | '!' | '-' | 'if' '(' <a href="#expr" title="expr">expr</a> ')' ( <a href="#expr" title="expr">expr</a> 'else' )? ) <a href="#expr" title="expr">expr</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| ( 'do' <a href="#expr" title="expr">expr</a> 'while' )? '(' <a href="#expr" title="expr">expr</a> ')'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#seq" title="seq">seq</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'let' <a href="#func" title="func">func</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#listcomp" title="listcomp">listcomp</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#array" title="array">array</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'c_null'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'nil'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_STRING" title="TOK_NUM_STRING">TOK_NUM_STRING</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_CHAR" title="TOK_NUM_CHAR">TOK_NUM_CHAR</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_DOUBLE" title="TOK_NUM_DOUBLE">TOK_NUM_DOUBLE</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_FLOAT" title="TOK_NUM_FLOAT">TOK_NUM_FLOAT</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_LONG" title="TOK_NUM_LONG">TOK_NUM_LONG</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_NUM_INT" title="TOK_NUM_INT">TOK_NUM_INT</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'false'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 'true'</div></code></div>
         </p>
      
      <p>referenced by:
         
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
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="expr_range_dim_list">expr_range_dim_list:</a></p><img border="0" src="../railroad/expr_range_dim_list.png" height="81" width="223" usemap="#expr_range_dim_list.map"><map name="expr_range_dim_list.map"><area shape="rect" coords="49,45,173,77" href="#expr_range_dim" title="expr_range_dim"></map><p>
         
         <div class="ebnf"><code><div><a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a> ( ',' <a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="expr_range_dim">expr_range_dim:</a></p><img border="0" src="../railroad/expr_range_dim.png" height="37" width="223" usemap="#expr_range_dim.map"><map name="expr_range_dim.map"><area shape="rect" coords="29,1,77,33" href="#expr" title="expr"><area shape="rect" coords="145,1,193,33" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#expr_range_dim" title="expr_range_dim">expr_range_dim</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#expr" title="expr">expr</a> '..' <a href="#expr" title="expr">expr</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr_range_dim_list" title="expr_range_dim_list">expr_range_dim_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="seq">seq:</a></p><img border="0" src="../railroad/seq.png" height="37" width="225" usemap="#seq.map"><map name="seq.map"><area shape="rect" coords="77,1,147,33" href="#seq_list" title="seq_list"></map><p>
         
         <div class="ebnf"><code><div><a href="#seq" title="seq">seq</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= '{' <a href="#seq_list" title="seq_list">seq_list</a> '}'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#except" title="except">except</a></li>
            
            <li><a href="#except_all" title="except_all">except_all</a></li>
            
            <li><a href="#expr" title="expr">expr</a></li>
            
            <li><a href="#func_body" title="func_body">func_body</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="seq_list">seq_list:</a></p><img border="0" src="../railroad/seq_list.png" height="245" width="419" usemap="#seq_list.map"><map name="seq_list.map"><area shape="rect" coords="49,17,97,49" href="#expr" title="expr"><area shape="rect" coords="49,61,95,93" href="#func" title="func"><area shape="rect" coords="49,105,89,137" href="#var" title="var"><area shape="rect" coords="49,149,85,181" href="#let" title="let"><area shape="rect" coords="261,17,309,49" href="#expr" title="expr"><area shape="rect" coords="261,61,307,93" href="#func" title="func"><area shape="rect" coords="261,105,301,137" href="#var" title="var"><area shape="rect" coords="261,149,297,181" href="#let" title="let"><area shape="rect" coords="197,193,243,225" href="#func" title="func"></map><p>
         
         <div class="ebnf"><code><div><a href="#seq_list" title="seq_list">seq_list</a>&nbsp;::= ( <a href="#expr" title="expr">expr</a> | <a href="#func" title="func">func</a> | <a href="#var" title="var">var</a> | <a href="#let" title="let">let</a> ) ( ';' ( <a href="#expr" title="expr">expr</a> | <a href="#func" title="func">func</a> | <a href="#var" title="var">var</a> | <a href="#let" title="let">let</a> ) | <a href="#func" title="func">func</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#never" title="never">never</a></li>
            
            <li><a href="#seq" title="seq">seq</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="var">var:</a></p><img border="0" src="../railroad/var.png" height="37" width="305" usemap="#var.map"><map name="var.map"><area shape="rect" coords="91,1,157,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="227,1,275,33" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#var" title="var">var</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'var' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '=' <a href="#expr" title="expr">expr</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="let">let:</a></p><img border="0" src="../railroad/let.png" height="37" width="301" usemap="#let.map"><map name="let.map"><area shape="rect" coords="87,1,153,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="223,1,271,33" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#let" title="let">let</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= 'let' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '=' <a href="#expr" title="expr">expr</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#seq_list" title="seq_list">seq_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="expr_list">expr_list:</a></p><img border="0" src="../railroad/expr_list.png" height="81" width="147" usemap="#expr_list.map"><map name="expr_list.map"><area shape="rect" coords="49,45,97,77" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#expr_list" title="expr_list">expr_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#expr" title="expr">expr</a> ( ',' <a href="#expr" title="expr">expr</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#array" title="array">array</a></li>
            
            <li><a href="#array_sub" title="array_sub">array_sub</a></li>
            
            <li><a href="#expr" title="expr">expr</a></li>
            
            <li><a href="#touple" title="touple">touple</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="touple">touple:</a></p><img border="0" src="../railroad/touple.png" height="69" width="619" usemap="#touple.map"><map name="touple.map"><area shape="rect" coords="75,1,123,33" href="#expr" title="expr"><area shape="rect" coords="207,33,281,65" href="#expr_list" title="expr_list"><area shape="rect" coords="457,1,543,33" href="#param_list" title="param_list"></map><p>
         
         <div class="ebnf"><code><div><a href="#touple" title="touple">touple</a>&nbsp;&nbsp;&nbsp;::= '(' <a href="#expr" title="expr">expr</a> ',' <a href="#expr_list" title="expr_list">expr_list</a>? ')' ':' '(' <a href="#param_list" title="param_list">param_list</a> ')'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="match_guard_list">match_guard_list:</a></p><img border="0" src="../railroad/match_guard_list.png" height="53" width="247" usemap="#match_guard_list.map"><map name="match_guard_list.map"><area shape="rect" coords="49,17,153,49" href="#match_guard" title="match_guard"></map><p>
         
         <div class="ebnf"><code><div><a href="#match_guard_list" title="match_guard_list">match_guard_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= ( <a href="#match_guard" title="match_guard">match_guard</a> ';' )+</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="match_guard">match_guard:</a></p><img border="0" src="../railroad/match_guard.png" height="125" width="375" usemap="#match_guard.map"><map name="match_guard.map"><area shape="rect" coords="49,45,201,77" href="#match_guard_record" title="match_guard_record"><area shape="rect" coords="49,89,189,121" href="#match_guard_item" title="match_guard_item"><area shape="rect" coords="297,1,345,33" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#match_guard" title="match_guard">match_guard</a></div> <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= ( 'else' | <a href="#match_guard_record" title="match_guard_record">match_guard_record</a> | <a href="#match_guard_item" title="match_guard_item">match_guard_item</a> ) '-&gt;' <a href="#expr" title="expr">expr</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#match_guard_list" title="match_guard_list">match_guard_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="match_guard_record">match_guard_record:</a></p><img border="0" src="../railroad/match_guard_record.png" height="69" width="655" usemap="#match_guard_record.map"><map name="match_guard_record.map"><area shape="rect" coords="29,1,95,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="179,33,245,65" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="335,1,401,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="467,1,579,33" href="#matchbind_list" title="matchbind_list"></map><p>
         
         <div class="ebnf"><code><div><a href="#match_guard_record" title="match_guard_record">match_guard_record</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? '::' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> '(' <a href="#matchbind_list" title="matchbind_list">matchbind_list</a> ')'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#iflet" title="iflet">iflet</a></li>
            
            <li><a href="#match_guard" title="match_guard">match_guard</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="match_guard_item">match_guard_item:</a></p><img border="0" src="../railroad/match_guard_item.png" height="69" width="431" usemap="#match_guard_item.map"><map name="match_guard_item.map"><area shape="rect" coords="29,1,95,33" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="179,33,245,65" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="335,1,401,33" href="#TOK_ID" title="TOK_ID"></map><p>
         
         <div class="ebnf"><code><div><a href="#match_guard_item" title="match_guard_item">match_guard_item</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> ( '.' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> )? '::' <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#iflet" title="iflet">iflet</a></li>
            
            <li><a href="#match_guard" title="match_guard">match_guard</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="matchbind_list">matchbind_list:</a></p><img border="0" src="../railroad/matchbind_list.png" height="81" width="185" usemap="#matchbind_list.map"><map name="matchbind_list.map"><area shape="rect" coords="49,45,135,77" href="#matchbind" title="matchbind"></map><p>
         
         <div class="ebnf"><code><div><a href="#matchbind_list" title="matchbind_list">matchbind_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#matchbind" title="matchbind">matchbind</a> ( ',' <a href="#matchbind" title="matchbind">matchbind</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#match_guard_record" title="match_guard_record">match_guard_record</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="matchbind">matchbind:</a></p><img border="0" src="../railroad/matchbind.png" height="37" width="125" usemap="#matchbind.map"><map name="matchbind.map"><area shape="rect" coords="29,1,95,33" href="#TOK_ID" title="TOK_ID"></map><p>
         
         <div class="ebnf"><code><div><a href="#matchbind" title="matchbind">matchbind</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#TOK_ID" title="TOK_ID">TOK_ID</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#matchbind_list" title="matchbind_list">matchbind_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="iflet">iflet:</a></p><img border="0" src="../railroad/iflet.png" height="81" width="809" usemap="#iflet.map"><map name="iflet.map"><area shape="rect" coords="201,1,353,33" href="#match_guard_record" title="match_guard_record"><area shape="rect" coords="201,45,341,77" href="#match_guard_item" title="match_guard_item"><area shape="rect" coords="443,1,491,33" href="#expr" title="expr"><area shape="rect" coords="557,1,605,33" href="#expr" title="expr"><area shape="rect" coords="711,33,759,65" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#iflet" title="iflet">iflet</a>&nbsp;&nbsp;&nbsp;&nbsp;::= 'if' 'let' '(' ( <a href="#match_guard_record" title="match_guard_record">match_guard_record</a> | <a href="#match_guard_item" title="match_guard_item">match_guard_item</a> ) '=' <a href="#expr" title="expr">expr</a> ')' <a href="#expr" title="expr">expr</a> ( 'else' <a href="#expr" title="expr">expr</a> )?</div></code></div> </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="listcomp">listcomp:</a></p><img border="0" src="../railroad/listcomp.png" height="37" width="487" usemap="#listcomp.map"><map name="listcomp.map"><area shape="rect" coords="75,1,123,33" href="#expr" title="expr"><area shape="rect" coords="189,1,287,33" href="#qualifier_list" title="qualifier_list"><area shape="rect" coords="397,1,457,33" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#listcomp" title="listcomp">listcomp</a>&nbsp;::= '[' <a href="#expr" title="expr">expr</a> '|' <a href="#qualifier_list" title="qualifier_list">qualifier_list</a> ']' ':' <a href="#param" title="param">param</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="qualifier_list">qualifier_list:</a></p><img border="0" src="../railroad/qualifier_list.png" height="81" width="169" usemap="#qualifier_list.map"><map name="qualifier_list.map"><area shape="rect" coords="49,45,119,77" href="#qualifier" title="qualifier"></map><p>
         
         <div class="ebnf"><code><div><a href="#qualifier_list" title="qualifier_list">qualifier_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#qualifier" title="qualifier">qualifier</a> ( ';' <a href="#qualifier" title="qualifier">qualifier</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#listcomp" title="listcomp">listcomp</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="qualifier">qualifier:</a></p><img border="0" src="../railroad/qualifier.png" height="37" width="141" usemap="#qualifier.map"><map name="qualifier.map"><area shape="rect" coords="29,1,111,33" href="#generator" title="generator"></map><p>
         
         <div class="ebnf"><code><div><a href="#qualifier" title="qualifier">qualifier</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#generator" title="generator">generator</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#qualifier_list" title="qualifier_list">qualifier_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="generator">generator:</a></p><img border="0" src="../railroad/generator.png" height="69" width="319" usemap="#generator.map"><map name="generator.map"><area shape="rect" coords="49,33,115,65" href="#TOK_ID" title="TOK_ID"><area shape="rect" coords="135,33,201,65" href="#TOK_IN" title="TOK_IN"><area shape="rect" coords="241,1,289,33" href="#expr" title="expr"></map><p>
         
         <div class="ebnf"><code><div><a href="#generator" title="generator">generator</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= ( <a href="#TOK_ID" title="TOK_ID">TOK_ID</a> <a href="#TOK_IN" title="TOK_IN">TOK_IN</a> )? <a href="#expr" title="expr">expr</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#qualifier" title="qualifier">qualifier</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="array_sub_list">array_sub_list:</a></p><img border="0" src="../railroad/array_sub_list.png" height="81" width="183" usemap="#array_sub_list.map"><map name="array_sub_list.map"><area shape="rect" coords="49,45,133,77" href="#array_sub" title="array_sub"></map><p>
         
         <div class="ebnf"><code><div><a href="#array_sub_list" title="array_sub_list">array_sub_list</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= <a href="#array_sub" title="array_sub">array_sub</a> ( ',' <a href="#array_sub" title="array_sub">array_sub</a> )*</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#array" title="array">array</a></li>
            
            <li><a href="#array_sub" title="array_sub">array_sub</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="array_sub">array_sub:</a></p><img border="0" src="../railroad/array_sub.png" height="81" width="301" usemap="#array_sub.map"><map name="array_sub.map"><area shape="rect" coords="95,1,205,33" href="#array_sub_list" title="array_sub_list"><area shape="rect" coords="95,45,169,77" href="#expr_list" title="expr_list"></map><p>
         
         <div class="ebnf"><code><div><a href="#array_sub" title="array_sub">array_sub</a></div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::= '[' ( <a href="#array_sub_list" title="array_sub_list">array_sub_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']'</div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#array_sub_list" title="array_sub_list">array_sub_list</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="array">array:</a></p><img border="0" src="../railroad/array.png" height="125" width="465" usemap="#array.map"><map name="array.map"><area shape="rect" coords="115,1,225,33" href="#array_sub_list" title="array_sub_list"><area shape="rect" coords="115,45,189,77" href="#expr_list" title="expr_list"><area shape="rect" coords="105,89,179,121" href="#expr_list" title="expr_list"><area shape="rect" coords="375,1,435,33" href="#param" title="param"></map><p>
         
         <div class="ebnf"><code><div><a href="#array" title="array">array</a>&nbsp;&nbsp;&nbsp;&nbsp;::= ( '[' ( <a href="#array_sub_list" title="array_sub_list">array_sub_list</a> | <a href="#expr_list" title="expr_list">expr_list</a> ) ']' | '{[' <a href="#expr_list" title="expr_list">expr_list</a> ']}' ) ':' <a href="#param" title="param">param</a></div></code></div>
         </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            </ul>
         </p><br><p style="font-size: 14px; font-weight:bold"><a name="TOK_IN">TOK_IN:</a></p><img border="0" src="../railroad/TOK_IN.png" height="81" width="135"><p>
         
         <div class="ebnf"><code><div><a href="#TOK_IN" title="TOK_IN">TOK_IN</a>&nbsp;&nbsp;&nbsp;::= 'in'</div><div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| '&lt;-'</div></code></div> </p>
      
      <p>referenced by:
         
         <ul>
            
            <li><a href="#expr" title="expr">expr</a></li>
            
            <li><a href="#generator" title="generator">generator</a></li>
            </ul>
         </p><br><hr>
      
      <p>
         
         <table border="0" class="signature">
            
            <tr>
               
               <td style="width: 100%">&nbsp;</td>
               
               <td valign="top">
                  
                  <nobr class="signature">... generated by <a name="Railroad-Diagram-Generator" class="signature" title="https://www.bottlecaps.de/rr/ui" href="https://www.bottlecaps.de/rr/ui" target="_blank">RR - Railroad Diagram Generator</a></nobr>
                  </td>
               
               <td><a name="Railroad-Diagram-Generator" title="https://www.bottlecaps.de/rr/ui" href="https://www.bottlecaps.de/rr/ui" target="_blank"><img border="0" src="../railroad/rr-1.63.png" height="16" width="16"></a></td>
               </tr>
            </table>
         </p>
</div>

