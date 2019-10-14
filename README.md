# Usage

1. Replace `/Users/kevin/work/src/github.com/kelda-inc/magda-web-server/src`
   with the path to your magda-web-server repo.

2. Run `docker-compose up`.

3. Access the app at `localhost:8080`.

4. Changes made to Magda are automatically synced.

5. Clean up with `docker-compose down`.

Note that you need permissions to pull the Magda images on your laptop. i.e.
`docker pull gcr.io/magda-221800/magda-web-server:0.0.50-2` should work.
