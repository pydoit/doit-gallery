<!-- Remember:
- you are here to share your type of doit usage
- do not share your code here (consider it implementation detail)
- feel free to:
  - reorder tasks in task listing to make it more explanatory
  - remove or hide sensitive information
  - shorten text, where appropriate
- Provide at least some task listing and single example of calling a task
  - feel free to provide less information then prescribed
  - feel free to commit incomplete issue and come to it later
  - use TODO if you intend to complete something later on, remove sections you are not willing to
    describe.
-->
# Annotation
<!--- Short summary of intended use and purpose of given `doit` application.
consider User story format such as: -->

As a <!-- intended user role -->
I want to be able <!-- functionality provided -->
so that <!-- value user get from the functionality -->


# Tasks overview

<!-- list the tasks -->
```
$ doit list
paste your list of tasks here
```
<!-- if appropriate, list all tasks -->
```
$ doit list --all
paste your list of tasks here
```

# Sample usage

<!--
Show one or few typical calls of `doit` based tasks.

Always introduce the call by description of situation or motivation for given usage.
-->

# Users
<!-- Describe the type of users, their number etc. -->
- Number of users: 
- Type of user: <!-- developer living on command line; expert on data processing with no python
  skills ... -->

# `doit` added value
<!-- elaborate a bit on advantages you got by using doit based solution. -->
<!-- e.g.:
- simplified call of dificult command line constructs
- put togather more actions and allow them to be called by simple calss
- speed up processing
- share standardize way of doing things with your colleagues
- orchestrate complex set of interrelated tasks
- whatever you feel is true
-->

# Meta
<!-- Provide information about environment, where it is used, e.g.: -->
- Python:
- doit:
- OS:

# dodo file

- name of dodo file: `dodo.py` <!-- change, if different or integrated into app -->
- number of lines in dodo file:
- does it import tasks or actions from other files?: <!-- specify type of module it imports -->
- url if you share the code publicly: Not sharing/http://.... <!-- do not promis anything here -->

# command and python package dependencies
<!-- list commands (possibly with very brief description) which you are dependent on -->
Non-python based commands:
- <!-- e.g. - nmcli (network manager CLI) -->

Python based commands:
- <!-- e.g. - sphinx: sphinx-build, sphinx-apidoc (reStructuredText based doc) -->

Other python packages:
- <!-- e.g. - requests -->

# `doit` features used

<!-- No need to show off you know all features, simple is also beautiful, practical is the best -->

- [ ] subtasks
- [ ] `"file_dep"` file dependency
- [ ] `"task_dep"`: task dependency
- [ ] `"clean"` clean task
    - [ ] custom clean action
- action types (anywhere, in `"actions"`, `"clean"`, `"uptodate"`...)
    - [ ] python-action
    - [ ] cmd-action
- [ ] `"uptodate"` calculated uptodate
- [ ] `pathlib`

# More details about you
<!-- if you are willing to share -->

# Anything more

<!-- Provide any more details, which might be interesting. -->
