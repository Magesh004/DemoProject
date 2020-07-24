# Uncomment the next line to define a global platform for your project
# platform :ios, '10.0'


 use_frameworks!
workspace 'DemoWorkspace.xcworkspace'

# PROJECT COCOAPODS DEPENDNECY FILES
target 'Application' do
    project './Application/Application.xcodeproj' 
    pod 'FrameworkDemo',:path => "/Users/administrator/Desktop/Zee5Demo/FrameworkDemo/FrameworkDemo.podspec"

  target 'ApplicationTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'ApplicationUITests' do
    # Pods for testing
  end

end

# FRAMEWORK COCOAPODS DEPENDNECY FILES
target 'FrameworkDemo' do
    project './frameworkDemo/FrameworkDemo.xcodeproj' 
    
end
