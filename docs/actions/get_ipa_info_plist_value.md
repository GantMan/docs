# get_ipa_info_plist_value


Returns a value from Info.plist inside a .ipa file




> This is useful for introspecting Info.plist files for .ipa files that have already been built.


get_ipa_info_plist_value |
-----|----
Supported platforms | ios, mac
Author | @johnboiles
Returns | Returns the value in the .ipa's Info.plist corresponding to the passed in Key



**1 Example**

```ruby
get_ipa_info_plist_value(ipa: "path.ipa", key: "KEY_YOU_READ")
```





**Parameters**

Key | Description
----|------------
  `key` | Name of parameter
  `ipa` | Path to IPA




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action get_ipa_info_plist_value
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/get_ipa_info_plist_value.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>
