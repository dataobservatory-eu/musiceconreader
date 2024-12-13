# Glossaries

🙋‍♀️ Reviewing the economics of music with a focus on price comparison, valuation and statistical estimation of variables.

🌈 Contribution guidelines - you must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.

## Source files

-   `index.qmd`: Preface of the booklet

-   `economics.qmd`: The review of economic literature

-   `surveying.qmd`: Surveying methodology methodology and best practice

## Rendered files

The edited files are rendered to `docs/`, which is *not synchronized* to GitHub (see `.gitignore`)

## Referencing and attribution

`bib`: Contains all bibliography: used citations, data used, visualisation used, datasets created, visualizations created, public text document outputs created.

-   `bib/competition.bib`: Competition economics of music (prices, quantities, practical issues.)

-   `bib/ISOdata.bib`: ISO standards for music. In our Zotero library: Digital Music Observatory / Metadata/ [ISO](https://www.zotero.org/groups/4559070/digital_music_observatory/collections/BYIWWB7F) folder.

-   `bib/measuringculture.bib`: Measuring and estimating the variables.

-   `bib/metadata.bib`: General metadata citations, we often use definitions from these academic sources, not only from ISO or other standards.

-   `bib/musicbusiness.bib`: Definition, structure, who is who in the music industry. Zotero library: Digital Music Observatory / Music economy / [Music industry](https://www.zotero.org/groups/4559070/digital_music_observatory/collections/ECPH557H) folder

-   `bib/musicvaluation.bib`: Price comparison, measurement, setting, fair value, valuation. In our Zotero library: Digital Music Observatory / Music economy / [Valuation](https://www.zotero.org/groups/4559070/digital_music_observatory/collections/I4JUEB4C) folder.

-   `bib/OpenMusE.bib`: Referencing EU-funded outputs. In our Zotero library: Digital Music Observatory / Music economy / [OpenMusE](https://www.zotero.org/groups/4559070/digital_music_observatory/collections/DHYH93EKhttps://www.zotero.org/groups/4559070/digital_music_observatory/collections/DHYH93EK) folder.

-   `bib/zeropricemusic.bib`: Unlicensed and zero price uses, when the end user is not paying for music. In our Zotero library: Digital Music Observatory / Music economy / folder.

## Data folders

We have two data folders, which may have numerous subfolders.

`data-raw`: Raw, unprocessed data, as received, downloaded, collected. You can place here small PDF files if when necessary.

`data`: This folder contains the processed data or our outputs. Any data here must adhere to the tidy data principle and be documented by DataCite standards. We are developing a tool, dataset, which will do this automatically in WP4. We can investigate a Python connector for this if there is a need for that.

## Visualisation folders

We save visualisations in folders corresponding to the file format. This is the best way to ensure that pandoc or any compiles has the necessary plugins to work with the visualizations. Every visualization that is intended to made pubic gets a bibliographic citation and a globally unique DOI identifier.

`png`: contains visualisations in Portable Network Graphics format (our preferred format.)

`jpg`: Contains visualization in Joint Photographic Experts Group format.

`webp`: Contains visualisations in WebP is an open image file format developed by Google intended as a replacement for JPEG, PNG, and GIF file formats. We prefer this for content intended for web use (presentations, blogposts), because it works much faster and better with browsers than PNG or JPG.

\[…\] You can use other formats if necessary.

## Other file formats

`docx`: Word documents. Whenever possible, use small files.

## Ignored files in .gitignore

The `.gitignore` file contains file names, bulk file name exceptions, and entire folders that are *not* to be synchronized to GitHub. `not_included`: serves as the place of your personal scrapbook, sandbox, that you do not want to share with anybody. `docs`: the final, edited texts (we do not synch because if the `qmd` file is correct, they should work with all users of the shared repository.)
