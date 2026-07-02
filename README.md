A list of OMERO instances that want to be part of the OMERO registry.

The goal is to map OMERO instances and facilitate reporting and collaboration.

Participation is voluntary and free.

If you want to add your OMERO instance to the registry, please fill in the fields that you would be comfortable with sharing and open a pull request.

The only required fields are `name`, `institution`, `country_code` and `access_type`. All other fields are optional.

Fields:

- `name` - A name for the OMERO instance (MANDATORY)
- `country_code` - ISO 3166-1 alpha-2 country code for the institution (MANDATORY)
- `access_type` - public, private, internal, mixed or unknown (MANDATORY)
- `omero_web_url` - url for the OMERO web client of the resource
- `info_url` - some url documenting the existence of the OMERO instance
- `institution` - institution responsible for the instance (MANDATORY
- `institution_ror` - ROR identifier for the institution
- `start_year` - roughly the year the instance started operating
- `end_year` - if applicable, roughly the year the instance stopped operating
- `contact_person` - name of a contact person for the instance
- `contact_person_orcid` - ORCID identifier for the contact person
- `notes` - any additional notes about the instance)
- `tags` - a list of tags. lowercase, no spaces

The controlled vocabulary for `access_type` is:

- `public` - the instance is meant to be publicly accessible and is open to anyone
- `private` - the instance is meant to be private, but it is reachable via login over the public internet
- `internal` - the instance is meant to be private and is only reachable from within a specific network (e.g. a university or company)
- `mixed` - the instance has both public and private components
- `unknown` - the access type is unknown

# Safety and privacy

The registry is a public resource. Please do not include any sensitive information in the registry.

In particular, if you want your OMERO.web url to _not_, please leave the `omero_web_url` field empty.
