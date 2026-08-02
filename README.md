# webdev
My own website--> taken from personal website from GWC

The starter code(the doctype formatting until the <head> tag) was taken from girls who code and then later on I learned how to build one on my own using a youtube video. I'm creating this website to store my work all in one place. Even if my work is in multiple places for example, a project that I'm working on at figma or canva for school or for other orgs can be included here. This will be a place of contact for me. Info about scholarships, lessons I've learned, built-in personal pomodoro, free certifications websites, any and all info I ever find on the internet, in person or other places. I'm not that much of a organizer and I'm making this website so that not only I learn but also other people who are complete begineers like me learn. This is to give hope, courage and faith that you don't have to be perfect; you just have to start. 

Below is my log of everything I do and what I learn along the way(wanted to put it here as I make changes instead of macondo.)

Log: 

Forgot to make a log so, now I'm doing it

Start: July 25? 2026

Learning Git and Github

## 7/26/26 real start time
 Making the website look old timey

7/26-27/ 26 Changing website to be a bit more than the one in GWC
Try to get into hack club- make my own website no AI doing it for me(only learning from it)

### 7/27/26 Childhood
7/27/26 Added childhood drawings, pics, videos, acivities, awards, etc. + grad pic favicon

#### 7/28/26 website bg + favicon
7/28/26 changed grad pic favicon --> grad pic gold bg favicon
thoughts and improvements
Want to make it indian and closer to my culture but each sub webpage will get a custom theme.

May take a long time to finish. Simple first then add on's such as buttons- 
- pomodoro timer + to do list. 
- Inspiration quotes
- Lessons learned
- Git hub link, insta handle-at the bottom
- orgs links, scholarship info-new page/segment
- People met + testimonials(add box to make a message)
- GWC pathways advice
- Hack club advisors advice
##### 8/1/26
I kept getting "cannot GET /nav%20bar%links/volunteer%20work"
and not only volunteer work but art, index, and portfolio but I didn't add much to miscellaneous.

asked gemini for help with the error message
apparently the links are case sensitive so I'm changing that and now it works

favicon and other things above later on but now just basics 
maybe add a subcribe to weekly learnings

The links hover portion I took help from gemini ai. I know how it works now 
    hover aspect:
 navbarlinks- links of the html under id
 a- the actual links under "href" so that the program can go there.
 :hover- gives the hover affect when user is on the link

I learned this from GWC but I don't remember the entire or exact definition
gemini told me that
padding: space inside the text or image and border
border: the perimeter of the image
margin: a little space outside the border

visually impaired-
1. hidden and only works with screen reader
2. how to do it?
    - class: make a unique name
    - position is absolute so that it pulls the default layout of the doc
    - width and height being 1 px it's still there but very tiny so that the screen reader can read it but it's not humanly visible
    - padding and borders are 0 bc it removes inner spacing and borders. This also makes sure that the padding and borders are not expaning or shrinking with the browser defaults.
    - margin of -1px: pulls the edges inside the 1px box and cancels it out so that it becomes "0px" 
    - overflow hidden makes anything that flows that tiny 1px 🪄 ✨ DISAPPEAR ✨ so we can't see it. It's there but not there yk. 
    - clip rect and (0,0,0) makes it really go to 0
    - white space no wrap will make the white spaces 🪄 ✨ DISAPPEAR ✨ (stops it from going to more lines)