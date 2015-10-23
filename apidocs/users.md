###GET /v1/users/\<username\>/goods
show what goods has \<username\>
####output example
    {
       "goods_count":2,
       "goods":[
          {
            "name":"chocolate",
            "count":1000
          },
          {
            "name":"tea",
            "count":1
          }
       ]
    }
###POST /v1/users/\<nickname\>
create a new user
###GET /v1/users/
show all users (now it only gives they names, but in future some other info will be added
####output example
    {
       "users_count":2,
       "users":[
          {
            "name":"John",
          },
          {
            "name":"Kate",
          }
       ]
    }
