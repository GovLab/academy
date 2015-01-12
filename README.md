# academy

## install the latest version of staticjinja
```
pip install git+git://github.com/Ceasar/staticjinja#egg=staticjinja
```

## commands for building
```
mkdir -p site
staticjinja build --outpath ./site --static static
staticjinja watch --outpath ./site --static static
(cd site; python -m SimpleHTTPServer &)
```

## Basic Folder Structure
- site        --*generated static site*
- templates   
  - static    
  - layout    --*base layout templates*


### Backup
I kept this as a backup in case we need it for reference
https://github.com/claudioccm/academy
