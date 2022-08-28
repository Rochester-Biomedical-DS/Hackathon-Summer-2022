# University of Rochester Biomedical Data Science Hackathon Summer 2022

The hackathon is now completed and final scores are posted.

# Logistics

<!-- 0.   Registration is open until 12PM Friday 8/19.  Teams can consist of up to 4 people. Register by using the google form. -->
0.   Each team must have a github handle associated with it in order to participate.  Make sure you edit your registration or email the organizers to provide this, if you haven't yet.
1.   You may add team members up
to noon EDT on 8/21 by editing your response to the google form or emailing the organizers.
2.  Teams of entirely undergraduates will be in the undergraduate
division, else they will be in the open division.
3.  Predictions on test data set are submitted by pushing to
    github.  A repository with the name `Hackathon-Summer-2022`,
    owned by the team captain, will
    be queried for a file named [prediction/prediction.csv](prediction/prediction.csv).  **If the team captain forks this
    repository and writes predictions there everything should work
    (as long as the predictions are formatted correctly).**
2.  Predictions will be scored at least once daily, starting 8/23, with
    scores posted by noon.  At
    the organizers' option, predictions may be scored more frequently
    than this.
2.  General questions/problems can be directed to [issues](https://github.com/Rochester-Biomedical-DS/Hackathon-Summer-2022/issues) page.  We encourage other hackathon participants to respond to issues.
3.  The scoreboard will be located
    [here](docs/Leaderboard.pdf).
    <!--[here](https://rochester-biomedical-ds.github.io/Hackathon-Summer-2022/Leaderboard.html)-->
    We  cannot provide support
    beyond the diagnostic output included on the scoreboard if an error is
    encountered in scoring your predictions.
5.  Interim scoring may employ forms of randomization (e.g. bootstrapping) from the test data set.  The final scores will use all the data and not be randomized.
4.  Competition runs through 11:59 PM EDT 26-August-2022.  The predictions each team has committed to their repository at that time will be used to determine their final score.

# Overview
The goal of this hackathon is to predict gene expression differences based on various features of genome sequences. Gene expression (transcript or mRNA abundance) is transcription of DNA into RNA and is determined by DNA sequence features around each gene, primarily but not exclusively transcription factor binding sites in promoter regions upstream of genes. Changes in DNA sequences can thus result in differences in gene expression. Individuals (e.g. humans or yeast strains) often show differences in gene expression. A major challenge to understanding phenotypic variation within a species, including human disease, is identifying DNA sequence changes that affect gene expression. 

# Data
*  The data are described in [Data.Description](Data.Description.txt). 
*  Training data are [here](train_data/).  
*  Test data are [here](test_data/), and are the same format as train data.  
*  Your predictions should be in the order of the sample_id column `SGD` [listed here](prediction/prediction.csv).  The first column will be examined, regardless of column name.  No join is performed on the `SGD` column.

# Prizes
1.  First place in each division: $300 + $75*(team size)
2.  Second place in each division: 0 + $50*(team size)
1.  Predictions will be scored based on mean square error, lower
values are better.

# Winners!
**Congratulations to the winning teams:**
 * 1st place Undergraduate division- JY
 * 2nd place Undergraduate division- jyon
 
 * 1st place Open division - DMMH 
 * 2nd place Open division- NASA

If your team's final MSE was <2.089, your prediction beat random guessing and you will receive a prize! 
* All individuals in the following teams will receive a prize: DMMH, NASA, BrownMunde, Minoans, RZ, JY, bobatea, QQ, Rabbits, FOMO - Fear Of Model Overfitting, JYon, Chien Bae Lee and Potter Ltd, HungryHippos, gz624, mynameistina, CookieMonster, I, LL, ABE, Midnight Chasers

In order to claim your prize, you will need to fill out a [post-competition survey](https://forms.gle/t1CRCvWjdr3WRah48) and [prize information form](https://forms.gle/sTAiRFjQ4kxwRdwq9).

In addition, winning teams will have the opportunity to present their solutions at a meeting of participants and faculty this fall. All teams that submit predictions may receive a participation certificate and teams beating random guessing are eligible for a participation prize to be announced after the completion of the hackathon. 


# Feedback and post-event information
Thank you for participating in this competition! We hope that you enjoyed the event. Please give us feedback so that we can improve future events.

**Fill out the post-competition [survey](https://forms.gle/t1CRCvWjdr3WRah48).** 
* If your team submitted predictions and you would like to receive a certificate of participation, please e-mail alarracu@bio.rochester.edu. 
* Some of the winning teams will present their approach to the hackathon in an upcoming meeting of the GIDS working group in life and biomedical data science. You are all invited. Details about the meeting will come via e-mail once it is scheduled.


In addition, winning teams will have the opportunity to present their solutions at a meeting of participants and faculty this fall. All teams that submit predictions may receive a participation certificate and teams beating random guessing are eligible for a participation prize to be announced after the completion of the hackathon. 


