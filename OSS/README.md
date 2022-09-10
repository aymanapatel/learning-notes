# Table of contents

- [License and OSS Fundamentals](#license-and-oss-fundamentals)
  * [License vs Contract](#license-vs-contract)
    + [Unilateral vs B-lateral Contract](#unilateral-vs-b-lateral-contract)
    + [Role of copyright, trademarks and patents](#role-of-copyright--trademarks-and-patents)
  * [OSS Principles](#oss-principles)
- [Licenses](#licenses)
  * [BSD: The first OSS License](#bsd--the-first-oss-license)
  * [GPL](#gpl)
  * [MIT](#mit)
    + [Apache](#apache)
    + [Permissive vs copyleft license](#permissive-vs-copyleft-license)
- [Non-software](#non-software)
  * [Creative Commons](#creative-commons)
    + [Attributes](#attributes)
    + [Restrictions](#restrictions)
  * [Multiple license compatibility](#multiple-license-compatibility)
  * [Dual licensing](#dual-licensing)
  * [Contributor License Agreement (CLAs)](#contributor-license-aggreement--clas-)
  * [Patent Promise](#patent-promise)


# License and OSS Fundamentals

## License vs Contract

Contracts are means of exchange or promise of exchange, while License are requirements for fair use of the product.

### Unilateral vs B-lateral Contract

- **Bilateral Contract** is contractual obligation that is open to bargain for means of exchange which can be money.
- **Unilateral Contract** is a promise from one party to another for a contractual obligation that cannot be negotiated.

### Role of copyright, trademarks and patents

1. Copyright: Exclusive legal right to use and distribute work. Work needs to tangible and use 
2. Trademarks: A word or symbol that descirbe a company or service. 
			It differes from copyright in the fact that trademarks do not entail a creative work which is part of a copyrighted material
3. Patents: Exclusive right to make, use and sell invention.


## OSS Principles

Interception of Intellectual Property and OSS Licenses yields OSS Principles. Open source is much more than code that is openly avaialble.

10 factors are required for the software to be considered as open source.
These include,

1. Free redistribution: Code that you create can be used for monetization but the code that you depend on, (i.e. your dependencies) cannot be charged for financial gain.
2. Must provide source code.
3. Must allow derived works: The whole goal of open source is collaboration. Without allowing works to be derived using Pull Requests, your project will not be enhanced by peers who are more experienced in the software stack.
4. Integrity of author's code must be maintained: Need to maintain who contributed a specific piece of code. This includes CLA agreement.
5. No discrimination against a person or a particular group: Open source thrives on diversity .
6. No discrimination against field of endevour
7. Distribution of only one license required to secure rights. A LICENSE page is usually placed at the source
8. License must not be speicfic to product: Product cannot be identified as Open source for a particular distribution platform. For example, you cannot have a package be open source for Ubuntu while it is closed-source for Mac. 
9. License must not restrict other software: This means that the license project cannot impose restrictions on other software that is distributed with licensed software.
10. License must be techincally neutral: This means that the project can work on different platforms and there is no lock-in.






# Licenses

Look this [site](https://choosealicense.com/) to get hold of all possible licenses

## BSD: The first OSS License

Initial licenses were created at Universities. BSD license was created by UC Berkley in 1990. It was used for the BSD OS, a Unix-like operating system.
It is a permissive license. 
BSD licnese 1 is not a OSI approved for its 'advertising clause" which requred acknowledgement that the software is developed by UC Berkely and its contributors.
This clause was later removed in the subsequent revisions to make it OSS compliant.


## GPL
> Copyleft

If you want to make sure your open source code does not end up in proprietary software, use **GPL**




## MIT
> Academic and Permissive

Anyone one is alowed to use, copy, modify, merge, distribute, publish or sell the software. However, it does not it explicit on how to share modifications.
It also does not tell anything about patent sharing.

### Apache
> Permissive

It is the most commecial favourable license. It has an embedded implicit CLA.


### Permissive vs copyleft license

Copyleft: It is an arrangement by which any work can be ditributed freely and also derived.

Strong copyleft

- Example: GPLV3
- Combining GPL with non-GPL will result in code that is GPL

Weak copyleft: 
- Example: LGPL
- Distribution of binary files does not affect the target code that uses the bonary files.


# Non-software

## Creative Commons

A non-software copyleft license for non-software domain.


### Attributes
The creator needs to be credited for the work.

### Restrictions
1. Share Alike 
2. Noncommercial
3. No derivateives

Check [Creative Commons licenses](https://creativecommons.org/licenses/) for more information on restirictions
Check [Creative Commons Choose](https://creativecommons.org/choose) for more information on choosing the creative commons license.

## Multiple license compatibility

A project with 2 licenses is possible only when the source license in included in the destination license
There are no license compatibility issues amongst the permissive licenses.
| Source    | Destination | Feasible |
|-----------|--------------|----------|
| Apache    | GPL V3       | Yes      |
| GPL V3    | Apache       | No       |
| MIT       | GPL V2/V3    | Yes      |
| GPL V2/V3 | MIT          | No       |


## Dual licensing

JQuery was under MIT and GPL.
Now it has moved to Permissive license, MIT.

## Contributor License Aggreement (CLAs)

Apache has implicit CLA.
Best practive to have a **explicit CLA**
CLA makes it explicit that contributors are transferring parent right to the project/software.

## Patent Promise

A promise to not enforce patent rights.




