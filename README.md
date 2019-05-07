# ![LOGO](logo.png) rv **flow**ground Connector

## Description

A generated **flow**ground connector for the rv API (version 1.1).

Generated from: https://api.apis.guru/v2/specs/sheetlabs.com/rig-veda/1.1/swagger.json<br/>
Generated at: 2019-05-07T17:44:01+03:00

## API Description

This API returns information about all of the verses in Rig Veda. The results are JSON objects that contain the name of the god, poet, and meter of the verses in Rig Veda, the category of the god and the poet, and the mandal and sukta number.

## Authorization

This API does not require authorization.

## Actions

### Fetch all records from the database

### Fetch all verses in a specific book

#### Input Parameters
* `mandal` - _required_ - Click to select the mandal number from the list.
    Possible values: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10.

### Fetch all verses composed in a specific meter

#### Input Parameters
* `meter` - _required_ - The name of the meter. Wildcard characters allowed, for example *tri

### Fetch all verses composed by a specific rishi

#### Input Parameters
* `sungby` - _required_ - The name of the rishi. Wildcard characters allowed, for example *mitra

### Fetch all verses composed by a specific category of beings

#### Input Parameters
* `sungbycategory` - _required_ - Click to select from the list.
    Possible values: animal, demon male, divine female, divine male, human female, human male.

### Fetch all verses addressed to a specific god, goddess, or object

#### Input Parameters
* `sungfor` - _required_ - The name of the god, goddess, or object. Wildcard characters allowed, for example *dra

### Fetch all verses composed for a specific category

#### Input Parameters
* `sungforcategory` - _required_ - Click to select from the list.
    Possible values: abstract, animal, demon male, divine female, divine human, divine male, human couple, human female, human male, human unborn, object, plant.

## License

**flow**ground :- Telekom iPaaS / sheetlabs-com-rig-veda-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
