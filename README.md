# RAFT

<h3>Download links </h3>

```
!wget https://www.dropbox.com/s/74o2439vl4f705d/internet_freedom_scores.csv --quiet

import gdown

url = 'https://drive.google.com/u/0/uc?export=download&confirm=dxYX&id=1Did693v60aQsIy3y02jYopLqQ9dX3T13'
output = 'goverement_requests.zip'
gdown.download(url, output, quiet=True)

url = 'https://drive.google.com/u/0/uc?export=download&confirm=uAxG&id=1pw3S6t8bkSk0__RxCPfGSWwhsZuC9FDy'
output = 'notices.json'
gdown.download(url, output, quiet=True)

url = 'https://drive.google.com/u/0/uc?id=10H32wf70nBFdwlqKvU_7my3BBPc8LDuv&export=download'
output = 'csv.csv'
gdown.download(url, output, quiet=False)

url = 'https://drive.google.com/u/0/uc?export=download&confirm=zN00&id=1yNIJLQWw6ZdQPrCYVFj-2P-i996L7CEj'
output = 'rtf.csv'
gdown.download(url, output, quiet=True)

```


<h3>Pipeline</h3>



```
JSON #encoding bug
rich text to csv (ok)
pdf to csv (work in progredd)
image to csv(necessary?)
Model
```
