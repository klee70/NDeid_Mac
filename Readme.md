# NDeid

NDeid is a standalone identification scrubber program which doesn't require tensorflow installation or word embeddings download. Currently this program has two versions, Mac & Linux. (Mac version is temporarily unavailable.)


## Using NDeid

To use NDeid, download the repository into ZIP file and run the following commands from the terminal: 
```
unzip NDeid.zip
cd NDeid
unzip lib.zip
```

To get offsets of PHIs from '.txt' files, place target files under 'NDeid/target' folder.

```
(For Linux)
./NDeid_linux > result.txt
(For Mac)
./NDeid_mac > result.txt
```
