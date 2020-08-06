# splitter
Re implementation of the Linux split utility in Go

## Why though
I wanted a way to split a file into X parts without first getting the current size or line count. 

## Install or Download
Head over the releases page to download a precompiled version or build it yourself with `go get https://github.com/jordanpotti/splitter`

## Usage

```
Usage of ./splitter:
  -numb int
        Number of files to split the target file into (default 2)
  -post string
        String to append to the output file
  -pre string
        String to prepend to output file
  -target string
        Target File to split
````

Thanks @jordanpotti
