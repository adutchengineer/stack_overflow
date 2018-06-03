# Creating a Tag Recommendation systems for Stack Overflow

## Summary
<br>
As a heavy user of StackOverflow, I see plenty of articles and sometimes I see tags that do not quite describe the posts. With this project, I will show different techniques to create a recommendation engine and to develop a recommendation engine that would suggest more applicable tags. In my collaborative filtering engine, the most accurate SVD based upon my gridsearchCV got an average root mean squared error of 1.4363715267626944 where the best parameters were {'n_epochs': 30, 'lr_all': 0.008, 'reg_all': 0.5}. 

## Files 
<br>
Project_2.ipynb <br>
README.md <br>
License <br>
geocoded <br>
----- Batch_geocoding.ipynb - converting address strings to locations	<br>
----- locations.csv input file of Batch_geocoding.ipynb <br>
----- geocoding_locations.csv - output file of Batch_geocoding.ipynb<br>
----- geocoding_locations.csv_bak - back-up file <br>
Data <br>
----- Query <br>
---------- QueryResults (10).csv - 100,001 - 150,000 datapoints	<br>
---------- QueryResults (8).csv - 1 - 50,000 datapoints <br>
---------- QueryResults (9).csv - 50,001 - 100,000 datapoints <br>
----- geocoded <br>
---------- geocoded_QueryResults_(10).csv	<br>
---------- geocoded_QueryResults_(9).csv <br>
---------- geocoding_locations.csv <br>
----- dump_KNN k-nearest-neigbhors method save <br>
----- dump_SVD - singular value decomposition method save <br>
----- graph.png - network image	<br>
----- plot.csv - needed for graph database <br>
----- ratings.csv - input for the collaborative filtering recommendation engine<br>
target/tmp/myCollaborativeFilter <br>


## License 

The MIT License

Copyright (c) 2010-2018 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
