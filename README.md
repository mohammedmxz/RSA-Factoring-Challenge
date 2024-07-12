# [RSA Factoring Challenge](https://en.wikipedia.org/wiki/RSA_\(cryptosystem%29) 💪

## [Mission Statement](https://www.youtube.com/watch?v=tGSUjuSBt1A)

* We've intercepted an unsecured network and discovered numbers used to encrypt critical documents. It appears these numbers aren't always generated using sufficiently large prime numbers. Your mission, should you choose to accept it, is to factorize these numbers as quickly as possible before the target patches this vulnerability on their server, enabling us to decode the encrypted documents.

## Requirements
* Operating System: Standard Ubuntu 20.04 LTS

## Provided Resources
* [How does HTTPS provide security?](https://stackoverflow.com/questions/3968095/how-does-https-provide-security)
* [Prime Factorization](https://privacycanada.net/mathematics/prime-factorization/)
* [Why RSA?](https://jaredatandi.hashnode.dev/rsa-factoring)

## Tasks 📜

+ [ ] **0. Factorize all the things!**<br/>_**[factors](factors)**_ - Factorize as many numbers as possible into a product of two smaller numbers.
  + **Usage:** `factors <file>`
      + `<file>` is a file containing natural numbers to factorize.
      + One number per line.
      + Assume all lines will be valid natural numbers greater than 1.
      + There will be no empty lines, and no spaces before or after the valid numbers.
      + The file will always end with a new line.
  + **Output format:** `n=p*q`
      + One factorization per line.
      + `p` and `q` do not have to be prime numbers.
  + You can process the numbers in the file in any order.
  + Your program should run without any external dependencies; you cannot install anything on the machine where your program will be executed.
  + **Time limit:** Your program will be terminated after 5 seconds if it has not completed.
  + Push all your scripts, source code, etc., to your repository.
      + We will only run your executable `factors`.
      
+ [ ] **1. RSA Factoring Challenge**<br/>_**[rsa](rsa)**_ - According to RSA Laboratories, for each RSA number `n`, there exist prime numbers `p` and `q` such that `n = p × q`. The task is to find these two primes given only `n`.
  + This task is similar to task 0, except:
    + `p` and `q` are always prime numbers.
    + There is only one number in the file.
  + How far can you get in less than 5 seconds?
    + **Read:** [RSA Factoring Challenge](https://en.wikipedia.org/wiki/RSA_Factoring_Challenge)
