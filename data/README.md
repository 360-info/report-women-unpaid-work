


# India

## `timeuse-india2019-*.csv`

Raw tables from India's 2019 Time Use Survey (specifically from the [press release](https://www.pib.gov.in/PressReleasePage.aspx?PRID=1660028) that accompanied the survey's release).

Files are:

1. `-percentage`: Percentage of persons of age 6 years and above participating in different activities in a day
2. `-minutes`: Average time (in minutes) spent in a day per participant of age 6 years and above in different activities
3. `-pctshare`: Percentage share of total time in different activities in a day per person of age 6 years and above.
  - This is used for validation purposes; we combine the first two tables manually in the analysis.

## `ratios-india2019.csv`

Derived ratios for women's participation in selected activities compared to men. Columns include:

- `activity`: the activity name from the original tables
- `activity_short`: a shorter version of the activity name
- `area`: either `urban` or `rural`
- `percentage`: the ratio of girls and women to boys and men who did the activity
- `minutes`: the ratio of average minutes girls and women who did the activity spent to boys and men who did the activity
- `share`: the ratio of the share of all surveyed girls and women's time to all surveyed boys and men