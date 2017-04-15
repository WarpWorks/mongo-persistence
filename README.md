# WarpWors/mongo-persistence

MongoDB persistence for WarpJS

## Install

    npm install --save @warp-works/mongo-persistence

## Usage

    const Persistence = require('@warp-works/mongo-persistence');
    const persistence = new Persistence('some-host', 'db-name');

    persistence.documents('collection-name')
        .then(console.log)
        .finally(() => {
            persistence.close();
        });

TODO: Document more.
