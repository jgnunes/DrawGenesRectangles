# Requirements
Python3 and the following packages:   
* Biopython
* matplotlib
* numpy
* PIL

# Run usage
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
