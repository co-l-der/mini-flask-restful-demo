
**简要描述：**

此项目为最小flask restful服务器端框架模板，可复用，方便快速搭建restful服务，项目包括以下内容

1. 一个restful接口

2. 接口参数校验

3. 错误码和异常捕获

4. 错误日志记录


**接口示例**

- ` http://localhost:5000/cat/detail`

  
**请求方式：**

- POST 

​
**请求示例**

``` 

 {

    "id": 1,

    "name": "tom",

    "gender": "male"

}

```

 **返回示例**

``` 

{

    "code": 0,

    "data": {

        "gender": "male",

        "id": 1,

        "name": "tom"

    }

}

```
