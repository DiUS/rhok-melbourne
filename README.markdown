Make sure submodules are checked out already:

```git submodule update -i```

Requirements
- Ruby
- Bundler

## To run:

```bundle install```

> NB: if using rbenv or similar you may need to run `rbenv rehash` to get mr-sparkle to work.

```mr-sparkle config.ru```

It should now be running accessible at `http://localhost:8080`

## To deploy:

Compress the whole repo, scp to server, deploy.sh.
