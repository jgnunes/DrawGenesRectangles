# Requirements
Python3 and the following packages:   
* Biopython
* matplotlib
* numpy
* PIL

# How to run
```
python draw_textBoxes.py <target_gbk_files>
```

Where <target_gbk_files> is a text file containing the target genbank files to be processed, e.g.: 

```
seq1.gb
seq2.gb
seq3.gb
```

Note:   
If a genbank file is not in the current working directory, you need to specify the path to the file. 

# Test
A `tests/` directory is provided for you to test the installation. 

Go to that directory and run the script: 
```
python ../draw_textBoxes.py target_files.txt
```

This should generate a `all_seqs.png` file, that looks like:  


<img src="images/all_seqs.png" width=50% height=50%>
