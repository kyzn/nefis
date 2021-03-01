This is hugo repository for [nef.is](https://nef.is/). Generated content (published) can be found in `/docs` folder.

## Quick notes

- Testing locally

      hugo server

- Testing locally with posts with future date

      hugo server --buildFuture

- Then go to

      http://localhost:1313/

- Generate `docs/` and commit

      rm -rf docs/ && hugo -d docs/ && echo -n "nef.is" > docs/CNAME && git add docs/ && git commit -m "generate docs"

- Add a new recipe (as page)

      hugo new my-new-recipe.md


## Installing hugo

- Install hugo

      brew install hugo

- Verify hugo version

      hugo version
