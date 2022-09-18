<script>
  import Word from "../components/Word.svelte";
  import Words from "../components/Words.svelte";
  import Examples from "../components/Examples.svelte";
</script>

<h1>Adverbes</h1>
<h2>Adverbes de manière</h2>
<Words>
  <Word jp={"ゆっくり"} en={"lentement"}/>
  <Word jp={"しっかり"} en={"fermement"}/>
  <Word jp={"きちんと"} en={"soigneusement"}/>
</Words>
<Examples>
  <Word jp={`祖母は<span class="emp">ゆっくり</span>話す`} en={"My grandmother speaks slowly"}/>
</Examples>
<h2>Adverbes de degré</h2>
<Words>
  <Word jp={"とても"} en={"très"}/>
  <Word jp={"もっと"} en={"encore plus"}/>
  <Word jp={"かなり"} en={"assez"}/>
</Words>
<Examples>
  <Word jp={`祖母は<span class="emp">とてもゆっくり</span>話す`} en={"My grandmother speaks very slowly"}/>
</Examples>
<h2>Adverbes de quantité</h2>
<Words>
  <Word jp={"たくさん"} en={"beaucoup"}/>
  <Word jp={"いっぱい"} en={"plein"}/>
</Words>
<Examples>
</Examples>
<h2>Adverbes de temps</h2>
<Words>
  <Word jp="ずっと" en="constamment"/>
  <Word jp="すぐ" en="immédiatement"/>
  <Word jp="間もなく [まもなく]" en="sous peu"/>
</Words>
<h2>Adverbes de fréquence</h2>
<Words>
  <Word jp={"時々 [ときどき]"} en={"de temps en temps"}/>
  <Word jp={"すぐ"} en={"souvent"}/>
  <Word jp={"いつも"} en={"toujours"}/>
</Words>
<Examples>
  <Word jp={`オタコンは時々コーヒーを飲む`} en={"Otacon boit de temps en temps du café"} />
</Examples>