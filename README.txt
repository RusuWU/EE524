This folder includes the scripts and output of stept 2 and 3, and also, the report is the pdf file.

The script picture for every state.txt associates with the outcome file in sub-folder.

For Stept 2 scripts and output, every benchmarks runs the same configuration, and the results include in the folder.
For Stept 3 scripts and output, its subfolder includes all the changing configurations. 
  1) Associativity---each benchmark-- 111 means L1I :L1D:L2=1-way:1-way:1-way
 			            112  means L1I :L1D:L2=1-way:1-way:2-way
                                                             222 means L1I :L1D:L2=2way:2way:2way
                                                             444  meansL1I :L1D:L2=4-way:4-way:4-way 
                                                              888 means L1I :L1D:L2=8-way:8-way:8-way
  2) Block size---each benchmark-- 16 means 16 kb     
                                                         32 means 32 kb  
                                                         64 means 64 kb   
                                                         128 means 128 kb     
  3)L2 cache--each benchmark-- cache size
  4)Size allocation for L1I and L1D----each benchmark-- 64.64 means L1I :L1D= 64kb:64kb                
                                                                                        128.256 means L1I :L1D= 128kb:256kb
                                                                                        256.128 means L1I :L1D= 256kb:128kb
                                                                                         256.256 means L1I :L1D= 256kb:256kb          
 5) Otimal configuration---each benchmark: This folder is for the results in step3.                