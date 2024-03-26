# EShop
This development is about to get shopping.

The app has several use-cases such as auhtentication service,
shipping service, and user-readble console ui.

## Auhtentication

## 1. We have FileStorageBroker which works on credentials.
you can use it for add credential to the file  and get all credentials 
from the file, and it inherit from IStorageBroker.cs interface.

![](images/1.png)

![](images/2.png)
        

        
### LoginService.cs

![](images/3.png)

## 2. We have also MemoryBroker inherits from IStorageBroker.cs interface. The broker work with products and use in-memory for storing products.

### MemoryBroker.cs
![](images/4.png)



## Logging

Main is logging broker. The broker manage to log on console. It has four essential methods.

LoggingBroker.cs

![](images/5.png)


## Model

![](images/6.png)
 
## We have some sort of shipping types and you can use all of that you want.

### 1.Sea
### 2.Air
### 3.Ground  and many more

#### -Air

![](images/7.png)

#### -Ground

![](images/8.png)

#### -Sea
![](images/9.png)


### And at the end we show you main Oreder service.

![](images/10.png)

### Main part is switching the shippings using IShipping interface because every shipping type classes inherit from it. We can implement **'O'** in the __Solid__.

Setting Shipping type : 

![](images/11.png)

---

## Result.

![result](https://github.com/Hamroliyev/EShop/blob/main/Assets/result.gif)



