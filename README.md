# Encoding-project-2

***Project Objective***

This project follows on from the encoding approach presented in the XML-TEI course. The goal this time is to apply the Text Encoding Initiative (TEI) to our own projects, while also being able to customize document encoding to address our research questions. 
Drawing on both lessons taught at school and the **TEI guidelines**. Our work therefore includes: README, three TEI XML files encoded according to the **TEI_all format** and a comparative analysis with the DTD designed during Assignment 1.

***Sources***

To achieve this, we encode three poems by *Victor Hugo* (**L'Oeuvre poétique**), *Charles Baudelaire* (**Les Fleurs du mal**), and *Paul Verlaine* (**Poèmes saturniers**), selected from digital reproductions available on Gallica. Each file is structured according to the basic TEI schema (for texts in reverse), comprising a <teiHeader> up to the <text>. We therefore have the title, author, source, ARK identifier, language, date and description.

***Encoding approach and principles***

**Metadata encoding**

We have: title of the poem `<titleStmt>`, the author `<author>`, the person who encodes `<respStmt>`, information about TEI document `<publicationStmt>` `<availability>` with attributes`"p"` and `<idno>`, the source `<sourceDesc>` (`<bibl>` containing the title of the collection).


**Structure of the body of the poem**

Each poem follows a specific structure, encoded according to its individual encoding needs. The `<text>`, `<body>`, and``<div>` tags contain the content of each. In the case of `<div>`, we have the attributes `"type"`, which specifies the document type (poem), and `"number` for the poem's number in the collection. `<head>` contains the poem's title, `<lg>` with its `"type"` attribute (`stanza`) for the epigraph and stanzas, and `<l>` for each line, with the attributes `"n"` for the line number and `rhyme` for the rhyme scheme.

**Use of AI**


We used "Google translate" to help us translate difficult words in order to improve our style.












