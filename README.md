API tutorial found here: https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one

PART ONE 
- I had to make a few adjustments to get it to work as it's no longer supported but I feel like it's a helpful tutorial. 
    - In the requests/items_spec.rb and requests/todos_spec.rb, I had to replace all 'json' with 'JSON.parse(response.body)'
    - In spec/factories/items.rb, I had to make it 'Faker::Movies::StarWars.character' instead of 'Faker::StarWars.character'
    - In spec/factories/todos.rb, I had to make it 'Faker::Number.number(digits: 10)' instead of 'Faker::Number.number(10)'

