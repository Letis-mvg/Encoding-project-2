**Reflection note between DTD and TEI_all**

In Assignment 1, i designed a personal DTD to encode my poems. This DTD included simple elements such as:

'<poem>' : for the poem,

'<number>' : for the poem number,

'<epigraph>' : for the epigraph (with a lang attribute),

'<lg>' : for stanzas,

'<l>' : for individual lines (with the n attribute for line numbers),

'<url>' : for linking to the source document (optional).

While this DTD allowed me to structure the poem, it had significant limitations. It only captured the internal structure of the poem and did not provide ways to encode metadata such as the author, source, publication, or the identity of the encoder. It also could not encode additional features like rhyme schemes, named characters, or typographical and visual layout aspects.

In contrast, the **TEI_all schema** offers a more comprehensive and standardized framework. 

Using TEI_all, I can encode:

**Metadata through** : '<teiHeader>', including the title, author, editor, source, date, and encoder information.

**Structured content** : using '<text>' and '<body>', with '<div type="poem">' for the poem and '<lg type="quatrain">' and '<lg type="sestain">' for stanzas.

**Rhyme and names** by adding attributes like rhyme to '<l>' and elements such as '<persName>' ('<foreName>', '<surname>') mentioned in the poem.


**Advantages of TEI_all compared to my DTD**

Richer metadata and standardized encoding.

Ability to encode rhyme schemes and named entities in a structured way.

Clear, reusable framework that can support future digital humanities projects.


**Limitation of TEI_all**

TEI_all does not allow encoding custom typographical. The elements mentioned in the TEI_all must be declared in the DTD. 
My TEI does not include all these elements. I modified the structure of my work in exercise 2, but I did not redo the DTD according to the teacher's instructions.

**Conclusion**

Using TEI_all enabled me to encode my poem more comprehensively, with richer metadata and a standardized structure, whereas my original DTD was simpler but limited. Understanding the trade-offs between custom DTD and standardized TEI encoding allows me to design an encoding workflow that is both usable and interoperable for literary research.
