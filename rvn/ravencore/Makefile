all:
	git clone https://github.com/OverstockMedici/ravencore
	cd ravencore && git checkout master
	cd ravencore && rm -rf .git # Delete .git folder to reduce space
	cd ravencore && npm install --production
	rm -rf ravencore/node_modules/ravencore-node/bin/*.gz
	rm -rf ravencore/node_modules/ravencore-node/bin/ravencoin-*/bin/raven-qt
	rm -rf ravencore/node_modules/ravencore-node/bin/ravencoin-*/bin/test_raven
	rm -rf ravencore/node_modules/ravencore-node/test/*

clean:
	rm -fr ravencore
