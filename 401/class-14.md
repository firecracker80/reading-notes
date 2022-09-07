# Reading Assignment 14

>## Intro to password hashing
>
>Hashing is a mathematical algorithm, described as a "one-way mechanism" used to map through any size data into bits of fixed size string. The fixed size part of that is the *hash*. This function has the following key properties:
> - easy and practical to compute the hash, but "difficult or impossible to re-generate the original input if only the hash value is known."
> - difficult to create an initial input that would match a specific desired output.
><!-- Retreived from auth0.com.  -->
>Hashing is ideal for password storage, because it is deterministic. That means that as long as the input is the same, it will always produce the same output. Important in authentication.
>
>## bcrypt overview
>
>Based on the Blowfish block ciphe cryptomatic algorithm and is adaptive. Because bcrypt uses a key factor, it is able to mitigate the cost of hashing. This makes it resistant to hacking. Hashing needs to be done slowly. bcrypt slows down hashing significantly by compensating powerful computers.
>
>## jBCrypt 
>
>A java implementation of OpenBSD Blowfish hashing code. This system uses a modified version of Bruce Schneier's Blowfish block cipher to hash passwords, increasing the difficulty of off-line password cracking and impeding hardware implementation. The algorithm's calculation cost is parametrized, allowing it to scale with the speed of computers. The goal is to decrease the likelihood that an attacker will learn the plaintext passwords from a compromised password database.

>## Things I want to know more about...
>Explain it's limitations better.