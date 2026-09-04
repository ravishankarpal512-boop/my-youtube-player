<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MyTube</title>

<style>
*{
    box-sizing:border-box;
}

body{
    margin:0;
    background:#0f0f0f;
    color:white;
    font-family:Arial,sans-serif;
}

/* TOP BAR */

.top{
    height:65px;
    background:#181818;
    display:flex;
    align-items:center;
    gap:20px;
    padding:10px 18px;
    position:sticky;
    top:0;
    z-index:10;
}

.logo{
    font-size:24px;
    font-weight:bold;
    white-space:nowrap;
}

.search{
    flex:1;
    max-width:650px;
    display:flex;
}

.search input{
    flex:1;
    padding:13px;
    background:#121212;
    border:1px solid #444;
    color:white;
    border-radius:25px 0 0 25px;
    font-size:16px;
}

.search button{
    width:60px;
    border:0;
    border-radius:0 25px 25px 0;
    background:#333;
    color:white;
    font-size:18px;
}

/* LAYOUT */

.layout{
    display:flex;
}

/* SIDEBAR */

.sidebar{
    width:220px;
    min-height:calc(100vh - 65px);
    background:#181818;
    padding:15px;
    position:fixed;
}

.sidebar button{
    width:100%;
    background:none;
    border:0;
    color:white;
    text-align:left;
    padding:14px;
    border-radius:8px;
    font-size:15px;
}

.sidebar button:hover{
    background:#333;
}

/* CONTENT */

.content{
    margin-left:220px;
    width:calc(100% - 220px);
    padding:20px;
}

/* CATEGORY */

.categories{
    display:flex;
    gap:10px;
    overflow:auto;
    margin-bottom:20px;
}

.categories button{
    background:#272727;
    color:white;
    border:0;
    padding:9px 16px;
    border-radius:8px;
    white-space:nowrap;
}

/* VIDEO GRID */

.grid{
    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(250px,1fr));
    gap:25px 18px;
}

.card{
    cursor:pointer;
}

.thumbnail{
    width:100%;
    aspect-ratio:16/9;
    background:#272727;
    border-radius:10px;
    overflow:hidden;
}

.thumbnail img{
    width:100%;
    height:100%;
    object-fit:cover;
}

.card h3{
    font-size:16px;
    margin:9px 0 5px;
}

.card p{
    margin:0;
    color:#aaa;
    font-size:13px;
}

/* PLAYER */

#playerPage{
    display:none;
}

.videoPlayer{
    width:100%;
    max-width:1000px;
    margin:auto;
    aspect-ratio:16/9;
    background:black;
}

.videoPlayer iframe{
    width:100%;
    height:100%;
    border:0;
}

.back{
    background:#333;
    color:white;
    border:0;
    padding:10px 18px;
    border-radius:7px;
    margin-bottom:15px;
}

/* MOBILE */

@media(max-width:700px){

    .sidebar{
        display:none;
    }

    .content{
        margin-left:0;
        width:100%;
        padding:12px;
    }

    .top{
        gap:8px;
        padding:8px;
    }

    .logo{
        font-size:19px;
    }

    .grid{
        grid-template-columns:1fr;
    }

}
</style>
</head>


<body>


<!-- TOP BAR -->

<div class="top">

<div class="logo">
▶ MyTube
</div>

<div class="search">

<input
id="search"
placeholder="Search videos..."
>

<button onclick="searchVideos()">
🔍
</button>

</div>

</div>



<div class="layout">


<!-- SIDEBAR -->

<div class="sidebar">

<button onclick="showHome()">
🏠 Home
</button>

<button>
🔥 Trending
</button>

<button>
📺 Subscriptions
</button>

<button>
📚 Library
</button>

<button>
🕘 History
</button>

</div>



<!-- HOME -->

<div class="content" id="homePage">


<div class="categories">

<button>All</button>
<button>Music</button>
<button>Gaming</button>
<button>Movies</button>
<button>News</button>
<button>Education</button>
<button>Live</button>

</div>



<div class="grid" id="videoGrid">


<!-- VIDEO 1 -->

<div class="card"
onclick="openVideo('dQw4w9WgXcQ','Sample Video')">

<div class="thumbnail">

<img
src="https://img.youtube.com/vi/dQw4w9WgXcQ/maxresdefault.jpg"
>

</div>

<h3>Sample YouTube Video</h3>

<p>MyTube • 1M views</p>

</div>



<!-- VIDEO 2 -->

<div class="card"
onclick="openVideo('aqz-KE-bpKQ','Big Buck Bunny')">

<div class="thumbnail">

<img
src="https://img.youtube.com/vi/aqz-KE-bpKQ/maxresdefault.jpg"
>

</div>

<h3>Big Buck Bunny</h3>

<p>MyTube • 500K views</p>

</div>



<!-- VIDEO 3 -->

<div class="card"
onclick="openVideo('ysz5S6PUM-U','Test Video')">

<div class="thumbnail">

<img
src="https://img.youtube.com/vi/ysz5S6PUM-U/maxresdefault.jpg"
>

</div>

<h3>Test Video</h3>

<p>MyTube • 200K views</p>

</div>


</div>

</div>



<!-- PLAYER PAGE -->

<div class="content" id="playerPage">

<button class="back"
onclick="showHome()">

← Back

</button>


<h2 id="videoTitle">
Video
</h2>


<div class="videoPlayer">

<iframe
id="videoFrame"
allow="autoplay; encrypted-media; picture-in-picture"
allowfullscreen>
</iframe>

</div>


<h3>Playback Speed</h3>

<button onclick="setSpeed(1)">
1×
</button>

<button onclick="setSpeed(1.25)">
1.25×
</button>

<button onclick="setSpeed(1.5)">
1.5×
</button>

<button onclick="setSpeed(1.75)">
1.75×
</button>

<button onclick="setSpeed(2)">
2×
</button>

</div>


</div>



<script>

let currentVideo="";


function openVideo(id,title){

    currentVideo=id;

    document.getElementById("homePage")
    .style.display="none";

    document.getElementById("playerPage")
    .style.display="block";


    document.getElementById("videoTitle")
    .innerText=title;


    document.getElementById("videoFrame")
    .src=
    "https://www.youtube.com/embed/"
    +id+
    "?enablejsapi=1&playsinline=1";

}


function showHome(){

    document.getElementById("playerPage")
    .style.display="none";

    document.getElementById("homePage")
    .style.display="block";

    document.getElementById("videoFrame")
    .src="";

}


function setSpeed(speed){

    if(!currentVideo){

        return;

    }


    document.getElementById("videoFrame")
    .contentWindow
    .postMessage(

        JSON.stringify({

            event:"command",

            func:"setPlaybackRate",

            args:[speed]

        }),

        "*"

    );

}


function searchVideos(){

    let text=
    document.getElementById("search")
    .value
    .toLowerCase();

    let cards=
    document.querySelectorAll(".card");


    cards.forEach(card=>{

        let title=
        card.innerText.toLowerCase();

        if(title.includes(text)){

            card.style.display="block";

        }else{

            card.style.display="none";

        }

    });

}

</script>


</body>
</html>
