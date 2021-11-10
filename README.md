# Gmail search filter for hiring outreach

If you're looking for a new job or are happy with your current role, it's useful to have a Gmail filter that groups all outreach from recruiters and hiring managers.

Just copy the following snippet into your Gmail search or apply it as a label filter:

    ("intro call" OR "more about the role" OR subject:"opportunities" OR ( (subject:"designer" OR subject:"lead" OR subject:"leadership" or "design manager" or "design director") AND (subject:"at" OR "inmail" OR subject:"founding" OR subject:"opportunities" OR subject:"opportunity" OR subject:"team" OR "we are looking for" OR "join our amazing team") ) OR "we hire for" OR ( (subject:"join") AND ("we are looking for" OR "hop") ) OR ( subject:"backed" AND (subject:"design" OR subject:"designer") ) OR ( (subject:"Opportunity" OR subject:"Opportunity") AND "inmail" ) OR ( "inmail' AND ("recruiting team" OR "looking for")) ) AND NOT (subject:"offer" OR subject:"investing" OR subject:"investment" OR subject:"overseas" OR subject:"taxes" ) 

It's targetted towards design positions in tech but can be modified for your needs.

This is by no means perfect but works most of the time. YMMV!
