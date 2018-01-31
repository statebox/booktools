# What is this

Sources for a docker image

	https://hub.docker.com/r/statebox/booktools/

Docker image with

- minimalistic LaTeX environment (`texlive` + some fonts and bla)
- `pandoc`
- `latexmk`
- `ghostscript` and `imagemagick` to convert PDF to PNG
- Python bindings `pandocfilters`

Some other stuff, look at the `Dockerfile`.

## Usage

You can pull this image from dockerhub

	docker pull statebox/booktools

## Development

This image is automatically build by `hub.docker.com` on each commit,
but you can run this to build the docker image manually:

	docker build -t statebox/booktools .

To push the updated image to `hub.docker.com`:

	docker push


