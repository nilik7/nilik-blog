---
layout: post
title:  "prime number encoding"
date:   2023-11-17 09:00:00 +0000
tags: [数学，奇想]
usemathjax: 
---


Today, I just throught of turning a number into a more complex number using prime numbers, I know in real life, prime number is used in security and etc.

Here is what I did:

For example:

<p>
START: Encode 832 <br>
-> 2*2*2*2*2*2*13 <br>
22222213 <br>
-> 13*17*193*521 <br>
1317193521 <br>
->3*7*62723501 <br>
376273501 <br>
-> 3*3*19*2004231 <br>
33192004231 <br>
-> 3*7*13*17*331*216071 <br>
27131733126071 <br>
-> 11*11*17*109*193*8580787 <br>
111117109193850787 <br>
-> 3*7*3541*10111*1477888271 <br>
373541101111477888271 <br>
-> 2*3*3*3*3*7*11*23*107*173*45319*155201 <br>
233337112310717345319155201 <br>
...
and continue the process until a prime is reached. <br>
(the prime factors are arrranged from smallest to largest)

For encoding, it is one to one.
However, for decoding, it can be many to one, or no results.

For exmaple:

Decode 987654323
-> no results

Decode 10453
-> no results



Decode 25971 <br>
</p>

| 2×5×19×71 | or | 2×51971 |
|---|---|---|
|  =13490 |   | =103942  |
| END  |   | END  |

I did this for fun, I am not sure if it is possible to get a final prime number for any number. For decoding, it is easy to find the original number.

If anyone knows how to do it, or if there has already been a similar/same sort of problem, please tell me. ;)


