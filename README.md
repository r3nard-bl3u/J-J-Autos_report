J&J AUTO SALES REPORT

How I turned scattered sales data into answers leadership can trust

"How are we doing?"

It sounds like a simple question. But when I looked at how we were answering it, the reality was anything but simple. Sales numbers lived in one file. Customer details lived in another. Product information somewhere else. And every time someone needed an answer, it meant pulling all of those pieces together by hand, reconciling them in a spreadsheet, and hoping nothing was out of date.
So, a question that should take seconds was taking days. And worse? Two people could run the same report and get two different numbers.


That's the problem I set out to solve.

Approach
•	Built a star schema with fact_orders and dimensions for customer, product, and date.

•	Implemented incremental ETL and deduplication in SQL; persisted staging tables for auditability.

•	Created DAX measures for Total Sales, Total Orders, Customer Lifetime Value (CLV), Deal Size buckets, and monthly time series.

•	Designed interactive Power BI pages with country and order status slicers, KPI cards, trend charts, product line bar charts, and a top customers table.


So, what did I build?

I built a single, interactive dashboard in Microsoft Power BI that brings every part of our sales business into one place. One screen. One source of truth. Every number is always up to date.
When you open it, the first thing you see is the health of the business at a glance: $9.76 million in sales, 2,747 orders, 96,000 units sold, and 89 customers — with Classic Cars standing out as our best-selling product line.


But here's what makes it different from a static report: 

you can interact with it. Click on 2019, and the entire dashboard refocuses on that year. Select "France," and instantly you're looking at our French business — the sales, the customers, the products they buy. Filter by deal size — large, medium, or small — and you can compare customer segments side by side.


Let me walk you through what you'd see:

	A month-by-month sales trend tells the story of our year. You can see exactly where business is steady, where it dips, and where it takes off.

	A product line breakdown ranks all seven of our product categories — from Classic Cars at the top down to Trains — so we always know what's pulling its weight and what isn't.

	An order status chart shows what's happening after the sale: how many orders have shipped, how many are in process, how many are on hold, and — importantly — how many were cancelled. That last slice is revenue we didn't capture, and now we can actually see it.

	A top 10 customers table shows us exactly who our most valuable customers are, how many orders they've placed, how much they're worth over their lifetime, and what they love to buy.

	A top 10 sales contacts chart reveals who's driving the most revenue — and where the next opportunity might be hiding.

	And on the side, a set of simple filters lets anyone slice the entire report by year, country, deal size, or order line. Click any chart, and every other chart updates to match. It's genuinely that easy.


Here's where it gets interesting

Building the dashboard was only half the work. The other half is what it taught us — and this is the part I'd want every stakeholder to hear:


Our business has a rhythm, and now we can see it: 

Sales surge in October and November. That's not a coincidence — it's a pattern. And once you can see a pattern, you can plan for it: inventory, staffing, marketing spends, all timed to the peak instead of reacting after it.

Two product lines carry the company. Classic Cars and Vintage Cars together make up the majority of our revenue. That's a strength — and it's also a concentration worth watching. This dashboard keeps that fact visible every single day.

A handful of customers are worth disproportionately more than the rest. Our number one customer alone has placed 259 orders worth over $912,000. When such a small group drives so much value, keeping them happy isn't just good service — it's risk management.

Not every order ships. A meaningful share of orders ends up on hold or cancelled. Before, that was invisible. Now it's measurable — and anything measurable can be improved.

Revenue is concentrated in a few top performers. Knowing who our strongest sales contacts are means we can learn from what works — and repeat it.


Who this actually helps
If you're an executive, you get a five-second pulse check on the business — no waiting, no chasing, no conflicting numbers.
If you lead sales, you can see your top customers, top products, and top performers in real time, and spot who needs attention before it's too late.
If you run operations, the order status view shows you exactly where orders are getting stuck.
If you're in finance or marketing, you're finally working from the same numbers as everyone else — and you have evidence, not instinct, to back your decisions.
The honest before-and-after:
Before this dashboard, answering a leadership question took days of manual work, and the numbers could differ depending on who pulled them. Trends were only obvious at quarter-end — when it was already too late to act. Decisions leaned on gut feeling.
Now? Questions are answered in seconds. There is one version of the truth, and everyone sees it. Trends show up the moment they happen, not after. And every decision can point to a number on a screen.
I want to be clear about one thing: the value here isn't the charts. The value is the time and confidence this gives back to the people running the business.
A quick word on the technology
I built this on Microsoft Power BI — the same analytics platform trusted by most of the Fortune 500. Under the hood, the data is cleaned, standardized, and organized automatically, so the numbers are consistent and reliable every time the report opens. The business owns everything — the data, the logic, the report — with no external dependency and no per-user cost to view it.
You don't need to remember any of that. You just open it and it works.
What's next
This dashboard is live and already delivering value. But I see it as phase one.
Johnson Ajimotokan
ajimotokanjohnson@gmail.com
BUSINESS SHOULD STOP GUESSING AND START KNOWING

