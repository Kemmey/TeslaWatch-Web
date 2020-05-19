<template>
  <Layout>
    <section id="container-centre" class="column centre flex-1">
      <h1 class="page-title">Watch app for Tesla</h1>
      <div class="content">
        <p>
          Simple app for Tesla vehicles.
        </p>
        <P>Check in on your vehicle, monitor charge state, unlock doors or charge port, activate HVAC preconditioning and set charge limit. Just the things you might need on a daily basis from your wrist - nothing less, nothing more - in a simple and intuitive interface.</P>
        <h2 class="text-3xl">Features</h2>
        <ul class="mb-12 list-disc pl-4">
          <li>HVAC on/off</li>
          <li>Open frunk or trunk</li>
          <li>Lock/unlock car - when unlocking and charger is attached, charge port is also unlocked</li>
          <li>Open/close charge port</li>
          <li>Set charge limit</li>
          <li>Start/stop charging if cable attached</li>
          <li>If you have multiple vehicles, tap vehicle name to choose active vehicle</li>
          <li>Complication showing current SoC and indicator if charging and charge time remaining. This will poll car for data every hour when disconnected or every 15 minutes if actively charging. These background updates can be disabled from the about screen, accessed from the bottom of the main interface by tapping the app logo</li>
        </ul>
        <h2 class="text-3xl">A note about security and privacy</h2>
        <p>This app accepts two types of login. Either Tesla account credentials or a Tesla API token. Your account credentials are never stored in the app, and are used only once to obtain an authentication token and refresh token directly from the Tesla API server. If you would rather supply that token yourself, you can do so instead. It is preferable to supply a refresh token, as the app will then have a perpetual login. Your token will be persisted in the app. Tokens will be revoked if you change your Tesla account password.</p>
        <h2 class="text-3xl">Disclaimer</h2>
        <p>This app is not endorsed by Tesla Inc. Use at your own risk. No guarantee of proper function is given. Only you are responsible for any changes to your car caused by using this app.</p>
        <h2 class="text-3xl">Bugs, feature requests and other issues</h2>
        <p>Please use the public issue tracker for this app on <a href="https://github.com/Kemmey/Kemmey-TeslaWatch-Public/issues">GitHub to report bugs and feature requests and vote for upcoming features.</a></p>
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
