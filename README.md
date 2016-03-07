## RAILS: Router Challenge



* The view does an `if params[:name]` check.  This is a code smell.  How could you do this better?

* Since :name is "truthy", I believe that if statement will always return true.  I would maybe add something like:
  if params[:name] == "name"


* The best approach for storing environment variables is to export them in a bash profile.

* No, if you use the fixtures, then you don't need to run migrations on the test database.
