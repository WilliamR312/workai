<script context="module" lang="ts">
    export type calendar = {id: number, title: string, description: string, startingDate: Date, endate: Date};
    let JeanKul = [{id: 666, title:"Fuck some moms", description: "grosse folle"},
                    {id: 69, title:"Will baise avec Nathan des daronnes et Kévin filme", description: "je suis une catin"}]
</script>

<p>
  {#each JeanKul as pig}
    <li>{pig.title} -> {pig.description}</li>
  {/each}
</p>

<div></div>