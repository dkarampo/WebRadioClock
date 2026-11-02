📻 Web Radio, Clock & Weather Dashboard
A simple browser-based dashboard that turns an old tablet into a clock, weather display and internet radio player.

I originally built this to replace an old internet radio device that had finally stopped working.

The story
For years I had a small web radio device at home.

It could play internet radio stations, and when I wasn't listening to anything it would display the time and local weather.

Eventually, the weather service stopped working because the service provider behind it was no longer available. There was no way to manually configure another provider.

Some time later, the radio itself also stopped working.

After trying several ways to bring it back to life, I decided it was finally time to let it rest.

There was one small problem...

I had become so used to having a clock in that particular spot that I kept looking there to check the time, only to find an empty space.

Then I remembered that I had an old 10-inch Android tablet that I hadn't used for a long time.

Instead of buying another internet radio, I decided to give the tablet a new job.

With the help of AI, and despite having no coding experience, I created this simple HTML-based dashboard.

✨ Features
🕐 Clock and date
Displays the current time and date, making the tablet useful even when the radio isn't playing.

🌤️ Local weather
Displays local weather information alongside the clock.

📻 Internet radio
Add and listen to your favorite web radio stations directly from the dashboard.

↕️ Reorder stations
Radio stations can be rearranged so you can keep your favorites where you want them.

💾 Export stations
Your station list can be exported so it can be moved or backed up and used on another device.

🖥️ Full-screen mode
The dashboard can automatically enter full-screen mode after the first button is pressed.

This behavior can be disabled in Settings.

📡 Google Cast support
When connected to a home network with Google Cast devices, the radio can be cast to compatible speakers.

This is particularly useful with a Google Home setup where multiple speakers can be used together.

🔄 Cast recovery
During testing, I found that after stopping a Cast session it wasn't always possible to start casting again.

As a workaround, using the Cast / Stop Cast button to stop casting refreshes the page, allowing a new Cast session to be started.

📱 What I use it on
My original setup is:

An old 10-inch tablet
Android 10
Connected permanently to my home Wi-Fi
Positioned where my old internet radio used to be
The idea is simple: rather than throwing away an older tablet that is still perfectly usable, turn it into a dedicated home information and radio display.

🚀 Getting started
Download the HTML file from this repository and open it on the device you want to use.

The project is designed around a single-page dashboard, making it practical for an old tablet that can remain in one location and act like a dedicated appliance.

Some functionality may depend on the browser, device permissions, network configuration, weather service and Cast environment being used.

📻 Radio stations
You can maintain your own list of internet radio stations.

Stations can be:

Added
Reordered
Exported for backup or transfer to another device
Actual radio stream compatibility depends on the stream and browser being used.

📡 Casting
The dashboard includes support for casting the radio to Google Cast devices.

In my setup, this allows me to send the radio to speakers in my Google Home environment rather than relying on the tablet's built-in speaker.

Known Cast behavior
There is a known issue where stopping a Cast session can prevent another Cast session from starting correctly.

The current workaround is intentional:

Stopping Cast also refreshes the page.

After the refresh, casting can be started again.

⚙️ Full-screen behavior
By default, full-screen mode can start automatically after the first interaction with the dashboard.

If you don't want this behavior, it can be disabled in Settings.

💡 Why this project exists
This isn't intended to be a complicated media center.

It simply replaces three things I used every day on my old internet radio:

🕐 Time + 🌤️ Weather + 📻 Radio

The difference is that I now have something I can modify myself instead of depending entirely on services built into a discontinued device.

It also gave an old Android tablet a useful second life instead of leaving it in a drawer.

⚠️ Known limitations
Cast behavior depends on the browser/device and Google Cast environment.
Restarting Cast after stopping it currently requires the automatic page refresh described above.
Internet radio streams can change or disappear over time.
Weather functionality depends on the external weather service used by the page.
Behavior may differ between browsers and Android versions.
🛠️ Built with
HTML
CSS
JavaScript
AI-assisted development
I am not a software developer. This project started as a personal solution to a small problem at home and evolved as I added features that I found useful.

🤖 AI-assisted project
This project was created with the assistance of AI.

I started without coding experience and used AI to help create the original HTML page and progressively add functionality such as full-screen mode, station management and casting.

It's a good example of how an old piece of hardware and a simple idea can become something useful again.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
