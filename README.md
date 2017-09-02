# Github-search (v1.0)

`github-search` searches for repositories on `http://www.github.com` from given keywords.

## Install

    dpkg -i github-search_1.0-1.deb

## Overview

The number of pages of search results can be specified by `NPAGES`.

The number of pages of search  results  can  be  specified  by `NPAGES`.  Default number of page is set to 5 but can be changed by changing the variable  `DEFAULT_NUMBER_OF_PAGES`  defined  in `/usr/bin/github-search`.

If `NPAGES` is set to 0, `github-search` looks for all pages.

Flags -n and -N gives the number of found repositories and the number of result pages respectively.

## Synopsis

       github-search [-n] [-N] [ -p NPAGES ] [ -h|--help ] [ -v|--version ] KEYWORD  

## Examples

       # github-search -p 1 "bash script" 
       http://github.com/eshiota/bash
       http://github.com/hannob/bashcheck
       http://github.com/cfenollosa/bashblog
       http://github.com/ppaskowsky/Bash
       http://github.com/knowledge-club/bash
       http://github.com/fideloper/Vaprobash
       http://github.com/sodonnell/bash
       http://github.com/jmcantrell/bashful
       http://github.com/awesome-lists/awesome-bash
       http://github.com/riobard/bash-powerline
