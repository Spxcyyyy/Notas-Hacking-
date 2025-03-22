## Descripción :
	Can you break into this super secure portal? `https://jupiter.challenges.picoctf.org/problem/6353/` ([link](https://jupiter.challenges.picoctf.org/problem/6353/)) or http://jupiter.challenges.picoctf.org:6353
### Solución :

Inspeccione la pagina y como la hint me decía sobre la ofuscación, le dije al chat que ofuscara el código y obtuve la flag

```
<script type="text/javascript">
(function(){
  const e=['Password Verified','Incorrect password','getElementById','value','substring','picoCTF{','not_this','_again_5','0a029}'];
  function t(e,t){return e.split('').map((e,n)=>String.fromCharCode(e.charCodeAt(0)^t.charCodeAt(n%t.length))).join('');}
  function n(){const n=document[e[2]]('pass')[e[3]];let r=4;
    if(n[e[4]](0,r*2)===e[5]&&n[e[4]](7,9)==='{n'&&n[e[4]](r*2,r*2*2)===e[6]&&n[e[4]](3,6)==='oCT'&&n[e[4]](r*3*2,r*4*2)===e[8]&&n[e[4]](6,11)==='F{not'&&n[e[4]](r*2*2,r*3*2)===e[7]&&n[e[4]](12,16)==='0a02'){
      alert(e[0]);
    } else {
      alert(e[1]);
    }
  }
  window.verify=n;
})();
</script>
```

	picoCTF{not_this_again_50a029}