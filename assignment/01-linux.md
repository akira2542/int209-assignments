# Linux assignment

## 1. Excercise File


* Create wipcamp12 directory inside your home directory
```bash
mkdir ~/wipcamp12
```
* Create programmer, website, network and ux-ui directory inside wipcamp12 directory
```bash
mkdir -p ~/wipcamp12/{programmer,website,network,ux-ui}
```
* Create slide01.txt file inside your wipcamp12 directory
```bash
touch ~/wipcamp12/slide01.txt
```
* Copy slide01.txt to slide02.txt and slide03.txt inside wipcamp12 directory
```bash
cp ~/wipcamp12/slide01.txt ~/wipcamp12/slide02.txt
cp ~/wipcamp12/slide01.txt ~/wipcamp12/slide03.txt
```
* Copy wipcamp12 directory to wipcamp13
```bash
cp -r ~/wipcamp12 ~/wipcamp13
```
* Delete slide03.txt inside wipcamp13
```bash
rm ~/wipcamp13/slide03.txt 
```
* Move slide01.txt inside wipcamp12 to newslide.txt inside wipcamp13
```bash
mv ~/wipcamp12/slide01.txt ~/wipcamp13/newslide.txt 
```
* Delete wipcamp12 and wipcamp13
```bash
rm -r ~/wipcamp12 && rm -r ~/wipcamp13
```