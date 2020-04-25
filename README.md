# Dwaraganathan 



<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
        <style>
            body {
                text align: center;
                margin-top = 200px;
            }
            
        </style>
    </head>
    <body>
      <table border="1">
          
          <tr>
              <td id="aa" onclick="g(1) ; mf()">
                      
              </td>
              <td id="bb" onclick="g(2) ; mf()">
                      
              </td>
              <td id="ee" onclick="g(5) ; mf()">
                  
              </td>
          </tr>
          <tr>
              <td id="cc" onclick="g(3) ; mf()">
                      
              </td>
              <td id="dd" onclick="g(4) ; mf()">
                      
              </td>
              <td id="ff" onclick="g(6) ; mf()">
                  
              </td>
          </tr>
          <tr>
              <td id="gg" onclick="g(7) ; mf()">
                  
              </td>
              <td id="hh" onclick="g(8) ; mf()">
                  
              </td>
              <td id="ii" onclick="g(9) ; mf()">
                  
              </td>
          </tr>
      </table>
      <p id = "hi"></p>
      <button onclick="mf() ; my()">
          Start
      </button>
    
      <script>
      var a1 = [0]
      var b1 = [0]
      var c1 = [0]
      var d1 = [0]
      var e1 = [0]
      var f1 = [0]
      var g1 = [0]
      var h1 = [0]
      var i1 = [0]
      alert("hi")
      function mf() {
           var all = new Array(9);
          for(i=1;i<=9;i++){
              all[i-1] = i
              see = new Set(all)
          }
          var set = 1
          var val = 0
          var sel = 1
    
              while(sel==1){
              var a = all[Math.floor(Math.random()*9)]
              if(see.has(a)){
                  var sel = 0
                  see.delete(a)   
              }
          }
          var sel = 1
          
          while(sel==1){
              var b = all[Math.floor(Math.random()*9)]
              if(see.has(b)){
                  var sel = 0
                  see.delete(b)   
              }
          }
          var sel = 1
          
          while(sel==1){
              var c = all[Math.floor(Math.random()*9)]
              if(see.has(c)){
                  var sel = 0
                  see.delete(c)   
              }
          }
          var sel = 1
          
          while(sel==1){
              var d = all[Math.floor(Math.random()*9)]
              if(see.has(d)){
                  var sel = 0
                  see.delete(d)   
              }
              
          }
          var sel = 1
          
          while(sel==1){
              var e = all[Math.floor(Math.random()*9)]
              if(see.has(e)){
                  var sel = 0
                  see.delete(e)   
              }
              
          }
          var sel = 1
          
          while(sel==1){
              var f = all[Math.floor(Math.random()*9)]
              if(see.has(f)){
                  var sel = 0
                  see.delete(f)   
              }
              
          }
          var sel = 1
          
          while(sel==1){
              var g = all[Math.floor(Math.random()*9)]
              if(see.has(g)){
                  var sel = 0
                  see.delete(g)   
              }
              
          }
          var sel = 1
          
          while(sel==1){
              var h = all[Math.floor(Math.random()*9)]
              if(see.has(h)){
                  var sel = 0
                  see.delete(h)   
              }
              
          }
          var sel = 1
          
          while(sel==1){
              var i = all[Math.floor(Math.random()*9)]
              if(see.has(i)){
                  var sel = 0
                  see.delete(i)   
              }
              
          }
          var sel = 1
          
    
          document.getElementById("aa").innerHTML = a;
          document.getElementById("bb").innerHTML = b;
          document.getElementById("cc").innerHTML = c;
          document.getElementById("dd").innerHTML = d;
          document.getElementById("ee").innerHTML = e;
          document.getElementById("ff").innerHTML = f;
          document.getElementById("gg").innerHTML = g;
          document.getElementById("hh").innerHTML = h;
          document.getElementById("ii").innerHTML = i;
          
          var set=0
          
     
        a1[0]=(a) 
        b1[0]=(b)
        c1[0]=(c)
        d1[0]=(d)
        e1[0]=(e)
        f1[0]=(f)
        g1[0]=(g)
        h1[0]=(h)
        i1[0]=(i)
      }
      var w = [9]
      var z = [1]
      
      function g(x){
            
            if (x==1){
                if (a1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
                
            } else if (x==2){
                if (b1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } else if (x==3){
                if (c1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            
            } else if (x==4){
                if (d1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            
            } else if (x==5){
                if (e1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } else if (x==6){
                if (f1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } else if (x==7){
                if (g1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } else if (x==8){
                if (h1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } else if (x==9){
                if (i1[0]==z[0]){
                    z[0]+=1
                    w[0]-=1
                } else {
                    w[0]=9
                    z[0]=1
                    alert("Mis-click")
                    u()
                    re()
                }
            } 
            
            if (w[0]<=0){
                alert("Congrats..! Your score is "+(Math.floor(t[0]/100)).toString()+" sec")
                w[0]=9
                z[0]=1
                u()
                
            }
            }
            /* //Math.floor(tee[0]/60)+":"+(tee[0]%60)*/
            
            var t=[0]
            var fu=[0]
            var te=new Array(1)
            function myAlert() {
                if ((t[0]%100)<10) {
                    var mil = "0" + (t[0]%100).toString()
                } else {
                    var mil = (t[0]%100).toString()
                }
                
                if (((t[0]/100)%60)<10){
                    var sec = "0" + (Math.floor(((t[0]/100)%60))).toString()
                } else {
                    var sec = (Math.floor(((t[0]/100)%60))).toString()
                }
                 
                var min = (Math.floor(t[0]/6000)).toString()
                document.getElementById("hi").innerHTML = min+":"+sec+":"+mil
                t[0]+=1    
            }
            
            function u(){
                clearInterval(te[0])
                fu[0]=0
                t[0]=0
            }
            
            function my(){
                if (fu[0]==0){
                    t[0]=0
                    te[0] = setInterval(myAlert, 10) 
                    fu[0]=1
                } else {
                    t[0]=0
                }
                              
            }
            
            function re(){
                t[0]=0
                myAlert()
            }
            
      </script>
      
    </body>
</html>
