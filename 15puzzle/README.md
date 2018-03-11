## 15 Puzzle

Code

````html
<body onkeydown=m(event.which&3) onload="m=d=>{for(i=c==s?1999:0;i--;)setTimeout(a
=>m(Math.random()*4|0));n=p+[-4,2,6,0][d];n>0&n<20&&n%5?f[p]=f[p=n-1]:0;f[p]='    
';o.innerText=c=f.join('');o.style.color=c==s?'#0c0':0};f=[i=j=s=0];while(i<20)f[i
++]=i%5?'['+(j<9?0:'')+ ++j+']':'\n';m(p=c=18);s=c"><pre id=o style=font-size:1cm>
````

Play

https://undlmn.github.io/games.code-golf/15puzzle/
