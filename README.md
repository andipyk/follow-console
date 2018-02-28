Instagram Auto Follow Developer Console Code
===
<img src="https://image.ibb.co/maG55x/ezgif_1_5a03fedf14.gif"/>


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
 
<img src="https://image.ibb.co/kYsZyH/ezgif_1_f65c4c3a5a.gif"/>
   
    
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