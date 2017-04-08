# Clpsm

> copy `n` parapraphs of lorem ipsum to clipboard   
   
   
### Use   

- Run w/ no arguement.
```
clpsm    // A paragraph is copied to clipboard, test w/ **ctrl+v** into text editor. nice.
```

- Run w/ number arguement. Up to **5**.
```
clpsm -n 3   // Get 3 paragraphs. sweet.
```    

---


### Setup   

1. **xclip** dependency - install w/ wtvr pkg manager 

2. Clone **clpsm** wherever you want & enter dir.
```
git clone https://github.com/ngpfontaine/clpsm.git && cd clpsm
```

3. Make it executable.
```
chmod +x clpsm
```

4. Run setup. a symlink will be created from the cloned location to **/bin/clpsm**.
```
bash clpsm -setup
```


### More
Check out my website at [nicfontaine.com](https://nicfontaine.com)  
Twitter: [@ngpfontaine](https://twitter.com/ngpfontaine)

### License
Use it, break it, complain, wtvr.
