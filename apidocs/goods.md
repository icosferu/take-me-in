###GET /v1/goods/
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
    
###POST /v1/goods
add something to goods. returns id. requires authorization
####input example
    {
       "name":"potatoes",
       "count":5
    }
####output example
    {
       "id":"3"
    }
    
###GET /v1/goods/\<id\>
get something by its id
    
###DELETE /v1/goods/\<id\>
delete something by its id
