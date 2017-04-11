# ideas
A collection of fun ideas for further refinements and implementation

1. Everdoc

   persistent documentation for everyday things. Take a picture of your things with your phone, feed through object recognition, return matches served from popular cloud storage providers, or allow user to upload documentation if no matches.

2. Low-cost IP Cam

   Proprietary IP camera can quickly become outdated as standards change, vendor dropping support, or have security implications when a found-bug is not patched. Use Raspberry Pi (low cost, standardized, well documented) and web standards (TCP/IP, WIFI, Power-Over-Ethernet, REST, WebRTC) to achieve interpretability and compatibility with other devices

3. RemoteKeys

   Play a MIDI instrument from anywhere. Play a synthesizer or player piano remotely on a MIDI keyboard connected to a Web MIDI-enabled browser, and pipe the resulting audio / stream the video back to the player via WebRTC. Todo: address latency problems

4. BLE (Bluetooth Low Energy) MIDI Router / Hub

   For times where creative flow excludes laptop computers, a handy box to route / merge (sum) / thru (pass-along) MIDI info received from various BLE-MIDI-enabled controllers, sound modules, and more. Capable of self-appoint or designating a specific MIDI device as the MIDI master clock. Low power consumption and simple to use.
   
5. DogEar

   A device that notifies you when an ultrasonic sound of sufficient amplifitude is heard, records it, and option to play it back at a lower, audible pitch. For detection of device communication tones that are too high-pitched for the human ear to detect.

6. FatTrack
   
   Implement data persistance and wireless data sync (Google Sheets, API call) for the Omron scale to remove complexity in logging weight and body fat % numbers.
   
7. Feel It In Your Bonez

   Tactile-based low frequency transducence for portable electronics. Although their small size limits the size of speakers that can be installed, allocating a portion of the spectral energy as moment of the enclosure may better convey information such as bass drum, beats, or perhaps SFX such as explosions in a small device.
   

8. Rainbow Seeker

   Software mechanism to detect continuous spectral chroma (color) change from red to purple in an image or document. It should be agnostic to the direction of the chroma gradient such as left-to-right, down-to-up, etc.

9. VelociKey (Visual MIDI)

   Browser-based webapp to display MIDI information visually. Original conceived purpose is to display velocity magnitude as integer or a histogram graph, utlizing MIDI over BLE. This allows for testing of MIDI controllers at a music store and obtain information about a said MIDI controller (velocity curve, polyphonic aftertouch, etc) simply by using a mobile phone, instead of needing to ask the clerk to hook the controller up to one of the in-store computers.


10. Password lifespan allowance based on password complexity

   Instead of setting arbiturary limit of 6-12 characters, 1 uppercase, 1 lowercase, 1 number, and picking an answer for those pesky challenge-response questions like "What is your mother's maiden name" and "name of your first boy/girlfriend," I enforce a mandatory expiration date for that password. The length of its life time will be based on your password's difficulty.

* Poor, easy-to-guess passwords: results in a shorter life
* Strong, difficult-to-guess passwords: results in a longer life



### Maybe's

1. Method to detect a raster image's original, lower native resolution

  * Uses
    * can be used to thwart sites that cheats Google Image search results who rescaled / resampled a lower-resolution image onto a larger canvas
    * can be used to determine what is the minimum canvas size needed to retain original image's details
  * Challenges
    * Todo: Test for "reasonable" sharpness? (e.g. large image but lacking in details expected)
    * Todo: Test for smallest "sharp" feature?
    * Todo: Test for digital compression artifact visible on enlarged image?
