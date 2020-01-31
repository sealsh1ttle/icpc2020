----------------------------------------------------------------------------------------------------------------
# ICPC 2020 - Replication Package

1) bots.txt contains the names of the 147 bots.

2) users.txt contains the names of the 728 users.

3) users_noCommitData.txt contains the names of the 13 users whose past commits data was not computed.

4) raw_data (folder) contains cross-proj_scenario.csv and single-proj_scenario.csv (i.e., the raw data of the 32062 PRs used for the cross-project and single-project scenarios).

5) tables-complete-results-statistical-tests (folder) contains the Tex code to generate the tables with the complete results of statistical tests, for both the single- and the cross-project scenarios, grouped by independent variable (PastCommits and PastPRs).

6) sentiment_polarity (folder) contains:
- the raw conversations(.csv) analyzed by the SentiStrengthSE and Senti4SD tools;
- the cross-project_scenario subfolder with the 4 boxplots of the sentiment polarity scores by SentiStrengthSE and Senti4SD for the general and source code discussions, when PastCommits and PastPRs are used as independent variables in the cross-project scenario;
- the single-project_scenario subfolder with the 4 boxplots of the sentiment polarity scores by SentiStrengthSE and Senti4SD for the general and source code discussions, when PastCommits and PastPRs are used as independent variables in the single-project scenario.


----------------------------------------------------------------------------------------------------------------
