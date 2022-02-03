# python-proje-
flat list


#proje 1:


input: [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

output: [1,'a','cat',2,3,'dog',4,5]

## Cod
```
 l=[[1,'a',['cat'],2],[[[3]],'dog'],4,5]
 
 l2=[]
for i in l:
    if type(i)==list:
        for e in i:
            if type(e)==list:
                for d in e:
                    if type(d)==list:
                        for k in d:
                            l2.append(k)
                    else:        
                        l2.append(d)
                  
            else:        
                l2.append(e)
    else:
        l2.append(i)
        
 print(l2)
 output =  [1, 'a', 'cat', 2, 3, 'dog', 4, 5]
 ```
 ## proje 2
 ```
 l3=[[1, 2], [3, 4], [5, 6, 7]]
 l3.sort(reverse=True)
 
 for i in range (len(l3)):
 l3[i].sort(reverse= True)
 
 print(l3)
    [[7, 6, 5], [4, 3], [2, 1]]
    ```
 

 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
