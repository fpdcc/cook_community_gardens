# Cook County Community Gardens

<img src="https://travis-ci.org/fpdcc/cook_community_gardens.svg?branch=master">


### A collaborative list of Community Gardens in Cook County, IL

### [The Map](CommunityGardens.geojson)

## License

CC-BY-SA

## How to contribute

1. Fork the project
2. Add or edit a location by editing and following the format in `CommunityGardens.geojson`
3. Submit a pull request

## Validating the geoJSON

When you submit a pull request, it will automatically check to ensure your geoJSON is valid.

If you'd like to check yourself, you can run `./script/cibuild` locally, or pasting the contents of `CommunityGardens.geojson` into http://geojsonlint.com.

## How to find the lat/long of a location

http://geocoder.us/.


thanks to [benbalter/dc-wifi-social](https://github.com/benbalter/dc-wifi-social) for the improved repo with geojson validation script
