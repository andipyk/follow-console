Instagram Auto Follow Developer Console Code
===

<img src="https://imgur.com/Kp21oD3"/>

Code
-------------
<pre>
 window.setInterval(function(){
    var items = document.getElementsByTagName("*");
        var stop="";
        for (var i = 0; i < items.length; i++) {
            if (items[i].innerHTML.indexOf("Follow") ===0 && items[i].innerHTML.indexOf("Following") && items[i].innerHTML.indexOf("Followers")) {

                items[i].click();
                var stop ="stop";

            }
            if (stop === "stop") {  break; }
        }
        var page=window.pageYOffset;
        window.scrollTo(0, page+50);

        console.log('loop');
    }, 1000);
    
    </pre>

    
Github Auto Follow Developer Console Code
===
    
<img src="https://imgur.com/9WKAc7U"/>
    
Code
-------------
<pre>
        var items = document.getElementsByTagName("button");
        for (var i = 0; i < items.length; i++) {
           if(items[i].innerHTML.indexOf("Follow")===13 && items[i].innerHTML.indexOf("Unfollow")){
               items[i].click();
           }

        }
        
        </pre>