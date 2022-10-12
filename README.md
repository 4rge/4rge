<!doctype html>
<! image created using https://www.ascii-art-generator.org/ >

<style>

@import url('https://fonts.googleapis.com/css?family=Source+Code+Pro');

* { box-sizing: border-box; }

body {
  margin: 0;
  padding: 0;
}

#typeWriter {
  width: 100%;
  height: 100%;
  color: #33d011;
  background: #222;
  font-family: 'Source Code Pro', monospace;  
  padding-left: 30px;
  padding-top: 30px;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 10;
}

#typeWriter span {
  display: block;
  font-size: 10px;
  letter-spacing: 2px;
}

#typeWriter :last-child::after {
  content: '_';
  display: inline-block;
  animation: blink 1s step-end infinite;
}

#typeWriter #init::after { display: none; }

#typeWriter span.typewriter-item::before {
  content: '>';
  display: inline-block;
  margin-right: 10px;
}
 @keyframes 
blink {  from, to {
 opacity: 0;
}
 50% {
 opacity: 1;
}
}
</style>
<html>
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="viewport" content="width=device-width, initial-scale=1">
		<title>ZZZlax's Hidden Page'</title>
		<link rel="stylesheet" type="text/css" href="typeWriter.css">
		<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
		<script type="text/javascript" src="typeWriter.js"></script>
</head>
<script>
function TypeWriter(elmt) {
	this.elmt = elmt;
	this.selector = $(elmt);
	this.linesToDisplay = [
	    '*****************************************************************************',
        '_Welcome to ZZZlaxs hidden page_________________________Powered By Arch______',
        '_Contact me via:________________________________________On ARM Cortex-53_____',
	    '_Phone: (***)-***-****__________________________________Built w/ Html/CSS/JS_',
	    '_Email: ZZZlax@protonmail.com___________________________Hosted Using Django__',
	    '_Github: www.github.com/ZZZlax_______________________________________________',
        '_____________________________________________________________________________',
        '___________________________XOkOKNW_________________WWWW______________________',
        '__________________________Nxllcclx0KKKK000KXNWWNKOkxddOW_____________________',
        '_________________________W0oooolc:cloooooloodxxdolooocoX_____________________',
        '_________________________Nklooooooodddoooloooloooolll;lX_____________________',
        '_________________________Kdlooooooooooooooooooooooll:,lX_____________________',
        '________________________Xkooooxkkdlooooooodxxdooool:;,c0W____________________',
        '____________________WX0kddddOKNWNKkolllldkKNNK0kdl:,,,`;ldOXW________________',
        '________________WX0OxdolldkXNWWWNNX0xdkOKNNNNNNX0d:,,,`.`,,:okKN_____________',
        '______________N0kddddoolldKNNNNNNNNNXXNNNNNNNXXK00kc,,```,,,;codOXW__________',
        '___________WXOxdddddoool:cONXKXXXXXNNNNNNXXKK0OOO00o,```,,,,:loolokKW________',
        '_________WKkdooddddoooool:lOKXKKKKXXXXXKKK0OOOOO00Ol,``,,,;:looooooox0W______',
        '________Xkllooooooooollllc::ok000kO0000000kk00000kl,,,,,;:clooooooooloxKW____',
        '______WKo:::ccccccccc::;:ldxxkkOkkkkOOOOOOkkOOOkkkxdl:;;;:clllooooooooookN___',
        '_____W0l;;;;;;;;;:;;,,;okKNNXXK0OOOOOOOOOkkkkkOOOOO00Oxl:;::::ccllllooolldK__',
        '_____Xo;;;;;;;;;;;;,:d0XNNNNNNNXXXXKKKK0000KKKKKKKKXXNNKkl;,,;;;:::::cccc:lO_',
        '_____NOollooxo;;;;:o0XNNNNNNNNNNNNNNNNNXXXXNNNNNNNNNNNNNNKd;,,,,;;;;;;;;;;;cO',
        '_______NXXNWXo;;;cxXNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNXx:;;;;;,;::::;;::k',
        '___________Wk:;;:xXNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNKd;;;;;,;dKOkkOk0N',
        '___________No,,;dKNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN0c;;;;,`lX_______',
        '___________Kc`,cOXNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNXd;;,,``;O_______',
        '_____NXNWWNKd;`cOKXXXNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNXkc,````;kN______',
        '____X00O0KOO0o,ck00KKKXXXXNNNNNNNNNNNNNNNNNNNNNNNNNNNNXXXXXK0OOl;::lO0X-_____',
        '_NXK0O00KXK00OkxxOO000000KKKXXXXXXXNNNNNNNNNXXXXXXXXKKKK000Oxx0kk0Ok0OOKKKK__',
        'N0kk0XXXXXXXXXXKOxxOOOOO00000000KKKKKKKKKKKKKKKKK00000OO0OkOKKKKXNXKKKK0kOKN_',
        '_XO0XKOOkkkOKXKK0OxxkOOOOOOOOOOO00000000000000000OOOOOOOkxOKXNNNXXXNNNNXKO0W_',
        '_WXKKkdddooodxO000OocokOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOkdk0KKK0OkkkkOKXNNKKW_',
        '__NK0xoooollccoO000d;``cdxkOOOOOOOOOOOOOOOOOOOOOOOOOkxo:lk00kolllooood0XX0X__',
        '___NKkoccccccclx000d:,,;;coxOOOOOOOOOOOOOOOOOOOkxdoc;,``;d0Oo:ccccccclxK0KW__',
        '_____NKkolllloxOOOOKKKKKKXNNNXXKK000OOOOO0000000kdolcccloxOOdccccc:ccok0XW___',
        '_______WNXK0000KKXW_______________WWWWWWWWWW______WWNNNWWNK0Oxdoooodk0XW_____',
        '_____________________________________________________________________________',
	    '*****************************************************************************',
	    '> This is a static web page intended for demonstration and marketing',
	    '> If you would like your own page, to learn how to make your own page',
	    '> or need work on your current page feel free to contact me.',
	    '> I am also available for Server Side, Automation Engineering',
	    '> and support for Home Networks.',
	    '*****************************************************************************',
    ];
	this.firstDelay = 50;
	this.typingDelay = 10;
	this.afterLineDelay = 100;
	this.endTimeOut = 2000;
	this.endText = "Thank's You!";
}

TypeWriter.prototype.typeIt = function(selector, text, n) {
	var that = this;

	if (n < (text.length)) {
		$(that.elmt + ' ' + selector).html(text.substring(0, n + 1));
		n++;
		setTimeout(function() {
			that.typeIt(selector, text, n);
		}, that.typingDelay);
	} else {
		$.event.trigger("TypeWriter:linedisplayed");
	}
};

TypeWriter.prototype.appendTypeWriterItem = function(...args) {
	switch (args.length) {
		case 0:
			this.selector.append(
				"<span class='typewriter-item'>"
			);
			break;
		case 1:
			this.selector.append(
				"<span class='typewriter-item' data-text='" + args[0] + "'>"
			);
			break;
		default:
			break;
	}
};

TypeWriter.prototype.start = function() {
	var that = this;
	var i = 0;

	that.appendTypeWriterItem(that.linesToDisplay[i]);

	setTimeout(function() {
		that.typeIt('span.typewriter-item', that.linesToDisplay[i], 0);
	}, that.firstDelay);

	$(window).on('TypeWriter:linedisplayed', function() {
		i++;

		if (i < that.linesToDisplay.length) {
			that.appendTypeWriterItem(that.linesToDisplay[i]);
			setTimeout(function() {
				that.typeIt('span.typewriter-item:last-child', that.linesToDisplay[i], 0);
			}, that.afterLineDelay);
		} else
			that.appendTypeWriterItem();

		if (i === that.linesToDisplay.length)
			$.event.trigger("TypeWriter:finished");
	});

	$(window).on('TypeWriter:finished', function() {
		$(window).on('keypress', function(e) {
			if (e.keyCode == 13) {
				$(that.elmt).append("<span id='init'>" + that.endText);
				setTimeout(function() {
					$(that.elmt).fadeOut("slow");
				}, that.endTimeOut);
			}
		});
	});
};
</script>	
<body>
	<section id="typeWriter"></section>
	<script type="text/javascript">
			$(function() {
				var typeWriter = new TypeWriter('#typeWriter');
				
				typeWriter.start();
			});
    </script>
    <script type="text/javascript">
          var _gaq = _gaq || [];
          _gaq.push(['_setAccount', 'UA-36251023-1']);
          _gaq.push(['_setDomainName', 'jqueryscript.net']);
          _gaq.push(['_trackPageview']);

          (function() {
            var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
            ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
            var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
          })();
    </script>
</body>
</html>
