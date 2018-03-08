# Bookmarklets to test Accessibility and other things

[Test Target size](javascript:(function()%7Bvar%20linksbuttons=document.querySelectorAll('a,%20button');for(var%20i=linksbuttons.length-1;i%3E=0;i--)%7Bvar%20width=linksbuttons%5Bi%5D.offsetWidth;var%20height=linksbuttons%5Bi%5D.offsetHeight;linksbuttons%5Bi%5D.innerHTML=width+'%E2%A8%89'+height+%22&nbsp;%22+linksbuttons%5Bi%5D.innerHTML;if((width%3C44)%7C%7C(height%3C44))%7Blinksbuttons%5Bi%5D.style.outline=%222px%20solid%20red%22;%7D%7D%7D)()) (WCAG 2.1 2.5.3, https://www.w3.org/TR/WCAG21/#target-size)
