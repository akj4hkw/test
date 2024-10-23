## TOPIC

General Topic/Overview: **Contextualizing Sports Absurdities and
Performance**

For this report, the focus is on contextualizing the extraordinary and
historic achievement of Gretchen Walsh’s record-breaking 100 butterfly
swim on March 22nd, 2024 at the 2024 NCAA Division I Women’s
Championships.

**Important Notes/Abbreviations:**

-   W = Women’s, M = Men’s
-   SCY = Short Course Yards (NCAA Distance)
-   Fly = Butterfly

*Short Course Yards (SCY)* refers to the length of the pool/lane. SCY
swims take place in pools/lane that are 25 yards in length. This differs
from other formats such as LCY (Long Course Yards: 50 yards), SCM (Short
Course Meters: 25 meters), and LCM (Long Course Meters: 50 meters).

Swim events follow this format: Gender, Distance, Stroke, Measurement.
For example, *W 100 Fly SCY* stands for Women’s 100 Yard Butterfly,
Short Course Yards.

## QUESTIONS

-   How does Gretchen Walsh’s performance in the 100 fly compare to
    other top performers in the same event over recent years?

-   How has the Short Course Yards (SCY) Women’s 100 Fly record changed
    over time, and what role did Gretchen Walsh play in its evolution?
    How does Walsh’s performance compare to previous record-breaking
    achievements in the same event?

-   How significant is Gretchen Walsh’s record-breaking performance in
    the broader historical context of SCY achievements? To what extent
    did Walsh’s swim demonstrate dominance in the sport?

## AUDIENCE

Fans of swimming, sports enthusiasts, analysts, and journalists
interested in understanding and appreciating the significance of
Gretchen Walsh’s achievement.

## DATA

The data for this analysis was obtained from two main sources on March
23rd & 24th, 2024:

1.  **USA Swimming**: The national governing body for competitive
    swimming in the United States. They collect and store data from
    officially sanctioned meets across the country. The data accessed
    included:
    -   [Top 100 Performers SCY W 100
        Fly](https://www.usaswimming.org/times/popular-resources/event-rank-search)
        (Record Progress.csv): Data on the top 100 performers in the SCY
        Women’s 100 Fly event from 2020 to 2024, including their times
        and ranks.

    <table>
    <thead>
    <tr class="header">
    <th style="text-align: left;">Variable</th>
    <th style="text-align: left;">Information</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="text-align: left;">Time</td>
    <td style="text-align: left;">Length (in Seconds) of the Swim</td>
    </tr>
    <tr class="even">
    <td style="text-align: left;">Athlete</td>
    <td style="text-align: left;">Name of the Athlete</td>
    </tr>
    <tr class="odd">
    <td style="text-align: left;">Swim Date</td>
    <td style="text-align: left;">Date of the Swim</td>
    </tr>
    </tbody>
    </table>

    -   [All Time Top Performances W 100 Fly SCY
        Fly](https://www.usaswimming.org/times/data-hub/all-time-top-performers)
        (Top Performers.csv): Data on the top all time W 100 Fly SCY
        performances, including the swim date, time, and athlete
        details.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Variable</th>
<th style="text-align: left;">Information</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Rank</td>
<td style="text-align: left;">Rank of the Swim in the Competition
Year</td>
</tr>
<tr class="even">
<td style="text-align: left;">Time</td>
<td style="text-align: left;">Length (in Seconds) of the Swim</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Full Name</td>
<td style="text-align: left;">Name of the Athlete</td>
</tr>
<tr class="even">
<td style="text-align: left;">Age</td>
<td style="text-align: left;">Age of the Athlete</td>
</tr>
<tr class="odd">
<td style="text-align: left;">LSC</td>
<td style="text-align: left;">Local Swimming Committee (local governing
body)</td>
</tr>
<tr class="even">
<td style="text-align: left;">Event</td>
<td style="text-align: left;">Name of the Event (ex: 100 FL SCY)</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Meet Name</td>
<td style="text-align: left;">Name of the Meet (ex: 2024 NCAA Division I
Women’s Championships)</td>
</tr>
<tr class="even">
<td style="text-align: left;">Time Standard</td>
<td style="text-align: left;">Which Meet Does this Swim Meet the Cutoff
for? (ex: 2024 Summer Nationals)</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Competition Year</td>
<td style="text-align: left;">Competition Year of Swim</td>
</tr>
</tbody>
</table>

1.  **SwimSwam**: A popular swimming news organization known for its
    coverage of premier swimming events. The data accessed from SwimSwam
    included:
    -   [SwimSwam: Gretchen Walsh’s Absurd
        Performance](https://swimswam.com/trying-to-contextualize-the-absurdity-of-gretchen-walshs-47-42-in-the-100-fly/)
        (Gap.csv): Data on the record percentage time difference in all
        NCAA Championship Meet SCY events, highlighting the significance
        of Gretchen Walsh’s performance. For context, the percentage
        time difference in SCY event gaps is a common metric used to
        assess dominance in collegiate swimming. It compares the
        performance of interest, such as Gretchen Walsh’s SCY 100 Fly,
        with the slowest swim in the ‘B Final’ (16th place). This
        comparison allows for a more accurate assessment of a swimmer’s
        dominance relative to their peers, especially compared to simply
        comparing against the next fastest swimmer, which may not
        accurately reflect historical dominance.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Variable</th>
<th style="text-align: left;">Information</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Event</td>
<td style="text-align: left;">Name of the Event (ex: W 100 Fly)</td>
</tr>
<tr class="even">
<td style="text-align: left;">1st</td>
<td style="text-align: left;">Name of the Winning Athlete (1st in the ‘A
Final’)</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Time 1st</td>
<td style="text-align: left;">The Length (in Seconds) of the Winning
Athlete’s Swim</td>
</tr>
<tr class="even">
<td style="text-align: left;">16th</td>
<td style="text-align: left;">Name of the Last Athlete (16th Overall,
8th in the ‘B Final’)</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Time 16th</td>
<td style="text-align: left;">The Length (in Seconds) of the Last
Athlete’s Swim</td>
</tr>
<tr class="even">
<td style="text-align: left;">Gap</td>
<td style="text-align: left;">Percentage Time Difference Between 1st and
16th</td>
</tr>
</tbody>
</table>

## DATA VIZ

### Data Viz 1

How does Gretchen Walsh’s performance in the 100 fly compare to other
top performers in the same event over recent years?

![unnamed-chunk-5-1](https://github.com/user-attachments/assets/cf4661a6-61a5-4707-8271-a83ad14d1765)


### Data Viz 2

How has the Short Course Yards (SCY) Women’s 100 Fly record changed over
time, and what role did Gretchen Walsh play in its evolution? How does
Walsh’s performance compare to previous record-breaking achievements in
the same event?

![unnamed-chunk-6-1](https://github.com/user-attachments/assets/6caa9eb5-a9c3-4203-84de-24cf8304ce0b)


### Data Viz 3

How significant is Gretchen Walsh’s record-breaking performance in the
broader historical context of SCY achievements? To what extent did
Walsh’s swim demonstrate dominance in the sport?

![unnamed-chunk-7-1](https://github.com/user-attachments/assets/6438f8e6-0120-4ef9-b702-86c9769fab49)

