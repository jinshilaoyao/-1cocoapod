# -1cocoapod

swift 使用cocoapod引入框架
文件名:Podfile
platform :ios, '8.0'

target ‘ibve’ do
use_frameworks!

pod "AFNetworking"
pod "SDWebImage"
pod "YYModel"
pod "FMDB"
pod "SVProgressHUD"
pod "pop"

end
