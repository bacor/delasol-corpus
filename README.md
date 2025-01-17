# 🌞 Delasol Corpus

**The [Delasol project](https://github.com/bacor/delasol) aims to develop methods for automatic hexachordal solmization. This repository contains a corpus of transcriptions of (historical) solmizations.**

_Note: The project is still under development._

## Contributors

- Bas Cornelissen
- Artur Dobija

## Organization

**Collections.**
The Delasol Corpus is organized into different collections that may correspond to
different sources. For example, [`marot-de-beze-1562`](/collections/marot-de-beze-1562/) corresponds to the 1562 Genevan
Psalter by Marot and de Bèze. 

**Drafts.** 
Collections that are still being developed and have not yet been released are stored
in the [drafts folder](/drafts).

**Formats: MuseScore & musicxml.**
All transcriptions are provided as MuseScore and MusicXML files. The MuseScore files
serve as the standard, the musicxml files are automatically generated from these using
Delasol's corpus class.

**Metadata.**
Every collection has a `collection.yaml` metadata file containing relevant metadata
about the corpus. In particular, it lists all files. Besides, there is a `README.md`
with more details about the collections, such as additional transcription guidelines
and so on. 

**Transcription guidelines.** 
Every collection is different, and may adopt its own guidelines transcription guidelines.
But all transcriptions within a collection should respect the exact same transcription 
guidelines, which are documented in the `README.md` of that collection. Besides that,
there are several general guidelines that are respected by all collections (unless very
explicitly stated). These are documented in [`transcription-guidelines`](guidelines/).
General guidelines are versioned and previous (major) versions are stored in the repository.
Individual collections always document which version of the guidelines they respect.
