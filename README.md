# Grafana Tutorials

[![License](https://img.shields.io/github/license/grafana/grafana)](LICENSE)

| Environment | URL                                                                 |
| ----------- | ------------------------------------------------------------------- |
| Production  | https://storage.googleapis.com/grafana-tutorials-prod/index.html    |
| Staging     | https://storage.googleapis.com/grafana-tutorials-staging/index.html |

Grafana Tutorials are step-by-step guides that help you make the most of Grafana.

![Screenshot](screenshot.png)

## Requirements

Tutorials are built using [claat](https://github.com/googlecodelabs/tools/tree/master/claat):

```
go get github.com/googlecodelabs/tools/claat
```

## Usage

To build tutorials and landing site altogether:

```
make
```

## Development

After running `make`, run a web server inside the `public` directory:

```
cd public/
python -m SimpleHTTPServer
```

## Resources

- [Google Codelabs Tools](https://github.com/googlecodelabs/tools)
- [Google Developer Codelabs](https://codelabs.developers.google.com/)
- [Ubuntu Tutorials](https://tutorials.ubuntu.com/)
