- Introduction
  
  This test is a perfomance test via Apptim.
  
- Test Strategy

  To ensure that our app delivers optimal performance, we utilized Apptim. Apptim is a powerful tool for monitoring and analyzing app performance. Using this platform, we     were able to test various aspects of our app and conduct measurements and you can use Apptim during development to improve your app performance and identify potential        issues in three areas:
  - Device resource usage (cpu, memory, battery consumption, etc.)  
  - User Experience (rendering times, events or actions response time)
  - App crashes (code exceptions or crashes due to intense resource usage)
    
  We were using it with the Desktop version. The app was running on an emulator, so we already know that the performance test won’t reach its highest potential.
  The specifications from the device were one cpu core and 2 gb RAM running on Android 13.
  
- Test Plan

  We would like to test:
    - CPU
    - Memory
    - Render
    - Network
    - Storage
      
- Test Cases

  
- Test Results
  
  We assume that the average FPS problem comes from using an emulator, we are trying to get a physical device to figure that out.
  (picture of the results are in the current folder "apptim_screen")

- Metrics

  ("apptim2_screen" in the current folder)

- Recommendations

  This software helped us testing our perfomance. It would be even better in the next step if we test the perfomance on a real hardware device.

- Conclusion

  The testing was good, the results were not bad too. But as we already mentioned, the test would be even better on a real hardware device to detect
  if the average FPS problem has something to do with the emulator or not. But nevertheless we are happy that we did this test via Apptim.
