README.md
======

Revisados
---------


PNLD2023-030_As aventuras do barão de Munchausen
PNLD2023-031_As coisas
PNLD2023-032_Conversando com varejeiras azuis
PNLD2023-033_Cultura

- [x] PNLD2023-001_Ninguém e eu ✔️
- [x] PNLD2023-002_Pedrinho petrificado ✔️
- [x] PNLD2023-003_Meu baú de cordéis ✔️
- [ ] PNLD2023-005_Viagem ao reino encantado do cordel (Aguardando Paulo)
- [x] PNLD2023-006_Sobrevoos (Camila Werner) ✔️
- [x] PNLD2023-007_O dia em que o mundo parou (Camila Werner) ✔️
- [x] PNLD2023-010_A mulher que virou tatu ✔️
- [x] PNLD2023-013_A semente e a torre ✔️
- [x] PNLD2023-014_Ideias de canário ✔️
- [ ] NÃO FAZER ~~PNLD2023-016_História de Aladim e a lâmpada maravilhosa~~ ✔️
- [ ] PNLD2023-017_Os cantos do homem-sombra ✔️ (Gabriela)
- [ ] NÃO FAZER ~~PNLD2023-019_Troca de pele~~ ✔️
- [ ] PNLD2023-021_A fábrica de robôs ✔️
------------------------------------------------------------------------
- [ ] PNLD2023-022_Lampião... Era o cavalo do tempo atrás da besta da vida ✔️
- [x] PNLD2023-025_Onde moram as coisas ✔️
- [x] PNLD2023-026_Caminhando, eu vou! (Flávia Savary) ✔️
- [x] PNLD2023-027_Figurinha carimbada (Camila Werner) ✔️
- [x] PNLD2023-028_Mr. Phillow é um fantasma! ✔️
- [x] PNLD2023-030_As aventuras do barão de Munchausen ✔️
- [x] PNLD2023-031_As coisas ✔️
- [x] PNLD2023-032_Conversando com varejeiras azuis ✔️
- [x] PNLD2023-033_Cultura ✔️
- [x] PNLD2023-034_Os doze trabalhos de Hércules ✔️
- [x] PNLD2023-035_Esconde-esconde ✔️
------------------------------------------------------------
- [ ] PNLD2023-004_Artimanhas de Pedro Malazartes
- [x] PNLD2023-024_O cavalo de ébano
- [x] PNLD2023-029_O plano da Emília e outros textos
- [x] PNLD2023-036_O reino do meio da tarde
- [x] PNLD2023-037_O galo Gogó
- [ ] PNLD2023-038_O reizinho que só falava sim

```tex
\usepackage{pdfpages}
\includepdf[nup=2x2, 				% grid
			%offset=-15mm -5mm, 	% posição
			scale=.8, 				% tamanho da página
            delta=4mm 4mm, 			
            frame,
            pages={1-4}]{test.pdf}

% Mais info: https://www.physik.tu-cottbus.de/physik/tp1/nutzer/doc/texmf/latex/pdfpages/pdf-ex.tex
```

```tex
\usepackage{pagecolor}
\pagecolor{yellow!30!orange}  % Mais info: https://tex.stackexchange.com/questions/82498/change-background-colour-for-entire-document

```

```tex
\usepackage[printwatermark]{xwatermark}
%\newwatermark[pagex=2]{\includegraphics{testc.png}}
%\newwatermark[oddpages]{\includegraphics{test.png}}
%\newwatermark[evenpages]{\includegraphics{testb.png}}

```

Diminuir o tamanho do arquivo em pdf.
```shell
ps2pdf input.pdf output.pdf

This also directly works on PDFs, as suggested in the comments.
Some users also report more success when using the ebook settings as follows:
ps2pdf -dPDFSETTINGS=/ebook input.pdf output.pdf

```
