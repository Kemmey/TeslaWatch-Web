<template>
  <Layout>
    <section id="container-centre" class="column centre flex-1">
      <h1 class="page-title">Frequently asked questions</h1>
      <div class="content">
        <h2 class="text-3xl">Watch app is logged out and refers to "Companion app not installed"</h2>
        <p>
          ADVISORY: On Friday  29/1-21 Tesla turned off legacy authentication. Now only MFA login will be supported. Impact is that login HAS to happen on iOS and then be transferred to the watch. It is NO LONGER possible to login directly on the watch. Please install the iOS app if missing. Thanks!<br/>

          This will affect all third party apps from Friday going forward that have not updated the login mechanism. <br/>

          Fortunately I did update Watch for Tesla three months ago, but you have to install the iOS companion app, since the login now require the use of a web browser, which is not available on the watch. <br/>

          Please install the app from here - it's the same purchase as the watch app, so not a new or additional purchase. <br/>

          <a href="https://apps.apple.com/dk/app/watch-app-for-tesla/id1512108917">https://apps.apple.com/dk/app/watch-app-for-tesla/id1512108917</a>
        </p>
        <h2 class="text-3xl">I bought the app, but it is not installing to my watch?</h2>
        <p>Try opening the AppStore on your watch - scroll all the way to the bottom and tap on "Account" then on "Purchased" then on "My purchases" (skip this step if not enrolled in an Apple family account) and then find the app and tap on the cloud icon - the app should install then. When finished, tap on open to open up the app.</p>
        <p>Also ensure that your Apple Watch has been updated to at least WatchOS 6.2.</p>
        <h2 class="text-3xl">Should I use username and password or token to login?</h2>
        <p>You can either login with your username and password - or you can login with an auth token. You only need one or the other. The auth token is a bit of a nerd/paranoid-feature where you can generate the authentication token for the Tesla API yourself and supply just that, knowing that the app will never have seen your Tesla username and password</p>
        <h2 class="text-3xl">How do I paste username, password or token to my watch?</h2>
        <p>On the Apple Watch, tap the input field and then tap on the keyboard icon. If your phone or ipad is on do not disturb, please manually check notification center for a Continuity Keyboard notification. When you tap on the notification there is no way to do the normal tap to get menu to paste - you have to use the new shortcut on iOS 13 where you do a three-finger-tap and then a menu will appear at the top of your screen. There you will now find the paste icon. Tap that to paste your username, password or token and then check on your watch that the value has indeed been input to the field.</p>
        <h2 class="text-3xl">My question is not listed here!</h2>
        <p>Please open an issue on the <a href="https://github.com/Kemmey/Kemmey-TeslaWatch-Public/issues" target="_blank">issue tracker</a>, and help will be on it's way as fast as possible!</p>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "FAQ"
  }
};
</script>
