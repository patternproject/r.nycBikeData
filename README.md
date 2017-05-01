# r.nycBikeData
Extending NYC Bike Data Analysis

This project was hampered with big data files associated with it. Tried git lfs but that takes too much time to upload the big data files. 
I had to install git lfs, add csv extension to the files that lfs watches over - as instructed here:
https://git-lfs.github.com/

I will redo the project as r.nycBikeData2 but will add the big files (in terms of size) to .gitignore
Using:
1. find “.1. Data” -size +10M >search.txt
2. diff search.txt .gitignore >diff.txt 
3. and then manually updating .gitignore based on diff.txt
