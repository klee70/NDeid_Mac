# NDeid_mac

NDeid is a standalone identification scrubber program which doesn't require tensorflow installation or word embeddings download. Currently this program has two versions, Mac & Linux.
(For Linux compatible version: https://github.com/klee70/NDeid)

## Currently NDeid_mac's running on the installation of protobuf3.6.0 which can be found -
Source code https://github.com/protocolbuffers/protobuf/releases/download/v3.6.0/protobuf-all-3.6.0.zip \n
How to install https://medium.com/@erika_dike/installing-the-protobuf-compiler-on-a-mac-a0d397af46b8

We're going to remove this dependency in near future.

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
