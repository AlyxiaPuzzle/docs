# Book Cipher

A book cipher, or Ottendorf cipher, is a cipher in which the key is some aspect of a book or other piece of text. Books, being common and widely available in modern times, are more convenient for this use than objects made specifically for cryptographic purposes. It is typically essential that both correspondents not only have the same book, but the same edition.

Traditionally book ciphers work by replacing words in the plaintext of a message with the location of words from the book being used. In this mode, book ciphers are more properly called codes.

This can have problems; if a word appears in the plaintext but not in the book, it cannot be encoded. An alternative approach which gets around this problem is to replace individual letters rather than words. One such method, used in the second Beale cipher, replaces the first letter of a word in the book with that word's position. In this case, the book cipher is properly a cipher — specifically, a homophonic substitution cipher. However, if used often, this technique has the side effect of creating a larger ciphertext (typically 4 to 6 digits being required to encipher each letter or syllable) and increases the time and effort required to decode the message.



> # Choosing the key

The main strength of a book cipher is the key. The sender and receiver of encoded messages can agree to use any book or other publication available to both of them as the key to their cipher. Someone intercepting the message and attempting to decode it, unless they are a skilled cryptographer (see Security below), must somehow identify the key from a huge number of possibilities available. In the context of espionage, a book cipher has a considerable advantage for a spy in enemy territory. A conventional codebook, if discovered by the local authorities, instantly incriminates the holder as a spy and gives the authorities the chance of deciphering the code and sending false messages impersonating the agent. On the other hand, a book, if chosen carefully to fit with the spy's cover story, would seem entirely innocuous. The drawback to a book cipher is that both parties have to possess an identical copy of the key. The book must not be of the sort that would look out of place in the possession of those using it and it must be of a type likely to contain any words required. Thus, for example, a spy wishing to send information about troop movements and numbers of armaments would be unlikely to find a cookbook or romance novel useful keys.

> # Using widely available publications
> ## Dictionary

Another approach is to use a dictionary as the codebook. This guarantees that nearly all words will be found, and also makes it much easier to find a word when encoding. This approach was used by George Scovell for the Duke of Wellington's army in some campaigns of the Peninsular War. In Scovell's method, a codeword would consist of a number (indicating the page of the dictionary), a letter (indicating the column on the page), and finally a number indicating which entry of the column was meant. However, this approach also has a disadvantage: because entries are arranged in alphabetical order, so are the code numbers. This can give strong hints to the cryptanalyst unless the message is superenciphered. The wide distribution and availability of dictionaries also present a problem; it is likely that anyone trying to break such a code is also in possession of the dictionary which can be used to read the message.

> ## Bible cipher

The Bible is a widely available book that is almost always printed with chapter and verse markings making it easy to find a specific string of text within it, making it particularly useful for this purpose; the widespread availability of concordances can ease the encoding process as well.

> # Security

Essentially, the code version of a "book cipher" is just like any other code, but one in which the trouble of preparing and distributing the codebook has been eliminated by using an existing text. However this means, as well as being attacked by all the usual means employed against other codes or ciphers, partial solutions may help the cryptanalyst to guess other codewords, or even to break the code completely by identifying the key text. This is, however, not the only way a book cipher may be broken. It is still susceptible to other methods of cryptanalysis, and as such is quite easily broken, even without sophisticated means, without the cryptanalyst having any idea what book the cipher is keyed to.

If used carefully, the cipher version is probably much stronger, because it acts as a homophonic cipher with an extremely large number of equivalents. However, this is at the cost of a very large ciphertext expansion.

