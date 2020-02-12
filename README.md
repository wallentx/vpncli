# vpncli
Command line OpenVPN wrapper written in bash that supports multiple profiles, MFA, and push auth.

Add `vpncli` to your `$PATH`. You will need to manually create the profile directories/files on your machine at `$HOME/.vpncli/profile/YOUR_PROFILE`. Included in this repo is an example `$PROFILE_PATH` and `$PROFILE` that you can use as a reference.

```
Description:  Connect to a VPN that requires a MFA token, and automatically pass OTP.
              Supports multiple VPN profiles/connections.
              Password can be provided instead of OTP with modification of this script.

      Usage:  vpncli [-h] [-d] [-l] [-p <PROFILE_NAME>] [-s <PROFILE_NAME>]

      Where:  -h  show this help text
              -d  disconnect from VPN
              -l  list profiles
              -p  connect using the specified profile
              -s  set the default VPN profile to use (current default: example-profile)"
```
