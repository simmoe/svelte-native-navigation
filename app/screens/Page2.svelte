<flexboxLayout class='flex-centered'>
    <label class='h1 text-center' text='page 2' />
    <button on:tap={()=>selectedTab=0} text='page 1'/>
</flexboxLayout>

<script>
    export let selectedTab 
</script>
