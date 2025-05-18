#Days-since
A simple static one file HTML project. This page will display the number of days since a provided date. The text displayed will be possible to provide from the query string. The default text will be "Days since". After that will de calculated numer of days be provided.

##Query string paratmeters.
- Datefrom, required, the start date
- text, optional, if provided, displayed instead of default text.
- title, optional, if provided, displayed instead <title> defined in the HTML-file.

#Tools used
- Only HTML, Javascript and CSS embedded in the same page.
- Github actions.

#Deploy
The page will be deployd as a static page on github. Deploy is done using a github action that is triggered every time a new change is commited on the main branch.

#Deveplopment
Development is done using VS code. Git is used as the version control system.