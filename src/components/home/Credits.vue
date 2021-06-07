<template>
  <div>
    <div class="credits">
      Project maintained by
      <a href="https://github.com/rajkale99">raj Kale</a>
    </div>
    <div class="credits">
      Website developed by
      <a href="https://github.com/andersonmendess">andersonmendess</a>
    </div>
        <div class="container" style="width:100%">
      <center>
        <script
          type="application/javascript"
          async
          src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"
        ></script>
        <ins
          class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-1677966849218512"
     data-ad-slot="9256395884"></ins>
        <script type="application/javascript">
          (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
      </center>
    </div>
    <div id="adBottom">
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- download bottom -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-1677966849218512"
     data-ad-slot="1730167184"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
</div>
  </div>
</template>
<script>
import Search from "../common/Search.vue";

export default {
  name: "Credits",
  components: {
    Search
  },
  data() {
    return {
      credits: [
        {
          title: 'Project maintained by',
          value: 'Raj Kale',
          url: 'https://github.com/rajkale99',
        },
        {
          title: "Website Originally developed by",
          value: "andersonmendess",
          url: "https://github.com/andersonmendess"
        }
      ]
    };
  }
};
</script>
