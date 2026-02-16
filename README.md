 Nimbus                                                        
                                                                                
  A native macOS Rainmeter-compatible skin engine. Runs Rainmeter skins         
  on macOS without modification.
                                                                                
  Requires macOS 14.0+                                                          
                                                                                
  Installation                                                                  
                                                                                
  1. Download Nimbus.app from this repo
  2. Open Terminal and run:

  xattr -cr ~/Downloads/nimbus-tester-build-only-main/Nimbus.app && chmod +x
  ~/Downloads/nimbus-tester-build-only-main/Nimbus.app/Contents/MacOS/nimbus-gui

  3. Double-click Nimbus.app to launch

  Why is step 2 needed? The app is ad-hoc signed (no Apple Developer ID), so
  macOS Gatekeeper blocks it on download. The terminal command clears the
  quarantine flag and restores the executable permission that Git strips.

  Permissions (IMPORTANT)

  On first launch, (if you choose to add monstercat or similar skins that need acesss to spotify, 
  now playing, etc) macOS will prompt you for Screen Recording permission. This
  is required for the audio visualizer to capture system audio via process taps.
   Grant it in System Settings > Privacy & Security > Screen Recording.

