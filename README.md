<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN"
   "http://www.w3.org/TR/html4/strict.dtd">

<html lang="en">
<head>
<link href="https://fonts.googleapis.com/css?family=Permanent+Marker" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Special+Elite" rel="stylesheet">
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<meta name="if:Enable endless scrolling" content="1">
	<meta name="generator" content="TextMate http://macromates.com/">
	<meta name="viewport" content="width=790">
	<title>{Title}{block:PostTitle} - {PostTitle}{/block:PostTitle}</title>	
	{block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
	<link rel="shortcut icon" href="{Favicon}">
	<link rel="alternate" type="application/rss+xml" title="RSS" href="{RSS}" />
	
	<meta name="text:Disqus shortname" content="" />
	<meta name="if:Pagination" content="1">
	<meta name="if:Show RSS and Archive buttons" content="1">
	<meta name="if:Show URL in posts" content="1">
	<meta name="if:Show note count" content="1">
	<meta name="if:Show notes on permalink page" content="1">
	
	<style type="text/css">
	
	body {
		font-family: 'Lucida Grande', 'Helvetica Neue', Helvetica, Arial, sans-serif;
		font-size: 16px;
		color: #202020;
		text-align:justify;
		background: #FFFFFF;
		margin: 0px 0 0px 0;
		padding: 0;
	}
	
	#header {
			border-bottom: 8px solid #202020;
			margin-bottom: 45px;
			width: 60%;
			padding-top:6px;
			padding-left:7.32%;
			margin-left:-7.47%;
			text-align:left;
			margin-top:-120px;
			position: fixed;
			z-index: 999;
			background: #faa45c;
			
		} 
		
			#header #top {
				
				padding: 0 0 0px 0;
				position: relative;
			}
		
				#header #top a.title {
					width: 100%;
					color: #202020;
					font-family: 'Special Elite', cursive;
					font-size: 12px;
					font-weight: normal;
					letter-spacing: 1px;
					text-decoration: none;
					margin: 0;
					text-align:left;
				}
						
				#header #top .buttons {
					position: absolute;
					bottom: 24px;
					right: 0;
					text-align:left;
				}
			
					#header #top .buttons a {
						color: #FFFFFF;
						font-weight: bold;
						text-transform: uppercase;
						text-align: left;
						text-decoration: none;
						background: #202020;
					}
				
			 #header #bottom {
				font-size: 34px;
				font-weight:bold;
				text-align:left;
				margin-top:5px;
				font-family: 'Special Elite', cursive;
			}
			
				#header #bottom a {
					font-size:14px;
					color: #202020;
					margin-bottom:7px;
					text-transform: uppercase;
					font-weight: none;
					text-decoration: none;
					
					}
				
				#header #bottom a:hover {text-decoration:underline;}				
	
	#container {
	        border:6px;
	        border-color:#040404;
	        margin-left:40%; 
	        margin-top:118px;
	        border-width:4px;
	        background-color:#faa45c}
	
	a:active, a:focus { outline: 0; }
	
	#content {
		width: 75%;
		margin: 0 auto;
		
	}
				
		#content #footer {
			color: #8E8E8E;
			line-height: 1.5em;
			text-align: right;
			margin: 8px 0 0 0;
			overflow: hidden;
		}

			#content #footer form {
				margin: 0 auto auto auto;
				float:right;
				position:absolute;
				font-size:8px;
			}

				#content #footer form input.text {
					width: 200px;
					text-align:right;
					position:absolute;
				}
	
		#content #footer #header #bottom a {
			color: #8E8E8E;
		}

	#content #newDay {
		padding: 45px 0 0 0;
	}
	
		#content #newDay .post {margin: 20px 0 50px 0; border-bottom: 1px solid #202020;}
		
		#content #newDay .post img { max-width: 76%;}
		
		
		#content #newDay .date {
			font-weight: none;
			text-transform: uppercase;
		}
	
		#content #newDay h2 {
			font-family: 'Special Elite', cursive;
			font-size: 25px;
			letter-spacing: 0px;
			margin: 0;
		}
		
			#content #newDay a.h2 {
				color: #0F6F9F;
				font-family: 'Special Elite', cursive;
				font-size: 25px;
				font-weight: none;
				letter-spacing: -1px;
				line-height: 38px;
				margin: 0;
			}
			
			#content #newDay a.h2 a:hover {text-transform: underline;}
			
			  #content #newDay a.h2.title {
			    color: #202020;
			  }
			
			#content #newDay .quote {
				font-family: 'Special Elite', cursive;
				font-size: 26px;
				text-align:left;
				letter-spacing: -1px;
				line-height: 1.2em;
			}
				
		#content #newDay .post img {
		  max-width: 100%;
		  padding: 1px;
		  font-size: 8px;
		}
		
		#content #newDay .photoset {
		  max-width: 100%;
		  padding: 1px;
		  position:center;
		  font-size: 8px;
		}
		
		#content #newDay .post code {
			font-size: 9px;
			background: #D9E5ED;
			font-family: 'Lucida Console', monospace;
			padding: 1px 4px;
		}
		
		#content #newDay .post {
			font-family: Arial;
			Word-spacing: -0.5px;
			font-size: 15px;
			line-height: 1.6em;
		}
		
			#content #newDay .post a {
				color: #0F6F9F;
				text-decoration: none;
			}
			
				#content #newDay .post a:hover { color: #000000; text-transform: underline;}
				
		/* this is for chat */
		#content #newDay .post table {
			font-family: Georgia;
			font-size: 14px;
			margin: 0 0 10px 0;
			border-collapse: collapse;
		}

			#content #newDay .post table tr td {
				padding: 0;
				vertical-align: top;
			}

			#content #newDay .post table tr td.name {
				font-weight: bold;
				text-align: right;
				padding: 4px 15px;
			}

			#content #newDay .post table tr td.words {
				width: 100%;
				text-align: left;
				padding: 4px 1px;
			}
		/* that was for chat */
			
		#content #newDay .bottom {
			width: 100%;
			color: #444444;
      font-family: 'Lucida Grande', 'Helvetica Neue', Helvetica, Arial, sans-serif;
			font-size: 8px;
			line-height: 1.8;
			text-transform: uppercase;
	
		}
			
			#content #newDay .bottom .notes,
			#content #newDay .bottom .tags {
				text-transform: none !important;
				margin: 0 13px 0 0;
				float: left;
			}
		
			#content #newDay .bottom a {
				color: #3E3E3E;
				text-transform: none;
			}
				#content #newDay .bottom a.time {
					font-weight: bold;
					text-transform: uppercase;
				}
				
				#content #newDay .bottom a:hover { text-decoration: underline; }



		
		blockquote {
border-left:3px solid #202020;
margin:15px 30px 0 10px;
padding-left:20px;
}
			
		ol.notes {
			width: 100%;
			border-bottom: solid 1px #ccc;
	    padding: 48px 0 0 0px;
	    margin: 8px 0px 0px 0px;
	    list-style-type: none;
		}
		
			ol.notes a {
				color: #444444;
			}

			ol.notes li.note {
				color: #777;
				font-family: 'Lucida Grande', 'Helvetica Neue', Helvetica, Arial, sans-serif;
				font-size: 10px;
		    border-top: solid 1px #ccc;
		    padding: 4px;
			}

				ol.notes li.note img.avatar {
			    vertical-align: -4px;
			    margin-right: 10px;
			    width: 16px;
			    height: 16px;
				}

				ol.notes li.note span.action {
					margin-bottom: 5px;
				}
		
					ol.notes li.note span.action a {
						font-weight: bold;
					}

				ol.notes li.note .answer_content {

				}

				ol.notes li.note blockquote {
			    border-color: #eee;
			    padding: 4px 10px;
			    margin: 10px 0px 0px 25px;
				}

					ol.notes li.note blockquote a {
				    text-decoration: none;
					}
					
				ol.notes li.note a:hover {
					text-decoration: underline;
				}
				
    ul#likes {
	    border-bottom: 1px solid #202020;
	    list-style-type: none;
	    margin: 0 0 0 0;
	    padding: 0 0 20px 0;
	    overflow: hidden;
	  }

	  li.like_post {
	    width: 150px;		    
      font-family: 'Lucida Grande', 'Helvetica Neue', Helvetica, Arial, sans-serif !important;
      font-size: 10px;list-style-type: none;
      margin: 0;
	    padding: 0 56px 0 0; 
	    float: left;
	  }

	    li.like_post:last-child {
	      padding: 0;
	      float: right;
	    }

	    li.like_post img {
	      max-width: 146px;
	      border: 1px solid #8E8E8E;
  			padding: 1px;
	    }

	    li.like_post blockquote {
	      margin: 0;
	      padding: 0 0 0 10px;
	      border-left: 1px solid #eee;
	    }

	    li.like_post .like_link a {
	      font-size: 12px;
	      color: #0F6F9F;
	    }

	      li.like_post .like_link a:hover {
		      color: #3A78E4;
		    }

		  li.like_post .like_title {
		    font-size: 12px;
		  }

	    li.like_post a {
	      color: #202020;
	    }

	    li.like_post ol,
	    li.like_post ul {
	      margin: 0 0 0 15px;
	      padding: 0;
	    }

      li.like_post .post_info_bottom {
        margin: 10px 0 0 0;
        display: block !important;
      }

        li.like_post .post_info_bottom a {
          color: #0F6F9F;
          text-decoration: none;
        }

          li.like_post .post_info_bottom a:hover {
            color: #3A78E4;
          }

    a.arrow.back,
    a.arrow.forward {
      display: none !important;
    }
    
    a.install {
        width: 50px;
        height: 20px;
        background: url(http://static.tumblr.com/thpaaos/dHHkt0jor/install_theme.png);
        display: block;
        position: absolute;
        top: 26px;
        right: 3px;
    }
    
    #loading {position: fixed; left: 0px; top: 0px; width: 100%; height: 100%; z-index: 9999; background: url(https://media.giphy.com/media/l3nWhI38IWDofyDrW/giphy.gif) 50% 50% no-repeat #111; background-size:350px; background-color:#FFFFFF;} 
    
    #permalinkpage {margin-bottom:20px, padding: 0 0 20px 0;}

    #permalinkpagination a:hover {text-decoration:underline;}

	{CustomCSS}	
	
	</style>
	
{block:IfEnableEndlessScrolling}
<script type="text/javascript" src="http://yourjavascript.com/21212225154/esz.js">
</script>
{/block:IfEnableEndlessScrolling}

<body>
	<div id="loading"></div>
	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
<script type="text/javascript"> $(window).load(function() { $("#loading").delay(1000).fadeOut("1700"); }) 
</script> 

<div id="container">
	<div id="content">
		<div id="header">
			<div id="top">
				<a  class="title">{Title}</a>
				<div style="clear: both"></div>
			</div>
			<div id="bottom">
			    
				{block:Description}<a href="http://lamareaysupoema.tumblr.com" style="font-size:20px; text-align:left">{Description}&nbsp;&nbsp;</a>{/block:Description}
				{block:HasPages}
                	<br/><br/>
                    {block:Pages}<a href="{URL}">{Label}</a>&nbsp;&nbsp;
                    
                    {/block:Pages}
                    <a href="http://lamareaysupoema.tumblr.com">Blog</a>
                {/block:HasPages}
                
			    
			
			</div>
			
		</div>
		
		{block:Posts}
		<div class = "autopagerize_page_element" >
		<!-- {block:NoRebloggedFrom}
{block:RebloggedFrom}{ReblogParentName}{/block:RebloggedFrom}
{/block:NoRebloggedFrom} -->
{block:ContentSource}<!-- {SourceURL}
{block:SourceLogo}<img src="{BlackLogoURL}"width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />{/block:SourceLogo}
{block:NoSourceLogo}{SourceLink}{/block:NoSourceLogo} -->
{/block:ContentSource}
		<div id="newDay">
		    
			
			<div class="post">
				{block:Text}
				{block:Title}<a href="{Permalink}" class="h2 title">{Title}</a>{/block:Title}
				<p>{Body}</p>
				{/block:Text}

				{block:Link}
				<a href="{URL}" class="h2" {Target}>{Name}</a>
				<p>{block:Description}{Description}{/block:Description}</p>
				{/block:Link}
				
				{block:Photo}
			
					{LinkOpenTag}<img src="{PhotoURL-HighRes}" alt="{PhotoAlt}">{LinkCloseTag}
					<p>{block:Caption}{Caption}{/block:Caption}</p>
			   
				{/block:Photo}
				
				{block:PhotoSet}
				<div class="photoset" style="max-width:75%; position:center"></div>
				{LinkOpenTag}<img src="{PhotoURL-250}" alt="{PhotoAlt}">{LinkCloseTag}</div>
					<p>{block:Caption}{Caption}{/block:Caption}</p>
				{/block:PhotoSet}
				
				{block:Quote}
				<div class="quote">
					"{Quote}"
				</div>
					<p>{block:Source}&mdash;{Source}
				    {/block:Source}</p>{block:RebloggedFrom}{RebloggedFrom}{/block:RebloggedFrom}
				{/block:Quote}
				
				{block:Chat}
					{block:Title}<div class="quote">{Title}</div>{/block:Title}
					<table>
						{block:Lines}
						<tr>
							{block:Label}<td class="name">{Label}</td>{block:Label}
							<td class="words">{Line}</td>
						</tr>
						{/block:Lines}
					</table>
				{/block:Chat}
				
				{block:Audio}
				  {block:AudioEmbed}
						{AudioEmbed-640}
					{/block:AudioEmbed}
					{block:AudioPlayer}
					  {AudioPlayerBlack}
					{/block:AudioPlayer}
					<p>{block:Caption}{Caption}{/block:Caption}</p>
				{/block:Audio}
				
				{block:Video}
					{Video-500}
					<p>{block:Caption}{Caption}{/block:Caption}</p>
				{block:Video}
				
				<div class="bottom">
			
				    {block:Date}
					<a href="{Permalink}" class="time">{24Hour}:{Minutes}, {DayOfMonth}/{MonthNumberWithZero}/{Year}</a>&nbsp;&nbsp;&nbsp;
				{/block:Date}
				</div>
				<div class="clear"></div>
				{block:IfShowNotesOnPermalinkPage}{PostNotes}{/block:IfShowNotesOnPermalinkPage}
		
		 
		</div>
		{/block:Posts}
		{block:Permalink}
		
<p>{block:Posts}{block:Permalink}{block:Date}

        {block:IfDisqusShortname}
        <div class="notecontainer" style="margin: 20px 0 1px 0; padding: 1px 10px 10px 10px;">
          <div id="disqus_thread"></div>
          <script type="text/javascript" src="http://disqus.com/forums/{text:Disqus Shortname}/embed.js"></script>
          <noscript><a href="http://{text:Disqus Shortname}.disqus.com/?url=ref">{lang:View the discussion thread}</a></noscript>
        </div>
        <div style="text-align: right; margin-top: 5px">
          
        </div>
        {/block:IfDisqusShortname}
        
{/block:Date}{/block:Permalink}{/block:Posts}
        {/block:Permalink}
		</div>
		</div>
		
		
		

		
		
  <!-- Twitter universal website tag code -->
<script>
!function(e,n,u,a){e.twq||(a=e.twq=function(){a.exe?a.exe.apply(a,arguments):
a.queue.push(arguments);},a.version='1',a.queue=[],t=n.createElement(u),
t.async=!0,t.src='//static.ads-twitter.com/uwt.js',s=n.getElementsByTagName(u)[0],
s.parentNode.insertBefore(t,s))}(window,document,'script');
// Insert Twitter Pixel ID and Standard Event data below
twq('init','nvcif');
twq('track','PageView');
</script>
<!-- End Twitter universal website tag code -->
  
</body>
</html>
