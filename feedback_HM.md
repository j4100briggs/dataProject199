I did this on Monday, 6/10 (you may have changed it since then)

---

### The Readme

#### 1. Is the Readme file the first document displayed upon lading the Github?  Does this Readme page include a title, and the name and contact information for all project members?

Yes, the Readme is the first document displayed. There is a title, names, and contact information.

#### 2. Is the purpose of this program clear from the Introduction?  What -in your own words- is the motivation behind the program.

Yes, the purpose is clear. The program condenses sequencing data and turns it into a Phyloseq object in R.

#### 3. Is there a program workflow and is it easy to understand?  What -in your own words- is the program workflow?

Yes, there is an easy-to-understand workflow for the bash scripts. The program cuts and sorts the input data, and then combines the sorted files into a single file which is the input to the R script. The R code converts the input into matrices and then makes these into a PhyloSeq object.

#### 4. Are the dependencies indicated in the workflow?  If there are Hoffman2 specific requirements are they indicated?

Yes, dependencies are clearly listed, and Hoffman2 requirements are indicated, with helpful instructions as well.

#### 5. Are there instructions for running the program?  Do the instructions make sense?  What would you do to improve the instructions?

Yes, there are clear instructions for running the program. You have to choose between damfish_script and damfish_script_filler, right? So just make it more clear in the instructions.

#### 6. Is there a section that indicates the files and directories produced by the program?

Outputs are listed, but not in their own section, and they could be described further (just another sentence or two).

#### 7. Are the research programs / motivations for the program cited?  Are the dependencies cited?

The motivations could be explained a bit further - for instance, add a specific example of a project the program could be used for. Dependencies are cited clearly.

---

### The Scripts

#### 8. Is there a directory that contains all of the program scripts?

The scripts are on the github page, but not in their own directory.

#### 9. Do these programs generate a run log?

N/A

---

### The Vignette

#### 10. Is there a directory called Vignette and does it include a test set, the commands used to run the program and the expected output databases?

Yes, there is a vignette directory and it includes those.

#### 11. Where you able to run the Vignette using the small test dataset? If not what errors did you get?  If so was it easy to run the dataset?  Where the instructions clear.

Yes, I was able to run it, and to me it looks like the output was right. It took a long time to install the "phyloseq" package - 15 minutes probably. It was easy to run with the included commands.

#### 12. Where you able to reproduce the expected output?  If not what was different.

Yes, it looked right to me :)

---

### General

#### 13. Give __at least two__ suggestions for ways to improve the GitHub page or the operation of the program.

Make sure the formatting isn't messed up after the Hoffman2 package instructions. Also, you should use some headers (#) in the markdown file so the sections are clearer.
