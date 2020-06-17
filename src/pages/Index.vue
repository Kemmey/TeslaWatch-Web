<template>
  <Layout>
    <section id="container-centre" class="column centre flex-1">
      <h1 class="page-title">Watch for Tesla</h1>
      <div class="content">
        <p>
          Convenience on the wrist.
        </p>

        <figure class="mt-10 md:mt-20"><img src="complications.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="ChargeLimit.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Context.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Controls1.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Controls2.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Keyless.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Main_Alt.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Main.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="MainControls.png"/></figure>
        <figure class="mt-10 md:mt-20"><img src="Temps.png"/></figure>
        
        <h2 class="text-3xl">Convenience</h2>
        <P>Convenience on the wrist - Watch for Tesla is the ideal companion in day to day life with your Tesla vehicle. These are just a few of the day to day conveniences this app will help achieve:</P>
        <ul class="mb-12 list-disc pl-4">
          <li>When charger is connected, use the force touch menu to unlock the charge port. No matter the vehicles lock-state, the charge port will unlock and allow the cable to be disconnected. If the vehicle is charging, charging will automatically be stopped first. You no longer have to wait around in the rain for your vehicle to detect your Bluetooth phone - just tap the unlock port button on your way to the vehicle, pull the charging cable and drive away. </li>
          <li>Add the graphic corner complication to your watch face and enjoy the convenience of having easy access to state of charge, charging indicator, time remaining if charging, sentry mode active indicator and indicator if any windows, doors or trunks are open. All from one complication, that also will launch the app when tapped. </li>
          <li>During and after charge, a panel will show how much energy was added. Convenient if you schedule your charge during the night - wake up each morning and easily check how much energy was added to the battery. </li>
          <li>If you have multiple vehicles on your account, tap the vehicle name to quickly and easily switch between them. </li>
          <li>Customize the app background with a custom photo of your own vehicle. Advanced users may use the option to add url querystring parameters from the active vehicle to automatically switch backgrounds based on vehicle options. </li>
          <li>You can queue up commands by tapping on buttons, then put your wrist down and the commands will execute in the background when the vehicle is successfully woken up. </li>
          <li>When you tap the unlock vehicle button, the charge port will also unlock if a charging cable is attached. That's convenience right there!</li>
          <li>Want to reduce phantom drain? Background updates can be configured to longer intervals between updates or to only update if car is already awake or can be disabled entirely for absolutely zero impact on phantom drain.</li>
          <li>A warning panel will show up if any doors, windows or trunks are left open. Conveniently, you can tap the panel to close any open windows.</li>
          <li>Need to access the frunk? Just do it from your wrist - no fiddling with your phone. </li>
          <li>Sitting comfy in the couch, but just remembered you have a road-trip in the morning? Set the charge limit to 100% - or any value really - and start charging, right from the convenience of your wrist!</li>
          <li>Leaving the office after a long hot day? Activate the HVAC when you're on your way, and enjoy a nice cool vehicle.</li>
          <li>Your significant other needs to enter the vehicle but refuses to install the Tesla app for Bluetooth key? Just unlock the car from your wrist - choose your battles wisely. Personal developer experience may apply.</li>
          <li>When charging, tap the time remaining label to switch to show time of expected completion - no more head calculus!</li>
          <li>Need to run a quick errand, but you don't have your phone? Unlock your vehicle from your wrist, then activate keyless drive and off you go. Just please be mindful that this feature requires internet connectivity on both watch and vehicle - so don't drive into the desert and leave your vehicle, or you'll get stuck there!</li>
        </ul>
        <h2 class="text-3xl">Features</h2>
        <ul class="mb-12 list-disc pl-4">
          <li>Turn HVAC on/off</li>
          <li>Open frunk or trunk</li>
          <li>Lock/unlock car - when unlocking and charger is attached, charge port is also unlocked</li>
          <li>Open/close charge port</li>
          <li>Set charge limit</li>
          <li>Start/stop charging if cable attached</li>
          <li>Set HVAC temperatures</li>
          <li>Toggle Sentry mode</li>
          <li>Vent / close the windows</li>
          <li>Flash the lights or honk the horn</li>
          <li>Activate or deactivate the defroster</li>
          <li>Show current vehicle location in Maps app</li>
          <li>Tap the large battery icon to switch to a smaller icon showing soc in percent next to current range - and as a bonus, an indicator if Sentry is active</li>
          <li>Units in app reflect choices in the active vehicle - celsius/fahrenheit, km/mi, SoC in percent or range</li>
          <li>Activate primary Homelink device if within reach of vehicle</li>
          <li>Show charge time remaining or tap to show estimated time of completion</li>
          <li>Keyless drive. This can be enabled in settings from the about screen. This optional feature require that you enter your Tesla account password into the app. Your password will be stored safely in the WatchOS Keychain. Please read the disclaimer about keyless drive - never drive without a backup key as you WILL risk getting stranded if either watch or vehicle is without internet connectivity!</li>
          <li>If you have multiple vehicles, tap vehicle name to choose active vehicle</li>
          <li>Complication showing current SoC and indicator if charging and charge time remaining. This will poll car for data every hour when disconnected or every 15 minutes if actively charging. These background updates can be disabled from the about screen, accessed from the bottom of the main interface by tapping the app logo</li>
          <li>Tip Jar as In-App purchase. This does not enable extra functionality in the app, but serve solely to allow kind souls to give donations to the developer should you find the app to be useful. </li>
          <li>Localized in the following languages</li>
          <ul>
            <li>English</li>
            <li>German</li>
            <li>Danish</li>
            <li>Swiss German</li>
            <li>Dutch</li>
          </ul>
        </ul>
        <h2 class="text-3xl">A note about security and privacy</h2>
        <p>This app accepts two types of login. Either Tesla account credentials or a Tesla API token. Your account credentials are by default not stored in the app, but are used only once to obtain an authentication token and refresh token directly from the Tesla API server. If you would rather supply that token yourself, you can do so instead. It is preferable to supply a refresh token, as the app will then have a perpetual login. Your token will be persisted in the app. Tokens will be revoked if you change your Tesla account password. With the optional keyless drive feature you can choose to store your password in the app - it will be securely stored in the watchOS keychain. This feature is optional and is not required for all other features to function. No network traffic will ever be emitted from this app that goes anywhere other than directly to the Tesla API servers. The source code for this application will at all times be made available to any security researcher for a voluntary security and safety audit.</p>
        <h2 class="text-3xl">Disclaimer</h2>
        <p>This app is not endorsed by Tesla Inc. Use at your own risk. No guarantee of proper function is given. Only you are responsible for any changes to your car caused by using this app.</p>
        <h2 class="text-3xl">Bugs, feature requests and other issues</h2>
        <p>Please use the public issue tracker for this app on <a href="https://github.com/Kemmey/Kemmey-TeslaWatch-Public/issues" target="_blank">GitHub</a> to report bugs and feature requests and vote for upcoming features.</p>
        <p><a href="https://apps.apple.com/us/app/id1512108917" target="_blank"><img src="Download_on_the_App_Store_Badge_US.svg"/></a></p>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  }
};
</script>
