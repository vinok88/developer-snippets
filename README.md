# developer-snippets
Collection of commands that will require for developers in day to day life

## OSGI Commands

`ls` - list component services and their state

`comp` <id> - component info
  
`ss` - list all the already installed bundles

`b <bundle id from ss>` - get bundle info

`headers <bundle Id>` - get the manifest.mf headers

`p org.wso2.training.osgi` - find the bundle that exported this bundle

`<Private-Package>org.wso2.training.internal</Private-Package>` - Include this in bundle config of pom.xml. This allows to copy the package into the bundle even it is not exported.

`diag <bundle_id>` - show the unresolved packeges

`uninstall <Bundle_id>` - uninstall a bundle

`services` - list all services
