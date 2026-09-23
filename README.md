# CBG71_Hepatozoon

Poster for the 71st Brazilian Congress of Genetics (Genética 2026), held in Florianópolis, Santa Catarina, Brazil, from September 29 to October 2, 2026.

**Morphological and genomic characterization of a novel *Hepatozoon* lineage in the critically endangered insular pitviper *Bothrops sazimai* (Squamata: Serpentes: Viperidae)**

Giselle Pessanha Pessoa, Igor Salles de Oliveira, Giovanna Yumi Scorsim Omura, Denis Jacob Machado, Milton Yutaka Nishiyama Junior, and Maria José de Jesus Silva

Giselle Pessanha Pessoa presents the poster on October 1, 2026, from 17:30 to 19:30 (Trabalho #253, thematic area Genética de Microrganismos). The congress rules require the presenting author to be the first author, so the poster lists her first.

## Accepted abstract

Cite the abstract accepted by the congress as follows. The congress lists it among the approved works at https://genetica2026.com.br/aprovados, and its text will appear in the electronic proceedings of the event.

> Salles de Oliveira, I., Pessoa, G. P., Omura, G. Y. S., Jacob Machado, D., Nishiyama Junior, M. Y., and Silva, M. J. J. 2026. Morphological and genomic characterization of a novel *Hepatozoon* lineage in the critically endangered insular pitviper *Bothrops sazimai* (Squamata: Serpentes: Viperidae). Abstract, Trabalho #253. 71º Congresso Brasileiro de Genética (Genética 2026), Sociedade Brasileira de Genética, Florianópolis, SC, Brazil, September 29 to October 2, 2026.

The congress does not allow changes after submission. The poster and `ABSTRACT.md` update that text with the best information available to the authors. The main changes are the family of *Hepatozoon* (Hepatozoidae), the number of apicoplast tRNA genes (26), the support values from the maximum likelihood tree, and a more cautious reading of the two 18S variants.

## Contents

| File | Content |
|---|---|
| `Poster_CBG71_Hepatozoon.pdf` | The poster, 100 cm by 100 cm |
| `ABSTRACT.md` | An updated abstract that matches the poster |
| `main.tex` | LaTeX source of the poster |
| `latexmkrc` | Sets LuaLaTeX as the compiler |
| `figures/` | Figures 1 to 7 |
| `logos/` | Logos of the event, the host institutions, and the funders |
| `LICENSE` | Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International |

## Building the poster

The repository is linked to an Overleaf project. In Overleaf, the `latexmkrc` file selects LuaLaTeX. To build it locally with TeX Live, run:

```sh
latexmk -lualatex main.tex
```

The poster uses the TeX Gyre Heros font, which ships with TeX Live. Each poster column has a fixed height. If an edit makes a column run past that height, the build log reports it as `Overfull \vbox`.

## License

Our text and figures are available under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license (CC BY-NC-SA 4.0). See `LICENSE`.

The license does not cover material owned by others. The logos belong to their organizations. Ricardo Sawaya holds the rights to the photograph in Figure 1. Figure 2 was created in BioRender (BioRender.com) and follows the BioRender terms of use.

## Contact

Denis Jacob Machado, dmachado@charlotte.edu
