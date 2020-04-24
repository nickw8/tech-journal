# Python
### Project requirements
Export project requirements
```shell
pip3 freeze > requirements.txt
```
Install project requirements
```shell
pip3 install -r requirements.txt
```
### Dictionaries
#### Add new kv pair to dict:
```python
wordFreqDic.update( {'before' : 23} )
```
### Editing files [good guide](https://realpython.com/read-write-files-python/):
```python
with open('dog_breeds.txt', 'r') as reader:
    # Read and print the entire file line by line
    for line in reader:
        print(line, end='')
```
