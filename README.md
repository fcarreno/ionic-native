This is a fork of the ionic-native repo [https://github.com/ionic-team/ionic-native](https://github.com/ionic-team/ionic-native)

Meant to adapt existing plugin wrappers with custom features (v3).  

Changes to the plugins cab be performed directly from `/src/@ionic-native/core/plugins/[pluginName]`

Once the changes are made, `npm run build [pluginName/s]` can be used to generate the distributable files that can be imported from ionic projects...  
(will be available under `dist/@ionic-native/[pluginName]`) 

NOTE: the project includes a v3 branch, which was created from an ionic-native commit hash which generates distributable wrapper files compatible with v3.
For latest ionic-native dev/build process, use master branch.


