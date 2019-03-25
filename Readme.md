# NDeid_mac

NDeid is a standalone identification scrubber program which doesn't require tensorflow installation or word embeddings download. Currently this program has two versions, Mac & Linux.
(For Linux compatible version: https://github.com/klee70/NDeid)


## Using NDeid_mac

To use NDeid, download the repository into ZIP file and run the following commands from the terminal: 
```
unzip NDeid_mac-master.zip
cd NDeid_mac-master
unzip lib.zip
```

To get offsets of PHIs from '.txt' files, place target files under 'NDeid_mac-master/target' folder.

```
./NDeid_mac > result.txt
```
