# UK-Source Ideographs

*UK-Source Ideographs* documents the source references for the CJK Unified Ideographs that are submitted by the UK (*United Kingdom*) to the [IRG](https://www.unicode.org/irg/) (*Ideographic Research Group*) for inclusion in their working sets by providing the actual submissions. Such ideographs are referred to as UK-source ideographs, which are documented in Unicode Standard Annex #38 ([UAX #38](https://unicode.org/reports/tr38/)), *Unicode Han Database (Unihan)*, as the [*kIRG_UKSource*](https://unicode.org/reports/tr38/#kIRG_UKSource) property.

* Document [IRG N2107R2](https://github.com/unicode-org/uk-source-ideographs/raw/main/IRGN2107R2.pdf) (PDF), which was originally submitted as IRG N2107 prior to [IRG Meeting #45](https://www.unicode.org/irg/docs/n2110-Recommendations.pdf), documents the 1,640 UK-source ideographs that were submitted for IRG Working Set 2015, 1,566 of which are encoded in [CJK Unified Ideographs Extension G](https://unicode.org/charts/PDF/U30000.pdf) ([Unicode Version 13.0](https://www.unicode.org/versions/Unicode13.0.0/)). For purely legacy reasons, these 1,640 UK-source ideographs, along with 16 that were withdrawn in the first revision of IRG N2107, can also be found in Unicode Standard Annex #45 ([UAX #45](https://unicode.org/reports/tr45/)), *U-Source Ideographs*, as source references UK-01313 through UK-02968.

* Document [IRG N2232R](https://github.com/unicode-org/uk-source-ideographs/raw/main/IRGN2232R.pdf) (PDF), which was originally submitted as IRG N2232 prior to [IRG Meeting #49](https://www.unicode.org/irg/docs/n2260-Recommendations.pdf), documents the 1,000 UK-source ideographs that were submitted for IRG Working Set 2017, 917 of which are encoded in [CJK Unified Ideographs Extension H](https://unicode.org/charts/PDF/U31350.pdf) ([Unicode Version 15.0](https://www.unicode.org/versions/Unicode15.0.0/)).

* Document [IRG N2487](https://github.com/unicode-org/uk-source-ideographs/raw/main/IRGN2487.pdf) (PDF), which was submitted prior to [IRG Meeting #57](https://www.unicode.org/irg/docs/n2500-Recommendations.pdf), documents the 1,000 UK-source ideographs that were submitted for IRG Working Set 2021, 906 of which are encoded in [CJK Unified Ideographs Extension J](https://unicode.org/charts/PDF/U323B0.pdf) ([Unicode Version 17.0](https://www.unicode.org/versions/Unicode17.0.0/)).

The above three documents each include the following two files as PDF attachments:

* A Microsoft Excel file that provides the per-ideograph attributes.
* A TrueType font that provides the representative glyphs for the UK-source ideographs, which are mapped from the PUA (*Private Use Area*) code points as specified in the Microsoft Excel file, the use of which is covered under the terms of the [Arphic Public License](https://ftp.gnu.org/gnu/non-gnu/chinese-fonts-truetype/LICENSE) (also see *[LICENSE](./LICENSE)*).

Evidence images for documents IRG N2107R2 and IRG N2232R can be downloaded from the [Latest Release](https://github.com/unicode-org/uk-source-ideographs/releases/latest/) as *UKSourceEvidenceIRGN2107.pdf* and *UKSourceEvidenceIRGN2232.pdf*, respectively. Click [here](https://www.unicode.org/irg/docs/n2487-UK_2021_sub_evidence.zip) to download a 398MB ZIP file that includes the evidence images for document IRG N2487.

All of the representative glyphs that correspond to the UK-source ideographs, which are mapped from their standardized code points, are available as a TrueType font, the use of which is covered under the terms of the [Arphic Public License](https://ftp.gnu.org/gnu/non-gnu/chinese-fonts-truetype/LICENSE) (also see *[LICENSE](./LICENSE)*), and can be easily downloaded from the [Latest Release](https://github.com/unicode-org/uk-source-ideographs/releases/latest/).

The table below specifies the number of UK-source ideographs that have been encoded in CJK Unified Ideographs **Extension** blocks, either from submissions for IRG working sets or as horizontal extensions, and as of [Unicode Version 17.0](https://www.unicode.org/versions/Unicode17.0.0/):

**Extension** | **Ideographs** | **Source**
--- | --- | ---
[A](https://unicode.org/charts/PDF/U3400.pdf)  | 3     | Horizontal extension
[B](https://unicode.org/charts/PDF/U20000.pdf) | 12    | Horizontal extension
[C](https://unicode.org/charts/PDF/U2A700.pdf) | 1     | Horizontal extension
[E](https://unicode.org/charts/PDF/U2B820.pdf) | 2     | Horizontal extension
[F](https://unicode.org/charts/PDF/U2CEB0.pdf) | 2     | Horizontal extension
[G](https://unicode.org/charts/PDF/U30000.pdf) | 1,566 | IRG Working Set 2015
[H](https://unicode.org/charts/PDF/U31350.pdf) | 917   | IRG Working Set 2017
[J](https://unicode.org/charts/PDF/U323B0.pdf) | 906   | IRG Working Set 2021

The [*kIRG_UKSource.txt*](https://github.com/unicode-org/uk-source-ideographs/raw/main/kIRG_UKSource.txt) data file is an excerpt of the Unihan database *Unihan_IRGSources.txt* data file that includes only the 3,409 ideographs with a *kIRG_UKSource* property value.

UK submissions for current and future IRG working sets will be added to this repository as their are standardized in CJK Unified Ideographs extension blocks.

### Copyright & Licenses

Copyright © 2020-2025 Unicode, Inc. Unicode and the Unicode Logo are registered trademarks of Unicode, Inc. in the United States and other countries.

A CLA is required to contribute to this project - please refer to the [CONTRIBUTING.md](https://github.com/unicode-org/.github/blob/main/.github/CONTRIBUTING.md) file (or start a Pull Request) for more information.

The contents of this repository are governed by the Unicode [Terms of Use](https://www.unicode.org/copyright.html) and are released under [LICENSE](./LICENSE).
