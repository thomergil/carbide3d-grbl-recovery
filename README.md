# Recover from a GRBL reset on a Carbide 3D CNC machine
I did something dumb and managed to completely screw up my [Carbide 3D Nomad 3 CNC](https://shop.carbide3d.com/products/nomad-3?variant=32912906354749) machine, which is otherwise awesome. (I managed to do this with [bCNC](https://github.com/vlachoudis/bCNC), which is also otherwise awesome.)

This is what Carbide 3D support told me to do.

**This has been tested and verified for the Nomad 3 only**.

1. Download Carbide Motion v5 from https://carbide3d.com/downloads/

   (Copies of these installer images are also in this repo, but use those only as a last resort.)
1. Install
1. Connect to Cutter
1. Go to Settings
1. Go to the Machine tab
1. Press the "Send Configuration Data" tab
1. Turn the machine off
1. Close Carbide Motion
1. Install the latest version of Carbide Motion from https://carbide3d.com/downloads/
1. Press "Setup New Machine"
1. Choose your machine from the dropdown
1. Press "Next"
1. Press "Connect to Machine"
1. Press "Initialize Machine"

Continue with the Setup Process. You are now back in business.
