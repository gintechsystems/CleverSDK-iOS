platform :ios, "9.0"

inhibit_all_warnings!

target "CleverSDK" do
  
  pod "PocketSVG", "~> 0.7"
  pod "SmartWKWebView", :git => "https://github.com/gintechsystems/SmartWKWebView.git"
  
  target "CleverSDKTests" do
    inherit! :search_paths

    pod "Specta", "~> 1.0"
    pod "Expecta", "~> 1.0"
  end

  target "Example" do
    inherit! :search_paths
  end
end
