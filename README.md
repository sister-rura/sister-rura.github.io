
        <div id="container"><div id="topBar">BUNKER UNDER CONSTRUCTION!</div><div id="header" style="margin-bottom: 10px; height: 127px;"></div>
            <div id="headerArea">
                
                
            </div>

            <div id="flex">
                <aside id="leftSidebar" style="margin-right: 10px;">
                    <h2>NOTES</h2>
                    <div class="box">
                        <p>STILL FIGURING THIS SHIT OUT</p>
                        <ul style="padding-left:10px;">
                            <li>PORTFOLIO BEST VIEWED ON 1920x1080 SCREENS</li>
                           
                        </ul>
                    </div>
                    <h2>EXPLORE OUR FACILITIES:</h2>
                    <h3></h3>
                    <ul>
						<li><a href=https://flakwolves.su/NoTigerbyMIKA.pdf target="_blank">MY BOOK!</a></li>
						<li><a href=https://flakwolves.su/visualportfolio target="blank">VISUAL PORTFOLIO!</a></li>
						<li><a href="https://bsky.app/profile/flakwolves.su" target="_blank">bluesky</a></li>
                        <li><a href="https://x.com/rura_66k" target="_blank">garbage dot com</a></li>	
                    </ul>
                </aside>
                <main>
                    <h1>COMBINED OPERATIONS COMMAND OF THE FLAK WOLVES AND OASIS MOUNTAIN DIVISION</h1>
                   
                    <div style="font-size: 16px;"><p>THERE ARE LINKS TO THE LEFT FOR BASIC PORTFOLIO SHIT. I am still adding my visual art and I will add more links to come.</p>
					<p>SOME STORIES OF MINE:</p>
					<p><a href="https://andataexpress.neocities.org/bloodied-moon">FULL-BLOODIED MOON</a>, a tale of tormented fighter-power and explosive martial death by the hand of femme-canine warrior WOLFIRE SIS. 
					<p><a href="https://www.miserytourism.com/suicide-diary-of-princess-and-the-mudfish">Suicide Diary of Princess and the Mudfish</a>, a series of dreams experienced by Dogshit, Bodyguard Princess of Dull Sword, paired with a progression of collages. Dreams of great death.
					<p><a href="https://apocalypse-confidential.com/2021/10/08/massive-like-fish-and-drunk/">Massive Like Fish And Drunk</a>, a story about the prophetic Stature, deformed mercenary cartographer of the medieval supraforest named "the Forum." Youth touched by curse, and then defensive execution. </div>
					<p><strong><em>ONLY MASSACRE REMAINS.</em></strong>

                </main>
                
            </div>
            <footer id="footer" style="margin-top: 10px;">mutt 2027 engine</footer>
        </div>
        <!-- THIS IS THE CSS !-->
        <style>
            /* user styles */

            /* styles are what change the color and sizes of stuff on your site. */

            /* these are variables that are being used in the code
    these tended to confuse some people, so I only kept 
    the images as variables */

            :root {
                --header-image: url('https://flakwolves.su/websitebanner.png');
                --body-bg-image: url('https://flakwolves.su/dkgraytexture.gif');

                /* colors */
                --content: #43256E;
            }

            /* if you have the URL of a font, you can set it below */
            /* feel free to delete this if it's not your vibe */

            /* this seems like a lot for just one font and I would have to agree 
    but I wanted to include an example of how to include a custom font.
    If you download a font file you can upload it onto your Neocities
    and then link it! Many fonts have separate files for each style
    (bold, italic, etc. T_T) which is why there are so many!
    
    */

            @font-face {
                font-family: SimSun;
                src: url('https://flakwolves.su/SimSun-01.ttf');
            }

            @font-face {
                font-family: SimSun;
                src: url('https://flakwolves.su/SimSun-01.ttf');
                font-weight: bold;
            }

            @font-face {
                font-family: SimSun;
                src: url('https://flakwolves.su/SimSun-01.ttf');
                font-style: italic;
            }

            @font-face {
                font-family: SimSun;
                src: url('https://flakwolves.su/SimSun-01.ttf');
                font-style: italic;
                font-weight: bold;
            }

            body {
                font-family: 'SimSun', serif;
                margin: 0;
                background-color: #08031A;
                /* you can delete the line below if you'd prefer to not use an image */
                background-size: 128px;
                color: #fceaff;
                background-image: var(--body-bg-image);
              }

            * {
                box-sizing: border-box;
            }

            /* below this line is CSS for the layout */

            /* this is a CSS comment
    to uncomment a line of CSS, remove the * and the /
    before and after the text */


            /* the "container" is what wraps your entire website */
            /* if you want something (like the header) to be Wider than
    the other elements, you will need to move that div outside
    of the container */
            #container {
                max-width: 900px;
                /* this is the width of your layout! */
                /* if you change the above value, scroll to the bottom
      and change the media query according to the comment! */
                margin: 0 auto;
                /* this centers the entire page */
            }

            /* the area below is for all links on your page
    EXCEPT for the navigation */
            #container a {
                color: #ffef00;
                font-weight: bold;
                /* if you want to remove the underline
      you can add a line below here that says:
      text-decoration:none; */
            }

            #header {
                width: 100%;
                background-color: #3eb489;
                /* header color here! */
                height: 150px;
                /* this is only for a background image! */
                /* if you want to put images IN the header, 
      you can add them directly to the <div id="header"></div> element! */
                background-image: var(--header-image);
                background-size: 100%;
            }

            /* navigation section!! */
            #navbar {
                height: 40px;
                background-color: #13092D;
                /* navbar color */
                width: 100%;
            }

            #navbar ul {
                display: flex;
                padding: 0;
                margin: 0;
                list-style-type: none;
                justify-content: space-evenly;
            }

            #navbar li {
                padding-top: 10px;
            }

            /* navigation links*/
            #navbar li a {
                color: #ffffff;
                /* navbar text color */
                font-weight: 800;
                text-decoration: none;
                /* this removes the underline */
            }

            /* navigation link when a link is hovered over */
            #navbar li a:hover {
                color: #a49cba;
                text-decoration: underline;
            }

            #flex {
                display: flex;
            }

            /* this colors BOTH sidebars
    if you want to style them separately,
    create styles for #leftSidebar and #rightSidebar */
            aside {
                background-color: #000000;
                width: 200px;
                padding: 20px;
                font-size: smaller;
                /* this makes the sidebar text slightly smaller */
            }


            /* this is the color of the main content area,
    between the sidebars! */
            main {
                background-color: #000000;
                flex: 1;
                padding: 20px;
                order: 2;
            }

            /* what's this "order" stuff about??
    allow me to explain!
    if you're using both sidebars, the "order" value
    tells the CSS the order in which to display them.
    left sidebar is 1, content is 2, and right sidebar is 3! */

            */ #leftSidebar {
                order: 1;
            }

            #rightSidebar {
                order: 3;
            }

            footer {
                background-color: #000000;
                /* background color for footer */
                width: 100%;
                height: 40px;
                padding: 10px;
                text-align: center;
                /* this centers the footer text */
            }

            
            h2,
            h3 {
                color: ffffff;
            }

            h1 {
                font-size: 30 px;
				color: #ffef00
            }
			
			
            strong {
                /* this styles bold text */
                color: #ffef00;
            }

            /* this is just a cool box, it's the darker colored one */
            .box {
                background-color: #000000;
                border: 1px solid #ffffff;
                padding: 10px;
            }

            /* CSS for extras */

            #topBar {
                width: 100%;
                height: 30px;
                padding: 10px;
                font-size: smaller;
                background-color: #000000;
            }


            /* BELOW THIS POINT IS MEDIA QUERY */

            /* so you wanna change the width of your page? 
    by default, the container width is 900px.
    in order to keep things responsive, take your new height,
    and then subtrack it by 100. use this new number as the 
    "max-width" value below
    */

            @media only screen and (max-width: 800px) {
                #flex {
                    flex-wrap: wrap;
                }

                aside {
                    width: 100%;
                }

                /* the order of the items is adjusted here for responsiveness!
      since the sidebars would be too small on a mobile device.
      feel free to play around with the order!
      */
                main {
                    order: 1;
                }

                #leftSidebar {
                    order: 2;
                }

                #rightSidebar {
                    order: 3;
                }

                #navbar ul {
                    flex-wrap: wrap;
                }
            }
        </style>

    
