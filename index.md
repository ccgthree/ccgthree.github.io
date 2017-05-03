# SSE Order Tracker

The bookmarklet linked below is an easy way to track your open SSE orders. Just drag it to you bookmark menu or bookmark bar in your preferred web browser. When you click it, it will ask you for your dealer number. Enter it and then click OK. Then, it will ask for your ZIP code. Enter it also and then click OK.

<a href="javascript:function!url(){ var date = new Date(); var y = date.getFullYear(); var m = date.getMonth() +1; if(m < 10){m = '0' + m;} var d = date.getDate(); if(d < 10){d = '0' + d;} var date = y + "-" + m + "-" + d; var dealerNum = prompt("Please enter your dealer number."); var dealerZip = prompt("Please enter your ZIP code."); return 'https://www.fedex.com/apps/fedextrack/?action=altref&trackingnumber='+ dealerNum +'&cntry_code=us&shipdate=' + date +'&account_number=&dest_cntry=us&dest_postal='+ dealerZip; } window.open(url(),"_blank");">SSE Tracker</a>
