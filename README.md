# supply-chain-linters-user

Experimental code for learning. Do not use.


Example golang command line tool that prints hello world.

In the next commit it uses a third party dependency version
that makes a network request to https://example.com/not-good

Useful to test a tool which can detect new syscalls being used.


The different components of this experiment/proof of concept...

- https://github.com/illume/supply-chain-linters the action and golang boilerplate
- https://github.com/illume/supply-chain-linters-user user of the linters, and the dependency
- https://github.com/illume/supply-chain-linters-dependency a dependency for testing that adds a network request



