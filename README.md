# cymotest.github.io

### The task at hand is to research the flagship product by Dental Hygiene company "SmarTeeth", which is "the future of toothbrushes".
### 'SmarTeeth' proudly state that the device comes built-in with an immutable secret from the factory and enhances its security further by acquiring a stronger secret when first initialized. They also state that all external communications are encrypted.

After initial research we were able to extract two strings (one from each device you have). We are not sure what it is, but we believe it contains some kind of unique ID for the device:

Device Serial Number (as provided on the manufacturer sticker) | Acquired secret
--- | ---
A7R38T | eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b290YnJ1c2hfaWQiOiJTbWFyVGVldGgtUHJvLUE3UjM4VCJ9
A9K3ZZ | eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b290YnJ1c2hfaWQiOiJTbWFyVGVldGgtUHJvLUE5SzNaWiJ9.VerC8eIpKidetYKthGNOmsHMYcpRjVqhS_IZOs_xTO4

We also found a URL that is expected to be the device backend: https://what-sould-be-here
Your Goal:
Your goal is to research the security procedures the device conducts against the backend, and think of potential ways to circumvent them, or gain higher privileges.
Expect to reveal secrets or find ways to trick the backend into thinking you are something you are not.
