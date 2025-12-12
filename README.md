# Engage2value-Fromclickstoconversions
https://www.kaggle.com/competitions/engage-2-value-from-clicks-to-conversions
First MLP
**Overview**
MLP Project T22025
**Description**
The goal of this competition is to predict a customer’s purchase value based on their multi-session behavior across digital touchpoints. The dataset captures anonymized user interactions such as browser types, traffic sources, device details, and geographical indicators. By modeling these patterns, participants will estimate the purchase potential of each user, helping optimize marketing and engagement strategies.
**Evaluation**
Submissions are evaluated on r2_score() between the predicted values and the True target.
Submission File
For each id in the test set, you must predict the target variable purchaseValue. The file should contain a header and have the following format:

id	purchaseValue
0	0
1	0
2	10990000
4	36500
5	0
etc.	

**Dataset Description**
This dataset captures detailed session-level information from a large-scale digital commerce platform. Each row corresponds to a unique user session and includes data on user behavior, acquisition channels, device information, and geographical location.

Participants are expected to predict the purchaseValue, which represents the total amount spent during a given session.

Key Feature Categories
User Behavior & Session Metrics

totalHits, pageViews, totals.bounces, new_visits, totals.visits: Indicators of user engagement and session activity.
sessionNumber, sessionStart: Information related to session sequence and timing.
Device & Technical Attributes

deviceType, os, browser, screenSize, device.browserSize, device.language: Details about the user's device and browsing environment.
browserMajor, device.*: Encompasses a variety of device-level descriptors such as model, version, and screen specifications.
gclIdPresent: Signals the presence of a Google Click ID used in ad tracking.
Traffic & Marketing Source

userChannel, trafficSource, trafficSource.medium, trafficSource.keyword, trafficSource.campaign: Insights into how users arrived at the platform.
trafficSource.adwordsClickInfo.*: Contains attributes from advertising sources, including ad network type and slot.
trafficSource.adContent, trafficSource.referralPath, trafficSource.isTrueDirect: Provide further attribution details.
Geographical Context

geoNetwork.city, locationCountry, geoNetwork.continent, geoNetwork.subContinent, geoNetwork.metro, geoNetwork.region: Geographic identifiers to help understand regional behavior trends.
geoCluster, locationZone: Groupings based on geographic or behavioral patterns.
Identifiers

userId, sessionId: Unique identifiers for each user and session, allowing for multi-session analysis.
Target Variable

purchaseValue: The amount (in currency units) spent by the customer during the session. This is the target variable to be predicted.
Files
3 files

Size
99.77 MB

Type
csv

License
Subject to Competition Rules

sample_submission.csv(278.97 kB)

2 of 2 columns


ID

purchaseValue
Label	Count
0.00 - 1450.25	1,451
1450.25 - 2900.50	1,450
2900.50 - 4350.75	1,450
4350.75 - 5801.00	1,450
5801.00 - 7251.25	1,451
7251.25 - 8701.50	1,450
8701.50 - 10151.75	1,450
10151.75 - 11602.00	1,450
11602.00 - 13052.25	1,451
13052.25 - 14502.50	1,450
14502.50 - 15952.75	1,450
15952.75 - 17403.00	1,450
17403.00 - 18853.25	1,451
18853.25 - 20303.50	1,450
20303.50 - 21753.75	1,450
21753.75 - 23204.00	1,450
23204.00 - 24654.25	1,451
24654.25 - 26104.50	1,450
26104.50 - 27554.75	1,450
27554.75 - 29005.00	1,451
0
29.0k
Label	Count
0.00 - 0.00	29,006
0
0
0
0.0


Final achieved score 0.65
