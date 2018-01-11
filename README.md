**1. Clone wallet sources**

```
git clone https://github.com/onezerobinary/academicwallet.git
```

**3. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../academic cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/onezerobinary/academic.git cryptonote
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
