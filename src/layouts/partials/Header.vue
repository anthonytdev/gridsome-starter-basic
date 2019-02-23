<template>
  <header class="alt">
    <g-link to="/"><span class="logo"><g-image src="@assets/images/logo.svg" alt="" /></span></g-link>
    <h1>{{ $static.metaData.siteName }}</h1>
    <p>Just another free, fully responsive site template<br />built by <a href="https://twitter.com/ajlkn">@ajlkn</a> for <a href="https://html5up.net">HTML5 UP</a>.</p>
	</header>
</template>

<script>
export default {
  name: 'Header-layout'
}
</script>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>
