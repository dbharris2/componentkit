apple_library(
  name = 'ComponentKit',
  deps = [],
  preprocessor_flags = [
    '-fobjc-arc',
    '-fno-objc-arc-exceptions',
    '-Qunused-arguments',
  ],
  exported_headers = glob([
    'ComponentKit/**/*.h',
    'ComponentTextKit/**/*.h',
  ]),
  srcs = glob([
    'ComponentKit/**/*.m',
    'ComponentKit/**/*.mm',
    'ComponentTextKit/**/*.m',
    'ComponentTextKit/**/*.mm',
  ]),
  frameworks = [
    '$SDKROOT/System/Library/Frameworks/CoreGraphics.framework',
    '$SDKROOT/System/Library/Frameworks/CoreText.framework',
    '$SDKROOT/System/Library/Frameworks/Foundation.framework',
    '$SDKROOT/System/Library/Frameworks/QuartzCore.framework',
    '$SDKROOT/System/Library/Frameworks/UIKit.framework',
  ],
  visibility = ['PUBLIC'],
)

