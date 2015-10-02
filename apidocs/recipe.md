##Recipe format
a recipe is a taste of some food or combination of two or more kinds of food.
for example: I like tomatoes. And I like cheese. But tomatoes are much more
tasty with cheese, aren't?
three recipes illustrating this:
#
    {
       "goods_count":1,
       "goods":[
          "tomatoes"
       ]
        "taste":10
    }
    {
       "goods_count":1,
       "goods":[
          "cheese"
       ]
        "taste":8
    }
    {
       "goods_count":2,
       "goods":[
          "tomatoes", "cheese"
       ]
        "taste":100500
    }

###PUT /v1/recipes/\<recipe\>
add a recipe. returns id
###DELETE /v1/recipes/id
delete a recipe by its id
###GET /v1/recipes/
show all recipes
