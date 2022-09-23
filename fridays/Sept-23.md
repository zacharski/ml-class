# 3 Question Friday

Earn 10xp by Slack direct messaging me the answers by Sept 30.

## 1. numpy Euclidean distance

I want to compute the Euclidean distance between two one dimensional arrays. For example 

```python
x = np.array([1, 2, 3])
y = np.array([3, 5, 7])
```

My function is 

```python
def euclidean(a, b):
  squared = np.square(a - b).sum()
  return squared

euclidean(x, y)
```

but it doesn't give the correct results. Can you fix it?

## 2. Loading a dataframe

I have a file called `evs.csv` that looks like

```
Ioniq 5,AWD,256,77.4,239,98,5.0
Tesla Model 3,AWD,315,80,298,113,3.1
Rivian R1T,AWD,316,135,562,70,3.0 
VW ID.4,RWD,260,82,260,107,7.7
F150 Lightning,AWD,230,110,318,68,4.0
```

I want the column named as follows:

| Make           | Drive | Range | Battery_kwH | PeakPower_kW | MPGe | 0-60 |
|:-------------- |:----- | -----:| -----------:| ------------:| ----:| ----:|
| Ioniq 5        | AWD   | 256   | 77.4        | 239          | 98   | 5.0  |
| Tesla Model 3  | AWD   | 315   | 80          | 298          | 113  | 3.1  |
| Rivian R1T     | AWD   | 316   | 135         | 562          | 70   | 3.0  |
| VW ID.4        | RWD   | 260   | 82          | 260          | 107  | 7.7  |
| F150 Lightning | AWD   | 230   | 110         | 318          | 68   | 4.0  |

When I load the file into a DataFrame using

```python
evs = pd.read_csv('evs.csv')
evs
```

It is missing the column names. How do I use `read_csv` and have the correct column names?



## 3. Lazy

What is the difference between an lazy learner and a eager learner? What is the kNN algorithm?


