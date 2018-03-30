
If you want to run Solr under Docker, you should use the latest version.
See https://hub.docker.com/_/solr/

If for some reason you have to run a legacy Solr 4, you could use the example
here as a base for building your own image. It is not supported though, there
will be no updates, and there is no build for it on Docker hub.

To build:

```
docker build -t solr4 .
```

To run:

```
docker run -P solr4
```
