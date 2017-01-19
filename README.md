## Today I learned
`enca file.txt -L czech` - **detect encoding** of the *file.txt*, assume it's in *czech*.  
`enca file.txt -L czech -x utf-8` - **detect and convert encoding** of the *file.txt* to *utf-8*, assume it's in *czech*.  

`vim -p $(grep -rl '#warn')` - **open all files containing** "*#warn*" as tabs in vim. search current directory recursively.
