# SublimePackages

Repository to store my "package_control.json" for all my packages including forked packages


## Package Control: ChannelRepositoryTools

Use [ChannelRepositoryTools](https://packagecontrol.io/packages/ChannelRepositoryTools) to ease the development.


## Content

My `package_control.json` contains:

* `out_of_control.json` : List of packages (mine or others) that are not included in Package Control main channel
* `patched_repository` : List of packages that are patched, in PR pending or not

Legacy
* `repository.json` : List of my packages
* `forked_repository.json` : List of forked packages


## Settings

In `Package Control.sublime-settings` (User)

In release
```
{
	"installed_packages":
	[
		...
	],
	"repositories":
	[
		"https://raw.githubusercontent.com/Starli0n/SublimePackages/master/package_control.json"
	]
}
```

In development
* There is no need of those json files as the repositories are cloned directly
* The `installed_packages` should not contains cloned repository
