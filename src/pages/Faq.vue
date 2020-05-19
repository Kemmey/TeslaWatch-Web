<template>
  <Layout>
    <section id="container-centre" class="column centre flex-1">
      <h1 class="page-title">Frequently asked questions</h1>
      <div class="content">
        <h2 class="text-3xl">How to get a Tesla API authentication token?</h2>
        <p>Use this Apple Shortcuts shortcut to obtain a Tesla API token using nothing but first-party software. You can modify the shortcut and grab the "refresh_token" value instead in order to have a perpetual login in the watch: <a href="https://shareshortcuts.com/shortcuts/256-tesla-access-token.html">https://shareshortcuts.com/shortcuts/256-tesla-access-token.html</a></p>
        <h2 class="text-3xl">I bought the app, but it is not installing to my watch?</h2>
        <p>Try opening the AppStore on your watch - scroll all the way to the bottom and tap on "Account" then on "Purchased" then on "My purchases" (skip this step if not enrolled in an Apple family account) and then find the app and tap on the cloud icon - the app should install then. When finished, tap on open to open up the app.</p>
        <p>Also ensure that your Apple Watch has been updated to at least WatchOS 6.2.</p>
        <h2 class="text-3xl">Should I use username and password or token to login?</h2>
        <p>You can either login with your username and password - or you can login with an auth token. You only need one or the other. The auth token is a bit of a nerd/paranoid-feature where you can generate the authentication token for the Tesla API yourself and supply just that, knowing that the app will never have seen your Tesla username and password</p>
        <h2 class="text-3xl">How do I paste the token to my watch?</h2>
        <p>On the Apple Watch, tap the token input field and then tap on the keyboard icon. If your phone or ipad is on do not disturb, please manually check notification center for a Continuity Keyboard notification. When you tap on the notification there is no way to do the normal tap to get menu to paste - you have to use the new shortcut on iOS 13 where you do a three-finger-tap and then a menu will appear at the top of your screen. There you will now find the paste icon. Tap that to paste your token and then check on your watch that the token has indeed been input to the field.</p>
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
