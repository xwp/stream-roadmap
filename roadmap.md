# Stream Roadmap

## Right Now: What does Stream do?

#### Tracking

- Stream tracks every activity which occurs in the admin area of your WordPress site
- This has been refined over time to be lean and efficient
- Tracking works globally on multisite

#### Records Table
- Stream presents everything which has has been tracked in a list table
- This includes advanced filtering and searching

## The Future: What will Stream do?

### The WordPress AI

In the context of WordPress, an Artificial Intelligence can reasonably be defined as a system which monitors everything that happens, analyses it, and then presents useful and actionable information to the user. In this sense, Stream is already half way there. We could get the rest of the way there by innovating in these key areas:

#### Monitoring
- Ping home page, record response time
- Run a DB query, record response time
- Track response times over time
- Compare with WP events, such as installing a plugin or changing the theme
	- “Stream noticed that your Database response time spike considerably on Monday. What might have caused this?”
- Ability to write custom tracking points, such as a hosting plan change

#### Recommendations
- Suggested Settings changes for optimisation
- Suggested plugins, based on what's you've already installed
- Suggestions based on the users activity
	- “Stream noticed that there you published three new posts last week, but none this week.”
	- “It looks like one of your recent comments included a question, which you haven't responded to yet.”
	- “Your database currently contains x number of unused meta items. You should consider installing this plugin to fix it.”
- Suggestion frequency based on user activity frequency

#### Notifications
- Emails
- Push Notifications
- External Webhooks
	- Zapier
	- IFTTT
	- Mailchimp
	- Zendesk
	- Stripe
	- etc.
- Create rules which trigger external services
	- If Luke updated a Page on the weekend, trigger a Zapier Zap
	- If Jonathan changed a Setting, send me a Push Notification
	- If Luke published a post in the last week, send him $10 via PayPal

#### Reports
- Intelligently collated data sets
- Sentence based report creation (with dropdown menus)
	- “Show me /how many/ /posts/ /were published/ in the last /week/”
	- “Show me /which/ /users/ /logged in/ in the last /month/”
- “Did you know?” text snippets
	- “On average, you publish two posts per week”
	- “Jonathan has been much more active than usual”
	- “There were 3 file changes in the Editor in the last week”