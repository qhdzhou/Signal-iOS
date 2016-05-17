platform :ios, '8.0'

target 'Signal' do
  pod 'SignalServiceKit',           :git => 'https://github.com/WhisperSystems/SignalServiceKit.git'
  pod 'OpenSSL',                    '~> 1.0.208'
  pod 'PastelogKit',                '~> 1.3'
  pod 'FFCircularProgressView',     '~> 0.5'
  pod 'SCWaveformView',             '~> 1.0'
  pod 'DJWActionSheet'

  pod 'JSQMessagesViewController',  :git => 'https://github.com/WhisperSystems/JSQMessagesViewController', :commit => 'e5582fef8a6b3e35f8070361ef37237222da712b'

  target 'SignalTests' do
    inherit! :search_paths
  end
end
