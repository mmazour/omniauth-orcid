## v.1.2.2 (November 6, 2016)

[onmiauth-orcid 1.2.2](https://github.com/datacite/omniauth-orcid/releases/tag/v.1.2.2) was released on November, 2016 with the following changes:

* changed default member scopes to `/read-limited /activities/update /person/update`
* upgrade to new `codeclimate-test-reporter` workflow

## v.1.2.1 (September 4, 2016)

[onmiauth-orcid 1.2.1](https://github.com/datacite/omniauth-orcid/releases/tag/v.1.2.1) was released on September 3, 2016 with the following changes:

* fixed missing scope. Scope can be manually set via `param[:scope]`.
* polished rspec tests

## v.1.1.5 (August 11, 2016)

[onmiauth-orcid 1.1.5](https://github.com/datacite/omniauth-orcid/releases/tag/v.1.1.5) was released on August 11, 2016 with the following changes:

* compatibility with omniauth-oauth2 1.4.0. Thanks to pull request [#7](https://github.com/datacite/omniauth-orcid/pull/7) by [eleanorakh](https://github.com/eleanorakh).

## v.1.1.4 (May 14, 2016)

[onmiauth-orcid 1.1.4](https://github.com/datacite/omniauth-orcid/releases/tag/v.1.1.4) was released on May 14, 2016 with the following changes:

* default scope depends on member status, `/authenticate` for non-members and `/orcid-profile/read-limited /orcid-works/create /orcid-bio/external-identifiers/create /affiliations/create /funding/create` for members

* added `/orcid-bio/external-identifiers/create /affiliations/create /funding/create` to the default scope

## v.1.0 (July 25, 2015)

[onmiauth-orcid 1.0](https://github.com/datacite/omniauth-orcid/releases/tag/v.1.0) was released on July 25, 2015 with the following changes:

* changed default scope to `authenticate`, and use the public API `https://pub.orcid.org` by default. These settings work for non-members.
* added `name` and `email` to the `info` hash returned by omniauth (`email` will be empty in almost all cases)
* cleaned up documentation in `README.md`
