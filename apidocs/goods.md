###GET /goods/
show all goods that we have
####output example
    {
       "goods_count":2,
       "goods":[
          {
            "name":"chocolate",
            "contributor":"John",
            "count":1000
          },
          {
            "name":"tea",
            "contributor":"John",
            "count":1
          }
       ]
    }
###GET /goods/\<username\>/
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
###POST /goods/\<something\>
add something to goods. returns id. requires authorization
####input example
    {
       "name":"potatoes",
       "count":5,
       "auth_hash":f2f044efa176ac107db
    }
###DELETE /goods/\<id\>
delete something by its id
