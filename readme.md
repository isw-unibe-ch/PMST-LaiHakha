# Person Marking in South-Central Trans-Himalayan: Hakha Lai

This PARALEX set contains person markers in Hakha Lai, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that the data set cannot be used to study variation in verb stems or inflectional classes.
* The source_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ. This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Hakha Lai
 
* Tone: There are three tonal contrasts in Hakha Lai (cf. Hyman & VanBik 2002, Peterson 2017: 258). Tones are not marked in the current version of the data set, since the transcription is based on the community orthography which does not mark tone, with one exception in the source forms: the postconsonantal allomorph n- of the 2nd person patient marker, which bears a high tone, is written 'n in the community orthography and the data set to distinguish it from the general plural marker n-, written n. Thus, the tone of the 2nd person marker can be inferred from this orthographic convention.
* Mapping between database paradigm labels (future and nonfuture) and Hakha Lai descriptive labels in Peterson (2017): identical labels.


## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.

Hyman, Larry M. and Kenneth VanBik. 2002. "Tone and syllable structure in Hakha Lai".
_BLS 28, Special Session on Tibeto-Burman and Southeast Asian Linguistics_: 15–28.

Peterson, David A. 2017. "Hakha Lai". Thurgood, Graham and Randy J. LaPolla (eds.). _The Sino-Tibetan Languages_. Second edition. London and New York: Routledge. 258–276. 
