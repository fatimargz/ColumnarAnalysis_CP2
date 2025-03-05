# Day 2 of Columnar Analysis Workshop for C2-THE-P2 Course 2025

## Setup 
We will be using the same environment setup as done with Frank in [Day 1][https://github.com/fstrug/C2P2sem2025-PythonExercises/tree/main].

```
ssh $USER@vmlab.niu.edu
conda activate columnar_env
git clone https://github.com/fatimargz/ColumnarAnalysis_CP2.git
```

Then start the jupyter lab session. Connect to a port available to your computer (may take several tries)
```
jupyter lab --no-browser --port 8080
```

In a separate terminal, connect to the vmlab with the port used above for jupyter lab. 
```
ssh -L 8080:localhost:8080 $USER@vmlab.niu.edu
```

Copy and paste the URL from the first terminal window in a browser to open the jupyter lab session.

