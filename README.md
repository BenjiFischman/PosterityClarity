# To Whom It May Concern

I, Benjamin Fischman know first hand that the erasure of history is unnacceptable. Privacy is a fundamental human right at the intersection of the first and fourth ammendmandt enshrined in the Bill of Rights US Constitution. Land of the free because of the brave, ay bold is my pen. Point of clarification, I am not a lawyer, nor do I wish to claim authority at this point in time. Yes, a STEM scholar by education, witty wordsmith of languages, and an aspiring bussiness person of note in truth (i.e.,Satya), said I. For example, if I choose to attend a graduate program in the future, start my own bussiness as a wealth creator, rejoin the rank and file in Big Tech, run for public service oppertunity, etcetera, etcetera, etcetera. My sincere hope is that this genuinue display of personal accountability to duty, honor and achievment will be a blessing rather than a curse on my fate and fortune. Obvious and self evident are my dreams of leadership, but I digress and prefer to take all worthwhile endaveours one day at a time. 

"For the writer intent on truth, life never was, never is (and never will be!) easy: his like have suffered every imaginable harassment — defimation, duels, a shattered family life, financial ruin or lifelong unrelieved poverty, the madhouse, jail", A. Solzhenitsyn... I can empathize, a terrible place to be, but a great place to have come from.

Hindsight is 2020, and I think, in part, a reason this source code went viral, to my ignorance at the time, was because it met the requriments of success acording to E.F. Schumacher's, Small is Beautiful montra, for any scientists' or technologists' work to be valuable to winnings it must be: 

- cheap enough so that the methods are virtually accessible to everyone
- suitable for small scale application; and
- compatible with the human need for creativity

Tangential backstory for continuity, this code was deleted from GitHub following the guidance of a Princapal PM. The Principal shall be refered to here on as Principal Wormer. I listened to the advise of Principal Wormer, and on or around the wherabouts of Febuary 28th 2018, was so moved to delete this repository for "reasons" persuaded at the moment via verbal communications with Principal PM Wermer. Alas, bad choice to allow a superior to impact my firm conviction in the ethics of a thriving open source culture in the marketplace of ideas. As a witness to the evolution of open data principles, perhaps unimamaginable invisible events in relation, I am confident sharing a harmless sample now is doing the right thing at an approprite time. Think of this as a postmortum, because last time I checked the code is defunct, which means Facebook innovated to improve their security. In retrospect, the code should prpbably have remained local and not been put on the internet for a global audience to mangle, but I was a naive student that with a desire to impress with plenty of prideful ignorance. Recall, pride in oneself is a cardinal sin. If I could do it over again, I would have sent Facebook a proffesional and polite email notifying the powers that be of a hole in their security architechture free of any expecations with an earnest growth mindset. Thank G-d, the segacity of time has served to mature my tone. Time heals all wounds and will typically tell weather; what happens next is a victory or defeat, my curiousity is piqued. To quote Mark Twain, history does not repeat itself but it does rhyme — sublime in literary nature amirite? I don't pretend to imagine a grudge because perception is reality. To be sure, the remuneration from this stupid idea was a $500 check. I did not recieve a single penny, wheat or not, for publishing this software online. Auto course correction, I have made signifigant donations to 501c3 charities since University well exceeding the $500 mark. Yes, I pay my taxes, continue to volunteer, publish, ask tough questions, and participate in open dialouge. I work to humble myself and allow dust to crush me as Ghandi once philosphised in his legendary book, The Story of my Expirments with Truth.

Upon further meditation, and inspired by power of recent events, I am choosing to honor righteousness in the consitancy of patterns over time to build trust with my dear readers and leave yet another document for posterity. To be clear, this code sample is not intended to help or assist bad actors. And for that matter otherwise be construed as anything but a gesture of good faith in service to higher ideals. All parties of note have been graciously abstracted within the bounds of common sense to safeguard careers, public shareholders and personal reputations. Maybe there is a chance we all might prosper as far as our talent performance will allow. The original goal of this project was educational exploration into creation of a system to foster real world communities and build healthy relationships. I think, err hope, we can all agree, it is important to work within the constraints of any system, zero trust is top of mind, to effect change we want to actualize in the world. My dear readers, press pause and reflect to ask oneself, just because I can create something does that mean one should? A grand cliche of the corniest perspectives, with great power comes great responsibility. Like any well written story, this whole narrative is open to interpretation, and as the author I would prefer to frame myself as the leading protagnonist. But I am not perfect, and I best acknowledge that I too don't believe everything I read or hear. Say what you will about the tenents, but in my experience a healthy dose of skepticism and diverse devotiotain to classic literature serve to inoculate one's mind and avoid the disaster of gullability. Feel free to respectfully disagree, but I admit to nothing but a dream and reserve all rights as a private American citizen with respect to the rule of law. In software development, and indeed life, every rule has an exception. For what it's worth, my families imigration legacy began in 17th century America with the first ordained Rabbi, Abraham Rice of German origin, in the United States. 

I am ecstatic to see what happens next,

-BF

P.S. My middle name is Rice, so to be concince, I suffice a precise optimist.


*June 3rd (+/-)2 2021*

# Facebook Scraper
### A web scraper for Facebook utilizing Node.js

<br><br>
#### Introduction
The purpose of this project is to collect demographics pertaining to members in a facebook group. The excersize had the intent to empower collegiate educational program recruitment initiatives. The client was on the board of regents at a public University.
As it stands today, **June 3, 2016**,
Facebook_Scraper isn't functional.Adaptation of a previous project
[GSScrapNode](https://github.com/BenjiFischman/GSScrapeNode) literature review aggregation tool for academics 
was accomidated to complete the customer ask.
<br><br>
GSScrapeNode is a version of GSScrape implemented through a Node.js
based webserver and a Google Chrome extension. It is built this way
because extracting titles from a Google Scholar web page is trivial,
but outputting the titles to a file is not. The file output aspect is
what generated a need for a webserver. In a nutshell, GSScrapeNode will
fetch the titles from a Google Scholar results page and post them to
a local webserver. The webserver will then write the titles to a file.
<br><br>
#### Installation
<ol>
	<li>You'll need to be running linux with both npm and nodejs
	installed. Both are available using <code>apt-get</code>.
	You will also need Google Chrome.</li>
	<li>Clone this repo to wherever. That path will be referred to as
	"scraper_path" in the following steps.</li>
	<li>In Chrome load the unpacked extension located in
	scraper_path/extension.</li>
	<li>In the scraper_path directory, run the command
	<code>npm install</code>. This will install the express and
	body-parser node modules</li>
	<li>Next, run <code>nodejs server.js</code><br>You should see a
	message indicating the server is listening on localhost:8080. You
	may change the listening port as needed.</li>
	<li>Navigate to a Google Scholar page with results and click the
	GSScrapeNode extension button. In scraper_path, there will be a new
	file called <code>titles.txt</code> that will hold the titles from
	that page. You may do this on as many pages as needed, and all
	titles will be appended to <code>titles.txt</code>, one title per
	line.</li>
</ol>
