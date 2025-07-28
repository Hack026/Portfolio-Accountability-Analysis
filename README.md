What happens when a business can't answer a simple, critical question: "Who is managing our customers?"

This project tackles that exact problem. It's a journey from a challenging, raw dataset to a clean, interactive Power BI dashboard that provides a single source of truth for portfolio management.

Project Presentation & Video Walkthrough: 

For a deeper dive into the project's objectives, process, and outcomes, you can view the full presentation and a video walkthrough.

Interactive Presentation- https://prezi.com/view/Fs2cdeude8Fb4SxQv2N7/

Watch the Video Walkthrough on YouTube- https://youtu.be/PzH-VW6Y2WI?si=YY1owNIBlhfTkIJl

The Situation: A Critical Blind Spot
What happens when a business can't easily see who is managing its customers?

This was the central question I tackled for my final project as a Summer Intern in the Power BI Department at Celebal Technologies.

Imagine a large organization with hundreds of customer portfolios, or "Pool Codes." Each pool represents a group of clients that should be managed by a dedicated Relationship Manager (RM). The problem was, there was no easy way to track which pools were actively managed and which were vacant or unassigned. This created a significant risk: unmanaged customer portfolios could lead to poor service, missed opportunities, and potential compliance issues. Leadership was essentially flying blind.


The Task: Create Clarity from Chaos
My mission was to build a dynamic Power BI dashboard that would provide immediate, clear answers to these critical business questions:

Who is responsible for what? Instantly see which RMs are assigned to which pools.

Where are our risks? Immediately identify the "unmapped" or vacant pools that need urgent attention.

How are our resources allocated? Understand the distribution of products and customer accounts across the different portfolios.

My Action: A Step-by-Step Approach to a Solution
Building a useful dashboard isn't just about making charts. It's about telling a story and making the data easy to understand. Here was my process:

1. Data Wrangling & Engineering
The source data was a single CSV file, and it was messy. This is where most of the magic happens.

Stitching the Data Together: Many records were broken and split across two rows. The first thing I did was engineer a process in Power Query to intelligently merge these broken pieces back into single, complete records.

Adding Business Intelligence: The data didn't explicitly say "Mapped" or "Unmapped." I created a new Mapping Status column using conditional logic. This wasn't just cleaning; it was adding a layer of business intelligence directly into the dataset.

Reshaping for Analysis: The product data was spread across 20+ columns, making it impossible to analyze. I completely restructured this by "unpivoting" it into a lean, long format. This single step unlocked the ability to create powerful visuals for product analysis.

2. Designing the Dashboard
I designed the dashboard with the end-user in mind, from the executive who needs a quick summary to the manager who needs to dig into the details.

The 30,000-Foot View: The top of the dashboard features four key KPI cards, providing an instant summary of the most critical metrics (Total Codes, Mapped, Unmapped, etc.).

Visual Storytelling: I used clean, simple charts (a donut and a bar chart) to visually represent the breakdown of mapping status and product allocation. This makes it easy to spot trends and outliers at a glance.

The Deep Dive: For users who need to see the raw details, I included a comprehensive table at the bottom.

Interactive Filtering: I added a slicer that allows any user to dynamically filter the entire report, making it a powerful tool for exploration and discovery.

The Result: From a Messy Spreadsheet to Actionable Intelligence
The final result is a polished, intuitive, and interactive Power BI dashboard that serves as a single source of truth for Pool Code management.

The key impact? It empowers the business to act.

Instead of spending hours trying to piece together information, leadership can now, in seconds, identify the exact 213 unmapped pool codes that represent an operational risk. They can analyze workload distribution and make informed decisions about resource allocation.

This project took a static, messy dataset and transformed it into a living tool that drives accountability and enables data-driven decision-making.
