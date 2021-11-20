---
layout: default
---

<html>
<style>
    .outline {
        border: 1px red solid;
    }
@import url(https://fonts.googleapis.com/css?family=Anonymous+Pro);
html{
min-height: 100%;
overflow: hidden;
}
body{
height: calc(100vh - 8em);
padding: 4em;
color: rgba(255,255,255,.75);
font-family: 'Anonymous Pro', monospace;  
 background-color: rgb(25,25,25);  
}
.line-1{
position: relative;
top: 50%;  
 width: 24em;
margin: 0 auto;
border-right: 2px solid rgba(255,255,255,.75);
font-size: 180%;
text-align: center;
white-space: nowrap;
overflow: hidden;
transform: translateY(-50%);  
}
.anim-typewriter{
animation: typewriter 4s steps(44) 1s 1 normal both,
blinkTextCursor 500ms steps(44) infinite normal;
}
@keyframes typewriter{
from{width: 0;}
to{width: 24em;}
}
@keyframes blinkTextCursor{
from{border-right-color: rgba(255,255,255,.75);}
to{border-right-color: transparent;}
}
</style>

<table style="width:70%;">
    <tr>
        <td>
            <div>
                <script src="https://tryhackme.com/badge/25541"></script>
            </div>
        </td>
        <td>
            <div>
                <script src="https://www.hackthebox.eu/badge/460748"></script>
            </div>
        </td>
    </tr>

</table>
<br>
<div id="content">
</div>
<p class="line-1 anim-typewriter" style="text-color:#808B96;">សួរស្តី អ្នកទាំងអស់គ្នា ស្វាគមន៏មកាន់ទំព័រមួយនេះ...</p>

<!-- <script>
    document.addEventListener('DOMContentLoaded', () => {
    var content = document.getElementById("content");
    content.
})
</script> -->
</html>
