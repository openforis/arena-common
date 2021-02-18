# arena-common

## how to publish a new version?

### Prerequisites 
1. Create a token:

	`Github > Settings > Dev settings > Personal access tokens > Generate new token`

2. `.npmrc` file:
	```
    @openforis:registry=https://npm.pkg.github.com
	_authToken = TOKEN
	always-auth = true
	```
3. `.yarnrc` file:	

	```
	"@openforis:registry" "https://npm.pkg.github.com"
	```
    
### Publish the package

`yarn publish`


## How to use the package?

To use the package a Github token is needed, to create and configure one follow the steps into Prerequisites.
