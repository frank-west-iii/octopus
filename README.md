# octopus
Playing with octopus merges

## fast forward

```
*   3d3e086 - (HEAD -> master, origin/master) Merge branches 'about' and 'contact' (3 seconds ago)
|\
| * e93baee - (contact) Add contact (4 minutes ago)
* | fc1d516 - (about) Add about (3 minutes ago)
|/
* e519b60 - Add home (5 minutes ago)
* 229eaad - First commit (6 minutes ago)
```

vs.

```
*   6db4f71 - (HEAD -> master) Merge branch 'contact' (3 seconds ago)
|\
| * e93baee - (contact) Add contact (4 minutes ago)
* | fc1d516 - (about) Add about (3 minutes ago)
|/
* e519b60 - Add home (5 minutes ago)
* 229eaad - First commit (6 minutes ago)
```

## no fast forward

```
*   29e8fd7 - (HEAD -> master) Merge branch 'contact' (3 seconds ago)
|\
| * e93baee - (contact) Add contact (4 minutes ago)
* |   3f53986 - Merge branch 'about' (13 seconds ago)
|\ \
| |/
|/|
| * fc1d516 - (about) Add about (3 minutes ago)
|/
* e519b60 - Add home (5 minutes ago)
* 229eaad - First commit (6 minutes ago)
```

vs

```
*   3524555 - (HEAD -> master) Merge branch 'contact' (3 seconds ago)
|\
| * e93baee - (contact) Add contact (4 minutes ago)
* |   8ba5433 - Merge branch 'about' (13 seconds ago)
|\ \
| |/
|/|
| * fc1d516 - (about) Add about (3 minutes ago)
|/
* e519b60 - Add home (5 minutes ago)
* 229eaad - First commit (6 minutes ago)
```
