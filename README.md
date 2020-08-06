# Special Characters References
I have wasted far too much time looking this up so I've compiled the syntax for inserting special characters into various formats for easy reference. These are codes that have worked for me, I claim no authority on their correctness. This is also not exhaustive but perhaps reletively comprehensive.

**Note**: GitHub flavored Markdown accepts HTML character codes. For R Markdown, use the code for the intended output format.

## Table of Contents

* [Special Letters](#special-letters)
* [Greek Letters](#greek-letters)

## Special Letters
### Conventions

* Q or q is a placeholder for one of the input demonstrated in the Character column
* X is arbitrary uppercase alphabetic input
* x is arbitary lowercase or any alphabetic input (see Description)
* LaTeX syntax is plain tex and works only in paragraph and left-to-right mode, other syntax might exist in other modes or specialized packages.

| Character                                        | Description                                          | Plain LaTeX              | BibTeX                      | HTML                  |
| ------------------------------------------------ | ---------------------------------------------------- | ------------------------ | --------------------------- | --------------------- |
| &Agrave;, &Egrave;, &Ograve;, &Ugrave;           | Uppercase letter with grave accent                   | ``\`{X}`` (backtick)     | ``{\`X}`` (backtick)        | `&Qgrave;`,  `X&#768;`| 
| &agrave;, &egrave;, &ograve;, &ugrave;           | Lowercase letter with grave accent                   | ``\`{x}``  (backtick)    | ``{\`x}``  (backtick)       | `&qgrave;`,  `x&#768;`|
| &Aacute;, &Eacute;, &Oacute;, &Uacute;  &Yacute; | Uppercase letter with acute accent                   | `\'{X}` (single quote)   | `{\'X}` (single quote)      | `&Qacute;`, `X&#769;` | 
| &aacute;, &eacute;, &oacute;, &uacute; &yacute;  | Lowercase letter with acute accent                   | `\'{x}` (single quote)   | `{\'x}` (single quote)      | `&qacute;`, `x&#769;` | 
| &Acirc;, &Ecirc;, &Ocirc;, &Ucirc;               | Uppercase letter with circumflex accent              | `\^{X}`                  | `{\^X}`                     | `&Qcirc;`, `X&#770;`  | 
| &acirc;, &ecirc;, &ocirc;, &ucirc;               | Lowercase letter with circumflex accent              | `\^{x}`                  | `{\^x}`                     | `&qcirc;`, `x&#770;`  | 
| &Atilde;, &Ntilde;, &Otilde;                     | Uppercase letter with tilde                          | `\~{X}`                  | `{\~X}`                     | `&Qtilde;`, `X&#771;` | 
| &atilde;, &ntilde;, &otilde;                     | Lowercase letter with tilde                          | `\~{x}`                  | `{\~x}`                     | `&qtilde;`, `x&#771;` | 
| &Auml;, &Euml;, &Ouml;, &Uuml;                   | Uppercase letter with umlaut                         | `\"{X}` (double quote)   | `{\"X}` (double quote)      | `&Quml;`, `X&#776;`   | 
| &auml;, &euml;, &ouml;, &uuml;                   | Lowercase letter with umlaut                         | `\"{x}` (double quote)   | `{\"x}` (double quote)      | `&quml;`, `x&#776;`   | 
| &Aring;                                          | Uppercase letter with ring                           | `\r{X}` (or `\AA` for A) | `{\r X}` (or `{\AA}` for A) | `&Aring;`, `X&#778;`  |
| &aring;                                          | Lowercase letter with ring                           | `\r{x}` (or `\aa` for a) | `{\r x}` (or `{\aa}` for a) | `&aring;`, `x&#778;`  |
| x&#772;                                          | Letter with macron accent above                      | `\={x}`                  | `{\=x}`                     |  `x&#772;`            |
| x&#817;                                          | Letter with macron accent below / underbar           | `\b{x}`                  | `{\b x}`                    | `x&#817;`             |
| x&#775;                                          | Letter with dot above                                | `\.{x}`                  | `{\.x}`                     | `x&#775;`             |
| x&#803;                                          | Letter with dot below                                | `\d{x}`                  | `{\d x}`                    | `x&#803;`             |
| x&#780;                                          | Letter with wedge accent / caron                     | `\v{x}`                  | `{\v x}`                    | `x&#780;`             |
| &Ccedil;                                         | Uppercase letter with cedilla                        | `\c{X}`                  | `{\c X}`                    | `&Ccedil;`            |
| &ccedil;                                         | Lowercase letter with cedilla                        | `\c{x}`                  | `{\c x}`                    | `&ccedil;`            |
| a&#808;                                          | Letter with ogonek                                   | `\k{x}`                  | `{\k x}`                    | `x&#808;`             |
| x&#783;                                          | Letter with double grave accent                      | NA                       | NA                          | `x&#783;`             |
| x&#779;                                          | Letter with "Hungarian" umlaut / double acute accent | `\H{X}`                  | `{\H X}`                    | `x&#779;`             |
| x&#865;x                                         | Two letters with ligature tie                        | `\t{xx}`                 | `{\t xx}`                   | `x&#865;x`            |
| &AElig;                                          | Uppercase AE dipthong                                | `\AE`                    | `{\AE}`                     | `&AElig;`             |
| &aelig;                                          | Lowercase ae dipthong                                | `\ae`                    | `{\ae}`                     | `&aelig;`             |
| &ETH;                                            | Uppercase eth                                        | `\DH`                    | `{\DH}`                     | `&ETH;`               |
| &eth;                                            | Lowercase eth                                        | `\dh`                    | `{\dh}`                     | `&eth;`               |
| &Lstrok;                                         | Uppercase barred L                                   | `\L`                     | `{\L}`                      | `&Lstrok;`            |
| &lstrok;                                         | Lowercase barred l                                   | `\l`                     | `{\l}`                      | `&lstrok;`            |
| &Oslash;                                         | Uppercase O with slash                               | `\O`                     | `{\O}`                      | `&Oslash;`            |
| &oslash;                                         | Lowercase o with slash                               | `\o`                     | `{\o}`                      | `&oslash;`            |
| &OElig;                                          | Uppercase OE dipthong                                | `\OE`                    | `{\AE}`                     | `&OElig;`             |
| &oelig;                                          | Lowercase oe dipthong                                | `\oe`                    | `{\oe}`                     | `&oelig;`             |
| &szlig;                                          | German sz ligature                                   | `\ss`                    | `{\ss}`                     | `&szlig;`             |
| &THORN;                                          | Uppercase thorn                                      | `\TH`                    | `{\TH}`                     | `&THORN;`             |
| &thorn;                                          | Lowercase thorn                                      | `\th`                    | `{\th}`                     | `&thorn;`             |

### References

* [whatsmyip HTML entities and special characters](https://www.whatsmyip.org/html-characters)
* [WikiBooks LaTeX special characters](https://en.wikibooks.org/wiki/LaTeX/Special_Characters)
* [topal.com HTML symbol, entities, and ASCII character reference](https://www.toptal.com/designers/htmlarrows)
* [LaTeX Help](https://www.asc.ohio-state.edu/miller.104/molspect/symposium/latexinstruct.html)
* [Bibtex syntax](https://tex.stackexchange.com/questions/57743/how-to-write-%C3%A4-and-other-umlauts-and-accented-letters-in-bibliography)
* [Diacritic Wikipedia page](https://en.wikipedia.org/wiki/Diacritic)
* [w3schools HTML Entities](https://www.w3schools.com/html/html_entities.asp)

## Greek Letters

| Character | Description | LaTeX Math Mode | LaTeX `textgreek` Package (paragraph mode) | HTML |
| ----- | ---------- | ------ | -------- | ------- |
| &Alpha; | Uppercase alpha | `A` | `\textAlpha` | `&Alpha;` | 
| &alpha; | Lowercase alpha | `\alpha` | `\textalpha` | `&alpha;` |
| &Beta; | Uppercase beta | `B` | `\textBeta` | `&Beta;` |
| &beta; | Lowercase beta | `\beta` | `\textbeta` | `&beta;` |
| &Gamma; | Uppercase gamma | `\Gamma` | `\textGamma` | `&Gamma;` |
| &gamma; | Lowercase gamma | `\gamma` | `\textgamma` | `&gamma;` |
| &Delta; | Uppercase delta | `\Delta` | `\textDelta` | `&Delta;` | 
| &delta; | Lowercase delta | `\delta` | `\textdelta` | `&delta;` |
| &Epsilon; | Uppercase epsilon | `E` | `\textEpsilon` | `&Epsilon;` | 
| &epsilon; | Lowercase epsilon | `\varepsilon` | `\textepsilon` | `&epsilon;` |
| &straightepsilon; | Straight epsilon | `\epsilon` |  `\straightepsilon` | `&straightepsilon;`|
| &Zeta; | Uppercase zeta | `Z` | `\textZeta` | `&Zeta;` | 
| &zeta; | Lowercase zeta | `\zeta` | `\textzeta` | `&zeta;` |
| &Eta; | Uppercase eta | `H` | `\textEta` | `&Eta;` | 
| &eta; | Lowercase eta | `\eta` | `\texteta` | `&eta;` |
| &Theta; | Uppercase theta | `\Theta` | `\textTheta` | `&Theta;` | 
| &theta; | Lowercase theta | `\theta` | `\straighttheta` | `&theta;` |
| &thetasym; | Script theta | `\vartheta` | `\texttheta`, `\scripttheta` | `&thetasym;` |
| &Iota; | Uppercase iota | `I` | `\textIota` | `&Iota;` | 
| &iota; | Lowercase iota | `\iota` | `\textiota` | `&iota;` |
| &Kappa; | Uppercase kappa | `K` | `\textKappa` | `&Kappa;` | 
| &kappa; | Lowercase kappa | `\kappa` | `\textkappa` | `&kappa;` |
| &Lambda; | Uppercase lambda | `\Lambda` | `\textLambda` | `&Lambda;` | 
| &lambda; | Lowercase lambda | `\lambda` | `\textlambda` | `&lambda;` |
| &Mu; | Uppercase mu | `M` | `\textMu` | `&Mu;` | 
| &mu; | Lowercase mu | `\mu` | `\textmugreek` | `&mu;` |
| &Nu; | Uppercase nu | `N` | `\textNu` | `&Nu;` | 
| &nu; | Lowercase nu | `\nu` | `\textnu` | `&nu;` |
| &Xi; | Uppercase xi | `\Xi` | `\textXi` | `&Xi;` | 
| &xi; | Lowercase xi | `\xi` | `\textxi` | `&xi;` |
| &Omicron; | Uppercase omicron | `O` | `\textOmikron` | `&Omicron;` | 
| &omicron; | Lowercase omicron | `o` | `\textomikron` | `&omicron;` |
| &Pi; | Uppercase pi | `\Pi` | `\textPi` | `&Pi;` | 
| &pi; | Lowercase pi | `\pi` | `\textpi` | `&pi;` |
| &Rho; | Uppercase rho | `P` | `\textRho` | `&Rho;` | 
| &rho; | Lowercase rho | `\rho` | `\textrho` | `&rho;` |
| &rhov; | Script rho | `\varrho` | NA | `&rhov;` |
| &Sigma; | Uppercase sigma | `\Sigma` | `\textSigma` | `&Sigma;` | 
| &sigma; | Lowercase sigma | `\sigma` | `\textsigma` | `&Sigma;` |
| &sigmaf; | Final sigma | `\varsigma` | `\textvarsigma` | `&sigmaf;` |
| &Tau; | Uppercase tau | `T` | `\textTau` | `&Tau;` | 
| &tau; | Lowercase tau | `\tau` | `\texttau` | `&tau;` |
| &Upsilon; | Uppercase upsilon | `\Upsilon` | `\textUpsilon` | `&Upsilon;` | 
| &upsilon; | Lowercase upsilon | `\upsilon` | `\textupsilon` | `&upsilon;` |
| &Phi; | Uppercase phi | `\Phi` | `\textPhi` | `&Phi;` | 
| &straightphi; | Lowercase phi | `\phi` | `\straightphi` | `&straightphi;` |
| &phi; | Script phi | `\varphi` | `\textphi` | `&phi;` |
| &Chi; | Uppercase chi | `X` | `\textChi` | `&Chi;` | 
| &chi; | Lowercase chi | `\chi` | `\textchi` | `&chi;` |
| &Psi; | Uppercase psi | `\Psi` | `\textPsi` | `&Psi;` | 
| &psi; | Lowercase psi | `\psi` | `\textpsi` | `&psi;` |
| &Omega; | Uppercase omega | `\Omega` | `\textOmega` | `&Omega;` | 
| &omega; | Lowercase omega | `\omega` | `\textomega` | `&omega;` |

### References

* [Overleaf Greek letters](https://www.overleaf.com/learn/latex/List_of_Greek_letters_and_math_symbols)
* [W3C Character Table](https://www.w3.org/TR/WD-math-970515/table04.html)
* [`textgreek` package](https://ctan.math.illinois.edu/macros/latex/contrib/textgreek/textgreek.pdf)
* [HTML5 Greek Letters](http://www.tutorialspark.com/html5/HTML5_Greek_Characters.php)

