FROM python:3.12.3-alpine
RUN python -m pip install jsonschema 'referencing-loaders>=0.3.1'
COPY lintsonschema /usr/local/bin
COPY schemas /schemas
CMD ["/usr/local/bin/lintsonschema"]
