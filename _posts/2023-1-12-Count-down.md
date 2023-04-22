---
layout: post
title: DSE test countdown 
tags: [countdown, dse]
categories: post
---

<html>
    <body>
    <script type="text/javascript">
        function changeTime(date, name) {
            var c = new Date(date).getTime();
            var delay = setInterval(function(){
                var n = new Date().getTime();
                var r = c - n;
                var d = Math.floor(r / (1000 * 60 * 60 * 24));
                var h = Math.floor((r % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                var m = Math.floor((r % (1000 * 60 * 60)) / (1000 * 60));
                var s = Math.floor((r % (1000 * 60)) / 1000);
                document.getElementById(name).innerHTML = d + "D " + h + "H " + m + "M " + s + "S"
            },1000)
        }
        changeTime("Apr 24, 2023 08:30:00","math");
        changeTime("Apr 25, 2023 08:30:00","zh12");
        changeTime("Apr 26, 2023 09:15:00","zh3");
        changeTime("Apr 27, 2023 08:30:00","ts");
        changeTime("May 10, 2023 08:30:00","zs");
        changeTime("May 15, 2023 08:30:00","ss");
    </script>
    <h2>English Language 1,2</h2>
    <p>21st April 2023</p>
    <p style="color:red">FINISHED</p>
    <h2>English Language 3 (Listening and Integrated Skills)</h2>
    <p>22rd April 2023
    <p style="color:red">FINISHED</p>
    <h2>Mathematics Compulsory Part 1,2</h2>
    <p>24th April 2023</p>
    <p id="math">0D 0H 0M 0S</p>
    <h2>Chinese Language 1,2</h2>
    <p>25th April 2023</p>
    <p id="zh12">0D 0H 0M 0S</p>
    <h2>Chinese Language 3 (Listening and Integrated Skills)</h2>
    <p>26th April 2023</p>
    <p id="zh3">0D 0H 0M 0S</p>
    <h2>Liberal Studies 1,2</h2>
    <p>27th April 2023</p>
    <p id="ts">0D 0H 0M 0S</p>
    <h2>Chinese History 1,2</h2>
    <p>10th May 2023</p>
    <p id="zs">0D 0H 0M 0S</p>
    <h2>History 1,2</h2>
    <p>15th May 2023</p>
    <p id="ss">0D 0H 0M 0S</p>