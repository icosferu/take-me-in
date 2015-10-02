###GET /goods/
show all goods that we have
####input example
    {
       "reminders_count":1,
       "reminders":[
          {
            "id":1,
            "user":"Admin",
            "name":"My reminder",
            "date":"31-12-2015",
            "time":"23-59"
            "moderators":[
                "Admin"
            ]
          }
       ]
    }
###GET /goods/\<username\>/
show what goods has \<username\>
###POST /goods/\<something\>
add something to goods. returns id. requires authorization
###DELETE /goods/\<id\>
delete something by its id
