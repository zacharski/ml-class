# Friday Puzzler - valid strings - optional

You can do none, one, or both

## 4 xp each



### due: by Sunday 11:59pm



### how to submit

Send me a Slack Direct message with your Python functions in a code block



### Function 1: valid strings

I consider a string to be valid if each unique character occurs an even number of times. 

```
aabbcccc
abccabcc
ccccbbaa
```

are all valid because each letter occurs an even number of times

* a = 2

* b = 2

* c = 4



```
aabbccccd
aabbccccddd
```

are both not valid because d occurs an odd number of times in both strings



**Function Description**

Complete the *isValid* function

isValid has the following parameter(s):

- *string s*: a string

**Returns**

- *string:* either `YES` or `NO`

**Input Format**

A single string . (the string length will be at least 1)



### Sample

```
isValid('aabbccccdddd')
YES
isValid('abcabc')
YES
isValid('cbadcba')
NO
```



### Function 2: Alternating Characters

from HackerRank

You are given a string containing characters `A` and `B`  only. Your task is to change it into a string such that there are no matching adjacent characters. To do this, you are allowed to delete zero or more characters in the string.

Your task is to find the minimum number of required deletions.

**Example**  

`AABAAB`

Remove an `A` at positions  1 and 4  to make   `ABAB` in  2 deletions.

**Function Description**

Complete the *ac* function (alternatingCharacters)

alternatingCharacters has the following parameter(s):

- *string s*: a string

**Returns**

- *int:* the minimum number of deletions required

**Input Format**

The first line contains an integer , the number of queries.  
The next  lines each contain a string  to analyze.

**Constraints**

- Each string  will consist only of characters `A`and  `B`.

**Samples**

```
ac('AAABBB')
4
ac('AAAA')
3
ac('ABABABA')
0
```

***Explanation**

* A**AA**B**BB**   -> 4

* A**AAA** -> 3

* ABABABA -> 0



## Helpful links

The following links may or may not be helpful



* default dictionaries from the container datatype [collections — Container datatypes &#8212; Python 3.11.1 documentation](https://docs.python.org/3/library/collections.html))

* [Iterate over characters of a string in Python]([Iterate over characters of a string in Python - GeeksforGeeks](https://www.geeksforgeeks.org/iterate-over-characters-of-a-string-in-python/))


