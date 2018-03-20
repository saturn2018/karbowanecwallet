**1. Clone wallet sources**

```
git clone https://github.com/saturn2018/saturnwallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../saturn cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/saturn2018/saturn.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
