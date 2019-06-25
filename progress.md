my progress

25.06
New commands:
q-  to exit log
rails test 
rails generate
rails destroy
touch (for example:  app/views/static_pages/about.html.erb)- update timestamp or create new file if doesn't exist)
mv file new name (for example: mv app/views/layouts/application.html.erb layout_file) to change file names
assert_select- tests for the presence of a particular HTML tag

New concepts: 
TDD- development where the failing test should be written before the code

Troubleshooting: 
"Bundler::LockfileError": delete gemfile.lock and then run command bundle install


24.06
Listing 3.7
git add -A
git commit -m ""
git push -u origin branch name

07.06: 
3.2 static pages, https://www.railstutorial.org/book/static_pages.  
Just deployed app to heroku at https://secure-basin-83669.herokuapp.com/, using command git push heroku master.
Also had to follow tutuorial here to fix heroku errorhttps://github.com/heroku/cli/issues/590