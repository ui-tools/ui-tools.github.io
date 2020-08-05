# Autoreverb for Soundcraft Ui24R

## What does the Autoreverb app do?

Autoreverb app changes Pre-delay and Decay parameters of the Reverberation depending on the current BPM.
It works with Soundcraft Ui24R mixer only.

## Where can I find it?

## Do I need an internet connection to use it?

No, Autoreverb works offline. You need the internet connection only when you open the link the first time.

## How to get rid of the address bar and get more space on the screen?

1. Press Add To Home Screen menu item in your browser
2. Find Autoreverb for Ui24R in your apps and start it

## I have opened the app, how to use it?

1. Set the IP address of your mixer if needed.
2. Press Connect
3. Choose the Effect Slot you want to control: FX1 or FX2.
4. Go to the Ui24R control panel and ensure, that for chosen FX:
    * FX type is Reverb
    * FX preset name contains word auto (e.g.: "myautopreset", "MyAutoPreset", "auto", "Large Hall Auto", etc.)

    > If at least one of these conditions is not met, AutoBypass mode turns on (no data is being sent to the mixer).

5. Turn off Bypass button
6. Choose Total Reverb and Pre-delay duration.
    > Decay = Total Reverb Time - Pre-delay

## What is "Pre-delay limit handler"?

The maximum Pre-delay of UI24R Reverb is limited to 50ms.

For example, optimal Pre-delay for "Large Room" (4/4 note) is 1/64 note. At 60 bpm it is 62.5 ms.

We have two options:

* **Divide:**  If Pre-delay is longer than 50 ms, it is divided by 2 recursively.
* **Max:** If Pre-delay is longer than 50 ms, 50 ms is set.

## How to save settings?

The settings are saved automatically.

## Can I start two instances of Autoreverb to control both FX1 and FX2?

It's tricky for now. It would work only if you use the apps on different devices or browsers.

## Can I use Autoreverb to control FX4 (Room)?

Not yet, maybe in future versions.
