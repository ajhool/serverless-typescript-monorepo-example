# serverless-typescript-monorepo-example
An example repo for managing several lambda/serverless typescript functions in a monorepo alongside common libraries. 

## Goals
 [ ] Run build / package / deploy / test commands from the parent/top-level directory.
 
 [ ] Run build / package / deploy / test commands from each individual function.
 
 [ ] Enable lambda functions to depend on common libraries, which can be imported as npm packages
 
 [ ] The user should be able to publish these common libraries as npm packages, but they shouldn't need to
 
 [ ] Provide a Serverless example as well as AWS specific templates.
 
 [ ] Webpack or similar bundler for tree-shaking and minified deployment package
 
 [ ] Incremental / cached build. Only build the packages that have changed since the last build. Note: this doesn't currently include incremental packaging, which might be doable but is not currently supported.

## Non-goals
 - Not a generator
 - Does not detect the status of deployed functions relative to local code. This would be nice to have, though...
 - Incremental packaging.
 
