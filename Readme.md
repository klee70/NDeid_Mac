# NDeid

NDeid is a standalone identification scrubber program which doesn't require tensorflow installation or word embeddings download. Currently this program has two versions, Mac & Linux.
(For Linux compatible version: https://github.com/klee70/NDeid)


## Using NDeid

To use NDeid, download the repository into ZIP file and run the following commands from the terminal: 
```
unzip NDeid_Mac-master.zip
cd NDeid_Mac-master
unzip lib.zip
```

To get offsets of PHIs from '.txt' files, place target files under 'NDeid_Mac-master/target' folder.

```
./NDeid_mac > result.txt
```
