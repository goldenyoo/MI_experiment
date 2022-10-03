# trying_svm
### raw data
##### channel_selection = [5 7 8 13 14 15 18 19];
|Data|Accuracy|Memo|
|------|---|---|
|DY|0.55||
|GC|0.49||
|1|||


### KA After_bpf_notch, *together*
#### Only K
##### channel_selection = 1:19;
|Data|chop|Accuracy|
|------|---|---|
|DY|32|0.52|
|DY|64|0.49|
|DY|128|0.44|
|GC|32|0.52|
|GC|64|0.46|
|GC|128|0.45|
|1|||

#### Only A
##### channel_selection = 1:19;
|Data|chop|Accuracy|
|------|---|---|
|DY|32|0.51|
|DY|64|0.49|
|DY|128|0.48|
|GC|32|0.49|
|GC|64|0.49|
|GC|128|0.48|
|1|||

#### K A
##### channel_selection = 1:19;
|Data|chop|Accuracy|
|------|---|---|
|DY|32|0.53|
|DY|64|0.50|
|DY|128|0.49|
|GC|32|0.50|
|GC|64|0.48|
|GC|128|0.46|
|1|||
