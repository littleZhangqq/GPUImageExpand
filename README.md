# GPUExpand

[![CI Status](https://img.shields.io/travis/892750407@qq.com/GPUExpand.svg?style=flat)](https://travis-ci.org/892750407@qq.com/GPUExpand)
[![Version](https://img.shields.io/cocoapods/v/GPUExpand.svg?style=flat)](https://cocoapods.org/pods/GPUExpand)
[![License](https://img.shields.io/cocoapods/l/GPUExpand.svg?style=flat)](https://cocoapods.org/pods/GPUExpand)
[![Platform](https://img.shields.io/cocoapods/p/GPUExpand.svg?style=flat)](https://cocoapods.org/pods/GPUExpand)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements
ios 10.0
使用   pod 'GPUExpand', '~> 1.0.1'来安装即可。
说明：
    使用原生的GPUimage框架可以做到很多事情，比如录制视频，添加水印滤镜等等，不过有个缺陷。在录制的时候选择暂停。调用moviewriter的pause方法后，摄像头可以继续捕捉画面但是视频流还在添加到回调的buffer中，说明这个pause方法没起到作用。而videocamera的stopcamera方法或者pause方法都会使摄像头暂停，不符合产品需求。
    在stackoverflow上有个老外重写了GPUimage，改变了这一现象，现在我把它集成到自己的pod中上传到Github，各位有这个需求的可以直接下面的使用方法用pod安装即可。当然我的项目中只针对这一处改动有需求。别的滤镜类和效果类没怎么用到，是否和原来的GPUimage有太大区别不清楚。
    且用着看吧各位

## Installation

GPUExpand is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'GPUExpand', '~> 1.0.1'
```

## Author

892750407@qq.com, [892750407@qq.com]

## License

GPUExpand is available under the MIT license. See the LICENSE file for more info.
