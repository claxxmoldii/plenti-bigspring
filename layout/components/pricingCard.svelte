<script>
  export let plans;
</script>

<div class="col-lg-4 mb-5 mb-lg-0 px-3 pr-3 px-lg-0">
  <div class="card shadow">
    <div class="card-body text-center py-5">
      <h3 class="mb-4">{plans.title}</h3>
      <span class="price">{plans.price}</span><span class="perMonth">/month</span>
      <p class="lead">{plans.bestfer}</p>
      <ul class="list-unstyled mb-5">
        <li>yeah...</li>
      </ul>
      <a href="/" class="btn btn-outline-primary">Get started for free</a>
    </div>
  </div>
</div>
