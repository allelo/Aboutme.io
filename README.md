<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>1xqfr5</title>

<style>
    body {
        margin:0;
        padding:0;
        background:#000;
        color:#fff;
        font-family: 'Trebuchet MS', Arial, sans-serif;
        overflow:hidden;
    }

    /* تأثير البلور اللي يتحرك مع الماوس */
    #cursor-glow {
        position:fixed;
        width:250px;
        height:250px;
        background:rgba(255,0,0,0.2);
        filter:blur(80px);
        border-radius:50%;
        pointer-events:none;
        transform:translate(-50%,-50%);
        z-index:0;
        transition: transform 0.05s linear;
    }

    body::before {
        content:"";
        position:fixed;
        inset:0;
        background:radial-gradient(circle at 20% 30%, rgba(255,0,0,0.15), transparent 60%),
                   radial-gradient(circle at 80% 60%, rgba(255,0,0,0.1), transparent 70%),
                   #000;
        z-index:-1;
    }

    h1 {
        text-align:center;
        margin-top:70px;
        font-size:40px;
        color:#ff3333;
        text-shadow:0 0 15px red;
        position:relative;
        z-index:2;
    }

    .subtitle {
        text-align:center;
        margin-top:-10px;
        opacity:0.8;
        font-size:14px;
        position:relative;
        z-index:2;
    }

    .card {
        width:420px;
        margin:40px auto;
        padding:30px;
        border:1px solid red;
        border-radius:15px;
        box-shadow:0 0 25px red;
        background:rgba(20,0,0,0.6);
        position:relative;
        z-index:2;
    }

    .services {
        display:grid;
        grid-template-columns:1fr 1fr;
        gap:15px;
        margin-top:20px;
    }

    .service {
        padding:12px;
        border:1px solid #ff3333;
        border-radius:10px;
        background:rgba(255,0,0,0.08);
        font-size:13px;
        transition:.3s;
        text-align:center;
    }

    .service:hover {
        box-shadow:0 0 15px red;
        transform:scale(1.05);
    }

    .skill {
        margin-top:18px;
        font-size:14px;
    }

    .bar {
        width:100%;
        height:8px;
        background:#222;
        border-radius:5px;
        margin-top:5px;
    }

    .fill {
        height:100%;
        border-radius:5px;
        background:red;
        box-shadow:0 0 10px red;
    }

    .discord-logo {
        width:65px;
        margin-top:25px;
        cursor:pointer;
        filter:drop-shadow(0 0 10px red);
        transition:0.3s;
        display:block;
        margin-left:auto;
        margin-right:auto;
    }

    .discord-logo:hover {
        transform:scale(1.15);
        filter:drop-shadow(0 0 20px red);
    }

</style>
</head>
<body>

<!-- البلور اللي يتحرك مع الماوس -->
<div id="cursor-glow"></div>

<h1>1xqfr5</h1>
<p class="subtitle">Security Enthusiast • Reverse Engineering • Red Team</p>

<div class="card">

<h2 style="text-align:center;color:#ff4444;text-shadow:0 0 10px red;">
    My Services
</h2>

<div class="services">
    <div class="service">Reverse Engineering</div>
    <div class="service">Penetration Testing</div>
    <div class="service">Malware Analysis</div>
    <div class="service">Exploit Development</div>
</div>

<h2 style="text-align:center;margin-top:30px;color:#ff4444;text-shadow:0 0 10px red;">
    Expertise
</h2>

<div class="skill">Binary Analysis
    <div class="bar"><div class="fill" style="width:75%"></div></div>
</div>

<div class="skill">Reverse Engineering
    <div class="bar"><div class="fill" style="width:68%"></div></div>
</div>

<div class="skill">C/C++
    <div class="bar"><div class="fill" style="width:72%"></div></div>
</div>

<div class="skill">Python
    <div class="bar"><div class="fill" style="width:82%"></div></div>
</div>

<div class="skill">Bug Bounty
    <div class="bar"><div class="fill" style="width:90%"></div></div>
</div>

<!-- لوجو الديسكورد الجديد -->
<a href="https://discord.gg/t25ya4vt9E" target="_blank">
    <img class="discord-logo" 
         src="https://cdn-icons-png.flaticon.com/512/5968/5968756.png"
         alt="Discord Logo">
</a>

</div>

<script>
    // حركة البلور مع الماوس
    const glow = document.getElementById("cursor-glow");

    document.addEventListener("mousemove", (e)=> {
        glow.style.transform = `translate(${e.clientX}px, ${e.clientY}px)`;
    });
</script>

</body>
</html>
