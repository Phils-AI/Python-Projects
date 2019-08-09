# Python-Projects

# pip skillset

If you want to share your project and you do have a lot of dependencies, go and make a requirements.txt file.
Create a new folder e.g. "project" - put all you code into a new folder "description/of/function" e.g. "converter"
Inside projects create a new folder "scripts" , cd into it and call:

```python
pip freeze > requirements.txt 
```

Now you have writen all your pip requirements into this file with every needed version.
If you want to improve - go and delete the ones one do not need to run your project.

It should look like this if you want it nice and clean: 
    .
    ├── ...
    ├── projects                    # parent folder
    │   ├── project_one             # seperat folder for project one
    │   ├── projects_two            # seperat folder for project two
    │   └── scripts                 # folder for all the dependencies and requirements one need
    │       └── requirements.txt    # txt file to install all requirements
    └── ...
    
var routes = (
  <Route name="App">
    <Route name="Admin">
      <Route name="Users"/>
      <Route name="Reports"/>
    </Route>
    <Route name="Course">
      <Route name="Assignments"/>
    </Route>
  </Route>
);

You can install all the requirements calling:
```python
pip install -r requirements.txt
```
