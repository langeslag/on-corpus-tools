# on-corpus-tools

Processing tools for various Old English text corpora and resources. I'm still organizing the folder structure.

## `menota-extract.ipynb`

A notebook converting any XML files located in `menota/xml/` and following the Menota schema into plaintext files, separating them out into a normalized and a diplomatic text. By default, the diplomatic text is normalized orthographically to match as closely as possible Unger's procedure in his 1862 _Stjórn_ for ease of comparison, but this may easily be changed by modifying the character substitution dictionary.

For the time being, the Menota corpus is not downloaded automatically as I figure out whether the Clarino REST API allows this.

## _Stjórn_

Notebooks processing and evaluating _Stjórn_.

1. Run `stjorn-extract.ipynb` first, then `stjorn-segment.ipynb`; these are prerequisites for the evaluation code.
2. The remaining notebooks relevant to _Stjórn_ are contained in `stjorn/`.

## License Notice

These tools are Copyright 2025 P. S. Langeslag.

These tools are free software: you can redistribute them and/or modify them under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

These tools are distributed in the hope that they will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with these tools. If not, see <https://www.gnu.org/licenses/>.
