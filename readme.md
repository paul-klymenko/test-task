# Test task

We have a text file where each line contains sha256 hash, e.g.:

```
c8536a06d0a62060df7318176892c5ccc640310a25158f938bf708a6fb96fff2
65c3a315a2e92d82ccd20f5ef93d8187986559f56081c9cbbd414de1ea2c0965
208c553f419c63123259a854861eb5b09412557da91572807a4ed06732b63e66
255b8302a6c134fc457b68835395b61ba4b99971f415fb8111fab542487d2ca1
...
```

This file can have 15-20 million hashes.

Write a Rest API server in python, choosing any suitable web library for implementation, which receives in json list of hashes and returns list of hashes that in the file.

Choose implementation which will work in the fastest way though think about memory efficient one to discuss.

Result should be provided as a link to GitHub repository with setup instructions.
