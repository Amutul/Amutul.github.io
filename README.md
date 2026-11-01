# Amutul Mahayadiya – Portfolio

Data and workforce analyst. I turn contact-center and people data into staffing decisions that keep service levels on track and agents supported.

**Live site:** https://amutul.github.io

## Projects in this repository

### Intraday staffing calculator
`staffing-calculator.html` · **Live:** https://amutul.github.io/staffing-calculator.html

How many agents does a contact center need in the next interval? Enter call volume, average handle time and a service-level target (for example, 80% of calls answered in 20 seconds), and the calculator:

- converts the inputs into workload (Erlangs)
- uses the **Erlang C** model to find the smallest number of agents that meets the target
- shows predicted service level, average speed of answer and occupancy
- converts agents on the phones into people to schedule, after shrinkage
- shows a what-if table and chart for staffing a few agents above or below

I built this with Claude, drawing on four years of real-time workforce management at Amazon, where this was the question I answered every day.

**Known limits of Erlang C:** it assumes callers never abandon and that calls arrive randomly and evenly within the interval, so it slightly overstates staffing. Real-time teams use it as a starting point and adjust with live data.

### Portfolio site
`index.html` · A single-page portfolio covering my experience at Amazon and Thesus Health, my projects and my skills.

## Tech
Plain HTML, CSS and JavaScript. No build step and no dependencies, so it runs anywhere, including free on GitHub Pages.

## Contact
mahayadiyaamutul@gmail.com
