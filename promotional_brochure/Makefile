pdf:   brochure-0.pdf brochure-1.pdf

brochure-0.pdf: brochure-0.png
	convert brochure-0.png brochure-0.pdf

brochure-1.pdf: brochure-1.png
	convert brochure-1.png brochure-1.pdf

brochure-0.png: Makefile brochure.svg
	inkscape -e brochure-0.png -b ffffffff -d 300 --export-id=page1_rect brochure.svg

brochure-1.png: Makefile brochure.svg
	inkscape -e brochure-1.png -b ffffffff -d 300 --export-id=page2_rect brochure.svg

clean:
	rm -f temp.png brochure.png brochure-0.png brochure-1.png brochure-0.pdf brochure-1.pdf brochure.pdf

.PHONY: pdf

