<script>
  export let jp;
  export let en;
</script>

<div class="container">
  <div>
    <span class="jp">
      {@html jp }
    </span>
  </div>
  <div>
    <span class="en">
      { en }
    </span>
  </div>
</div>

<style>
.container {
  background-color: antiquewhite;
  color: black;
  padding: 4px 8px;
  text-align: center;
  margin: 8px;
  border-radius: 8px;
}
.en {
  font-size: 1.2rem;
  font-weight: 200;
  font-style: italic;
}
.jp {
  font-size: 1.8rem;
  font-weight: 200;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
</style>