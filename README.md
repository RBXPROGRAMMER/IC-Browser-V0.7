<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial
}

* {
  box-sizing: border-box;
}

/* The browser window */
.container {
  border: 3px solid #f1f1f1;
  border-top-left-radius: 4px;
  border-top-right-radius: 4px;
}

/* Container for columns and the top "toolbar" */
.row {
  padding: 10px;
  background: #f1f1f1;
  border-top-left-radius: 4px;
  border-top-right-radius: 4px;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
}

.left {
  width: 15%;
}

.right {
  width: 10%;
}

.middle {
  width: 75%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Three dots */
.dot {
  margin-top: 4px;
  height: 12px;
  width: 12px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
}

/* Style the input field */
input[type=text] {
  width: 100%;
  border-radius: 3px;
  border: none;
  background-color: white;
  margin-top: -8px;
  height: 25px;
  color: #666;
  padding: 5px;
}

/* Three bars (hamburger menu) */
.bar {
  width: 17px;
  height: 3px;
  background-color: #aaa;
  margin: 3px 0;
  display: block;
}

/* Page content */
.content {
  padding: 0.8px;
}
</style>
</head>
<body>

<div class="container">
  <div class="row">
    <div class="column right">
      <span class="dot" style="background:#ED594A;"></span>
      <span class="dot" style="background:#FDD800;"></span>
      <span class="dot" style="background:#5AC05A;"></span>
    </div>
   <html>
	<input id='ibox' type='text'>
	<button onclick='searchFor(ibox.value)'>Search</button>
	<script>
	var sites=[{ tag: 'npr', url: 'npr.org'},
		{ tag: 'ign', url:'http://www.ign.com' },
    { tag: 'ign', url:'__SEARCH RESULTS__' },
    { tag: 'cnet', url: 'http://www.cnet.com' },
    { tag: 'cnet', url: '__SEARCH RESULTS__' },
    { tag: 'zoom', url: 'http://www.zoom.com' },
    { tag: 'zoom', url: '__SEARCH RESULTS__' },
    { tag: 'rottentomatoes', url: 'http://www.rottentomatoes.com' },
    { tag: 'rottentomatoes', url: '__SEARCH RESULTS__' },
    { tag: 'xfinity', url: 'http://www.xfinity.com' },
    { tag: 'xfinity', url: '__SEARCH RESULTS__' },
    { tag: 'amazon', url: 'http://www.amazon.com' },
    { tag: 'amazon', url: '__SEARCH RESULTS__' },
    { tag: 'nih', url: 'http://www.nih.gov' },
    { tag: 'nih', url: '__SEARCH RESULTS__' },
    { tag: 'bing', url: 'http://www.bing.com' },
    { tag: 'bing', url: '__SEARCH RESULTS__'},
    { tag: 'instagram', url: 'http://www.instagram.com' },
    { tag: 'instagram', url: '__SEARCH RESULTS__' },
    { tag: 'baidu', url: 'http://baidu.com' },
    { tag: 'baidu', url: '__SEARCH RESULTS__' },
    { tag: 'google', url:'http://www.google.com' },
    { tag: 'google', url:'__SEARCH RESULTS__' },
    { tag: 'youtube', url: 'http://www.youtube.com' },
    { tag: 'youtube', url: '__SEARCH RESULTS__' },
    { tag: 'omegle', url: 'http://www.omegle.com' },
    { tag: 'omegle', url: '__SEARCH RESULTS__' },
    { tag: 'easyjet', url: 'http://easyjet.com' },
    { tag: 'easyjet', url: '__SEARCH RESULTS__' },
    { tag: 'tfl', url: 'http://tfl.gov.uk' },
    { tag: 'tfl', url: '__SEARCH RESULTS__' },
    { tag: 'abc', url: 'http://abc.go.com' },
    { tag: 'abc', url: '__SEARCH RESULTS__' },
    { tag: 'tampermonkey', url: 'http://www.tampermonkey.com' },
    { tag: 'tampermonkey', url: '__SEARCH RESULTS__' },
    { tag: 'friv', url: 'http://www.friv.com' },
    { tag: 'friv', url: '__SEARCH RESULTS__'},
    { tag: 'wikipedia', url: 'http://en.wikipedia.org' },
    { tag: 'wikipedia', url: '__SEARCH RESULTS__' },
    { tag: 'fandom', url: 'http://www.fandom.com' },
    { tag: 'fandom', url: '__SEARCH RESULTS__' },
    { tag: 'zsl', url: 'http://www.zsl.org' },
    { tag: 'zsl', url: '__SEARCH RESULTS__' }];
    function searchFor(x){
		for(n=0; n<43; n++){
		if(x==sites[n].tag)document.write('<a href="'+sites[n].url+'">'+sites[n].url+'</a>')
		}
	}
	</script>
</html>


  <div class="content">
    <h3>IC Browser Search Engine V0.4</h3>
    <p>There are now over 20 websites on the search engine! Scroll down to the bottom of the browser to see the websites! (all letters must be lowercase when searching).</p>
  </div>
</div>

</body>
</html>





<h1> IC browser V0.7</h1>


<h2> Top Recommended websites  </h2>

<h3> Featured websites!
<h4> <a href='https://www.friv.com'>Friv</a> <---- Website for playing so many cool game for free! ITS EVEN AD FREE! </h4>


<h3> Entertainment </h3>

<h4> <a href='https://www.youtube.com'>Youtube</a> <---- Website or app for watching nearly anything you want </h4>
<h4> <a href='https://www.tiktok.com/'>Tiktok</a>     <---- The app for watching very good entertainment </h4>
<h4> <a href='https://www.facebook.com/'>Facebook</a>    <---- The app for watching mixed things </h4>
<h4> <a href='https://www.netflix.com/'>Netflix</a>    <---- The app for watching movies in 4k, 8k, and even 16k! </h4>
<h4> <a href='https://www.spotify.com/'>Spotify</a>     <---- The music app for listening good quallity music </h4>
<h4> <a href='https://www.primevideo.com/'>Primevideo</a> <---- website or app for watching new movies and other movies in 4k, 8k and even 16k! </h4>
<h4> <a href='https://www.disneyplus.com/'>Disneyplus</a>  <---- The TV app for watching all disney movies (rating: U - PG) </h4>
<h4> <a href='https://www.animeflv.net/'>anime</a>  <---- Website for watching all sorts of anime </h4>
<h4> <a href='https://www.convertbinary.com/text-to-binary///'>Text to binary code</a> <---- website for transferring letters to binary code </h4>


<h3> Programming </h3>

<h4> <a href='https://www.kite.com/'>Kite</a> <---- Website for programming  </h4>
<h4> <a href='https://www.tampermonkey.net/'>Tampermonkey</a> <---- Website for programming  </h4>
<h4> <a href='https://www.python.org/'>Python</a> <---- Website for very advanced programming </h4>
<h4> <a href='https://www.scratch.mit.edu/'>Scratch</a> <---- A website for basic programming<html>

<h3> News </h3>

<h4> <a href='https://www.bbc.co.uk/'>BBC NEWS</a> <---- TV channel for knowing the news in the UK </h4>
<h4> <a href='https://abcnews.go.com/'>ABC NEWS</a> <---- TV channel for knowing the news in the US </h4>
<h4> <a href='https://www.bbc.co.uk/newsround/'>NEWS ROUND</a> <--- Website for worldwide news (for kids) </h4>
<h4> <a href='https://www.cnn.com/'>CNN NEWS</a> <---- TV channel for knowing the news in some countries (mostly the US) </h4>

<h3> Browsers </h3>

<h4> <a href='https://www.baidu.com'>Baidu</a> <---- A Chinese browser for searching a lot of things! (Chinese)</h4>
<h4> <a href='https://www.google.com/'>Google</a> <---- The best and most popular browsing system on the internet </h4>
<h4> <a href='https://www.firefox.com/'>Firefox</a> <---- Just like google, one of the most popular browser on the internet </h4>
<h4> <a href='https://www.apple.com/safari//'>Safari</a> <---- The most popular and best browser for Phone or Ipad </h4>
<h4> <a href='https://www.opera.com/'>Opera</a> <---- A good browser for computers </h4>
<h4> <a href='https://www.fandom.com/'>Fandom</a> <--- A website or browser (?) for most wiki searches and other things </h4>
<h4> <a href='https://www.bing.com/'>Bing</a> <--- A website or browser (?) searching things. (Like google) </h4>

<h3> Contacting </h3>

<h4> <a href='https://www.whatsapp.com/'>Whatsapp</a> <---- A app for sending messages, calling and voice messages for free! (wifi required) </h4>
<h4> <a href='https://www.skype.com/'>Skype</a> <---- A app for calling, chatting, video messages and way more for free! (wifi required) </h4>
<h4> <a href='https://www.viber.com/'>Viber</a> <---- A app for calling, chatting, video messages and more! (wifi required) </h4>

<h3>-----------------------------------------------------------------------------------------------------------------------------------------------------------</h3>

<body>

<p>Click this button to see your coordinates! Its a new feature on the browser!</p>

<button onclick="getLocation()">Click here!</button>

<p id="demo"></p>

<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else {
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude +
  "<br>Longitude: " + position.coords.longitude;
}
</script>

</body>


</body>


<h2> The searches on the search engine </h2>

<h3> type: google to go to: google.com </h3>
<h3> type: youtube to go to: youtube.com </h3>
<h3> type: easyjet to go to: easyjet.com </h3>
<h3> type: omegle to go to: omegle.com </h3>
<h3> type: tfl to go to: tfl.gov.uk </h3>
<h3> type: bbc to go to: bbc.co.uk</h3>
<h3> type: abc to go to: abc.go.com</h3>
<h3> type: wikipedia to go to: en.wikipedia.org </h3>
<h3> type: tampermonkey to go to: tampermonkey.com</h3>
<h3> type: friv to go to: friv.com</h3>
<h3> type: wikipedia to go to: en.wikipedia.org</h3>
<h3> type: fandom to go to: www.fandom.com</h3>
<h3> type: zsl to go to: zsl.org</h3>
<h3> type: ign to go to: ign.com</h3>
<h3> type: npr to go to: npr.org</h3>
<h3> type: cnet to go to: cnet.com </h3>
<h3> type: zoom to go to: zoom.com</h3>
<h3> type: rottentomatoes to go to: rottentomatoes.com</h3>
<h3> type: xfinity to go to: xfinity.com</h3>
<h3> type: amazon to go to: amazon.com</h3>
<h3> type: nih to go to: nih.gov</h3>
<h3> type: bing to go to: bing.com</h3>
<h3> type: instagram to go to: instagram.com</h3>
<h3> type: baidu to go to: baidu.com</h3>




<h1> New digital clock </h1>

<head>
    <title>Digital Clock using JavaScript</title>
    <link href="https://fonts.googleapis.com/css?family=Orbitron" rel="stylesheet" type="text/css"/>

    <style>
        .tabBlock
        {
            background-color:#57574f;
            border:solid 0px #FFA54F;
            border-radius:5px; -moz-border-radius:5px; -webkit-border-radius:5px;
            max-width:200px;
            width:100%;
            overflow:hidden;
            display:block;
        }
        .clock
        {
            vertical-align:middle;
            font-family:Orbitron;
            font-size:40px;
            font-weight:normal;
            color:#FFF;
            padding:0 10px;
        }
        .clocklg
        {
            vertical-align:middle;
            font-family:Orbitron;
            font-size:20px;
            font-weight:normal;
            color:#FFF;
        }
    </style>
</head>

<!-- ON LOAD OF THE PAGE, THE CLOCK WILL START TICKING. -->
<body onload="digitized();">
    <div style="background-color:#F3F3F3;
        max-width:220px;width:100%;margin:0 auto;padding:20px;">

        <table class="tabBlock" align="center" cellspacing="0" cellpadding="0" border="0">
            <tr><td class="clock" id="dc"></td>  <!-- THE DIGITAL CLOCK. -->
                <td>
                    <table cellpadding="0" cellspacing="0" border="0">

                        <!-- HOUR IN 'AM' AND 'PM'. -->
                        <tr><td class="clocklg" id="dc_hour"></td></tr>

                        <!-- SHOWING SECONDS. -->
                        <tr><td class="clocklg" id="dc_second"></td></tr>
                    </table>
                </td>
            </tr>
        </table>
    </div>
</body>

<script>
    // OUR FUNCTION WHICH IS EXECUTED ON LOAD OF THE PAGE.
    function digitized() {
        var dt = new Date();    // DATE() CONSTRUCTOR FOR CURRENT SYSTEM DATE AND TIME.
        var hrs = dt.getHours();
        var min = dt.getMinutes();
        var sec = dt.getSeconds();

        min = Ticking(min);
        sec = Ticking(sec);

        document.getElementById('dc').innerHTML = hrs + ":" + min;
        document.getElementById('dc_second').innerHTML = sec;

        if (hrs > 12) {
            document.getElementById('dc_hour').innerHTML = 'PM';
        }
        else {
            document.getElementById('dc_hour').innerHTML = 'AM';
        }

        // CALL THE FUNCTION EVERY 1 SECOND (RECURSION).
        var time
        time = setInterval('digitized()', 1000);
    }

    function Ticking(ticVal) {
        if (ticVal < 10) {
            ticVal = "0" + ticVal;
        }
        return ticVal;
    }
</script>


<button onclick="https://www.w3schools.com/code/tryit.asp?filename=GN16896F317E')" >Share this program</button>



<h3>-----------------------------------------------------------------------end--------------------------------------------------------------------------------</h3>
</html>
