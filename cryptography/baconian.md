# Bacon's Cipher
Bacon's cipher or the Baconian cipher is a method of steganographic message encoding devised by Francis Bacon in 1605. A message is concealed in the presentation of text, rather than its content.

> ## Encoding
To encode a message, each letter of the plaintext is replaced by a group of five of the letters 'A' or 'B'. This replacement is a 5-bit binary encoding and is done according to the alphabet of the Baconian cipher (from the Latin Alphabet), shown below:

|letter|  a   |  b   |  c   |  d   |  e   |  f   |  g   |  h   | i, j |  k   |  l   |  m   |  n   |  o   |  p   |  q   |  r   |  s   |  t   | u, v |  w   |  x   |  y   |  z   |
|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
|code  |aaaaa |aaaab |aaaba |aaabb |aabaa |aabab |aabba |aabbb |abaaa |abaab |ababa |ababb |abbaa	|abbab |abbba |abbbb |baaaa |baaab |baaba |baabb |babaa |babab |babba |babbb |
|binary|00000 |00001 |00010 |00011 |00100 |00101 |00110 |00111 |01000 |01001 |01010 |01011 |01100 |01101 |01110 |01111 |10000 |10001 |10010 |10011 |10100 |10101 |10110 |10111 |

The writer must make use of two different typefaces for this cipher. After preparing a false message with the same number of letters as all of the As and Bs in the real, secret message, two typefaces are chosen, one to represent As and the other Bs. Then each letter of the false message must be presented in the appropriate typeface, according to whether it stands for an A or a B.

To decode the message, the reverse method is applied. Each "typeface 1" letter in the false message is replaced with an A and each "typeface 2" letter is replaced with a B. The Baconian alphabet is then used to recover the original message.

Any method of writing the message that allows two distinct representations for each character can be used for the Bacon Cipher. Bacon himself prepared a Biliteral Alphabet for handwritten capital and small letters with each having two alternative forms, one to be used as A and the other as B. This was published as an illustrated plate in his De Augmentis Scientiarum (The Advancement of Learning).

Because any message of the right length can be used to carry the encoding, the secret message is effectively hidden in plain sight. The false message can be on any topic and thus can distract a person seeking to find the real message.

> ## Example
The word 'steganography', encoded with quotation marks, where standard text represents "typeface 1" and text in boldface represents "typeface 2":

**T**o en**co**de **a** mes**s**age e**ac**h letter **of** the **pl**a**i**nt**ex**t **i**s replaced b**y** **a g**rou**p of f**i**ve** o**f t**he l**et**te**rs 'A' or 'B'.**
The pattern of standard and boldface letters is:

ba aabbaa b aaabaaa abba aaaaaa bb aaa bbabaabba ba aaaaaaaa ab b baaab bb babb ab baa abbaabb 'b' bb 'b'.
This decodes in groups of five as

baaab(S) baaba(T) aabaa(E) aabba(G) aaaaa(A) abbaa(N) abbab(O) aabba(G) baaaa(R) aaaaa(A) abbba(P) aabbb(H) babba(Y) bbaaa bbaab bbbbb
where the last three groups, being unintelligible, are assumed not to form part of the message.

### Now you try!
What does the text below mean? We've already done the first step for you!

ABAAA BAABBAABAA AAABBABAAABAAABAAABAABBABBAABBAABAABAAAAAABAAAAABB BAAABABBABABABBAABAABAABAAABBBABAAAABBAAAABBA ABAAA AAABAAAAAAABBAABAABA ABBBABAABBBAABA BAABAAABBBABAAABAAAB ABAAAABBAA BAABAAABBBAABAA ABBAAABBABBAAAAABABBAAAAAABABA AAABBABBABAAABABAAAB ABBABBAAAA BAABAAABBBAABAABABBA ABABAABABA BAAABAABAAAABAA AABBBABBABABBBAAABAAAABABBAABBABABAABABABABBA BAABAAABBBAABAABABBA AAABBABBABABBAA BAABA AAAABABBABBAABAAABBBAABAABAAAA BAABAABBAB AAABBAABAAAAABAABBABAAABBAABAA BAABAAABBBABAAABAAAB BAABAAABBBAABAABABBA BAAAAAABAA BAABABAAAABABBAABAAAABBAAAABBA BAABAABBAB BAAAAAABAAABBBAABABAAAAAAAAABAAABAA ABABBAABAA BABAAABAAABAABAAABBB AAAAAABBAA AAAAAABAAA
