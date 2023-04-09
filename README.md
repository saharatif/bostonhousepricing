# bostonhousepricing

Clone the repository

Create new environment 

```conda create -p boston python==3.9 -y
   conda activate boston/
   pip install -r requirements.txt
   conda install -c anaconda scikit-learn 
```
Kill the PID 
```
lsof -i tcp:5000
kill -9 <PID>
```