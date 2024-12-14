To run and reproduce results in the file:
1. login to jupyter notebook and access ylin250@snl-server-5.cs.ucsb.edu server
2. run imports necessary in the 1st 2 code chunks
3. (optional) collect data via netunicorn and run docker image on said pipeline
4. (optional) if steo 3 was applied, you will need to cd into the /mnt/md0/cs190n/project folder and ls- lh to find the folder containing the most recently collected data
5. load collected data into mtrain, gtrain, mtest, and gtest, combining files wherever needed
6. preprocess data to calculate for packet avg number, packet frequency, and spikes, also label music and game videos correspondingly for classification
7. feed data into the model, and observe the output for important features, adjusting them to the model correspondingly
