# Uncomment the next line to define a global platform for your project
platform :osx, '10.12'
inhibit_all_warnings!

target 'SwiftV2ray' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwiftV2ray
  pod 'Swifter', '~> 1.3.3'
  pod 'XCGLogger', '~> 6.0.1'
  
  post_install do |installer|
      # Your list of targets here.
      myTargets = ['Swifter']
      
      installer.pods_project.targets.each do |target|
          if myTargets.include? target.name
              target.build_configurations.each do |config|
                  config.build_settings['SWIFT_VERSION'] = '3.2'
              end
          end
      end
  end

end

target 'SwiftV2ray Preference' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SwiftV2ray Preference

end
