# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'podCache' do
  use_frameworks!
  plugin "cocoapods-binary-cache"
  
  config_cocoapods_binary_cache(
    cache_repo: {
      "default" => {
        "remote" => "git@github.com:JiamingZhou02/podCache.git",
        "local" => "~/.cocoapods-binary-cache/prebuilt-frameworks"
      }
    },
    prebuild_config: "Debug"
  )

  # Pods for podCache
    pod 'Alamofire', '5.4.4', :binary => true

  target 'podCacheTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'podCacheUITests' do
    # Pods for testing
  end

end
