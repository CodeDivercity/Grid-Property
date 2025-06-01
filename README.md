# Grid-Property
<b>Practice Source :</b> https://appbrewery.github.io/grid-sizing/


<b>display:</b> grid;

<b>grid-template-columns:</b> 1fr 2fr (Ratio like 1:2) | 100px 200px | repeat (2, 100px) <br>
<b>grid-template-rows:</b> 1fr 2fr (Ratio like 1:2) | 100px 200px | repeat (2, 100px)
gap: 10px;

<b>grid-auto-rows:</b> 150px; <br>
<b>grid-auto-columns:</b> 50px;

<b>grid-column:</b> span 2 | 1 / span 2; <br>
<b>grid-row:</b> span 2 | 1 / span 2;

<b>grid-row-start:</b> 2; <br>
<b>grid-row-end:</b> span 3; <br>
<b>grid-column-start:</b> 2; <br>
<b>grid-column-end:</b> 2; <br>

<b>grid-area:</b> 2 / 1 / span 2 / span 3; | 2 / 1 / 3 / 3; <br>
(Here 2=grid-row-start, 1=grid-column-start, 3=grid-row-end, 3=grid-column-end)
