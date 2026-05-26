# WordCount-Using-MapReduce-Hadoop

## Hands-On Assignment ITCS6190

The purpose of this assignment is to understand how Hadoop MapReduce works by running a simple word count example in a Docker-based Hadoop environment.

## Approach and Implementation

### Mapper Logic

The Mapper reads each line from the input file and breaks the line into individual words using `StringTokenizer`.

Each valid word is emitted as a key-value pair:

```text
word, 1
