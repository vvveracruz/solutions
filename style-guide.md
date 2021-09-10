# Style Guide

Style guidelines for documents in this repo will go here.

## Folder structure
- Only the name of the book is required unless there are multiple with names that might be confused with each other
- Shortening filler words is ok (eg: introduction -> intro, elementary -> elem, etc), shortening key words is not good practice (eg: number theory -> num th, calculus -> calc)

## Makefiles

I'm using makefiles to generate the pdfs just because it's simple and more or less independent of 
installation (although not OS...)

This also makes it very easy to keep the build files separate, and `make clean` will clean them.