# smartGlycan
a collection of in-house tools to process N-Glycan and O-Glycan data

##(1) ExtractNglycan (9-3-2016)
ExtractNglycan takes MaxQuant result folder as input and reads peptides.txt.

It removes the decoy and non-deaminated peptides and test if the deaminated peptide has a motif of "N[!P][S|T]". If yes, just print the whole line.

The result name is Nglycan.txt. The sreenshot is listed [below](https://github.com/changcheng1987/smartGlycan/blob/master/ExtractNglycan_screenshot.png).

![screenshot](https://github.com/changcheng1987/smartGlycan/blob/master/ExtractNglycan_screenshot.png)