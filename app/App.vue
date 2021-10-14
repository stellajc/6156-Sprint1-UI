<template>
  <div>
    <h3 class="p-3 text-center">Vue HTTP GET Requests with Fetch</h3>
    <get-request/>
    <get-request-async-await/>
    <get-request-error-handling/>
    <get-request-set-headers/>
  </div>
</template>

<script>
import GetRequest from "./GetRequest";
import GetRequestAsyncAwait from "./GetRequestAsyncAwait";
import GetRequestErrorHandling from "./GetRequestErrorHandling";
import GetRequestSetHeaders from "./GetRequestSetHeaders";

export default {
  name: "app",
  components: {
    GetRequest,
    GetRequestAsyncAwait,
    GetRequestErrorHandling,
    GetRequestSetHeaders
  }
};
</script>
