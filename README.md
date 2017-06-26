# solargraph-utils

A Node package for interacting with the Solargraph rubygem.

## Example

    import SolargraphServer from 'solargraph-utils';
    let server = new SolargraphServer();
    server.start();
    server.suggest('Str', 0, 3).then((response) => {
        console.log("The server's response: " + response);
    });
    server.stop();