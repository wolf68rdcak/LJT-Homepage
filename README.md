# Junteng Liu's Academic Homepage

Personal academic website forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io). The upstream theme and MIT license are retained.

## Content

- `_config.yml`: identity, profile links, and site URL
- `_pages/about.md`: biography, interests, education, experience, and honors
- `_pages/publications.html`: six publications with authors, years, and venues
- `_pages/cv.md`: academic CV
- `_data/navigation.yml`: primary navigation

Content was populated from saved profile information. The dated 'first-year' description was omitted. MINIMAX is described by its February 2025 start date because its current end date is not known. No paper URLs, PDF CV, or additional awards were invented. The avatar uses the saved public GitHub identity, Vicent0205; wolf68rdcak owns this repository.

## Publishing

In Settings > Pages, select Deploy from a branch, then `master` and `/ (root)`. Once deployment succeeds, the configured URL is https://wolf68rdcak.github.io/academicpages.github.io/ . Deployment has not been verified.

The existing `wolf68rdcak.github.io` repository was left unchanged. To move this site to that root address, first resolve the repository-name conflict, then update `repository` and set `baseurl` to an empty string.

## Local Preview

Install Ruby and Bundler, then run `bundle install` and `bundle exec jekyll serve`. Upstream sample publications, posts, talks, teaching, and demonstration pages remain in source but are excluded from site output.
