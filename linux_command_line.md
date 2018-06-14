
# Linux command line

## Get directory content
```
ls
```

## Remove directory
```
rm -r mydir
```
## Make directory
```
mkdir mydir
```
## Loop through all files of type in directory
```
for f in *.bz2
do 
  echo $f
done
```
can be written as
```
for f in *.bz2; do echo $f; done
```
