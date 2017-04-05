# Uncomment the next line to define a global platform for your project
platform :ios, '10.1'
abstract_target 'test' do
pod 'AFNetworking'

target 'FoodTracker' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for FoodTracker
  pod 'Bugtags'
  target 'FoodTrackerTests' do
    inherit! :search_paths
    # Pods for testing
    pod 'Bugtags'
  end

end
end
