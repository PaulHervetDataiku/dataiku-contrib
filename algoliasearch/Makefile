PLUGIN_VERSION=0.0.6
PLUGIN_ID=algoliasearch

all:
	cat plugin.json|json_pp > /dev/null
	rm -rf dist
	mkdir dist
	zip -r dist/dss-plugin-${PLUGIN_ID}-${PLUGIN_VERSION}.zip code-env plugin.json python-connectors
