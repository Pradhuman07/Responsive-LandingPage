**Units:-**
----------------------------------------------------------------------------------------------
• px             -> fixed (depends on screen resolution)
• %              -> relative to parent size
• vh , vw        -> viewport height , viewport width  
• vmax , vmin    -> vmax = max(vh, vw) , vmin = min(vh, vw)   
• em , rem       -> em = relative to font-size of the parent, rem = relative to font-size of the root element(html)  (1rem = 16px, by default set by the browser)
----------------------------------------------------------------------------------------------
**px:-** 
• px = pixel = fixed unit of measurement.
• 1px = 1/96 inch
----------------------------------------------------------------------------------------------
**%:-**
• % = percentage = relative to the parent element.
• 100% = full size of the parent element.
----------------------------------------------------------------------------------------------
**vh,vw:-** (viewport height, viewport width)
• 1vh = 1% of the height of the current viewport .
• 1vw = 1% of the width of the current viewport.
----------------------------------------------------------------------------------------------
**em:-**
#html:- 
<div> 
  <p>Hello<p> 
</div>

#css:-
div {
  font-size: 20px;
}

p {         //child of div
  font-size: 1.5em;   // = 1.5 * 20px = 30px 
}
----------------------------------------------------------------------------------------------
**rem:-**
#NOTE:- 1 rem is not always 16px, but by default, it is.#

• 1 rem = 1 "root em" = size relative to the root element (<html>) font size.
• By default, most browsers set html { font-size: 16px; } → So, 1 rem = 16px
• But if you change the root font size (e.g., html { font-size: 10px; }), then:→ 1 rem = 10px
----------------------------------------------------------------------------------------------