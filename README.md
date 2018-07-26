# c-musical-oneliners
Exploring musical one-liners as inspired by Bisqwit and Viznut.
For some introductory reading, check out Viznut's original
write-up series:
1. Introduction:     `http://viznut.fi/texts-en/bytebeat_algorithmic_symphonies.html`
2. Deeper analysis:  `http://viznut.fi/texts-en/bytebeat_deep_analysis.html`
3. arXiv submission: `http://viznut.fi/texts-en/bytebeat_exploring_space.pdf`
4. Finnish writing:  `http://viznut.fi/texts-fi/bytebeat_ja_demoskene.html`,

or this write-up by Kragen:
1. `http://canonical.org/~kragen/bytebeat/ `


## Setup (~1m)

1. `gcc oneliner.c`
2. `brew install sox`
3. `./a.out | play -c1 -b8 -eunsigned -traw -r8k -`

(convenience line once sox is installed)
* `gcc oneliner; ./a.out | play -c1 -b8 -eunsigned -traw -r8k -`
