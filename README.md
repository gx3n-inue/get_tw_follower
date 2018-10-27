# get_follower

This program acquires follower information of Twitter.
  

## system
*Python 3.6 or Later

## Download

```
>git clone https://github.com/gx3n-inue/get_follower
```

## Run
  
```
>python get_follower.py
```
  

## LICENSE
  
get_follower ver1.01    
This project is licensed under the terms of the MIT license, see LICENSE.  


## 注意
pyhon 3.7.0では、"async"予約語となっており、

```
File "(途中省略)/site-packages/tweepy/streaming.py", line 358
    def _start(self, async):
```
が発生します。

上記のエラーが表示される場合は、site-packages/tweepy/streaming.pyの async を
別の変数名に置き換えるなどしてください。
