# Artur Rakuts
***
## Junior web developer
***
### Contact info:
* **Phone:** +375(33)654-65-58
* **E-mail:** arturrakut@gmail.com
* **Telegram:** @swoopi215
* **[Codewars](https://www.codewars.com/users/swoopi215)**
* **[Leetcode](https://leetcode.com/swoopi215/)**
---
### About me:
I'm 25 y.o. dota 2 enjoyer and now I'm constantly in a study. 
I graduated from university in 2020. After that I've worked for profession 2 years. It was civil engineering. 

Every day I try to improve my English knowledge and programming skills. 
Especially, I like to solve catas on the [Codewars](https://www.codewars.com/users/swoopi215).

I hope to become a programmer one day, but now I have to learn more, cuz nowadays requirements for Jun pos are high.

---
### Skills:
#### Frontend
* HTML5 (basic)
* CSS3 (basic)
* Bootstrap
#### Backend
* Python
* Django
#### Databases
* Postgesql
#### Tools
* Git(basic)
* Linux(basic)
* Pycharm
* Adobe Photoshop
* AutoCAD
---
### Code example:

**Snail Sort** from [Codewars](https://www.codewars.com/kata/521c2db8ddc89b9b7a0000c1).

Given an ```n x n``` array, return the array elements arranged from outermost elements to the middle element, traveling clockwise.
```
array = [[1,2,3],
         [4,5,6],
         [7,8,9]]
snail(array) #=> [1,2,3,6,9,8,7,4,5]
```
NOTE: The idea is not sort the elements from the lowest value to the highest; the idea is to traverse the 2-d array in a clockwise snailshell pattern.

NOTE 2: The 0x0 (empty matrix) is represented as en empty array inside an array [[]].
```
def snail(array):
    results = []
    while len(array) > 0:
        # go right
        results += array[0]
        del array[0]

        if len(array) > 0:
            # go down
            for i in array:
                results += [i[-1]]
                del i[-1]

            # go left
            if array[-1]:
                results += array[-1][::-1]
                del array[-1]

            # go top
            for i in reversed(array):
                results += [i[0]]
                del i[0]

    return results
```
### Education
Institution|      Duration       |Note
:---:|:-------------------:|:---:
Polotsk State University|     2015 - 2020     |Civil engineering
Itstep | Nov 2021 - Aug 2022 |Python for web development
English scholl|       Dec 2022 - atm. | Studying English in progress      
---