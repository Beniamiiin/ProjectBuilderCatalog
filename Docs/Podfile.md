# Default podfile

```
platform :ios, '10.0'
use_frameworks!

target 'PROJECT_NAME' do
	# Rx
	pod 'RxSwift', '~> 4.4.0'
	pod 'RxCocoa', '~> 4.4.0'

	# DI
	pod 'Swinject', '~> 2.5.0'
	pod 'SwinjectStoryboard', '~> 2.1.0'

  	# Networking
	pod 'Moya/RxSwift', '~> 12.0.1'

	# Helpers
	pod 'UIColor_Hex_Swift', '~> 4.2'
end
```