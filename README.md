# triumphant-hoodoo

## Use
The following is an example of basic use of the tool. At the moment this example is more of a design spec than an actual example.
```
$ hoodoo init
hoodoo project initialized
$ hoodoo add theme learn-haskell
learn-haskell theme added
$ hoodoo create goal write-todo-app
write-todo-app goal created
Note: you have created the goal "write-todo-app" without a theme. 
  To assign write-todo-app a theme, run:
    "hoodoo assign [task] [theme]"
$ hoodoo assign write-todo-app learn-haskell
write-todo-app assigned to theme: learn-haskell
```

## Use With VCS
In addition to helping individuals keep track of their tasks and goals, hoodoo 
is designed to allow clear communication between project collaborarors. hoodoo 
projects can be shared simply by checking .hoodoo into version control
