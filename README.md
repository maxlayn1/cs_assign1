# cs_assign1

## example of using python decorator to augment a function
```python
def main():

    number = 2
    new_number = increment_by_one(number)
    print('Original number:', number)
    print('Number incremented by decorator:', new_number)

def increment_by_101_instead(func):
    def wrapper(*args):
        temp = args[0] + 100
        return func(temp)
    return wrapper

@increment_by_101_instead
def increment_by_one(num):
    return num + 1

main()
```

### and here is a picture of Masha!
![A black cat sitting next to a cat tree](https://github.com/user-attachments/assets/27c416a9-3299-4f80-a0d2-08d68ef0f438)

