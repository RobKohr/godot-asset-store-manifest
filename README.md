## My amazing bridge building asset

This is a made up asset to show how to create an asset with a manifest file for easily importing into http://godotasset.store

### Manifest properties

#### title
To show at the top of the product page

#### description
A short description to show in the small buy box next to the image previews


#### godotVersion
What is the version of godot that this was developed against

#### icon
Icon image. Defaults to "icon.png" if not set

#### previews (array)
A list of relative paths for images and videos. Also can have urls for youtube videos. If not specified, the previews directory will be scanned and used.

#### details
A relative path to the detailed description for the asset. Defaults to "README.md"

#### price
Price in USD. Set to 0 or don't set at all to set it to be free. Only non-private repos can be free.

#### Tags
A list of tags related to this project. For good suggestions, go to https://godotasset.store/top-tags

#### Branch
The branch to fetch for the most recent updates. Defaults to "master".
