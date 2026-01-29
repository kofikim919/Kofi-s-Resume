docker build -t latex .
docker run --rm -i -v "$PWD":/data latex kofi_kim_resume.tex
