NHyphenator-Mono
================
Monoport of https://github.com/alkozko/NHyphenator


To get new hyphenations patterns for a other languages go to:

http://extensions.openoffice.org/en/search?f[0]=field_project_tags%3A157

1. Search the dictionary of your languages
2. Download the extension
3. Unzip it
4. Copy the hyph_xx_xx/hyph_xx_xx.dic file into Resources folder and rename it to hyph-xx-xx.pat.txt
5. Create a hyph-xx-xx.hyph.txt file for word exceptions
6. Add the new files to "Patterns.resx"
7. Add your Language to the "HyphenatePatternsLanguage" enum in "Hyphenator.cs"
8. Extend the "LoadPatterns" (Hyphenator.cs) method for your languages
9. Done.