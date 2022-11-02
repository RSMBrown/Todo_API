API tutorial found here: https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one

PART ONE 
- I had to make a few adjustments to get it to work as it's no longer supported but I feel like it's a helpful tutorial. 
    - In spec/factories/items.rb, I had to make it 'Faker::Movies::StarWars.character' instead of 'Faker::StarWars.character'
    - In spec/factories/todos.rb, I had to make it 'Faker::Number.number(digits: 10)' instead of 'Faker::Number.number(10)'

PART TWO 
- Went alright, just kept spelling Authorize with an s

PART THREE 
- Had a few errors - guide doesn't tell you to create user first before testing 

