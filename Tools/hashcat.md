From the [Hashcat Wiki](https://hashcat.net/wiki/)

Core attack modes
    [[Dictionary attack]] - trying all words in a list; also called “straight” mode (attack mode 0, -a 0)
    [[Combinator attack]] - concatenating words from multiple wordlists (-a 1)
    [[Brute force]] attack and Mask attack - trying all characters from given charsets, per position (-a 3)
    [[Hybrid attack]] - combining wordlists+masks (-a 6) and masks+wordlists (-a 7); can also be done with rules
    [[Association attack]] - use an username, a filename, a hint, or any other pieces of information which could have had an influence in the password generation to attack one specific hash (-a 9)

Other attacks
    Rule-based attack - applying rules to words from wordlists; combines with wordlist-based attacks (attack modes 0, 6, and 7)
    Toggle-case attack - toggling case of characters; now accomplished with rules

