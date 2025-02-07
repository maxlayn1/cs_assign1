# cs_assign1

## example of using python decorator to augment a function
<code>
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
</code>

### some content again!
![Alt text](image_url) i want to add cat owl 
