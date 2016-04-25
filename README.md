# Kalk
  Execute a command line calculator written in Perl

## SYNOPSYS
    $ kalk [-h] [-v] expression

## DESCRIPTION
  This script reads command arguments as one algebraic expresseion, calculates it, and prints the answer with the input expression. Numbers can contain either commas or spaces in themselves like 1,017,283.
  
## OPTIONS
    -h  Print help
    -v  Print script name with its version

## EXAMPLES
    $ perldoc kalk
    $ kalk -h
    $ kalk -v
    $ kalk 9+5
    $ kalk 2**8
    $ kalk '(57+139)*1.05/2'
    $ kalk sqrt 3
    $ kalk 1,017,283 + 1,327,720

## AUTHOR
  Coded by Kohji OKAMURA, Ph.D

## HISTORY
  Apr 14, 2005  The initial version as calc.pl  
  Apr 18, 2005  Minor modification  
  May 31, 2007  POD and error message are added  
  Jan 23, 2009  Modified a little (use warnings etc.)  
  Mar 17, 2010  Accept commas  
  Oct 13, 2010  Minor modification  
  Jul 31, 2012  Print original input expression  
  Apr 25, 2016  Renamed as Kalk from calc; released as Kalk ver. 1.0  
