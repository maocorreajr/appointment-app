# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'COPApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for COPApp
	pod 'FSCalendar'
	pod 'CalendarKit'
	pod 'DateToolsSwift'
	pod 'Firebase'
	pod 'Firebase/Auth'
	pod 'Firebase/Database'
pod 'Firebase/Firestore'
pod 'Firebase/Core'
	pod 'Firebase/Storage'
	pod 'FirebaseUI'
	pod 'Firebase/Messaging'
	pod 'SVProgressHUD'
post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings.delete('CODE_SIGNING_ALLOWED')
        config.build_settings.delete('CODE_SIGNING_REQUIRED')
    end
end
end
