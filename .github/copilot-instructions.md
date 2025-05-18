# Days-since
A simple static one file HTML project. This page will display the number of days since a provided date. The text displayed will be possible to provide from the query string. The default text will be "Days since {date-from}: {days}". You can use the placeholders {days} and {date-from} in your text.

## Query string parameters
- datefrom: required, the start date (format: YYYY-MM-DD)
- text: optional, if provided, displayed instead of default text. You can use {days} and {date-from} as placeholders.
- title: optional, if provided, displayed instead of the <title> defined in the HTML file.

## Text template example
- "{days} days since {date-from}"
- Use {days} to insert the calculated number of days.
- Use {date-from} to insert the provided start date.

If no custom text is provided, the default will be:
"Days since {date-from}: {days}"

You can set your own text using the query string parameter, for example:
?text=It%20has%20been%20{days}%20days%20since%20{date-from}

# Tools used
- Only HTML, Javascript and CSS embedded in the same page.
- Github actions.

# Deploy
The page will be deployed as a static page on GitHub from the main branch.

# Development
Development is done using VS Code. Git is used as the version control system.